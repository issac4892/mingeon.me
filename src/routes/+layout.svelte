<script lang="ts">
  let { children } = $props();
</script>

<div class="layout">
  {@render children()}
</div>

<style>
  @font-face {
    font-family: 'LINE Seed KR';
    font-weight: 400;
    src: url('/fonts/LINESeedKR-Rg.woff2') format('woff2');
  }

  @font-face {
    font-family: 'LINE Seed KR';
    font-weight: 100;
    src: url('/fonts/LINESeedKR-Th.woff2') format('woff2');
  }

  @font-face {
    font-family: 'LINE Seed KR';
    font-weight: 700;
    src: url('/fonts/LINESeedKR-Bd.woff2') format('woff2');
  }

  :root {
    font-family:
      'LINE Seed KR',
      system-ui,
      -apple-system,
      BlinkMacSystemFont,
      'Segoe UI',
      Roboto,
      Oxygen,
      Ubuntu,
      Cantarell,
      'Open Sans',
      'Helvetica Neue',
      sans-serif;

    width: 100%;
    height: 100%;
  }

  .layout {
    width: 100%;
    height: 100%;
  }
</style>
