---
layout: post
redirect_from:
  - /components/
id: page-badges
title: Badges
page-header:
  headline: Badges
toc: true
---

<p>

  Badges are a lightweight method of annotating or labeling content. Wrap content in the <code>.badge</code> class to add an inline badge. The font-size and line-height of a badge inherit from that of it's parent's properties.

</p>

<!-- =================================================
BEGIN: Example
================================================== -->

<div class="panel flush-bottom">

  <div class="panel-cell">

    <span class="badge">

      Badge

    </span>

  </div>

  <div class="panel-cell panel-cell-light panel-cell-code-block">

<pre class="prettyprint transparent flush lang-html">
&lt;span class="badge"&gt;
  Badge
&lt;/span&gt;
</pre>

  </div>

</div>

<!-- =================================================
END: Example
================================================== -->

{% include components/badges/badges-states.md %}
{% include components/badges/badges-rounded.md %}