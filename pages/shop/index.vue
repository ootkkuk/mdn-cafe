<template>
  <layout-wrapper>
    <layout-visual title="Shop" :height="40" visual="visual-shop"/>
    <div class="container w-full mx-auto pt-20 pb-20 px-6 md:px-0">
      <table class="table-auto w-full mb-10">
        <tbody>
          <tr>
            <th class="border px-4 py-2">店舗名</th>
            <td class="border px-4 py-2">Mdnカフェ</td>
          </tr>
          <tr>
            <th class="border px-4 py-2">店舗住所</th>
            <td class="border px-4 py-2">〒101-0051<br>東京都千代田区神田神保町1-105<br>神保町三井ビルディング22F</td>
          </tr>
          <tr>
            <th class="border px-4 py-2">座席数</th>
            <td class="border px-4 py-2">50席</td>
          </tr>
          <tr>
            <th class="border px-4 py-2">アクセス</th>
            <td class="border px-4 py-2">○○駅5番出口から徒歩1分</td>
          </tr>
        </tbody>
      </table>
      <div class="mb-10">
        <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m12!1m3!1d13047.637143840588!2d136.89313769999998!3d35.15888305!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!5e0!3m2!1sja!2sjp!4v1677133340703!5m2!1sja!2sjp" frameborder="0" allowfullscreen="true" loading="lazy" referrerpolicy="no-referrer-when-downgrade" class="w-full h-64"></iframe>
      </div>
      <div class="mx-auto mb-10 text-center">
        <nuxt-link to="/" class="rounded-lg px-4 md:px-5 xl:px-4 py-3 md:py-4 xl:py-3 bg-white hover:bg-gray-200 md:text-lg xl:text-base text-gray-800 font-semibold leading-tight shadow-md">トップへ戻る</nuxt-link>
      </div>
    </div><!-- /.container -->
  </layout-wrapper>
</template>