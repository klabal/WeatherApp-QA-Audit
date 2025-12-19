# API Test Plan: WeatherApp Backend

| ID | Endpoint | Priority | Auth | Expected Result |
|:---|:---|:---|:---|:---|
| 1 | POST `/auth/login` | Critical | No | 200 OK. Returns auth token/session cookie. |
| 2 | POST `/auth/login` (Fail) | High | No | 401 Unauthorized for invalid credentials. |
| 3 | GET `/api/search?q={query}` | Critical | Yes | 200 OK. Returns array of matching locations. |
| 4 | GET `/api/search` (Empty) | High | Yes | 200 OK with empty array or 404 Not Found. |
| 5 | GET `/api/weather/{id}` | High | Yes | 200 OK. Returns temp, wind, precipitation JSON. |
| 6 | Protected Access | High | No | 401/403 for any API call without token. |
| 7 | POST `/api/favorites` | High | Yes | 201 Created. Location added to favorites. |
| 8 | DELETE `/api/favorites/{id}`| Medium | Yes | 200 OK or 204 No Content on removal. |
| 9 | GET `/api/favorites` | Medium | Yes | 200 OK. Returns user's bookmarked list. |
