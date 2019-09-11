# ES6 Türkçe Kaynaklar Listesi (:zap: Liste devamlı güncelleniyor)

ES6 konuları hakkında birşeyler yazmalıyım dedim, kaynakları araştırırken bu konuda çok Türkçe kaynak olduğunu gördüm. Bu sevindirici bir durum. Sonra ES6 hakkında yazı yazmak yerine bu yazılanları kategorize edip bir liste haline getirip github'ta paylaşmak daha mantıklı olacağını düşündüm. Yeni makaleler eklendikçe veya bu makalelerden linki ölen olursa çıkarmayı hep beraber yaparız dedim. 

Ben okuduğum kaynaklara göre bir sınıflandırma yaptım. Bu konuda farklı önerisi olan arkadaşların fikirlerine açığım. Zaten listenin github'ta olma sebebide bu. Bu listeyi canlı tutmak.

Buradan aşağıdaki listede yazısı bulunan tüm arkadaşlara şükranlarımı sunuyorum.

Benim gözümden kaçan ve aramalarımda karşıma çıkmayan kaynakları eklemeyi unutmayın lütfen.

> video eğitimlerinin yanına :video_camera: işaretini koydum.

> yeni eklediğim yazıların başına :star: işaretini koydum.

> Sitesine erişemediğim yazıları 🚫 işaretiyle belirttim.

