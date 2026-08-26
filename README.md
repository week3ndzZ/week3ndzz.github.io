# Wenkang Jiang — Academic Homepage

A lightweight, responsive, multi-page academic homepage built with plain HTML
and CSS for GitHub Pages. The layout follows the classic Jemdoc academic style
and the page structure of [Erdun Gao's homepage](https://erdungao.github.io/).

## Preview locally

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Publish with GitHub Pages

1. Open the repository on GitHub and go to **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select `main` and `/ (root)`, then save.

The project-site URL will be:

<https://week3ndzz.github.io/wenkang.github.io/>

> The address `wenkang.github.io` is only available to the GitHub account or organisation named `wenkang`. With the current account, a root user site would require a repository named `week3ndzZ.github.io`; a separately owned custom domain is another option.

## Update profile details

- Homepage and biography: `index.html`
- Publication entries: `Publications.html`
- Academic background: `Experience.html`
- Academic service: `Service.html`
- Base typography and page styling: `jemdoc.css`
- Responsive layout and page components: `site.css`
- Profile artwork: `pic/wenkang-profile.svg`
- Browser icon: `favicon.svg`

The current profile artwork is an original WJ monogram. Replace it with a
personal photograph and update the image path in `index.html` when a suitable
portrait is available. No third-party portrait or image asset is included.
