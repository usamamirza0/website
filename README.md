# usamamirza.com

Personal academic website of Usama Mirza, Ph.D. student in Electrical and Electronics Engineering at Bilkent University.

Built with [Hugo](https://gohugo.io/) and the [Wowchemy Academic](https://github.com/wowchemy/starter-hugo-academic) theme, and deployed on Netlify.

## Structure

- `content/authors/admin/_index.md`: profile, bio, education and social links
- `content/_index.md`: homepage sections (publications, experience, awards)
- `content/publication/`: one folder per publication (`index.md` + `cite.bib`)
- `static/uploads/resume.pdf`: CV linked from the site
- `config/_default/`: site configuration and navigation menu

Publications are grouped on the homepage by publication type (`2` = journal) and by tag (`Conference Paper` or `Abstract`).

## Local preview

Requires Hugo (extended) and Go.

```bash
hugo server
```
