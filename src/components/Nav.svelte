<script type="text/javascript">
	
</script>

<nav uk-sticky>
	<img src="./img/logo.png" alt="Logo">
    <a class="uk-navbar-toggle" uk-navbar-toggle-icon href={"#"} uk-toggle="target: #offcanvas-flip" style="color: white;"></a>
    <div id="offcanvas-flip" uk-offcanvas="flip: true; overlay: true">
	    <div class="uk-offcanvas-bar">
	    	<div class="off-top" style="display: flex; align-items: center;">
		    	<img src="./img/logo.png" alt="Logo" style="width: 5rem;">
		        <h4 style="font-family: 'Aboreto', cursive;">DREAMCATCHER</h4>
	    	</div>
	        <span class="uk-offcanvas-close" uk-icon="icon: close;"></span>
	    		<ul class="uk-list">
				    <li><a href={"#"}>Members<span uk-icon="icon: chevron-right"></span></a></li>
				    <li><a href={"#"}>Albums<span uk-icon="icon: chevron-right"></span></a></li>
				    <li><a href={"#"}>Events<span uk-icon="icon: chevron-right"></span></a></li>  
				    <li><a href={"#"}>News<span uk-icon="icon: chevron-right"></span></a></li>
				    <li><a href={"#"}>Store<span uk-icon="icon: chevron-right"></span></a></li>  


				</ul>
				<div class="off-socials">
					<a href="https://twitter.com/hf_dreamcatcher" target="_blank"><i class="fa-brands fa-twitter"></i></a>
					<a href="https://www.instagram.com/hf_dreamcatcher/" target="_blank"><i class="fa-brands fa-instagram"></i></a>
					<a href="https://www.facebook.com/happyfacedreamcatcher" target="_blank"><i class="fa-brands fa-facebook"></i></a>
					<a href="https://weibo.com/dreamcatcher7" target="_blank"><i class="fa-brands fa-weibo"></i></a>
					<a href="https://www.youtube.com/playlist?list=PLll3b9MjHm8G6R8EGNcvh76rTsUAKYMCS"><i class="fa-brands fa-youtube"></i></a>
					<a href="https://www.tiktok.com/@official_dreamcatcher" target="_blank"><i class="fa-brands fa-tiktok"></i></a>

				</div>
	    </div>
</div>
</nav>

<style type="text/css">
	nav{
		display: flex;
		align-items: center;
		justify-content: space-between;
		height: 90px;
		padding: 10px 10px;
	}
	nav img{
		width: 5rem;
	}
	.uk-offcanvas-bar{background-color: black;}
	.uk-offcanvas-close:hover{
		color:#f2c763; 
	}
	
	.uk-list{
		margin-top: 60px;
		line-height: 3rem;
	}
	.uk-list a{
		font-size: 25px;
		text-decoration: none;
		transition: 0.2s ease-in-out;
	}
	.uk-list a:hover, i:hover{
		color: #f2c763;
	}

	.off-socials {
		position: absolute;
		bottom: 50px;

	}
	.off-socials i{
		font-size: 25px;
		margin-right: 15px;
		transition: 0.2s ease-in-out;
	}
	
</style>