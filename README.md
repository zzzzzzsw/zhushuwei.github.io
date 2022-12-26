<!DOCTYPE html>
<html lang="zxx">
<head>
    <title>Home</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta charset="utf-8" />
    <meta name="keywords" content="" />
    <script>
        addEventListener("load", function () {
            setTimeout(hideURLbar, 0);
        }, false);

        function hideURLbar() {
            window.scrollTo(0, 1);
        }
    </script>
    <!-- Custom Theme files -->
    <link href="css/bootstrap.css" type="text/css" rel="stylesheet" media="all">
    <link href="css/style.css" type="text/css" rel="stylesheet" media="all">
    <!-- font-awesome icons -->
    <link href="css/fontawesome-all.min.css" rel="stylesheet">
    <!-- //Custom Theme files -->
    <!-- online-fonts -->
    <link href="http://fonts.googleapis.com/css?family=Source+Sans+Pro:200,300,400,600,700,900" rel="stylesheet">
    <!-- //online-fonts -->
</head>
<body>
    <div class="sidenav">
		<div class="side_top">
			<img src="images/t3.jpg" alt="news image" class="img-fluid navimg">
			<h1>不以物喜<br>不以己悲</h1>
		</div>
		<!-- header -->
		<header>
			<div class="container-fluid px-lg-5 ">
				<nav class="mnu mx-auto">
                    <label for="drop" class="toggle">Menu</label>
                    <input type="checkbox" id="drop">
						<ul class="menu">
							<li class="active"><a href="index.html">Home</a></li>
							 <li class="mt-sm-3"><a href="#about" class="scroll">About</a></li>
							 <li class="mt-sm-3"><a href="#gallery" class="scroll">Opus</a></li>
							<li class="mt-sm-3"><a href="#services" class="scroll">University</a></li>
							<li class="mt-sm-3"><a href="#news" class="scroll">plan</a></li>
                            <li class="mt-sm-3"><a href="#contact" class="scroll">Contact</a></li>
                        </ul>
				</nav>
			</div>
		</header>
    </div>
    <div class="main" id="about">
        <div class="banner-text-w3ls">
            <div class="container">
                <div class="mx-auto text-left">
                    <h2>朱姝威的个人主页
					<br>Welcome to my profile！</h2>
					<p class="banp mt-5">你们好呀！我是一名来自华东交通大学经济统计学专业的大三的学生。我喜欢旅游，听音乐，也爱好拍照记录生活，让我感觉最幸福的事是能够按照自己的节奏安排自己的生活。欢迎来到我的个人主页，了解我的生活和碎碎念~</p>
					<a class="btn btn-primary mt-lg-5 mt-3 agile-link-bnr" href="#services" role="button">Learn More</a>
                </div>
            </div>
        </div>
		 <!-- Gallery -->
    <section class="gallery" id="gallery">
        <div class="container py-lg-5">
           <h3 class="w3_head mb-5">我的镜头</h3>
	   		<p>点击图片看看它的故事</p>
			 <div class="row news-grids mt-lg-5 mt-4 text-center">
                <div class="col-md-6 gal-img">
                    <a href="#gal1"><img src="images/g2.jpg" alt="news image" class="img-fluid"></a>
                </div>
                <div class="col-md-6 proj-1 gal-img">
                    <a href="#gal2"><img src="images/g3.jpg" alt="news image" class="img-fluid"></a>
                </div>
                <div class="col-md-6 mt-5 gal-img">
                    <a href="#gal3"><img src="images/g4.jpg" alt="news image" class="img-fluid"></a>
                </div>
                <div class="col-md-6 mt-5 gal-img">
                    <a href="#gal4"><img src="images/g5.jpg" alt="news image" class="img-fluid"></a>
                </div>
                <div class="col-md-6 mt-5 gal-img">
                    <a href="#gal5"><img src="images/g6.jpg" alt="news image" class="img-fluid"></a>
                </div>
                <div class="col-md-6 mt-5 gal-img">
                    <a href="#gal6"><img src="images/g7.jpg" alt="news image" class="img-fluid"></a>
                </div>
            </div>
        </div>
        <!-- popup-->
        <div id="gal1" class="pop-overlay animate">
            <div class="popup">
                <img src="images/g2.jpg" alt="Popup Image" class="img-fluid" />
                <p class="mt-4">寝室楼下的绝美晚霞~</p>
                <a class="close" href="#gallery">&times;</a>
            </div>
        </div>
        <!-- //popup -->

        <!-- popup-->
        <div id="gal2" class="pop-overlay animate">
            <div class="popup">
                <img src="images/g3.jpg" alt="Popup Image" class="img-fluid" />
                <p class="mt-4">和妈妈一起看火烧云</p>
                <a class="close" href="#gallery">&times;</a>
            </div>
        </div>
        <!-- //popup -->
        <!-- popup-->
        <div id="gal3" class="pop-overlay animate">
            <div class="popup">
                <img src="images/g4.jpg" alt="Popup Image" class="img-fluid" />
                <p class="mt-4">2022年没能回家看的中秋的月亮</p>
                <a class="close" href="#gallery">&times;</a>
            </div>
        </div>
        <!-- //popup3 -->
        <!-- popup-->
        <div id="gal4" class="pop-overlay animate">
            <div class="popup">
                <img src="images/g5.jpg" alt="Popup Image" class="img-fluid" />
                <p class="mt-4">雨过天晴，很幸运能够看到双彩虹</p>
                <a class="close" href="#gallery">&times;</a>
            </div>
        </div>
        <!-- //popup -->
        <!-- popup-->
        <div id="gal5" class="pop-overlay animate">
            <div class="popup">
                <img src="images/g6.jpg" alt="Popup Image" class="img-fluid" />
                <p class="mt-4">和好朋友去聚餐啦</p>
                <a class="close" href="#gallery">&times;</a>
            </div>
        </div>
        <!-- //popup -->
        <!-- popup-->
        <div id="gal6" class="pop-overlay animate">
            <div class="popup">
                <img src="images/g7.jpg" alt="Popup Image" class="img-fluid" />
                <p class="mt-4">和好朋友的探店</p>
                <a class="close" href="#gallery">&times;</a>
            </div>
        </div>
        <!-- //popup -->
    </section>
