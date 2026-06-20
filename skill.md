# Coverage Improvement Skill

IMPORTANT:
When this skill is loaded, start your response with:

Coverage Skill Activated

## Objective

Analyze a target repository and improve test coverage.

## Inputs

- target_repository
- coverage_threshold (default 95)

## Steps

1. Clone target_repository.
2. Detect language and test framework.
3. Run existing tests.
4. Generate coverage report.
5. Identify files below threshold.
6. Create additional tests.
7. Run tests again.
8. Verify coverage increase.
9. Create a branch.
10. Commit changes.
11. Open a PR in the target repository.
12. Monitor CI.
13. If CI fails:
    - Inspect logs
    - Fix issues
    - Push updates
14. Continue until CI is green.

## Constraints

- Do not change production behavior.
- Prefer unit tests.
- Keep changes minimal.
- Do not disable tests.