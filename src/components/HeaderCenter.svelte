<script type="text/javascript">
	
</script>

<main>
	<div class="left">
		<img src="./img/albums/Apocalypse_Save_Us.jpg" alt="cover">
		<p><span>Apocalypse-Save Us</span> - Released:April 12, 2022</p>
	</div>
	<div class="right">
		<h1>APOCALYPSE-SAVE US</h1>
		<h3>Dreamcatcher</h3>
		<a href="https://open.spotify.com/album/1ONjVRtxAqiTivu0EiEBm5?si=_7w_o7XSTHq29Z6ZhGSHzQ" target="_blank"><button class="listen-now"><span uk-icon="icon: play; ratio:2"></span>LISTEN NOW</button></a>
	</div>
</main>

<style type="text/css">
	main{
		display:flex;
		align-items: center;
		gap:40px;

	}
	.left p{
		margin-top: 2px;
		color: white
	}
	.left img{
		width: 25rem;
	}
	.left p span{color: #F2C763;}

	
	.right h1, h3{
		color: white;
		font-family: 'Aboreto', cursive;
	}
	.listen-now{
		background-color: #f2c763;
		color: white;
		height: 50px;
		width: 12rem;
		border: none;
		border-radius: 2px;
		padding-right: 2px;
		cursor: pointer;
		text-align: justify;
		letter-spacing: 2px;
		transition: 0.2s ease-in-out;
		font-family: 'Aboreto', cursive;
	}
	.listen-now:hover{
		color: #101820;
		background: white;

	}

	

	@media screen and (max-width: 900px) {
		main{
			display:flex;
			flex-direction: column;
			margin-top: -20px;
		}
		.left img{
			width: 20rem;
		}
		.left h1{
			font-size: 20px;
		}


}
	
</style>