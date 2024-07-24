<script setup lang="ts">

</script>

<template>
  <!DOCTYPE html>
  <html lang="ko">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>QnA 게시판</title>
  </head>
  <body>
  <main>
    <article class="question">
      <h1>
        <img src="../assets/Q.png" alt="질문 아이콘">
        <span>공부 잘하는 법 알려주세요</span>
      </h1>
      <p class="question-author">홍길동</p>
      <p class="question-created-at">2024-07-22</p>
      <p class="question-content">성적이 안나와서 고민이에요 ㅠㅠ</p>
    </article>

    <section class="answers">
      <h2>
        <img src="../assets/A.png" alt="질문 아이콘">
        총 3개의 답변이 작성되었습니다
      </h2>

      <div class="answer">
        <div class="answer-meta">
          <p class="answer-author">금잔디</p>
          <p class="answer-created-at">2024-07-22</p>
          <p class="likes">17</p>
        </div>
        <p class="answer-content">교과서 위주로 공부하시면 됩니다.</p>
      </div>
    </section>

    <nav class="pagination">
      <span>1</span> | <a href="#">2</a> | <a href="#">3</a>
    </nav>
  </main>
  </body>
  </html>
</template>

<style scoped>

</style>