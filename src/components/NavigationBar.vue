<template>
    <div className="image">
        <img src="/src/assets/logo.svg" alt="">
    </div>

    <div className="link">
        <a href="#Home" className="">Home</a>
        <a href="#About" className="">About</a>
        <a href="#Skill" className=""> Skill</a>
    </div>

</template>
<style scoped>
a {
    text-decoration: none;
    color: black;
}

a:hover {
    color: gray;
    transition: 1s ease-in-out
}

img {
    width: 8%;
    float: left;
}

.link{
    display: inline-flex;
    flex-wrap: wrap ;
    justify-content: space-evenly;
    width: 50%;
    float: right;
}
.image{
    width: 50%;
}
</style>