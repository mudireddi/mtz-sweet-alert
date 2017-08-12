# `<sweet-alert>` - a Polymer wrapper for [SweetAlert2](https://github.com/limonte/sweetalert2)

![Bower version](https://img.shields.io/bower/v/sweetalert2-polymer.svg)
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/limonte/sweetalert2-polymer)

[Live demo ↗](https://limonte.github.io/sweetalert2-polymer/components/sweet-alert/#/elements/sweet-alert/demos/demo/index.html)

<!--
```
<custom-element-demo height="450">
  <template>
    <link rel="import" href="sweet-alert.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<sweet-alert title="Oops..." text="Something went wrong!" type="error"></sweet-alert>

<script>
  document.querySelector('sweet-alert').open()
</script>
```