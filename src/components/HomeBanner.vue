<template>
  <section class="banner">
    <div class="main_title">
      <hr />
      <h1>ONE PAGE</h1>
      <h2>Multi-Purpose Theme</h2>
      <hr />
    </div>
    <p>Premium one-page multi-purpose theme perfect for everyone - start using Moxie today!</p>
    <button class="btnInit">get started</button>
  </section>
</template>

<script>
export default {
  name: "HomeBanner",
  props: {
    title: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
section {
  background: url("https://images.unsplash.com/photo-1451187580459-43490279c0fa?ixlib=rb-1.2.1&auto=format&fit=crop&w=1080&q=80")
    no-repeat center;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  background-size: cover;
  color: #fff;
  text-align: center;
  padding-top: 10rem;
  padding-bottom: 10rem;
}

h1 {
  font-size: 3rem;
  margin-top: 0.5rem;
  margin-bottom: 0.5rem;
  font-weight: 600;
}
h2 {
  font-size: 1.5rem;
  margin-top: 0.2rem;
  margin-bottom: 0.5rem;
  font-weight: 300;
}
p {
  font-weight: 100;
  margin: 3rem;
}

.btnInit {
  border-color: white;
  border-style: solid;
  padding: 10px 40px 10px 40px;
  background: none;
  color: white;
  font-family: "Raleway", sans-serif;
  font-weight: 600;
  text-transform: uppercase;
}
</style>