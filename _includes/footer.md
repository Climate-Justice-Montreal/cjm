<hr style="height:10px;visibility:hidden;margin:0"/>

## {{ site.title }}

{% for each in site.data.navigation.footer-en %}[{{ each.title }}]({{ each.link }}){% unless forloop.last == true %} &ensp;{% endunless %}{% endfor %}

<br>
[![Creative Commons License](/assets/images/cc_logo.png){: img_center}](http://creativecommons.org/licenses/by-nc-sa/4.0/)
