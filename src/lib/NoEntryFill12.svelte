<script lang="ts">
  export let size = '16';
  export let color = 'currentColor';
  export let ariaLabel = 'no entry fill 12';
</script>

<svg
  xmlns="http://www.w3.org/2000/svg"
  width={size}
  height={size}
  fill={color}
  class={$$props.class}
  {...$$restProps}
  aria-label={ariaLabel}
  viewBox="0 0 12 12"
  ><path fill-rule="evenodd" d="M6 0a6 6 0 100 12A6 6 0 006 0zm3 5H3v2h6V5z" /></svg
>
