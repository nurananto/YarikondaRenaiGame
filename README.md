# Yarikonda Renai Game no Akuyaku ni Tensei shitanode, Gensaku Chishiki de Heroine wo Kouryaku shimasu

> Yūto Hatano adalah penggemar berat game bishōjo Hōkago no Flare Story, sampai-sampai ia memainkannya berulang kali. Andai dunia ini seperti itu, pasti pergi ke sekolah akan lebih menyenangkan... pikirnya, lalu keesokan paginya—tak disangka, ia benar-benar masuk ke dunia game tersebut! Namun, ia bukan menjadi sang protagonis, melainkan si penjahat, Kanji Aku!Awalnya, ia berharap bisa melakukan berbagai hal bersama para heroine yang ia kagumi. Namun, sebagai seorang penjahat, tentu saja tingkat kesukaan mereka terhadapnya berada di titik terendah. Dengan kondisi ini, menaklukkan mereka hanyalah impian yang mustahil...Parahnya lagi, jika ia memilih opsi yang salah, maka yang menantinya adalah kematian!!Dengan status terendah dan tingkat kesukaan yang paling buruk, Kanji Aku harus menghadapi berbagai pilihan hidup dan mati, menaklukkan para heroine, dan mencari jalan keluar dari dunia ini!,

---

## Info

| | |
|---|---|
| Judul | Yarikonda Renai Game no Akuyaku ni Tensei shitanode, Gensaku Chishiki de Heroine wo Kouryaku shimasu |
| Judul Alternatif | やり込んだ恋愛ゲームの悪役に転生したので、原作知識でヒロインを攻略します |
| Author | Kennoji |
| Artist | Yuuma Yun |
| Tipe | Manga (Hitam Putih) |
| Status | Ongoing |
| Genre | Seinen · Comedy · Romance · School Life · Slice of Life · Isekai |
| Chapter | 43 chapter (2 locked) |

## Link

- [MangaDex](https://mangadex.org/title/a605a5d0-21a6-481f-a055-74735ea4f2c2/yarikonda-renai-game-no-akuyaku-ni-tensei-shitanode-gensaku-chishiki-de-heroine-wo-kouryaku-shimasu)
- [Raw](https://www.manga-up.com/titles/1518)

---

## Struktur

```
YarikondaRenaiGame/
├── manga-config.json     # Metadata manga
├── manga.json            # Data chapter (auto-generated)
├── manga-automation.js   # Script automation
├── encrypt-manifest.js   # Script enkripsi manifest
├── daily-views.json      # Data views harian
└── <chapter>/
    └── manifest.json     # Daftar halaman (encrypted)
```

## Automation

Semua proses berjalan otomatis via GitHub Actions:

1. Push chapter baru (folder + manifest.json)
2. `encrypt-manifest.yml` — enkripsi manifest
3. `manga-automation.yml` — regenerate manga.json
4. Trigger rebuild ke website utama
5. `sync-cover.yml` — sinkronisasi cover dari website

---

Bagian dari [Nurananto Scanlation](https://nuranantoscans.my.id)