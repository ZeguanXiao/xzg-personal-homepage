# Zeguan Xiao's Homepage

Academic homepage for [Zeguan Xiao (肖泽管)](https://ZeguanXiao.github.io/xzg-personal-homepage/), based on [AcadHomepage](https://github.com/RayeRen/acad-homepage.github.io).

This site is a single-page personal homepage (about, news, publications, honors, education). There is no blog.

## Local preview

```bash
export PATH="/opt/homebrew/opt/ruby@3.3/bin:$PATH"
bundle install
bundle exec jekyll serve
```

Then open http://127.0.0.1:4000/xzg-personal-homepage/.

## Deploy

The site is published from `ZeguanXiao/xzg-personal-homepage` to GitHub Pages at https://ZeguanXiao.github.io/xzg-personal-homepage/.

To enable automatic Google Scholar citation badges, add a repository secret named `GOOGLE_SCHOLAR_ID` with value `rgQWhpUAAAAJ`, then enable GitHub Actions.
