# Reef — Finance & Workspace Dashboard

An internal dashboard combining financial tracking with team/workspace management, built with a bilingual (Arabic/English) interface.

## Key Features

- **Finance Module** — track and manage financial records
- **Workspace Management** — manage workspaces/teams and their related resources
- **Dashboard Overview** — consolidated summary view across modules
- **Multi-language Support** — Arabic/English localization
- **Reusable Component Library** — shared components layered over both PrimeNG and Angular Material

## Tech Stack

| Layer | Technology |
|---|---|
| Framework | Angular 13 |
| UI Kits | PrimeNG + Angular Material |
| Styling | Bootstrap |
| i18n | ngx-translate |

## Architecture Highlights

```
src/app/
├── finance/        # financial records module
├── workspace/       # workspace/team management
├── dashboard/        # overview dashboard
└── shared/           # shared services, pipes, PrimeNG/Material/ngx wrapper modules
```

## Getting Started

```bash
npm install
ng serve
```

Navigate to `http://localhost:4200/`.
