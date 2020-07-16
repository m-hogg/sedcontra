<style>
	#container {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
	}
	#logo {
		margin-top: 5%;
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
	}

	#topic {
		margin-top: 10%;
		max-width: 50%;
		border: 1px solid black;
		border-radius: 20px;
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		padding: 30px 100px;
	}

	#buttonbox {
		margin-top: 25px;
	}
</style>

<svelte:head>
	<title>SedContra</title>
</svelte:head>

<div id="container">
	<div id="logo">
		<!-- I'll get a logo in here eventually -->
		<h1>Sed Contra</h1>
		<h3>A Place to Debate</h3>
	</div>

	<div id="topic">
		<h2>Is a Hotdog a Sandwich?</h2>
		<h4>The age old question</h4>
		<div id="buttonbox">
			<button>Absolutely it is</button>
			<button>Of course it's not</button>
		</div>
	</div>
</div>