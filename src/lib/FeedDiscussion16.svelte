<script lang="ts">
  export let size = '16';
  export let color = 'currentColor';
  export let ariaLabel = 'feed discussion 16';
</script>

<svg
  xmlns="http://www.w3.org/2000/svg"
  width={size}
  height={size}
  fill={color}
  class={$$props.class}
  {...$$restProps}
  aria-label={ariaLabel}
  viewBox="0 0 16 16"
  ><path
    fill-rule="evenodd"
    d="M8 16A8 8 0 108 0a8 8 0 000 16zM4 5a1 1 0 011-1h6a1 1 0 011 1v5a1 1 0 01-1 1H8.707l-1.853 1.854A.5.5 0 016 12.5V11H5a1 1 0 01-1-1V5z"
  /></svg
>
