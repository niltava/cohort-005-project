# Revoke Enrollments on refund approval instead of deleting them

When a Platform Admin approves a Refund Request, the Learner loses access straight away, at approval rather than when the money is issued. We mark the Enrollment as revoked and keep it, along with all of the Learner's progress (lesson progress, watch history, quiz attempts, ratings). We don't delete anything. Deleting can't be undone. The watch history is the evidence behind the approval decision. And a Learner who buys the course again, or claims a Seat, should get their old progress back.

## Consequences

- Any code that asks "is this person enrolled?" or counts Enrollments (course access, instructor student lists, enrollment counts, analytics) has to leave out Revoked Enrollments.
- Buying again or claiming a Seat reinstates the existing Enrollment instead of creating a second one.
