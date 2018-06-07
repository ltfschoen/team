# Team repo README

This repo is for organising the development work between different parts of the Parity tech stack. The goal is efficient self-organisation.

* There should be one issue for each "major" project that Parity is working on, these might be "major" sub-projects under the main parity repo, like light-client or sharding.
* Each project should have an owner.
* Each project should have people assigned to it that are working on that project, please self-assign and move yourself if you switch projects.

## High-level company goals for 2018

Our overall strategy will be to play to our strength: core technology and (seemingly) simple products that use it to do things that nobody else can. 

We’ll be moving away from current-generation technology to blaze the trail of promising next generation technology (Polkadot). We’ll also be ensuring our focus stays with building, not running and we’ll be ditching anything that’s too operations-heavy. Words of the day are WebAssembly, libp2p, light-client, Polkadot, on-chain governance, bridging and PoS.


### For more reading...
+ Scroll back up and read through [Parity Announcements](https://riot.im/app/#/room/#announcements:matrix.parity.io) channel, such as Gavs announcement on 2018 Strategy
+ [Statement on the importance of light clients](https://paritytech.io/creating-a-lighter-experience/)

## Culture

See [this post](https://hackmd.io/Bz0eJaNPSBOTmhpgV6UgGA) for a longer explanation of how we see the culture at the company.

In short, **"Work on what you want to work on"**.

However, to make this a reality, there are two requirements, that everyone has a great understanding of the vision is and what is productive for the company to work on, and that everyone has a great understanding of their own responsibilities and a willingness to live up to those responsibilities.

We'll be working more on trying to make sure everyone understands that vision of the coming little while and hopefully this document can serve as a starting point, and if you ever have any questions reach out to Fred (@folsen).

I highly encourage people to [watch this video](https://www.youtube.com/watch?v=uk-CF7klLdA) and [read this book](https://legacy.gitbook.com/book/hintjens/social-architecture/details).


## Owner expectations
The owner of a project bears the responsibility of that project overall, this means they are the driver of the project and makes sure that nothing falls through the cracks. The project owner must have a good overview of the vision and roadmap of the project and is responsible for making sure that the project gets the attention it deserves. _The project owner should ideally be someone who is actively working on that project, writing code day to day._

Responsibilities of the project owner includes (but is not necessarily limited to):

- Be available to help answer questions about the project and direct efforts/interests about the project, such as prioritising issues or feature requests.
- Keep project issue up-to-date (weekly or more frequently if necessary), with changes to goal/vision, roadmap, assignees or other
- If more resources are needed on a project, get in touch with Fred
- Consult Head of Security (Kirill) regarding licensing or security related things such as audit requirements, how to handle personal data etc.
- Consult comms team (Phil) for comms related things, branding/naming, disclaimers etc.pp.
- Let the comms team (Phil) know in advance about any comms related events (releases, audits, third party integrations, anything the public might benefit from knowing about) by e.g. tagging them on an action point in the project's issue
- Chat room: make sure to invite @r00t to your project's riot room and make @r00t admin, @r00t has to list the channel in the community directory


## Process for transitioning to a new project
This is a very informal process. Basically there's two goals, 1) make sure everyone is informed that you're moving and 2) don't leave any gaps behind you. Roughly it would look something like:

1) Give your your current project owner a heads-up, if you are the project owner give Fred a heads-up (preferably with a suggested replacement, but not necessary)
2) If you don't already know what you want to work on, check team repo for a project you are interested in, projects with the `help wanted` tag are a good start. Talk to the project owner if there's any room for more people to work in that project.
3) Let Fred know that you're moving

## Issue labels

Issue labels are assigned by Fred and each project can have one of the following three labels:
+ `help wanted`: means that there's definitely room for more people to join the project
+ `20 percent`: means that this project is open to be taken as a 20% project by one person (spend one day a week), 20% projects should by default only have 1 person on it, but exceptions might be made, feel free to propose new 20% projects
+ `on ice`: This project is currently not actively being worked on, but it would be desirable to have someone start
