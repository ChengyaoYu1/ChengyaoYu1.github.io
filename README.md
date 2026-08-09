# Chengyao Yu — Academic Homepage

Source code for [Chengyao Yu's academic homepage](https://ChengyaoYu1.github.io), featuring research interests, publications, talks, and teaching experience.

## Content

- Homepage: `_pages/about.md`
- Publications: `_publications/`
- Talks: `_talks/`
- Teaching: `_teaching/`
- Site settings: `_config.yml`
- Navigation: `_data/navigation.yml`

## Local development

Install Ruby, Bundler, and Node.js, then run:

```bash
bundle install
npm install
npm run build:js
bundle exec jekyll serve -l -H localhost
```

The site will be available at <http://localhost:4000>.

## Credits

Built with [Jekyll](https://jekyllrb.com/) and based on the [Academic Pages](https://github.com/academicpages/academicpages.github.io) template.
