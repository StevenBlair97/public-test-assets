# Public Test Assets

This folder is intended for GitHub Pages. It hosts public CSS/assets for a local analytics/session-replay test.

## Public URL

```txt
https://stevenblair97.github.io/public-test-assets/
```

## CSS URL

```txt
https://stevenblair97.github.io/public-test-assets/styles/site.css
```

## How it is used

The local React site loads this public stylesheet from `index.html`. This lets the local site keep running on your machine while Microsoft Clarity has a public stylesheet URL it can fetch for heatmap/session replay rendering.

## Files

```txt
public-test-assets/
  index.html
  .nojekyll
  styles/
    site.css
  assets/
    images/
      README.md
      .gitkeep
  snippets/
    local-site-head.html
    example-public-paths.txt
```

## Upload order

1. Upload this folder to the `public-test-assets` GitHub repository.
2. Confirm that `styles/site.css` is available at the public CSS URL above.
3. Run the local React site.
4. Browse the local site and check Clarity recordings/heatmaps.

## Images

The image folder is currently a placeholder. If you later want Clarity replays to show the images more accurately, upload the real images here and update the local React image paths to point at this public URL.
