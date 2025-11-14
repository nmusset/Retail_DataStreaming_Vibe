# Persona - QA Tester (platform team)

## Description

As a QA tester from the platform team, I ensure that the core platform infrastructure remains stable, reliable, and backward-compatible as it evolves. I validate that platform changes don't break existing client workflows, transformations, or integrations. I'm responsible for protecting all stakeholders from regressions while enabling the platform to improve and scale.

## Needs

- **Comprehensive test suite**: End-to-end tests covering all critical platform workflows
- **Existing workflow catalog**: Inventory of all active client configurations and transformations
- **Automated regression testing**: Continuous validation against real-world scenarios
- **Performance testing tools**: Capability to validate system behavior under load
- **Platform monitoring access**: Visibility into system health metrics and logs
- **Test data repository**: Collection of representative transformations and data samples
- **Staging environment**: Production-equivalent environment for pre-release validation
- **Change documentation**: Clear descriptions of platform modifications and potential impacts

## Wishes

- **Zero regression deployments**: Platform updates that never break existing workflows
- **Automated compatibility checks**: Tools that validate backward compatibility automatically
- **Early issue detection**: Problems discovered in testing, not production
- **Comprehensive coverage**: Tests representing all possible client scenarios
- **Fast test execution**: Quick validation cycles without sacrificing thoroughness
- **Clear impact analysis**: Understanding which workflows might be affected by changes
- **Proactive monitoring**: Continuous validation that production remains healthy post-deployment
- **Rollback confidence**: Verified ability to revert changes if issues arise

## Fears & Blockers

- **Breaking production workflows**: Platform changes causing client data delivery failures
- **Undiscovered edge cases**: Scenarios not covered by tests causing production issues
- **Test environment drift**: Staging not accurately representing production conditions
- **Incomplete test coverage**: Missing critical paths in the test suite
- **Time constraints**: Pressure to release quickly without adequate testing
- **Complex dependencies**: Difficulty predicting how changes affect interconnected components
- **Silent failures**: Issues that don't trigger alerts but affect data quality
- **Scale differences**: Problems only appearing under production load levels
- **Unknown transformations**: Client scripts with behaviors not reflected in tests
- **Monitoring gaps**: Production issues not visible in available metrics
- **Legacy workflows**: Older integrations lacking documentation or test coverage
