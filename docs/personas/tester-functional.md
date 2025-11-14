# Persona - QA Tester (functional team)

## Description

As a QA tester from the functional team, I validate that data transformation scripts and binaries work correctly both in isolation and when integrated with the platform. I ensure transformations meet business requirements, handle edge cases properly, and perform reliably in production-like conditions. I bridge the gap between functional development and platform integration.

## Needs

- **Test data access**: Representative datasets for testing transformations thoroughly
- **Local test environment**: Ability to test transformations independently of the platform
- **Integration test environment**: Platform staging environment mimicking production
- **Test automation tools**: Frameworks to create repeatable, automated tests
- **Expected output specifications**: Clear definitions of correct transformation results
- **Platform test interface**: Simple way to deploy and test transformations on the platform
- **Performance benchmarks**: Understanding of acceptable execution times and resource usage
- **Error scenario coverage**: Documentation of edge cases and error conditions to test

## Wishes

- **Comprehensive test coverage**: Confidence that all scenarios are validated before deployment
- **Quick feedback loops**: Fast test execution to iterate rapidly
- **Production parity**: Test environments that accurately reflect production behavior
- **Easy data setup**: Simple ways to create and manage test datasets
- **Integration confidence**: Assurance that platform updates won't break tested transformations
- **Automated regression testing**: Continuous validation that changes don't break existing functionality
- **Clear pass/fail criteria**: Unambiguous determination of test success
- **Isolated test runs**: Tests not interfering with other testers or environments

## Fears & Blockers

- **Environment inconsistencies**: Transformations working locally but failing on the platform
- **Insufficient test data**: Missing edge cases leading to production issues
- **Platform opacity**: Inability to verify transformation behavior within the platform
- **Integration surprises**: Platform behavior differing from expectations during integration
- **Regression risks**: Changes to transformations inadvertently breaking existing functionality
- **Time pressure**: Insufficient testing time leading to quality compromises
- **Platform changes**: Updates to the platform invalidating previous test results
- **Complex debugging**: Difficulty diagnosing failures in integrated environments
- **Test environment availability**: Conflicts or downtime preventing testing activities
- **Incomplete requirements**: Ambiguous acceptance criteria making test validation unclear
