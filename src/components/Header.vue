<template>
  <!-- <header>
    <div class="page-banner home-banner">
      <div class="container h-100">
        <div class="row align-items-center h-100">
          <div class="col-lg-6 py-3 wow fadeInUp">
            <p
              class="text-green-600 hover:text-green-500 text-2xl lg:text-4xl font-medium lg:font-semibold mb-5 lg:leading-normal leading-snug">
              HI, I'm ANASKHON
              <br />
              Front-End Developer,
              <br />
              Blockchain Engineer
            </p>
            <p
              class="hidden lg:block text-2xl mb-5">
              I like to craft solid and scalable frontend products with great
              user experiences.
            </p>

            

            <router-link
              to="/about"
              name="fade"
              class="btn btn-outline border text-secondary">
              About
            </router-link>
            <a
              href="#"
              class="btn btn-primary btn-split ml-2">
              Resume
              <div class="fab"><span class="mai-play"></span></div>
            </a>
          </div>
          <div class="col-lg-6 wow zoomIn">
            <div
              class="m-3 lg:m-3 p-1 lg:p-5">
              <lottie-player
                src="https://assets2.lottiefiles.com/packages/lf20_gnb0jsok.json"
                background="transparent"
                speed="1"
                style="max-width: 500px; max-height: 500px"
                autoplay></lottie-player>
            </div>
          </div>
        </div>
      </div>
    </div>
  </header> -->

  <!DOCTYPE html>
<html>
<head>
	<link rel="stylesheet" type="text/css" href="style.css" />
	<title>Aliansi Siber Uin Suska Riau</title>
</head>
<body>
	<div class="wrapper">
			<div class="nav">
				<div class="logo">
					logo
				</div>
				<div class="menu">
					<ul>
						<li><a href="#">Home</a></li>
						<li><a href="about.html" _blank>About</a></li>
						<li><a href="#">Contact</a></li>
						<li><a href="#">Forum</a></li>
						<li><a href="#">Hall Of Fame</a></li>
					</ul>
				</div>
				<div class="header">
				<h1>Muhammad Zulfikri</h1>
				<p>Programmer and game developer</p>
			</div>
		</div>
	</div>
</body>
</html>
</template>

<script>
import { directive as motion } from "@vueuse/motion";

export default {};
</script>

<style>
html,body{
	margin: 0;
	padding: 0;
	width: 100%;
}



body{
	background: url("https://images.unsplash.com/photo-1542831371-29b0f74f9713?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=870&q=80");
	height: 100vh;
	width: 100%;
	background-repeat: no-repeat;
	background-position: center;
	background-size: cover;
	display: table;
	background-attachment: fixed;
	font-family: montserrat;
}
.nav{
	position: fixed;
	top: 0;
	left: 0;
	margin: 0;
	padding: 0;
	width: 100%;
	height: 80px;
	border-bottom: 1px solid rgba(255,255,255,0.5)
}
.logo{
	letter-spacing: 1px;
	float:left;
	margin-left: 20px;
	color: #fff;
	line-height: 80px;
	font-size: 22px
	padding 0 6em;
}

.menu{
	float: left;
	line-height: 50px;
	margin: 0 6em;
}

.menu ul{
	list-style: none;
}

.menu ul li{
	display: inline-block;
}

.menu ul li a{
	text-decoration: none;
	color: rgb(255, 255, 255);
	font-size: 16px;
	font-weight: lighter;
	padding: 0 20px;

}

ul li:nth-child(5) a{

	color: #009f8b;
	border: 1px solid #009f8b;
	padding: 20px 20px;
	border-radius: 4px;

}

.header{
	position: absolute;
	top: 500%;
	left: 50%;
	transform: translate(-50%,-50%);
	text-align: center;

}

.header h1{
	color: rgb(216, 226, 216);
	font-size: 40px;
	font-weight: 400px;
	margin-bottom: 8px;
	
}

.header p{
	color: rgb(207, 207, 207);
	font-size: 24px;
	font-weight: lighter;
}
</style>
