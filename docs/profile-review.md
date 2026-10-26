# Profile revision review

The introduction returns to a personal, confident tone. Three restrained cyan panels establish software, firmware/systems and AI. A two-by-two showcase keeps project benefits visible, with architecture and reliability evidence in one optional dropdown. Technology groups cover experience beyond the showcased repositories. Faith wording is preserved.

## Rendered previews

[Before this revision](preview-before.png) · [After: desktop light](preview-desktop.png) · [After: mobile dark](preview-mobile.png)

These are actual local renders of GitHub's Markdown API output with github-markdown-css. They reproduce the README content area, not GitHub's surrounding profile layout. On phones the requested two-column cards remain side by side; the pillar panels wrap.

## Verification

- [x] GitHub Markdown API accepted the README, tables, details and image attributes.
- [x] Rendered at 1040px, 390px and 320px in light and dark themes.
- [x] No page or card-table horizontal overflow, including with all dropdowns open.
- [x] All local images loaded; every image has alt text or is explicitly decorative.
- [x] Dropdown keyboard activation tested.
- [x] All 19 unique GitHub/Chrome Store destinations returned HTTP 200.
- [x] LinkedIn profile and EduFeed media verified in the user's local browser; automated requests return LinkedIn's 999 response.
- [x] Genuine project images; no generated product screenshots or exposed credentials.
- [x] No application repository, account setting, pin or repository description modified.

## Suggested profile metadata (not applied)

Bio: Software developer with a computer systems engineering background. Building web and mobile apps, exploring embedded systems and practical AI. Auckland, NZ.

Pin order: Remote Experiment Control Lab → Fieldroom → EduFeed. Three strong projects are sufficient.

| Repository | Proposed description |
| --- | --- |
| Remote-Expriment-Control-Lab | Configure simulated experiments, monitor live measurements and replay saved results. React, FastAPI, C++ and PostgreSQL. |
| Live-Event-Operations | Fieldroom: equipment bookings, pickup, returns and maintenance for a fictional club, with database-enforced booking conflicts. |
| edufeed | A Chrome extension that replaces YouTube recommendations with subscriptions or selected educational content. |

## Evidence and remaining issues

The lab is a simulator; hosted access requires an operator account. Fieldroom is a portfolio application for a fictional club. Their source, architecture, tests and successful CI were reviewed for the first revision and links rechecked here.

EduFeed has a verified Chrome Web Store listing, so the profile includes an install link. Its public README still describes a store build as planned. The repository's docs/demo.gif and manifest icon16/icon48/icon128 assets are absent. The extension's store package has not been matched to the public source revision. These application-repository issues remain outside this task.

The EduFeed showcase uses the user's original LinkedIn image, Edufeed pic 1. It shows the extension in context; the other visible image was the options page.

The broader technology list reflects user-confirmed experience and existing profile/project history. It does not imply equal proficiency or that every technology appears in these three repositories. AI API integration and development assistants are separated.

## Exact files changed in this revision

- README.md
- assets/PROVENANCE.txt
- assets/edufeed-focus.jpg
- assets/icons/amazonwebservices.svg
- assets/icons/androidstudio.svg
- assets/icons/angular.svg
- assets/icons/c.svg
- assets/icons/css3.svg
- assets/icons/dart.svg
- assets/icons/figma.svg
- assets/icons/firebase.svg
- assets/icons/flutter.svg
- assets/icons/git.svg
- assets/icons/githubactions.svg
- assets/icons/googlecloud.svg
- assets/icons/html5.svg
- assets/icons/java.svg
- assets/icons/jira.svg
- assets/icons/linux.svg
- assets/icons/php.svg
- assets/icons/playwright.svg
- assets/icons/raspberrypi.svg
- assets/icons/supabase.svg
- assets/icons/vscode.svg
- assets/icons/vuejs.svg
- assets/more-to-come.svg
- assets/pillars/LICENSE
- assets/pillars/ai.svg
- assets/pillars/software.svg
- assets/pillars/systems.svg
- assets/signal.svg (removed)
- docs/preview-before.png
- docs/preview-desktop.png
- docs/preview-mobile.png
- docs/profile-review.md

## Reversal

Revert this revision's single commit to restore the preceding profile design. The earlier redesign commit remains in history as well.
