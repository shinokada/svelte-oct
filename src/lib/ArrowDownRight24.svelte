<script lang="ts">
  export let size = '16';
  export let color = 'currentColor';
  export let ariaLabel = 'arrow down right 24';
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
  viewBox="0 0 24 24"
  ><path
    d="M18.25 8.5a.75.75 0 0 1 .75.75v9a.75.75 0 0 1-.75.75h-9a.75.75 0 0 1 0-1.5h7.19L6.22 7.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L17.5 16.44V9.25a.75.75 0 0 1 .75-.75Z"
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
