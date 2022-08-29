<script>
	import Nav from './components/Nav.svelte'
	import HeaderCenter from './components/HeaderCenter.svelte'
	import MusicVideo from './components/MusicVideo.svelte'
	import OtherReleases from './components/OtherReleases.svelte'
	import Footer from './components/footer.svelte'
	import Stream from './components/Stream.svelte'
	
</script>

<main>
	<div class="header">
		<Nav />
		<div class="center">
			<HeaderCenter/>
		</div>
	</div>
	<Stream/>
	<MusicVideo/>
	<OtherReleases/>
	<Footer/>


	
</main>




<style type="text/css">
	main{
		display: grid;

		background-color: 	black;
	}
	.header{
		background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 1)), url("../img/group-img-min.jpg");
		background-position: center;
  		background-repeat: no-repeat;
  		background-size: cover;
	    left: 0px;
	    top: 0px;
	    width: 100%;
	    height: 120vh;
	    
	}
	.center{
		position: absolute;
		left: 55%;
    	top: 60%;
    	width: 90%;
    	transform: translate(-50%, -50%);	
	}

	@media screen and (max-width: 900px) {
		.center{
			position: absolute;
			left: 50%;
    		top: 70%;
    		width: 90%;
    		transform: translate(-50%, -50%);	
		}
		
}

	

	
</style>