<script lang="ts">
  export let size = '16';
  export let role = 'img';
  export let color = 'currentColor';
  export let ariaLabel = 'move to top 24';
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
    d="M4.75 3.5a.75.75 0 0 1 0-1.5h14.5a.75.75 0 0 1 0 1.5H4.75Zm.47 9.47a.749.749 0 1 0 1.06 1.06l4.97-4.969V21.25a.75.75 0 0 0 1.5 0V9.061l4.97 4.969a.749.749 0 1 0 1.06-1.06l-6.25-6.25a.749.749 0 0 0-1.06 0l-6.25 6.25Z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-oct.vercel.app/)
## Props
@prop export let size = '16';
@prop export let role = 'img';
@prop export let color = 'currentColor';
@prop export let ariaLabel = 'move to top 24';
-->
