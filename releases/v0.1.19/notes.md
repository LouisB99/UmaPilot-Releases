# UmaPilot v0.1.19

- Use the project running style with explicit position assumptions: Front Runner leads, Pace Chaser sits near the front, Late Surger follows, and End Closer runs towards the back.
- Compare equally weighted fields of 9, 12 and 16 runners. Block impossible position/overtaking conditions before scoring; do not assign numeric benefit to tactical alternatives the simulator cannot safely isolate.
- Rebuild older Brain analyses and explain the position assumptions in the recommendation UI.

Validated with 66 Brain tests, the actual bundled Umalator worker, a production build, responsive browser checks, and 22 existing guest/parent-selection regressions. Shadow Break contributes zero in the leading Front Runner scenario; Red Shift and Angling and Scheming remain simulatable. Other race events remain approximations.

This release does not add unowned, permanently borrowed loop slots. That requested feature remains pending. No accounts, credentials or saved projects are included in this update.
