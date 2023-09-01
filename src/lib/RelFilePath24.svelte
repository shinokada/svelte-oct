<script lang="ts">
  export let size = '16';
  export let role = 'img';
  export let color = 'currentColor';
  export let ariaLabel = 'rel file path 24';
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
    d="M19.564 4.42a.75.75 0 0 0-1.378-.59l-6.75 15.75a.75.75 0 0 0 1.378.59l6.75-15.75ZM7 18.5a1.5 1.5 0 1 1-3 0 1.5 1.5 0 0 1 3 0Z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-oct.vercel.app/)
## Props
@prop export let size = '16';
@prop export let role = 'img';
@prop export let color = 'currentColor';
@prop export let ariaLabel = 'rel file path 24';
-->