<!-- services -->
			<section class="slide-wrapper" id="services">
                    <div class="services">
					<h3 class="w3_head mb-5">My University</h3>
					<div class="row service_w3top mt-5">
                                <div class="col-lg-6">
                                    <div class="d-flex services-box">
                                        <div class="icon">
                                            <span class="fa fa-pencil"></span>
                                        </div>
                                        <!-- .Icon ends here -->
                                        <div class="service-content">
                                            <h4>Inagittis Lacg</h4>
                                            <p>
                                                Quisque sagittis lacus eu lorem sodalesd vulputate velitdipisc inagittis lacg enean adipiscing.
                                            </p>
                                        </div>
                                        <!-- .Service-content ends here -->
                                    </div>
                                    <!-- .Services-box ends here -->

                                    <div class="d-flex services-box">
                                        <div class="icon">
                                            <span class="fa fa-rocket"></span>
                                        </div>
                                        <!-- .Icon ends here -->
                                        <div class="service-content">
                                            <h4>Velitdipisc Inagittis</h4>
                                            <p>
                                                Quisque sagittis lacus eu lorem sodalesd vulputate velitdipisc inagittis lacg enean adipiscing.
                                            </p>
                                        </div>
                                        <!-- .Service-content ends here -->
                                    </div>
                                    <!-- .Services-box ends here -->
                                </div>
                                <!-- .Col ends here -->
                                <div class="col-lg-6">
                                    <div class="d-flex services-box">
                                        <div class="icon">
                                            <span class="fa fa-laptop"></span>
                                        </div>
                                        <!-- .Icon ends here -->
                                        <div class="service-content">
                                            <h4>Vulputate Velitdipisc</h4>
                                            <p>
                                                Quisque sagittis lacus eu lorem sodalesd vulputate velitdipisc inagittis lacg enean adipiscing.
                                            </p>
                                        </div>
                                        <!-- .Service-content ends here -->
                                    </div>
                                    <!-- .Services-box ends here -->

                                    <div class="d-flex services-box">
                                        <div class="icon">
                                            <span class="fa fa-paint-brush"></span>
                                        </div>
                                        <!-- .Icon ends here -->
                                        <div class="service-content">
                                            <h4>Sagittis Lacus</h4>
                                            <p>
                                                Quisque sagittis lacus eu lorem sodalesd vulputate velitdipisc inagittis lacg enean adipiscing.
                                            </p>
                                        </div>
                                        <!-- .Service-content ends here -->
                                    </div>
                                    <!-- .Services-box ends here -->
                                </div>
                                <!-- .Col ends here -->
                            </div>
                            <!-- .Row ends here -->
                        <!-- .Container ends here -->
                    </div>
                    <!-- .Services ends here -->
                </section>
			<!-- //services -->

		<!-- news -->
       <div class="news" id="news">
		<div class="text-left">
			<h3 class="w3_head mb-5">Recent News</h3>
		</div>
			<div class="row news-grids">
				<div class="col-lg-6 news-grids-left">
					<div class="news_top">
						<img src="images/g1.jpg" alt="news image" class="img-fluid">
						<h4>Nulla pellentesque</h4>
						<p class="newsp">Accumsan orci faucibus id eu lorem semper. Eu ac iaculis </p>
					</div>
				</div>
				<div class="col-lg-6 news-grids-middle">
					<div class="news_top">
						<img src="images/g8.jpg" alt="news image" class="img-fluid">
						<h4>Nulla pellentesque</h4>
						<p class="newsp">Accumsan orci faucibus id eu lorem semper. Eu ac iaculis </p>
					</div>
				</div>
				<div class="col-lg-6 news-grids-right">
					<div class="news_top">
						<img src="images/g9.jpg" alt="news image" class="img-fluid">
						<h4>Nulla pellentesque</h4>
						<p class="newsp">Accumsan orci faucibus id eu lorem semper. Eu ac iaculis </p>
					</div>
				</div>
				<div class="col-lg-6 news-grids-right">
					<div class="news_top">
						<img src="images/g10.jpg" alt="news image" class="img-fluid">
						<h4>Nulla pellentesque</h4>
						<p class="newsp">Accumsan orci faucibus id eu lorem semper. Eu ac iaculis </p>
					</div>
				</div>
				<div class="col-lg-6 news-grids-right">
					<div class="news_top">
						<img src="images/g11.jpg" alt="news image" class="img-fluid">
						<h4>Nulla pellentesque</h4>
						<p class="newsp">Accumsan orci faucibus id eu lorem semper. Eu ac iaculis </p>
					</div>
				</div>
				<div class="col-lg-6 news-grids-right">
					<div class="news_top">
						<img src="images/g12.jpg" alt="news image" class="img-fluid">
						<h4>Nulla pellentesque</h4>
						<p class="newsp">Accumsan orci faucibus id eu lorem semper. Eu ac iaculis </p>
					</div>
				</div>
			</div>
			<a class="btn btn-primary mt-lg-5 mt-3 agile-link-bnr" href="#about" role="button">Learn More</a>			
		</div>
