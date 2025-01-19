+++
title = "Cluster"
description = "Cluster Layout from Every Layout"
+++

<details>
  <summary>Cluster Style</summary>

```scss
{{ include_code(path="sass/layout/_cluster.scss") }}
```
</details>


## Cluster Normal (justify-content: flex-start)
<div class="cluster">
  <div class="box">Home</div>
  <div class="box">About</div>
  <div class="box">Contact</div>
</div>

## Cluster Center (justify-content: center)
<div class="cluster" style="justify-content: center">
  <div class="box">Home</div>
  <div class="box">About</div>
  <div class="box">Contact</div>
</div>

## Cluster Normal (justify-content: flex-end)
<div class="cluster" style="justify-content: flex-end">
  <div class="box">Home</div>
  <div class="box">About</div>
  <div class="box">Contact</div>
</div>
