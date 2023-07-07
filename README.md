# micro-project
HTML file
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="proj1.css" />
    <style>
        @import url("https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap");
    </style>
    <title>Document</title>
</head>

<body>
    <form action="#">
        <div class="upper">
            <div class="upperleft">
                <div class="heading">
                    <h1>An inspiring design delivered to your inbox every morning</h1>
                </div>
                <div class="para">
                    Our team scouts the internet for the best designs, illustrations and art and delivers a truly inspiring one every day to your inbox
                </div>
                <div class="head">
                    <h4>Show me how it looks</h4>
                </div>

                <div class="mail">
                    <input type="email" placeholder="Your e-mail address" />
                </div>
                <div class="btn"><button>Register Now</button></div>
                <div class="spam">Free - No Spam - No Data Sharing</div>

            </div>
            <div class="upperright">
                <img src="./dweep io 1.png" alt="">
            </div>
        </div>
        <div class="lower">
            <div class="lowerleft">
                <div class="word">
                    <p> Prompt Generator</p>
                    <p>Dweep Daily</p>
                    <p>All Contributors</p>
                    <p> Your data on Dweep.io</p>
                    <p> Contribute to Dweep</p>
                </div>
            </div>
            <div class="lowerright">
                <div class="below">
                    <div class="first">
                        <p> Dweep.io</p>
                        <p>Made with love in India</p>
                        <div class="img">
                            <img src="./LinkedinLogo.png" alt="">
                            <img src="./InstagramLogo.png" alt="">
                        </div>
                    </div>
                    <div class="second">
                        <p>hello@dweep.io</p>
                    </div>

                </div>
            </div>
        </div>

    </form>
</body>

</html>

css file
* {
    margin: 0px;
    padding: 0px;
    font-family: Inter;
}

body {}

.upperleft {
    width: 50vh;
}

.heading {
    position: relative;
    top: 100px;
    left: 100px;
}

h1 {
    font-family: "Inter", sans-serif;
    font-weight: bolder;
    font-size: 30px;
    line-height: 44px;
}


/* .upperright {
    position: relative;
    left: 1200px;
}

img {
    height: 500px;
} */

.para {
    position: relative;
    top: 130px;
    left: 100px;
    font-family: Inter;
    font-size: 20px;
    font-weight: 500;
    line-height: 32px;
    letter-spacing: 0em;
    text-align: left;
}

.head {
    position: relative;
    top: 150px;
    left: 100px;
}

h4 {
    font-family: Inter;
    font-size: 20px;
    font-weight: 800;
    line-height: 32px;
    letter-spacing: 0em;
    text-align: left;
}

input[type="email"] {
    height: 44px;
    width: 300px;
    border-radius: 8px;
    border: 4px;
    border: 4px solid rgba(0, 0, 0, 1);
    font-size: 20px;
    padding: 8px;
}

.mail {
    position: relative;
    top: 211px;
    left: 100px;
}

.btn {
    position: relative;
    top: 144px;
    left: 470px;
}

button {
    /* width: 200px;
    height: 44px;
    margin-top: 40px;
    border-radius: 8px;
    border: 4px;
    border: 4px solid rgba(0, 0, 0, 1);
    font-size: 20px;
    padding: 8px; */
    width: 216px;
    height: 66px;
    top: 411px;
    border-radius: 8px;
    border: 4px solid rgba(40, 40, 40, 1);
    background: rgba(40, 40, 40, 1);
    color: rgba(255, 255, 255, 1);
    font-family: Inter;
    font-size: 20px;
    font-weight: 700;
    line-height: 24px;
    letter-spacing: 0em;
    text-align: center;
}

.spam {
    position: relative;
    margin-top: 180px;
    /* margin-left: 140px; */
    text-align: center;
    font-family: Inter;
    font-size: 16px;
    font-weight: 500;
    color: rgba(255, 255, 255, 1);
}

.upperright {
    position: relative;
    left: 650px;
    /* margin-top: -512px; */
}

.upper {
    display: flex;
    background-color: #ffcd9e;
}

.lower {
    width: 1920px;
    height: 390px;
    top: 592px;
    background: rgba(40, 40, 40, 1);
}

.lowerleft {
    width: 300px;
    height: 350px;
    margin-left: 140px;
    text-align: center;
    border: solid rgba(40, 40, 40, 1);
}

.lowerleft p {
    margin-top: 5px;
    font-size: 20px;
    font-weight: 400;
    line-height: 32px;
    letter-spacing: 0em;
    text-align: left;
    color: rgba(255, 255, 255, 1);
}

.word {
    margin-top: 80px;
}

.lowerright {
    margin-left: 1360px;
    margin-top: -280px;
    color: rgba(255, 255, 255, 1);
    width: 520px;
    /* border: 1px solid white; */
}

.first p {
    margin-top: 15px;
}

.below {
    /* border: 1px solid white; */
    font-family: Inter;
    font-size: 20px;
    font-weight: 400;
    line-height: 32px;
    letter-spacing: 0em;
    text-align: right;
    /* margin-right: 800px; */
    width: 220px;
}

.second {
    margin-top: 28px;
}
