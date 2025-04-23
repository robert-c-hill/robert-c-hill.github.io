---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<html>

<head>
    <title>PDF in HTML</title>
</head>
<style>
    .pdf {
        width: 100%;
        aspect-ratio: 4 / 3;
    }

    .pdf,
    html,
    body {
        height: 100%;
        margin: 0;
        padding: 0;
    }

    h1,
    h3 {
        text-align: center;
    }

    h1 {
        color: black;
    }
</style>

<body>

    <h1>Curriculum Vitae</h1>
    <object class="pdf" 
            data=
"https://robert-c-hill.github.io/files/Robert.C.Hill_CV.pdf"
            width="800"
            height="500">
    </object>
</body>

</html>


