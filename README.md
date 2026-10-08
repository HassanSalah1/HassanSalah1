# Hassan Salah

**Software Engineer, Tech Lead & DevOps** · Cairo, Egypt

I build production backends, lead the delivery around them, and run the AWS they ship on —
architecture, infrastructure, CI/CD, and the teams that keep them up.

By day I operate live APIs and the fleets behind them. In parallel I lead product delivery across
healthcare, logistics, education, and legal platforms — mostly private work
for clients and products that cannot live in a public repo.

## Focus

- **Production engineering** — APIs, background jobs, incident response, deploys
- **DevOps** — Terraform, autoscaling web and worker fleets, GitHub Actions releases, and CloudWatch alarms
- **Tech leadership** — scoping, architecture, reusable admin platforms, handing teams a stack they can actually ship
- **Arabic-first products** — RTL, bilingual UX, and operations software used in Egypt and the GCC

## What I build

**Mobility & logistics**  
Real-time ride dispatch, scheduled trips, driver matching, fleet admin, and B2B freight marketplaces (orders, drivers, invoicing).

**Healthcare & pharma**  
Clinic scheduling, pharmacy POS, patient-support CRMs, remote-care programs, and hospital procurement workflows.

**Education & learning**  
LMS platforms, assessment engines, Quran academies, and bilingual course experiences.

**Operations SaaS**  
Nursery / childcare management, legal-services directories, Umrah travel marketplaces, loyalty programs, and Filament admin platforms with RBAC.

**Cloud & reliability**  
Infrastructure as code for live systems: load balancers, autoscaling web and worker fleets, managed Postgres and Redis, private networking, and IAM. Production deploys run through GitHub Actions and roll the fleet with capacity held up, then check that instances are on the commit that just shipped. App, worker, and Nginx logs go to CloudWatch, with alarms for errors, latency, database, and cache.

Most of this runs in private repositories. The contribution graph is the public trail; the products are not.

## Stack

| | |
|---|---|
| **Languages** | PHP · Python · TypeScript · SQL |
| **Backend** | Laravel · Filament · Django · NestJS · REST · Redis · queues (Celery, RQ) |
| **Frontend** | React · Next.js · Vue · Livewire |
| **Data** | MySQL · PostgreSQL · MongoDB |
| **Cloud** | AWS (EC2, ASG, ALB, RDS, ElastiCache, CloudWatch, IAM) · Terraform · GitHub Actions · Nginx · Docker |

## How I work

- Split large products into APIs, admin portals, booking surfaces, and infra — then keep the domain model consistent.
- Write the architecture, the deploy path, and the security baseline so other engineers can move without guessing.
- Own the path from commit to production: the workflow, a rolling refresh that does not drop capacity, and a check that the fleet is on that commit.
- Scale web on CPU and latency, workers on queue depth, and alert before the database or cache runs hot.
- Own production: dispatch bugs, OTP/auth failures, AWS incidents, and the runbooks that prevent the next one.
- Repeat a delivery pattern: Laravel + Filament + RBAC for operations software; Django + Redis + AWS when the system has to stay up under live load.

## Contact

- Email: dev.hassan.salah@gmail.com
- GitHub: [HassanSalah1](https://github.com/HassanSalah1)
