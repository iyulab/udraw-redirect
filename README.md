# udraw-redirect

Serves `udraw.iyulab.com` and sends every path to the same path on `https://draw.u-platform.kr` (the U-Draw intro site moved there on 2026-10-04). Known pages redirect instantly with `meta refresh` + `canonical`; any other path is redirected by `404.html`. GitHub Pages serves this branch as-is (`.nojekyll`); the custom domain is in `CNAME`.