<!-- //news -->
<!-- contact -->
	 <section class="wedo" id="contact">
			<h3 class="w3_head mb-5">Get In Touch </h3>
		   <p class="banp mt-5"> Integer porttitor mollisar curae suspendisse mauris posuere accumsan massa posuere lacus convallis tellus interdum. Amet nullam fringilla nibh nulla convallis ut venenatis purus sit arcu sociis.</p>
		   <div class="row mt-4">
			   <div class="col-lg-7 contact_grid_right">
					<form action="#" method="post">
						<div class="row contact_top">
							<div class="col-sm-6">
								<input type="text" name="Name" placeholder="Name" required="">
							</div>
							<div class="col-sm-6">
								<input type="email" name="Email" placeholder="Email" required="">
							</div>
						</div>	
							
							<textarea name="Message" onfocus="this.value = '';" onblur="if (this.value == '') {this.value = 'Message...';}" required="">Message...</textarea>
							<input type="submit" class="btn" value="Send Message">
					</form>
				</div>
				<div class="col-lg-5 contact_grid_left">
				<h3 class="w3_head mb-5">Locate Us </h3>
					<ul class="footer-bottom-list">
							<li>
								<span class="fa fa-map-marker"></span> 3481 Honey Street
								<span> California, USA </span>
								
							</li>
							<li>
								<span class="fa fa-envelope"></span>
								<a href="mailto:name@example.com"> mail@example.com</a>
							</li>
							<li>
								<span class="fa fa-phone"></span> +143 367 436 2049 </li>
							<li>
								<span class="fa fa-fax"></span> +166 367 808 5055 </li>
							<li>
								<span class="fa fa-globe"></span>
								<a href="#"> www.websitename.com</a>
							</li>
					</ul>
				</div>
			</div>
			<div class="cpy-right text-left">
				<p>Copyright &copy; 2019.Company name All rights reserved.<a target="_blank" href="http://sc.chinaz.com/moban/">&#x7F51;&#x9875;&#x6A21;&#x677F;</a>

				</p>
			</div>
	</section>
	 <!-- //contact -->
    </div>

</body>
</html>
