<template>
  <nav class="nav">
    <ul>
      <li>
        <a href="">О нас</a>
      </li>
      <li>
        <a href="">Создание сайтов</a>
      </li>
      <li>
        <a href="">Маркетинг и продвижение</a>
      </li>
      <li>
        <a href="">Сопровождение сайтов</a>
      </li>
      <li>
        <a href="">Портфолио</a>
      </li>
      <li>
        <a href="">Цены</a>
      </li>
      <li>
        <a href="">Контакты</a>
      </li>
    </ul>
  </nav>
</template>

<script>
export default {
}
</script>

<style scoped>
.nav ul {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 15px 0;
}
.nav ul li a {
  text-decoration: none;
  color: #000;
  font-size: 17px;
  font-style: normal;
  font-weight: 500;
  line-height: 150%; /* 25.5px */
}
</style>
