# AgriConnect – Agribusiness Solution Internship

**Internship Track:** Junior Software Developer – Agribusiness Solution
**Platform:** YuvaIntern (NSDC)
**Duration:** 13 September 2026 – 18 October 2026 (5 weeks)
**Intern:** Akash Srivastav

## Project Overview

AgriConnect is a proposed digital marketplace and advisory platform connecting
farmers/producers, distributors, retailers, logistics partners, and platform
administrators. This repository tracks the weekly deliverables produced during
the internship: requirements analysis, system architecture, module development,
testing/deployment planning, and final project documentation.

## Repository Structure

- `week1-requirements/` — Week1_Requirements_Analysis_Report.docx
- `week2-architecture/` — System Architecture & Design (upcoming)
- `week3-module-dev/` — Module Development & Integration Planning (upcoming)
- `week4-testing-deployment/` — Testing, Debugging & Deployment Strategy (upcoming)
- `week5-final-docs/` — Performance Evaluation & Final Documentation (upcoming)
- `README.md`

Each week's folder will contain the corresponding Word (.docx) report, any
supporting diagrams, and code or pseudocode where applicable.

## Progress Log

### 15 September 2026
- Repository initialized.
- Added project README with internship overview, planned repo structure, and
  progress log.
- Week 1 task (Requirements Gathering and Analysis) in progress: stakeholder
  research, user stories, use cases, and functional/non-functional
  requirements being drafted.

### 17 September 2026
- Completed and uploaded Week 1 deliverable: `Week1_Requirements_Analysis_Report.docx`.
- Report covers stakeholder identification, sector challenges, user personas,
  12 user stories, 4 detailed use cases, 27 functional requirements, 12
  non-functional requirements, a system data-flow diagram, a use case diagram,
  and 3 low-fidelity UI mock-ups.
- README updated to reflect Week 1 submission.
- Next up: Week 2 – System Architecture and Design.

### 26 September 2026
- Completed and uploaded Week 2 deliverable: `Week2_System_Architecture_Design_Report.docx`.
- Report defines a layered microservices architecture (six services behind a
  single API Gateway), a high-level architecture diagram, a component
  responsibility table, detailed module design with sample REST endpoints,
  a data model overview, a sequence diagram for the place-order flow, a
  deployment/infrastructure view, design rationale for scalability/security/
  modularity, technology stack recommendations, and full traceability back
  to all twelve Week 1 non-functional requirements.
- Grounded in real-world data: a case study on India's e-NAM agri-market
  platform, TRAI connectivity statistics, and UPI/NPCI payment volume data.
- README updated to reflect Week 2 submission.
- Next up: Week 3 – Module Development and Integration Planning.

## Tech Stack (Finalized in Week 2)

| Layer | Technology |
|---|---|
| Mobile Client | React Native |
| Admin Web Dashboard | React.js |
| API Gateway | Managed API Gateway (auth, rate limiting, routing) |
| Backend Services | Node.js + Express (TypeScript) |
| Primary Database | PostgreSQL (managed) |
| Cache | Redis (managed) |
| Message Queue | Managed queue (e.g. Amazon SQS or RabbitMQ) |
| Object Storage / CDN | S3-compatible storage + CDN |
| Hosting | Docker containers on a managed container service |
| Monitoring | Centralized logging + metrics dashboard |

Six core microservices — User & Auth, Crop Listing & Inventory, Market Price
Engine, Order & Logistics, Notification, and Analytics & Reporting — sit
behind a single API Gateway, with an event-driven message queue decoupling
notification dispatch from the main request path. Full rationale in
`week2-architecture/Week2_System_Architecture_Design_Report.docx`.

## License

This repository is for internship submission and educational purposes
