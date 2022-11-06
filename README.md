# javascript-studies

Template Literals (önceki adıyla Template Strings), ES6 ile gelmiş bir string yazma şeklidir.
Örnek: `Bu bir yeni string örneğidir.` içerisinde ${} ile kod çalıştırabilr veya değişken çağırabilirsin.

-Çok Satırlı Dize Yazımı
-İnterpolasyon, metin içerisinde değişken kullanmak anlamına gelir.
-HTML Şablonları

const kisi = `
<p>${ad}</>
<p>${soyad}</>
<p>${gozRengi}</>
<p>${yas}</>
`;

document.body.innerHTML = kisi;

Template Literals;

Kod okunabilirliğini kolaylaştırır,
Stringler içerisinde değişken yazma kolaylığını sağlar,
Şablon etiketlerini daha az karmaşık hale getirir.
