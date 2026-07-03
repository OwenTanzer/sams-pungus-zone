# sams-pungus-zone

## Web app policy

Any web page/app built in this repo must include cache busting by default —
don't wait for a "stuck on old version" report to add it. For a static
single-file page (like `index.html`), that means the no-cache meta tags plus
the one-time query-string redirect pattern used in `index.html`. For anything
with separate build assets, prefer content-hashed filenames for JS/CSS instead.
