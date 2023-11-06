<script>
    import './../../../styles.css'
</script>

<svelte:head>
	<title>Ecora - App</title>
</svelte:head>

<style>
    .logo {
		width: 100%;
		max-width: 300px;
		margin: 0 auto;
		display: block;
	
	}

    .login-content {
        width: 80%;
        margin:0 auto;
    }
</style>

<ion-content>
	<img src="/plantbox-logo.jpg" alt="PlantBox logo" class="logo"/>
    <div class="login-content default">
        <h2>Welcome!</h2>
        <p>please login to continue our app</p>
        <ion-item>
            <ion-input label="Email" label-placement="stacked" type="email" placeholder="email@domain.com"></ion-input>
        </ion-item>
        <ion-item>
            <ion-input label="Password" label-placement="stacked" type="password" placeholder="****"></ion-input>
        </ion-item>
        <ion-button expand="block" color="dark">Login</ion-button>
    </div>
    
</ion-content>
