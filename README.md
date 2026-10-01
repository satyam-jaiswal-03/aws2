Build the application as a professional, production-ready React frontend + Spring Boot backend.

Key requirements:

* Frontend communicates with Spring Boot through REST APIs.
* When a frontend request triggers backend processing, show backend logs/progress in the frontend in near real time, synchronized with the actual backend execution.
* Use a proper mechanism such as WebSocket/SSE for live log streaming rather than repeatedly starting the same backend request.
* Long-running operations must run asynchronously with a job/task ID, status tracking, cancellation/error handling, and result retrieval.
* Navigating between frontend pages must not restart an existing backend job. Preserve task state and reconnect to the existing task when returning to the page.
* Keep frontend and backend state clearly separated and synchronized.
* Implement proper loading, progress, success, failure, retry, timeout, and empty states.
* Use clean component/service architecture, reusable API clients, centralized error handling, logging, configuration, and environment-based settings.
* Follow production practices for security, validation, CORS, authentication readiness, scalability, and maintainability.
* Avoid unnecessary API calls and duplicate backend processing.
* Keep the UI responsive and professional, with clear task status and live execution logs.
* Prefer simple, robust solutions over unnecessary complexity.