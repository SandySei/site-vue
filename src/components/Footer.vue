<script>
export default {};
</script>

<template>
  <div id="Footer">
    <div id="notes">
      <p>By sandyalves98@hotmail.com</p>

      <nav>
        <a
          href="https://github.com/SandySei"
          class="btn btn-white btn-animate"
          target="_blank"
          style="display: flex; align-items: center"
        >
          Git Hub&emsp;
          <img src="/arquivos/Git.png" alt="Logo GitHub" width="30" />
        </a>

        <a
          href="https://www.linkedin.com/in/sandyseixas"
          class="btn btn-white btn-animate"
          target="_blank"
          style="display: flex; align-items: center"
        >
          LinkedIn&emsp;
          <img src="/arquivos/Linkedin.png" alt="Logo LinkedIn" width="30" />
        </a>

        <a
          href="https://wa.me/5541997576128"
          class="btn btn-white btn-animate"
          target="_blank"
          style="display: flex; align-items: center"
        >
          WhatsApp&emsp;
          <img src="/arquivos/Whatsapp.png" alt="Logo Whats" width="30" />
        </a>
      </nav>
    </div>
  </div>
</template>

<style scoped>
nav {
  display: flex;
  justify-content: space-between;
}

div#Footer {
  background-color: #000000;
  min-height: 6vh;
}

div#notes {
  display: flex;
  justify-content: space-evenly;
  align-items: center;
  flex-direction: row;
}

p,
a {
  color: white;
  text-transform: uppercase;
  text-decoration: none;
  padding: 10px 12px;
  display: inline-block;
  font-family: Arial;
  font-size: 12px;
  font-weight: bold;
}
a.btn:link {
  text-transform: uppercase;
  text-decoration: none;
  padding: 6px 12px;
  display: inline-block;
  border-radius: 50px;
  transition: all 0.3s;
  font-family: Arial;
  font-size: 12px;
  font-weight: bold;
}

.btn:hover {
  transform: translateY(-3px);
  box-shadow: 0 2px 4px #ffffff;
}

.btn:active {
  transform: translateY(-1px);
  box-shadow: 0 5px 10px rgb(255, 255, 255);
}

.btn-white {
  background-color: #000000;
  color: #ffffff;
}

.btn::after {
  content: "";
  display: inline-block;
  height: 100%;
  width: 100%;
  border-radius: 100px;
  position: absolute;
  top: 0;
  left: 0;
  z-index: -1;
  transition: all 0.4s;
}

.btn-white::after {
  background-color: #033691;
}

.btn:hover::after {
  transform: scaleX(1.4) scaleY(1.6);
  opacity: 0;
}
</style>
