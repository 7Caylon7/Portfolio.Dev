<template>
  <header>
    <div class="navbar">
      <div class="logo">
        <img src="#" alt="#">
        <h2>Solon.Dev</h2>
      </div>
      <ul class="nav-links">
        <li><a href="#home">Home</a></li>
        <li><a href="#perfil">Perfil</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contato">Contact</a></li>
      </ul>
      <div class="social-links">
        <a href="https://github.com/7Caylon7" target="_blank">
          <span class="pi pi-github" style="font-size: 1.5rem"></span>
        </a>
        <a href="https://www.linkedin.com/in/caylon-solon-monte-costa-10624823b" target="_blank">
          <span class="pi pi-linkedin" style="font-size: 1.5rem"></span>
        </a>
        <a href="https://www.instagram.com/ca_ylon?igsh=YnptaGp3MXFhZmdj" target="_blank">
          <span class="pi pi-instagram" style="font-size: 1.5rem"></span>
        </a>
        <a href="https://wa.me/91982671271" target="_blank">
          <span class="pi pi-whatsapp" style="font-size: 1.5rem"></span>
        </a>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: 'NavBar'
}
</script>

<!-- Adicione o atributo "escopo" para limitar o CSS apenas a este componente -->
<style scoped>
.navbar{
  background-color: #212121;
  color: #fff;
  padding: 1rem;
  display: flex;
  flex-wrap: nowrap;
  justify-content: space-around;
  align-items: center;
}

.nav-links{
  color: #fff;
  display: flex;
  gap: 3rem;
  font-size: 1.2rem;
}

.nav-links li {
  padding: .5rem;
  border: none;
  outline: none;
  border-radius: 0.3rem;
  cursor: pointer;
  background-color: #0E0E1A;
  font-weight: 700;
  box-shadow: 0px 0px 60px #1f4c65;
  transition: all 3s;
  -webkit-box-reflect: below 10px linear-gradient(to bottom, rgba(0,0,0,0.0), rgba(0,0,0,0.4));
}


.nav-links li:hover {
  background: linear-gradient(270deg, rgba(2, 29, 78, 0.681) 0%, rgba(31, 215, 232, 0.873) 60%);
  color: #040426;
  transition-duration: 1s;
}


a{
  color: #fff;
}

.social-links a{
  margin-right: 0.5rem;
}
</style>
