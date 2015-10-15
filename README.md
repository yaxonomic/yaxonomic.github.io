# Yaxonomic Capstone Team Website

## Local build:

Just run
```bash
jekyll serve -w
```

## Upload to CEFNS:

```bash
jekyll build
scp -r _site/* sftp.cefns.nau.edu:/www/sites/cefns/Research/D4P/EGR486/<DISCIPLINE>/<YEAR>-Projects/<GROUP-NAME>
```
Alternatively, follow the [instructions here](http://nau.edu/CEFNS/IT/Support/Capstone-Website-Help/) to upload the freshly created contents in `_site/`
