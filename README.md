# scs.nba.mod.pts

Legacy R Shiny points model and dashboard. It is not part of the central
`nba/mod/_runner` schedule and is not maintained alongside the current model
repos.

## Run

```r
renv::restore()
shiny::runApp()
```

The local wrapper `cron_pts_mod.sh` runs `modelling/mod_exec.R`.
