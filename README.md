# HERITAGEVAULT

![HERITAGEVAULT Logo](./Doc/Screenshot_20250503-174414_1.jpg)

HERITAGEVAULT adalah platform berbasis blockchain yang melestarikan warisan budaya Indonesia melalui digitalisasi artefak tradisional sebagai NFT pada jaringan Internet Computer Protocol (ICP). Dirancang khusus untuk Hackathon ICP Indonesia, proyek ini menggabungkan teknologi blockchain, AR (Augmented Reality), dan pelestarian budaya dalam aplikasi yang ramah pengguna.

## 🌟 Fitur Utama

### 1. Marketplace Terdesentralisasi untuk Artefak Budaya
- Jual-beli produk batik dan kerajinan tradisional
- Filter berdasarkan kategori, daerah asal, dan rentang harga
- Sistem peringkat dan ulasan untuk meningkatkan kepercayaan
- Dukungan royalti bagi para pengrajin tradisional
- Tampilan grid dan list untuk kemudahan eksplorasi

### 2. Pengalaman Augmented Reality (AR)
- Visualisasikan batik dalam lingkungan dunia nyata
- Pantau bagaimana motif batik menyatu dengan objek disekitar
- Bagikan pengalaman AR dan simpan sebagai gambar
- Mode layar penuh untuk pengalaman yang lebih immersive
- Info kontekstual tentang asal dan makna batik

### 3. Integrasi Blockchain ICP
- Koneksi wallet ICP yang aman (Internet Identity, Plug, Stoic)
- Dukungan multi-jaringan (mainnet, testnet, devnet)
- Verifikasi keaslian artefak melalui hash blockchain
- Transaksi terdesentralisasi untuk transparansi
- Aset digital bersertifikat NFT

### 4. Penyimpanan Permanen via IPFS/Pinata
- Metadata dan gambar disimpan secara terdesentralisasi
- Jaminan preservasi data jangka panjang
- Resistensi terhadap sensor dan modifikasi
- Hash verifikasi untuk memastikan integritas data
- Integrasi API Pinata untuk upload dan akses konten

## 💻 Teknologi

- **Frontend**: React.js, Tailwind CSS, ShadCN UI
- **Backend**: Express.js, PostgreSQL, Drizzle ORM
- **Blockchain**: Internet Computer Protocol (ICP)
- **Storage**: IPFS via Pinata
- **Augmented Reality**: WebAR, device camera API
- **Authentication**: Internet Identity, Plug wallet, Stoic wallet

## 🚀 Persyaratan

- Node.js v16+
- PostgreSQL
- Koneksi Internet
- Browser modern dengan dukungan WebAR
- Perangkat dengan kamera (untuk fitur AR)

## ⚙️ Instalasi & Penggunaan

1. Clone repositori:
   ```
   git clone https://github.com/yourusername/heritagevault.git
   cd heritagevault
   ```

2. Instal dependensi:
   ```
   npm install
   ```

3. Buat file `.env` dengan kredensial yang diperlukan:
   ```
   DATABASE_URL=postgresql://username:password@localhost:5432/heritagevault
   PINATA_API_KEY=your_pinata_api_key
   PINATA_SECRET_KEY=your_pinata_secret_key
   ```

4. Setup database:
   ```
   npm run db:push
   npm run db:seed
   ```

5. Jalankan aplikasi:
   ```
   npm run dev
   ```

6. Buka browser dan navigasikan ke:
   ```
   http://localhost:5000
   ```

## 🎯 Target Pengembangan

HERITAGEVAULT ditargetkan untuk memenuhi beberapa tujuan penting:

1. **Pelestarian Budaya**: Mendokumentasikan dan melestarikan batik dan kerajinan tradisional Indonesia dalam format digital permanen
2. **Pemberdayaan Pengrajin**: Memberikan platform bagi pengrajin tradisional untuk mendapatkan penghasilan dari karya mereka
3. **Edukasi**: Mengedukasi masyarakat tentang kekayaan budaya Indonesia
4. **Inovasi Teknologi**: Menunjukkan aplikasi praktis dari blockchain, AR, dan NFT dalam konteks pelestarian budaya

## 📱 Tampilan Aplikasi

### Antarmuka Marketplace
![Marketplace](./attached_assets/Screenshot_20250503-154814.jpg)

### Visualisasi 3D Artefak
![3D Viewer](./attached_assets/Screenshot_20250503-151115.jpg)

### Pengalaman Augmented Reality
![AR Experience](./attached_assets/Screenshot_20250503-162518.jpg)

### Koneksi Wallet ICP
![Wallet Integration](./attached_assets/Screenshot_20250503-163344.jpg)

## 🔗 Integrasi ICP

HERITAGEVAULT terintegrasi dengan Internet Computer Protocol melalui:

1. **Identitas Digital**: Autentikasi melalui Internet Identity
2. **Kontrak Cerdas**: Tokenisasi artefak sebagai NFT
3. **Pembayaran**: Transaksi menggunakan token ICP
4. **Verifikasi**: Validasi keaslian melalui hash blockchain

## 🤝 Kontribusi

Kontribusi sangat dihargai! Jika Anda tertarik untuk berkontribusi:

1. Fork repositori
2. Buat branch fitur (`git checkout -b feature/amazing-feature`)
3. Commit perubahan Anda (`git commit -m 'Add some amazing feature'`)
4. Push ke branch (`git push origin feature/amazing-feature`)
5. Buka Pull Request

## 📄 Lisensi

Proyek ini dilisensikan di bawah [MIT License](LICENSE).

## 🙏 Pengakuan

- Tim ICP Hackathon Indonesia
- Komunitas pengrajin tradisional Indonesia
- Semua library open-source yang digunakan dalam proyek
- [Internet Computer Protocol](https://internetcomputer.org/) untuk infrastruktur blockchain
- [Pinata](https://www.pinata.cloud/) untuk layanan IPFS

---

Dibuat dengan ❤️ untuk ICP Hackathon 13 Indonesia 2025
