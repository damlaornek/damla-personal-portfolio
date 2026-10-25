# Damla — Kişisel Portföy

HTML5, CSS3 ve vanilla JavaScript ile hazırlanmış, Türkçe, responsive ve erişilebilir kişisel portföy sitesi. İlk sürüm statiktir; Node.js veya API anahtarı gerektirmez ve GitHub Pages ile yayımlanabilir.

## Dosya yapısı

```text
damla-portfolio-clean/
├── index.html
├── css/style.css
├── js/script.js
└── README.md
```

## Yerel olarak görüntüleme

`index.html` dosyasını tarayıcıda açabilir veya VS Code Live Server kullanabilirsin. Site statik olduğu için Node.js gerekmez.

## GitHub'a yükleme

1. GitHub'da yeni bir repository oluştur. Önerilen ad: `damla-portfolio-clean`.
2. README, `.gitignore` veya lisans ekleme seçeneklerini seçme; bu klasörde zaten README var.
3. Bu klasörü VS Code ile aç ve terminalde şu komutları çalıştır:

```powershell
git init
git add .
git commit -m "Create clean personal portfolio"
git branch -M main
git remote add origin https://github.com/damlaornek/damla-portfolio-clean.git
git push -u origin main
```

Depo adresin farklıysa `origin` adresini GitHub'daki yeni deponun Code bölümünden kopyaladığın adresle değiştir.

## GitHub Pages ile yayımlama

1. GitHub deposunda **Settings → Pages** sayfasını aç.
2. **Build and deployment → Source** alanında `Deploy from a branch` seç.
3. Branch olarak `main`, klasör olarak `/(root)` seçip **Save** düğmesine bas.
4. Birkaç dakika sonra `https://damlaornek.github.io/damla-portfolio-clean/` adresinden kontrol et.

## İçerik düzenleme

- Metinler ve bağlantılar: `index.html`
- Görünüm: `css/style.css`
- Mobil menü ve yıl bilgisi: `js/script.js`

## Güvenlik notu

Bu statik sürümde sunucu veya API anahtarı bulunmaz. Gelecekte AI API entegrasyonu eklenirse API anahtarını istemci tarafındaki HTML/JavaScript içine koyma; sunucu tarafında sakla.

## Kullanılan teknolojiler

HTML5 semantic elements, CSS3 responsive layout, vanilla JavaScript.
