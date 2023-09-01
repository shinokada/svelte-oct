<script lang="ts">
  export let size = '16';
  export let role = 'img';
  export let color = 'currentColor';
  export let ariaLabel = 'share android 24';
</script>

<svg
  xmlns="http://www.w3.org/2000/svg"
  width={size}
  height={size}
  fill={color}
  {...$$restProps}
  {role}
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
    d="M20 5.5a3.498 3.498 0 0 1-6.062 2.385l-5.112 3.021a3.498 3.498 0 0 1 0 2.188l5.112 3.021a3.5 3.5 0 1 1-.764 1.29l-5.112-3.02a3.499 3.499 0 1 1-3.843-5.642 3.499 3.499 0 0 1 3.843.872l5.112-3.021A3.5 3.5 0 1 1 20 5.5Zm-1.5 13a2 2 0 1 0-3.999-.001 2 2 0 0 0 3.999.001Zm0-13a2 2 0 1 0-3.999-.001A2 2 0 0 0 18.5 5.5ZM5.5 14a2 2 0 1 0 .001-3.999A2 2 0 0 0 5.5 14Z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-oct.vercel.app/)
## Props
@prop export let size = '16';
@prop export let role = 'img';
@prop export let color = 'currentColor';
@prop export let ariaLabel = 'share android 24';
-->
