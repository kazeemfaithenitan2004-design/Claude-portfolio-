# Portfolio: setup (about 15 minutes)
1. Create a GitHub repo and upload this whole folder (netlify.toml at the root, `site/` inside).
2. Netlify: Add new site > Import from Git > pick the repo. Build command empty, publish dir `site` (already in netlify.toml).
3. Edit `site/admin/config.yml`: set `repo:` to `your-username/your-repo` and `site_url:` to your Netlify URL.
4. Sign in at `https://YOUR-SITE.netlify.app/admin/` with "Sign in with GitHub token":
   GitHub > Settings > Developer settings > Fine-grained tokens > select only this repo > Contents: Read and write, Pull requests: Read and write. Paste the token (never put it in any file).
   Optional later: Netlify > Site configuration > Access & security > OAuth > GitHub, for normal GitHub login.
5. Edit in /admin, press Publish. Netlify rebuilds in about a minute.
Netlify Identity / Git Gateway is not used (deprecated).
Not verified live: I could not test the GitHub login or editorial workflow from here. If drafts misbehave, delete the `publish_mode` line.

## To check before going live
- Followers: screenshots show 4.6K and 8.3K, not 4,600 to 8,500.
- "2.8M impressions": the only 2.8 screenshot (Aug) reads 2.8K views. The 1M figure is a 28-day window.
- "130K+ best post": best post screenshot shows 250,805 views (130K is a daily peak on a chart).
- "10-20 posts/day": Meta showed 11.1/day (Sep-Oct) and 4.3/day (Aug). Not published.
- Periods on metric cards are my reading of screenshot axes; confirm them.
- Not used: the unredacted profile screenshot (shows the brand name), the Creator Dashboard (brand watermark), the 160K and Aug 2.8K views screenshots.
- Add: CV, social URLs, project duration, strategies (left empty).
