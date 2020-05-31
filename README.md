# remark-bug

> @nuxt/content remark bug demonstration

## Bug reproduction

Run `yarn install` followed by `yarn generate`. There will be warning messages:
```
 WARN  remark-twemoji is not installed

 WARN  remark-frontmatter,yaml is not installed
```
The packages will work despite those messages, however.
