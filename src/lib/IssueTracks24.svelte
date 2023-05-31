<script lang="ts">
  export let size = '16';
  export let color = 'currentColor';
  export let ariaLabel = 'issue tracks 24';
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
    d="M2.5 12a9.5 9.5 0 1 1 19 0 .75.75 0 0 0 1.5 0c0-6.075-4.925-11-11-11S1 5.925 1 12s4.925 11 11 11a.75.75 0 0 0 0-1.5A9.5 9.5 0 0 1 2.5 12Z"
  /><path
    d="M12 14a2 2 0 1 0 0-4 2 2 0 0 0 0 4Zm2.5 2.75a.75.75 0 0 1 .75-.75h7a.75.75 0 0 1 0 1.5h-7a.75.75 0 0 1-.75-.75Zm3.75 2.75a.75.75 0 0 0 0 1.5h4a.75.75 0 0 0 0-1.5h-4Z"
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
