<template>
<main>
    <section class="kepala">
        <div class="container">
            <nav>
                <a>
                    <h1><b class="hover">madj.</b></h1>
                </a>
                <div class="menu">
                    <ul class="menu-links">
                        <li>
                            <a href="#" class="hover">home.</a>
                        </li>
                        <li>
                            <a href="#" class="hover">work.</a>
                        </li>
                        <li>
                            <a href="https://www.instagram.com/maldiid/" target="_blank" class="hover">
                                <font-awesome-icon :icon="['fab','instagram']" />
                            </a>
                        </li>
                        <li>
                            <a href="https://github.com/madj14" target="_blank" class="hover">
                                <font-awesome-icon :icon="['fab','github']" />
                            </a>
                        </li>
                        <li>
                            <a href="https://www.linkedin.com/in/muhammad-aldi-darmawan-9045a31b8/" target="_blank" class="hover">
                                <font-awesome-icon :icon="['fab','linkedin']" />
                            </a>
                        </li>
                    </ul>
                </div>
            </nav>
        </div>
    </section>
    <div class="myimg">
        <img src="@/assets/landscape.png" alt="gambar aldi">
    </div>
    <section class="badan">
        <div class="container">
            <div class="badan-dalem">
                <div class="intro">
                    <div class="intro-txt">
                        <h1><b>Ahoy, it's me Aldi.</b></h1>
                        <h2>2nd year Computer Science Student</h2>
                        <h3>@ Multimedia Nusantara University</h3>
                        <p>
                            A nerd who enjoy playing games and loves to eat. But also i enjoyed making a project for myself.<br/> I suggest not to explore the work i've doing because it's only few of them.
                        </p>
                    </div>
                    <div class="intro-btn">
                        <a href="#" class="btn btn-outline">Know more</a>
                    </div>
                </div>
            </div>
        </div>
    </section>
</main>
</template>

<script>
export default {
    name: 'home',
}
</script>

<style scoped>
h1 .hover{
    font-family: 'Dancing script';
    font-size: 30px;
}
.kepala{
    margin-top: 32px;
}
nav{
    display: flex;
    justify-content: space-between;
    padding: 40px 18px;
    align-items: center;
}
nav a{
    text-decoration: none;
    transition: all .2s ease;
}
nav .menu{
    display: flex;
    justify-content: space-between;
    vertical-align: middle;
    align-items: center;
}
nav .menu ul{
    padding: 0;
    font-size: 0;
    display: flex;
    justify-content: center;
}
ul{
    list-style: none;
}
nav .menu .menu-links li{
    line-height: normal;
    margin: 0 22px;
}
nav .menu ul>li{
    font-size: 20px;
    display: list-item;
}
.intro{
    width: 55%;
    position: relative;
    padding-bottom: 100px;
    display: block;
}
.intro-txt h1{
    font-weight: 800;
    font-size: 50px;
    margin-bottom: 20px;
    margin-top: 100px;
}
.intro-txt h2{
    margin-top: 10px;
    margin-bottom: 18px;
}
.intro-btn{
    display: flex;
    margin-top: 50px;
}
.btn{
    display: inline-block;
    padding: 16px 24px;
    letter-spacing: 2px;
    text-transform: uppercase;
    border: 1px solid black;
    box-shadow: 0 24px 48px rgba(0, 0, 0, 0.2);
    margin-right: 24px;
    background: #ffffff;
    transition: 1s;
}
.btn:hover{
    background-color: #222831;
    transition: 1s;
    color: #eeeeee;
}
a{
    text-decoration: none;
    transition: all .2 ease;
}.intro{
    width: 55%;
    position: relative;
    padding-bottom: 100px;
    display: block;
    font-family: 'Roboto Mono';
}
.intro-txt h1{
    font-weight: 800;
    font-size: 50px;
    margin-bottom: 20px;
    margin-top: 100px;
}
.intro-txt h2{
    margin-top: 10px;
    margin-bottom: 18px;
}
.intro-btn{
    display: flex;
    margin-top: 50px;
}
.btn{
    display: inline-block;
    padding: 16px 24px;
    letter-spacing: 2px;
    text-transform: uppercase;
    border: 1px solid black;
    box-shadow: 0 24px 48px rgba(0, 0, 0, 0.2);
    margin-right: 24px;
    background: #ffffff;
    transition: 1s;
}
.btn:hover{
    background-color: #222831;
    transition: 1s;
    color: #eeeeee;
}
a{
    text-decoration: none;
    transition: all .2 ease;
}
</style>