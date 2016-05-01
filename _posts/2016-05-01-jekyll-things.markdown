---
layout:     post
title:      "jekyll blog things "
subtitle:   "pitfalls of jekyll blog."
date:       2016-05-01 12:00:00
author:     "carbin-gun"
header-img: "img/post-bg-01.jpg"
---

### Syntax
A blog hosted by jekyll has its unique syntax strcture.If the syntax can't be parsed well,the parser will quit the parsing the article display.
commonly used syntax for article abstract for example
	---
	layout:     post
	title:      "jekyll blog things "
	subtitle:   "pitfalls of jekyll blog."
	date:       2016-05-01 12:00:00
	author:     "carbin-gun"
	header-img: "img/post-bg-01.jpg"
	---
### naming
- the name of the article should follow the pattern of `yyyy-mm-dd-{article-name-delimeter-by-middle-line}`
-  jekyll blog system is to sequence all the articles in the filename date value mentioned above.if the date is the newest ,that article will be put at the top.