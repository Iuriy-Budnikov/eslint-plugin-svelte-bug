<script lang="ts">
  import Wrapper from './Wrapper.svelte';
</script>

<Wrapper>
  {@const text = 'text'}
  <button>
    {text}
  </button>
</Wrapper>
