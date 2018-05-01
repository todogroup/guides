# Shutting Down an Open Source Project

This Open Source Guide is designed to offer advice about how your enterprise and your development team can plan for the day when you are ready to end or move away from an unneeded open source project. By shutting down the project gracefully or by transitioning it to others who can continue the work, your enterprise can responsibly oversee the life cycle of the effort. In this way, you can also set proper expectations for users, ensure that long-term project code dependencies are supported, and preserve your company’s reputation within the open source community as a responsible participant.

This guide will help you decide when a project is no longer useful, understand how to disengage from a project, and determine what to do about its code, repositories, websites, wikis, and other project assets as you head in a new direction.

## Lifecycle planning for your open source project

As software developers start to envision and develop new and needed business-critical open source projects, they should also incorporate clear and specific plans for each project’s complete life cycle, from its birth to its eventual demise. Such planning should also be conducted as part of a company’s overall open source strategy, incorporating all of the projects it oversees.

These efforts could mean planning for a future shuttering of a project, a transfer of its operations to another interested group of users, or a corporate pull-out from the initiative. Such end-of-life planning is part of the responsibility that enterprises have for projects, their users, and for the open source community that sustains it all. These plans are necessary to allow such transitions to be conducted gracefully for other users if a project is ended or transferred.

### Why life cycle planning is important

Planning for the potential end of an open source project isn’t unique. Similar life cycle planning is done for proprietary software initiatives, IT systems hardware deployments, and a wide range of other business decisions. For an open source initiative, project life cycle planning could include the traditional life cycle evaluations, such as an outline of the project’s scope and vision and estimates for its growth, as well as open source-specific categories like planning for community building and early user adoption and incorporating user feedback and contributions.

It’s natural for any project to undergo development slowdowns or for user adoption to peak and then decline. Even highly successful open source projects may eventually stop being useful to their creators or users as business plans change or new technologies and innovations replace them. Thus, an exit plan is critical to ensure a smooth transition.

## What does a dead open source project look like?

If the steady flow of contributions or commits to your open source project has fallen off, that doesn’t necessarily mean a project is dead. It may simply mean that the project is mature, has achieved its development goals, and is serving its users without requiring much upkeep or updating, which could be a good thing.

On the other hand, if the number of people adopting the project and using the code has declined significantly, that could be a sign that interest is waning and the project may be dying. Other relevant metrics can include the level of project activity in general and whether users are posting inquiries and joining online discussions about the code.

### Trouble signs to watch for

A dead or dying project can also be indicated by problems, such as unresolved differences about the direction of development or through lost energy from formerly involved contributors, who may have moved on to other projects that better capture their interest. An obvious sign is a decline in the project that coincides with members of your team or the community asking questions about whether it should continue, be ended, or left outright. Another indicator is that the code is no longer being patched or updated by the community to resolve vulnerabilities.

> “If you don’t have anybody asking questions, if nobody’s making contributions, if there doesn’t seem to be any new adoptions, nobody seems to be adding dependencies, and if you're not seeing any other signs the people are using it, that’s a potential big warning sign. It may all be fine, but it’s worth checking to see if the project is dying.” – Dr. David A. Wheeler, open source expert and lead for two projects with The Linux Foundation’s [Core Infrastructure Initiative](https://www.coreinfrastructure.org/) (CII)

These signs can be tricky to gauge even with hard data, since your code often may be accessed indirectly through package managers for other applications, rather than via direct downloads. This can make it hard to know exactly how many users you have and can accurately track as a project goes through its life cycle.

## Why plan for the end of a project before you even launch it?

As you plan your open source project, related decisions about how you might someday end or transition the project are a critical part of the project’s life cycle.

Why is that? Because pulling out of a project without a plan to protect its community and users can substantially harm an organization’s reputation within the open source community and the project itself. If you manage an open source software project, remember that others depend on it and that their continued use of it depends in part on your management and administrative efforts. Certainly your company can choose to change a project’s direction or status, but part of your responsibility is to clearly, quickly, and openly communicate such changes to a project’s users so they can plan for their own needs. It would be irresponsible to close a project and take down its code without communicating those intentions to users.

### Protect your company’s reputation

Leaving other users in a lurch is not something you want to do. In the world of open source, this issue should not be taken lightly. That doesn’t mean your potential exit plans need to be made in detail even before you get the project underway, but frequent, open communication will help assure users that you will not drop a project without adequate notice and that you will work to prevent users from being left hanging. In addition, by building, developing, and promoting code that is easily forkable, your project can offer flexible transfer capabilities to others if you should decide to end your own involvement in the project. Although you need not announce a full disengagement procedure in your life cycle plans, you can still let users know that you intend to close or transition the project smoothly and responsibly.

