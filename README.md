# Prachi Lipsa Mohanty — Portfolio

## Files
```
portfolio/
├── index.html                          ← the whole site (HTML + CSS + JS in one file)
└── assets/
    └── certificates/
        ├── web-a-thon-certificate.jpg
        ├── cybersecurity-infosys-certificate.png
        ├── cpp-saylor-certificate.png       ← image version, shown in the "View Certificate" modal
        ├── cpp-saylor-certificate.pdf       ← original PDF, kept for reference
        ├── python-saylor-certificate.png    ← image version, shown in the "View Certificate" modal
        └── python-saylor-certificate.pdf    ← original PDF, kept for reference
```

All four certificates from your CV (Web-A-Thon, Cyber Security, C++, Python) now have
working "View Certificate" buttons.

## Editing your info later
Everything is plain text inside `index.html` — search for the section by its `id`
(e.g. `id="projects"`, `id="education"`) and edit the text directly. No build step,
no dependencies.

## Deploying with GitHub Pages
1. Create a new GitHub repo, e.g. `prachi-lipsa29.github.io` (using this exact name
   gives you the shortest URL) or any other name like `portfolio`.
2. Upload the contents of this `portfolio/` folder to the repo root (`index.html` and
   the `assets/` folder side by side — not nested inside another folder).
3. In the repo, go to **Settings → Pages**, set **Source** to the `main` branch and
   `/ (root)`, then save.
4. GitHub will publish your site at:
   - `https://prachi-lipsa29.github.io` (if the repo is named exactly that), or
   - `https://prachi-lipsa29.github.io/portfolio` (if the repo is named `portfolio`
     or anything else).
5. It can take a minute or two to go live after the first deploy.

## Custom domain (optional)
If you buy a domain later (e.g. from Namecheap or Google Domains), add a `CNAME` file
with your domain name to the repo root and point your domain's DNS to GitHub Pages —
GitHub's docs walk through the exact records under **Settings → Pages → Custom domain**.
