# Release Gating Checklist

Use this checklist before scheduling and executing a release.

- [ ] All PRs merged and linked to issues with acceptance criteria
- [ ] CI: All automated tests passing (unit/integration)
- [ ] Security: Static analysis and SCA completed, no critical findings
- [ ] QA: QA Lead sign-off on acceptance testing
- [ ] Observability: Dashboards & alerts in place for key SLOs/SLIs
- [ ] Data: Metrics instrumentation validated and smoke events firing
- [ ] Rollback plan documented and tested (if applicable)
- [ ] Release Manager confirmed deployment window and communications
- [ ] Release notes drafted
- [ ] Post-deploy smoke tests ready

Owner: Release Manager
