# octanet_task1
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>Landing Page</title>
    <link rel="stylesheet" href="landing_page.css">
    <script src="https://kit.fontawesome.com/cc01bf3621.js" crossorigin="anonymous"></script>
    <link href="https://cdn.jsdelivr.net/npm/remixicon@4.2.0/fonts/remixicon.css" rel="stylesheet"/>
    <style>
        * {
    padding:0px;
    margin:0px;
}
body {
    font-family: 'Roboto','sans-serif';
}
.main_one {
    background-color:whitesmoke;
    min-height: 40rem;
    border-radius:20px;
    position:relative;
}
.img1 {
    width:160px;
    height:90px;
    display:block;
    margin-left:auto;
    margin-right:auto;
}
.links {
    padding-top:1rem;

}
.links a,.links i {
    padding-left:17px;
}
 .links i {
  padding-right:1rem;
 }
.right a{
    padding-right: 3rem;
}
.left {
    float:left;
}
.right{
    float:right;
}
.links a {
    text-decoration:none;
    color:black;
}
.links a:hover {
    text-decoration:underline;
    color:blue;
}

.img2 {
    position:absolute;
    bottom:0%;
    left:21%;
    height:30rem;
}
.txt1 {
    position:absolute;
    top:34%;
    left:60%;
    font-weight: 400;
    font-size:20px;
}

.txt1 i {
    display:inline;
}
.txt2 {
    position:absolute;
    top:45%;
    left:60%;
    font-weight:900;
    font-size: 40px;
}
.buttons {
    position:absolute;
    left:60%;
    top:70%;
}
.buttons button {
   padding:5px;
   width:90px;
   font-weight: 400;
   font-size:15px;
   margin-left:8px;
}

.buttons .one {
    background-color:#000;
    color:white;
    
}
.buttons .two {
    background-color:#fff;
    width:105px;
}

button:hover {
    cursor:pointer;
}
.fa-sharp {
    float:right;
}
.fa-sharp  {
    padding-left:17px;
    padding-top:13px;
}

.more {
    margin-top:20px;
}

.more h2 {
    font-size:40px;
    margin-bottom:20px;
}
.more img {
    width:27%;
    float:right;
}
.more p {
    font-size:26px;
    line-height:29px;
    word-spacing:11px;
}

.follows {
    clear:both;
    background-image:url('https://static.vecteezy.com/system/resources/previews/000/518/751/original/vector-black-triangular-abstract-texture-low-light-background.jpg');
    background-size: cover;
    margin:0px;
    padding:0px;
    margin-top:20px;
}

.follows h2{
    color:#fff;
    text-align:center;
    font-size:46px;
}

.icons {
    height:150px;
    width:150px;
    background-color: #9c9c9d;
    margin:10px;
    padding:20px;
    text-align:center;
    overflow:hidden;
    display:inline-flex;
}
.icons a {
   display:grid;
}

.icons .fa {
    font-size:108px;
    color:#fff;
    padding-left:20%;
}

.x {
    margin-left:21%;
}

@media (max-width:300px) {
    .links a {
        margin:50px;
        padding:50px;
    }
    .links i {
        margin:40px;
        padding:50px;
    }
}
    </style>
</head>

<body>
    <div class="title">
        <img src="https://www.pngarts.com/files/3/Naruto-Shippuden-Logo-PNG-Transparent-Image.png"
            alt="Naruto Shippuden" class="img1">
    </div>
    <div class="main_one">
        <div class="links">
            <div class="left">
                <a href="">nanami.to</a>
            </div>
            <div class="right">
                <a href="">My List</a>
                <a href="">Recently Added</a>
                <a href="">Originals</a>
                <a href="">Films</a>
                <a href="">Homes</a>
                <i class="fa-solid fa-magnifying-glass fa-xl"></i>
                <i class="fa-solid fa-house"></i>
            </div>
        </div>
        <img src="https://i.pinimg.com/originals/d3/e5/3f/d3e53f6151bb84b8d2cdc377aec8ae2e.png" alt="Naruto"
            class="img2">
        <div class="txt1">
                <p>#1 series worldwide</p>
                <i class="fa-solid fa-star"></i>
                <i class="fa-solid fa-star"></i>
                <i class="fa-solid fa-star"></i>
                <i class="fa-solid fa-star"></i>
                <i class="fa-solid fa-star"></i>
                <i class="fa-regular fa-star"></i>
        </div>
        <div class="txt2">
            <h2>NARUTO SHIPPUDEN</h2>
        </div>
        <div class="buttons">
            <button type="submit" class="one"> <i class="fa-solid fa-play"></i> &nbsp; PLAY</button>
            <button type="submit" class="two"><i class="fa-solid fa-check"></i> &nbsp; MY LIST</button>
            <i class="fa-sharp fa-regular fa-heart fa-2xl"></i>
        </div>
    </div>
    <div class="more">
        <h2>NARUTO SHIPPUDEN:</h2>
        <img src="https://th.bing.com/th/id/R.0d1e0201df18616fbceb02800cfdc538?rik=2zhTMopMD49bbg&riu=http%3a%2f%2fimg3.wikia.nocookie.net%2f__cb20131107012205%2ftoonami%2fimages%2f0%2f08%2fShipuden.jpg&ehk=Z%2bSKSDeFbtnE%2fnylHGmp6OzBk515UiRVyRHHAYnqWQ8%3d&risl=&pid=ImgRaw&r=0" alt="">
        <p>Naruto: Shippūden (Naruto Shippūden, literally meaning: Naruto Hurricane Chronicles) is the anime adaptation of Part II of the Naruto 
            manga, set two-and-a-half years after Naruto Uzumaki leaves Konohagakure to train with Jiraiya. The series had 500 episodes, which originally aired in Japan
             on TV Tokyo from 2007 until 2017. Naruto: Shippūden can be legally accessed through sites such as Hulu (for United States users only) and Crunchyroll 
             (for those living outside the US).</p>
        <div class="follows">
             <h2>Follow Us:</h2>
              <div class="icons x">
                 <i class="fa fa-twitter"></i>
              </div>
              <div class="icons">
                 <i class="fa fa-instagram"></i>
              </div>
              <div class="icons">
                 <i class="fa fa-facebook"></i>
              </div>
              <div class="icons">
                 <i class="fa fa-linkedin"></i>
              </div>
        </div>
    </div>
</body>

</html>
