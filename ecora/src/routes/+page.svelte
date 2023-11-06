<script>
	import '../styles.css'
</script>

<svelte:head>
	<title>Welcome to Ecora, powered by PlantBox</title>
</svelte:head>

<style>
	.logo {
		width: 100%;
		max-width: 500px;
		margin: 0 auto;
		display: block;
	
	}

	.button-container {
		position: absolute;
		bottom: 20%;
		left: 50%;
		transform: translateX(-50%);
		/* width: 80%; */
		/* margin: 0 auto; */
		display: flex;
		flex-direction: column;
		gap: 15px;
	}
</style>

<ion-content>
	<img src="/plantbox-logo.jpg" alt="PlantBox logo" class="logo"/>
	<div class="button-container default">
		<ion-button expand="block" color="dark" href="/app/login">Login</ion-button>
		<ion-button expand="block" color="medium">Register</ion-button>
	</div>
</ion-content>