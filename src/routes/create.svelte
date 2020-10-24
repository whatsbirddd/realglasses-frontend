<svelte:head>
	<title>Real Glasses</title>
</svelte:head>

<p>그룹 관계를 선택하세요.</p>
<form action="/group" method="post">
  <input type="radio" id="family" name="relation" value="family" />
  <label for="family">가족</label>
  <input type="radio" id="friend" name="relation" value="friend" />
  <label for="friend">친구</label>
  <input type="radio" id="ice-breaking" name="relation" value="ice-breaking" />
  <label for="ice-breaking">친해지고 싶어요</label>
  <button type="submit">그룹 만들기</button>
</form>
