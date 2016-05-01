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

{% highlight  %}
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
### What's up
- what's up here.
### Jekyll docs
> [http://jekyllcn.com/docs][1]

### Highlight
 jekyll's highlight uses the special code block.you should put your highlight-wanted part into a code block . you can even specify what you're highlighting,and show the line number by an option of `linenos`.

{% highlight  %}
> {% highlight %}
> //contents you want to highlight
> {% endhighlight %}
{% endhighlight %}

[1]:	http://jekyllcn.com/docs