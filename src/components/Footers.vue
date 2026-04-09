<template>
  <footer class="footer" id="about">
    <div class="footer-content">
      <div class="contact-row">
        <span><strong>Email:</strong> info@ubumwehotel.rw</span>
        <span class="separator">|</span>
        <span><strong>Phone:</strong> +250 722 472 350</span>
      </div>

      <div class="social-links">
        <a href="https://facebook.com/t__natty" target="_blank">Facebook</a>
        <a href="https://twitter.com/t__natty" target="_blank">Twitter</a>
        <a href="https://instagram.com/t__natty" target="_blank">Instagram</a>
        <a href="https://linkedin.com/t__natty" target="_blank">LinkedIn</a>
      </div>

      <div class="bottom-bar">
        <p>© 2026 UBUMWE Hotel - Huye District</p>
        <p class="dev-tag">Developed by <span>Nayihembiki Joselynne</span> from BICTHUB</p>
      </div>
    </div>
  </footer>
</template>

<style scoped>
.footer {
  /* Strictly maintained positions */
  position: absolute;
  left: 15px;
  top: 500px;
  width: 1150px;
  height: 150px;
  
  /* Visual Styles */
  background: #2c2c2c;
  color: white;
  padding: 20px;
  text-align: center;
  border-radius: 4px;
  box-shadow: inset 0px 4px 10px coral;
  display: flex;
  flex-direction: column;
  justify-content: center;
  box-sizing: border-box; /* Ensures padding doesn't break the width */
}

.contact-row {
  margin-bottom: 10px;
  font-size: 0.9rem;
}

.separator {
  margin: 0 15px;
  color: coral;
}

.social-links {
  margin-bottom: 15px;
}

.social-links a {
  margin: 0 12px;
  color: #4db6ac;
  text-decoration: none;
  font-weight: 500;
  transition: 0.3s;
}

.social-links a:hover {
  color: coral;
  text-decoration: underline;
}

.bottom-bar {
  font-size: 0.8rem;
  border-top: 1px solid #444;
  padding-top: 10px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.dev-tag span {
  color: #4db6ac;
  font-weight: bold;
}
</style>