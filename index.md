---
layout: default
title: SCEditor - A lightweight WYSIWYG HTML and BBCode editor
---

## Demo

<!--script type="text/javascript" src="//ajax.googleapis.com/ajax/libs/jquery/1.7.2/jquery.min.js"> </script>
<link rel="stylesheet" href="https://raw.github.com/samclarke/SCEditor/master/minified/jquery.sceditor.min.css" type="text/css" media="all" />
<script type="text/javascript" src="https://raw.github.com/samclarke/SCEditor/master/minified/jquery.sceditor.min.js"> </script>
<script>$(document).ready(function() {
	$("textarea").sceditorBBCodePlugin({
		style: "https://raw.github.com/samclarke/SCEditor/master/minified/jquery.sceditor.default.min.css"
	});
});</script-->

<textarea>This [b]is[/b] [color=#ff0000]a[/color] [size=3]demo[/size] :).</textarea>

## Setup
To use SCEditor, first include jQuery and SCEditor:

{% highlight html %}
<script type="text/javascript" src="//ajax.googleapis.com/ajax/libs/jquery/1.7.2/jquery.min.js"></script>
<link rel="stylesheet" href="minified/jquery.sceditor.min.css" type="text/css" media="all" />
<script type="text/javascript" src="minified/jquery.sceditor.min.js"></script>
{% endhighlight %}

Then simply do:

{% highlight javascript %}
$(document).ready(function() {
	$("textarea").sceditor();
});
{% endhighlight %}

or for the BBCode WYSIWYG editor do:

{% highlight javascript %}
$(document).ready(function() {
	$("textarea").sceditorBBCodePlugin();
});
{% endhighlight %}

For options see the readme or [documentation](http://www.samclarke.com/2012/04/sceditor-documentation/).

## Support or Contact
If you find any bugs or have any questions you can contact me via
[my website](http://www.samclarke.com/contact),
via [GitHub](http://www.samclarke.com/contact)
or by [leaving a comment](http://www.samclarke.com/2011/07/sceditor/).


## Credits
**SCeditor by:**
Sam Clarke (@samclarke)

**Nomicons: The Full Monty Emoticons by:**
Oscar Gruno, aka Nominell v. 2.0 -> oscargruno@mac.com
Andy Fedosjeenko, aka Nightwolf -> bobo@animevanguard.com

**Icons by:**
Mark James (http://www.famfamfam.com/lab/icons/silk/)
Licensed under the [Creative Commons CC-BY license](http://creativecommons.org/licenses/by/3.0/).