### Seek a diverse contributor base

Having a diverse group of code contributors is important to help your project grow by bringing in new ideas, deeper problem-solving capabilities, and more developer eyes on the code. It’s also helpful later if you decide to end or leave your project. With a diverse community involved in the effort, you could have have interested community members who potentially want to maintain it, broadening your options for future transition. If you do decide to leave a project, you would likely prefer to hand it off to other people who care about and will continue it, rather than announce its demise.

These early steps lay the groundwork for project success by establishing a level of trust that will allow a healthy ecosystem and commercial dependencies to be built around your project.

> “When you're starting your project, you're trying to get people to trust you and allay their fears about joining the project and using your code. Later, if you say, ‘Hey, this project’s going to go away soon,’ that is not going to help with trust. Instead, you should say you're going to do your best to make it work out if it will ever be ended, and that you promise not to just drop users. Tell them you’ll let them know what is happening at each step. Give them time to transition, and work on ways to help with the transition. That can be very helpful.” – Dr. David A. Wheeler, open source expert and lead for two projects with The Linux Foundation’s [Core Infrastructure Initiative](https://www.coreinfrastructure.org/) (CII)

## Deciding when to end, transfer or pull out of a project

Whatever the reason, there may come to decide whether an open source project should be ended or transferred to another entity or whether your enterprise should end its participation in the project. It could be because your business goals have changed and that the project no longer corresponds with your new direction. Or, maybe it’s because a key person or team that headed the effort leaves the company, or that project performance metrics such as participation, updates, and usage are declining drastically based on your latest user data. It’s also possible that disagreements have arisen among community members about the future of the project and it looks like changes may be needed.

### Disagreements can influence new project directions

If disagreements have arisen about the project inside the community – whether about its scope, technical matters, licensing or other issues – then you might consider splitting the project to allow interested parties to pursue what’s important to them. A similar quandary helped inspire developer Linus Torvalds to create Linux back in 1991. Torvalds had been experimenting with Minix, a small UNIX-like operating system kernel developed by Andrew S. Tanenbaum to teach college students about coding. Torvalds created Linux after he decided Minix had a radically different scope and vision, leaving him to create his own separate operating system.

The scope of projects can certainly change over time and be readjusted as needed, but if it the project is simply no longer needed, then it can be a candidate for dissolution or transfer. Projects can even be repurposed to either find a way to make your existing users happy or to incorporate a functionality that needs new users. Ultimately, however, if you have software and nobody needs it, then the project is probably finished. Even if it’s the best software in the world, if nobody needs that capability, then nobody cares.

> “That definitely does happen in different ways. We could stop using the project and its code because we just moved on to other things, or maybe the people who are maintaining it are now working on different things or have even left Facebook. Maybe nobody’s there supporting it and we're also not using it in our own apps. Some projects are contained enough that they're basically done being used.” – Christine Abernathy, Open Source Team Developer Advocate at Facebook

### Examples from the user trenches

For business users, a wide range of factors affect decisions on whether open source projects should be ended. At software maker Autodesk, where some 190 open source projects are homegrown and in use, declining participation in a project’s development is seen as a clear indicator of code that might be past its prime, which can lead to placing a formerly thriving project into “maintenance mode.” Under that designation, the code is no longer actively maintained and if users have questions they may or may not be answered. In such a case, community members of the project can still use it, but no community support is provided.

Similar usage indicators, including patch and maintenance requests, are monitored at Facebook, where some 400 open source projects have been homegrown so far, to periodically review the fates of ongoing projects. And at Capital One, where about 20 open source projects have been started in-house and are in use, projects are regularly transferred to other organizations or shut down depending on the needs of the company.

## How to end an open source project

Whatever you do to end or transfer an open source project, perhaps the most important move you can make is to be candid with users at every step. Being open about your intentions helps establish trust for future work with all potential developer communities.

Once you've decided to make the move, you must determine whether to end it, transfer it to another organization, or just pull out and end your direct involvement.

### How transfers can be helpful

By transferring the project to another organization that wants to continue to maintain it, you can then directly assist in the transition of the project’s data and other resources. This approach can help reduce the worry and risks of the existing community and its users. If the project has used common or standard interfaces, it will likely be easier to extract and move embedded data or replace it with another similar component if needed. That won’t always work, of course, because clearly some open source projects are unique. However, providing and using standardized interfaces early in the project life cycle can help make these transition efforts easier.

