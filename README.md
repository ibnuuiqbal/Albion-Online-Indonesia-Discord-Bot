# 🇮🇩 Albion Online Discord Bot (MABAR) - Professional Guild Management System

[![Status Bot](https://img.shields.io/badge/Status-Aktif%20di%20Discord-4E9A06?style=for-the-badge&logo=discord)](https://github.com/ibnuuiqbal/Albion-Online-Indonesia-Discord-Bot)
[![Lisensi](https://img.shields.io/badge/License-Proprietary%20(Private)-red?style=for-the-badge)](https://github.com/ibnuuiqbal/Albion-Online-Indonesia-Discord-Bot)
[![Node.js](https://img.shields.io/badge/Node.js-v16.x+-339933?style=for-the-badge&logo=node.js)](https://nodejs.org/)

<p align="center">
  <img src="https://github.com/ibnuuiqbal/readme-assets/blob/main/bannerawal.png?raw=true" alt="Logo Bot MABAR" width="800">
</p>

**Mabar Assistant** adalah solusi All-in-One tercanggih untuk manajemen Guild Albion Online. Bot ini bukan sekadar penyedia informasi, melainkan sistem manajemen operasional lengkap yang mengintegrasikan Ekonomi Mikro, Kedisiplinan Militer (CTA), Diplomasi (NAP), Killboard Visual Otomatis, Artificial Intelligence, Hideout ROA rute otomatis ,serta fitur Social Engagement untuk membangun komunitas guild yang lebih solid dan transparan.

<p align="center">
  <img src="https://github.com/ibnuuiqbal/readme-assets/blob/main/Screenshot_11.png?raw=true" alt="Preview Bot MABAR" width="800" height="400">
</p>

## 🛡️ Ingin Bergabung atau Menggunakan Bot Kami?

<img src="https://github.com/ibnuuiqbal/readme-assets/blob/main/mabar.png?raw=true" alt="Logo Guild MABAR" width="100" height="100">

Bot ini dikembangkan khusus untuk Discord kami (**Mabar**).

Kami menyambut pemain Albion Online lainnya! Jika Anda tertarik untuk **Mabar Bersama** atau ingin melihat bot ini beraksi, silakan bergabung dengan Publik server Discord kami:

[➡️ **KLIK DI SINI UNTUK GABUNG SERVER DISCORD KAMI** ⬅️](https://discord.gg/h7UcseapeH)

---

## 🚀 Fitur Unggulan & Automasi (Update 2026)
Bot ini ditenagai oleh *background scheduler* canggih yang berjalan secara otonom 24/7 untuk memastikan guild berjalan lancar tanpa campur tangan manual terus-menerus:

* **🛡️ Smart Role Sync & Strike System:** Otomatis mendeteksi jika member keluar guild in-game dan mencabut role Discord mereka. Dilengkapi *Safety Valve* dan *Strike System* (toleransi 5x gagal) untuk mencegah pencabutan role massal saat API Albion sedang *down*, serta fitur auto-rename jika member mengganti *nickname* in-game.
* **⚔️ Real-time Parallel Killboard:** Mengambil data Killboard dari API Albion secara simultan setiap 15 detik, memproses "Whale/Juicy Kill", dan melakukan *auto-posting* visualisasi gambar ke channel Discord.
* **🧠 AI Albion Insight Broadcaster:** Menyiarkan *lore*, fakta rahasia, dan panduan dunia Albion secara otomatis dengan durasi acak (6-12 jam) menggunakan integrasi AI.
* **⏱️ Interactive Smart Alarm:** Sistem pengingat otomatis yang memanggil user secara langsung dengan tampilan *embed* visual saat waktu *timer* atau objektif telah habis.
* **🔄 Robust Recovery System:** Melakukan pembersihan tiket kadaluwarsa dan pemulihan data pendaftaran party secara otomatis setiap 30 menit, menjaga data tetap aman meskipun bot atau VPS melakukan *restart*.
* **📅 Scheduled Guild Events:** Automasi rotasi pemilihan Role MVP setiap hari Minggu, Giveaway harian di jam 17:00, dan pemotongan pajak (*automatic tax*) setiap 4 hari sekali.
* **Hybrid Economy:** Integrasi saldo Cash, Bank Pribadi, dan Bank Guild yang saling terhubung untuk ekosistem finansial internal Discord.

---

## 📜 Daftar Lengkap Slash Commands (Update 2026)

### ⚔️ Kategori: Pengelolaan Mabar & Party
Command untuk open konten, registrasi, dan pengelolaan party.
* `/konten` — Command utama untuk open konten party.
* `/kontenstats` — Statistik performa konten.
* `/rankmabar` — Lihat ranking dan statistik partisipasi internal.
* `/hideout` — Update rute hideout + Core Info.
* `/splitloot` — Hitung pembagian loot party.
* `/nap` — Kelola guild kawan (Non-Aggression Pact).
* `/regear` — Request Regear item.

### 📊 Kategori: Analisis Guild & PvP Tracker
Command untuk cek killboard, statistik guild, dan data kompetitif.
* `/albionprofile` — Cek profile karakter & statistik Fame.
* `/roa` — Scanner Map Road of Avalon.
* `/avaraid` — Panduan Raid Boss Avalonian.
* `/scout` — Kirim laporan scout wilayah.
* `/season` — Cek status Season dan reward.

### 💰 Kategori: Finansial & Banking
Command untuk mengelola saldo, transaksi virtual, dan investasi.
* `/subsidi` — Subsidi silver untuk member.
* `/balance` — Cek saldo Cash, Bank, dan Deposit/Withdraw.
* `/daily` — Ambil bonus harian.
* `/invest` — Investasikan & Claim silver untuk bunga (24 jam).
* `/donasi` — Donasikan cash ke bank guild.
* `/guildbalance` — Lihat saldo bank guild (Treasury).
* `/siphon` — Managemen Siphoned Energy.
* `/rob` — Merampok user lain (berisiko gagal/denda).
* `/satpam` — Sewa Satpam untuk perlindungan rob.

### 🤝 Kategori: Koperasi & Simpan Pinjam
Sistem manajemen hutang-piutang antar anggota Guild.
* `/hutang` — Menu utama hutang (Bayar, Tagih, Cek, Lunas).

### 🎯 Kategori: Minigame & Bounty
Command untuk petualangan, mini-game, dan sistem perburuan.
* `/adventure` — Petualangan RPG dengan reward.
* `/confess` — Kirim pesan rahasia anonim.
* `/fishing` — Minigame memancing Albion.
* `/trivia` — Mainkan trivia bertema Albion.
* `/gamble` — Slot machine mini-game.
* `/kocok` — Command kocok acak (nama/angka).
* `/albionmeme` — Meme Albion dari Reddit.
* `/stats` — Statistik permainan kamu.
* `/bounty` — Cek daftar buronan (bounty) aktif.

### ⭐ Kategori: Fitur Special
Command untuk informasi game, bot, dan user.
* `/combatfame` — Fame Kalkulator.
* `/lore` — Sejarah Albion Online.
* `/price` — Cek harga item Albion (Market Data).
* `/gold` — Cek harga Gold Albion saat ini.
* `/premium` — Cek harga Premium Albion.
* `/resource` — Informasi Bonus Crafting Kota.
* `/build` — Random Build Albion / Simpan Build.
* `/rute` — Cek rute farming/ganking terbaik.
* `/userinfo` — Info detail user Discord.
* `/profile` — Info Profile akun bot kamu.
* `/randomfact` — Fakta acak Albion Online.
* `/timezone` — Cek waktu UTC saat ini.
* `/timer` — Sistem pengingat waktu & objective.
* `/roll` — Roll dadu 1–100.
* `/poll` — Membuat polling suara.
* `/saran` — Berikan saran fitur ke developer bot.
* `/register` — Daftarkan nickname Albion ke bot.
* `/serverinfo` — Informasi server Discord ini.

### ⚙️ Kategori: Moderasi & Staff Tools
⚠️ **Khusus Role Staff/Admin** untuk manajemen bot dan guild.

**🛡️ Admin Utama**
* `/admin economy setbalance` — Atur saldo user/guild (Owner).
* `/admin economy tax` — Potong pajak massal.
* `/admin economy sweep` — Bersihkan saldo non-member.
* `/admin user point` — Kelola poin user (Give/Set/Remove).
* `/admin user caller` — Kelola status caller.
* `/admin blacklist` — Tambah/Hapus user blacklist.

**🛠️ Guild Management**
* `/setup-killboard` — Konfigurasi channel killboard.
* `/cta` — Lacak absensi cta+ Auto DM ke orang yang tidak ikut cta.
* `/jadwal` — Kelola jadwal mabar guild.
* `/giveaway` — Mulai giveaway silver otomatis.
* `/sendregister` — Kirim ulang panel registrasi.
* `/chat` — Kirim pesan menggunakan bot.

## 📸 Galeri Fitur Bot

| **⚔️ Killboard System** | **📝 Register System** |
| :---: | :---: |
| <img src="https://github.com/ibnuuiqbal/readme-assets/blob/main/foto-2026/killboard.png?raw=true" width="100%"> | <img src="https://github.com/ibnuuiqbal/readme-assets/blob/main/foto-2026/register-system.png?raw=true" width="100%"> |
| *Tracking K/D Real-time (Albion API)* | *Sistem Registrasi & Verifikasi IGN* |

<br>

| **📢 Party Management** | **⭐ Rating System** |
| :---: | :---: |
| <img src="https://github.com/ibnuuiqbal/readme-assets/blob/main/foto-2026/Screenshot_12.png?raw=true" width="100%"> | <img src="https://github.com/ibnuuiqbal/readme-assets/blob/main/foto-2026/Screenshot_8.png?raw=true" width="100%"> |
| *Manajemen Ping Konten* | *Sistem Rating & Feedback Leader / Party* |
## 🛡️ Lisensi & Kontak Jual/Sewa

Source code bot ini bersifat **Proprietary**. Bot ini adalah solusi profesional bagi Guild yang ingin meningkatkan manajemen secara otomatis tanpa ribet.

* **Sewa Bulanan:** Instalasi cepat di server Anda tanpa perlu ribet urus VPS.
* **Beli Source Code:** Hak milik penuh atas seluruh file, bebas modifikasi, dan hosting mandiri.

**Tertarik? Hubungi Lead Developer:**
[➡️ **GABUNG SERVER DISCORD MABAR** ⬅️](https://discord.gg/h7UcseapeH)

---
<p align="center">
  Dibuat dengan ❤️ oleh <strong>Ibnuuiqbal (JokoSmilch)</strong><br>
  <i>Inspirasi: Temen Assistance oleh pxndameong & Freezer Cool</i>
</p>
