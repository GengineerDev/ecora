<script>
	import '../styles.css'
</script>

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
		width: 80%;
		margin: 0 auto;
		display: flex;
		flex-direction: column;
		gap: 15px;
	}
</style>

<ion-content>
	<img src="/plantbox-logo.jpg" alt="PlantBox logo" class="logo"/>
	<div class="button-container">
		<ion-button expand="block" color="dark">Login</ion-button>
		<ion-button expand="block" color="medium">Register</ion-button>
	</div>
	
	<!-- <ion-list>
		<ion-item>
			<ion-input label="Username"></ion-input>
		</ion-item>
		<ion-item>
			<ion-input label="Password" type="password"></ion-input>
		</ion-item>
	</ion-list> -->
</ion-content>