<script setup lang="ts">

</script>

<template>
<body>
  <div class="section">
    <div class="title">
      <h2>Welcome to Aokiju Labo!</h2>
    </div>
    <div class="text">
      <h3>
        <p>こんにちは！Raitoです！</p>
        <p>ついにバージョンが上がりました！</p>
        <p>元のサイトはHTML/CSSでコーディングしてましたが、Ver.2.0からNode.js/Nuxt.jsでコーディングしています！</p>
        <p>HTML/CSSでできなかったことができるようになったので、適当に試してみたいと思います！</p>
      </h3>
    </div>
  </div>

  <div class="section">
    <div class="title">
      <h2>自己紹介</h2>
    </div>
    <div class="text">
      <h3>
        <p>名前：Raito</p>
        <p>好きな食べ物は和菓子</p>
        <p>趣味はルービックキューブ!</p>
        <p>3×3の自己ベストは12.95秒</p>
        <p>C++,C,Ruby,JavaScriptを勉強中!</p>
      </h3>
    </div>
  </div>

  <div class="section">
    <div class="title">
      <h2>作成したもの</h2>
    </div>
    <div class="text">
      <NuxtLink to="/">Aokiju Labo</NuxtLink>
      <h3>
        <p>このサイトです。自分の制作したものや趣味のものを載せています。自分の技術が上がったらアップデートしていきます。</p>
      </h3>
    </div>
  </div>

  <div class="section">
    <div class="title">
      <h2>ニュース</h2>
    </div>
        <h3>変更したことなどの記録を上げます！</h3>
        <div class="explain">
          <ul class="news">
            <li><NuxtLink to="/news/20241013">2024/10/16:Ver.2.0稼働！</NuxtLink></li>
            <li><NuxtLink to="/news/20241013">2024/10/13:サイト作成開始！</NuxtLink></li>
          </ul>
        </div>
    </div>
</body>
</template>