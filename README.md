
# Davit Datunasvili

<!-- სორსები -->

<link rel="preconnect" href="https://fonts.googleapis.com" />
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
<link
    href="https://fonts.googleapis.com/css2?family=Barlow+Condensed:ital,wght@0,300;0,500;0,700;1,200;1,300;1,500&display=swap"
    rel="stylesheet" />


<!-- სტილი -->
<style>
    .skin *{
    box-sizing: border-box;
    margin:0;
    padding:0;
    font-family: 'Barlow Condensed', sans-serif;
    font-weight: 300;
}
.skin{
    border-radius: 5px;
    background:url("https://dm0qx8t0i9gc9.cloudfront.net/thumbnails/video/GTYSdDW/videoblocks-abstract-polygon-blue-pink-background_b78neb3og_thumbnail-1080_01.png") 
    no-repeat;
    background-size: cover;
    width: 600px;
    height: 250px;
    overflow: hidden !important;

    margin: auto;
    margin-top:100px;
}
.profile {
    border-radius: 20px;
    margin:20px;
    padding: 20px !important;
    width: 200px;
    display: inline-flex !important;
    flex-direction: column;
    justify-content: center !important;
    align-items: center !important;

    background-color: rgba(255, 252, 252, 0.349);
    backdrop-filter: blur(1px);
    height: 200px;
    box-shadow: 1px 1px 10px  rgba(255, 255, 255, 0.692);
}
.profile img{
    border-radius: 50%;
    width: 100px;
    margin-bottom: 5px;
    width: 100px;
}
.profile p{
    font-size: 23px;
    font-style: italic;
    font-weight: 200;
    border-bottom: 1px solid rgba(255, 255, 255, 0.692);
}
.profile  a, .profile i{
    cursor: pointer;
    margin-top: 5px;
    font-size: 27px;
    color: black;
    float: left;
    margin-left: 4px;
    line-height: 25px;
}
.profile i:hover{
    color:rgba(255, 255, 255, 0.459);
}

/* projects */
.projects{
    display: grid;
    grid-template-columns: 1fr 1fr;
    border-radius: 20px;
    margin:20px;
    padding: 20px !important;
    width: 320px;
    grid-template-rows: 30px;
    float: right;
    background-color: rgba(233, 233, 233, 0.548);
    backdrop-filter: blur(1px);
    height: 200px;
    box-shadow: 1px 1px 10px  rgba(255, 255, 255, 0.692);
    align-items: center;
}

.post{
    margin-bottom: 5px;
    height: 30px; 
}

.post a {
    margin-left: 10px;
    text-decoration: none;
    color: #2d083b;

}

.post a:hover {
    color:#8b25b0 ;
    text-shadow: 0 0 20px #fff, 0 0 30px #b83be6, 0 0 40px #b83be6, 0 0 50px #b83be6, 0 0 60px #b83be6, 0 0 70px #b83be6, 0 0 80px #b83be6;

}
.post img{
    width: 18px;

    background-color: #2d083b;
    border: 2px solid #2d083b;
    border-radius: 50%;
}
.post span{
    vertical-align: top;
}




/* stats */
.stat_1, .stat_2{
    height: 40px;
    width: 100%;
    background: pink;
    bottom: 0 !important;
    padding-top: 10px;
    padding-bottom: 10px;
    margin-top: 20px;
    display: flex;
    align-items: center !important;
    width: 100px;
}
.stat_1{
    border-top-left-radius: 40px;
    border-bottom-left-radius: 40px;
    justify-content: center;
    padding-left:10px ;
    margin-left: 40px !important;
}

.stat_2{
    
    border-top-right-radius: 40px;
    border-bottom-right-radius: 40px;
    justify-content: center;
    padding-right:10px ;
    margin-right: -38px !important;
    
}
.stat_1 img{
    margin: 0 auto;
    width: 30px; 
    padding: 4px;
}
.stat_2 img{
    margin: 0 auto;
    width: 30px; 
    padding: 4px;
}
.stat_1 a:hover, .stat_2 a:hover{
    box-sizing:border-box;
    border-bottom:2px #b83be6 solid;
    
}
</style>