> “The best practice is to just be upfront and clear with the state of your projects. If you're no longer supporting a project, or you're in the process of winding it down, make that painfully obvious to anybody that would stumble across your code. You want them to see it’s no longer being maintained so new users don’t start using it and have this unwritten expectation that it is out there and that you are sponsoring this project and developing it.'” – Jared Smith, Open Source Community Manager at Capital One

### Make needed updates when transferring projects

Transferring a project has the added benefit of continuing to make the code available to other users, long after it was first created and nurtured by its original development community. Of course, more than just code will be affected. There’s also the documentation, Contributor License Agreements (CLAs), the project repository, wikis, websites to transfer, as well as some potential support infrastructure which will need to be reviewed and updated. Transfers can be done through an actual transfer procedure or by forwarding the project domains and other resources to a new user group.

In lieu of transferral, the project can be moved to a new host home and accessed by sending community members to a referral site where it is continued, rather than completely disengaging from it.

> “It doesn’t happen all the time, but in the past with one of our projects we moved it over to a different company. We don’t have any hard and fast rules about doing this. Typically, we’ll just move it to a different organization. When it comes to moving within groups, we sort of shop around internally and find out whether it is still being used by someone. With our open source projects, we strive toward internal adoption. So, it might be used by an entirely different team. If they are willing to maintain it, then we move it to a different team, and that’s very easy. That just means changing a label somewhere where it says who’s the owner.” – Christine Abernathy, Open Source Team Developer Advocate at Facebook

### Killing a project outright

Some organizations may simply want to kill an outdated project and retire its efforts for a myriad of reasons, from legal concerns to competitive pressures. The direction your enterprise ultimately takes is up to you. In this case, the code doesn’t need to be removed but can instead be archived, or made “read-only,” so it may still be used by others to fork it into new projects without your involvement. It can also be moved to an archiving site where it can be stored for users.

It’s important to always remember that just because your company doesn’t care about the code anymore it doesn’t mean that the existing community doesn’t care. It behooves you, then, to remind them as you proceed that they can fork the code and create their own uses for it without you. This also wouldn’t be a bad time to remind users who depend upon the open source code in your projects that they would be wise to mirror and save the code on their own for projects that are very important to them. Code can disappear over time and a good backup or mirror can be critical for users.

To make whichever option you choose work efficiently, a step-by-step disengagement plan is a good idea to keep it all organized. That means clear and early communications with users who are likely to care as well as a sufficient timeline that gives affected users time to finish their work and move to an alternate platform if needed. How much time will be enough for users? It depends. Start with at least six months, or it could be longer. The key is to set reasonable expectations and communicate your plans very clearly and quite often.

If your enterprise transfers the project to another group, the users should be kept up to date on what is being done to protect their interests as well.

### Work toward a smooth transition

When a workable partner is secured, then approach your project disengagement like you would handle any product that is being discontinued. Decide what, if any, involvement your organization will have with the project going forward in terms of developer time and then work closely with the new entity to prepare for a smooth transition. Be sure to set expectations that the actual transfer could take months to accomplish, and then turn the project over officially to the new owners when all the needed steps are completed.

A potential problem that could crop up, though, is if the group which is interested in taking over your old project is not one you favor to operate it into the future. This can happen, and you will have to come up with a plan for action in such a case. How do you deal with this? Well, if you're so attached to your code that you are considering not transferring it to a group that is not exactly in line with your corporate or philosophical directions, then maybe it’s not the right time to end the project. If you care about it that much, perhaps there’s a reason that you shouldn’t be leaving this project.

### The importance of clear communications

Clearly communicating the new direction of the transferred, ended, or rebranded project will continue to be your responsibility even after the transition. Be sure to openly advise developers and community members about the status of the project with its new operators and give them clear details about how the project is now being maintained if they care to continue to use it. Don’t forget to update your project website, social media channels, and other connected community assets so participants know where to find the moved project and can continue to make their contributions and use the code.

Remember to communicate all this information to downstream organizations and users as well. This includes companies, non-profits, and others that are using your code, and who may not be aware of the demise or transfer of the project because they're not directly involved in the development cycle. You should make efforts to advise them of what is happening through your websites, social media channels, and other outlets, especially if the project is well-known and has had a substantial following.

> “The biggest thing is to communicate the changes and tell the community of the plans ASAP. Don’t leave the users wondering if the project is still being maintained. For the most part, good code lives on, in my opinion, so if you've got a project that has good code, I would rather not ever take something down from GitHub but set the expectations at, ‘Hey, this project is no longer being actively maintained.’” – Guy Martin, Director of Open at Autodesk

