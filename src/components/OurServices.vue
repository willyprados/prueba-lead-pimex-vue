<template>
  <section class="banner">
    <p class="pre-title">bringing you proven results</p>
    <div class="star_line">
      <h1>Our Services</h1>
      <hr />
      <span class="fas fa-star"></span>
    </div>
    <p
      class="description"
    >Movie comes buit with a cool interactive services tab system custom buit by Pulsar Media.</p>
    <div class="iconBack">
      <i class="fas fa-code-branch">
        <h2>Marketing</h2>
      </i>
      <i class="fas fa-rocket">
        <h2>Advertising</h2>
      </i>
      <i class="fas fa-cloud">
        <h2>Cloud Storage</h2>
      </i>
      <i class="fas fa-users">
        <h2>Consulting</h2>
      </i>
    </div>
  </section>
</template>

<script>
export default {
  name: "OurServices",
  props: {
    title: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
section {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  margin-top: 1rem;
}
h1 {
  color: #5cc9c1;
  text-transform: uppercase;
  font-size: 3rem;
  margin-top: 0.5rem;
  margin-bottom: 0.5rem;
  font-weight: 600;
}
hr {
  border: 1px solid #5cc9c1;
}
.pre-title {
  text-transform: uppercase;
  font-size: 0.8rem;
  margin-bottom: 0;
  font-weight: 100;
  color: #777;
}
.description {
  font-size: 0.8rem;
  color: #777;
  margin-bottom: 0.8rem;
}
.iconBack {
  background: url("https://images.unsplash.com/photo-1505506874110-6a7a69069a08?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1514&q=80")
    no-repeat center;
  align-self: stretch;
  color: white;
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  padding-top: 3rem;
  padding-bottom: 3rem;
}
.iconBack i {
  font-size: 3rem;
}
.iconBack h2 {
  font-size: 1rem;
  margin-bottom: 0;
}
.star_line {
  padding-left: 30px;
  padding-right: 30px;
}
.fa-star {
  color: #5cc9c1;
  background-color: white;
  position: relative;
  top: -20px;
  padding-left: 20px;
  padding-right: 20px;
}
</style>