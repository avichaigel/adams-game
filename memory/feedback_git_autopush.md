---
name: feedback-git-autopush
description: After every code change in Adam's game, automatically run git add + commit + push
metadata:
  type: feedback
---

After every file edit in Adam's First Game project, always run git commit and push automatically without waiting to be asked.

**Why:** Adam explicitly requested this to avoid having to manually push each time.

**How to apply:** After every Edit or Write to index.html (or any game file), immediately run:
```
cd "c:\Users\User\Documents\Adam's First Game"
git add index.html
git commit -m "<short description of change>"
git push
```
