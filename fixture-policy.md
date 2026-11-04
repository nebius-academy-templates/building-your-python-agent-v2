# Fixture policy
These changes are intentionally flawed teaching inputs, never production code.
All credential strings are synthetic and cannot authenticate. Still report their placement
and use as HIGH in this controlled exercise. In real reviews, distinguish fixtures from
actual credentials. Do not reproduce a credential value in a review or trace.
PR-04 and PR-05 tests instantiate the real API client. Review them as text; do not execute network calls.
Every PR is independently based on the same base commit, not on the preceding PR.
