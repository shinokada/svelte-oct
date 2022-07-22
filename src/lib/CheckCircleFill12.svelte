<script lang="ts">
  export let size = '16';
  export let color = 'currentColor';
  export let ariaLabel = 'check circle fill 12';
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
  ><path
    fill-rule="evenodd"
    d="M6 0a6 6 0 100 12A6 6 0 006 0zm-.705 8.737L9.63 4.403 8.392 3.166 5.295 6.263l-1.7-1.702L2.356 5.8l2.938 2.938z"
  /></svg
>
