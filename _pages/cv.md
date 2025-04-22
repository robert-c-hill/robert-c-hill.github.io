---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<!DOCTYPE html>
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

    
</style>

<body>

    <h3>Embedding the PDF file Using Object Tag</h3>
    <object class="pdf" 
            data=
"https://www.w3.org/WAI/ER/tests/xhtml/testfiles/resources/pdf/dummy.pdf"
            width="800"
            height="500">
    </object>
</body>

</html>
