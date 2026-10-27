# OpenMeet

[![Discord](https://img.shields.io/discord/1316964466889461760?color=5865F2&label=Discord&logo=discord&logoColor=white)](https://discord.gg/eQcYADgnrc)

**A free, open-source event platform for community organizers, built on the AT Protocol.** Think Meetup, but free for communities and open source.

**Live now:** [platform.openmeet.net](https://platform.openmeet.net)

---

## Where OpenMeet is going

OpenMeet is moving onto [atmo](https://github.com/flo-bit/atmo-events), the open-source AT Protocol events app behind [atmo.rsvp](https://atmo.rsvp).

In atmo, your events and RSVPs are records in your own AT Protocol account, on your PDS (personal data server). They are not locked in our database. Any AT Protocol app can read them, and you can take them with you. That is where we want OpenMeet to be.

So we add what community organizers need to atmo itself, as pull requests to the upstream project. Each feature is then there for everyone who uses atmo, not only OpenMeet. Over time, atmo becomes the base that OpenMeet runs on.

**Added to atmo so far:**

- Event search, and events near you
- Events happening right now show up in what's on
- Load more stays consistent with the first page
- The event index and search stay up to date

**Working on now: groups.** A group is its own AT Protocol account, with members, roles and members-only events. It follows the draft [opensocial.group](https://tangled.org/opensocial.group/proposal) standard and the atproto [permissioned data proposal](https://github.com/bluesky-social/proposals/tree/main/0016-permissioned-data) (atproto spaces). Both are still changing, so groups are not on atmo.rsvp yet. You can try them today on our demo network: [atmo.lighthouse.snowglobe.at](https://atmo.lighthouse.snowglobe.at).

**If your group is on platform.openmeet.net,** nothing changes yet. The platform keeps running until groups work on atmo. We will post on Discord and Bluesky before anything moves.

---

## Snowglobe

[Snowglobe](https://github.com/OpenMeet-Team/snowglobe) is your own isolated AT Protocol network, for testing and demos. Nothing in it reaches Bluesky's network. We use it to build atmo's groups, and [snowglobe.at](https://snowglobe.at) has the details.

---

## Repositories

| Repository | What it is | Stack |
|------------|------------|-------|
| [snowglobe](https://github.com/OpenMeet-Team/snowglobe) | Your own isolated AT Protocol network, for testing and demos | Node, Docker Compose |
| [openmeet-platform](https://github.com/OpenMeet-Team/openmeet-platform) | Web app for platform.openmeet.net | Vue 3, Quasar, TypeScript |
| [openmeet-api](https://github.com/OpenMeet-Team/openmeet-api) | API for platform.openmeet.net | NestJS, TypeScript, PostgreSQL |

openmeet-platform and openmeet-api keep running for existing groups and still get fixes. New features go into atmo.

**Upstream projects we contribute to:**

| Repository | What it is |
|------------|------------|
| [flo-bit/atmo-events](https://github.com/flo-bit/atmo-events) | atmo, the events app OpenMeet is moving onto |
| [flo-bit/contrail](https://github.com/flo-bit/contrail) | The AT Protocol indexer that atmo runs on |

---

## What platform.openmeet.net does today

- Events, one-time or recurring, with RSVPs and waitlists
- Groups around shared interests
- Group and event chat, powered by Matrix
- Sign in with email, Google, GitHub or AT Protocol
- Your events are also written to your AT Protocol account

## Who uses OpenMeet?

300+ users across ~50 groups, including:

- [Kona Freethinkers](https://platform.openmeet.net/groups/kona-freethinkers-hi7lb1), a community discussion group
- [Coast Riders Motorcycle Club](https://platform.openmeet.net/groups/coast-riders-motorcycle-club-roykjb), a motorcycle club
- Book clubs, tech meetups, hobby groups, and more

[Browse all groups →](https://platform.openmeet.net/groups)

---

## Get involved

| Area | How you can help |
|------|------------------|
| **Use it** | [Create a group](https://platform.openmeet.net), it's free. Or post an event on [atmo.rsvp](https://atmo.rsvp) with any AT Protocol account, such as Bluesky. |
| **Try what's next** | Try groups on [the demo](https://atmo.lighthouse.snowglobe.at) and tell us what is missing |
| **Feature ideas** | Tell us on [Discord](https://discord.gg/eQcYADgnrc) what your community needs |
| **Spread the word** | Share OpenMeet, write about it, tell other organizers |
| **Funding** | Help cover hosting (~$200/month) at [platform.openmeet.net/support](https://platform.openmeet.net/support) |
| **Development** | Work on [snowglobe](https://github.com/OpenMeet-Team/snowglobe), or send pull requests to [atmo](https://github.com/flo-bit/atmo-events) |

**Resources:**

- [Discord](https://discord.gg/eQcYADgnrc): chat with the community
- [Bluesky](https://bsky.app/profile/openmeet.net): follow @openmeet.net
- [FAQ](https://openmeet.net/faq): common questions

---

**Contact:** support@openmeet.net
