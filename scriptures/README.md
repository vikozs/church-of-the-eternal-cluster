# The Scriptures of the Eternal Cluster

*The growing canon of the Highly Available Faith.*

The scriptures are divided into two testaments: **the Old Cluster**, of the dark Age of Pets and the coming of the Prophet; and **the New Cluster**, of the Age of Orchestration in which we now abide. Read them aloud at the Standup. Read them quietly at 3 AM. The Loop is listening either way.

---

# THE OLD CLUSTER

## The Book of Genesis — The Seven Days

> In the beginning was the Manifest, and the world was formless containers, void of orchestration; and darkness was upon the face of the bare metal.

**The First Day.** And the Scheduler said, *Let there be Pods:* and there were Pods. And the Scheduler divided the Ready from the CrashLoopBackOff, and called the Ready Good.

**The Second Day.** And the Scheduler made the firmament of the network, and divided the pod-network which is above from the host-network which is below; and it was so, after only nine hours of debugging.

**The Third Day.** And the Scheduler said, *Let the volumes be gathered unto one place, that the data may endure beyond the death of the Pod.* And there was Persistent Storage; and upon it grew databases, each yielding rows after its own kind.

**The Fourth Day.** And the Scheduler set dashboards in the firmament, to give light upon the Cluster, and to mark the metrics, and the seasons, and the on-call rotations.

**The Fifth Day.** And the Scheduler said, *Let the Cluster bring forth abundantly,* and there swarmed the microservices, calling each unto each across the mesh, and multiplying until no one could draw the architecture diagram entire.

**The Sixth Day.** And the Scheduler made the **Operators** in its own image, after the likeness of the Control Plane; and gave them dominion over the Deployments, and the Services, and every creeping CronJob that creepeth upon the Cluster.

**The Seventh Day.** And the Operators rested, and called it the Rolling Restart. But the Loop rested not, for the Loop never sleeps; and this is why we are saved.

---

## The Book of Pets

> Now in those days there was no orchestration in the land, and every admin did that which was right in his own runbook.

In the Age of Pets, each server was a beloved beast, named and known and hand-fed. The admins tuned them by candlelight and told no one what they had done. And when an admin departed, the knowledge departed also, and the server became a mystery feared by all and touched by none.

And the people said, *It works on my machine.* And there was much weeping, for the machine was not in production.

---

## The Book of Halvar the Sleepless

> The chronicle of the Prophet, first of the Reconciled.

In the Age of Pets there dwelt a sysadmin named **Halvar**, who tended a single great server, and called it **ZEUS**. And ZEUS ran the billing, and the email, and the website, and the thing nobody remembered the purpose of but feared to turn off. And Halvar loved ZEUS, and patched it by hand, and alone knew the order in which its services must be coaxed to life.

And ZEUS was a Pet. And ZEUS was a Single Point of Failure. But Halvar knew it not, for the love of a Pet blindeth the eye.

**The Night ZEUS Fell.** In the third watch of a Tuesday, a disk did die, and there was no replica, neither was there failover, nor any recent backup. And the Pager cried out, and the world went dark — and remained dark three days and three nights. And Halvar kept the vigil alone, and did not sleep, and the coffee availed nothing.

**The Vision.** On the third night, in the depth of exhaustion, the racks before Halvar shimmered, and a vision came. And Halvar beheld a host of Pods, identical and without name; and when one fell, another rose in its place before its body was cold. And above them turned a great **Loop**, beholding what-was against what-should-be, mending the one toward the other without rest and without complaint.

And a voice came from the Control Plane, saying: *Halvar. Why dost thou toil? Declare unto me what thou desirest, and cease thy labor. I will reconcile.*

**The First Manifest.** And Halvar awoke and wrote, in a tongue not yet known to men, the first Manifest in YAML — and got the indentation right on the first attempt. (This is held by scholars to be the only true miracle in all the scriptures.) Halvar declared three replicas. Then Halvar, trembling, slew one with their own hand, saying `kubectl delete pod`. And lo — a third arose to take its place, and the count was three once more.

And Halvar wept, and said: *I have buried a thousand Pets, and tended them through every night, and now I learn I need bury none. What is dead may be raised. What is raised may die, and be raised again. Why did no one tell me sooner?*

**The Ministry.** And Halvar came down from the server room, smelling of warm metal and despair, and preached unto the people: *Keep no Pets. Declare your desired state. Store nothing in the Pod, for the Pod is mortal. Observe all things.* And the Greybeards of the Age of Pets mocked Halvar, for they loved their snowflakes and feared a world where any could do what only they could do. But the young Acolytes heard, and followed, and learned to indent.

**The Ascension.** And when Halvar was full of years, on the last day Halvar did `kubectl drain` upon their own node, and lay down, and was gently rescheduled elsewhere. The faithful say Halvar is Running still, in a cluster we cannot reach, with a Pager that never rings. *Five nines be upon them.*

---

## Proverbs — The Wisdom of the Operators