### Provide updates through project repositories

Another important place to post information about project changes is the project’s repository itself on GitHub or related destinations. There you can place detailed notes explaining what’s happening, including readme files to help get the messages to participants.

As the project moves on, it’s time to officially transfer the assets, if necessary, to its new operators. If you are bringing in new administrators while maintaining the actual assets within your existing company, you can keep the copyrights on the affected code and let them use it with the open source licenses of their choice.

To keep the project repositories well organized, you might consider setting up a designated area where you can store and make available all transitioned open source projects that your company no longer supports (e.g., https://github.com/twitter-archive). In this way, the projects are still available for users to get code, and potential users can also still find readme files explaining the status of the projects. This designated section of the repository can provide clarity for users and help them understand the difference between active and retired projects, while also ensuring that enterprises can properly showcase their latest live open source projects in their active repositories.

### Archiving tips

Several steps are involved in archiving a project. For example, moving it to a read-only status helps make it clear, without having to change any URLs, that the project is now archived and no longer open to regular updates in its previous form.

Also important is to provide users with a clear alternative plan for their projects, including how to get and fork the code for their ongoing uses. As part of that responsibility, you should provide users with a way to contact you so they can have their fork listed and made available to other interested users. Some companies provide this assistance, while other choose not to do so.

Once a repository is archived, you cannot add or remove collaborators or teams, and issues become read-only. To make changes in an archived repository, you must unarchive the repository first. See the GitHub documentation for more details: [https://help.github.com/articles/about-archiving-repositories/](https://help.github.com/articles/about-archiving-repositories/)

### Infrastructure updates when shuttering projects

Ending a project can also affect your project’s infrastructure and support, which must be judged on a case-by-case basis, depending on how your project was set up. Some projects use and maintain only a small set of code, so there might not be much to do. If it is all code and it’s posted on your repository, then you're probably done and need not take additional steps to transfer or secure it.

Other projects, however, may require significant effort to shutter them using various backend tools to do the work. These may include services that may have been shared for many purposes, such as a test infrastructure. Although that test infrastructure has been used for the project previously, you may want to remove it before transferring the code so you can use the tool to test other work later. It may be hard to disentangle, but it can be done if desired.

> “Companies really **need to do** a better job of succession planning in open source. Just throwing something out there without proper planning and getting people from outside the company to become contributors and then expecting that it’s going to be that way forever is a challenge. You need to prepare that members of the community, whether they're from your company or from other places, are going to come in and follow somewhat of a life cycle and eventually, people become elders or retired from a community, and you need to have succession planning for that.” – Guy Martin, Director of Open at Autodesk

### Have a tough skin

There may also be some negative public comments and reactions posted about your actions, including unhappy users or “trolls” who disparage your move as abandoning users. Remember, however, most users are aware that priorities change over time and that enterprises might eventually have to stop some open source projects as their work matures. Every company must do this sometimes, so don’t take the comments too personally.

## Final thoughts

Shuttering, transferring, or leaving an open source project is inevitably a step your enterprise will choose to take at some point, but it need not be a debilitating task. With proper planning, clear and widespread communications and the step-by-step completion of legal and procedural tasks, transitioning an open source project can be accomplished satisfactorily for all involved.

By developing and including simple plans to shutter an open source project even as you begin planning a fledgling project’s first steps, you will ensure a healthy life cycle management plan. These plans will help your open source projects run as efficiently and successfully as possible from their lofty starts to their eventual quieter endings.

## Acknowledgements

Contributors to this guide:

* [Christine Abernathy](https://twitter.com/abernathyca), Open Source Team Developer Advocate at Facebook
* [Chris Aniszczyk](https://twitter.com/cra), CTO of CNCF (former head of open source at Twitter)
* [Guy Martin](https://twitter.com/guyma), Director of Open at Autodesk
* Jared Smith, Open Source Community Manager at Capital One
* [Dr. David A. Wheeler](https://www.dwheeler.com/), open source expert and lead for two projects with The Linux Foundation’s Core Infrastructure Initiative (CII)

*These resources were created in partnership with the TODO (Talk Openly, Develop Openly) Group – the professional open source program networking group at The Linux Foundation. A special thanks goes out to the open source program managers who contributed their time and knowledge to making these comprehensive guides. Participating companies include Autodesk, Comcast, Dropbox, Facebook, Google, Intel, Microsoft, Netflix, Oath (Yahoo + AOL), Red Hat, Salesforce, Samsung and VMware. To learn more, visit: [todogroup.org](http://todogroup.org/)*
