# ASB Construction Inc. — "coming soon" placeholder

A single page to put online while the main site (`../construction-site`) is being finished.

```
index.html               The page (all styling is inside it)
images/logo-stacked.jpg  Logo
```

## Before uploading

In `index.html`, replace the sample details (each appears more than once):
- `(555) 555-0123` and `+15555550123` → your phone
- `info@example.com` → your email
- `123 Builder Way, Your City, ST 00000` → your address (or delete that line)

## Upload to GoDaddy (Economy / cPanel)

1. GoDaddy → My Products → Web Hosting → **Manage** → **cPanel Admin** → **File Manager** → `public_html`.
2. Upload `index.html` and the `images` folder (or zip both, upload, then right-click → **Extract**).
3. Visit your domain to check it.

## When the main site is ready

1. In `public_html`, delete `index.html` and `images/` from this placeholder
   (or move them into a folder such as `old-placeholder/` if you want a backup).
2. Upload the contents of `construction-site/` as described in its README.
