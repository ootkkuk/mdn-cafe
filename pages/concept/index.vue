<template>
  <layout-wrapper>
    <layout-visual title="Concept" :height="40" visual="visual-concept"/>
    <div class="container w-full mx-auto pt-20 pb-20 px-6 md:px-0">
      <h3 class="text-2xl text-red-800 font-extrabold mb-5 text-center">打ち合わせやリモートワークができるちょっとした空間</h3>
      <div class="clearfix p-4 mb-10">
        <img src="/assets/img/concept.jpg" class="float-right ml-4 my-2 h-56" alt="">
        <div>
          <p class="mb-5">
            Mdn Cafeでは、リモートワークや会社の打ち合わせなどが快適に行える空間を提供するカフェです。<br>
            リモートワークや打ち合わせを快適にするため席は完全個室にしています。<br>
            オンラインでの作業ができるようにWi-Fi環境も完備しています。また、週末は勉強会の場所としても提供しています。
          </p>
          <p class="mb-5">
            お食事は天然素材を使ったドーナッツ・パンケーキを開発しています。<br>
            シンプルな素材と調理方法で食材本来の味を引き立てる自慢のドーナッツ・パンケーキをご提供しています。<br>
            コーヒーはブラジル産の豆を使用して、酸味とスッキリとして苦味があるコーヒーになります。
          </p>
        </div>
      </div>
      <base-button name="トップへもどる" link="/" />
    </div><!-- /.container -->
  </layout-wrapper>
</template>

<script>
  export default {
    head(){
      return {
        title: 'コンセプト',
        meta: [
          {
            hid: 'description',
            name: 'description',
            content: 'コンセプトページの説明'
          }
        ]
      }
    }
  }
</script>