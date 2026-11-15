# Leonardo Benicio — Social Links

**Current version:** `2.0.10`

A minimal Hugo site for Leonardo Benicio’s social and contact links, built with the [AboutMe v2 theme](https://github.com/lbenicio/theme). GitHub Actions deploys this static site to Cloudflare Workers. Configure the repository secrets `CLOUDFLARE_API_TOKEN` and `CLOUDFLARE_ACCOUNT_ID`; the Worker serves the site on its custom domain.

Run a local preview with `hugo server`.


Before the first deployment, configure the two Cloudflare secrets above. If the hostname still has a DNS CNAME pointing to AWS, remove that conflicting record before Wrangler creates the Worker custom domain.
