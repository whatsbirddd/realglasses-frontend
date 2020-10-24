<svelte:head>
	<title>Real Glasses</title>
</svelte:head>

<main>
  <section>
    <canvas></canvas>
    <canvas></canvas>
  </section>
  <section>
    <button>대화코드 복사하기</button>
    <div>
      <p>대화거리가 필요해</p>
      <div>
        <button>선택형</button>
        <button>질문형</button>
      </div>
      <div>제일 싫어하는 음식이 무엇인가요?</div>
    </div>
  </section>
</main>

<style>
  main {
    display: flex;
  }
  canvas {
    border: 1px solid black;
  }
</style>
