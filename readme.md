# Twitch4J Page

Page content builded via [Hugo](https://gohugo.io) and custom-maded layout.
With Bootstrap assets (delivered from [`package.json`](package.json)).

## Contest

- [Documentation](content/docs) - with breadcrumb navigation and sidebar lvl 2 menu
- [Javadoc](static/javadoc) (generated from JDK9+ - Recommended JDK11 which are current LTS)
- [Search](assets/js/script.js) (using [lunr.js](https://lunrjs.com/)

## Configuration

Using [`config.yml`](config.yml) we define a custom menu content... and the other stuff.

## Write your documentation

Ckecout [how to](how_to.md) utilize this custom template.

## Additional Notes

To before starting editing documentation you needs

- [`hugo`](https://gohugo.io) - to generate this page
- [`node`](https://nodejs.org) - to install and deliver those [packages](package.json)

```txt
IMPORTANT: This readme is not a part of the content generated by hugo.
```

## Live View

To editing this project type in project console `npm run server`

## Generate files

To generate ready to deploy project just type in project console `npm run generate` or `npm run generate:minify`. All content are be generated in: `public` folder.

## GitHub Actions

Project will automatically generate files and push them into `gh-pages` branch.
To define own configuration pleas go to [`.github/workflows/gh-pages.yml`](.github/workflows/gh-pages.yml) and follow those useful documentation:

- [Github Actions Documentation](https://docs.github.com/en/actions)
- [GitHub Actions for GitHub Pages](https://github.com/peaceiris/actions-gh-pages)
- [GitHub Actions for Hugo](https://github.com/peaceiris/actions-hugo)

## License

This project is under [MIT License](LICENSE)
