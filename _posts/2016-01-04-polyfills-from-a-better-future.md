---
inFeed: true
hasPage: true
inNav: false
inLanguage: null
starred: false
keywords: []
description: Grid Style Sheet
datePublished: '2016-01-04T09:05:36.316Z'
dateModified: '2016-01-04T09:05:17.609Z'
title: Polyfills from a Better Future
author: []
authors: []
publisher:
  name: null
  domain: null
  url: null
  favicon: null
sourcePath: _posts/2016-01-04-polyfills-from-a-better-future.md
published: true
url: polyfills-from-a-better-future/index.html
_type: Article

---
Web developers are expected to build increasingly sophisticated UIs faster, cheaper, with tools that have not evolved with the times. Why is the trivial task of centering an element with CSS so

? CSS was designed to separate presentation from content, but even with

, a trivial change in layout can require deep changes in both the HTML content and the CSS presentation. CSS layout primitives are not expressive enough - it doesn't really matter that some div is 720px wide - what matters is how it relates to other elements in the layout. WTF, why can't we position & size elements relative to each other, not just relative to their positioned parents? For more than a decade, web developers have been asking for this, but the W3C refuses to tackle the engineering problems associated with the "cyclic dependencies" that naturally arise in relative layout logic. Sounds like a classic constraint satisfaction problem - JavaScript to the rescue!
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/ffe64358-ed21-40d8-ac84-f8585972795f.jpg)

Web developers are expected to build increasingly sophisticated UIs faster, cheaper, with tools that have not evolved with the times. Why is the trivial task of centering an element with CSS so

[obtusely complex][0]

? CSS was designed to separate presentation from content, but even with

[Flexbox][1]

, a trivial change in layout can require deep changes in both the HTML content and the CSS presentation. CSS layout primitives are not expressive enough - it doesn't really matter that some div is 720px wide - what matters is how it relates to other elements in the layout. WTF, why can't we position & size elements relative to each other, not just relative to their positioned parents? For more than a decade, web developers have been asking for this, but the W3C refuses to tackle the engineering problems associated with the "cyclic dependencies" that naturally arise in relative layout logic. Sounds like a classic constraint satisfaction problem - JavaScript to the rescue!

[0]: http://coding.smashingmagazine.com/2013/08/09/absolute-horizontal-vertical-centering-css/
[1]: https://developer.mozilla.org/en-US/docs/Web/Guide/CSS/Flexible_boxes