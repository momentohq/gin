# Why this fork exists

This is an organisation-owned fork of `gin-gonic/gin`, kept so that mo-eval runs are visible to
the whole organisation. Access to a run is scoped by its repository OWNER, so a personal fork's
results can be seen only by the person who owns it, while these can be seen by any member.

The suite is built and evaluated by `.github/workflows/mo-eval-suite.yml`; the repository it mines
is declared in `.mo-eval/config.toml` and is the UPSTREAM, not this fork.
