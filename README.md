# ENvision

## About

*Enterprise Nation’s Platform for Intelligent Programmes & Onboarding*

---

ENvision is a professional-grade, multi-tenant SaaS platform designed for rapid creation, customisation, and management of onboarding flows, lead capture, and programme delivery—powered by cutting-edge AI and world-class cloud architecture.

## 🌟 What is ENvision?

ENvision enables Enterprise Nation and its partners to:
- Instantly launch fully branded, data-driven landing pages and signup journeys for any client or programme.
- Personalise every user experience with AI-powered diagnostics, analytics, and content recommendations.
- Support global operations with multi-region data residency, localisation, and robust compliance.
- Provide enterprise admins with full oversight and deep insights across all tenants and users.
- Seamlessly integrate with CRM, email, and analytics tools for a unified business workflow.

## 🔥 Key Features

- **Multi-tenant:** Each company/partner gets its own secure, isolated portal and dashboards.
- **Configurable Journeys:** Dynamic, schema-driven forms and flows for onboarding, signups, or data capture.
- **Advanced AI:** Automated diagnostics, recommendations, and analytics using Python, OpenAI, and .NET.
- **Global Ready:** Full multi-language, region-aware, and data-resident architecture.
- **Stunning UI:** Modern, customisable frontends (Next.js, shadcn/ui) with brand-level theming.
- **Cloud-Native:** Deployed with Docker, Kubernetes (AKS), and fully monitored with OpenTelemetry.
- **Integrated:** Out-of-the-box support for CRM (Dynamics 365), OAuth/SSO, email automation, and Stripe billing.

## 🛠️ How It’s Used

1. **For Programme Managers:**  
   Quickly spin up new landing pages or entire programmes, configure fields, branding, and workflows in minutes.
2. **For End Users:**  
   Discover available programmes, complete guided signups or diagnostics, and receive personalised recommendations.
3. **For Admins:**  
   Oversee all tenants, manage content and users, and unlock actionable insights—all in a single pane of glass.
4. **For Developers:**  
   Extend, customise, and automate every part of the platform with modern APIs and AI agent integrations.

## 🚦 Why ENvision?

- **Speed:** Launch new initiatives in hours, not weeks.
- **Personalisation:** Every journey, every user, every brand—tailored.
- **Compliance:** Data sovereignty, audit trails, and secure multi-region deployment baked in.
- **AI-Native:** Future-proofed with the latest in AI-powered automation and insights.

---

> **See What’s Next. Build What’s Possible. — ENvision by Enterprise Nation**



## Tech Stack

- **Backend**: ASP.NET Core (C#)
- **Frontend**: Next.js with TypeScript
- **AI Engine**: Python with modern AI/ML libraries
- **Database**: TBD (PostgreSQL recommended)
- **Infrastructure**: Docker, Kubernetes (planned)

## Project Structure

```
MultiTenant-SaaS-AI/
├── src/
│   ├── backend/          # ASP.NET Core API
│   ├── frontend/         # Next.js TypeScript frontend
│   └── ai/              # Python AI/ML logic
├── docs/                # Project documentation
├── devlogs/             # Development logs
├── diagrams/            # Architecture diagrams
└── .github/             # GitHub Actions workflows
```

## Quick Start

1. **Backend Setup**: See [src/backend/README.md](src/backend/README.md)
2. **Frontend Setup**: See [src/frontend/README.md](src/frontend/README.md)
3. **AI Engine Setup**: See [src/ai/README.md](src/ai/README.md)
4. **Architecture**: See [docs/architecture.md](docs/architecture.md)
5. **Development Setup**: See [docs/setup.md](docs/setup.md)

## Multi-Tenancy Features

- Tenant isolation at the database level
- Customizable branding per tenant
- Role-based access control (RBAC)
- Usage analytics and billing per tenant
- AI model customization per tenant

## Development

This project follows a microservices architecture pattern with clear separation of concerns:

- **Backend**: Handles business logic, authentication, and API endpoints
- **Frontend**: Provides the user interface and client-side functionality
- **AI Engine**: Processes AI/ML workloads and model inference


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. 