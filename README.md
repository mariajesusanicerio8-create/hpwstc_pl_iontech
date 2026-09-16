# IONTECH Product Catalog — GitHub Pages Ready

## IMPORTANT
Upload the CONTENTS of this folder to the ROOT of your GitHub repository.
Do NOT upload the `IONTECH_GITHUB_READY` folder itself and do NOT create another nested `iontech-product-catalog` folder.

Your repository should look like:

```
index.html
admin.html
404.html
robots.txt
assets/
  app.js
  admin.js
  styles.css
data/
  products.js
  catalog-summary.json
```

Then enable GitHub Pages from Settings → Pages → Deploy from branch → main → /(root).

The public site is designed for the repository path `HPWSTCPL_Iontech`, but the relative asset paths also work for other GitHub Pages project names.

The Admin page can edit homepage text, product fields, specifications, components, prices, quantities, images, branding and SEO. Components are shown publicly in one table.

NOTE: This static version stores admin changes in the browser's local storage. A real shared admin/database requires a backend such as Supabase.
