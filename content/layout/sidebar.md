+++
title = "Sidebar"
description = "Sidebar Layout from Every Layout"
+++

<details>
  <summary>Sidebar Style</summary>

```scss
{{ include_code(path="sass/layout/_sidebar.scss") }}
```

</details>

```html
<main class="with-sidebar">
  <aside class="sidebar"></aside>
  <article class="not-sidebar"></article>
</main>
```

<main class="with-sidebar">
  <aside class="sidebar">
    <div class="box">Sidebar</div>
  </aside>
  <article class="not-sidebar"><div class="box">Article</div></article>
</main>