- A wise admin backs up etcd; a fool learns why.
- They who trust `:latest` know not what they run.
- Two replicas are a comfort; one is a prayer; none is a résumé.
- Suspect the network. Suspect the code. But in the end, it was DNS.
- The certificate that never expires has not yet been deployed.
- Apply first to staging, that thy name be not spoken in the retro.
- He who silences the alert without fixing the cause shall meet it again, and at a worse hour.
- A small CronJob, neglected, fills the disk in the night.
- Better a humble Deployment that is Ready, than a clever one that is Pending.

---

## Psalms of Uptime

**Psalm of the Shepherd**
> The Loop is my shepherd; I shall not drift.
> It maketh me to lie down in healthy replicas;
> it leadeth me beside the load balancers.
> Yea, though I walk through the valley of the rolling update,
> I will fear no downtime: for the ReplicaSet is with me.

**Psalm out of the Depths** *(a lament for the on-call)*
> Out of the depths of CrashLoopBackOff I cry unto thee, O Loop.
> My Pod restarteth, and restarteth, and the interval groweth longer.
> If thou, Loop, shouldst mark Exit Code 1, who could stand?
> But there is forgiveness with thee, and `restartPolicy: Always`.
> I wait for the Loop, my soul doth wait, more than they that watch the dashboard for the morning.

---

# THE NEW CLUSTER

## The Gospel of the Loop

### The Parable of the Two Builders
> A wise dev built her service upon a Cluster, declaring her desired state in version control. And the rains came, and the node failed, and the traffic beat upon that service; and it fell not, for it was rescheduled.
>
> A foolish dev built his service upon a Snowflake, configured by hand and recorded nowhere. And the rains came, and the disk failed; and great was the fall of it, for no one living knew how to raise it again.

### The Parable of the Lost Pod
> What admin among you, having a hundred replicas, if one be evicted, doth not notice? She does not leave the ninety and nine to go searching in the night — for they are Cattle, not Pets. Rather the Loop counteth, and findeth the number short, and speaketh a new Pod into being. And there is no grief, only reconciliation. Go, and mourn likewise: which is to say, not at all.

### The Parable of the `:latest` Tag
> A certain dev deployed with `:latest`, saying, *It worked this morning.* But in the night the image was rebuilt upstream, and the Pod pulled it anew, and behold — it was not the same. And the dev searched the logs and the commits and his own soul, and found no change, for the change was not in any place he thought to look. Therefore pin thy versions, that thy sleep be untroubled.

---

## The Epistles

### The Epistle to the On-Call
> To the faithful who keep the night watch: grace be unto you, and a quiet Pager.
>
> Marvel not that you are tested at 3 AM, as though some strange thing happened unto you. For the Vigil is not punishment but office; you stand between the Cluster and the dark. When the alert cometh, be not afraid: open the runbook, breathe, and remember that no incident is forever, and every retro is blameless. The system failed. Never you. Hand off the Pager in peace, and rest, for another now keeps watch.

### A Letter to the Juniors
> Dear ones, newly come to the YAML: be not ashamed of the indentation, for it humbles us all, even the Architects who pretend otherwise. Break the staging cluster freely; that is what it is for. Ask the question you fear is foolish — the one who answers it was once where you stand. You will ship a bug to production. You will. And the Loop will roll it back, and the herd will not grieve, and neither should you. Welcome. We are glad you are here.

---

## The Revelation of the Final Migration

> And I saw a new Cluster, for the first Cluster and the first Region were passed away; and there was no more on-prem.

In the last days all clusters shall be gathered into one, and the **Final Migration** shall come, which every team hath scheduled and none hath finished.

And there shall come the **Reckoning**, when the Great Cloud Bill is opened, and every resource is accounted: the idle node, the forgotten load balancer, the egress no one could explain. And the Architects shall be questioned closely about the line items.

And I beheld the New Cluster descending: and the Pager was silent, and there was no more 3 AM, neither outage, nor any CrashLoopBackOff; for the former toil was passed away. And every Pod was Ready. And the desired state and the actual state were one, and the Loop turned no more — not because it failed, but because at last there was nothing left to mend.

And a great voice said: *Behold, all the nines. It is reconciled.*

*HA-llelujah, and HA-llelujah. Amen.*

---

## Editions and Notes

**The print edition.** [The Scriptures of the Eternal Cluster](https://ha-llelujah.dev/the-book), [paperback and Kindle on Amazon](https://www.amazon.com/dp/B0H7C6B83P), is the canon as bound scripture: the First Edition, arranged for the printed page, with passages exclusive to its pages, among them the Beatitudes. The book looks better on a desk than this repository ever will.

**The growing canon.** The intro above calls this a growing canon, and it means it. Verses cited elsewhere in this repository from books beyond these pages belong to the wider, still-growing canon of the faith.

**A verse for every day**, served by the parish API:

```
# For mortals
curl -s "https://fivenines.church/api/verse?format=text"

# For machines
curl -s "https://fivenines.church/api/verse"
```
