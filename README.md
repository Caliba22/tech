# Calissa's Technical Project Portfolio

**Intended live address:** https://tech.calissa.org

This is a responsive static portfolio website highlighting IAM/SailPoint learning, a smart sliding glass door concept, and a private Solana token learning project. It uses plain HTML, CSS, and JavaScript and needs no build step.

## Publishing on GitHub Pages

1. While signed in to GitHub **Caliba22**, open https://github.com/new.
2. Use the existing **public** repository `Caliba22/tech`.
3. Unzip this package. The `index.html`, `CNAME`, and `README.md` files are placed at the repository root on `main`.
4. Open **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**, branch `main`, folder `/(root)`, then Save.
5. In **Settings → Pages → Custom domain**, enter `tech.calissa.org` and Save. GitHub may create or update its `CNAME` file. Verify it still reads `tech.calissa.org`.
6. In GoDaddy DNS for **calissa.org**, add the following record (provided there is no conflicting record for `tech`):

   | Type | Name | Value |
   | --- | --- | --- |
   | CNAME | `tech` | `Caliba22.github.io` |

   Do not alter the DNS records for `@`, `www`, or any records supporting Adobe Portfolio. Do not put `https://` in the CNAME target.
7. Once DNS is verified and the option becomes available, enable **Enforce HTTPS** in the Pages settings.

Your normal photography site stays at `calissa.org`; only the new `tech` subdomain points to GitHub Pages. DNS can take time to propagate.

## Scope and privacy

- This is a public static site; **never commit** seed phrases, private keys, tokens, passwords, or other secret credentials.
- SailPoint/VetCare is labeled as a learning/proof-of-concept effort, not verified production experience.
- The sliding door is labeled as a design concept rather than a tested installation.
- Links: https://github.com/calisiba/SailPoint-IAM-Postman-Demo (empty at last check), https://github.com/Caliba22/Crypto , and https://github.com/Caliba22/token-list .

GitHub docs: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site