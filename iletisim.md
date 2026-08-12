---
layout: default
title: İletişim
permalink: /iletisim/
---

{% include signature.html %}
<h2>İletişim</h2>

<p class="entry-body">Yet Aydın'daki bir ilana yanıt vermek ya da genel olarak iletişime geçmek isterseniz, aşağıdaki formu kullanabilirsiniz.</p>

<div class="contact">
  <form action="https://formspree.io/f/xoeawllg" method="POST">
    <input type="text" name="name" placeholder="Ad Soyad" required>
    <input type="email" name="email" placeholder="E-posta" required>
    <select name="konu" required>
      <option value="" disabled selected>Konu seçin</option>
      <option value="ilan">Yet Aydın'daki bir ilana yanıt</option>
      <option value="genel">Genel iletişim</option>
    </select>
    <textarea name="message" placeholder="Mesajınız" required></textarea>
    <button type="submit">Gönder</button>
  </form>
</div>
