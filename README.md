# The Nush Project — thenushproject.org

Static site: `index.html` + `styles.css`. No build step.

Preview locally:

    python3 -m http.server 8090

## Going live (GitHub Pages)
1. Push this repo to GitHub, then Settings → Pages → deploy from `main` / root.
2. `CNAME` already says `thenushproject.org`.
3. At your domain registrar, point DNS at GitHub Pages:
   - A records for `@`: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
   - CNAME `www` → `<your-github-username>.github.io`
4. Tick "Enforce HTTPS" once the certificate is issued.
