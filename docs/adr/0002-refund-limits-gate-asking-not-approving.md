# Refund limits decide who may ask, not who may be approved

The refund limits (14-day window, 2 hours watched, 50% of lessons completed) only decide whether a Purchaser may *raise* a Refund Request. Once a request is Open, a Platform Admin may approve it even if the Purchaser is now over a limit. The review screen shows live figures and flags any broken limit, but doesn't block approval. We chose this because the Learner keeps access while the request is Open and can drift over a limit just by waiting for review, and because the decision is meant to be a human judgement, not a rerun of the eligibility check.

## Considered Options

- **Snapshot the figures when the request is raised**: rejected. The Platform Admin should see what the Learner has consumed by the time of the decision, since that's what the money pays for.
- **Re-check the limits at approval and block**: rejected. It punishes slow reviews and adds nothing a human can't already see from the flags.
