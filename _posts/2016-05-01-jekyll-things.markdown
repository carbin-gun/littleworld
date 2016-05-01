---
layout:     post
title:      "jekyll blog things "
subtitle:   "pitfalls of jekyll blog."
date:       2016-05-01 12:00:00
author:     "carbin-gun"
header-img: "img/post-bg-01.jpg"
---

### Syntax
A blog hosted by jekyll has its unique syntax structure especially for the header.If the syntax can't be parsed well,the parser will quit the parsing and the article display.

commonly used syntax for article abstract for example:

{% highlight javascript %}
---
layout:     post
title:      "jekyll blog things "
subtitle:   "pitfalls of jekyll blog."
date:       2016-05-01 12:00:00
author:     "carbin-gun"
header-img: "img/post-bg-01.jpg"
---
{% endhighlight %}


### Naming
- the name of the article should follow the pattern of `yyyy-mm-dd-{article-name-delimeter-by-middle-line}`.
-  jekyll blog system is to sequence all the articles in the filename date value mentioned above.if the date is the newest ,that article will be put at the top.
- what's wrong here.

### Docs
> [https://jekyllrb.com/docs/][1]

### Highlight
the jekyll highlight should use the `Liquid tag` called `highlight`to do that work.

### Preview
As for sometimes parse fault ,Putting all the things on live preview at local place is a good idea.Jekyll local preview is a simple task.
{% highlight ruby  %}

1. gem install jekyll
2. gem jekyll-paginate //install components used
3. jekyll serve //it will watch all the changes and compile instantly.
4. if the preview is ok,push all the changes to github. 
{% endhighlight %}

[1]:	https://jekyllrb.com/docs/posts/