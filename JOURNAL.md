## Week 7 — Issue selection

**Issue link:** https://github.com/ascherj/pathreview/issues/119

**Issue title:** Add inline docstrings to all public methods in core/services/

**Tier:** [ ] Tier 1 [X] Tier 2 [ ] Tier 3

**Problem summary:**
The public methods in the files under core/services don't have docstrings to explain what they do, what arguments they take, what they return, and any errors they may raise. A successful fix would make these methods easier to understand for any person who will later maintain this code base or needs to change any files/functionality in core/services. This problem affects the services layer of the code, but this fix is more important for maintainability down the line. I picked this problem because when I'm coding individually I normally don't put much effort into documentation. I think that getting practice with adding documentation to methods is going to be helpful for me if I work on a team at my work in the future.

**Branch name:** docs/110-services-methods-missing-docstrings

**Setup confirmation:** [X] App runs locally at localhost:5173

**Cohort ledger:** [X] Issue added to cohort ledger

## Week 8 — Reproduction & solution planning

**Reproduction commit link:** https://github.com/SahilMulki/pathreview/commit/6ea4b55a3e3c5b249c81aa15fe9d7cd4fbb02461

**Reproduction summary:**
This issue is a documentation issue, so it can't be reproduced in any traditional sense. This issue relates to the lack of inline docstrings for any methods in profile_service.py and review_service.py.

**PLAN.md link:** [PLAN.md](./PLAN.md)

**Walkthrough video (recommended):**

**Blockers or open questions:**
None

## Week 9 — Solution building & PR submission

### Check-in 1 (mid-week)

**Current progress:**
So far I've done the first two steps of my plan. The first step was to read and deeply understand each method in the files in core/services. The second step was to review other docstrings in the repo to make sure that ones I write will follow the expected style and conventions.

**Next steps:**
For the rest of the week I will work on actually writing the docstrings. Then once they are written I will write tests and make sure that all tests pass. Then I will create a pull request and submit.

**Blockers:**

---

### Check-in 2 (end of week)

**PR link:** [link to your submitted pull request]

**Branch:** docs/110-services-methods-missing-docstrings

**What you built:**
I added complete inline docstrings to profile_service.py and review_service.py. These docstrings are the full Google-style docstrings with Args:, Returns:, and Raises:. These docstrings also document the behavior of the method.

**Tests added or updated:**
I added a test under tests/unit/test_service_docstrings.py. This test checks all functions in core/services to make sure they have docstrings with sufficient detail (includes Args:, Returns:, and Raises:).

**Self-review confirmation:** [X] make check passes [X] make test-unit passes

**Draft PR feedback received from:** none
