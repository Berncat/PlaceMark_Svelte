<script>
  import { user } from "../stores.js";
</script>

{#if $user.email}
  <p class="has-text-right">Logged in: {$user.email}</p>
{:else}
  <p class="has-text-right">Not Logged in</p>
{/if}
<div class="is-flex columns is-centered">
  <p class="title is-1 m-5">
    <i style="color:hsl(204, 86%, 53%);" class="fas fa-map-marker-alt" /> Placemark.ie
  </p>
</div>
