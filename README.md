# remark-bug

> @nuxt/content remark bug demonstration

## Bug reproduction

Run `yarn install` followed by `yarn generate`. There will be warning messages:
```
 WARN  remark-twemoji is not installed

 WARN  remark-frontmatter,yaml is not installed
```
The packages will work despite those messages, however.

**Update:** `remark-twemoji` issue is solved by [installing `twemoji`](https://github.com/madiodio/remark-twemoji/issues/8#issuecomment-636511097)