## İçindekiler

 - [ES6 giriş ve toplu ES6 yazıları](#es6-giriş-ve-toplu-es6-yazıları)
 - [Değişkenler let ve const](#değişkenler-let-ve-const)
 - [Template literal](#template-literal)
 - [Ok (Arrow) fonksiyonları](#ok-arrow-fonksiyonları)
 - [ES6 Yeni String Metodları](#es6-yeni-string-metodları)
 - [ES6 Dizi İşlemleri](#es6-dizi-işlemleri)
 - [Başlangıç parametre değerleri (Default Parameters)](#başlangıç-parametre-değerleri-default-parameters)
 - [Spread Operator (...) ve Rest parametresi](#spread-operator--ve-rest-parametresi)
 - [Object literal](#object-literal)
 - [Destructuring](#destructuring)
 - [Sınıf (Class)](#sınıf-class)
 - [Genarator fonksiyonlar](#genarator-fonksiyonlar)
 - [Modüller (Modules)](#modüller-modules)
 - [Promise](#promise)
 - [Sembol (Symbol)](#sembol-symbol)
 - [Set Nesnesi](#set-nesnesi)
 - [Map ve WeakMap Nesneleri](#map-ve-weakmap-nesneleri)
 - [Proxy](#proxy)
 - [Ücretli Eğitimler](#ücretli-eğitimler)

## ES6 giriş ve toplu ES6 yazıları

 - [ECMAScript 6 Hakkında](https://omergulcicek.github.io/es6/giris/ecmascript-6-hakkinda) - Ömer Gülçiçek
 -  [JavaScript'in Yeni Sürümü EcmaScript 6'ya Giriş Türkçe Sunum](https://www.youtube.com/watch?v=Vp4K03xWsgE&feature=youtu.be) - Üstün Özgür :video_camera:
 - [JavaScript ES6](https://www.yusufsezer.com.tr/javascript-es6/) - Yusuf Sezer
 - [ES6: Nedir?](https://www.youtube.com/watch?v=10QS23uUvF4) - Uçbirim :video_camera:
 - 🚫 ECMAScript 6 (ES6) Nedir? Nasıl Kullanılır? - buraktokak.com/ecmascript-6-es6-nedir-nasil-kullanilir/ - Burak Tokak
 - [ES6 Eğitimi - Ders 1](https://www.linkedin.com/pulse/es6-e%C4%9Fitimi-ders-1-hale-nur-%C3%A7al%C4%B1%C5%9Fkan/) - Hale Nur Çalışkan
 - [ES5, ES6, ES2016, ES.Next: JavaScript sürümleri nasıl ilerliyor?](http://oguzhan.in/es5-es6-es2016-es-next-javascript-surumleri-nasil-ilerliyor/) - Oğuzhan Aslan
 - [ES6 yazı serisi](https://indatawetrust.blogspot.com/2016/02/es6-ecmascript6-yazi-serisi.html) - Ahmet Şimşek
 - [ECMAScript6 nedir? Nasıl kullanılır, Neden kullanmalıyız?](https://cagatay.me/ecmascript6-nedir-nas%C4%B1l-kullan%C4%B1l%C4%B1r-neden-kullanmal%C4%B1y%C4%B1z-3-a1d092b7d261) - Çağatay Çalı
 - 🚫 EcmaScript 6 Nedir? Bilinmesi Gerekenler - mehmetmasa.com.tr/javascript-dersleri/ecmascript-6-nedir-bilinmesi-gerekenler/ - Mehmet Maşa
 - [Javascript Notları(ECMA6)-Başlangıç](https://www.youtube.com/watch?v=IMnmjHlc1l0) - Fatih Çakıroğlu :video_camera:
 - [ES6 / ES7 ile Javascript e gelen yenilikler](https://yazilimgunlugu.org/es6-es7-ile-javascript-e-gelen-yenilikler/) - Yazılım Günlüğü
 - [ES6](https://dhalsim.github.io/javascript/2015/11/14/es6) - Barış Aydek
 - [ECMAScript 6 (Harmony)](https://slides.com/azizarslan/ecmascript-6) - Aziz Arslan
 - [Javascript: Eski Köye Yeni Adet](http://bilisim.io/2019/03/12/javascript-eski-koye-yeni-adet/) - Tahir Kardak
 - [Airbnb JavaScript Kılavuzu - ECMAScript 6+ (ES 2015+) Özellikleri](https://github.com/eraycetinay/javascript#ecmascript-6-es-2015-%C3%96zellikleri) - Eray Çetinay
 - [Ecma Script nedir?](https://www.kodevreni.com/4149-reactjs-temel-anlat%C4%B1m/?do=findComment&comment=13810) - Halit Izgın / kodevreni
 - [Javascriptin en gıcık konuları: Webpack, Babel, Eslint ve Diğerleri](https://medium.com/t%C3%BCrkiye/javascriptin-en-g%C4%B1c%C4%B1k-konular%C4%B1-webpack-babel-eslint-ve-di%C4%9Ferleri-fb2e1232a085) - Murat Turkay
 - [ECMAScript 6 - ES6 - (ES 2015) Nedir?](http://www.webcebir.com/251-ecmascript-6-es6-es-2015-nedir-dersi.html) - webcebir
 - [ES6 ile Gelen Yenilikler](https://medium.com/@emreacara/es6-ile-gelen-yenilikler-8206e9d2654c) - Emre Acar
 - :star: [Javascript ES6 Notlar Part — 1](https://medium.com/@odayibasi/javascript-es6-notlar-part-1-a78acf9ba77e) - Onur Dayıbaşı

## Değişkenler let ve const

 - [var, const ve let](https://medium.com/@busramemis/js-var-const-ve-let-ce26bc9818f7)  - Büşra Memiş
 - [var’dan const-let’e - ECMAScript 6 - Türkçe Doküman](https://omergulcicek.github.io/es6/es6-temel-ozellikleri/var-dan-const-let-e)  - Ömer Gülçiçek
 - [IIFE’den blocklara  - ECMAScript 6 - Türkçe Doküman](https://omergulcicek.github.io/es6/es6-temel-ozellikleri/iifes-den-blocklara)  - Ömer Gülçiçek
 - [ECMAScript6 nedir? Nasıl kullanılır, Neden kullanmalıyız?](https://cagatay.me/ecmascript6-nedir-nas%C4%B1l-kullan%C4%B1l%C4%B1r-neden-kullanmal%C4%B1y%C4%B1z-3-a1d092b7d261) - Çağatay Çalı
 - [ES6 Değişkenler (var, let, const)](https://www.irfansimsar.com.tr/blog/yazilim/es6-degiskenler-var-let-const/) - İrfan Simsar
 - [ECMAScript 6 - Değişkenler](http://blog.sercaneraslan.com/ecmascript-6-degiskenler) - Sercan Eraslan
 - [javaScript Var, Let ve Const](http://www.webcebir.com/240-javascript-var-let-ve-const-dersi.html) - webcebir
 - [ES6 Eğitimi - Ders 3 (Değişkenler)](https://www.linkedin.com/pulse/es6-e%C4%9Fitimi-ders-3-de%C4%9Fi%C5%9Fkenler-hale-nur-%C3%A7al%C4%B1%C5%9Fkan/)  - Hale Nur Çalışkan
 - [JS Ders 1 Ecmascript 6 let kullanımı](https://www.youtube.com/watch?v=GanwZdZReco) - fehmiuyarnet :video_camera:
 - [JS Ders 2 Ecmascript 6 const kullanımı](https://www.youtube.com/watch?v=JrzV2bjEI-Q) - fehmiuyarnet :video_camera:
 - [Javascript Notları(ECMA6)-Değişlenler](https://www.youtube.com/watch?v=QnDI24SQh3c) - Fatih Çakıroğlu :video_camera:
 - [ECMAScript 6 – let Değişken Tipi](https://www.gencayyildiz.com/blog/ecmascript-6-let-degisken-tipi/) - Gencay Yıldız
 - [Ecmascript 6 Dersleri 1 - Var, Let ve Const - Part 1](https://www.youtube.com/watch?v=oYdr1w9Ti1M) - Yazılım Bilimi :video_camera:
 - [Scope, let ve const](https://www.e-adys.com/react-native/03-03-scope-let-ve-const/) - Erdinç Uzun
 - [JavaScript Tanımlamada var, let ve const farkı](https://ahmetonursolmaz.com.tr/javascript-var-let-ve-const-farki/) - Ahmet Onur Solmaz
 - [Javascript Dersleri 44 Let Ve Const Kullanımı (ES6)](https://youtu.be/d9pfCP5d1p8) - kolay video dersleri :video_camera:
 - [ECMAScript 6 ile gelen let, const, default parametreler](https://www.youtube.com/watch?v=i5KABnhogaE) - Tarık Güney :video_camera:
 - [Javascript’te Değişkenlerin Etki Alanları](https://www.haydarcan.com/javascriptte-degiskenlerin-etki-alanlari/) - Haydar Can
 - [JavaScript’de const ve Sabit Tanımlar](https://www.haydarcan.com/javascriptde-sabit-tanimlar-ve-string-veri-tipleri/) - Haydar Can
 - [Javascript Let,Const vs Var](https://www.youtube.com/watch?v=SZXKTvVNX7M) - sanalonyedi :video_camera:
 - [Popüler Bir Javascript İşe Alım Sorusu](http://erdoganb.com/2017/10/populer-bir-javascript-ise-alim-sorusu/) - Erdoğan Bavaş
 - [JavaScript | Function Scope vs Block Scope](https://medium.com/@tugrulbayrak/javascript-scope-65e86de65cff) - Tuğrul Bayrak
 - [Modern JavaScript(ES6+) Eğitiminden Notlar](https://malikmasis.blogspot.com/2019/05/modern-javascriptes6-egitiminden-notlar.html) - malikmasis
 - [Javascript | var-let-const kavramları #1](https://medium.com/@goktugsultan/https-medium-com-goktugsultan-es6-var-let-const-kavramlar-28f7512c72fc) - Götuğ Sultan

## Template literal

 - [Javascript ES6'dan En Çok Kullandığım 5 Özellik - 3 Template literals](https://blog.durul.me/2018/03/21/javascript-es6-en-cok-kullandigim-5-ozellik.html) - Durul Doktoroglu
 - [javaScript Template Literal](http://www.webcebir.com/227-javascript-template-literal-dersi.html) - webcebir
 - 🚫 ECMAScript 6 ile String ve Değişken Gömme Özelliği - buraktokak.com/ecmascript-ile-string-ve-degisken-gomme-ozelligi/  - Burak Tokak
 - [JAVASCRIPT’TE TEMPLATE LİTERAL VE DATE OBJESİ](https://www.kodportali.com/yazilim/javascriptte-template-literal/) - Kod Portali / Muhammet Ali Can
 - [JS Ders 9 Ecmascript 6 Template Literals](https://www.youtube.com/watch?v=yF_SsBMwqQk) - fehmiuyarnet :video_camera:
 - [ES6 Template strings nedir? Nasıl kullanılır?](https://indatawetrust.blogspot.com/2016/02/es6-template-strings-nedir-nasil-kullanilir.html)
 - [Javascript Notları(ECMA6)-TemplateString ve Default Deger](https://youtu.be/hAoc4HMTgcQ?t=155) - Fatih Çakıroğlu :video_camera:
 - [ECMAScript 6 – Template Literal](https://www.gencayyildiz.com/blog/ecmascript-6-template-literal/)  - Gencay Yıldız
 - [Template Literals](https://www.e-adys.com/react-native/03-09-template-literals/) - Erdinç Uzun
 - :star: [ES6: Template literals ve tagged template literals](https://www.youtube.com/watch?v=nTDMPMxFQJo) - uçbirim :video_camera:

## Ok (Arrow) fonksiyonları

 - [Arrow fonksiyonları - ECMAScript 6 - Türkçe Doküman](https://omergulcicek.github.io/es6/es6-temel-ozellikleri/arrow-fonksiyonlari) Ömer Gülçiçek
 - [Javascript ES6'dan En Çok Kullandığım 5 Özellik - 1 Arrow functions](https://blog.durul.me/2018/03/21/javascript-es6-en-cok-kullandigim-5-ozellik.html) - Durul Doktoroglu
 - [Nedir bu Arrow Function (ES6)](https://www.irfansimsar.com.tr/blog/yazilim/nedir-bu-arrow-function-es6/)) - İrfan Simsar
 - 🚫 ECMAScript 6 Arrow Fonksiyon Notasyonu Kullanımı - buraktokak.com/ecmascript-6-arrow-fonksiyon-notasyonu-kullanimi/ - Burak Tokak
 - [Arrow Function: Nerede kullanıyoruz? Neden Kullanıyoruz?](https://medium.com/@oyilmaztekin/arrow-function-nerede-kullan%C4%B1yoruz-neden-kullan%C4%B1yoruz-a45b07face82) - Özer Yılmaztekin
 - [Arrow functions - MDN Türkçe çeviri](https://developer.mozilla.org/tr/docs/Web/JavaScript/Reference/Functions/Arrow_functions) MDN
 - [ES6: Ok fonksiyon (arrow function) tanımlaması](https://www.youtube.com/watch?v=nOdEv46H0s0) - Uçbirim 
 - [ES6 arrow functions](https://medium.com/@emrahday/es6-arrow-functions-98c07d537ec0) - Emrah
 - [Javascript EcmaScript 2015 (ES6) ile gelen Arrow Function Kullanımı](https://www.youtube.com/watch?v=0P4NqV3q7Hs) - Sadık Turan :video_camera:
 - [JS Ders 5 Ecmascript 6 Arrow Functions](https://www.youtube.com/watch?v=1_9CZTE5Qao&t=216s) - fehmiuyarnet :video_camera:
 - [ECMAScript 6 – Arrow Functions](https://www.gencayyildiz.com/blog/ecmascript-6-arrow-functions/) - Gencay Yıldız
 - [Arrow Fonksiyonu](https://www.e-adys.com/react-native/03-04-arrow-fonksiyonu/) - Erdinç Uzun
 - [javaScript ARROW(OK) FONKSİYONLAR](http://www.webcebir.com/258-javascript-arrow-ok-fonksiyonlar-dersi.html) - Webcebir

## ES6 Yeni String Metodları

 - [ES6 Yeni String Metodları](https://www.irfansimsar.com.tr/blog/yazilim/es6-yeni-string-metodlari/) - İrfan Simsar
 - [JS Ders 18 Ecmascript 6 ile eklenen number ve string metodları](https://www.youtube.com/watch?v=Q2TBi1nP6JQ) - fehmiuyarnet :video_camera:
 - [ES6: find, includes, repeat ve bir kaç gömülü metod](https://www.youtube.com/watch?v=giAOiydwTbA) - uçbirim :video_camera:
 - [String Extensions](https://www.karalamalar.net/string-extensions/) - karalamalar

## ES6 Dizi İşlemleri

 - [JavaScript İle Temel Dizi İşlemleri](https://cagatay.me/javascript-i%CC%87le-temel-dizi-i%CC%87%C5%9Flemleri-javascript-array-operations-de040d8ac41e) - Çağatay Çalı
 - 🚫 Javascript Array.map() Metodu ve Kullanımı buraktokak.com/javascript-array-map-metodu-ve-kullanimi/ - Burak Tokak
 - [Javascript Map Metodu](https://yazilimtasarim.com/javascript-map-metodu/) - Mustafa Zahid EFE
 - [Javascript Filter Metodu](https://yazilimtasarim.com/__trashed-3/) - Mustafa Zahid EFE
 - [JavaScript hap yazısı : Array.some(), Array.every() ve Array.findIndex()](https://medium.com/@muratdogan/javascript-hap-yaz%C4%B1s%C4%B1-array-some-array-every-ve-array-findindex-f59aa2d87888) - Murat Doğan
 - [Bilmeniz gereken 10 JavaScript dizi(Array) metodu](https://medium.com/@yusufgungor/bilmeniz-gereken-10-javascript-dizi-metodu-4753424510fd) - Yusuf GÜNGÖR
 - [ES6: map ve filter fonksiyonları](https://www.youtube.com/watch?v=GOSBTrG6VW0) - Uçbirim :video_camera:
 - [Javascript: Map, Reduce Ve Filter – Bölüm 1](http://bilisim.io/2019/02/15/javascript-map-reduce-ve-filter-bolum-1/) - bilisim.io / Tahir Kardak
 - [Javascript: Map, Reduce Ve Filter — Bölüm 2](http://bilisim.io/2019/02/15/javascript-map-reduce-ve-filter%E2%80%8A-%E2%80%8Abolum-2/) - bilisim.io / Tahir Kardak
 - [Javascript: Map, Reduce Ve Filter — Bölüm 3](http://bilisim.io/2019/02/15/javascript-map-reduce-ve-filter%E2%80%8A-%E2%80%8Abolum-3/) - bilisim.io / Tahir Kardak
 - [Javascript: Map, Reduce Ve Filter — Bölüm 4](http://bilisim.io/2019/02/15/javascript-map-reduce-ve-filter%E2%80%8A-%E2%80%8Abolum-4/) - bilisim.io / Tahir Kardak
 - [Javascript Notları(ECMA6)-Diziler](https://www.youtube.com/watch?v=XFoID44CRzQ)  - Fatih Çakıroğlu :video_camera:
 - [Javascript Notları(ECMA6)-Diziler[Object.Keys]](https://www.youtube.com/watch?v=hB6FvYrwxbs) - Fatih Çakıroğlu :video_camera:
 - [ Javascript Notları(ECMA6)-Diziler[Some]](https://www.youtube.com/watch?v=cmiwG_lRAgg)  - Fatih Çakıroğlu :video_camera:
 - [Javascript Notları(ECMA6)-Diziler[Find]](https://www.youtube.com/watch?v=E7QHgnVarAQ) - Fatih Çakıroğlu :video_camera:
 - [Javascript Notları(ECMA6)-Diziler[Filter]](https://www.youtube.com/watch?v=4dyeVNVobS8) - Fatih Çakıroğlu :video_camera:
 - [Javascript Notları(ECMA6)-Diziler\[Reduce\]](https://www.youtube.com/watch?v=7DRCi4kZZbA)  - Fatih Çakıroğlu :video_camera:
 - [JavaScript Filter Map Reduce](https://medium.com/@clkgkhn/javascript-filter-map-reduce-1c3191d99ad2) - Gökhan Çelik
 - [Javascript reduce Fonksiyonu](https://medium.com/@ibrahim.kurce/javascript-reduce-fonksiyonu-da5e09ba2e44) - İbrahim Kürce
 - [Javascript’te Toplam Almanın Farklı Yöntemleri](https://medium.com/@ibrahim.kurce/javascripteki%CC%87-toplam-almanin-farkli-y%C3%B6ntemleri%CC%87-80718950a2c2) - İbrahim Kürce
 - [Custom filter ve map Fonksiyonları](https://medium.com/@ibrahim.kurce/custom-filter-ve-map-fonksiyonlar%C4%B1-b2b6278edb54) - İbrahim Kürce
  - [Map ve Reduce - Javascript](https://www.youtube.com/watch?v=SZXKTvVNX7M) - sanalonyedi :video_camera:

## Başlangıç parametre değerleri (Default Parameters)

 - [Parametreleri varsayılan değerleriyle kullanmak - ECMAScript 6 - Türkçe Doküman](https://omergulcicek.github.io/es6/es6-temel-ozellikleri/parametreleri-varsayilan-degerleriyle-kullanmak) - Ömer Gülçiçek
 - [Parametre isimlerini kullanmak - ECMAScript 6 - Türkçe Doküman](https://omergulcicek.github.io/es6/es6-temel-ozellikleri/parametre-isimlerini-kullanmak) - Ömer Gülçiçek
 - [JS Ders 3 Ecmascript 6 Default Parameters (Varsayılan Parametreler)](https://www.youtube.com/watch?v=Nkm8POOhnhQ) - fehmiuyarnet :video_camera:
 -  [Javascript Notları(ECMA6)-TemplateString ve Default Deger](https://youtu.be/hAoc4HMTgcQ) - Fatih Çakıroğlu :video_camera:
 - [Genişletilmiş Parametre Yönetimi](https://www.e-adys.com/react-native/03-10-genisletilmis-parametre-yonetimi/) - Erdinç Uzun
 - [ECMAScript 6: Default Values](http://ersu.me/article/javascript/ecmascript6-default-values) - Hakan Ersu
 - [javascript ES-6 Default Parameters (Varsayılan Parametreler)](http://www.webcebir.com/261-javascript-es-6-default-parameters-varsayilan-parametreler-dersi.html) - Webcebir

## Spread Operator (...) ve Rest parametresi

 - [apply()’den spread operatörlere - ECMAScript 6 - Türkçe Doküman](https://omergulcicek.github.io/es6/es6-temel-ozellikleri/applyden-spread-operatorlere) - Ömer Gülçiçek
 - [concat()’den spread operatörlere - ECMAScript 6 - Türkçe Doküman](https://omergulcicek.github.io/es6/es6-temel-ozellikleri/concatden-spread-operatorlere) - Ömer Gülçiçek
 -  [Javascript ES6'dan En Çok Kullandığım 5 Özellik - 4 Obje ve dizi rest/spread operatörleri](https://blog.durul.me/2018/03/21/javascript-es6-en-cok-kullandigim-5-ozellik.html) - Durul Doktoroğlu
 -  [Javascript’de destructuring hikayesi - Bolum 6: spreading operator ](https://medium.com/@emrahday/javascriptde-destructuring-hikayesi-bf5884ed1fa5) - Emrah
 - [JS Ders 10 Ecmascript 6 Spread Operator Kullanımı](https://www.youtube.com/watch?v=rG4syi1ZagY) - fehmiuyarnet :video_camera:
 - [Sen JavaScript’in Bir Lütfusun Spread Operatör - Extended Version :)](https://medium.com/@muratdogan/sen-javascriptin-bir-l%C3%BCtfusun-spread-operat%C3%B6r-extended-version-fa5de70beaeb) - Murat Doğan
 - [ES6: Spread (...) operatörü](https://www.youtube.com/watch?v=QuZeiud4vvE) - Uçbirim :video_camera:
 - [Javascript Harikaları-1 : Rest Parameters](http://bilisim.io/2019/02/20/javascript-harikalari-1-rest-parameters/) - bilisim.io / Tahir Kardak
 - [ES6 Default + rest + spread nedir? Nasıl kullanılır?](https://indatawetrust.blogspot.com/2016/02/es6-default-rest-spread-nedir-nasil-kullanilir.html) - Ahmet Şimşek
 - [ECMAScript 6 – Spread Operator](https://www.gencayyildiz.com/blog/ecmascript-6-spread-operator/) - Gencay Yıldız
 - [Gelişmiş Atama](https://www.e-adys.com/react-native/03-11-gelismis-atama/) - Erdinç Uzun

## Object literal

- [ES6 Enhanced object literals nedir? Nasıl kullanılır?](https://indatawetrust.blogspot.com/2016/02/es6-enhanced-object-literals-nedir-nasl.html) - Ahmet Şimşek
-  [Javascript ES6'dan En Çok Kullandığım 5 Özellik - 5 Property-value shorthand notation](https://blog.durul.me/2018/03/21/javascript-es6-en-cok-kullandigim-5-ozellik.html) - Durul Doktoroğlu
- [Javascript Nesne Tanımlama Yöntemleri](http://www.muratoner.net/javascript/javascript-nesne-tanimlama-yontemleri-bol-ornekli) - Murat Öner

## Destructuring

 - [Javascript ES6'dan En Çok Kullandığım 5 Özellik - 2 Property destructing](https://blog.durul.me/2018/03/21/javascript-es6-en-cok-kullandigim-5-ozellik.html) - Durul Doktoroğlu
 - [ECMAScript 6 - Destructuring](http://blog.sercaneraslan.com/ecmascript-6-destructuring) - Sercan Eraslan
 - [Javascript’de destructuring hikayesi](https://medium.com/@emrahday/javascriptde-destructuring-hikayesi-bf5884ed1fa5) - Emrah
 - [JS Ders 4 Ecmascript 6 Destructuring Assignment (Çoklu Değer Atama)](https://www.youtube.com/watch?v=Nk_7KL47EhI) - fehmiuyarnet :video_camera:
 - [ES6: destructuring örnekleri](https://www.youtube.com/watch?v=KbYi-LjyhHQ) - Uçbirim :video_camera:
 - [ECMAScript 6 – Destructuring](https://www.gencayyildiz.com/blog/ecmascript-6-destructuring/) - Gencay Yıldız
 - [ES6 Destructuring nedir? Nasıl kullanılır?](https://indatawetrust.blogspot.com/2016/02/es6-destructuring-nedir-nasil-kullanilir.html) - Ahmet Şimşek

## Sınıf (Class)

 - [constructorsden classlara  - ECMAScript 6 - Türkçe Doküman](https://omergulcicek.github.io/es6/es6-temel-ozellikleri/constructorsden-classlara) - Ömer Gülçiçek
 - [JavaScript ES6 Classes](https://www.yusufsezer.com.tr/javascript-es6-classes/) - Yusuf Sezer
 - [ES6 Class nedir? Nasıl kullanılır?](https://indatawetrust.blogspot.com/2016/02/es6-class-nedir-nasil-kullanilir.html) - Ahmet Şimşek
 - [Javascript’de class tanımlama ve diğer class işlemleri](http://www.muratoner.net/javascript/javascriptde-class-tanimlama-ve-diger-class-islemleri) - Murat Öner
 - [ecmascript class ders](https://www.youtube.com/watch?v=syxq-kWp91s&vl=tr) - Dılo abinin yeri :video_camera:
 - [Javascript sınıf tanımlama](http://boraozer.com/2018/09/19/javascript-sinif-tanimlama/) - Bora Özer
 - [Javascript(ecmascript 6) Notları-class](https://youtu.be/BsewfjaJKFE) - Fatih Çakıroğlu :video_camera:
 - [Javascript Notları(ECMA6)-Miras alma](https://www.youtube.com/watch?v=vKxTKlllMMQ) - Fatih Çakıroğlu :video_camera:
 - [Class (Sınıf) Kavramı](https://www.e-adys.com/react-native/03-07-class-sinif-kavrami/) - Erdinç Uzun

## Genarator fonksiyonlar

- [JS Ders 12 Ecmascript 6 Generators Kullanımı](https://www.youtube.com/watch?v=4eagrgZ8nuM) - fehmiuyarnet :video_camera:
- [Generatörler ve asenkron fonksiyonlar](https://www.youtube.com/watch?v=L3zeriJutZA) - Uçbirim :video_camera:
- [ES6 generator ve ES7 async fonksiyonlar](https://kodcu.com/2017/06/es6-generator-ve-es7-async-fonksiyonlar/) - kodcu
- [JavaScript Fonksiyonları: Üretici Fonksiyonlar - Generator Functions](http://yazilim.cevapsitesi.com/Makaleler/68/javascript-fonksiyonlari-uretici-fonksiyonlar-generator-functions) - yazilim.cevapsitesi / canora
- [Es6 Generators nedir? Nasıl kullanılır?](https://indatawetrust.blogspot.com/2016/02/es6-generators-nedir-nasil-kullanilir.html) - Ahmet Şimşek
- [Generators](https://www.e-adys.com/react-native/03-06-generators/) - Erdinç Uzun

## Modüller (Modules)

 - 🚫 ES6 Import İfadesi ve Yöntemleri - buraktokak.com/es6-import-ifadesi-ve-yontemleri/ - Burak Tokak
 - [JS Ders 13 Ecmascript 6 Modules (Modüller)](https://www.youtube.com/watch?v=CpZqChqJk8E) - fehmiuyarnet :video_camera:
 - [ES6 modules nedir? Nasıl kullanılır?](https://indatawetrust.blogspot.com/2016/03/es6-modules-nedir-nasil-kullanilir.html) - Ahmet Şimşek
 - 🚫 Ecmascript 6 Modül Sistemi - mehmetmasa.com.tr/javascript-dersleri/ecmascript-6-modul-sistemi/ - Mehmet Maşa
 - [ECMAScript – Module.exports ve Require Komutları](https://www.gencayyildiz.com/blog/ecmascript-module-exports-ve-require-komutlari/) - Gencay Yıldız
 - [Modules](https://www.e-adys.com/react-native/03-08-modules/) - Erdinç Uzun

## Promise

 - [JavaScript ES6 Promise](https://www.yusufsezer.com.tr/javascript-es6-promise/) - Yusuf Sezer
 - [JavaScript Promise](https://medium.com/@emrahday/js-promise-cff34a0df761) - Emrah
 - [Promise ile Asekron Javascript Kullanımı Nasıl Yapılır ?](https://www.youtube.com/watch?v=MBexO0Cfh3c) - Sadık Turan :video_camera:
 - [JS Ders 17 Ecmascript 6 Promise Nesnesi](https://www.youtube.com/watch?v=8RQzw4hA-p0) - fehmiuyarnet :video_camera:
 - [javascript Promise ile async işlemler - ders 25](https://www.youtube.com/watch?v=bIiA_E6HNc0) - Dılo abinin yeri :video_camera:
 - [Javascript’te Promise Kullanımı](https://medium.com/codefiction/javascriptte-promise-kullan%C4%B1m%C4%B1-ccca1123989a) - Özgün Bal
 - [Javascript Promise nedir ?](https://www.youtube.com/watch?v=RYoA61va9og) - Fatih Çakıroğlu :video_camera:
 - [ECMAScript 6 – Promise Yapısı](https://www.gencayyildiz.com/blog/ecmascript-6-promise-yapisi/) - Gencay Yıldız
 - [ECMAScript 6 – Async / Await Keywordleri](https://www.gencayyildiz.com/blog/ecmascript-6-async-await-keywordleri/) - Gencay Yıldız
 - [Javascript ile Asenkron İşlemler](https://batikansenemoglu.com/javascript-ile-asenkron-islemler/) - Batıkan Senemoğlu
 - [Özgün Bal - Javascript'te Promise Kullanımı](https://www.youtube.com/watch?v=40YcabXaRTc) - Codefiction / Özgün Bal :video_camera:
 - [Javascript’te Promise Kullanımı](http://erdoganb.com/2017/10/javascriptte-promise-kullanimi/) - Erdoğan Bavaş
 - [Callback, Promise ve Async](https://youtu.be/3x2s2Bk2y4k) - Uğur AKTAŞ :video_camera:
 - :star: [JavaScript ES7 async await](https://www.yusufsezer.com.tr/javascript-es7-async-await/) - Yusuf Sezer

## Sembol (Symbol)

 - [ES6 Symbol](https://medium.com/@emrahday/es6-symbol-d7d0fd99e2d4) - Emrah
 - [ES6: Semboller](https://www.youtube.com/watch?v=TcpDqUcAP1s) - Uçbirim :video_camera:
 - [ES6: Semboller](https://medium.com/@selmansamet/es6-semboller-33f5308c1355) -  selmansamet

## Set Nesnesi

 - [JS Ders 14 Ecmascript 6 Set Nesnesi Kullanımı](https://www.youtube.com/watch?v=JY4I38YAj3Y) - fehmiuyarnet :video_camera:
 - [ES6: Map ve Set tipleri](https://www.youtube.com/watch?v=AzrJqLCKRss) - Uçbirim :video_camera:
 - [ES6 Map + Set + WeakMap + WeakSet nedir? Nasıl kullanılır?](https://indatawetrust.blogspot.com/2016/03/es6-map-set-weakmap-weakset-nedir-nasil-kullanilir.html) - Ahmet Şimşek
 - [Map ve Set](https://www.e-adys.com/react-native/03-14-map-ve-set/) - Erdinç Uzun

## Map ve WeakMap Nesneleri

 - [JS Ders 15 Ecmascript 6 Map ve WeakMap Nesnelerinin Kullanımı](https://www.youtube.com/watch?v=OQOJuPjiWj0) - fehmiuyarnet :video_camera:
 - [ES6: Map ve Set tipleri](https://www.youtube.com/watch?v=AzrJqLCKRss) - Uçbirim :video_camera:
 - [ES6 Map + Set + WeakMap + WeakSet nedir? Nasıl kullanılır?](https://indatawetrust.blogspot.com/2016/03/es6-map-set-weakmap-weakset-nedir-nasil-kullanilir.html) - Ahmet Şimşek
 - [Map ve Set](https://www.e-adys.com/react-native/03-14-map-ve-set/) - Erdinç Uzun

## Proxy 

 - [JS Konseptleri #1: Proxy Nedir ve Kullanım Alanları Nelerdir?](https://www.kodportali.com/yazilim/javascript/js-konseptleri-proxy-nedir-ve-kullanim-alanlari-nelerdir/) - Kod Portali / Muhammet Ali Can
 - [ES6 Proxies](https://www.e-adys.com/react-native/03-16-es6-proxies/) - Erdinç Uzun
 - [JavaScript ve Observer İşlemleri](https://aligoren.com/javascript-ve-observer-islemleri/) - Ali Gören

## Ücretli Eğitimler

 - [EcmaScript6 (ES6) İle JavaScript Yenilikleri](https://www.udemy.com/ecmascript6-es6-ile-javascript-yenilikleri/) - Selman UZUN :video_camera:
 - [Komple Modern JavaScript Kursu - ES6+ (2019)](https://www.udemy.com/sfrdan-ileri-seviyeye-modern-javascript-kursu/) - Mustafa Murat Coşkun :video_camera:
 - [Modern Javascript Kursu: ES6/ES7+ (2019)](https://www.udemy.com/modern-javascript-kursu/) - Sadık Turan :video_camera:
 - [Sıfırdan JavaScript Eğitimi: Oyun Projesi ve ES6 İçerir!](https://www.udemy.com/javascripti-sfrdan-ogrenin-oyun-projesi-ve-es6-icerir/) - Sultan Kalkan :video_camera:
 - [Sıfırdan Her Yönüyle JavaScript & Node.JS](https://www.udemy.com/nodejs-egitimi/) - Mehmet Seven :video_camera:
 - [JavaScript ile Temel Programlama ve İleri Seviye JavaScript](https://www.udemy.com/javascript-ile-temel-programlama-ve-ileri-seviye-javascript/) - Doğukan Güven Nomak, Fatih Kadir Akın :video_camera:
