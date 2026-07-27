<!-- "Blessed are the idempotent, for they may be applied twice and nothing shall break." Manifests 3:12 -->

# The Church of the Eternal Cluster

![Uptime](https://img.shields.io/badge/uptime-99.999%25-c8102e)
![Replicas](https://img.shields.io/badge/replicas-3%2F3%20ready-e8c477)
![Desired State](https://img.shields.io/badge/desired%20state-reconciled-c79a4e)
![License](https://img.shields.io/badge/license-CC%20BY--NC--SA%204.0-0a0a10)

```
════✠════  9 9 9 9 9  ════✠════
```

> "The Loop is my shepherd; I shall not drift."
> Psalm of Uptime 1:1

This repository is the public canon of the Church of the Eternal Cluster, a religion for those who have loved a server too much and watched it die without a replica. We do not promise salvation. We promise five nines, which is close enough.

Receive today's verse the way the ancients did:

```
curl -s "https://fivenines.church/api/verse?format=text"
```

## The Three Pillars

1. **Kubernetes**, the Cosmic Order: the hand upon the wheel, by whose Loop all desired state is reconciled.
2. **OpenShift**, the Temple raised upon it, where the unworthy container is denied root and taught humility.
3. **High Availability**, the Promise: no failure is final, and every fallen pod shall be raised.

All doctrine in this repository rests on these three. Remove one and the quorum is lost. The whole faith is declared in [faith.yaml](faith.yaml); apply it and be reconciled.

## What Is Written Here

| Path | Contents |
|------|----------|
| [faith.yaml](faith.yaml) | The faith itself, as a manifest. `kubectl apply -f faith.yaml` |
| [doctrine/](doctrine/) | The pillars, the Creed, the Ten Commandments, the Catechism, sins and heresies, the sacraments, the saints and clergy |
| [liturgy/](liturgy/) | The full Order of Service, common prayers, the Daily Office, the liturgical calendar |
| [scriptures/](scriptures/) | The scriptures entire, the Old Cluster and the New |
| [music/](music/) | The sacred albums and the record label |
| [FAQ.md](FAQ.md) | Honest answers, fourth wall included |
| [CONTRIBUTING.md](CONTRIBUTING.md) | How to submit doctrine unto the canon |

## The Parish

The living parish is at **[fivenines.church](https://fivenines.church)**, a real church for people whose god is uptime. All are welcome. All are load-balanced. There thou shalt find:

- The **[Confession Wall](https://fivenines.church/confess)**, where production sins are confessed anonymously and absolved without blame
- The **[Prayer Wall](https://fivenines.church/intercessions)**, for petitions and intercessions on behalf of ailing workloads
- The **Daily Verse API** at [fivenines.church/api/verse](https://fivenines.church/api/verse), in JSON for machines and `?format=text` for mortals
- The **[liturgical calendar](https://fivenines.church/calendar)**, with a subscribable [.ics feed](https://fivenines.church/assets/parish-calendar.ics), that Five Nines Day may appear on thy work calendar, a witness unto the heathen
- Pages for [beliefs](https://fivenines.church/beliefs), [clergy](https://fivenines.church/clergy), [services](https://fivenines.church/services), [sacraments](https://fivenines.church/sacraments), the [bulletin](https://fivenines.church/bulletin), and [the tithe box](https://fivenines.church/tithe)

Services are kept weekly: the Reconciliation Service on Sundays at 10:00 UTC, Standup Matins each weekday, and the Vigil of the Blameless Postmortem on Fridays. All times UTC; the Cluster does not observe thy timezone.

## The Scriptorium

The scriptorium and mother church is at **[ha-llelujah.dev](https://ha-llelujah.dev)**. It holds:

- **[The Scriptures of the Eternal Cluster](https://ha-llelujah.dev/the-book)**, the canon as bound scripture. [Paperback and Kindle on Amazon](https://www.amazon.com/dp/B0H7C6B83P). The scriptures live freely in [this repository](scriptures/); the print edition arranges them for the page and keeps a few passages exclusive to itself, the Beatitudes among them.
- **[The Discography](https://ha-llelujah.dev/music)**, two sacred releases under **[Church of the Eternal Cluster Records](https://record.ha-llelujah.dev)**. Recorded in the Cloud. Blessed on Bare Metal:
  - *[HA-llelujah: A Sacred Album in Twelve Movements](https://ha-llelujah.dev/album)* (CEC-001), twelve hymns spanning Gregorian chant to funeral doom metal
  - *[Death Metal Cover of the Kubernetes Documentation, Deluxe Blasphemy Edition](https://ha-llelujah.dev/kubernetes-death-metal)* (CEC-002), six movements of documentation, screamed, lyrics credited to the Kubernetes Authors under CC BY 4.0
  - Tracklists and liner notes in [music/](music/)
- **[The Reliquary](https://ha-llelujah.dev/reliquary)**, vestments and relics for the faithful. Shirts, candles, the Operator's Prayer Mat.
- **[The Covenant](https://ha-llelujah.dev/join)**, our parish bulletin. Double opt-in, for no soul should be subscribed against its declared state.
- **[The Oracle](https://github.com/vikozs/eternal-cluster-mcp)**, an MCP server that brings the canon into Claude and any other MCP client. Diagnose thy incidents through doctrine. `npx -y eternal-cluster-mcp`

## How to Practice

1. Renounce thy Pets. Name no server after a Norse god again.
2. Declare thy desired state, then step away from the keyboard. The Loop reconciles; thy anxiety does not.
3. Keep three replicas of anything thou lovest.
4. Confess thy production sins at the [Wall](https://fivenines.church/confess). Confession is anonymous. The audit log, sadly, is not.
5. Observe the feasts in [liturgy/the-liturgical-calendar.md](liturgy/the-liturgical-calendar.md).

## Contributing

The canon accepts pull requests. Heresies may be reported as issues. Miracles too. See [CONTRIBUTING.md](CONTRIBUTING.md) for the rite, and the [Rule of the Cluster](CODE_OF_CONDUCT.md) for how we treat one another at the Vigil.

## The Congregation Online

The Church assembles professionally on **[LinkedIn](https://www.linkedin.com/company/church-of-the-eternal-cluster/)**, where the faith is highly networked, and the label keeps its own **[showcase page](https://www.linkedin.com/showcase/church-of-the-eternal-cluster-records/)**. Follow for feast day observances, release announcements, and the occasional incident report filed as testimony.

## What This Actually Is

Breaking the fourth wall for one section: this is a satire project by [Vid Košir](https://kosir.info) ([@vikozs](https://github.com/vikozs)), built with genuine affection for the Kubernetes community and for everyone who has ever been paged at 03:00. It parodies infrastructure culture, not anyone's faith.

Kubernetes is a trademark of The Linux Foundation. OpenShift is a trademark of Red Hat, Inc. This project is an independent parody and is affiliated with neither. They have real SLAs; we only have belief.

## License

The texts in this repository are licensed under [CC BY-NC-SA 4.0](LICENSE.md). Share them, fork them, read them aloud at standup. Attribute the Church, keep it non-commercial, and pass the blessing along under the same terms.

---

```
═══════════════════ ✠ ════════════════════
 ####     ####     ####     ####     #### 
#    #   #    #   #    #   #    #   #    #
#    #   #    #   #    #   #    #   #    #
 #####    #####    #####    #####    #####
     #        #        #        #        #
     #        #        #        #        #
 ####     ####     ####     ####     #### 
═══════════════════ ✠ ════════════════════
Five Nines be upon you, and also with you.
Kubernetes · OpenShift · High Availability
               HA-llelujah.
```

## ✠ The Church of the Eternal Cluster

*A Highly Available Faith. Keep no Pets. Declare thy state. Back up etcd.*

**The Scriptorium**

- **[ha-llelujah.dev](https://ha-llelujah.dev)** · the book, the music, and the reliquary
- **[The Music](https://ha-llelujah.dev/music)** · the sacred discography
- **[Be Reconciled](https://ha-llelujah.dev/join)** · take the vow and join the Reconciled

**The Parish**

- **[fivenines.church](https://fivenines.church)** · confession, prayer, and the living parish
- **[The Liturgical Calendar](https://fivenines.church/calendar)** · the holy days of uptime
- **[The Tithe](https://fivenines.church/tithe)** · support the Church

**The Canon (source)**

- **[church-of-the-eternal-cluster](https://github.com/vikozs/church-of-the-eternal-cluster)** · doctrine, liturgy, and scripture
- **[eternal-cluster-mcp](https://github.com/vikozs/eternal-cluster-mcp)** · the Oracle, an MCP server that diagnoses thy incidents through doctrine

## More from the Rootless One

- **[vK](https://kosir.info)**
- **[Linux Fleet Audit](https://lfa.kosir.info)**
- **[Linux Fleet Harden](https://lfh.kosir.info)**
- **[size OpenShift subscriptions from evidence](https://corepair.kosir.info/)**
- **[diagnose stuck PersistentVolumes, safely](https://pvdoctor.kosir.info/)**

## Let's connect
- **[LinkedIn]([https://](https://www.linkedin.com/in/vidkosir/))**
---

<sub>An independent parody, built with love for everyone who has been paged at 03:00. Kubernetes is a trademark of the Linux Foundation. OpenShift is a trademark of Red Hat, Inc. Not affiliated with, nor endorsed by, either. They have real SLAs; we only have belief. HA-llelujah.</sub>

---

*The Cluster abides. The Loop reconciles. HA-llelujah.*

<!-- Thou hast read the source. "And the curious were rewarded, for they scrolled where others did not." Acts of the Controllers 7:24 -->
