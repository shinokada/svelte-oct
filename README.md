# Svelte-Oct icons

[![npm version](https://badgen.net/npm/v/svelte-oct)](https://www.npmjs.com/package/svelte-oct)
[![license](https://badgen.net/npm/license/svelte-oct)](https://github.com/shinokada/svelte-oct/blob/main/LICENSE)

500+ SVG [Octicons](https://github.com/primer/octicons) components for Svelte. Svelte-oct icons support major CSS frameworks using the `class` props.

<p align="center">
<img width="450" src="https://raw.githubusercontent.com/shinokada/svelte-oct/main/static/images/octicons.webp" />
</p>

## Icon name list

[Icon list](https://github.com/shinokada/svelte-oct/blob/main/icon-list.md)

## Installation

```sh
npm i -D svelte-oct
```

## REPL

[Demo](https://svelte.dev/repl/60e7000b54004872aa4006535fcef7fd?version=3.48.0)

## Usages

In a svelte file:

```html
<script>
  import {
    Accessibility16,
    Alert16,
    Archive16
  } from 'svelte-oct';
</script>

<Accessibility16 />
<Alert16 />
<Archive16 />
```

## Size

Use the `size` prop to change the size of icons.

```html
<Accessibility16 size="40" />
<Alert16 size="50" />
<Archive16 size="60" />
```

## CSS HEX Colors

Use the `color` prop to change colors with HEX color code.

```html
<Accessibility16 color="#c61515" />
<Alert16 color="#3759e5" />
<Archive16 color="#3fe537" />
```

## CSS framworks suport

Use the `class` prop to change size, colors and add additional css.

Tailwind CSS example:

```html
<Accessibility16 class="h-24 w-24 text-blue-700 mr-4" />
```

Bootstrap examples:

```html
<Accessibility16 class="position-absolute top-0 px-1" />
```

## Dark mode

If you are using the dark mode on your website with Tailwind CSS, add your dark mode class to the `class` prop.

Let's use `dark` for the dark mode class as an example.

```html
<Accessibility16 class="text-blue-700 dark:text-red-500" />
```

## aria-label

All icons have aria-label. For example `Accessibility16` has `aria-label="accessibility 16"`.
Use `ariaLabel` prop to modify the `aria-label` value.

```html
<Accessibility16 ariaLabel="accessibility" />
```

## Passing down other attributes

You can pass other attibutes as well.

```html
<Accessibility16 tabindex="0" />
```

## Using svelte:component

```html
<script>
  import { Accessibility16 } from 'svelte-oct';
</script>

<svelte:component this="{Accessibility16}" />
```

## Using onMount

```html
<script>
  import { Accessibility16 } from 'svelte-oct';
  import { onMount } from 'svelte';
  const props = {
    size: '50',
    color: '#ff0000'
  };
  onMount(() => {
    const icon = new Accessibility16({ target: document.body, props });
  });
</script>
```

## Import all

Use `import * as Icon from 'svelte-oct`.

```html
<script>
  import * as Icon from 'svelte-oct';
</script>

<Icon.Accessibility16 />
<Icon.Alert16 />

<h1>Size</h1>
<Icon.Accessibility16 size="30" />
<Icon.Alert16 size="40" />

<h1>CSS HEX color</h1>
<Icon.Accessibility16 color="#c61515" size="40" />

<h1>Tailwind CSS</h1>
<Icon.Accessibility16 class="text-blue-500" />
<Icon.Alert16 class="text-pink-700" />
```

## Other icons

- [Svelte-Icon-Sets](https://svelte-svg-icons.vercel.app/)
