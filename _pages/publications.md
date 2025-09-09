---
permalink: /publications/
title: "Publications"
layout: single
---

This site supports individual publication pages (in the `_publications` collection) and list views.  
You can add new items by creating Markdown files in the `_publications/` folder or by using the template's TSV/BibTeX generators.

**Quick start:** create a file like `_publications/2025-01-01-example.md` with this front matter and content:

```
---
title: "Paper title"
collection: publications
permalink: /publication/paper-title
date: 2025-01-01
venue: "Journal / Conference"
paperurl: "https://doi.org/10.xxxx/xxxxx"
citation: "Your Name, *et al.*, 2025."
---

**Abstract.** A short abstract.
```

For batch import from TSV/BibTeX, see the repository `markdown_generator` tools.