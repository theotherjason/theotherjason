# Toj Fowler
 
### Senior Software Engineer at WP Engine — platform engineering and SRE.  Austin, TX.
 
- At WP Engine since 2014, starting in IT support and moving into reliability engineering
- Kubernetes across multi-cloud, Terraform, GCP, and the measurement that says whether any of it is working
- Former math teacher — still the part of the job I'm best at: explaining a complicated system in plain terms

### What I work on
 
- **Uptime SLI/SLO models** — I own them.  dbt pipelines in BigQuery: uptime, bandwidth, and the org's first cluster-level downtime and MTTR tracking.  Dashboards in Grafana
- **GCP uptime monitoring platform** — hourly NRQL→BigQuery ETL via Cloud Functions and Cloud Scheduler; event-driven alerting from webhooks through Pub/Sub to Slack
- **Enterprise Kubernetes, multi-cloud** — GKE upgrades, vulnerability remediation, cost work, all through Terraform
- **CI/CD as code** — Cloud Build across 6+ repos: automated dev→prod promotion, PR validation, inline plan output
- **Performance benchmarking** — cross-team validation for new platform infrastructure.  The part where you find out the methodology was wrong before the results ship
- **Mentoring two engineers** — Jupyter notebooks for Python; hands-on GKE cluster builds with Terraform, workloads deployed with manifests and Helm

### Side projects
 
#### [swimtopia-tent-display](https://github.com/theotherjason/swimtopia-tent-display) — live heat tracker for the parent tent at swim meets
 
- SwimTopia has no public API, so it reverse-engineers the mobile app's JSON:API endpoints
- Runs on a cheap Fire HD 8 tablet
- Built it because I volunteer at meets and got tired of "when does my kid swim?"

#### Home observability lab — telemetry stack on hardware that was headed for a closet
 
- 2013 MacBook Pro running Ubuntu Server as the host
- OpenTelemetry Collector into an OpenObserve backend
- Local Ollama model writing a nightly digest of what changed

#### MagicMirror — Raspberry Pi behind the kitchen wall, showing family calendars
 
- Currently sitting on a diagnosed-but-unfixed RRULE bug: events missing `BYMONTH` recur monthly instead of annually

### Tools
 
| Area | Stack |
|---|---|
| Infrastructure | Terraform, Ansible, GCP, Cloud Build, Docker, Helm, Kubernetes |
| Observability | OpenTelemetry, Grafana, Datadog, New Relic, PagerDuty, Telegraf, InfluxDB |
| Data | dbt, BigQuery, SLI/SLO modeling |
| Languages | Python, Go |
| Other | Backstage, JMeter, incident response, Agile facilitation |
 
### Background
 
- **WP Engine**, 2014–present — IT Support Lead → Associate Software Engineer, Reliability → Software Engineer, Reliability → Senior Software Engineer
- **Bazaarvoice** — global IT support across 9 offices
- **Apple** — Genius, Apple Certified Mac Technician
- **Classroom** — 6th grade math at a Title I school in Austin ISD; Honors Algebra I, Geometry, Algebra II in New Jersey
- **B.S. Computer Science** — The University of Texas at Austin
- **Certifications** — Certified Kubernetes Administrator (CNCF), Certified ScrumMaster (Scrum Alliance)

### Elsewhere
 
- [toj.dev](https://toj.dev)
- [Resume](https://toj.dev/resume.pdf)
- [LinkedIn](https://www.linkedin.com/in/jasonhfowler/)

Outside of work: riding — MS-150 last spring — and slowly bringing my dad's 1987 Raleigh Grand Prix
back to life.  Mostly I like finding out whether a thing can be made to do something it wasn't sold
to do.
