<script>
	let groupcode ="";
	function chatpage(){

	}
</script>

<style>
	body{
		height : 100vh;
		margin: 0;
		background: linear-gradient(#95cd7d 75%, #FFEEA5 25%);
	}
	h1,p{
		text-align: center;
		color: #ffeea5;
		font-weight: 700;
	}
	input{
		position: absolute;
		top: 50%;
		left:30%;
		width: 300px;
		height: 50px;
		background-color: #95cd7d;
		border: thick solid #ffeea5;
	}
	#join{
		position: relative;
		top: 50%;
		left: 75%;
		background-color: #ffeea5;
		color: white;
		text-shadow: 1px 1px 1px 1px #000000;
		border:none;
		width: 100px;
		height: 50px;
		font-size: large;
		font-weight: 600;
	}
	#create{
		position : absolute;
		left: 40%;
		bottom: 20%;
		background-color:#95cd7d;
		border: none;
		color:white;
		font-size: large;
		text-align: center;
		width:200px;
		height: 50px;
	}
	
</style>

<svelte:head>
	<title>Join</title>
</svelte:head>

<body>
	<div class = "green"> 
		<h1>Already in a group?</h1>
		<p>Please enter the group code</p>
		<input value = {groupcode}>
		<button id= "join" on:click = {chatpage}>JOIN</button>
	</div>
	<button id= "create">Create a group!</button>
</body>
