# Deployment and migration cutover

## Already completed

- [x] Public repository `bakodramane/ai-official-statistics` created.
- [x] All 171 source files transferred and verified against their original Git blob SHAs.
- [x] Original 125 bilingual post-source files preserved.
- [x] Migration PR #1 merged into `main`.
- [x] Jekyll build, project-site URL checks and bilingual archive/RSS tests passed on `main`.
- [x] Weekly ChatGPT bilingual publication task retargeted to this repository; schedule unchanged.
- [x] Original portfolio migration prepared in draft [PR #34](https://github.com/bakodramane/bakodramane.github.io/pull/34).

## Still needed

1. **Enable Pages:** Go to [repository Pages settings](https://github.com/bakodramane/ai-official-statistics/settings/pages). Under Build and deployment select **Deploy from a branch**, choose `main` / `/(root)`, then **Save**.
2. Confirm the published [English homepage](https://bakodramane.github.io/ai-official-statistics/), [French homepage](https://bakodramane.github.io/ai-official-statistics/fr/accueil/), [archive](https://bakodramane.github.io/ai-official-statistics/archive/), [English articles](https://bakodramane.github.io/ai-official-statistics/en/), [French articles](https://bakodramane.github.io/ai-official-statistics/fr/) and [RSS feed](https://bakodramane.github.io/ai-official-statistics/feed.xml).
3. Open representative dated English and French posts. Verify paired language switches, styles and links.
4. Review and merge [portfolio PR #34](https://github.com/bakodramane/bakodramane.github.io/pull/34) (supersedes #33) **only after** step 2 is successful. The portfolio PR keeps the professional site intact, links to this new blog, and creates forwarding pages for old article URLs.
5. Recheck old-to-new redirects and the legacy RSS migration notice after PR #34 merges.

## Important limitations

- GitHub Pages does not provide server-side 301s for these old post URLs. The portfolio PR uses HTML meta refresh/JavaScript forwarding and canonical metadata.
- Subscribers to the old Atom feed need to subscribe to the new blog feed; the old feed becomes a one-entry migration notice.
- The professional site has not been cut over until PR #34 merges.
- Avoid changing `baseurl` unless a new custom domain is actually configured.
