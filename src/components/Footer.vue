<template>
  <footer class="footer">
    <div class="container">
      <div class="footer-box">
        <router-link to="/" class="footer-logo logo">
          <img src="../assests/image/logo.png" alt="logo" />
        </router-link>
        <div class="footer-nav">
          <ul>
            <a href="./goods.html">
              <li>Ресторанам</li>
            </a>
            <a href="./goods.html">
              <li>Курьерам</li>
            </a>
            <a href="./goods.html">
              <li>Пресс-центр</li>
            </a>
            <a href="./goods.html">
              <li>Контакты</li>
            </a>
          </ul>
        </div>
        <div class="footer-social">
          <img src="../assests/image/social/instagram.png" alt="INST" />
          <img src="../assests/image/social/facebook.png" alt="FB" />
          <img src="../assests/image/social/vk.png" alt="VK" />
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style scoped>
.footer {
  display: flex;
  align-items: center;
  min-height: 156px;
  padding: 60px 0;
}

.footer-box {
  height: 100%;
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: space-between;
  gap: 36px;
}

.footer-nav {
  flex-grow: 1;
}

.footer-nav ul {
  display: flex;
  align-items: center;
  list-style: none;
  padding: 0;
  margin: 0;
  gap: 15px;
  flex-wrap: wrap;
}

.footer-nav ul li {
  color: #595959;
  font-size: 18px;
  font-weight: 400;
}

.footer-nav ul a {
  text-decoration: none;
}

.footer-social {
  display: flex;
  align-items: center;
  justify-content: flex-end;
  gap: 20px;
}
</style>
