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

    h1 {
        color: green;
    }
</style>

<body>
        <h1>GeeksforGeeks</h1>
        <h3>Embedding the PDF file Using Iframe Tag</h3>
        <iframe class="pdf" 
                src=
"https://media.geeksforgeeks.org/wp-content/cdn-uploads/20210101201653/PDF.pdf"
            width="800" height="500">
        </iframe>
</body>

</html>
