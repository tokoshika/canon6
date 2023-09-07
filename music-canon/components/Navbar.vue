<template>
  <nav>
    <ul class="nav">
      <li>
        <NuxtLink to="/" style="color: green; text-decoration: none"
          >ホーム</NuxtLink
        >
      </li>
      <li>
        <NuxtLink to="/canon01" style="color: green; text-decoration: none"
          >教科書P26<span style="color: tomato">(楽器12)</span></NuxtLink
        >
      </li>
    </ul>
  </nav>

  <slot />
</template>

<style>
  .nav {
    display: flex;
    /* justify-content: space-between; */
    margin-left: 2rem;
    margin-right: 2rem;
    list-style: none;
    background-color: rgb(233, 223, 223);
    text-align: center;
    font-family: "Zen Maru Gothic";
  }

  li {
    margin-right: 3rem;
  }

  .color {
    text-decoration: none;
  }
</style>
