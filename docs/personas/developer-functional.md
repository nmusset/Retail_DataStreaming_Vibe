# Persona - Developer (functional team)

## Description

As a developer from the functional team, I create data transformation scripts and binaries that process client data according to specific business rules. I focus on implementing the transformation logic without needing to understand the platform's internal architecture. The platform should be a reliable black box that executes my code and provides visibility into its performance.

## Needs

- **Clear interface contract**: Well-defined input/output specifications for my transformations
- **Local development capability**: Ability to develop and test transformations on my machine
- **Development documentation**: Clear guidelines on how to build compatible scripts/binaries
- **Observability**: Logs and metrics showing how my transformations perform in production
- **Error visibility**: Detailed error messages when my code fails or produces unexpected results
- **Debugging support**: Tools to troubleshoot issues without accessing the platform internals
- **Version control**: Ability to deploy and rollback different versions of my transformations

## Wishes

- **Platform abstraction**: The platform should "just work" - I shouldn't need to know its architecture
- **Quick deployment**: Fast and simple process to deploy new or updated transformations
- **Performance insights**: Metrics on execution time, resource usage, and throughput
- **Standard tooling**: Use familiar development tools and languages
- **Isolated testing environment**: Safe space to test changes before production deployment
- **Clear feedback loops**: Immediate notification if my code causes issues
- **Flexible implementation**: Freedom to use appropriate scripts or compiled binaries as needed

## Fears & Blockers

- **Platform coupling**: My code becoming too dependent on platform-specific features
- **Opaque failures**: Errors occurring without sufficient information to diagnose the cause
- **Performance mysteries**: My transformations running slowly without understanding why
- **Breaking changes**: Platform updates that break my existing transformations without warning
- **Limited debugging**: Inability to trace issues through the execution pipeline
- **Deployment complexity**: Complicated or manual deployment processes that slow development
- **Lack of standards**: Unclear best practices leading to inconsistent implementations
- **Resource limitations**: Platform constraints that prevent implementing necessary transformations
