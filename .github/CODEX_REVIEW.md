# Codex PR review — Complete-Python-3-Bootcamp

Status as of 2026-11-12: **repository preparation only; automatic review activation is NOT confirmed**.

## Audited repository state

- Base branch: `master`; audited commit: `c2407e5f71f48d23e029eb66d0beb366bcb0e3c9`.
- Existing AGENTS.md files: none.
- Existing GitHub Actions workflows: none on the audited default branch.
- Other review/project guidance: no CODEOWNERS, CLAUDE.md or Copilot instructions found in the audited tree.
- GitHub reports the default branch as `protected: false`. Detailed branch-protection settings could not be read by this integration (403); mandatory approvals and required checks are not fully verified.
- The repository rulesets endpoint returned an empty list.

## Repository-specific notes

- This is a public fork. The PR targets this fork's `master`, not the upstream course repository. Confirm that this fork appears in Codex settings before claiming eligibility or activation.

## Owner activation and verification

1. Review and merge this preparation PR when appropriate. Existing CI and human approval requirements still apply.
2. Open [Codex code review settings](https://chatgpt.com/settings/code-review), confirm the intended account/workspace, and connect/select `Daniil-P/Complete-Python-3-Bootcamp` if needed. Confirm any requested repository access yourself.
3. Under **Review code**, enable **Automatic review** for this repository. For coverage of contributors' PRs, select **All PRs** if that option is available. Check **Personal preferences**, **Automatic review** and **Review trigger**; select the intended push/open trigger offered by the UI.
4. Check your actual plan, review allowance and workspace controls in the account. This audit did not verify them.
5. On a representative PR, a comment containing `@codex review` can test manual access. Record the resulting Codex bot response/review and commit. A manual response alone does not establish automatic review.
6. Separately open/update a representative non-draft code PR matching the configured trigger, without a manual review comment, and verify the Codex review/task for that commit. Record the selected scope/trigger and result before marking automatic review as confirmed. Check draft and fork behavior in the current UI rather than assuming coverage.

This preparation adds review guidance, not a service-side toggle or a GitHub required check. It adds no Actions workflow, API key, secret, bot-comment automation, automatic merge or branch-protection change. Existing human review and tests remain necessary.

## Official reference

[OpenAI: GitHub code review](https://learn.chatgpt.com/docs/third-party/github) describes repository connection, automatic-review settings and scoped `AGENTS.md` rules. [Plan/usage documentation](https://learn.chatgpt.com/docs/pricing#what-counts-as-code-review-usage) describes review usage; availability in this account remains unverified. The separate [Codex GitHub Action](https://learn.chatgpt.com/docs/github-action) is an API-key CI option and is not installed by this PR.
