<script>
  import Header from '../components/Header.svelte';
  import Main from '../components/Main.svelte';
  import Sidebar from '../components/Sidebar.svelte';
  import TimeLine from '../components/TimeLine.svelte';
</script>

<style>
  :global(body) {
    margin: 0;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto,
      Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji",
      "Segoe UI Symbol";
    background-color: #637383;
    color: #fff;
  }
</style>

<Header />
<Main>
  <TimeLine />
  <Sidebar />
</Main>