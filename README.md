# elegant-social-media

Rendered Instagram media for the elegant.menu weekly social run.

Each Sunday the content run commits that week's carousel slides and Reels under `weeks/<monday-date>/`, imports them into WordPress media from their raw.githubusercontent.com URLs, and stores the WordPress URLs in the `social_queue` table. The n8n publisher posts from the WordPress URLs, not from here.

This repo is public on purpose (WordPress needs a public URL to import from). Don't put anything private here.
