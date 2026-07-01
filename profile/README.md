
### Conventions

**dev envrionmet:** Makefile

**Local hooks:** lefthook built by source enforced by scripts

**package manager:** `pnpm` — do not use `npm`

**deployments strat**: artifact promotion

**branching strat**: trunk based development, branches follow conventional commits with path-based scoping:

  ```
  type/scope-description              # base-branch
  _type/scope-description/sub-task    # sub-branch
  __type/.../sub-sub-task             # nested sub-branch
  ```

  > commit example: `type(scope): description` — [conventional commits](https://www.conventionalcommits.org)
