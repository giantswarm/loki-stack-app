---
name: Add application to playground catalog
about: Template for checklist when including new application in the playground catalog
labels: team/halo, area/managed-services, mission/managed-services/apps
assignees: giantswarm/team-halo
---

<!--
Boards:
* Please include in the "pre-playground - quality check" of this board https://github.com/orgs/giantswarm/projects/107
 
Source: https://github.com/giantswarm/giantswarm/blob/master/areas/managed-services/application-quality-bars.md
-->

# Playground catalog quality bar checklist

Upstream: [link to the upstream project repo]

## Checklist - MUST

- [ ] The application has a helm chart that is included in the catalog.
- [ ] The application starts and runs with a correct config on at least one current active release of Giant Swarm platform,
  (on every applicable provider).
- [ ] Docs - short and rather minimal, what is necessary to run the app:
  - [ ] must be available in the application repository and URL listed in chart's meta-data,
  - [ ] application requirements, dependencies and installation steps are clearly stated,
  - [ ] documentation must be provided for available installation options,
  - [ ] need to clearly state the version of GS platform and providers this application version is confirmed to run.
- [ ] Images: be re-tagged and present in our registries.

## Checklist - SHOULD

- [ ] Config: if only possible, default config must be good enough to start the application on an empty GS tenant cluster.
