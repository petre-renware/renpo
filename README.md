# RENware Software Systems portal

## Project data

* code-name: `renpo`
* p/n: `0000-0112` (T2 class)
* published URL: [www.renware.eu](http;//www.renware.eu)




## Directories

* `docs/` - keep released portal files. Available on `publishing` branch.

* `static_portal/` - keep current portal generation, development tests. Files are not guaranteed on `git` but only local clone.

* `doc_src/` - keep all source document, pages, pictures, etc. Guaranteed on all working branches except `publishing` whixh is dedicated to GitHub releasing portal site

All other directories are used in current working process.



## Branches

All classic branches, `master`, `development` and `xxx-dev` are used according to SDEVEN methodology.

Branch `publishing` is dedicated to GitHub publishing site action from directory `docs/`. This branch is not guaranteed fir history or origin (could be orphan) but *only for last commited content*. Its history is not relevant as content, maybe just as a historical activity.



## Technical info

* Site is of "static" type, generated using [`mkdocs` tool](http://www.mkdocs.org).

* Site is published under `www.renware.eu` URL using a DNS CNAME record, made available for GitHub too.