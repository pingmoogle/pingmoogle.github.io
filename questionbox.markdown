---
layout: page_with_diy_title
title: Box
diy_title: Ping's Question Box
permalink: /box/
---

<head>
    <script src='//unpkg.com/valine/dist/Valine.min.js'></script>
    <style type="text/css">.v[data-class=v] .vsys {visibility: hidden;}</style>
    <style type="text/css">
    .v[data-class=v] .status-bar, .v[data-class=v] .veditor, .v[data-class=v] .vinput, .v[data-class=v] p, .v[data-class=v] pre code {color: #000000 !important};
    </style>
</head>
<body>
<div>
    <div id="vcomments"></div>
    <script>
        new Valine({
            el: '#vcomments',
            appId: 'kFrG1MByLxgKAON8SQTP8lXC-gzGzoHsz',
            appKey: 'mcKCP02bv1aN2OJRjtfFYcDF',
            placeholder:"输入问题，昵称可以不填",
            avatar:"hide",
            meta:['nick']
        })
    </script>
</div>


</body>
