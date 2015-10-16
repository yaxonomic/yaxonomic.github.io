# Yaxonomic Capstone Team Website

## Local build:

Just run
```bash
jekyll serve -w
```

## Upload to CEFNS:

```bash
jekyll build
scp -r _site/* <USERNAME>@sftp.cefns.nau.edu:/www/sites/cefns/capstone/projects/CS/2016/Yaxonimic

```
Alternatively, follow the [instructions here](http://nau.edu/CEFNS/IT/Support/Capstone-Website-Help/) to upload the freshly created contents in `_site/`
