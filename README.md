# ByeBike Cancer website

Static site converted from the Tilda export of byebikecancer.com. No build step: the repository root is the site.

## Pages

| URL | File |
| --- | --- |
| `/` | `index.html` |
| `/sponsors/` | `sponsors/index.html` |
| `/mission/` | `mission/index.html` |
| `/ride2025/` | `ride2025/index.html` |
| `/sponsors-monty/` | `sponsors-monty/index.html` |
| `/contact/` | `contact/index.html` |
| `/sponsorsprofiles/` | `sponsorsprofiles/index.html` |
| `/donations/` | `donations/index.html` |
| `/arrival/` | `arrival/index.html` |

Shared assets live in `images/`, `css/` and `js/`. All links and asset paths are relative, so the site works at a domain root and under a `username.github.io/repo/` subpath.

## Deploy on GitHub Pages

1. Push the contents of this folder to the repository root.
2. In the repository: Settings > Pages > Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
3. For the custom domain, enter `byebikecancer.com` under Settings > Pages > Custom domain (this creates a `CNAME` file) and point the DNS records to GitHub Pages.

`.nojekyll` is included so GitHub serves the files as they are.

## Still depends on Tilda

- Forms submit to Tilda's form service using the project's form key. They keep working only while the Tilda project stays active.
- Fonts and a fallback script load from `tildacdn.com`.
- `js/tilda-stat-1.0.min.js` reports page views to Tilda statistics.

Google Tag Manager (`GTM-M7MP94B8`) is unchanged.
