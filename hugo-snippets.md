# Hugo Snippets & Tricks

A running list of useful Hugo/Go templates, shortcodes, and configurations I've picked up.

---

## Front Matter Examples
```toml
title = "Improve the News"
date = "2025-06-20"
desription = "Full-stack consulting on a real-time curation platform"
```

## List all case studies
```go
{{ range where .Site.RegularPages "Section" "case-studies" }}
    <li><a href="{{ .RelPermalink }}">{{ .Title }}</a></li>
{{ end }}
```




