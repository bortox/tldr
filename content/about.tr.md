---
date: 2021-11-17
title: "TLDR Sayfaları Hakkında"
description: "TLDR Sayfaları nedir? Nasıl katkıda bulunulur? Bu web sitesi nedir"
---

> Uyarı: Bu sayfa otomatik olarak çevrilmiştir - bu web sitesindeki TLDR Sayfalarının aksine - bu nedenle çeviri hataları olabilir

![TLDR Pages Logo](/tldr-logo.png)

|Gitter|PRs|Contributors|Build Status|LICENSE|
|---|---|---|---|---|
[![Gitter chat][gitter-image]][gitter-url]|[![Merged PRs][prs-merged-image]][prs-merged-url]|[![GitHub contributors][contributors-image]][contributors-url]|[![Build status][github-actions-image]][github-actions-url]|[![license][license-image]][license-url]

[github-actions-url]: https://github.com/tldr-pages/tldr/actions
[github-actions-image]: https://img.shields.io/github/workflow/status/tldr-pages/tldr/CI.svg
[gitter-url]: https://gitter.im/tldr-pages/tldr
[gitter-image]: https://img.shields.io/badge/chat-on_gitter-deeppink
[prs-merged-url]: https://github.com/tldr-pages/tldr/pulls?q=is:pr+is:merged
[prs-merged-image]: https://img.shields.io/github/issues-pr-closed-raw/tldr-pages/tldr.svg?label=merged+PRs&color=green
[contributors-url]: https://github.com/tldr-pages/tldr/graphs/contributors
[contributors-image]: https://img.shields.io/github/contributors-anon/tldr-pages/tldr.svg
[license-url]: https://github.com/tldr-pages/tldr/blob/main/LICENSE.md
[license-image]: https://img.shields.io/badge/license-CC_BY_4.0-blue.svg
</div>

## tldr-pages nedir?

