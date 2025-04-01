# Pull Request Checklist

Please ensure the following items are checked before merging:

### ✅ QA & Testing
- [ ] QA tests completed successfully - please see [QA processes/best practices](https://seafairworkspace.slack.com/docs/T011CB745ST/F07QHLD923A?focus_section_id=temp:C:SKAe5f69682764d4359a92217de3)
  - You can merge PRs **only if there is a successful run comment**.
  - Then remove the `run end-to-end test` label to proceed.
  - Based on [this](https://docs.google.com/spreadsheets/d/13C0u7rLBU3vmrjQ81lUOnAF8JQJmLdQlxZ5tFSD6pPw/edit?gid=0#gid=0) list, we can ignore relevant failures. However, if the PR is affected by a temporary failure, let's wait until the issue is fixed before re-running it

### 🚀 Release Impact
- [ ] Release does not significantly impact an existing product flow.
- [ ] Product documentation does not need updates or is already updated.
- [ ] Migration is **not** needed, or migration is ready to run.
- [ ] Migration does **not** lock a core database table.
- [ ] Release does **not** require downtime.

### 🔄 Testing & Dependencies
- [ ] Regression tests on related modules have been performed.
- [ ] Permissions, Alert Configurations, and other necessary data have been backfilled.
- [ ] Feature dependencies are deployed (e.g., **Calypso <> FE**).

---

**Note:** If any of the above criteria are not met, please discuss with your team before proceeding with the merge. 🚦
📌 **[View this checklist online](https://seafairworkspace.slack.com/docs/T011CB745ST/F07QHLD923A)**  