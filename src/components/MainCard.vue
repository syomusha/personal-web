<template>
    <div class="main-container">
        <div class="container-one">
            <div class="profile">
                <img src="../assets/pfp1.jpg" alt="">
                <h1>Andrew Syomushkin</h1>
                <p>Third year Computer Science and Business student at Trinity College Dublin</p>
            </div>
            <div class="social-links">
                <div class="link">
                    <a href="https://github.com/syomusha">
                        <img src="../assets/github.png" alt="">
                        <h2>Github</h2>
                    </a>
                </div>

                <div class="link">
                    <a href="https://www.linkedin.com/in/andrew-syomushkin-395620249/">
                       <img src="../assets/linkedin.png" alt="">
                       <h2>LinkedIn</h2>
                    </a>
                </div>
                <div class="link">
                    <a href="https://www.instagram.com/syomusha/">
                        <img src="../assets/instagram.png" alt="">
                        <h2>Instagram</h2>
                    </a>
                </div>
            </div>
        </div>
        <div class="container-two">
            <div class="about-me">
                <h1>About me</h1>
                <p>I enjoy working on myself. That includes all aspects: physical, mental and everything in between. </p>
                <p>I wish to work in tech. Therefore, I need to get my social credit score up, and prove that I'm a good worker.</p>
                <p>To prove that I'm a great worker, I need to get some projects under my belt.</p>
                <p>I will spend this summer working on projects, which will help in my future.</p>
            </div>
            <div class="technologies">
                <h1>Technologies Studied</h1>
                <div class="logos">
                    <img src="../assets/mongo.png" alt="">
                    <img src="../assets/ExpressJS.png" alt="">
                    <img src="../assets/VueJS.svg" alt="">
                    <img src="../assets/Nodejs.png" alt="">

                </div>
                <div class="button-container">
                    <div class="projects-button">
                        <a href="">My project</a>
                    </div>
                    <div class="projects-button">
                        <a href="">My CV</a>
                    </div>
                </div>
            </div>
        </div>

    </div>
</template>

<script>

</script>

<style scoped>
    img{
        height:20px;
    }
    .main-container{
        display: flex;
        flex-direction: row;
        background-color: #A0D4FF;
        border-radius:25px;
    }
    .container-one {
        background-color: #1292EE;
        padding:2.5%;
        width:40%;
        border-radius:25px;
    }

    .profile img{
        height: 20rem;
        border-radius:50%;
    }

    .link a{
        text-decoration:none;
        color: #000000;
        font-size:12px;
    }

    .link img{
        height:4rem;
    }
    .container-two {
        width:60%;
        margin:2.5%;
    }

    .about-me{
        justify-content: center;
        align-items: center;
    }

    .logos img{
        height:5rem;
        padding:5px ;
        
    }

    .button-container {
        margin-top: 5%;
        display:flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
    }

    .button-container{
        margin-top: 5%;
        display:flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
    }
    .projects-button {
        background-color: #005CA4;
        margin:5px ;
        padding:5px;
        border-radius:20px;
    }
    .projects-button a{
        text-decoration: none;
        color: #fff;
    }


</style>