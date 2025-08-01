# 📝 Commit Mesajı Kuralları

Bu projede anlamlı, tutarlı ve otomasyon dostu commit mesajları kullanıyoruz. Lütfen aşağıdaki kurallara uyun.

---

## 🎯 Biçim (Format)

```
<tip>(<alan>): <kısa açıklama>

<body> (opsiyonel, gerekirse detay)

<footer> (opsiyonel, örneğin issue referansı)
```

### 🔑 Örnekler

```
feat(auth): kullanıcı girişi eklendi

fix(ui): buton hizası düzeltildi

docs(readme): kullanım talimatları güncellendi

refactor(core): performans iyileştirildi

chore(deps): lodash versiyonu güncellendi

test(api): login endpoint için test eklendi

revert: önceki login özelliği geri alındı
```

---

## 📚 Kullanılabilecek `<tip>` Değerleri

| Tip       | Açıklama                                      |
|-----------|-----------------------------------------------|
| `feat`    | Yeni özellik                                  |
| `fix`     | Hata düzeltmesi                               |
| `docs`    | Dokümantasyon ile ilgili değişiklik           |
| `style`   | Formatlama, boşluk, noktalama vs.             |
| `refactor`| Yeniden yapılandırma, davranış değiştirmeden  |
| `perf`    | Performans iyileştirmesi                      |
| `test`    | Test ekleme veya düzeltme                     |
| `chore`   | Araç/geliştirme yapılandırmaları              |
| `revert`  | Önceki commit’i geri alma                     |

---

## 🛑 Kaçınılması Gerekenler

- ❌ `update code`, `fix bug`, `misc changes` gibi belirsiz mesajlar
- ❌ Tüm commit mesajını büyük harfle yazmak
- ❌ Mesajsız veya otomatik commit mesajları (`Update README.md` gibi)

---

## 🧠 Ekstra Kurallar

- Mesajlar **Türkçe** olabilir ama anlamlı olmalı.
- Ana mesaj 50 karakteri geçmemeli.
- Detay gerekiyorsa alt satıra ekleyin.
- Issue varsa mesaj sonunda belirtin:

```
Closes #42
```

---