tldr-pages** projesi, işbirliği içinde sürdürülen yardım sayfalarının bir koleksiyonudur
daha basit ve daha erişilebilir bir tamamlayıcı sağlayan komut satırı araçları için
geleneksel [man sayfalarına](https://en.wikipedia.org/wiki/Man_page).

Belki de komut satırları dünyasında yenisinizdir? Belki biraz paslanmışsınızdır ya da `lsof` veya `tar` gibi komutların argümanlarını her zaman hatırlayamıyor musunuz?

Man tar'da açıklanan ilk seçeneğin şu olması kesinlikle yardımcı olmuyor:

```
-b blok
   Teyp sürücüsü G/Ç için blok boyutunu 512 baytlık kayıtlar halinde belirtin.
   Normalde bu argüman sadece teyp sürücülerine okuma veya yazma yaparken gereklidir,
   ve genellikle o zaman bile değil, çünkü 20 kayıtlık (10240 bayt) varsayılan blok boyutu çok yaygındır.
```

Pratik örneklere odaklanan daha basit yardım sayfaları için yer var gibi görünüyor.
Ne dersin?

![tar komutunu gösteren tldr istemcisinin animasyonlu SVG'si](/tldr-tar.svg)

> tar komutu için TLDR sayfası da bu web sitesinde bulunabilir [bu bağlantı](https://tldr.bortox.it/content/common/tar)

Bu depo tam olarak şudur: sürekli büyüyen bir örnek koleksiyonu.
En yaygın UNIX, Linux, macOS, SunOS, Android ve Windows komut satırı araçları için.

## Bu site nedir?

Bu sitenin amacı, topluluk tarafından yönetilen yardım sayfalarının bir koleksiyonu olan TLDR Sayfalarını
komut satırı araçları_ için web kullanıcılarının favori arama motorlarına 'TLDR sayfaları + komut_adı' yazmaları yeterlidir.

Şu anda basit bir Google aramasıyla bir komutun TLDR sayfasını bulmak mümkün değildir. İngilizce dışında belirli bir dilde bir komut ararken durum daha da kötüdür, çünkü genellikle yavaş ve tıklama tuzağı web siteleri vardır.

Aslında bu site yorumları ve paylaşımı da destekleyerek TLDR sayfalarını 'web dostu' hale getiriyor. 

### Analiz, izleme ve duyurular

Tabii ki **reklam** yok. 

Takip Matomo ile yapılır. Matomo **kişisel veri**[^1] toplamayacak şekilde ayarlanmıştır, bu nedenle GDPR uyumludur ve banner çerezleri gerektirmez. Eğer vazgeçmek isterseniz, [bunu buradan yapabilirsiniz](https://stats.bortox.it/index.php?module=CoreAdminHome&action=optOut&language=it).

Site PHP-Friends tarafından **Avrupa'da** barındırılmaktadır. web-carbon.com'a göre, veri merkezi **sürdürülebilir enerji** kullanıyor!

Siteyi **desteklemek** istiyorsanız (sunucular için ödeme yapıyorum), [**buraya bir şey bağışlayın**](https://bortox.it/contribuisci-cs-en).

### Neden bu site?

1. TLDR sayfalarını indekslemek ve birden fazla dilde çevrimiçi olarak kolayca aranabilir hale getirmek
2. sadece bir şey yazmak için

### Bu site nasıl çalışıyor?

* Markdown'daki TLDR kaynak dosyaları ve ilişkili Git verileri bir betikten okunur (30m).
* Hugo uyumlu sayfalar betik tarafından oluşturulur
* Hugo bu web sitesini (~6500 sayfa) sadece 10 saniyede oluşturuyor!

### Olası yeni özellikler

- [ ] Katılıma özel sayfalar
- DeepL ile otomatik çeviri (ücretsiz sürümde 500.000 karakter/ay'a kadar)


## Nasıl kullanılır

Bu sayfalara kendi bilgisayarınızdan erişmenin popüler ve kullanışlı bir yolu
Node.js istemcisini](https://github.com/tldr-pages/tldr-node-client) yüklemektir,
tldr-pages projesinin bakımcıları tarafından desteklenmektedir:

``sh
npm install -g tldr
```

Alternatif olarak, `pip3` aracılığıyla kurulabilen [Python istemcisi](https://github.com/tldr-pages/tldr-python-client) kullanabilirsiniz.

``sh
pip3 install tldr
```

Bu size `tar` gibi komutlar için basitleştirilmiş, okunması kolay bir kılavuza doğrudan erişim sağlar,
normal `man tar` yerine `tldr tar` yazarak erişilebilir.

Herhangi bir yazılım yüklemeden çevrimdışı bir sürüm istiyorsanız,
PDF versiyonuna] bakınız (https://tldr.sh/assets/tldr-book.pdf).

Bilgisayarınıza bir istemci yüklemeden göz atmak için
<https://tldr.ostera.io> adresindeki web istemcisine bakın.

Ayrıca topluluk tarafından sağlanan **çeşitli diğer müşteriler** de bulunmaktadır,
hem komut satırı hem de diğer platformlar için.
Müşterilerin tam listesi için [wiki](https://github.com/tldr-pages/tldr/wiki/tldr-pages-clients) adresimize bakın.


## tldr-pages'e nasıl katkıda bulunabilirim?

Tüm katkılara açığız!

Katkıda bulunmanın bazı yolları şunlardır

- Kapsanmayan favori komutunuzu eklemek.
- Örnekler eklemek veya mevcut bir sayfanın içeriğini geliştirmek.
- Konularımızdan istenen sayfaları [help wanted](https://github.com/tldr-pages/tldr/issues?q=is%3Aopen+is%3Aissue+label%3A%22help+wanted%22) etiketi ile ekleme.
- Sayfaların farklı dillere çevrilmesi.

Tüm `tldr` sayfaları Markdown ile yazılmıştır, bu nedenle oldukça kolay bir şekilde düzenlenebilir ve değişiklikler
Git ile komut satırında veya
GitHub web arayüzü üzerinden.

Misafirperver ve işbirlikçi](YÖNETİŞİM.md) bir topluluğu sürdürmeye çalışıyoruz.
İlk kez katkıda bulunacaksanız, [Katkı Yönergeleri]'ne (https://github.com/tldr-pages/tldr/blob/main/CONTRIBUTING.md) bir göz atın ve başlayın!

Çevirilere katkıda bulunmak isterseniz, <https://lukwebsforge.github.io/tldri18n/>
tüm çevirilerin genel ilerlemesini görmek ve hangi çevirilerin eksik veya güncel olmadığını öğrenmek için.

## 'tldr' ne anlama geliyor?

TL;DR "Çok uzun; okumadım" anlamına gelmektedir.
İnternet jargonundan türetilmiş olup, uzun bir metnin (veya bir kısmının)
(veya bir kısmı) çok uzun olduğu için atlanmıştır.
Daha fazla bilgi How-To Geek'in [makalesinde](https://www.howtogeek.com/435266/what-does-tldr-mean-and-how-do-you-use-it/).

[^1]: Ziyaretçi kaydı yok, çerezler olmadan izleme, [resmi matomo kılavuzu](https://matomo.org/faq/new-to-piwik/how-do-i-use-matomo-analytics-without-consent-or-cookie-banner/) uyarınca anonimleştirilmiş IP adresleri (2 bayt, 192.168.xxx.xxx gibi) ... 