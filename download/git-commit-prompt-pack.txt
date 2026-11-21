# Git Commit Prompt Pack

40 prompts that write clean, conventional commit messages
## Prompts

1. Analyze the following staged git diff and generate a Conventional Commits v1.0.0 compliant message. Use the `feat` type if new functionality was added, `fix` for bug fixes, `refactor` for code restructuring without behavior changes, or `docs` for documentation. Keep the subject line under 50 characters, use the imperative mood, and do not end with a period.

2. Review the git diff provided below and write a conventional commit message. The change includes breaking changes. Clearly indicate this by appending an exclamation mark after the type and scope (e.g., `feat(api)!:`) and include a `BREAKING CHANGE:` footer detailing the migration path.

3. Examine the following git status and diff. Generate a conventional commit message using the `chore` type for maintenance tasks, dependency updates, or tooling configuration changes. Ensure the subject line clearly states what dependency or file was modified.

4. Look at the provided code changes which implement a new UI component. Write a conventional commit message using the `feat(ui):` prefix. Provide a concise subject line, followed by a blank line, and a bulleted body explaining the specific visual or interactive updates made.

5. Analyze this git diff representing a performance optimization. Write a conventional commit message using the `perf:` prefix. In the body of the commit, briefly explain the performance bottleneck that was resolved and the measurable improvement or approach used.

6. Review the following code changes that fix a production bug. Generate a conventional commit message using the `fix:` prefix. Include the relevant issue tracker reference (e.g., `Closes #123`) in the footer of the commit message.

7. Based on the provided git diff, write a conventional commit message using the `refactor:` type. Ensure the commit body explicitly states that no functional or behavioral changes were introduced, focusing purely on code readability or architectural cleanup.

8. Examine the test files and implementation code in the provided git diff. Generate a conventional commit message using the `test:` type. Mention whether new tests were added, existing tests were updated, or test coverage was improved.

9. Analyze the changes in the documentation, README, or inline comments from the provided diff. Write a conventional commit message using the `docs:` type, ensuring the subject line accurately reflects which documentation section was updated.

10. Review the following git diff which introduces changes to CI/CD pipelines, GitHub Actions, or build scripts. Write a conventional commit message using the `ci:` or `build:` prefix, keeping the subject line direct and imperative.

11. You are given a massive git diff containing multiple unrelated changes. Analyze the diff, separate the changes logically, and generate the *primary* conventional commit message for the most critical feature or fix included, adhering strictly to the 50/72 rule.

12. Examine the provided git diff which reverts a previous commit. Generate a conventional commit message using the `revert:` prefix. In the subject line, include the first 7 characters of the commit hash being reverted, and explain the reason for the revert in the body.

13. Review the code changes supplied below and write a conventional commit message using the `style:` prefix. Use this for changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc.) and state the linter or formatter used if applicable.

14. Analyze the attached git diff and write a conventional commit message tailored for a monorepo structure. Use an appropriate scope corresponding to the package or workspace modified (e.g., `feat(auth-service): add OAuth2 login flow`).

15. Look at the provided experimental or Work-In-Progress (WIP) git diff. Write a temporary conventional commit message using the `wip:` prefix (or `chore(wip):`), ensuring it clearly communicates that the code is incomplete and subject to change.

16. Examine the provided bug fix git diff. Write a conventional commit message using the `fix:` type, and include a detailed reproduction step or root cause analysis in the commit body to help future maintainers understand *why* the bug occurred.

17. Based on the following git diff, write a conventional commit message for a security patch or vulnerability fix. Use the `fix(security):` prefix and provide a high-level summary of the vulnerability mitigated without disclosing exploitable specifics.

18. Review the provided git diff which updates third-party dependencies (e.g., `package.json`, `go.mod`, `Cargo.toml`). Write a conventional commit message using the `chore(deps):` prefix, naming the specific library updated and whether it was a major, minor, or patch update.

19. Analyze the database migration files in the provided git diff. Write a conventional commit message using the `feat(db):` or `fix(db):` prefix. In the commit body, explicitly state whether the migration is forward-only or if a rollback script is included.

20. Look at the code changes provided and write a conventional commit message focused strictly on accessibility (a11y) improvements (e.g., adding ARIA attributes, fixing keyboard navigation). Use the `feat(a11y):` or `fix(a11y):` prefix.

21. Examine the provided refactoring diff which removes deprecated code or legacy APIs. Write a conventional commit message using the `refactor:` prefix and include a `BREAKING CHANGE:` footer detailing what legacy functionality has been permanently removed.

22. Review the following git diff that translates UI text or adds localization files. Write a conventional commit message using the `i18n:` or `chore(l10n):` prefix, specifying the language locale code added or updated in the subject line.

23. Analyze the provided git diff containing configuration updates (e.g., ESLint, Prettier, TypeScript compiler options). Write a conventional commit message using the `chore(config):` prefix, summarizing the exact rule or compiler behavior modified.

24. Look at the provided code changes for a minor visual polish or CSS adjustment. Write a conventional commit message using the `style(css):` or `fix(ui):` prefix, ensuring the description clearly notes the layout property, spacing, or color palette adjusted.

25. Review the final release commit diff provided below. Generate a conventional commit message representing a version bump (e.g., `chore(release): v1.2.0`). Omit the body unless summarizing a high-level changelog of features and fixes included in this release tag.
