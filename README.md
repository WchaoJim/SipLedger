# SipLedger — Privacy & Support

Static English and Simplified Chinese pages for 饮有数 / SipLedger.

## Pages

| Page | English | 简体中文 |
| --- | --- | --- |
| Home | `index.html` | `zh/index.html` |
| Privacy policy | `privacy/index.html` | `zh/privacy/index.html` |
| Support & data safety | `support/index.html` | `zh/support/index.html` |
| Terms of use | `terms/index.html` | `zh/terms/index.html` |

HTML and CSS only. No build step, external fonts, analytics scripts, forms, or runtime dependencies. Links work both at a domain root and under a GitHub Pages project path. The language switch links to the corresponding page.

## Local preview

From this directory:

```sh
python3 -m http.server 8874 --bind 127.0.0.1
```

Open `http://127.0.0.1:8874/` or `http://127.0.0.1:8874/zh/`.

## GitHub Pages

The prepared files have not yet been deployed. Before deployment, finalize the privacy operator identity, support handling commitments, and policy review. Do not treat proposed URLs as live URLs.

Publish this website repository alone. In its GitHub Settings → Pages, choose **Deploy from a branch**, select the branch containing these files and **/(root)**, then save. The repository includes `.nojekyll` and uses only static files. Confirm HTTPS and all page URLs after the build completes.

Suggested repository: `WchaoJim/sipledger-site`.

Proposed App Store URL mapping once deployment is verified:

| Field | English | 简体中文 |
| --- | --- | --- |
| Privacy Policy URL | `https://wchaojim.github.io/sipledger-site/privacy/` | `https://wchaojim.github.io/sipledger-site/zh/privacy/` |
| Support URL | `https://wchaojim.github.io/sipledger-site/support/` | `https://wchaojim.github.io/sipledger-site/zh/support/` |

## Maintenance

Update both languages when data practices, support details, or product behavior change, and revise each page’s update date. Check current sync scope, backups, image handling, deletion, and purchase behavior against the actual app. Website copy does not establish that a planned feature has been implemented or tested.

Keep exported journals, app source code, device screenshots, account settings, and internal audit material out of this website repository.

The SipLedger brand and icon remain reserved; public hosting does not grant an open-source license to these materials.
