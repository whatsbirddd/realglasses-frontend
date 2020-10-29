<script>
	import successkid from 'images/successkid.jpg';
</script>

<style>
    figure{
        height: 100px;
        width: 100px;
        background-color:#95cd7d;
    }

	img {
		width: 400%;
		max-width: 400px;
		margin: 0 0 1em 0;
	}

	p {
		margin: 1em auto;
	}

	@media (min-width: 480px) {
	}
</style>

<svelte:head>
	<title>Have a fun</title>
</svelte:head>

<figure>
	<img alt="Success Kid" src="{successkid}">
	<figcaption>Have fun!</figcaption>
</figure>

<p><strong>loading...</strong></p>