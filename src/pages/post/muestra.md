---
setup: |
  import Layout from '../../layouts/Post.astro'
title: Muestra de astro!
date: 8 Feb 2022
urlto: 'post/muestra'
desc: Muestra de lo que se puede hacer usando Astro
author: L1ghtingBolt
nsfw: false
---
Este es un post del blog, hecho en Astro.
El blog está hecho en Svelte.
A su vez, las publicaciones en Markdown, pero...

Tiene ese markdown posibilidad para <b>HTML</b> y <b>CSS</b>? <i>Si</i>!
<div>
<br/>
<h1 class="text-3xl font-bold mb-10">Titulo H1 con HTML estilizado!</h1>
<label for="cb">Label con una checkbox</label>

<input type="checkbox" id="cb">
<style>
    .divrojo {
        background: red;
        color: white;
        border-radius: 10px;
        padding: 5px;
        width: 100px;
        margin: auto;
    }
</style>
<div class="divrojo">
    Div rojo usando css
</div>
</div>