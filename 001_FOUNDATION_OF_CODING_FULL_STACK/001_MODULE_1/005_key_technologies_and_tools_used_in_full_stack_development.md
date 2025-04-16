# Yazılım Dilleri (Coding Languages)

Yazılımcıların bilgisayarlara ne yapmaları gerektiğini anlatmak için kullandığı araçlardır.

---

# Ön Yüz (Front-End) Teknolojileri

## Yazılım Dilleri

### HTML

- **Element (Öğe)**: Açılış etiketi, içerik ve kapanış etiketinden oluşan yapıdır.
- **Tag (Etiket)**: HTML öğelerini tanımlayan köşeli parantez içindeki yapılardır.
- **Attribute (Özellik)**: HTML etiketlerine ek bilgi sağlayan anahtar-değer çiftidir.

| Terim         | Tanım                                                          | Örnek                                                                |
| ------------- | -------------------------------------------------------------- | -------------------------------------------------------------------- |
| **Element**   | Başlangıç etiketi, içerik ve bitiş etiketinden oluşan yapıdır. | `<p>Hello</p>` – Bu bir paragraf elementidir.                        |
| **Tag**       | HTML elemanını tanımlayan köşeli parantez içindeki ifadedir.   | `<p>` (açılış tag'i), `</p>` (kapanış tag'i)                         |
| **Attribute** | Etikete ek bilgi sağlayan anahtar-değer çiftidir.              | `<a href="https://example.com">Link</a>` – `href` bir attribute’tür. |

---

### CSS

- **Selector (Seçici)**: Hangi HTML elemanına stil uygulanacağını belirler.
- **Property (Özellik)**: Verilecek stilin ne tür bir özellik olduğunu ifade eder.
- **Value (Değer)**: Özelliğe atanacak değeri belirtir.

| Terim        | Tanım                                          | Örnek                               |
| ------------ | ---------------------------------------------- | ----------------------------------- |
| **Selector** | Hangi HTML elemanının stilleneceğini belirler. | `p` – Tüm `<p>` etiketlerini seçer. |
| **Property** | Stil vermek istediğimiz özelliktir.            | `color`, `font-size`, `margin` vb.  |
| **Value**    | Özelliğe (property) verilen değerdir.          | `red`, `16px`, `10px` gibi          |

**Tam bir CSS örneği:**

```css
p {
  color: red;
  font-size: 16px;
}
```

Bu örnekte:
- `p` selector'dür.
- `color` ve `font-size` property'dir.
- `red` ve `16px` value'dur.

---

### JavaScript: Statement ve Expression

- **Statement (İfade)**: Belirli bir işlemi gerçekleştiren, bağımsız çalışabilen komutlardır.
- **Expression (İfade)**: Her zaman bir değer döndüren yapılardır. Genellikle bir ifadenin parçası olarak kullanılırlar.

| Terim         | Tanım                                                                  | Örnek                                               |
| ------------- | ---------------------------------------------------------------------- | ---------------------------------------------------- |
| **Statement** | Bir işlemi gerçekleştiren tam bir komuttur.                           | `let x = 5;`, `if (x > 3) { alert("Hi"); }`          |
| **Expression**| Bir değer üreten yapıdır. Diğer ifadelerin içinde de kullanılabilir.  | `3 + 4`, `x * 2`, `"Hello".toUpperCase()` gibi       |

**Açıklama:**
- **Statement** çalıştığında bir iş yapar ama mutlaka bir değer döndürmek zorunda değildir.
- **Expression** ise mutlaka bir değer döner.

**JavaScript Örneği:**

```javascript
let x = 10;       // Statement
y = x + 5;        // Expression statement
console.log(y);   // Statement, ama içinde expression var
```

Bu örnekte:
- `let x = 10;` bir statement'tır.
- `x + 5` bir expression'dır.
- `console.log(y);` bir statement olup, parametre olarak expression alır.

---

## Framework Nedir?

Kod yazarken kullanılan, önceden oluşturulmuş yapılardır. Geliştiricilere projelerini daha düzenli ve hızlı bir şekilde geliştirme imkânı tanır.

**Popüler Framework'ler:** React, Angular, Vue

## Kütüphane (Library) Nedir?

Sıkça kullanılan fonksiyonların, bileşenlerin veya metodların bir araya getirildiği hazır kod bloklarıdır. Belirli görevleri yerine getirmek için kullanılırlar.

**Popüler Kütüphaneler:**
- `React.js`
- `Vue.js`
- `Node.js`

