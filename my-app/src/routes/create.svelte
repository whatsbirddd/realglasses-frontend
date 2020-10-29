<script>
    let relation = 'Friend';
</script>


<h2>Chat Style</h2>

<label>
	<input type=checkbox group={relation} value="Family">
	Family
</label>

<label>
	<input type=checkbox group={relation} value="Friend">
	Friend
</label>

<label>
	<input type=checkbox group={relation} value="Couple">
	Couple
</label>

<label>
	<input type=checkbox group={relation} value="first">
	We first met!
</label>


<label>
	<input type=checkbox group={relation} value="closer">
	We want to be closer!
</label>

{#if relation.length === 0}
	<p>Please select one</p>
{:else}
	<p>
		Have a good time
	</p>
{/if}
