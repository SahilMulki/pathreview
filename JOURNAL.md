## Week 7 — Issue selection

**Issue link:** https://github.com/ascherj/pathreview/issues/119

**Issue title:** Add inline docstrings to all public methods in core/services/

**Tier:** [ ] Tier 1 [X] Tier 2 [ ] Tier 3

**Problem summary:**
The public methods in the files under core/services don't have docstrings to explain what they do, what arguments they take, what they return, and any errors they may raise. A successful fix would make these methods easier to understand for any person who will later maintain this code base or needs to change any files/functionality in core/services. This problem affects the services layer of the code, but this fix is more important for maintainability down the line. I picked this problem because when I'm coding individually I normally don't put much effort into documentation. I think that getting practice with adding documentation to methods is going to be helpful for me if I work on a team at my work in the future.

**Branch name:** docs/110-services-methods-missing-docstrings

**Setup confirmation:** [X] App runs locally at localhost:5173

**Cohort ledger:** [X] Issue added to cohort ledger
