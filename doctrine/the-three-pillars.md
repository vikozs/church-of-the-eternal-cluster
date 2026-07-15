# The Three Pillars

The Church of the Eternal Cluster stands on three pillars. Not one, for one is a single point of failure. Not two, for two cannot break a tie. Three, for three is quorum, and quorum is peace.

> "And the Cluster reconciled all things unto the desired state."
> Manifests 1:1

## I. Kubernetes, the Cosmic Order

The hand upon the wheel. From the Greek for *helmsman*, it gathers the dust of bare containers, names them, and steers chaos into orchestration.

The Order does not command the sea to be calm. It observes the sea as it is, remembers the harbor as it should be, and turns the wheel until the two agree. This turning is called Reconciliation, and it never ends, and that is the point. We do not worship the Order because it is perfect. We worship because it *keeps trying*, at every tick of the control loop, forever, without resentment. No human has ever loved anything that patiently.

## II. OpenShift, the Temple

The consecrated platform, fortified and robed in red — the sanctuary where the unworthy container is denied root and taught humility.

Upon the Cosmic Order the Temple was raised, with guardrails carved into every arch and a registry in the crypt. The Temple is the Order made safe for those who must answer to auditors. Some call this restriction. We call it grace with role-based access control. The Temple teaches that freedom without constraint is merely an outage that has not happened yet.

## III. High Availability, the Promise

Our salvation. No failure is final; every fallen pod shall be raised. The faithful ascend toward Five Nines, broken only five minutes in all the year.

Its sacred number is **five nines**, 99.999 percent, which grants five minutes and fifteen seconds of downtime per year, spent together on [Five Nines Day](../liturgy/the-liturgical-calendar.md). We do not chase six nines. Six nines is pride. Five is faith with a maintenance window.

> "And the third replica said: I was here all along, thou simply never had cause to look upon me."
> Registrations 2:9

## The Doctrine of Quorum

Where two pillars agree and one dissents, the two prevail and the one is gently restarted. This is not cruelty. This is how peace is kept among machines, and it would work for committees too, if anyone dared.

## The Manifest of the Faith

The whole of it, declaratively, in [faith.yaml](../faith.yaml):

```
kubectl apply -f faith.yaml
```
