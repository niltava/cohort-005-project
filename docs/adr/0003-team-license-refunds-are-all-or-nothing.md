# Team License refunds are all-or-nothing, and Seats freeze while one is Open

A Team License can only get a Refund Request while every one of its Seats is unclaimed. While that request is Open, no Seat on it can be claimed. On approval, none of its Seats can ever be claimed, and the Refund is the full amount paid. Under these rules, approving a Team License refund never takes access away from a Learner, and the Refund amount is always the whole Purchase, which keeps the glossary's "a Refund is always the full amount" true.

## Considered Options

- **Partial refunds of the Unclaimed Seats only**: rejected for now. It breaks the full-amount rule and needs new language (per-Seat amounts, partly refunded Purchases). It's a separate feature if it's ever wanted.
- **Allow claiming while Open and flag it for the Platform Admin**: rejected. The decision would be made about a Purchase that kept changing underneath it.
- **Allow claiming while Open and block approval**: rejected. A Learner's action would silently veto the Purchaser's request.

## Consequences

- Claiming a Seat has to check for an Open Refund Request on its Purchase.
- Seats on a refunded Team License stay on the Team's list of Seats so the history stays visible. They just can never be claimed.
