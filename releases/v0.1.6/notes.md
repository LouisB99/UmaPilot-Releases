# UmaPilot v0.1.6

Guest parents and saved execution loops are now clearer and more reliable.

- Consider saved guests even when they are missing from the latest shortlist.
- Try the other eligible parent if the preferred guest cannot be used; preserve approved parent lineage.
- Show Guest planned and Owned veteran separately in Next Action, with portraits.
- Show the guest attempts checked before launch in the actual run receipt.
- Mark a recommendation as applied only when its roles and closure match the saved execution loop.
- Preserve in-progress loops when rebuilding recommendations.

Verified with 127 offline backend tests, 10 UI logic tests, and a browser layout check. Includes fresh rental allowance checks across daily reset and the actual guest trainer ID in compiled launch requests. No live career was started during testing.
