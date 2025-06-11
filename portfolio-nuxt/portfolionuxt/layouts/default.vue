<template>
  <div>
    <header class="header">
      <h1 class="header-title"><span class="highlight">N</span>73</h1>
      <nav class="header-content">
        <NuxtLink to="/" class="header-item">top</NuxtLink>

        <NuxtLink to="/profile" class="header-item">profile</NuxtLink>

        <NuxtLink to="/work" class="header-item">works</NuxtLink>

        <NuxtLink to="/contact" class="header-item">contact</NuxtLink>
      </nav>
    </header>
    <main class="main">
      <slot />
    </main>
  </div>
</template>
<style>
body {
  background-color: #424242;
  color: #fff;
  margin: 0;
  padding: 0;
  font-family: sans-serif;
}

/* ヘッダー全体を横並び・中央揃え */
.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0px 50px;
  background-color: #2c2c2c;
  height: 90px;
}

/* タイトル */
.header-title {
  font-size: 35px;
  font-weight: bold;
  color: #fff;
}

/* Nの差し色 */
.highlight {
  color: #00c8ff;
}

/* ナビゲーションリンクの横並び */
.header-content {
  display: flex;
  gap: 30px;
}

/* 各リンクの見た目 */
.header-item {
  color: #fff;
  font-size: 25px;
  text-decoration: none;
  transition: color 0.3s ease;
}

.header-item:hover {
  color: #00c8ff;
}
</style>
