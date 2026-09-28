# Phase 3 – Project Design

## Architecture
Frontend → FastAPI Backend → Planner Logic → Gemini AI → Structured Response → Frontend

## Main Components
- Jinja2/HTML/CSS/JavaScript frontend
- FastAPI application layer
- Gemini 1.5 Flash Pro AI layer
- Authentication/session layer
- Recommendation/history layer
- External or mock product/service sources

## Planner Flow
### Home
Budget + rooms + quantities → AI → furniture/decor/lighting suggestions

### Party
Budget + event + guests + venue requirements → AI → food/venue/decor suggestions

### Jewelry
Budget + occasion + style + optional outfit image → AI → jewelry suggestions

## Security Design
Authentication, protected routes, session handling, environment variables for API credentials, and input validation.
