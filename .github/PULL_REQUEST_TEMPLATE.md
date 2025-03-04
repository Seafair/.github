# Pull Request Checklist

Please ensure the following items are checked before merging:

## ✅ QA & Testing
- [ ] QA tests completed successfully - please see [QA processes/best practices](#)
  - You can merge PRs **only if there is a successful run comment**.
  - Then remove the `run end-to-end test` label to proceed.

## 🚀 Release Impact
- [ ] Release does not significantly impact an existing product flow.
- [ ] Product documentation does not need updates or is already updated.
- [ ] Migration is **not** needed, or migration is ready to run.
- [ ] Migration does **not** lock a core database table.
- [ ] Release does **not** require downtime.

## 🔄 Testing & Dependencies
- [ ] Regression tests on related modules have been performed.
- [ ] Permissions, Alert Configurations, and other necessary data have been backfilled.
- [ ] Feature dependencies are deployed (e.g., **Calypso <> FE**).

---

**Note:** If any of the above criteria are not met, please discuss with your team before proceeding with the merge. 🚦
📌 **[View this checklist online](https://seafairworkspace.slack.com/docs/T011CB745ST/F07QHLD923A)**  