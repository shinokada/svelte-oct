# Svelte Oct

<div class="flex gap-2 my-8">
<a href="https://github.com/sponsors/shinokada" target="_blank"><img src="https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&color=%23fe8e86" alt="sponsor" height="25"></a>
<a href="https://www.npmjs.com/package/svelte-oct" rel="nofollow" target="_blank"><img src="https://img.shields.io/npm/v/svelte-oct" alt="npm" height="25"></a>
<a href="https://twitter.com/shinokada" rel="nofollow" target="_blank"><img src="https://img.shields.io/badge/created%20by-@shinokada-4BBAAB.svg" alt="Created by Shin Okada" height="25"></a>
<a href="https://opensource.org/licenses/MIT" rel="nofollow" target="_blank"><img src="https://img.shields.io/github/license/shinokada/svelte-oct" alt="License" height="25"></a>
<a href="https://www.npmjs.com/package/svelte-oct" rel="nofollow" target="_blank"><img src="https://img.shields.io/npm/dw/svelte-oct.svg" alt="npm" height="25"></a>
</div>

500+ SVG [Octicons](https://github.com/primer/octicons) components for Svelte. 

Thank you for considering my open-source package. If you use it in a commercial project, please support me by sponsoring me on GitHub: https://github.com/sponsors/shinokada. Your support helps me maintain and improve this package for the benefit of the community.


## Repo

[GitHub Repo](https://github.com/shinokada/svelte-oct)

## Original source

[primer/octicons](https://github.com/primer/octicons)

## License

[Svelte-Oct License](https://github.com/shinokada/svelte-oct/blob/main/LICENSE)

[primer/octicons LICENSE](https://github.com/primer/octicons/blob/main/LICENSE)

## Installation

```sh
pnpm i -D svelte-oct
```

## Usages

In a svelte file:

```html
<script>
  import { Accessibility16, Alert16, Archive16 } from 'svelte-oct';
</script>

<Accessibility16 />
<Alert16 />
<Archive16 />
```

## Faster compiling

If you need only a few icons from this library in your Svelte app, import them directly. This can optimize compilation speed and improve performance by reducing the amount of code processed during compilation.

```html
<script>
  import Archive16 from 'svelte-oct/Archive16.svelte';
</script>

<Archive16 />
```

If you are a TypeScript user, install **typescript version 5.0.0 or above**.

```sh
pnpm i -D typescript@beta
```

To avoid any complaints from the editor, add `node16` or `nodenext` to `moduleResolution` in your tsconfig.json file.

```json
{
  //...
  "compilerOptions": {
    // ...
    "moduleResolution": "nodenext"
  }
}
```

## Props

- size = '16';
- role = 'img';
- color = 'currentColor';
- ariaLabel = 'accessibility 16';

## IDE support

If you are using an LSP-compatible editor, such as VSCode, Atom, Sublime Text, or Neovim, hovering over a component name will display a documentation link, features, props, events, and an example.

## Size

Use the `size` prop to change the size of icons.

```html
<Accessibility16 size="40" />
<Alert16 size="50" />
<Archive16 size="60" />
```

If you are using Tailwind CSS, you can add a custom size using Tailwind CSS by including the desired classes in the class prop. For example:

```html
<Accessibility16 class="shrink-0 h-20 w-20" />
```

## CSS HEX Colors

Use the `color` prop to change colors with HEX color code.

```html
<Accessibility16 color="#c61515" />
<Alert16 color="#3759e5" />
<Archive16 color="#3fe537" />
```

## CSS framworks suport

You can apply CSS framework color and other attributes directly to the icon component or its parent tag using the `class` prop.

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

## Unfocusable icon

If you want to make an icon unfocusable, add `tabindex="-1"`.

```html
<Accessibility16 tabindex="-1" />
```

## Events

All icons have the following events:

- on:click
- on:keydown
- on:keyup
- on:focus
- on:blur
- on:mouseenter
- on:mouseleave
- on:mouseover
- on:mouseout

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

[Svelte-Icon-Sets](https://svelte-svg-icons.vercel.app/)