<script src="https://kit.fontawesome.com/f24d87d665.js" crossorigin="anonymous"></script>
<!-- კოდი -->
<div class="skin">
    <!-- ავატარი -->
    <div class="profile">
        <img src="https://avatars.githubusercontent.com/u/71693187?v=4" alt="" />
        <p class="nickname">David Datunashvili</p>

        <div class="social">
            <a href="https://github.com/ddatunashvili" target="_self">
                <i class="fa-brands fa-github-alt"></i>
            </a>
            <a href="https://www.linkedin.com/in/ddatunashvili/">
                <i class="fa-brands fa-linkedin"></i>
            </a>
            <a href="https://www.facebook.com/ddatunashvilii">
                <i class="fa-brands fa-facebook"></i>
            </a>
            <a href="https://www.instagram.com/ddatunashvilii">
                <i class="fa-brands fa-instagram"></i>
            </a>
        </div>
    </div>

    <!-- პროექტები -->
    <div class="projects">
        <div class="post">
            <a href="https://drive.google.com/file/d/1KUTOJ-okIL-tlKtIYPNRK_DAjTriMq7_/view?usp=sharing"
                target="_blank">
                <i class="fa-sharp fa-solid fa-file-pdf"></i>
                Open My resume</a>
        </div>
        <div class="post">
            <a style="display: flex ;align-items: center;"
                href="https://drive.google.com/file/d/1QgMQYhezgUkoDuAD1rvp9zRbKnUyLQh3/view?usp=sharing"
                target="_blank">

                <img class="unilab" crossorigin="anonymous"
                    src="https://media-private.canva.com/begSo/MAFLZebegSo/1/t.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIAJWF6QO3UH4PAAJ6Q%2F20220905%2Fus-east-1%2Fs3%2Faws4_request&amp;X-Amz-Date=20220905T155533Z&amp;X-Amz-Expires=34167&amp;X-Amz-Signature=2d38c65e67ea5272d141e6f815ad0fef6016213f3b75a10c8466b2a9f895a70e&amp;X-Amz-SignedHeaders=host&amp;response-expires=Tue%2C%2006%20Sep%202022%2001%3A25%3A00%20GMT">
                <span style="margin-left: 4px;">
                    UniLab - Python
                </span>
            </a>
        </div>
        <!-- პროექტები -->
        <div class="post">
            <a href="https://github.com/ddatunashvili/football_stats.py" target="_blank">
                <i class="fa-solid fa-chart-line"></i>
                Simple football stats</a>
        </div>


        <div class="post">
            <a href="https://github.com/ddatunashvili/sales_agent.py" target="_blank">
                <i class="fa-solid fa-database"></i>
                Mymarket Scraping</a>
        </div>

        <div class="post">
            <a href="https://github.com/ddatunashvili/jima_bot.py" target="_blank">
                <i class="fa-solid fa-user-tie"></i>
                Jima
                Discord Bot</a>
        </div>

        <div class="post">
            <a href="https://github.com/ddatunashvili/book_checker.py" target="_blank">
                <i class="fa-solid fa-book"></i>
                Book Analizer</a>
        </div>

        <div class="post">
            <a href="https://github.com/ddatunashvili/Gojo_satori" target="_blank"><img
                    style="width: 20px;margin-left: -3px;" src="https://img.icons8.com/doodle/344/satoru-gojo.png"
                    alt="">
                <span>Anime Generator</span>
            </a>
        </div>
        <div class="post">
            <a href="https://github.com/ddatunashvili/Auto_Paraphraze" target="_blank">
                <i class="fa-solid fa-note-sticky"></i>
                </i>
                Auto Note Maker</a>
        </div>

        <!-- სტატისტიკა -->
        <div class="stat_1">
            <a href="https://flask.palletsprojects.com/en/2.2.x/">
                <img src="https://cdn.iconscout.com/icon/free/png-256/flask-51-285137.png" alt="">
            </a>
            <a href="https://pandas.pydata.org/">
                <img src="https://cdn-icons-png.flaticon.com/512/48/48674.png" alt="">
            </a>
            <a href="https://numpy.org/">
                <img src="https://cdn-icons-png.flaticon.com/512/3430/3430812.png" alt="">
            </a>

        </div>
        <div class="stat_2">
            <a href="https://seaborn.pydata.org/">
                <img src="https://user-images.githubusercontent.com/315810/92159303-30d41100-edfb-11ea-8107-1c5352202571.png"
                    alt="">
            </a>
            <a href="https://selenium-python.readthedocs.io/">
                <img style="border-radius: 50%;padding: 0;"
                    src="https://pbs.twimg.com/profile_images/986990489214902272/vt2slFtJ_400x400.jpg" alt="">
            </a>
            <a href="https://beautiful-soup-4.readthedocs.io/en/latest/">
                <img src="https://cdn-icons-png.flaticon.com/512/2388/2388080.png" alt="">
            </a>
        </div>
    </div>
    </body>

    </html>
</div>

## Web Designer and  Python Developer

My name is Davit Datunsahvili I'm a Front End Developer based in Georgia ☀️. 
I describe myself as a passionate developer who loves coding, open source, and the web platform ❤️.

Aside from my job, I like to create and contribute to open source projects. That helps me to learn a ton of new stuff, 
grow as a developer and support other open source projects. Also I enjoy making programming videos on Youtube.

In my free time you can find me at billiards club 🎱



## Skills: 
* 🐍 Python 
    *  flask
    *  Pandas
    *  Numpy
    *  Seaborn
    *  Matplotlib
    *  Selenium
    *  beautifulsoup
    
* 🖼️ Wordpress
    * Elementor
    * wp-bakery
    * Contact Form 7
    * Jetpack
    * Google Analytics
    * UpdraftPlus
    * SEMRush
    * LiveChat
    * WP Mail SMTP
    
* 💻 HTML , CSS , JS , jquery
* 🗃️ Git
* 🎨 Photoshop
* 🖌️ Inkscape   
* 🌈 Figma
* 🖖 Canva   



    

        
## Work:
- 🔭 I’m currently working as a Front  end developer at Faroutsolutions
- 🌱 I’m currently learning react js framework 


