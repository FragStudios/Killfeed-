<script>
  // import svelteLogo from './assets/svelte.svg';
</script>

<main >
  <div class = "killfeed_container">
  <div class = "killer">
    <h1>Jay</h1>
    <img src="https://i.imgur.com/rQzloYs.png" alt="">
  </div>
  <div class = "victim">
    <h1>Jay</h1>
    <img src="https://i.imgur.com/rQzloYs.png" alt="">
  </div>
</div>

</main>

<style>
  main {
    position: relative;
    width: 100%;
    height: 100%;
    background-image: url(https://i.imgur.com/a9YO4qc.png);
    background-size: cover;
    margin: 0 auto;
    display: flex;
    justify-content: flex-end;
    align-items: flex-start;
  }

 .killfeed_container {
  background: rgba(88, 88, 88, 0.404);
    height: 4%;
    border-radius: 0.5rem;
    margin: 0.5%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding-inline: 2%;
}
.victim {
  display: flex;
    flex-direction: row-reverse;
    align-items: center;
    justify-content: center;
    align-content: center;

}
.killer {
  display: flex;
}


.victim > img,
.killer > img {
 width: 3rem;
}


</style>
