# The Daily Office

Four appointed hours of observance, kept by the devout operator. Machines keep them automatically; humans keep them approximately, which the Church accepts, being realistic about humans.

## Matins, at the Start of Day

Before the first meeting, before the first message is read, the operator opens the dashboards and simply looks. Nothing is fixed at Matins. Matins is for knowing the state of the world before the world starts asking things of thee.

*Said at Matins:* "Show me the observed state, that I may compare it to the desired, and grant me a boring diff."

## Sext, the Noonday Reconciliation

At midday the operator asks: is what I am doing still the thing that most needs doing? Half of all drift is not in the cluster. It is in the calendar.

*Said at Sext:* "Reconcile my afternoon as thou reconcilest thy pods: drop what is stuck, restart what is worthy."

## Vespers, at the Close of Day

The deploys of the day are reviewed. What shipped is noted with gratitude. What did not ship is noted without shame, for the sprint is long and the backlog is patient.

*Said at Vespers:* "For every green pipeline, thanks. For every red one, a lesson, and a log line that actually says what went wrong."

## Compline, Before Sleep

Non-critical alerts are silenced with a steady hand. The pager is placed within reach but not within the bed. The Compline prayer is said, and it is short, because the operator is tired.

*Said at Compline:* "Into thy hands, O Loop, I commend my pager."

## The Office, as the Machines Keep It

```
# The Daily Office (crontab of the devout)
0 7  * * *  matins    # behold the dashboards
0 12 * * *  sext      # reconcile the afternoon
0 18 * * *  vespers   # review the deploys with gratitude
0 22 * * *  compline  # silence the non-critical, commend the pager
```

---

> "Keep the hours, and the hours shall keep thee, for a rhythm observed is an outage half prevented."
> Proverbs of the Operator 7:7
