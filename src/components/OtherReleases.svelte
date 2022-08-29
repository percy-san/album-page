<script type="text/javascript">

	const releases = [
		{album:"Alone_In_The_City.jpg", name:'Alone In The City', artist:"Dreamcatcher"},
		{album:"Tree_Of_Language.jpg", name:'Tree Of Language', artist:"Dreamcatcher"},
		{album:"Dystopia_Lose_Myself.jpg", name:'Dystopia_Lose_Myself', artist:"Dreamcatcher"},
		{album:"Dystopia_Road_to_Utopia.jpg", name:'Dystopia Road To Utopia', artist:"Dreamcatcher"},
		{album:"Raid_of_Dream.png", name:'Raid Of Dream', artist:"Dreamcatcher"},
		{album:"Summer_Holiday.jpg", name:'SummerHoliday', artist:"Dreamcatcher"}


	]
	
</script>

<main>
	<h1>CHECK OUT OTHER RELEASES</h1>
	<div class="other-release">
		{#each releases as release}
			<div>
		        <div class="card">
		            <div class="media-top">
		            	<img src={`../img/albums/${release.album}`} alt="Album">
		            </div>
		            <div class="body">
		                <h3 class="title">{release.name}</h3>
		                <p>{release.artist}</p>
		            </div>
		        </div>
		    </div>
		{/each}
		
	</div>
	<hr/>
		

	

</main>


<style type="text/css">
	h1{
		color: white;
		font-weight: 500;
		font-family: 'Aboreto', cursive;
	}
	main{
		display: block;
		margin: 0 auto;
		width: 80%;
		margin-top: 2rem;
		
	}

	.other-release{
		display: grid;
		grid-template-columns: 1fr 1fr 1fr 1fr 1fr 1fr;
		grid-template-rows: 1fr ;
		column-gap: 15px;
		padding: 10px;
	}
	.card{
		word-break: break-all;
		background-color: black;

	}
	
	.media-top{
		width: 100%;
	}
	.body{
		line-height: 0;
		color: white;
		width: 100%;
	}
	.body h3{
		color: white;
		font-weight: 500;
		font-size: 15px;
	}
	.body p{
		font-size: 12px;
		
		margin-top: -10px;
	}


	@media screen and (max-width: 900px) {
		h1{
			margin-bottom: 5rem;
		}
		.other-release{
			display: flex;
			flex-direction: column;
			align-items: center;
			gap:3rem;
		}
		

		.body h3{
			font-size: 20px;
		}
		.body p{
			font-size: 15px;
		}


	}

	
</style>