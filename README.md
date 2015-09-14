# mediawiki-fetcher
Fetches single pages or entire categories from a MediaWiki.

Downloads:
- pages as markdown files
- all included elements (images, PDFs, ...)

Requirements:
- pip install mwclient
- wget installation

Usage:
- Download single page (+ images, etc.): `python wiki-fetcher.py --host wiki.domain.org --user username --pass password ApiPlaygorund` 
- Download entire category (all pages + images, etc.): `python wiki-fetcher.py --host wiki.domain.org --user username --pass password -c categoryname` 


