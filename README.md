# sannu1
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>portfolio</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorgin>
    <link href="https://fonts.googleleapis.com/css2?family=wght@400;600;700&
    display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
        }

        body {
            background-color: rgb(0, 0, 13);
            color: white;
            font-family: 'poppins', sans-serif;
        }
        nav{
            display: flex;
            justify-content: space-around;
            align-items: center;
            height: 80px;
            background-color: rgb(18,10,62);
            text-decoration: none;
        }
        nav ul{
            display: flex;
            justify-content: center;
        }
        nav ul li{
            list-style: none;
            margin: 0  23px;
        }
        nav ul li a{
            text-decoration: none;
            color: white;
        }
        nav ul li a:hover{
            color: rgb(139, 139, 220);
            font-size: 1.04rem;
        }
        main hr{
            border: 0;
            background:#9c97f1;
            height: 1.2px;
            margin: 50px 84px;
        }
        .left{
            font-size: 1.5rem;
            text-decoration: none;
        }
        .firstsection{
            display: flex;
            justify-content: space-around;
            margin: 80px 0;
            align-items: center;
        }
        .firstsection >div{
            width: 30%;
        }
        .leftsection{
            
            font-size: 3rem;
        }
        .rightsection img{
            width: 80%;
            margin: 50px 0;
        }
        .text-gray{
            color: gray;
        }
        .purple{
            color: rgb(155, 65, 239);
        }
        #element{
            color: rgb(155, 65, 239);
        }
        .secondSection{
            max-width: 80vw;
            margin: auto;
            height: 80vh;
        }
        .secondSection h1{
            font-size: 1.9rem;
        }
        .secondSection .box{
            background: white;
            width: 80vw;
            height: 2px;
            margin: 56px 0;
            display: flex;
        }
        .secondSection .vertical{
            height: 93px;
            width: 1px;
            background-color: white;
            margin: 0 100px;
        }
        .image-top{
            width: 23px;
            position: relative;
            top: -32px;
            left: -9px;
        }
        footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 1rem 0;
    position: absolute;
    width: 100%;
    bottom: 0;
}
.project {
    background: #f4f4f4;
    padding: 1rem;
    margin: 1rem 0;
    border-left: 5px solid #333;
}
        
    </style>

</head>

<body>
    <header>
        <nav>
            <div class="left">Surabhi's portfolio</div>
            <div class="right">
                <ul>
                    <li> <a href="/">Home</a></li>
                    <li> <a href="/">About</a></li>
                    <li> <a href="/">Skills</a></li>
                    <li> <a href="/">Projects</a></li>
                    <li> <a href="/">Resume</a></li>
                    <li> <a href="/">Contact me</a></li>
                </ul>
            </div>
        </nav>
    </header>
    <main>
        <section class="firstsection">
            <div class="leftsection">
                Hi! My name is <span class="purple">Sanu's</span>
                and I'm a passionate
                <span id="element"></span>
            </div>
            <div class="rightsection">
                <img src="sk.png" alt="">
            </div>
        </section>
        <hr>
        <section class="secondSection">
            <span class="text-gray">What i have done so far</span>
            <h1>Work Experience</h1>

            <div class="box">
                <div class="vertical">
                    <img  class="image-top" src="sk.png" alt="" >
                    <div class="vertical-title">
                        HTML Developer
                    </div>
                    <div class="vertical-desc">
                        <h3>Work Experience - Student</h3>
                    </div>
                </div>
                <div class="box">
                    <div class="vertical">
                        <img  class="image-top" src="linked in.jpeg">
                        <div class="vertical-title">
                            HTML Developer
                        </div>
                        <div class="vertical-desc">
                            <h3>linked in - Surabhi Kumari Sahu</h3>
                        </div>
                    </div>
                    <div class="box">
                        <div class="vertical">
                            <img  class="image-top" src="insta.jpeg">
                            <div class="vertical-title">
                                HTML Developer
                            </div>
                            <div class="vertical-desc">
                                <h3>@cutipe_surabhi</h3>
                            </div>
                        </div>
            </div>
        </section>
    </main>
    <section id="projects">
        <h2>Projects</h2>
        <div class="project">
            <h3>Project 1</h3>
            <p>Design Websites</p>
        </div>
        <div class="project">
            <h3>Project 2</h3>
            <p>Create a online website of a cafe</p>
        </div>
        <footer>
        <section id="contact">
            <h2>Contact</h2>
            <p>Feel free to get in touch with me through the following methods:</p>
            <ul>
                <li>Email: <a href="mailto:sanukumarpanda116@gmail.com">sanukumarpanda116@gmail.com</a></li>
                <li>LinkedIn: <a href="https://www.linkedin.com/in/sanu-kumar-b1657925a?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app" target="_blank">LinkedIn Profile</a></li>
            </ul>
        </section>
    </footer>
    <script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>
    <script>
        var typed = new Typed('#element', {
          strings: ['Web Developer', 'Graphics Designer' ,'Web Designer'],
          typeSpeed: 50,
        });
      </script>

</body>

</html>
