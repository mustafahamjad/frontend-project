# frontend-project
NutriPlan – A responsive React web app for smart meal planning, recipe search, nutrition tracking, and auto-generated grocery lists with weather-aware suggestions and nearby store maps.
**Design principles:** presentational components stay dumb (props in, JSX out); container components handle data fetching via hooks; shared state lives in Context only where multiple features need it; everything else stays local state.

## External APIs

| API | Purpose |
| --- | --- |
| Spoonacular / Edamam Recipe API | Search recipes by ingredient, diet, cuisine, and allergy filters |
| USDA FoodData Central API | Detailed nutrition data (macros, vitamins, minerals) |
| Open Food Facts API | Barcode-based product lookup for packaged foods |
| OpenWeatherMap API | Weather-based meal suggestions |
| Google Maps Places API | Locate nearby grocery stores |

## Features

### Must-Have (Core MVP)
- Recipe search with ingredient/diet/cuisine filters
- Recipe detail page with instructions, image, and nutrition facts
- Nutrition breakdown (calories, macros) with chart visualization
- Save/favorite recipes (persisted in localStorage)
- Weekly meal planner calendar
- Auto-generated grocery list from planned meals
- Fully responsive layout (mobile, tablet, desktop)

### Nice-to-Have (Stretch Goals)
- Weather-based meal suggestions
- Nearby grocery store map (Google Maps Places API)
- Barcode/product lookup (Open Food Facts)
- Dark mode toggle
- Print/export grocery list as PDF

## Design Strategy

- **Visual style:** Clean, food-forward — soft off-white background, deep green accent, warm neutral tones, generous white space
- **Typography:** Poppins (headings) + Inter (body)
- **Layout:** Card-based recipe grid, calendar-style planner grid, checklist grocery list
- **Navigation:** Persistent top navbar (desktop), collapsible bottom tab bar (mobile)
- **Feedback states:** Skeleton loaders, empty-state illustrations, toast notifications
- **Accessibility:** Semantic HTML, ARIA labels, visible focus states, WCAG AA contrast
- **Design process:** Low-fidelity Figma wireframes → design-token file (colors, spacing, radii) for consistent Tailwind usage

## Timeline (7 Days)

| Day | Focus |
| --- | --- |
| Day 1 | Planning & setup — wireframes, project scaffolding, folder structure, routing |
| Day 2 | Core layout & design system — Navbar, Footer, theme, reusable UI components |
| Day 3 | API integration layer — service layer, env vars, Recipe & Nutrition API hooks |
| Day 4 | Core features — search/filtering, recipe detail, nutrition charts, favorites |
| Day 5 | Secondary features — meal planner, grocery list, store finder, weather widget |
| Day 6 | State, persistence & polish — localStorage, loading/error states, accessibility, animations |
| Day 7 | Testing & submission — cross-browser testing, bug fixes, performance check, deployment |

**Estimated effort:** ~35–40 hours across 7 days (5–6 focused hours/day)

## Author

**Muhammad Mustafa** — Registration No. 5112124012
