<template>
  <div class="Hero container">
    <div class="text-container">
      <h3 class="header">Find your Fire Extinguisher</h3>
      <p class="snippet">
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste iusto
        illum quidem asperiores, cum nisi aperiam eius ipsa sapiente odit!
      </p>
      <button class="button btn">Start Looking</button>
    </div>
    <img
      class="image"
      src="~assets/svg/fire-extinguisher.svg"
      alt="fire extinguisher"
    />
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.Hero {
  height: 80vh;
  position: relative;
  display: flex;
  padding: 5rem;
  align-items: flex-start;
  justify-content: space-between;
  margin-bottom: 5rem;
}

.text-container {
  width: 50%;
  margin-top: 4rem;
}

.header {
  font-weight: 900;
  font-size: 4rem;
}

.snippet {
  color: grey;
  font-size: 1 rem;
}

.image {
  width: 27.5rem;
  margin-top: 2rem;
}

.overlay {
  background: rgba(0, 0, 0, 0);
  position: absolute;
  width: 100%;
  height: 100%;
  top: 0;
}

.button {
  padding: 1rem 4rem;
  border-radius: 100rem;
  background-color: rgb(231, 81, 43);
  color: white;
  width: 20rem;
  font-weight: 700;
  transition: 0.5s;
}

.button:hover {
  width: 21.5rem;
}

@media (max-width: 500px) {
  .Hero {
    height: 40vh;
  }
}
</style>
