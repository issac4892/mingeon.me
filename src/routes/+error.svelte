<script lang="ts">
  import { page } from '$app/stores';
</script>

<svelte:head>
  <title>{$page.status}</title>
</svelte:head>

<div class="container">
  <div class="emphasis">{$page.status}</div>
  <div class="soon">{$page.error}</div>
</div>

<style>
  .container {
    width: 100%;
    height: 100%;

    display: flex;
    flex-direction: column;

    justify-content: center;
    align-items: center;

    gap: 30px;
  }

  .soon {
    font-size: 12px;
  }

  .emphasis {
    font-weight: 700;
  }
</style>
