# Environment Variables

List of environment variables to configure DVC behavior.

- `DVC_EXP_BASELINE_REF`: Git revision for the baseline commit from which an
  <abbr>experiment</abbr> derives. Automatically set by DVC.
- `DVC_EXP_NAME`: Name of the <abbr>experiment</abbr>. Automatically set by DVC.
- `DVC_GLOBAL_CONFIG_DIR`: Directory in which DVC will look for global
  [configuration](/doc/user-guide/project-structure/configuration).
- `DVC_NO_ANALYTICS`: If `true`, disables
  [analytics](/doc/user-guide/analytics). Overrides `dvc config core.analytics`.
- `DVC_PAGER`: Set what program DVC uses for paging output (for example,
  `more`).
- `DVC_ROOT`: Root directory of your <abbr>DVC repository</abbr>. Automatically
  set by DVC.
- `DVC_SITE_CACHE_DIR`: Directory for the
  [site cache dir](/doc/user-guide/project-structure/internal-files#site-cache-dir).
  Overrides `dvc config core.site_cache_dir`.
- `DVC_STUDIO_OFFLINE`: If `true`, disables sharing
  [live experiments](/doc/studio/user-guide/experiments/live-metrics-and-plots)
  even if the DVC Studio token is set. Overrides `dvc config studio.offline`.
- `DVC_STUDIO_REPO_URL`: Set URL of Git remote associated with the DVC Studio
  project. Overrides `dvc config studio.repo_url`.
- `DVC_STUDIO_TOKEN`: Set DVC Studio access token to use. Overrides
  `dvc config studio.token`.
- `DVC_STUDIO_URL`: Set URL of Studio to use (in case of self-hosted DVC Studio
  instance). Overrides `dvc config studio.url`.
- `DVC_SYSTEM_CONFIG_DIR`: Directory in which DVC will look for system
  [configuration](/doc/user-guide/project-structure/configuration).

See also [DVCLive environment variables](/doc/dvclive/env).
