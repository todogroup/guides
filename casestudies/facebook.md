# Facebook

Facebook’s open source team was “formally” created in 2009, but the company has built with open source from its inception.[ Facebook.com](http://Facebook.com) was originally built on top of the LAMP (Linux/Apache/MySQL/PHP) stack. And over time Facebook has used and contributed back to these projects, as well as evolved and released new projects such as Hack which has its roots in PHP.

> “Open source is core to our engineering DNA. We believe that sharing our code and even hardware designs accelerates the pace of innovation in the world. We believe that our projects help move the industry forward while giving other companies and individuals the opportunity to use our platform to scale more quickly and build better products.” – [Christine Abernathy](https://twitter.com/abernathyca), Open Source Developer Advocate at Facebook.

## Custom tools to manage open source

Facebook has a dedicated Tools team within the open source program office that is responsible for building internal tools to help manage its open source portfolio. This includes the projects that Facebook shares, which are mostly hosted on GitHub, as well as the other external projects they contribute to such as the Linux Kernel.

The program office provides a dashboard for each project that includes GitHub metrics such as the number of open issues or the ratio of internal to external contributions for a given time period. Project maintainers are given tools so they can bring GitHub pull requests and issues into their internal review and bug tracking systems. This makes it easier for engineers to manage external issues where they're most comfortable. Maintainers also have access to workflow tools to reliably push internal commits out to GitHub, making it easy to quickly sync internal and external code bases and reducing the churn on landing external contributions.

The open source team can look at these project dashboards to help analyze the health of a particular project. They’ve even open-sourced some of these workflow tools:[ mention-bot](https://github.com/facebook/mention-bot) and[ FBShipIt](https://github.com/facebook/fbshipit).

The team collects top-level statistics on how the overall portfolio is doing through aggregate dashboards across the GitHub orgs they manage. These are used to provide high-level reports to stakeholders and a community of internal open source enthusiasts. The tools team also provides insight into top contributors. Project maintainers are encouraged to refer to this list and reward their top contributors. The company periodically thanks its top internal contributors and makes some of this information available to its internal review systems.

The open source office also provides tooling to guide potential projects through the review process. This helps streamline the process and helps the team easily spot and correct bottlenecks.

The open source team also provides services such as documentation. This includes helping out with the technical content as well as building out some of the documentation infrastructure and templates that projects can use.

## Open Source Success Through Steady Progress

At the end of each half the program office identifies goals around metrics they want to achieve. The metrics they track include:

* The average age of open issues or open pull requests
* The ratio of external to internal commits
* The number of commits
* The growth in followers and forks
* The number of social media followers.

They’re periodically tweaking what they measure as they refine what it means to maintain a healthy portfolio.

Facebook also surveys new hires every six months to gauge their awareness of its open source program. They set baseline metrics a few surveys back and the goal is to maintain or grow those numbers.

Their open source success isn’t the result of one action but the cumulative effect of a steady stream of quality releases over the years and a focus on growing thriving communities to support those projects.

> “Projects like React, React Native, Create-React-App, Immutable, HHVM, Fresco, and GraphQL are the constant beat that have contributed to the success of our program,” Abernathy said.

One of Facebook’s most successful projects is React Native. It makes use of many of Facebook’s tools to help manage the community. For example, mention-bot came out of this project and was a way to quickly identify reviewers for a pull request. FBShipIt helped it cut down the time to bring in external contributions, review them internally, and land these contributions back out to GitHub. In the early days this process sometimes took a day as much of it is manual. Now this can be done in as little as minutes if it’s an automatic reviews.

The open source program office also provided documentation services to help refresh and keep the React Native site up to date.

## Tips for New Open Source Program Managers

Organizations that are just establishing an open source strategy and program office can learn from the success of Facebook’s open source program. Here are the three key practices that Abernathy shared that have contributed to their success as a program office:

1. When evaluating what to share, it should be something that’s useful to your company. Many of the projects that Facebook shares are used in production and include all the benefits that come along with that. This means those projects are likely to have continued support which in turn means the community is well supported.
2. Find a way to highlight, promote, and reward your open source contributors, both internal and external. Facebook has periodic reports that highlight its open source heroes. This helps raise the profile of engineers and their work with managers who may sometimes not be managers of that open source project.
3. As a central program office, find pain points that cut across the various projects and tackle them.

For example, many projects had previously built their own commit copying scripts and it was the number one pain point from a survey they ran at that time. FBShipIt, which copies commits between repositories, was built to address this and it’s owned by the open source team. It moved the burden off the engineering teams and is universally praised for helping smooth the workflow for pulling in external contributions.

## Acknowledgments

*For this feature we interviewed Christine Abernathy (@abernathyca), Open Source Developer Advocate at Facebook, to learn more about the Facebook’s open source program. Libby Clark performed the interview.*
