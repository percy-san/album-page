<script type="text/javascript">
	export let trackNumber = ""
	export let songName = ""
	export let albumName = ""
	export let trackDuration = ""
</script>


<main>
	<div class="left">
		<p class="number">{trackNumber}</p>
			
		<div class="song-info">
			<p class="song-name">{songName}</p>
			<p class="album">{albumName}</p>
		</div>
	</div>
	<div class="right">
		<p class="duration">{trackDuration}</p>
	</div>

</main>


<style type="text/css">


	main{
		display: flex;
		align-items: center;
		justify-content: space-between;
		padding: 10px 5px 0 5px;
		margin-top: 20px;
		transition:0.2s ease-in-out;	
	}

	.left{
		display: flex;
		align-items: center;
	}
	.number{
		font-size: 20px;
		margin-right: 20px;
	}

	.song-info{
		line-height: 3px;
	}
	.song-name, .album, .number, .duration{color: white;}
	.song-name{
		font-weight: 500;
		font-size: 20px;
	}
	.album{
		font-weight: 200;
		font-size: 15px;
	}
	
</style>