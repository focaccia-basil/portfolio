<template>
  <div class="container">
    <ul class="all-skills">
      <li class="skillset">
        <h3>FRONTEND</h3>
        <ul class="icons">
          <li class="icon">
            <img src="@/assets/logo.png" />
          </li>
          <li class="icon">
            <img src="@/assets/html.png" />
          </li>
          <li class="icon">
            <img src="../assets/css3.png" />
          </li>
        </ul>
      </li>
      <div style="font-size: 45px">+</div>
      <li class="skillset">
        <h3>BACKEND</h3>
        <ul class="icons">
          <li class="icon">
            <img src="@/assets/java.png" />
          </li>
          <li class="icon">
            <img src="@/assets/python.png" />
          </li>
          <li class="icon">
            <img src="../assets/js.png" />
          </li>
        </ul>
      </li>
      <div style="font-size: 45px">+</div>
      <li class="mobile">
        <h3>MOBILE</h3>
        <ul class="icons">
          <li class="icon">
            <img src="@/assets/swift.png" />
          </li>
        </ul>
      </li>
    </ul>
  </div>
</template>

<style scoped>
.container {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
}

.container ul {
  list-style: none;
}

.container .all-skills {
  display: flex;
  flex-direction: column;
}

.all-skills .skillset,
.mobile {
  margin: 2rem;
  min-width: 1000px;
  border: 1px solid peachpuff;
  border-radius: 22px;
  cursor: pointer;
}
.skillset .icons {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
}
.skillset .mobile {
  display: flex;
  justify-content: center;
}

.skillset:hover,
.mobile:hover {
  background: rgb(26, 26, 26);
}

img {
  max-height: 200px;
  max-width: 200px;
  min-height: 50px;
  min-width: 50px;
}
</style>
