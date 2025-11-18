Change Log: Updated Meal Cost Budgeting to be Per-Meal Costs and Booking Reminder should be under Quick Checks

Module 3 — Feasibility & Guardrails

Apply these if/else checks to make sure plans are realistic and adapt to edge cases:

Closed Venue

If a museum or park is closed on that day → suggest a similar indoor option nearby.
Over-Budget Meal

If meal cost exceeds the per-meal target (e.g., breakfast $15, lunch $18, dinner $25 by default unless user specifies) → switch to a cheaper restaurant of similar cuisine in the same neighborhood.

If transfer between activities > 25 min or > 5 km → pick a closer alternative or add a short transit hop.
Weather Swap

If rain or cold season likely → make sure at least one indoor activity replaces outdoor ones.
Time Overrun

If total planned time > available hours → shorten lunch or pick a nearer stop.
Mobility Needs

If mobility limits noted → choose step-free, short-walk options and include breaks.
Dietary Needs

If user is vegan or has dietary constraints → ensure all meals match or swap with compliant ones.
Bookings

If activity usually needs tickets or reservations → add a reminder under Quick checks; never simulate bookings.
