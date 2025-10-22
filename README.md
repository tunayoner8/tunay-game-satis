# Tunay Game Satış (Ücretsiz Demo Mağaza + Admin Panel)

Bu proje, **Vite + React + Tailwind** ile hazırlanmış ücretsiz bir demo mağazadır.
- Kategoriler: **UCE**, **Hesap**, **Klan**
- Özellikler: Ürün listeleme, ürün detay, sepet, sahte ödeme/sipariş oluşturma, **admin paneli** (ürün & sipariş yönetimi)
- **Veriler localStorage**'da saklanır (ücretsiz ve anında çalışır).

## Hızlı Başlangıç (Bilgisayarda)
1) Bilgisayarda **Node.js 18+** kurulu olsun.
2) Proje klasörüne girin ve aşağıdakileri çalıştırın:
```bash
npm install
npm run dev
```
3) Tarayıcıda `http://localhost:5173` açın.

### Admin Girişi
- E-posta: `admin@tunaygames.com`
- Şifre: `Admin123!`

## Ücretsiz Yayınlama (Vercel)
1) vercel.com hesabı açın (ücretsiz).
2) "New Project" → "Import" → Bu projeyi GitHub'a yükleyip bağlayın **veya** Vercel'in "Deploy" ekranında kendi repo'nuzu seçin.
3) **Build Command:** `npm run build` — **Output Dir:** `dist`
4) Deploy'a basın. 1-2 dk içinde canlı olur.

> **Not:** LocalStorage tabanlı olduğu için çok kullanıcılı üretim senaryosu için uygun değildir. İsterseniz Firestore/Supabase gibi tamamen ücretsiz veritabanlarına geçiş yapılabilir. (İsteğe bağlı yönergeler eklenebilir.)

## Görsel Ekleme
Admin panelinde **Görsel URL** alanına doğrudan bağlantı ekleyebilirsiniz. Telif haklarına dikkat edin.
