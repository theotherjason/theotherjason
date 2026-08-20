## Toj Fowler
 
Senior Software Engineer at WP Engine in Austin, TX — platform engineering and SRE.  Kubernetes
across multi-cloud, Terraform, GCP, and the reliability measurement that tells you whether any of it
is actually working.  I've been at WP Engine since 2014, starting in IT support and moving into
reliability engineering.
 
Before all that I taught math, and it still shows up in the job — explaining benchmark results to
leadership, or building a Python notebook and a hands-on GKE walkthrough for an engineer moving into
infrastructure work.
 
### What I work on
 
- Uptime SLI/SLO measurement — I own the models. dbt pipelines in BigQuery covering uptime,
  bandwidth, and our first cluster-level downtime and MTTR tracking, with dashboards in Grafana.
- A GCP uptime monitoring platform: hourly NRQL→BigQuery ETL through Cloud Functions and Cloud
  Scheduler, plus event-driven alerting routing webhooks through Pub/Sub to Slack.
- Enterprise Kubernetes across multi-cloud — GKE upgrades, vulnerability remediation, cost work, all
  through Terraform.
- Cloud Build CI/CD managed as code across 6+ repos, with automated dev→prod promotion, PR
  validation, and inline plan output.
- Cross-team performance benchmarking and validation for new platform infrastructure — the part
  where you find out the methodology was wrong before the results ship.
- Mentoring two engineers through Terraform, Kubernetes, and Python — Jupyter notebooks for the
  Python side, hands-on sessions spinning up a GKE cluster with Terraform and deploying workloads to
  it with manifests and Helm.
### Side projects
 
**[swimtopia-tent-display](https://github.com/theotherjason/swimtopia-tent-display)** — a live heat
tracker for the parent tent at swim meets.  SwimTopia has no public API, so this reverse-engineers
the mobile app's JSON:API endpoints and renders current and upcoming heats on a cheap Fire HD 8
tablet.  Built it because I volunteer at meets and got tired of the "when does my kid swim?"
question.  Open source.
 
**Home observability lab** — a 2013 MacBook Pro running Ubuntu Server as a telemetry host: an
OpenTelemetry Collector into an OpenObserve backend, with a local Ollama model producing a nightly
digest of what changed.  Deliberately built on hardware that was headed for a closet.
 
**MagicMirror** — Raspberry Pi behind the kitchen wall showing family calendars.  Currently sitting
on a diagnosed-but-unfixed RRULE bug where events missing `BYMONTH` recur monthly instead of
annually.
 
### Tools
 
| | |
|---|---|
| Infrastructure | Terraform, Ansible, GCP, Cloud Build, Docker, Helm, Kubernetes |
| Observability | OpenTelemetry, Grafana, Datadog, New Relic, PagerDuty, Telegraf, InfluxDB |
| Data | dbt, BigQuery, SLI/SLO modeling |
| Languages | Python, Go |
| Other | Backstage, JMeter, incident response, Agile facilitation |
 
### Background
 
- **WP Engine**, 2014–present — IT Support Lead → Associate Software Engineer, Reliability →
  Software Engineer, Reliability → Senior Software Engineer
- **Bazaarvoice** — global IT support across 9 offices
- **Apple** — Genius, Apple Certified Mac Technician
- **Classroom** — 6th grade math at a Title I school in Austin ISD, then Honors Algebra I, Geometry,
  and Algebra II in New Jersey
- **B.S. Computer Science**, The University of Texas at Austin
- **Certified Kubernetes Administrator** (CNCF), **Certified ScrumMaster** (Scrum Alliance)
### Elsewhere
 
- [toj.dev](https://toj.dev)
- [Resume](https://toj.dev/resume.pdf)
- [LinkedIn](https://www.linkedin.com/in/jasonhfowler/)
Outside of work I ride — the MS-150 last spring — and I'm slowly bringing my dad's 1987 Raleigh
Grand Prix back to life.  Mostly I like finding out whether a thing can be made to do something it
wasn't sold to do.
