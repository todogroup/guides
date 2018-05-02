# Using Open Source Code

One of the most important responsibilities of an open source program office is ensuring that your organization meets its legal obligations when integrating open source code with proprietary and third-party source code in your commercial products.

You need to establish guidelines on how developers can use open source code, and detailed processes to track where open source code is coming from, how it’s licensed, and where it ultimately ends up. This guide gets you started with a baseline compliance program for using, releasing, and distributing open source code.

**Contents**

1. [Why track and review code](#why-track-and-review-code)
2. [Compliance roles and responsibilities](#compliance-roles-and-responsibilities)
3. [A simple policy for using open source code](#a-simple-policy-for-using-open-source-code)
4. [Five-stage code review process](#5-stage-code-review-process)
5. [What to do after v1.0](#what-to-do-after-v10)
6. [Sample open source usage request form](#open-source-usage-request-form)
7. [Final words](#final-words)
8. [Architecture diagram template](#architecture-diagram-template)

## Why track and review code?

Simply stated, if your company isn’t tracking how and where its developers use open source code, you're at risk of non compliance with applicable open source licenses – this can be an expensive path to go through both in terms of legal fees and engineering time spent to correct the error. Ignoring your open source legal obligations also has repercussions for your company’s reputation in the open source community.

An open source program office helps centralize policies and decision-making around open source consumption, distribution, and release, tracks code provenance and use, and ensures the organization doesn’t run afoul of its compliance obligations.

Ideally, your open source program includes a complete compliance program, developed with the help of your legal counsel. In this guide, we’ll cover one important aspect of your compliance program: your policy and processes for using, releasing, and distributing open source code.

> “A well-designed open source compliance process should simultaneously ensure compliance with the terms of open source licenses and also help companies protect their own intellectual property and that of third-party suppliers from unintended disclosure and/or other consequences.” – [Ibrahim Haddad](https://twitter.com/ibrahimatlinux), Vice President of R&D and Head of the Open Source Group at Samsung Research America

There are several benefits companies can experience from maintaining an open source compliance program:

* **Gain a technical advantage.** Since compliant software portfolios are easier to service, test, upgrade, and maintain.
* **Identify crucial pieces of open source code.** You’ll discover what code is in use across multiple products and parts of your organization, and/or are highly strategic and beneficial to your open source strategy.
* **Demonstrate the costs and risks associated with using open source components.** This is easier to see when code goes through multiple rounds of review.
* **Build community trust.** In the event of a compliance challenge, such a program can demonstrate an ongoing pattern of acting in good faith.
* **Prepare for a possible acquisition, sale, or new product or service release.** This is a less common ways benefit, but compliance assurance is a mandatory practice before the completion of such transactions.
* **Build credibility in the supply chain.** You can improve compliance across your software supply chain, dealing with OEMs and downstream vendors.

## Compliance roles and responsibilities

Within your open source program you’ll want to create a designated open source compliance team that’s tasked with ensuring open source compliance.

The core team, often called the auditing team or the Open Source Review Board (OSRB), consists of representatives from engineering and product teams, one or more legal counsel, and the Compliance Officer (who is typically the open source program manager).

Other individuals across multiple departments also contribute on an ongoing basis to your open source compliance efforts: documentation, supply chain, corporate development, IT, localization and the Open Source Executive Committee (OSEC) which oversees the overall open source strategy. But unlike the core team, members of the extended team are only working on compliance on a part-time basis, based on tasks they receive from the OSRB.

The OSRB is in charge of creating an open source compliance strategy and a set of processes that determine how a company will implement these rules on a daily basis. The strategy establishes what must be done to ensure compliance and offers a governing set of principles for how employees interact with open source software. It includes a formal process for the approval, acquisition, and use of open source, and a method for releasing software that contains open source or that’s licensed under an open source license.

## A simple policy for using open source code

The usage policy is an essential component of any compliance program. This set of rules is included in your open source strategy document (you have one, right?) and made available to everyone for easy reference.The usage policy is an essential component of any compliance program. This set of rules is included in your open source strategy document (you have one, right?) and made available to everyone for easy reference.

The usage policy ensures that any software (proprietary, third-party, or open source) that makes its way into the product base has been audited, reviewed, and approved. It also ensures that your company has a plan to fulfill the license obligations resulting from using the various software components, before your products make it to customers.

There is no need to make a lengthy or complicated document. A good open source usage policy includes six simple rules:

* Engineers must receive approval from the OSRB before integrating any open source code in a product.
* Software received from third parties must be audited to identify any open source code included, which ensures license obligations can be fulfilled before a product ships.
* All software must be audited and reviewed, including all proprietary software components.
* Products must fulfill open source licensing obligations prior to customer receipt.
* Approval for using a given open source component in one product is not approval for another deployment, even if the open source component is the same.
* All changed components must go through the approval process.

## 5-stage code review process

Once you have a policy in place, you must plan and create a process that makes it easy to apply the policy. Your job is to grease the wheels for developer use of open source and contribution to open source projects.

> “If your code review process is overly burdensome, you’ll slow innovation or provide a good excuse for developers to circumvent the process completely.” – [Ibrahim Haddad](https://twitter.com/ibrahimatlinux), Vice President of R&D and Head of the Open Source Group at Samsung Research America

The process begins by scanning the source code of the software package in question, then moves on to identifying and resolving any discovered issues, performing legal and architectural reviews, and making a decision regarding the usage approval.

The diagram described below illustrates a simplistic view of a compliance usage process. In reality, the process is much more iterative in nature. Keep in mind that these phases are for illustration purposes and may need to be modified depending on your company’s own needs and open source program configuration.

Let’s walk through each stage in the process.

### Stage 1: Source Code Scan

In the source code scanning phase, all the source code is scanned using a specialized software tools (there are many commercial vendors that offer such tools in addition to a couple open source alternatives).

This phase typically kicks off when an engineer submits an online usage form. (See the link to the sample usage form and rules for using it, below.) The form includes all the information about the open source component in question, and specifies the location of the source code in the source code repository system.

The form submission automatically creates a compliance ticket in a system such as JIRA or Bugzilla and a source code scanning request will be sent to the designated auditing staff.

Periodic full platform scans should also take place every few weeks to ensure that no open source software component has been integrated into the platform without a corresponding form. If any was found, then a JIRA ticket is automatically issued and assigned to the auditing staff.

Some of the factors that can trigger a source code scan include:

* An incoming usage form, usually filled out by engineering staff.
* A periodically scheduled full platform scan. Such scans are very useful for uncovering open source code that snuck into your software platform without a usage form.
* Changes in a previously approved software component. In many cases, engineers start evaluating and testing with a certain version of an OSS component, and later adopt that component when a new version is available.
* Source code is received from a third-party software provider who may or may not have disclosed open source.
* Source code is downloaded from the web with an unknown author and/or license, which may or may not have incorporated open source code.
* A new proprietary software component enters the build system where engineering may or may not have borrowed open source code and used it in a proprietary software component.

After the code is scanned, the scanning tool produces a report that provides information on:

* Known software components in use, also known as the software Bill of Materials (BoM)
* Licenses in effect, license texts, and summary of obligations
* License conflicts to be verified by legal
* File inventory
* Identified files
* Dependencies
* Code matches
* Files pending identification
* Source code matches pending identification

#### Note on Downloaded Open Source Packages

It is vital to archive open source packages downloaded from the web in their original form. These packages will be used in a later stage (prior to distribution) to verify and track any changes introduced to the source code by computing the difference between the original package and the modified package.

If a third-party software provider uses open source, the product team integrating that code into the product must submit an open source usage form describing the open source to be used. If the third-party software provider only provides binaries, not source code, then the product team and/or the software supplier manager who manages the relationship with the third-party software provider must obtain a confirmation (for instance, a scan report) that there is no open source in the provided software.

### Stage 2: Identification and Resolution

In the identification and resolution phase, the auditing team inspects and resolves each file or snippet flagged by the scanning tool.

For example, the scanning tool’s report can flag issues such as conflicting and incompatible licenses. If there are no issues, then the compliance office will move the compliance ticket forward to the legal review phase.

If there are issues to be resolved, then the compliance officer creates subtasks within the compliance tickets and assigns them to the appropriate engineers to be resolved. In some cases, a code rework is needed; in other cases it may simply be a matter of clarification. The sub-tasks should include a description of the issue, a proposed solution to be implemented by engineering, and a specific timeline for completion.

The compliance officer may simply close the subtasks once all issues are resolved and pass the ticket along for legal review. Or they might first order a re-scan of the source code and generate a new scan report confirming that earlier issues do not exist anymore. Once they're satisfied that all issues are resolved, the compliance officer forwards the compliance ticket to a representative from the legal department for review and approval.

In preparation for legal review, you should attach all licensing information related to the open source software to the compliance ticket, such as COPYING, README, LICENSE files, etc.

### Stage 3: Legal Review

In the legal review phase, the legal counsel (typically a member of the open source review board, or OSRB) reviews reports generated by the scanning tool, the license information of the software component, and any comments left in the compliance ticket by engineers and members of the auditing team.

When a compliance ticket reaches the legal review phase, it already contains:

* A source code scan report and confirmation that all the issues identified in the scanning phase have been resolved.
* Copies of the license information attached to the ticket: typically, the compliance officer attaches the README, COPYING, and AUTHORS files available in the source code packages to the compliance ticket. Other than the license information, which for OSS components is usually available in a COPYING or a LICENSE file, you need to also capture copyright and attribution notices as well. This information will provide appropriate attributions in your product documentation.
* Feedback from the compliance officer regarding the compliance ticket (concerns, additional questions, etc.).
* Feedback from the engineering representative on the auditing team or from the engineer (package owner) who follows/maintains this package internally.

The goal of this phase is to produce a legal opinion of compliance, and a decision on the incoming and outgoing license(s) for the software component in question. The incoming and outgoing licenses are in the plural form because in some cases, a software component can include source code available under different licenses. There are three possible outcomes at this stage:

#### No issues with compliance

If there are no issues with the licensing, the legal counsel would then decide on the incoming and outgoing licenses of the software component and forward the compliance ticket one step further in the process into the compliance architectural phase.

The incoming license is the license under which you received the software package. The outgoing license is the license under which you are licensing the software package. In some cases, when the incoming license is a permissive license that allows relicensing (e.g., BSD), companies will relicense that software under their own proprietary license. A more complex example would be a software component that includes proprietary source code, source code licensed under License-A, source code that is available under License-B, and source code available under License-C.During legal review, the legal counsel will need to decide on the incoming and outgoing license(s):

Incoming licenses= Proprietary License + License A + License B + License C
Outgoing license(s) = ?

#### Issues with compliance

If a licensing issue is found, such as mixed source code with incompatible licenses, the legal counsel will flag these issues and reassign the compliance ticket in JIRA to engineering to rework the code.

For example, legal review may uncover that closely held intellectual property has been combined with an open source code package. Legal counsel will flag this and re-assign the compliance ticket to engineering to remove the proprietary source code from the open source component. In the event that engineering insists on keeping the proprietary source code in the open source component, the open source executive committee (OSEC) will have to release the proprietary source code under an open source license.

#### Unclear issues with compliance

In some cases, if the licensing information is not clear or if it is not available, the legal counsel or engineering staff members contacts the project maintainer or the open source developer to clarify the ambiguities and to confirm under which license that specific software component is licensed.

### Stage 4: Architecture Review

In the architecture review, the compliance officer and an engineering representative on the auditing team or open source review board perform an analysis of the interaction between the open source, proprietary, and third-party code. This is accomplished by examining an architectural diagram (see an example, below) that identifies:

* Open source components (used “as is” or modified)
* Proprietary components
* Components originating from third-party software providers
* Component dependencies
* Communication protocols
* Other open source packages that the specific software component interacts with or depends on, especially if it is governed by a different open source license.

The result of the architecture review is an analysis of the licensing obligations that may extend from open source to proprietary or third-party software components (and across open source components as well).

If the compliance officer discovers any issues, such as a proprietary software component linking to a GPL licensed component, the compliance officer forwards the compliance ticket to engineering for resolution. If there are no issues, then the compliance officer moves the ticket to the final stage in the approval process.

### Stage 5: Final Review

The final review is usually a face-to-face meeting of the auditing team or open source review board (OSRB) during which the team approves or rejects the usage of the software component.

The team bases its decision on the complete compliance record of the software component, which includes the following:

* A source code scan report generated by the scanning tool.
* The list of discovered issues, information on how they were resolved, and who verified that these issues were successfully resolved.
* Architectural diagrams and information on how this software component interacts with other software components.
* Legal opinion on compliance, and decision on incoming and outgoing licenses.
* Dynamic and static linkage analysis, if applicable in an embedded environment (C/C++).

In most cases, if a software component reaches the final review, it will be approved unless a condition has presented itself (such as the software component is no longer in use). Once approved, the compliance officer will prepare the list of license obligations for the approved software component and pass it to appropriate departments for fulfillment. This can include:

* Updating the software inventory to reflect that the specific OSS software component version x is approved for usage in product y, version z.
* Issuing a ticket to the documentation team to update end user notices in the product documentation, to reflect that open source is being used in the product or service.
* Triggering the distribution process before the product ships.

The compliance officer tracks all open tickets and ensures their completion by the time the product ships or service launches.

For a more detailed usage process and possible scenarios, see our ebook [Open Source Compliance in the Enterprise](https://www.linuxfoundation.org/publications/open-source-compliance-enterprise/).

## What to do after v1.0

Initial compliance, also called baseline compliance, happens when development starts, and continues until the release of the first version of the product. The compliance team identifies all open source code included in the software baseline, and drives all of the source components through the five-stage approval process outlined above.

> “It’s important to remember that open source compliance doesn’t stop with version 1.0.” – [Ibrahim Haddad](https://twitter.com/ibrahimatlinux), Vice President of R&D and Head of the Open Source Group at Samsung Research America

You will also need to develop an incremental compliance process to check in on the source code once the product ships. This process starts when development begins on a new branch that includes additional features and/or bug fixes.

Incremental compliance is the process by which compliance is maintained when product features are added to the baseline version 1.0. Incremental compliance requires a comparatively smaller effort as opposed to the efforts involved in establishing baseline compliance. But several challenges can arise. You must correctly identify the source code that changed between version 1.0 and version 1.1, and verify compliance on the delta between the releases:

* New software components may have been introduced.
* Existing software components may have been retired.
* Existing software components may have been upgraded to a newer version.
* The license on a software component may have changed between versions.
* Existing software components may have code changes involving bug fixes or changes to functionality and architecture.

The obvious question is: How can we keep track of all of these changes? The answer is simple: a bill of material difference tool (BOM diff tool). Given the BOM for product v1.1 and the BOM for v1.0, we compute the delta and the output of the tool is the following:

* Names of new software components added in v1.1
* Names of updated software components
* Names of retired software components

With this information in hand, achieving incremental compliance becomes a relatively easy task:

* Enter new software components into the five-phase usage approval process.
* Compute a line-by-line diff of the source code in changed software components, and decide if you want to scan the source code again or rely on the previous scan.
* Update the software registry by removing the software components that are not used anymore.

The diagram described below provides an overview of the incremental compliance process. The BOM file for each product release is stored on the build server. The BOM diff tool takes two BOM files as input, each corresponding to a different product release, and computes the delta to produce a list of changes as previously discussed.

At this point, the compliance officer will create new compliance tickets for all new software components in the release, update compliance tickets where source code has changed and possibly re-pass them through the process, and finally update the software registry to remove retired software components from the approved list.

### Open source usage request form

Completing the open source usage request form is an important step when developers bring open source software into your company, and should be taken very seriously.

Developers fill out the online form requesting approval to use a given open source component. The form comprises several questions that will provide necessary information for the auditing team or open source review board, allowing it to approve or disapprove the usage of the proposed open source component.

The table in the sample form available [here](https://github.com/todogroup/policies/blob/master/linuxfoundation/lf_compliance_approval.pdf) highlights the information requested in an open source usage request form. Usually, these values are chosen from a pull-down menu to make the data entry efficient.

There are several rules governing the OSRB usage form, for instance:

* The form applies only to the usage of open source in a specific product and in a specific context. It is not a general approval of the open source component for all use cases in all products.
* The form is the basis of audit activity and provides information the review team needs to verify if the implementation is consistent with the usage plan expressed in the form, and with the audit and architectural review results.
* The form must be updated and re-submitted whenever the usage plans for that specific open source component changes.
* The auditing team or review board must approve the form before engineering integrates the open source into the product build.
* The open source executive committee must approve the usage of any open source package where licensing terms require granting a patent license or patent non-assertion.

## Final words

Open source compliance is an essential part of the software development process. If you use open source software in your product(s) and you do not have a solid compliance program, then you should consider this guide as a call to action.

At its core, open source compliance consists of a set of actions that control the intake and distribution of open source used in commercial products. The result of compliance due diligence is an identification of all open source used in the product (components and snippets) and a plan to meet the license obligations. For a detailed guide to open source compliance download our free ebook, [Open Source Compliance in the Enterprise](https://www.linuxfoundation.org/publications/open-source-compliance-enterprise/) by Ibrahim Haddad.

## Architecture diagram template

An architectural diagram, used in the architecture review phase of the open source review process, illustrates the interactions between the various software components in an example platform. An example template architectural diagram, available [here](https://www.linuxfoundation.org/wp-content/uploads/2017/09/OpenSourceGuideGraphics_V2_G6.png), shows the following:

* Module dependencies
* Proprietary components
* Open source components (modified versus as-is)
* Dynamic versus static linking
* Kernel space versus user space
* Shared header files
* Communication protocols
* Other open source components that the software component in question interacts or depends on, especially if it is governed by a different open source license

## Acknowledgements

Contributors:

**![](https://www.linuxfoundation.org/wp-content/uploads/2017/09/thumb_ibrahim.png)
Ibrahim Haddad**
VP of R&D and Head of the Open Source Group
Samsung Research America

*These resources were created in partnership with the TODO (Talk Openly, Develop Openly) Group – the professional open source program networking group at The Linux Foundation. A special thanks goes out to the open source program managers who contributed their time and knowledge to making these comprehensive guides. Participating companies include Autodesk, Comcast, Dropbox, Facebook, Google, Intel, Microsoft, Netflix, Oath (Yahoo + AOL), Red Hat, Salesforce, Samsung and VMware. To learn more, visit: [todogroup.org](http://todogroup.org/)*
