---
layout: default
lang: en
title: "Privacy Policy — It Is Done"
permalink: /privacy/
---
<script>
(function () {
  if (location.search.indexOf('lang=en') >= 0) return;
  var l = ((navigator.languages && navigator.languages[0]) || navigator.language || '').toLowerCase();
  var t = /^zh-(hant|tw|hk|mo)/.test(l) ? 'zh-Hant' : { ko: 'ko', ja: 'ja', de: 'de', fr: 'fr', es: 'es', it: 'it', pt: 'pt' }[l.split('-')[0]];
  if (t) location.replace(t + '/');
})();
</script>
<nav class="langs" aria-label="Language"><strong>English</strong> · <a href="./ko/" hreflang="ko">한국어</a> · <a href="./ja/" hreflang="ja">日本語</a> · <a href="./zh-Hant/" hreflang="zh-Hant">繁體中文</a> · <a href="./de/" hreflang="de">Deutsch</a> · <a href="./fr/" hreflang="fr">Français</a> · <a href="./es/" hreflang="es">Español</a> · <a href="./it/" hreflang="it">Italiano</a> · <a href="./pt/" hreflang="pt">Português</a></nav>

{% include privacy-en.md %}
