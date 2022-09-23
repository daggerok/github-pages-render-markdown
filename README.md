# github-pages-render-markdown
GitHub pages render markdown starter

## [Getting started](https://github.com/daggerok/github-pages-render-markdown#getting-started)

* Create public GitHub repository with default `main` branch
* In project root folder create README.md file with some markdown content in it
* Go to `https://github.com/$username/$repository/settings` project
  [Settings](https://github.com/daggerok/github-pages-render-markdown/settings)
* Go to `https://github.com/$username/$repository/settings/pages`
  [Pages](https://github.com/daggerok/github-pages-render-markdown/settings/pages) tab
* In section `Build and deployment` select:
  * Source: `Deploy from a branch`
  * Branch: `main` and `/` root path
* Add and push commit to trigger GitHub Actions `pages build and deployment`
* Then you can verify on `https://$username.github.io/$repository/` site
  [how markdown was rendered](https://daggerok.github.io/github-pages-render-markdown/)
