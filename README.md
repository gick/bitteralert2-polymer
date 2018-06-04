# `<bitter-alert>` - a Polymer 1 wrapper for [SweetAlert2](https://github.com/gick/bitter-alert)
# forked from Polymer 2 [sweet-alert](https://github.com/limonte/sweetalert2-polymer)

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

# Installation

```bash
bower install --save sweetalert2-polymer
```

# Usage

```html
<link rel="import" href="bower_components/sweet-alert/sweet-alert.html">

<sweet-alert type="success" title="Awesome"></sweet-alert>
```
