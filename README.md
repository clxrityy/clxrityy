<style>
	.main {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
	}
	.banner-container {
		position: relative;
		text-align: center;
	}
	.banner {
		width: 100%;
	}
	.banner-txt {
		position: absolute;
  		top: 50%;
  		left: 50%;
  		transform: translate(-50%, -50%);
		display: flex;
		flex-direction: row;
		align-items: center;
	}
	.main-container {
		display: flex;
		flex-direction: row;
		align-items: center;
		justify-content: space-between;
	}
	.right h5 {
		display: flex;
		flex-direction: column;
	}
	.right h4 {
		display: flex;
		flex-direction: row;
		align-items: center;
		gap: 1px;
	}
</style>

<div class="main">
	<div class="banner-container">
		<img class="banner" src="./img/clxrity_banner.png" />
		<div class="banner-txt">
			<h1>
				clxrity
				<img src="./img/potted_plant.gif" width="25px" />
			</h1>
		</div>
	</div>
	<div class="main-container">
		<div class="right">
			<h4>
				Web Developer / Music Producer
			</h4>
			<p>
				I'm a networking student who codes & makes music in my free time.
			</p>
			<h5>
				<a href="https://mjanglin.com">mjanglin.com</a>
				<a href="mailto:contact@mjanglin.com">contact@mjanglin.com</a>
			</h5>
			<hr />
			<a href="https://open.spotify.com/artist/0HaFO6TLXEZ2De3d67dThV">
				<img src="./img/spotify.png" width="50px" />
			</a>
			<a href="https://soundcloud.com/clxrityy">
				<img src="./img/soundcloud.png" width="50px" />
			</a>
			<a href="https://www.instagram.com/mjxnglin/">
				<img src="./img/instagram.png" width="50px" />
			</a>
		</div>
		<div class="left">
			<img src="./img/clxrity_fountain.gif" width="250px" />
		</div>
	</div>
</div>
