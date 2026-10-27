# Profile revision review

This revision puts all 22 user-selected core technologies above the projects, with recognisable icons and explicit labels that stay together when the layout wraps. A direct link leads to the full toolkit. The detailed technology categories are visible headings, with no disclosure controls hiding experience. The optional project engineering notes remain collapsible. Existing project cards, introduction and personal quote are preserved.

## Rendered previews

[Before this revision](preview-before.png) · [After: desktop light](preview-desktop.png) · [After: mobile dark](preview-mobile.png)

These are actual local renders of GitHub's Markdown API output with github-markdown-css. They reproduce the README content area, not GitHub's surrounding profile layout. On phones the requested two-column cards remain side by side; the pillar panels wrap.

## Verification

- [x] GitHub Markdown API accepted the README, tables, details and image attributes.
- [x] Rendered at 1040px, 390px and 320px in light and dark themes.
- [x] No page or card-table horizontal overflow at any tested width. All core-toolkit labels remain attached to their icons.
- [x] All local images loaded; every image has alt text or is explicitly decorative.
- [x] All six detailed technology categories are visible without opening dropdowns. The project engineering disclosure is retained.
- [x] All 19 unique GitHub/Chrome Store destinations returned HTTP 200.
- [x] LinkedIn profile and EduFeed media verified in the user's local browser; automated requests return LinkedIn's 999 response.
- [x] Genuine project images; no generated product screenshots or exposed credentials.
- [x] No application repository, account setting, pin or repository description modified.

## Suggested profile metadata (not applied)

Bio: Software developer with a computer systems engineering background. Building web and mobile apps, embedded systems and AI-assisted development. Auckland, NZ.

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

The broader technology list reflects user-confirmed experience and existing profile/project history. It does not imply equal proficiency or that every technology appears in these three repositories. AI tools are presented as development aids, without claims of model training or AI product delivery.

## Exact files changed in this revision

- README.md
- assets/PROVENANCE.txt
- assets/toolkit/aws.svg
- assets/toolkit/c.svg
- assets/toolkit/claude-code.svg
- assets/toolkit/codex.svg
- assets/toolkit/cplusplus.svg
- assets/toolkit/css.svg
- assets/toolkit/dart.svg
- assets/toolkit/docker.svg
- assets/toolkit/firebase.svg
- assets/toolkit/flutter.svg
- assets/toolkit/git.svg
- assets/toolkit/google-cloud.svg
- assets/toolkit/html.svg
- assets/toolkit/java.svg
- assets/toolkit/javascript.svg
- assets/toolkit/linux.svg
- assets/toolkit/postgresql.svg
- assets/toolkit/python.svg
- assets/toolkit/raspberry-pi.svg
- assets/toolkit/react-native.svg
- assets/toolkit/react.svg
- assets/toolkit/typescript.svg
- docs/preview-before.png
- docs/preview-desktop.png
- docs/preview-mobile.png
- docs/profile-review.md

## Reversal

Revert this revision's single commit to restore the preceding profile design. The earlier redesign commit remains in history as well.
