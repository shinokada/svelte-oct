<script lang="ts">
  export let size = '16';
  export let color = 'currentColor';
  export let ariaLabel = 'arrow both 16';
</script>

<svg
  xmlns="http://www.w3.org/2000/svg"
  width={size}
  height={size}
  fill={color}
  class={$$props.class}
  {...$$restProps}
  aria-label={ariaLabel}
  on:click
  on:keydown
  on:keyup
  on:focus
  on:blur
  on:mouseenter
  on:mouseleave
  on:mouseover
  on:mouseout
  viewBox="0 0 16 16"
  ><path
    d="M3.72 3.72a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042L2.56 7h10.88l-2.22-2.22a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018l3.5 3.5a.75.75 0 0 1 0 1.06l-3.5 3.5a.749.749 0 0 1-1.275-.326.749.749 0 0 1 .215-.734l2.22-2.22H2.56l2.22 2.22a.749.749 0 0 1-.326 1.275.749.749 0 0 1-.734-.215l-3.5-3.5a.75.75 0 0 1 0-1.06Z"
  /></svg
>
<!--
@component
[Go to Document](https://svelte-oct.codewithshin.com/)
## Props
@prop size = '24';
@prop color = 'currentColor';
@prop ariaLabel = 'icon file name';
## Event
- on:click
- on:keydown
- on:keyup
- on:focus
- on:blur
- on:mouseenter
- on:mouseleave
- on:mouseover
- on:mouseout
-->
