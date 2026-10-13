# Projects

Client websites by [Elevven11 Studio](https://elevven11studio.github.io/), built as plain HTML and CSS with no build step.

| Site | Folder | Live |
| --- | --- | --- |
| Legacy Gadgets | `legacy-gadgets/` | https://elevven11studio.github.io/projects/legacy-gadgets/ |
| O.D.O Stitches | `odo-stitches/` | https://elevven11studio.github.io/projects/odo-stitches/ |

`index.html` at the root links to each site.

## Run locally

```bash
npx serve . -l 5566
```

Then open http://localhost:5566.

## Add a project

1. Create a folder with an `index.html`.
2. Use relative paths for assets, since the site is served under `/projects/`.
3. Link it from the root `index.html`.
4. Push to `main`. GitHub Pages redeploys automatically.
