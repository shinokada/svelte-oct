<script lang="ts">
  export let size = '16';
  export let color = 'currentColor';
  export let ariaLabel = 'x circle fill 24';
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
    d="M1 12C1 5.925 5.925 1 12 1s11 4.925 11 11-4.925 11-11 11S1 18.075 1 12Zm8.036-4.024a.751.751 0 0 0-1.042.018.751.751 0 0 0-.018 1.042L10.939 12l-2.963 2.963a.749.749 0 0 0 .326 1.275.749.749 0 0 0 .734-.215L12 13.06l2.963 2.964a.75.75 0 0 0 1.061-1.06L13.061 12l2.963-2.964a.749.749 0 0 0-.326-1.275.749.749 0 0 0-.734.215L12 10.939Z"
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
