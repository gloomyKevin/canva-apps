# Apps for Canva — listing pages

Public pages required by the Canva Apps Marketplace, for every app I publish.

    /                     developer site  → 「公司或你的网站 URL」
    /<app>/               app overview
    /<app>/terms.html     → 「条款和条件URL」
    /<app>/privacy.html   → 「隐私政策URL」
    /<app>/support.html   → 「支持团队URL」

One folder per app, so a second app needs no new repository and no new URLs
for the developer-level fields.

Plain static HTML, no build step, no dependencies — legal pages should not
depend on a CDN staying up. `.nojekyll` keeps GitHub Pages from filtering files.
