---
layout: default
title: Bir Kılavuz Yazarak Katkıda Bulunmak
permalink: katki
---

# Kılavuz Ekleyerek Katkıda Bulunmak

Kılavuzlar sitesi [jekyll](https://github.com/mojombo/jekyll) ile çalışır ve tüm belgeler [markdown](http://daringfireball.net/projects/markdown/) kullanılarak yazıldı. Bir kılavuz eklemek için, sadece aşağıdaki adımları takip etmeniz gerekir.

  1. [Github'daki repoyu](https://github.com/railsgirls/railsgirls.github.com) "Fork" butonuna tıklayarak hesabınıza kopyalayın.
  2. Hesabınıza kopyaladığınız repoyu `git clone` ile bilgisayarınıza kopyalayın.
  3. Lokalinizdeki kopyanın içindeki `_posts` dizinin içine `YYYY-MM-DD-rehber_adi.markdown` adında bir dosya oluşturun.
  4. Bu dosyanın tepesine YAML formatında olan aşağıdaki satırları eklemeniz gerekiyor. Bunlar bakmakta olduğunuz rehberden alınmıştır:
    
    <pre>---
layout: default
title: Contributing a Guide
permalink: contributing
---</pre>

  5. Bu yeni rehberi git reponuza ekleyin (commit edin).

  6. Eklemeden (committen) sonra, bunu hesabınızdaki repoya gönderin (push edin).
  7. Şimdi rehberinizin açıklaması ile beraber bir çekme isteği (pull request) açabilirsiniz. İşte bu kadar!

[Rails Girls App Tutorial](https://github.com/railsgirls/railsgirls.github.com/blob/master/_posts/2012-04-18-app.markdown)'daki yapıyı takip edebilirsiniz.

Rails Girls'ü harika hale getirmek için zaman ayırdığınız için çok teşekkür ederiz.
