<template>
    <main>
        <section class="project">
            <h1><b>Project</b></h1>
            <h2>It may not the best but im trying and learn to make it better.</h2>
            <div class="project-list">
                <a href="http://dicoding-maldid.surge.sh/" target="_blank" class="hover">
                    <div class="card">
                        <img src="@/assets/dicoding.png" alt="Dicoding Academy">
                        <h1>Dicoding Academy Project</h1>
                        <p>Here's my project for my certification at Dicoding class "Belajar Dasar Pemrograman Web"</p>
                    </div>
                </a>
                <a href="https://ptilabmaldid.surge.sh/index.html" target="_blank" class="hover">
                    <div class="card">
                        <img src="@/assets/umn.png" alt="Multimedia Nusantara University">
                        <h1>Mid-Test Project</h1>
                        <p>This is my mid-test project for my Introduction to Internet class</p>
                    </div>
                </a>
            </div>
        </section>
        <section class="kaki">
            <div class="container">
                <div class="credit">
                    <h4>© Maldid 2020.</h4>
                </div>
            </div>
        </section>
    </main>
</template>

<script>
export default {
    name: 'work'
}
</script>

<style scoped>
a{
    text-decoration: none;
    transition: all .2s ease;
}
.project{
    margin: 0 auto;
}
.project h1{
    font-weight: 800;
    font-size: 50px;
    margin-bottom: 20px;
    margin-top: 100px;
}
.project-list {
    display: flex;
    justify-content: space-between;
    vertical-align: middle;
    align-items: center;
}
.project-list h1{
    font-size: 30px;
}
.card{
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
    max-width: 300px;
    margin: auto;
    text-align: center;
    padding: 10px;
}
.credit{
    padding: 50px;
    display: flex;
    justify-content: center;
}
</style>