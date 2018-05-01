# The Open Source Program at Microsoft: How Open Source Thrives

Microsoft is now an accepted big player in the open source space, but just a few years ago such a role for the software giant, seemed inconceivable. Many people were thus surprised when Microsoft emerged from its market lead as a proprietary software maker to make a move towards open source in a big way. Although the company’s story is remarkable, its open source journey has been neither as abrupt or unexpected as it may have appeared.

> “Despite perception, Microsoft has been doing open source for quite a while. At first, it was experimental pieces here and there but about six years ago, in 2011, we brought much of that into focus in an entity called Microsoft Open Technologies,” explained Jeff McAffer, Director of Open Source Programs Office at Microsoft.

## Open source in earnest

That’s when the exploration of what Microsoft could do with open source began in earnest, McAffer said. In the early days, if anyone in the company was interested in doing anything with open source, they came to the centralized group for assistance from the open source developers, contributors, and maintainers involved.

About three years ago, things began to change. Microsoft decided to make open source pervasive throughout the company and rolled open source into the main engineering groups.

> “If that’s all we had done, we would have left an untenable vacuum around how we do open source,” said McAffer. “Someone has to think about policy and how all the open source efforts would be coordinated, the processes and tools they would use, how would we keep track of projects, etc. So, we created what is now known as the Open Source Programs Office to handle all those issues.”

Some of the technical people from the earlier open source group moved to the newly formed program office, while the others joined engineering groups pertinent to their work. It turned out that Microsoft needed additional talent to make sure all projects and processes were fully manned, and so recruitment efforts, both internally and externally, were soon under way. Today, open source is a thriving part of Microsoft’s global works.

## Business and programmatic goals

Microsoft does not have a central open source strategy or a central approval body. Instead, the Open Source Programs Office facilitates those discussions and decisions throughout the company. Teams still need to have their open source engagement reviewed, but it is done more locally.

> “They know their business, they understand how they want their technical interactions to work, where they want to drive in terms of ecosystems, and all the various nuances of what needs to happen,” McAffer said.

> “We defer most of those decisions and directions to the local management, but we give them a structure in which to think about those decisions and directions. We do have central policies about how we manage IP and what do we do about security issues. We give them tools and processes that embody those policies to make it super simple for them to execute in a coherent yet specific way.”

## The tools to manage

Microsoft’s policies boil down into processes that then are tooled accordingly to handle the workload. One example is open source releases. As a matter of policy, releases are made on GitHub.

> “We've got a bunch of tooling around our presence on GitHub, where we manage something like 10,000+ repos across about 100 organizations with about 12,000 Microsoft people interacting in that space,” said McAffer.

> “That gets up to a scale where you really need a system to manage a multitude of aspects. For example, when people want to contribute to one of the projects that we're running, we need tools to help manage the contributor license agreements or CLA’s. For all of those things, we've either built up solutions ourselves or turned to open source solutions.” For example, for CLA management, Microsoft uses [CLA Assistant](https://cla-assistant.io), an open source program that SAP originated.

> “On the GitHub management side, we went the other direction, as there wasn’t an existing set of tooling to help manage an enterprise presence on GitHub,” said McAffer. “So we ended up creating what’s now called the [open source portal](https://github.com/Microsoft/opensource-portal), which is available on GitHub as open source.”

Elements of that are easily seen on [opensource.microsoft.com](https://opensource.microsoft.com/), but then there’s an internal side, too, where Microsoft employees manage repos and teams. “We've open sourced that and other companies are picking it up and using that internally for themselves, so it’s a bi-directional thing,” McAffer explained.

GitHub is a very rich environment, where lots of interactions are possible. Microsoft, like a lot of companies, was finding it difficult to keep track of everything going on and understanding what was happening with its repos.

> “We ended up engaging with the GHTorrent project. We did quite a bit of work with them, and we actually are now sponsoring the GHTorrent project so we pay for all their Azure resources, everything you can see that at [GHTorrent.org](http://ghtorrent.org/),” he said.

GHTorrent helps Microsoft understand what’s going on at GitHub but also internally in terms of its own projects. Even so, there are some things that GHTorrent was not set up to do, including work with private repositories and some of the more detailed data concerning teams where admin permissions are required.

The company ended up creating another system called [GHCrawler](https://github.com/microsoft/ghcrawler), which it also open source. This tool tracks everything on GitHub down to the commit level, team, and permissions changes. That data is then used in metrics and tracking analysis to discover insights such as how many pull requests are coming in, how fast they are getting action, and how long they take to close or merge. “It gives us a way of tracking our presence,” said McAffer.

## Simplifying open source use

Consumption of open source is an entirely different matter, and a different process, at Microsoft. The company uses open source in myriad ways, and the need to track them all and to manage the legal security aspects is enormous.

> “We've done a massive amount of work to simplify the processes and the policies around open source use, to really understand the key attributes of being a responsible consumer of open source, how to do it right, and to make sure we adhere to the licenses,” McAffer said.

> “To that end, we've written a lot of tools internally to discover, track, and monitor what’s going on there and report on the use of open source,” he continued. Those tools also tend to be somewhat proprietary as they are deeply integrated with Microsoft’s engineering systems.

> “We've been trying to see ways we can tease that out and make more of that available to the open source community more broadly, but it’s been a bit hard because it is very specific in many ways to our business policy or our engineering system, which isn’t going to be the same as anybody else’s,” McAffer said.

The Microsoft open source journey has been an interesting one over the years and in the true open source spirit, we will continue to share what we learned with everyone in that process, from tools to code.

## Acknowledgements

We would like to thank Carol Smith, Senior Open Source Program Manager at Microsoft and Jeff McAffer, Director of Open Source Programs Office at Microsoft for being interviewed. We would also like to thank Pam Baker for performing the interview.

