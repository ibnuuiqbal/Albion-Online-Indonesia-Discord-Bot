# 🇮🇩 Albion Online Discord Bot (MABAR) - Professional Guild Management System

[![Status Bot](https://img.shields.io/badge/Status-Aktif%20di%20Discord-4E9A06?style=for-the-badge&logo=discord)](https://github.com/ibnuuiqbal/Albion-Online-Indonesia-Discord-Bot)
[![Lisensi](https://img.shields.io/badge/License-Proprietary%20(Private)-red?style=for-the-badge)](https://github.com/ibnuuiqbal/Albion-Online-Indonesia-Discord-Bot)
[![Node.js](https://img.shields.io/badge/Node.js-v16.x+-339933?style=for-the-badge&logo=node.js)](https://nodejs.org/)

<p align="center">
  <img src="https://github.com/ibnuuiqbal/readme-assets/blob/main/bannerawal.png?raw=true" alt="Logo Bot MABAR" width="800">
</p>

**Mabar Assistant** adalah solusi All-in-One tercanggih untuk manajemen Guild Albion Online. Bot ini bukan sekadar penyedia informasi, melainkan sistem manajemen operasional lengkap berbasis **MongoDB** yang mengintegrasikan Ekonomi Mikro, Kedisiplinan Militer (CTA), Diplomasi (NAP), Killboard Visual Otomatis, Artificial Intelligence, serta fitur Social Engagement untuk membangun komunitas guild yang lebih solid dan transparan.

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
* **Visual Killboard Engine:** Generator gambar killboard otomatis dengan statistik Silver dinamis, deteksi "Whale/Juicy Kill", dan notifikasi hype yang seru.
* **Robust Recovery System:** Seluruh data pendaftaran party `/konten` tetap terjaga otomatis meskipun bot/VPS restart.
* **Automatic Tax & Audit:** Perhitungan pajak guild dan audit finansial otomatis.
* **Smart Content Feedback:** Pelacakan performa Caller dengan sistem rating dari member.
* **Hybrid Economy:** Integrasi saldo Cash, Bank Pribadi, dan Bank Guild yang saling terhubung.

---

## 📜 Daftar Lengkap Slash Commands (Update 2026)

### ⚔️ Kategori: Pengelolaan Mabar & Konten
Sistem pendaftaran party interaktif dengan auto-role dan reward terintegrasi.
* `/konten` - Membuka pendaftaran party (Mabar) otomatis.
* `/kontenstats` - Statistik performa konten guild (Done/Auto/Expired).
* `/rankmabar` - Papan peringkat partisipasi & kontribusi member.
* `/avaraid` - (BARU) Manajemen khusus untuk Raid Avalonian Dungeon.
* `/nap` - Manajemen Non-Aggression Pact (Diplomasi Guild).
* `/splitloot` - Kalkulator pembagian loot party secara adil transparan.
* `/regear` - Sistem klaim regear otomatis via Modal UI & Transfer Silver.
* `/hideout` & `/hideout-delete` - Manajemen Otomatis lokasi HQ/HO ROA dan Rute.
* `/rute` - Informasi rute portal dan rest area tercepat.
* `/scanner` - Scan zona untuk deteksi aktivitas musuh.
* `/scout` - Sistem pelaporan scout di lapangan secara real-time.
* `/jadwal` & `/canceljadwal` - Penjadwalan konten mabar di masa mendatang.
* `/partydelete` - Menghapus/Reset data party dalam database.
* `/done_manual` & `/recover_manual` - Override status party secara manual.
* `/build` - Berbagi dan menyimpan komposisi build item Albion.

### 💀 Kategori: Killboard & PvP Tracker
Fitur pelacakan pembunuhan dengan visualisasi gambar berkualitas tinggi.
* `/setup-killboard` - Konfigurasi channel untuk auto-posting killboard guild.
* `/lastkill` - Menampilkan detail pembunuhan terakhir member/guild secara manual.
* `/blacklist` - Daftar pemain/guild yang di-blacklist oleh komunitas.

### 🛡️ Kategori: Militer & CTA (Call to Arms)
Fitur khusus untuk manajemen perang (ZvZ) dan keaktifan militer.
* `/cta-rank` - Peringkat keaktifan member dalam event CTA.
* `/cta-history` - Riwayat partisipasi CTA individu maupun guild.
* `/cta-check` - Pengecekan kehadiran member saat jam CTA dimulai.
* `/setcaller` - Penentuan Caller utama dengan sistem rating kontribusi.
* `/setpoint`, `/clear-point` - Manajemen poin kontribusi member.

### 💰 Kategori: Keuangan & Bank Guild
Manajemen ekonomi guild yang transparan, aman, dan otomatis.
* `/balance` / `/profile` - Cek saldo Cash (dompet) & Bank pribadi.
* `/deposit` / `/withdraw` - Manajemen simpanan bank pribadi.
* `/transfer` - Kirim silver aman antar anggota guild.
* `/donasi` - Kontribusi perak langsung ke kas Bank Guild.
* `/guildbalance` & `/guildroster` - Status keuangan & list member guild terbaru.
* `/subsidi` - Distribusi dana bantuan guild untuk member.
* `/tax` - Pengaturan persentase pajak transaksi internal guild.
* `/invest` & `/claiminvest` - Sistem investasi perak dengan bunga harian.
* `/history` - Log riwayat lengkap seluruh transaksi finansial user.
* `/siphon` - Manajemen deposit dan pengecekan Siphoned Energy.
* `/bayar`, `/lunas`, `/ngutang`, `/tagih`, `/cek_piutang` - Sistem manajemen hutang piutang member.
* `/setbalance` & `/sweepbalance` - Tool administratif untuk audit/reset saldo.

### 📊 Kategori: Informasi & Albion API
Data real-time yang ditarik langsung dari server resmi Albion Online.
* `/roa` / `/roa-info` - Informasi Roads of Avalon (Map/Tier).
* `/albionprofile` - Statistik lengkap karakter (Fame, Kill, Death, Ratio).
* `/price` / `/gold` / `/premium` - Cek harga market & kurs perak secara real-time.
* `/combatfame` - Kalkulator optimasi penggunaan tome/fame senjata.
* `/resource` - Data bonus harian kota untuk crafting & gathering.
* `/banditstatus` - Update otomatis event Faction Warfare (Bandit).
* `/gvgstatus`, `/season`, `/topterritory` - Monitoring kompetisi guild secara global.
* `/randomfact` - Fakta unik dan edukatif seputar Albion Online.
* `/timezone` - Konversi waktu WIB ke UTC (Waktu Server Albion).

### 🎯 Kategori: Minigame & Entertainment
Meningkatkan retensi dan aktivitas member di dalam server Discord.
* `/adventure` / `/fishing` - Roleplay petualangan dan memancing ikan Albion.
* `/quest`, `/work`, `/daily` - Aktivitas harian untuk menghasilkan silver bot.
* `/trivia` - Kuis Albion Online dengan koleksi 500+ pertanyaan.
* `/gamble`, `/coinflip`, `/dice`, `/kocok`, `/roll` - Game keberuntungan & taruhan.
* `/lottery` & `/giveaway` - Sistem undian otomatis berhadiah saldo.
* `/rob`, `/bounty`, `/setbounty` - Fitur interaksi PvP sosial (rampok & buronan).
* `/rps` - Permainan Batu Gunting Kertas klasik.
* `/albionmeme` - Menampilkan meme terbaru dari subreddit Albion Online.
* `/confess` - Mengirimkan pesan anonim ke channel tertentu.
* `/stats` - Statistik perkembangan minigame pribadi.

### ⚙️ Kategori: Utilitas & Sistem
Fitur inti untuk menjaga ketertiban, pendaftaran, dan fungsi bot.
* `/register` & `/sendregister` - Sistem integrasi pendaftaran nickname in-game.
* `/mytimers` & `/timer` - Pengingat waktu konten pribadi maupun guild.
* `/userinfo` / `/serverinfo` - Informasi mendalam mengenai user & server.
* `/help` / `/info` / `/ping` - Pusat bantuan, status teknis, dan latensi bot.
* `/saran` / `/poll` / `/chat` - Fitur feedback, voting, dan interaksi bot.
* `/satpam` - Sistem logging moderasi dan proteksi server.
* `/dbfix` - Tool pemeliharaan struktur database MongoDB.
* `/cleanupbounty` / `/claimbounty` - Manajemen sistem buronan.

---

## ⚙️ Kategori: Beberapa Foto Bot

| **Killboard System** | **Party Management** | **Economy System** |
| :---: | :---: | :---: |
| ![Killboard](https://github.com/ibnuuiqbal/readme-assets/blob/main/foto-2026/killboard.png?raw=true) | ![Party](https://via.placeholder.com/400x200?text=Foto+Party+Management) | ![Economy](https://via.placeholder.com/400x200?text=Foto+Economy+System) |
| *Tracking kill/death secara real-time dari API Albion.* | *Sistem pendaftaran party dengan pemilihan role.* | *Sistem saldo, subsidi, dan daily rewards.* |
---
---
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
