# Journal

A minimal, typography-heavy newsletter theme for [Ghost](https://github.com/TryGhost/Ghost).

# Development

Edition styles are compiled using Gulp/PostCSS to polyfill future CSS spec. You'll need [Node](https://nodejs.org/), [pnpm](https://pnpm.io/) and [Gulp](https://gulpjs.com) installed globally. After that, from the theme's root directory:

```bash
# Install
pnpm i

# Run build & watch for changes
pnpm run dev

# Launch a development Ghost instance (user must be in docker group and docker installed)
pnpm run ghost
```

Now you can edit `/assets/css/` files, which will be compiled to `/assets/built/` automatically.

The `zip` Gulp task packages the theme files into `dist/journal.zip`, which you can then upload to your site.

```bash
pnpm run zip
```

# Contribution

This repo is synced automatically with [TryGhost/Themes](https://github.com/TryGhost/Themes) monorepo. If you're looking to contribute or raise an issue, head over to the main repository [TryGhost/Themes](https://github.com/TryGhost/Themes) where our official themes are developed.

## Credits

Originally released by the Ghost Foundation under the [MIT license](LICENSE).
