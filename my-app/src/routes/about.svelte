<script>
	import Box from './Box.svelte';
	let groupcode ="";
	function chatpage(){

	}
</script>

<style>
	box{
		width:300px;
		height:45px;
		border: 3px;
		border-color: #FFEEA5;
		position : absolute;
		top: 40%;
		left:30%;
	}
	button{
		border: none;
	}
	#join{
		background-color: #FFEEA5;
		color: #FFFFFF;
		text-shadow : 1px,1px,1px,1px, #95cd7d;
		padding : 15px 32px;
		text-align: center;
		display : inline-block;
		font-size: 16px;
	}
	#create{
		background-color: #95cd7d;
		color: #ffffff;
		display : inline-block;
		font-size: 16px;
		padding: 15px 32px;
		display : inline-block;
		text-align: center;
	}
</style>

<svelte:head>
	<title>Join</title>
</svelte:head>

<body>
	<h1>Already in a group?</h1>
	<p>Please enter the group code</p>
	<box>
		<input value = {groupcode}>
	</box><button id= "join" on:click = {chatpage}>JOIN</button>
	<button id= "create">Create a group!</button>
</body>
