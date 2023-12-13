+++
title = "Homepage"
description = "Homepage"
date = "1980-06-13"
+++

Homepage nl

{{ range ( where .Site.RegularPages "Type" "posts" | first 3 ) }}
  <li><a href="{{ .Permalink }}">{{ .Title }}</a></li>
{{end}}