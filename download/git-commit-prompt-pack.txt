# Git Commit Prompt Pack

40 prompts that write clean, conventional commit messages
## Prompts

1. Analyze the following staged git diff and generate a Conventional Commits v1.0.0 compliant message. Format it as `type(scope): short description`. Use one of: feat, fix, docs, style, refactor, test, chlore. Keep the subject line under 50 characters.
2. Review this git diff and write a Conventional Commit message. Include a body that explains the 'why' behind the changes, not just the 'what'. Wrap body lines at 72 characters.
3. Based on the provided git diff, generate a breaking change commit message. Ensure it follows the convention by appending an exclamation mark after the type/scope (e.g., `feat(api)!:`) and include a `BREAKING CHANGE: ` footer describing the migration path.
4. Examine this set of uncommitted changes and suggest three different commit messages ranging from minimal (just the subject) to detailed (subject, body, and issue reference). Let me choose the best fit.
5. Look at this git diff which fixes a bug. Write a conventional fix commit message and append a footer referencing the issue tracker in the format `Fixes #123`.
6. Analyze the following documentation updates in the git diff and write a clear, concise `docs:` conventional commit. Summarize the user-facing impact in the body.
7. Review this git diff containing only unit and integration tests. Write a `test:` conventional commit message that specifies which modules or components were covered.
8. Based on this dependency upgrade diff, write a `chore(deps):` commit message that clearly states which packages were updated and whether they are major, minor, or patch bumps.
9. Examine this code refactoring diff. Write a `refactor:` commit message that explicitly states what technical debt was addressed without changing external behavior.
10. Read the following git diff for a performance optimization. Write a `perf:` conventional commit message that highlights the specific bottleneck resolved or metric improved.
11. Generate a conventional commit message for this UI/UX styling change. Use the `style:` type and mention the specific components or design tokens affected.
12. Analyze this messy git diff containing multiple distinct changes. Break them down and suggest how I should split them into separate atomic commits with appropriate conventional messages.
13. Write a `ci:` conventional commit message based on this diff involving GitHub Actions or CI/CD pipeline configurations.
14. Review this git diff for a new feature implementation. Write a conventional commit message and generate a corresponding release note bullet point for the changelog.
15. Inspect this git diff which reverts a previous commit. Write a conventional commit message starting with `revert: ` and include the hash and reason for the revert in the body.
16. Analyze this security patch diff. Write a conventional commit message using `fix:` or `security:` and provide a detailed, jargon-free explanation of the vulnerability addressed in the body.
17. Based on this localization or i18n git diff, write a conventional commit message detailing the languages, locales, or translation keys added or modified.
18. Look at this database migration diff. Write a conventional commit message that clearly indicates schema changes, specifying whether tables or columns were added, dropped, or altered.
19. Review this configuration file update diff (e.g., tsconfig, eslint, webpack). Write a conventional commit message using the `chore:` type with a descriptive scope.
20. Analyze this git diff and write a localized conventional commit message in [Language]. Ensure standard commit terminology remains accurate.
21. Examine this experimental or Work-In-Progress (WIP) diff. Write a temporary conventional commit message that flags the code as incomplete, using `wip:` or a clearly marked `refactor(wip):` format.
22. Review this git diff involving asset additions (images, fonts, icons). Write a conventional commit message using `chore:` or `assets:` with a clear description of the new resources.
23. Based on this monorepo git diff, write a conventional commit message that uses the workspace package name as the scope (e.g., `feat(auth-service): add jwt validation`).
24. Inspect this git diff where dead code was removed. Write a conventional commit message using `refactor:` or `chore:` that specifies which obsolete files, functions, or variables were purged.
25. Analyze this final release commit diff. Write a conventional commit message for a version bump (e.g., `chore(release): v1.2.0`) and list the primary feature additions included in the release body.
