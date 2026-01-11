<!DOCTYPE html>
<html lang="tr">
  <head>
    <meta charset="UTF-8" />
    <title>goit-react-hw-01 | React Bileşenler</title>
  </head>
  <body>
    <h1>📘 goit-react-hw-01 — React: Bileşenler</h1>

    <h2>📌 Proje Açıklaması</h2>
    <p>
      Bu proje, React’in temel kavramlarından biri olan <b>bileşen (component)</b>
      yapısını öğrenmek ve uygulamak amacıyla hazırlanmıştır.
      Projede kullanıcı profili, arkadaş listesi ve işlem geçmişi gibi
      farklı arayüz bileşenleri oluşturulmuş ve tek bir sayfada
      <code>&lt;App&gt;</code> bileşeni altında render edilmiştir.
    </p>

    <h2>🔗 Canlı Proje ve Kaynak Kod</h2>
    <ul>
      <li>
        <b>GitHub Repository:</b>
        <a href="https://github.com/kutluhangil/goit-react-hw-01" target="_blank">
          https://github.com/kutluhangil/goit-react-hw-01
        </a>
      </li>
      <li>
        <b>Canlı Demo (Vercel):</b>
        <a href="https://goit-react-hw-01.vercel.app" target="_blank">
          https://goit-react-hw-01.vercel.app
        </a>
      </li>
    </ul>

    <h2>⚙️ Kullanılan Teknolojiler</h2>
    <ul>
      <li>React</li>
      <li>Vite</li>
      <li>JavaScript (ES6+)</li>
      <li>CSS Modules</li>
      <li>Prettier</li>
    </ul>

    <h2>📁 Proje Yapısı</h2>
    <pre>
src/
 ├── components/
 │   ├── Profile/
 │   │   ├── Profile.jsx
 │   │   └── Profile.module.css
 │   ├── FriendList/
 │   │   ├── FriendList.jsx
 │   │   └── FriendList.module.css
 │   ├── FriendListItem/
 │   │   ├── FriendListItem.jsx
 │   │   └── FriendListItem.module.css
 │   ├── TransactionHistory/
 │   │   ├── TransactionHistory.jsx
 │   │   └── TransactionHistory.module.css
 │   └── App/
 │       ├── App.jsx
 │       └── App.module.css
 ├── userData.json
 ├── friends.json
 ├── transactions.json
 └── main.jsx
    </pre>

    <h2>✅ Genel Gereksinimler</h2>
    <ul>
      <li>Proje Vite kullanılarak oluşturulmuştur.</li>
      <li>Uygulama Vercel üzerinde başarıyla deploy edilmiştir.</li>
      <li>Tarayıcı konsolunda herhangi bir hata veya uyarı bulunmamaktadır.</li>
      <li>Tüm bileşenler <code>src/components</code> klasörü altında düzenlenmiştir.</li>
      <li>Her bileşen için ayrı JSX ve <code>.module.css</code> dosyaları kullanılmıştır.</li>
      <li>Bileşenler varsayılan dışa aktarma (<code>export default</code>) ile aktarılmıştır.</li>
      <li>Tüm bileşenler <code>&lt;App&gt;</code> bileşeni içerisinde render edilmiştir.</li>
      <li>Props’lar doğru ve eksiksiz şekilde iletilmiştir.</li>
      <li>Kod Prettier ile formatlanmıştır.</li>
      <li>Stil yönetimi CSS Modules ile yapılmıştır.</li>
    </ul>

    <h2>🧩 Görev 1 — Sosyal Medya Profili</h2>
    <p>
      <code>&lt;Profile&gt;</code> bileşeni, kullanıcıya ait profil bilgilerini
      prop’lar aracılığıyla alır ve ekranda gösterir.
    </p>
    <ul>
      <li>name — Kullanıcı adı</li>
      <li>tag — Kullanıcı etiketi</li>
      <li>location — Konum bilgisi</li>
      <li>image — Avatar bağlantısı</li>
      <li>stats — Followers, views ve likes bilgileri</li>
    </ul>
    <p>
      Kullanıcı verileri <code>userData.json</code> dosyasında saklanmış ve
      App bileşeninde içe aktarılmıştır.
    </p>

    <h2>👥 Görev 2 — Arkadaş Listesi</h2>
    <p>
      <code>&lt;FriendList&gt;</code> bileşeni, arkadaş nesnelerinden oluşan
      bir diziyi prop olarak alır ve her arkadaş için
      <code>&lt;FriendListItem&gt;</code> bileşenini render eder.
    </p>
    <ul>
      <li>avatar — Avatar görseli</li>
      <li>name — Arkadaş adı</li>
      <li>isOnline — Çevrimiçi durumu</li>
    </ul>
    <p>
      Online durumuna göre metin ve renk CSS sınıfları ile kontrol edilmiştir.
      Arkadaş verileri <code>friends.json</code> dosyasında tutulmaktadır.
    </p>

    <h2>💳 Görev 3 — İşlem Geçmişi</h2>
    <p>
      <code>&lt;TransactionHistory&gt;</code> bileşeni, işlem verilerini tablo
      formatında görüntüler.
    </p>
    <ul>
      <li>type — İşlem türü</li>
      <li>amount — Tutar</li>
      <li>currency — Para birimi</li>
    </ul>
    <p>
      İşlem verileri <code>transactions.json</code> dosyasından alınarak
      App bileşenine prop olarak iletilmiştir.
    </p>

    <h2>🚀 Kurulum ve Çalıştırma</h2>
    <pre>
npm install
npm run dev
    </pre>

    <h2>📦 Production Build</h2>
    <pre>
npm run build
    </pre>

    <h2>👨‍💻 Geliştirici</h2>
    <p>
      Bu proje GoIT React eğitimi kapsamında hazırlanmıştır.
    </p>

    <p><b>React öğrenme yolculuğunun ilk adımı 🚀</b></p>
  </body>
</html>
