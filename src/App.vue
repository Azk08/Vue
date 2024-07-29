<script setup>
import Home from './components/HomePage.vue';
import Navigation from './components/NavigationBar.vue';
import About from './components/AboutPage.vue';
import Skill from './components/SkillPage.vue';
import Footer from './components/FooterPage.vue';
</script>

<template>
    <nav className="">
        <Navigation/>
    </nav>
    <header id="Home" >
        <Home/>
    </header>
    <main className="">
        <About id="About"/>
        <Skill id="Skill"/>
    </main>
    <footer>
        <Footer/>
    </footer>
</template>

<style scoped>


body{
    background-color: black;
    padding: 0;
    margin: 0;
}


header{
    display: flex;
    flex-wrap: wrap;
    padding: 180px;
    justify-content: center;
     /* background: linear-gradient(  white 50% , #00ff0057 100%);  */
}
nav{
    display: flex;
    flex-wrap: wrap;
    justify-content: space-evenly;
    padding: 10px;
    backdrop-filter: blur(10px);
    align-items: center;
    position: sticky;
    top: 0;
}

.about{
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    padding: 150px;
}
.skill{
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    align-items: center;
    padding: 150px;
}
footer{
    background-color: black;
    color: white;
    padding: 100px;
}
</style>