# Detailed Defect Log: WeatherApp

| Bug ID | Category | Severity | Description | Actual Behavior |
|:---|:---|:---|:---|:---|
| BUG-01 | Auth | Medium | Misleading login error. | Shows "Username is required" instead of auth error. |
| BUG-02 | UI/Auth | Low | Missing "Remember Me". | Feature missing from the login form. |
| BUG-03 | Search | High | Search result clutter. | Returns irrelevant global results for specific cities. |
| BUG-04 | Search UI | Low | No "Reset" filters. | Requires page refresh to clear search results. |
| BUG-05 | Bookmarks | Medium | Guest bookmarking UI. | Icon visible but doesn't function for guests. |
| BUG-06 | Bookmarks | Medium | Stale UI on removal. | List updates only after manual page refresh. |
| BUG-07 | UI/UX | Low | Poor location highlight. | City name is hard to find on the dashboard. |
| BUG-08 | Data | **Hold** | Weekly temp discrepancy. | Night temps vary significantly vs trusted sources. |
| BUG-09 | Data | **Hold** | Sunrise/Sunset times. | 1-2 min error; Time zone issues for global cities. |
| BUG-10 | Data | Critical | UV Index units. | Shown as percentage instead of 0-11 scale. |
| BUG-11 | Data | Critical | Precipitation mismatch. | System reports 100% while sources show 25%. |
| BUG-12 | Data | **Hold** | Hourly data mismatch. | Discrepancies vs Google; Time zone issues. |
| BUG-13 | Features | Low | No Imperial units. | Only Metric system (C, km/h) supported. |
| BUG-14 | UI/Visual | Medium | Icon mismatch. | Sunny icon shown during rain data. |
| BUG-15 | Geo | High | Broken location label. | City name doesn't appear in label after permission. |
| BUG-16 | Geo | Medium | No Revoke option. | Must use browser settings to stop sharing location. |
| BUG-17 | Geo | Medium | Raw error text. | Denying location shows unstyled error message. |
| BUG-18 | Security | Medium | Spec. char handling. | Login fields don't sanitize symbols like `ĄĖĘ`. |
