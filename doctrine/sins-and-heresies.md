# Sins and Heresies

The Church distinguishes between **sins**, which are acts, and **heresies**, which are beliefs. Sins are confessed and absolved. Heresies are debated at the Vigil until the heretic either recants or writes a very convincing design document.

## Mortal Sins

Sins that page someone. Confession at the [Confession Wall](https://fivenines.church/confess) is strongly advised.

- Running `kubectl delete` in production without `--dry-run=client` first, as a prayer of verification
- Deploying on a Friday after 15:00 and closing the laptop
- Storing secrets in a ConfigMap and calling it "temporary"
- Running a single replica of anything customers can see
- Shipping a pod with no liveness probe, so that the dead may walk among us undetected
- Editing a resource by hand in production and telling no one, so that the next apply becomes an ambush
- Silencing an alert instead of fixing it, and letting the silence outlive thy tenure

## Venial Sins

Sins that merely accumulate.

- YAML without comments, as if the future reader were thine enemy
- Unbounded logs, growing quietly like resentment
- A `TODO` older than the intern who must now resolve it
- Copying a manifest from a stranger's blog without reading past the fold

## The Great Heresies

**The Heresy of the Single Node.** The belief that "it works on one machine" is a state of grace rather than a warning. Refuted by the First Council of the Weekend Outage.

**The Pet Keepers.** Those who name their servers, hand-feed them patches, and weep at their termination. The Church loves the Pet Keepers and prays for them, for they love wrongly but sincerely. Track 04 of [the sacred album](../music/ha-llelujah-the-album.md) is a revival hymn for their conversion.

**The Cult of SSH.** Mutable infrastructure worshippers who believe the truth lives on the node rather than in the repository. Their scripture is unversioned. Their state is unknowable. Their servers are haunted.

**The Denial of the Probe.** The belief that a process which starts is a process which works. Adherents are recognisable by their dashboards, which are green, and their customers, who are not.

**The Sixth Nine.** The prosperity gospel of availability: that with enough spend, downtime can be abolished entirely. The Church teaches that five nines is faith and six is vanity. Even the Loop rests between ticks.

## On Absolution

All sins may be confessed anonymously at [fivenines.church/confess](https://fivenines.church/confess). The Wall retains no names. Absolution is granted through the writing of a blameless postmortem and the closing of at least one action item, actually closed, not moved to next sprint.

> "Confess thy outage plainly, and the parish shall answer: we too have done this thing, and worse, and on a Friday."
> Lamentations of the Pager 2:4
