# AI-Powered Location & Interest-Based Mobile App

## Overview

A cross-platform mobile app that helps users find personalized places and events based on their location and interests. The app integrates external search APIs, advanced LLM summarization, and Splunk dashboards for monitoring and cost tracking.

---

## Repository Structure

- **/mobile_app/**: Flutter app source code (Android/iOS)
- **/backend/**: FastAPI (Python) or Node.js backend code
- **/openapi_spec/**: REST API specifications (OpenAPI YAML/JSON)
- **/docs/**: Project documentation, architecture diagrams, privacy and ethics notes
- **/splunk_dashboards/**: Splunk queries, dashboards, and config files
- **/tests/**: Integration and end-to-end test suites
- **/.github/**: GitHub Actions workflows, issue, and PR templates

---

## Getting Started

### Prerequisites

- Flutter SDK
- Python 3.10+ (for FastAPI) or Node.js (for Express)
- PostgreSQL or Google Firestore account
- Access to Bing/Google/Serper.dev API and Gemini/GPT-4o API
- Splunk Cloud/Enterprise account for dashboards

### Setup

1. **Clone the Repository:**
    ```sh
    git clone https://github.com/<your-org>/<your-repo>.git
    ```

2. **Mobile App:**
    - Navigate to `mobile_app/` and follow setup instructions in `mobile_app/README.md`.

3. **Backend:**
    - Navigate to `backend/` and follow setup instructions in `backend/README.md`.

4. **API Spec:**
    - See `openapi_spec/openapi.yaml` for API endpoints.

5. **Docs:**
    - Architecture and privacy notes are in `/docs/`.

---

## Documentation

- **System Architecture**: `/docs/architecture.md`
- **API Reference**: `/openapi_spec/openapi.yaml`
- **GDPR & Ethics**: `/docs/privacy_gdpr.md`, `/docs/ethical_ai.md`
- **Splunk Dashboards**: `/splunk_dashboards/`
- **Testing**: `/tests/`

---

## Contribution Guidelines

1. Open an issue for feature requests or bugs.
2. Fork and create a feature branch.
3. Ensure tests pass before submitting a pull request.
4. Follow the code style guidelines in the contributing docs (see `/docs/`).

---
