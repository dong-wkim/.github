# dong-wkim · Assets

Static assets — logos, icons, and images — hosted here and served via raw GitHub URLs or [GitHub Pages](https://dong-wkim.github.io/.github/).

## Directory structure

```
assets/
  logos/    ← wordmarks and full logo lockups
  icons/    ← app icons and favicons
  images/   ← screenshots, banners, and other images
```

## Usage

Reference any asset directly in Markdown:

```md
![Logo](https://raw.githubusercontent.com/dong-wkim/.github/main/assets/logos/logo.svg)
```

Or in HTML:

```html
<img src="https://raw.githubusercontent.com/dong-wkim/.github/main/assets/logos/logo.svg" alt="Logo" />
```

## Asset catalog

| File | Description | Raw URL |
|------|-------------|---------|
| `assets/logos/logo.svg` | Primary logo (dark) | [link](https://raw.githubusercontent.com/dong-wkim/.github/main/assets/logos/logo.svg) |
| `assets/logos/logo-light.svg` | Logo variant (light) | [link](https://raw.githubusercontent.com/dong-wkim/.github/main/assets/logos/logo-light.svg) |
| `assets/icons/icon.svg` | App icon 64×64 | [link](https://raw.githubusercontent.com/dong-wkim/.github/main/assets/icons/icon.svg) |
| `assets/icons/favicon.svg` | Favicon 32×32 | [link](https://raw.githubusercontent.com/dong-wkim/.github/main/assets/icons/favicon.svg) |

## Adding assets

1. Drop the file into the appropriate sub-directory under `assets/`.
2. Add a row to the table above.
3. Optionally enable **GitHub Pages** (Settings → Pages → Source: `main` branch, `/ (root)`) to serve the visual catalog at the URL shown in the Pages settings after enabling it.
