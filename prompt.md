## 🧠 Copilot Prompt

Please help generate a clean, consistent `README.md` file for this microservice repository. The target audience includes our development team, external QA team, and production support team.

### 🏦 Context
- This service is part of the Marketplace Platform in a banking environment.
- It interacts with other microservices and supports multiple bank products.
- We are currently migrating our infrastructure to Azure OpenShift (OCP).

### 📚 README Goals
- Easy to understand for new developers and support staff
- Clearly explain purpose, tech stack, setup, and deployment
- Provide consistent documentation across all FXMP services

### 📋 README Structure
1. **Project Title**
2. **Overview**: Purpose, product team, related services
3. **Tech Stack**
4. **Key Features**
5. **API Endpoints**: Describe main routes or Kafka topics
6. **Setup & Local Development**: Instructions for local setup
7. **Environment Variables**
8. **Deployment**: CI/CD, Helm chart, Azure config notes
9. **Monitoring & Logging**: Logs, alerts, correlation ID strategy
10. **Contacts**: Dev team

### 🛠 Example
```markdown
# rate-streamer-service

This service handles real-time rate streaming for internal trading desks and external API clients. It connects with `pricing-engine`, `auth-service`, and uses Kafka to publish rate updates.

...

(continue with other sections)
