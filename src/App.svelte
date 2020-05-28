<script>
</script>

<main>
	<header><img src='./assets/redcrosslogo.png' alt='Red Cross Logo' width='25%'></header>
	<div class="center">
		<div>
		<h1 class="red">GIVE BLOOD</h1>
		<h1>SAVE LIVES</h1></div>
		<img src="./assets/redcross.png" alt="blood drop logo" width="300px" class="blood-drop"/>
	</div>
	<footer>
		<div class="links">
			<a href="https://www.redcross.org/give-blood.html/" target="_blank" rel="noopener noreferrer">
				<img src='./assets/donate-blood-white.png' alt='donate blood' width="30%" />
				Donate Blood
			</a>
		</div>
		<div class="links">
			<a href="https://www.redcross.org/volunteer/become-a-volunteer.html/" target="_blank" rel="noopener noreferrer" class="volunteer">
			<img src='./assets/volunteer.png' alt='Volunteer' width="30%"/>
			Volunteer
			</a>
		</div>
		<div class="links">
			<a href="https://www.redcross.org/donate/donation.html/" target="_blank" rel="noopener noreferrer">
			<img src='./assets/donate-money-white.png' alt='donate blood' width="30%" />
				Donate Money
			</a>
			</div>
	</footer>
</main>

<style>
@import url('https://fonts.googleapis.com/css2?family=Open+Sans&display=swap');
	main {
		background-image: url('/assets/bg-red-cross.jpg');
		min-height: 100vh;
 		height: 100vh;
		background-size: cover;
		background-repeat: no-repeat;
		background-position: center center;
		font-family: 'Open Sans', sans-serif;font-family: 'Open Sans', sans-serif;
		overflow: hidden;
		display: grid;
		grid-template-rows: 150px 1fr 250px;
	}

	header {
		padding: 20px;
	}

	.center {
		display: flex;
		align-items: center;
		align-content: center;
		justify-content: center;
		width: 100vw;
	}

	h1{
		font-size: 5vh;
		text-shadow: -1px -1px 1px rgba(255,255,255,.1), 1px 1px 1px rgba(0,0,0,.5);
	}

	.red {
		color: #9a0000;
	}

	footer {
		text-align: center;
		display: flex;
		justify-content: center;
		align-items: flex-start;
	}

	.links {
		display: grid;
		justify-items: center;
	}

	a {	
		display: grid;
		justify-items: center;
		position: relative;
		top: -1px;
		text-decoration: none;
		color: white;
		font-weight: bold;
		text-shadow: -1px -1px 1px rgba(255,255,255,.1), 1px 1px 1px rgba(0,0,0,.5);
	}

	a>img {
		padding: 5px;
		border-radius: 25px;
		background-color: transparent;
		transition: all 0.3s linear;
	}

	a>img:hover {
		border-radius: 10px;
		background-color: #111;
	}

	@media only screen and (max-width: 600px) {
		main {
			grid-template-rows: 100px 1fr 1fr;
		}
		.blood-drop {
			width: 150px;
		}

		footer {
			display: grid;
		}
	}
</style>