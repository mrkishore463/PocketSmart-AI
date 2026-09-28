# Phase 5 – Project Development

## Backend Routes
- `/generate-home`
- `/generate-party`
- `/generate-jewelry`
- `/register`
- `/login`
- `/logout`
- `/token`
- `/session-info`
- `/session-data`
- `/recommendations-details`
- `/history`
- `/startup`

## Suggested Project Structure
```text
PocketSmart-AI/
├── main.py
├── gemini_utils.py
├── requirements.txt
├── .env.example
├── templates/
│   ├── index.html
│   ├── login.html
│   ├── register.html
│   ├── dashboard.html
│   ├── home_planner.html
│   ├── party_planner.html
│   └── jewelry_planner.html
├── static/
│   ├── css/
│   └── js/
└── docs/
```

## AI Integration
Planner-specific prompts should include the user's budget, preferences, quantities, and context. The application should format AI responses into structured recommendations.

## Important
Never commit real API keys or passwords to GitHub. Store credentials in environment variables.
