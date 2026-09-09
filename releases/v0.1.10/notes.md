UmaPilot v0.1.10

- Fix Narita Brian Independent Training start rejection 205. Each of his four alternative goal groups now uses the unique entry selected by determine_race_for_generate=0, instead of selecting the lowest program ID. Saved base or conditional variants are normalized to the generated goal.
- Stop before sending if the generated branch cannot be resolved uniquely. Other trainees keep their existing agenda behavior.

Verified live: the corrected Brian start was accepted, and a subsequent account refresh confirmed the active Grand Concert career. Exactly one start was submitted, without retries or career collection.

Validation: 55 relevant backend tests passed, including an exact comparison with the server-accepted agenda and an ambiguous-branch regression.

Updating from v0.1.8 also installs v0.1.9 automatic reconnection, approved-parent colors, and start diagnostics.
