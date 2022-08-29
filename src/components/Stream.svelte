<script type="text/javascript">
	import Tracklist from '../shared/TrackList.svelte'

	const songList = [
		{id:1, songName:"Intro:Save us",albumName:"[Apocalypse : Save us]",duration:"1:01"},
		{id:2, songName:"Locked Inside A Door",albumName:"[Apocalypse : Save us]",duration:"3:07"},
		{id:3, songName:"MAISON",albumName:"[Apocalypse : Save us]",duration:"3:05"},
		{id:4, songName:"Starlight",albumName:"[Apocalypse : Save us]",duration:"3:19"},
		{id:5, songName:"Together",albumName:"[Apocalypse : Save us]",duration:"3:44"},
		{id:6, songName:"Always",albumName:"[Apocalypse : Save us]",duration:"4:29"},
		{id:7, songName:"Skit : The seven doors",albumName:"[Apocalypse : Save us]",duration:"1:45"},
		{id:8, songName:"Cherry (Real Miracle) (JI U SOLO)",albumName:"[Apocalypse : Save us]",duration:"3:15"},
		{id:9, songName:"No Dot (SU A SOLO)",albumName:"[Apocalypse : Save us]",duration:"3:19"},
		{id:10, songName:"Entrancing (SIYEON SOLO)",albumName:"[Apocalypse : Save us]",duration:"3:32"},
		{id:11, songName:"Winter (HANDONG SOLO)",albumName:"[Apocalypse : Save us]",duration:"3:15"},
		{id:12, songName:"For (YOOHYEON SOLO)",albumName:"[Apocalypse : Save us]",duration:"3:45"},
		{id:13, songName:"Beauty Full (DAMI SOLO)",albumName:"[Apocalypse : Save us]",duration:"3:03"},
		{id:14, songName:"Playground (GAHYEON SOLO)",albumName:"[Apocalypse : Save us]",duration:"3:01"}


	]

	

	
</script>
<main>
	<div class="stream-options">
		<h1 >STREAM IT YOUR WAY </h1>
		<div class="stream-icons">
			<a href="https://open.spotify.com/album/1ONjVRtxAqiTivu0EiEBm5?si=_7w_o7XSTHq29Z6ZhGSHzQ" target="_blank"><i class="fa-brands fa-spotify" uk-tooltip="title:Spotify; pos: bottom; delay: 300"></i></a>
			<a href="https://music.apple.com/us/album/apocalypse-save-us/1617742170" target="_blank"><i class="fa-brands fa-apple"  uk-tooltip="title:Apple Music; pos: bottom; delay: 300"></i></a>
			<a href="https://deezer.page.link/MtTWXU4nNUyMocXu8" target="_blank"><i class="fa-brands fa-deezer" uk-tooltip="title:Deezer; pos: bottom; delay: 300"></i></a>
		</div>
	</div>

	<h1>TRACK LIST</h1>
	<div class="track-list">
		{#each songList as songs}
		<Tracklist trackNumber={songs.id} songName={songs.songName} albumName={songs.albumName} trackDuration ={songs.duration}/>

		{/each}
		
	</div>
</main>

<style type="text/css">
	h1{
		font-weight: 500;
		color: white;
		font-family: 'Aboreto', cursive;
	}
	main{
		display: block;
		margin: 0 auto;
		width: 80%;
	}

	.stream-options h1, .stream-icons i{
		color: white;
	}

	.stream-icons{
		display: flex;
		align-items: center;
		justify-content: space-between;
		width: 12rem;
		padding: 10px;

	}
	.stream-icons a i{
		margin-right: 20px;
		font-size: 30px;
		transition: 0.2s ease-in-out;

	}
	.stream-icons a i:hover{
		color:#f2c763; 

	}


	
</style>