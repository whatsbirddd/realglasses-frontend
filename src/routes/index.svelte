<script>
	import axios from 'axios';
	import { URL } from '../../config';

	let groupCode;
	let url;

	function handleInput(e) {
		console.log(e.target.value);
		groupCode = e.target.value;
		url = URL + `joinGroup/${groupCode}`;
	}

	function handleClick() {
		axios.get(url)
		.then(function(res) {
			console.log(res);
		})
		.catch(function(err) {
			console.log(err);
		});
	}
</script>

<svelte:head>
	<title>Real Glasses</title>
</svelte:head>

<div>그룹 참여하기</div>
<div>
	<input type="text" placeholder="그룹 코드를 입력하세요" on:input={handleInput} />
	<button type="submit" on:click={handleClick}>참여하기</button>
</div>
<hr />
<a href="/create">그룹 만들기</a>
