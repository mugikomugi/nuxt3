<template>
  <footer class="footer panel" id="footer">
    <section class="foterInner eBox6">
      <img src="~/assets/image/logo-or.svg" alt="" />
      <h3 class="footerTitle">Gallery Nuxt.ver</h3>
      <p class="footerSub">Afterword</p>
      <!-- <p class="myName">mugikomugi</p> -->
      <p class="footerText">
        サイトデザインをするにはシステムやデータベースの知識も必要と感じ、スクリプト言語も勉強中。<br />今回、Nuxtで初めてサイトを構築しましたが、最初のサイト設計がとても重要だと痛感しました。下層ページはTOPページと違う作りにしたかったのでheaderとfooterは別コンポーネントにしましたが、リンク部分は一緒なので変更したい場合それぞれ書き換えることになります。ページを増やしていく前提でのコンポーネント造りなど、システムがわかった上で設計🟰デザインすることはとても大切だと思います。
      </p>
    </section>
    <figure class="footerImg">
      <img src="~/assets/image/footer.jpg" alt="" />
      <figcaption>Illustrated by mugikomugi</figcaption>
    </figure>
    <ul class="snsLink">
      <li>
        <a
          href="https://github.com/mugikomugi?tab=repositories"
          target="_blank"
          rel="noopener"
          ><img src="~/assets/image/git.svg" alt="Git Hub"
        /></a>
      </li>
      <li>
        <a
          href="https://qiita.com/kanrek_jyosi/items/ffbeab1ce30da87832ab"
          target="_blank"
          rel="noopener"
          ><img src="~/assets/image/qiita.svg" alt="Qiita"
        /></a>
      </li>
    </ul>
    <div class="copy">
      <small>Copyright 2024 mugikomugi All Rights Reserved. 無断転載禁止</small>
    </div>
  </footer>
</template>