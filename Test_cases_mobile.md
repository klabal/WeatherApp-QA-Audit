# Mobile Compatibility Test Cases (Google Pixel 6, Google Chrome)

| ID | Feature | Priority | Test Steps | Expected Result | Status |
|:---|:---|:---|:---|:---|:---|
| M1 | Hamburger Menu | High | 1. Open app on Pixel 6. 2. Tap the menu icon. | Menu expands smoothly without overlapping search. | **Pass** |
| M2 | Search Bar Focus | High | 1. Tap the search bar. 2. Start typing. | Keyboard appears; "Search" button remains visible or accessible. | **Fail** |
| M3 | Mobile Layout | Medium | 1. View weekly forecast on mobile. | Columns stack vertically; no horizontal scrolling needed. | **Pass** |
| M4 | Touch Targets | Medium | 1. Try to click "Bookmark" icon. | Icons are large enough for thumb interaction (min 44x44px). | **Fail** |
| M5 | Orientation | Low | 1. Rotate device to Landscape mode. | Layout adjusts correctly without breaking UI. | **Hold** |
