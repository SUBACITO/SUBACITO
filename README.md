<style>
    body {
    font-family: 'Arial', sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background-color: #f9f9f9;
}

.cv-container {
    max-width: 800px;
    margin: 20px auto;
    background: #fff;
    padding: 20px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    border-radius: 15px;
}
.my-cv{
    display: flex;
}

.header {
    width: 100%;
    text-align: center;
    /* border-bottom: 2px solid #333; */
    padding-bottom: 10px;
    display: flex;
    background: url(https://images.rawpixel.com/image_800/czNmcy1wcml2YXRlL3Jhd3BpeGVsX2ltYWdlcy93ZWJzaXRlX2NvbnRlbnQvbHIvcC00MjYtamFja2Fuc3RleS1ycC1zZXB0MjAxOS0wMTIzLWV5ZS5qcGc.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    border-radius: 15px;
    margin-bottom: 15px;
    box-shadow: rgba(100, 100, 111, 0.2) 0px 7px 29px 0px;
}

.header-content {
    text-align: left;
    margin: 50px auto;
    width: 50%;
    padding: 20px;
}


.img-container{
    width: 250px;
    float: right;
    margin-right: 40px;
}

.header h1 {
    margin: 0;
    font-size: 2em;
    font-weight: bold;
}

.header h2 {
    margin: 5px 0 0;
    font-size: 1.5em;
    color: #555;
    font-weight: normal;
}
.pic-face{
    width: 50%;
}

.pic-face img{
    width: 100%;
    object-fit: cover;
    border-radius: 50%;
    min-height: 250px;
    padding: 20px;
    box-shadow: rgba(100, 100, 111, 0.2) 0px 7px 29px 0px;
}

.sidebar {
    width: 30%;
    padding-right: 20px;
    border-right: 2px solid #d7c124;
}

.main-content {
    width: 70%;
    padding-left: 20px;
}

section {
    margin-bottom: 20px;
}

h3 {
    margin-bottom: 10px;
    color: #333;
    /* border-bottom: 1px solid #333; */
    padding-bottom: 5px;
}

.contact-info p,
.profile-summary p,
.job p,
.education-item p {
    margin: 5px 0;
    line-height: 1.4;
}

.job ul,
.skills ul {
    list-style-type: disc;
    display: flex;
    flex-direction: column;
}

.job ul {
    margin-top: 5px;
}

.skills ul {
    columns: 2;
    -webkit-columns: 2;
    -moz-columns: 2;
}

.clearfix::after {
    content: "";
    display: table;
    clear: both;
}

.company {
    font-style: italic;
    margin-bottom: 5px;
}

.institution {
    font-style: italic;
    margin-bottom: 5px;
}
.job h4{
    background: #f5e4e4;
    padding: 10px;
    border-radius: 10px;
}


@media only screen and (max-width: 650px) {
    .my-cv{
        flex-direction: column;
    }
    .sidebar{
        width: 100%;
        border: none;
    }
    .header{
        flex-direction: column;
    }
    .pic-face{
        display: flex;
        justify-content: center;
        width: 100%;
    }
    .img-container{
        margin: 0;
    }
    
  }
</style>
<body>
    <div class="cv-container">
        <header class="header">
            <div class="header-content">
                <h1>Nguyễn Trần Giang Vỹ</h1>
                <h2>Software Engineer</h2>
            </div>
            <div class="pic-face">
                <div class="img-container">
                    <img src="img/image.png" alt="">
                </div>
            </div>
        </header>
        <div class="my-cv">
            <aside class="sidebar">
                <section class="contact-info">
                    <h3>Contact</h3>
                    <p><strong>📧</strong> subacitodev@gmail.com</p>
                </section>
                <section class="skills">
                    <h3>Skills</h3>
                    <ul>
                        <li>JavaScript</li>
                        <li>Java</li>
                        <li>Python</li>
                        <li>Vue Js</li>
                        <li>C#</li>
                        <li>SQL</li>
                    </ul>
                </section>
                <section class="tools">
                    <h3>Tools</h3>
                    <ul>
                        <li>SQL</li>
                        <li>Unity Engine</li>
                        <li>FUI</li>
                    </ul>
                </section>
                <section class="languages">
                    <h3>Languages</h3>
                    <ul>
                        <li>Vietnamese</li>
                        <li>English</li>
                    </ul>
                </section>
            </aside>
            <main class="main-content">
                <section class="profile-summary">
                    <h3>Presentation</h3>
                    <p>A dedicated and innovative software engineer with over 2 years of experience specializing in Unity game development and web application design. Passionate about leveraging technology's transformative power through continuous learning and creative problem-solving.
</p>
                </section>
                <section class="experience">
                    <h3>Experience</h3>
                    <div class="job">
                        <h4>Front-end web development</h4>
                        <p class="company">ThoMi Technology Solution Company, 2021 - 2022 <a href="https://changhanna.vn/trang-chu.html">https://changhanna.vn/trang-chu.html</a></p>
                        <ul>
                            <li>Developed and maintained various web applications, enhancing their functionality and user experience.
</li>
                            <li>Improved application performance by 20%, contributing to higher user satisfaction and engagement.
</li>
                        </ul>
                    </div>
                    <div class="job">
                        <h4>Game Developer</h4>
                        <p class="company">Farmverse (Blockchain Competition in China), 2021 - 2022</p>
                        <ul>
                            <li>Utilized RPG Maker MV Tool to develop engaging game applications.</li>
                            <li>Focused on maintaining and enhancing existing game features to improve user experience.</li>
                        </ul>
                    </div>
                    <div class="job">
                        <h4>Game Developer</h4>
                        <p class="company">Solo - TheNone, 2024 - Present</p>
                        <ul>
                            <li>Developed a multiplayer game using Unity Engine and Photon Pun.</li>
                            <li>Implemented innovative features to create an immersive gaming experience.</li>
                        </ul>
                    </div>
                </section>
                <section class="education">
                    <h3>Education</h3>
                    <div class="education-item">
                        <h4>Bachelor of Information Technology</h4>
                        <p class="institution">Lac Hong University, 2021 - 2025</p>
                    </div>
                </section>
            </main>
        </div>
    </div>
</body>

</html>
