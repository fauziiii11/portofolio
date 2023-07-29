<template>
<Navbar></Navbar>
<hr>
<br>
<center><Header></Header></center>
<br>
<center><Hobi></Hobi></center>
<br>
<br>
<hr>
<br>
<Galery></Galery>
<br>
<hr>
<br>
<Skill></Skill>
<br>
<hr>
<br>
<center><History></History></center>
<br>
<hr>
<br>
<Kontak></Kontak>
<br>
<hr>
<br>
<Footer></Footer>
</template>

<script>
import Navbar from './components/Navbar.vue';
import Header from './components/Header.vue';
import Hobi from './components/Hobi.vue';
import Galery from './components/Galery.vue';
import Footer from './components/Footer.vue';
import Kontak from './components/Kontak.vue';
import Skill from './components/Skill.vue';
import History from './components/History.vue';
import 'flowbite/dist/flowbite'

export default {
  components : {
    Navbar,
    Header,
    Hobi,
    Galery,
    Footer,
    Kontak,
    Skill,
    History
  }
}
</script>