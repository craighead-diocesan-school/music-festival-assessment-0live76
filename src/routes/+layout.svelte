<script>
  import "../app.scss"
</script>

<slot />

<style>
  @media only screen and (max-width: 600px) {
    :global(body) {
      width: 100%;
    }
  }
</style>
