# AlgoCatalyst — organization defaults

This repository holds AlgoCatalyst's **default community health files** — the standard files
GitHub automatically applies to every repository in the organization that doesn't define its
own. See [GitHub's docs](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file).

It is intentionally **public**: that is what lets these defaults reach the org's
repositories (including private ones). It contains only generic, non-sensitive files —
never product code.

## Contents

- `PULL_REQUEST_TEMPLATE.md` — the default pull-request description shown when a PR is opened
  in any org repo that has no template of its own. (The `/pr` command writes its own body; this
  is the fallback for hand-opened PRs, and it carries the `Closes #` reminder the required
  "Verify linked issue" check depends on.)

Managed as part of [`foundation`](https://github.com/AlgoCatalyst/foundation) (build step 5b).
