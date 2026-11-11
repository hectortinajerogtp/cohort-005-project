# Cadence

An online course platform where learners buy courses and can ask for their money back shortly after purchase.

## Refunds

**Refund**:
The record of a learner asking for their money back on a Purchase, from the moment they ask until staff approve or decline it. A declined Refund is still a Refund; it returned nothing.
_Avoid_: Cancellation, Reversal, Chargeback, Pending chargeback, Cancel my purchase

**Requested Refund**:
A Refund awaiting a staff decision. A Refund is always Requested, Approved or Declined.
_Avoid_: Pending, Open, Pending chargeback, Open request

**Approve**:
Staff decision that a Refund is granted and money goes back to the learner.
_Avoid_: Process, Reverse, Accept

**Decline**:
Staff decision that a Refund is refused and nothing is returned.
_Avoid_: Reject, Deny

**Resolved**:
A Refund that staff have approved or declined.
_Avoid_: Closed, Completed

**Refund Window**:
The 14 calendar days after a Purchase during which a learner can ask for a Refund.
_Avoid_: Cancel window, Cancellation period

**Refund Eligibility**:
Whether a learner may ask for a Refund right now: inside the Refund Window, under the watch-time and completion limits, and not on a claimed team seat.
_Avoid_: Cancellation offer

**Refund Amount**:
What a Refund is for, fixed when it is Requested. It is always the Amount Paid, never the list price.
_Avoid_: Refundable amount, Reversal amount

**Amount Refunded**:
What was actually returned to the learner. It exists only once a Refund is Approved.
_Avoid_: Refund Amount (the two differ for a Declined Refund)

## Purchases

**Learner**:
A person who buys and takes courses, and the only one who can ask for a Refund.
_Avoid_: Student, customer, buyer

**Purchase**:
A learner's payment for a course. A learner can only ask for a Refund on their latest Purchase of a course, and a Purchase can have at most one Requested Refund at a time.
_Avoid_: Order, transaction

**Amount Paid**:
What the learner actually paid for a Purchase, after any PPP discount.
_Avoid_: Price, list price (that is the course's undiscounted price)

**PPP discount**:
A country-based reduction on a course's price for purchasing-power parity.
_Avoid_: Regional discount, country discount

**Seat**:
One place on a team Purchase that a team member can take up to access the course. A Seat is either Claimed or Unclaimed, and a Claimed Seat is not eligible for a Refund because it belongs to the team.
_Avoid_: Coupon, license (for a single place)

**Claimed Seat** / **Unclaimed Seat**:
A Seat that a learner has taken up, or one still waiting to be taken.
_Avoid_: Redeemed coupon, used coupon
