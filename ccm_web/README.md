# Incott × Codex Community Malaysia

The first web integration lives inside SFE’s CCM page, not in a second community app.

## Included
- Six curated learning/tool resources with search, category filters and a saved list.
- A five-step project checklist with real progress, stored on the visitor’s device.
- Existing CCM training pathways, free builder pack and WhatsApp community links.
- Responsive CSS module and React component; no AI API, new login or fake activity.

## Install in the SFE Next.js application
Copy `community-hub.tsx` and `community-hub.module.css` alongside the existing CCM page. Import `CommunityHub` and render it before `TrainingPathways`. The artwork paths refer to SFE-owned artwork; supply your own licensed artwork in another application. React 19 and TypeScript are expected. The module does not contain SFE’s private authentication, commerce or databases.

## Boundaries
Bookmarks/checklists are browser-local and do not sync. Discussion currently happens in WhatsApp. This is the first web slice of Incott, not a migration of all Flutter/Firebase features. The original `news_app` and `news_admin` sources remain intact. A future member publishing system needs moderation, account-bound storage, consent and abuse controls before launch. Legacy mobile dependencies still require qualification.
