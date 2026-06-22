# 🇮🇩 Albion Online Discord Bot (MABAR) - Professional Guild Management System

[![Status Bot](https://img.shields.io/badge/Status-Aktif%20di%20Discord-4E9A06?style=for-the-badge&logo=discord)](https://github.com/ibnuuiqbal/Albion-Online-Indonesia-Discord-Bot)
[![Lisensi](https://img.shields.io/badge/License-Proprietary%20(Private)-red?style=for-the-badge)](https://github.com/ibnuuiqbal/Albion-Online-Indonesia-Discord-Bot)
[![Node.js](https://img.shields.io/badge/Node.js-v16.x+-339933?style=for-the-badge&logo=node.js)](https://nodejs.org/)
[![Website](https://img.shields.io/badge/Website-albionindo.my.id-blue?style=for-the-badge&logo=google-chrome)](https://albionindo.my.id/bot/)

<p align="center">
  <img src="https://github.com/ibnuuiqbal/readme-assets/blob/main/foto-2026/bannerawal.png?raw=true" alt="Logo Bot MABAR" width="800">
</p>

**Mabar Assistant** adalah solusi All-in-One tercanggih untuk manajemen Guild Albion Online. Bot ini bukan sekadar penyedia informasi, melainkan sistem manajemen operasional lengkap yang mengintegrasikan Ekonomi Mikro, Kedisiplinan Militer (CTA), Diplomasi (NAP), Killboard Visual Otomatis, Artificial Intelligence, Hideout ROA rute otomatis, serta fitur Social Engagement untuk membangun komunitas guild yang lebih solid dan transparan.

<p align="center">
  <img src="https://github.com/ibnuuiqbal/readme-assets/blob/main/Screenshot_11.png?raw=true" alt="Preview Bot MABAR" width="800" height="400">
</p>

## 🛡️ Ingin Bergabung atau Menggunakan Bot Kami?

<img src="https://github.com/ibnuuiqbal/readme-assets/blob/main/foto-2026/bag.png?raw=true" alt="Logo Guild MABAR" width="100" height="100">

Bot ini dikembangkan khusus untuk Discord kami (**Mabar**).

Kami menyambut pemain Albion Online lainnya! Jika Anda tertarik untuk **Mabar Bersama**, ingin melihat bot ini beraksi, atau membaca dokumentasi lengkapnya, silakan kunjungi website resmi kami atau bergabung ke server Discord Publik kami:

🌐 **[KUNJUNGI WEBSITE RESMI BOT MABAR](https://albionindo.my.id/bot/)** 💬 **[GABUNG SERVER DISCORD KAMI](https://discord.gg/h7UcseapeH)**

---

## 🚀 Fitur Unggulan & Automasi (Update 2026)
Bot ini ditenagai oleh *background scheduler* canggih yang berjalan secara otonom 24/7 untuk memastikan guild berjalan lancar tanpa campur tangan manual terus-menerus:

* **🔨 Real-time Auction & Coaching System:** Sistem **Lelang (Auction)** interaktif untuk jual beli item langka antar member/guild, serta modul **VOD Review** untuk evaluasi gameplay member oleh Officer/Shotcaller.
* **🛡️ Smart Role Sync & Strike System:** Otomatis mendeteksi jika member keluar guild in-game dan mencabut role Discord mereka. Dilengkapi *Safety Valve* dan *Strike System* (toleransi 5x gagal) untuk mencegah pencabutan role massal saat API Albion sedang *down*, serta fitur auto-rename jika member mengganti *nickname* in-game.
* **⚔️ Real-time Parallel Killboard:** Mengambil data Killboard dari API Albion secara simultan setiap 15 detik, memproses "Whale/Juicy Kill", dan melakukan *auto-posting* visualisasi gambar ke channel Discord.
* **🧠 AI Albion Insight Broadcaster:** Menyiarkan *lore*, fakta rahasia, dan panduan dunia Albion secara otomatis dengan durasi acak (6-12 jam) menggunakan integrasi AI.
* **⏱️ Interactive Smart Alarm:** Sistem pengingat otomatis yang memanggil user secara langsung dengan tampilan *embed* visual saat waktu *timer* atau objektif telah habis.
* **🔄 Robust Recovery System:** Melakukan pembersihan tiket kadaluwarsa dan pemulihan data pendaftaran party secara otomatis setiap 30 menit, menjaga data tetap aman meskipun bot atau VPS melakukan *restart*.
* **📅 Scheduled Guild Events:** Automasi rotasi pemilihan Role MVP setiap hari Minggu, Giveaway harian di jam 17:00, dan pemotongan pajak (*automatic tax*) setiap 4 hari sekali.
* **Hybrid Economy:** Integrasi saldo Cash, Bank Pribadi, dan Bank Guild yang saling terhubung untuk ekosistem finansial internal Discord.

---

## 📜 DAFTAR LENGKAP SLASH COMMANDS

<details>
<summary><b>📋 TABLE OF CONTENTS — Klik untuk navigasi cepat ke semua command</b></summary>

<br>

### ⚔️ Kategori: Pengelolaan Mabar & Party
| # | Command | Deskripsi Singkat |
|---|---------|-------------------|
| 1 | [`/konten`](#-1-konten-open-konten-party) | Open konten party utama |
| 2 | [`/kontenstats`](#-2-kontenstats-statistik-performa-konten) | Statistik performa konten |
| 3 | [`/rankmabar`](#-3-rankmabar-ranking-dan-statistik-partisipasi) | Ranking & statistik partisipasi |
| 4 | [`/hideout`](#-4-hideout-update-rute-hideout-core-info) | Update rute hideout + Core Info |
| 5 | [`/splitloot`](#-5-splitloot-hitung-pembagian-loot) | Hitung pembagian loot party |
| 6 | [`/nap`](#-6-nap-kelola-guild-kawan-non-aggression-pact) | Kelola guild kawan (NAP) |
| 7 | [`/regear`](#-7-regear-request-regear-item) | Request Regear item |

### 📊 Kategori: Analisis Guild & PvP Tracker
| # | Command | Deskripsi Singkat |
|---|---------|-------------------|
| 8 | [`/vods`](#-8-vods-submit-vod-gameplay) | 📹 Submit VOD gameplay |
| 9 | [`/albionprofile`](#-9-albionprofile-cek-profile-karakter--statistik-fame) | Cek profile karakter & statistik Fame |
| 10 | [`/roa`](#-10-roa-scanner-map-road-of-avalon) | Scanner Map Road of Avalon |
| 11 | [`/avaraid`](#-11-avaraid-panduan-raid-boss-avalonians) | Panduan Raid Boss Avalonian |
| 12 | [`/scout`](#-12-scout-kirim-laporan-scout-wilayah) | Kirim laporan scout wilayah |
| 13 | [`/season`](#-13-season-cek-status-season-dan-reward) | Cek status Season dan reward |

### 💰 Kategori: Finansial & Banking
| # | Command | Deskripsi Singkat |
|---|---------|-------------------|
| 14 | [`/lelang`](#-14-lelang-sistem-lelang-item) | 🔨 Sistem lelang item |
| 15 | [`/subsidi`](#-15-subsidi-subsidi-silver-untuk-member) | Subsidi silver untuk member |
| 16 | [`/balance`](#-16-balance-cek-saluran-keuangan) | Cek saldo Cash, Bank, Deposit/Withdraw |
| 17 | [`/daily`](#-17-daily-ambil-bonus-harian) | Ambil bonus harian |
| 18 | [`/invest`](#-18-invest-investasikan-claim-silver) | Investasikan & Claim silver (24 jam) |
| 19 | [`/donasi`](#-19-donasi-donasikan-cash-ke-bank-guild) | Donasikan cash ke bank guild |
| 20 | [`/guildbalance`](#-20-guildbalance-lihat-saldo-bank-guild) | Lihat saldo bank guild (Treasury) |
| 21 | [`/siphon`](#-21-siphon-management-siphoned-energy) | Managemen Siphoned Energy |
| 22 | [`/rob`](#-22-rob-merampok-user-lain) | Merampok user lain (risiko) |
| 23 | [`/satpam`](#-23-satpam-sewa-satpam-untuk-perlindungan) | Sewa Satpam untuk perlindungan |

### 🤝 Kategori: Koperasi & Simpan Pinjam
| # | Command | Deskripsi Singkat |
|---|---------|-------------------|
| 24 | [`/hutang`](#-24-hutang-sistem-manajemen-hutang-piutang) | Sistem manajemen hutang-piutang |

### 🎯 Kategori: Minigame & Bounty
| # | Command | Deskripsi Singkat |
|---|---------|-------------------|
| 25 | [`/adventure`](#-25-adventure-petualangan-rpg-dengan-reward) | Petualangan RPG dengan reward |
| 26 | [`/confess`](#-26-confess-kirim-pesan-rahasia-anonim) | Kirim pesan rahasia anonim |
| 27 | [`/fishing`](#-27-fishing-minigame-memancing-albion) | Minigame memancing Albion |
| 28 | [`/trivia`](#-28-trivia-mainkan-trivia-bertema-albion) | Mainkan trivia bertema Albion |
| 29 | [`/gamble`](#-29-gamble-slot-machine-mini-game) | Slot machine mini-game |
| 30 | [`/kocok`](#-30-kocok-command-kocok-acak) | Command kocok acak (nama/angka) |
| 31 | [`/albionmeme`](#-31-albionmeme-meme-albion-dari-reddit) | Meme Albion dari Reddit |
| 32 | [`/stats`](#-32-stats-statistik-permainan-kamu) | Statistik permainan kamu |
| 33 | [`/bounty`](#-33-bounty-cek-daftar-buronan-bounty-aktif) | Cek daftar buronan (bounty) aktif |

### ⭐ Kategori: Fitur Special
| # | Command | Deskripsi Singkat |
|---|---------|-------------------|
| 34 | [`/play`](#-34-play-sistem-musik-albion-premium) | 🎵 Sistem Musik Albion (Premium) |
| 35 | [`/combatfame`](#-35-combatfame-fame-kalkulator) | Fame Kalkulator |
| 36 | [`/lore`](#-36-lore-sejarah-albion-online) | Sejarah Albion Online |
| 37 | [`/price`](#-37-price-cek-harga-item-albion) | Cek harga item Albion |
| 38 | [`/gold`](#-38-gold-cek-harga-gold-albion) | Cek harga Gold Albion |
| 39 | [`/premium`](#-39-premium-cek-harga-premium-albion) | Cek harga Premium Albion |
| 40 | [`/resource`](#-40-resource-informasi-bonus-crafting-kota) | Informasi Bonus Crafting Kota |
| 41 | [`/build`](#-41-build-random-build-albion-simpan-build) | Random Build / Simpan Build |
| 42 | [`/rute`](#-42-rute-cek-rute-farming-ganking-terbaik) | Cek rute farming/ganking terbaik |
| 43 | [`/userinfo`](#-43-userinfo-info-detail-user-discord) | Info detail user Discord |
| 44 | [`/profile`](#-44-profile-info-profile-akun-bot-kamu) | Info Profile akun bot kamu |
| 45 | [`/randomfact`](#-45-randomfact-fakta-acak-albion-online) | Fakta acak Albion Online |
| 46 | [`/timezone`](#-46-timezone-cek-waktu-utc-saat-ini) | Cek waktu UTC saat ini |
| 47 | [`/timer`](#-47-timer-sistem-pengingat-waktu-objective) | Sistem pengingat waktu & objective |
| 48 | [`/roll`](#-48-roll-roll-dadu-1-100) | Roll dadu 1–100 |
| 49 | [`/poll`](#-49-poll-membuat-polling-suara) | Membuat polling suara |
| 50 | [`/saran`](#-50-saran-berikan-saran-fitur-ke-developer) | Berikan saran fitur ke developer |
| 51 | [`/register`](#-51-register-daftarkan-nickname-albion-ke-bot) | Daftarkan nickname Albion ke bot |
| 52 | [`/serverinfo`](#-52-serverinfo-informasi-server-discord-ini) | Informasi server Discord ini |

### ⚙️ Kategori: Moderasi & Staff Tools
| # | Command | Deskripsi Singkat |
|---|---------|-------------------|
| 53 | [`/admin economy setbalance`](#-53-admin-economy-setbalance-atur-saldo-userguild) | Atur saldo user/guild (Owner) |
| 54 | [`/admin economy tax`](#-54-admin-economy-tax-potong-pajak-massal) | Potong pajak massal |
| 55 | [`/admin economy sweep`](#-55-admin-economy-sweep-bersihkan-saldo-non-member) | Bersihkan saldo non-member |
| 56 | [`/admin user point`](#-56-admin-user-point-kelola-poin-user) | Kelola poin user |
| 57 | [`/admin user caller`](#-57-admin-user-caller-kelola-status-caller) | Kelola status caller |
| 58 | [`/admin blacklist`](#-58-admin-blacklist-tambahhapus-user-blacklist) | Tambah/Hapus user blacklist |
| 59 | [`/setup-killboard`](#-59-setup-killboard-konfigurasi-channel-killboard) | Konfigurasi channel killboard |
| 60 | [`/cta`](#-60-cta-lacak-absensi-cta-ping-otomatis) | Lacak absensi CTA & Ping otomatis |
| 61 | [`/jadwal`](#-61-jadwal-kelola-jadwal-mabar-guild) | Kelola jadwal mabar guild |
| 62 | [`/giveaway`](#-62-giveaway-mulai-giveaway-silver-otomatis) | Mulai giveaway silver otomatis |
| 63 | [`/sendregister`](#-63-sendregister-kirim-ulang-panel-registrasi) | Kirim ulang panel registrasi |
| 64 | [`/chat`](#-64-chat-kirim-pesan-menggunakan-bot) | Kirim pesan menggunakan bot |

</details>

---

## 📖 DOKUMENTASI LENGKAP PER COMMAND

---

### ⚔️ 1. `/konten` — Open Konten Party

<details>
<summary><b>📖 Klik untuk membuka panduan lengkap command ini</b> 
  <span style="float: right;">
    <img src="https://img.shields.io/badge/Level-Member-4E9A06?style=flat-square">
    <img src="https://img.shields.io/badge/Difficulty-⭐-yellow?style=flat-square">
  </span>
</summary>

<br>

**🎯 Fungsi Utama**
Command utama untuk membuka konten party di Albion Online. Mengirim notifikasi ke channel, auto-assign role, dan timer otomatis.

**📝 Format Penggunaan**
