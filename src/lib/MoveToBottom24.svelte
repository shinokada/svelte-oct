<script lang="ts">
  export let size = '16';
  export let color = 'currentColor';
  export let ariaLabel = 'move to bottom 24';
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
    d="M4 21.25a.75.75 0 0 1 .75-.75h14.5a.75.75 0 0 1 0 1.5H4.75a.75.75 0 0 1-.75-.75ZM5.22 9.97a.749.749 0 0 1 1.06 0l4.97 4.969V2.75a.75.75 0 0 1 1.5 0v12.189l4.97-4.969a.749.749 0 1 1 1.06 1.06l-6.25 6.25a.749.749 0 0 1-1.06 0l-6.25-6.25a.749.749 0 0 1 0-1.06Z"
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
