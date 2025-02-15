# Agentic Fediverse

The "Agentic Fediverse" is the idea of a new kind of [network federation](https://en.wikipedia.org/wiki/Federation_(information_technology)), a complementary iteration on the concept of federation currently established with [ActivityPub]. It's an experiment and something that we in [Muni Town](https://github.com/muni-town) are still trying to define more concretely.

> **Note:** This is a temporary place for collecting links about the agentic fediverse, until this can be hosted directly on [Weird.one](https://weird.one).

[ActivityPub]: https://activitypub.rocks/

### Tenets

We are still working on defining the core tenets of the agentic fediverse, but here is what we have so far.

An agentic fediverse is..

1. **A fediverse of agents**; agent-centric, as opposed to server-centric.
2. **Local-first**; solve local problems for local people.
3. **Accessible by default**; inaccessibility is a bug.
4. **Systematically consensual**; architected on the basis of informed consent.

### Primer

The word *agentic* occurs primarily in the social sciences, pertaining to an individual's agency, often used interchangeably with _autonomy_ or _self-determination_.

> In [social science](https://en.wikipedia.org/wiki/Agency_(sociology)), agency is the capacity of individuals to have the power and resources to fulfill their potential.

To be _agentic_ is to be agent-centric. An agentic system optimizes for agency in its users, for example by measuring _user agency_ as a metric of system performance.

# Definitive Topics

## Web Agency

https://weird.one/muni.town/web-agency

## The Great Untangling (series)

### Reclaiming (my) digital identity

https://blog.erlend.sh/reclaiming-my-digital-identity

> #### Connective tissue
> 
> I've grown up in an unprecedented time of connective magic. Unlike my ancestors, I have known not tens, not hundreds, but thousands of people with whom I co-created something of value. Such is the power of the digital age. My deepest connections exist locally, offline. Yet many of those connections were initially mediated through the incredible connective tissue of the internet.
> 
> My life as a somewhat odd person would have been a profoundly lonely one had it not been for the online spaces where I found The Others; fellow weirdos interested in play-crafts like storytelling and game development, coupled with an obsession for openness as a means to digital emancipation. To most of the thousands of people I've come across in my two decades as a netizen, the digital expression of my persona is my entire persona. I hope to live long enough to engage in a physical handshake or even an embrace with many of my online friends, but I recognize that a large number of these connections will forever remain purely digital.
> 
> Therefore it is acutely important to me that my digital identity properly reflects my truest self. I want the people in my life to have seen and known the real me, regardless of whether they came into contact with my physical or digital being.
>   
> #### Identity prison
> 
> And therein lies my predicament: Ever since I first logged on to the internet, I've never had legitimate ownership of my own digital identity. My digital expression has always been mediated through some higher power. Sadly not of the paternal kind that intends to lift my spirit up until I can stand on my own.

### Websites as the atomic matter of the internet
> https://blog.erlend.sh/weird-web-pages#website
> I consider the personal website to be the smallest possible building block of web identity. Once you wanna go past the observer (READ) level to the contributor (WRITE) level as a netizen, you’re gonna need a material web-persona to make yourself known. Unfortunately we never made personal websites easy enough to build, so the likes of Facebook became mainstream persona providers.
>
> (...)
> 
> ### Web pages materialize the internet
> 
> The size of the internet can be measured in the atomic mass of the websites it's made up of. We collectively materialize the internet with every additional web page we create.

> https://blog.erlend.sh/assembling-community-os
> Digital autonomy begets individual freedom begets fairness & equality.
> 
> The hopeful possibility of this moment lies in the open-social web protocols which make up the foundations of a comms & coordination ecosystem owned and operated by the general public.

## Decentralize ownership; Recentralize agency

> https://blog.erlend.sh/weird-netizens
> To free ourselves of our current predicament, we must simultaneously de-centralize and re-centralize identity.
> 
> By de-centralizing the ownership of identity away from platform monopolies and back to individuals, we can re-centralize the agency of personhood.
> 
> Once more for clarity:
> Decentralize ownership.
> Recentralize agency.
> 
> The central authority of ones digital identity must first and foremost be the individual themselves. That's how we regain our digital sovereignty.
>
> (...)
>
> ### Decoupling Identity
> 
> All mainstream identity providers get you hooked into their ID-network by means of a tight coupling between a light identity layer plus a heavy service:
>
> GitHub: ID + git
> Discord: ID + chat
> Gmail: ID + email
> Mastodon ID + microblog 🆕
> The indivisibility of this coupling weakens our digital sovereignty. Even if I stopped using Gmail for email, I still rely heavily on it for my authentication to hundreds of sites & services. It’s part of their lock-in scheme. (Mastodon being the obvious exception, since it's open source 🆕)
> 
> Gmail et.al. make identity confusing because they've made it appear necessarily coupled with an overarching complexity like email or a social network. But identity should stand on its own. In fact it is paramount that our identity is not owned by a personal-data-loving megacorp because there's nothing more valuable for them to keep locked up than the very essence of your digital self.


## Autonomous identity for the pluriverse (based on OAuth/OIDC)

https://socialhub.activitypub.rocks/t/autonomous-identity-for-the-pluriverse-based-on-oauth-oidc/3675?u=erlend_sh

### Mitigating sysadmin authority

> Like the separation of church and state, it seems prudent to keep the management of our digital identities separate from our social network servers.
> 
> My default ‘fedi ID’ is currently hosted on writing.exchange/@erlend - a Mastodon instance. This is already a big improvement from letting Twitter (or Google, or GitHub) be the chief custodian of my digital identity, since they won’t even let me move elsewhere if I’d like to do that. Mastodon makes that possible, thus giving me some genuine ownership over my contact list.
> 
> But I’m still beholden to an external server admin. Should writing.exchange go down, that’s my fedi ID gone, along with all my followers (contact list). This has already happened to several fediverse instances being run by hobbyists who for whatever reason (lost interest; finances; health; technical issues) stopped running their server, in some cases with no warning whatsoever.

## How to Federate (agentically)?

https://zicklag.katharos.group/blog/how-to-federate/

> Wouldn’t it be awesome if your data could be stored locally on your own computer, you could author posts offline, and even host your profile right from home if you wanted, too, just by keeping a tab open in your browser, or installing a normal app!
> 
> Servers could become optional. They would be very handy for keeping your data backed up, and for hosting your public data when your computer isn’t on, but they wouldn’t need to have any power over you as a self-sovereign agent on the web.
> 
> You could even have multiple servers that keep your data backed up, and you could move from one server to another easily, because it’s all built on data synchronization, not messaging and mailboxes.
> 
> I think this model is still technically “federation”, but it’s much more peer-to-peer than Email or Mastodon, for instance. We’re envisioning a fediverse of individual agents, not a fediverse of servers. We want an agentic fediverse.

### Incremental Complexity & Superb User Experience

> One of the major caveats of true self-sovereignty for users is that it comes with greater responsibility. For example if you are truly the only one with the power to control your identity, if you lose your password, nobody can help you recover it, unless you setup some backup or recovery method yourself. If somebody else could recover it for you, i.e. a server, then the server would have the power to steal your identity.
> 
> But that’s kind of how it’s always been. The server can reset your password, and in many cases, that will be the best user experience. The important part is having a choice, and being able to change your mind later.

## A Plan for Social Media - Rethinking Federation

https://raphael.lullis.net/a-plan-for-social-media-less-fedi-more-webby/

### The server is the wrong place for application logic

> All these issues could’ve been avoided if the decision-making process was delegated to the client. It’s nice that the server can make search queries, but it would be even better if the client could choose a separate, “global” search engine. It’s nice that the server can make recommendations for accounts to follow, but it would be even better if I had a menu pointing me to external services that are dedicated to this task. By forcing the user to do everything through the server, we become needlessly dependent on it.

### Networks are smarter at the edges

> The “server-centric” approach to the application development is at odds with the nature of distributed systems. We need to stop treating the client as a dumb terminal and give it as much power (and responsibility) as possible.

### The proposal: a Social Web browser, built into the browser

> If we have the client as the center piece of our social web, why not build it already in the foundation of the web client that is already used by virtually everyone?

## (Thoughts on) Fedi v2

https://www.thepaperpilot.org/garden/fedi-v2/

### Motivation

> The current fediverse, while in theory fully Decentralized, in practice suffers many of the issues associated with centralization. This is primarily caused by the friction of having to pick a server and the non feasibility of individuals buying a domain and setting up a single user instance - both of these causes lead to a handful of large servers with the bulk of the users. You can see this in action by looking up the relative sizes of lemmy and mastodon instances. Single-user Mastodon Instance is a Bad Idea goes over the non feasibility of self hosting and how it contributes to a handful of servers having the majority of the users.
> 
> The promise of federation is the ability to interact with the whole network, while being able to fully choose and customize how you yourself interact with the network. In practice though, clients are severely limited to what they can do based on the server software. Of particular note, Lemmy and Mastodon show content in different formats (threads vs microblogs), and no clients allow changing how they're displayed, or respecting the format of the source of the content. Clients also are unable to change sorting algorithms or how downvotes are handled - those are all dependent on the server. A Plan for Social Media - Rethinking Federation similarly criticizes how much of the decisions are dependent on the server, which most people won't be able to or willing to self host.
> 
> The pick a server problem is such a problem because not only do you have to pick what server has moderation policies you align with, but that you're also linking your identity with that server. Smaller servers tend to be more focused or niche, which is unlikely to fully encompass any person's entire identity. Why would I confine myself to being thepaperpilot@writinglovers.com if I'm more than a writing lover? Additionally, I'm risking that the community at that instance won't grow away from things I want to associate with, such as fascism or crypto. My identity could end up being associated with things I drastically don't want it to be.

## A Web of Data

https://zicklag.katharos.group/blog/a-web-of-data/

> Today the internet is made up primarily of a web of HTML pages. The HTML usually contains or references CSS and JavaScript that is largely concerned with the presentation or interactivity of that page. We need massively complicated web browsers and web standards to actually view these pages as they are meant to be viewed.

> Imagine an alternative internet protocol were each “thing” on the internet is an “Entity”. Entities might represent blog articles, chat messages, tweets, comments, or anything else. Each entity also has a path to that entity, like a URL.

> This might help us converge on one shared, flexible data protocol, similar to the internet of HTML pages that exists today, instead of having to make new protocols and APIs every time we want to let other people create custom frontends to our data.
> 
> It will inherently be a web of data, and presentation will be an optionally configurable layer on top, not an inescapable necessity for delivering your content.
