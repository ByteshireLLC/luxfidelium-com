# luxfidelium.com

This repo exists only to send luxfidelium.com to Lux Fidelium's landing page at https://byteshire.com/luxfidelium/.

GitHub Pages serves it from `main` with the custom domain in `CNAME`, and issues the HTTPS certificate. `index.html` handles the home page and `404.html` handles every other path, so any old link lands on the app's page.

The DNS records live at Hover: A records for the bare domain at 185.199.108.153, 185.199.109.153, 185.199.110.153 and 185.199.111.153, and a CNAME for `www` pointing at `byteshirellc.github.io`.

Its twin, `luxfidelium-app`, does the same for luxfidelium.app. The landing page itself is built in `byteshire-web`.
