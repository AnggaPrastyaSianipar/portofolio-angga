---
# Biarkan judul beranda kosong untuk menggunakan judul nama situs Anda
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    content:
      # Pilih profil pengguna untuk ditampilkan (nama folder di dalam `content/authors/`)
      username: me
      text: ''
      # Tampilkan tombol ajakan bertindak (CTA) di bawah biografi Anda? (opsional)
      button:
        text: Unduh CV
        url: resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Menggunakan Gradient Mesh yang otomatis menyesuaikan dengan warna tema terpilih
      background:
        gradient_mesh:
          enable: true

      # Penyesuaian ukuran teks nama profil
      name:
        size: md # Pilihan: xs, sm, md, lg (bawaan), xl

      # Kustomisasi bentuk dan ukuran Foto Profil (Avatar)
      avatar:
        size: medium # Pilihan: small (150px), medium (200px), large (320px), xl (400px), xxl (500px)
        shape: circle # Pilihan: circle (bawaan), square, rounded

  - block: markdown
    content:
      title: '📚 Riset & Penelitian'
      subtitle: ''
      text: |-
        Selamat datang di situs portofolio akademik saya. Saya adalah seorang peneliti di bidang Teknik Informatika yang berfokus pada pemanfaatan sains data dan kecerdasan buatan untuk menyelesaikan studi analisis prediktif.

        Saya menerapkan berbagai metode komputasi, pengembangan perangkat lunak, serta analisis kuantitatif untuk menginvestigasi peran teknologi cerdas di era digital.

        Silakan hubungi saya untuk kolaborasi riset, diskusi proyek ilmiah, maupun kerja sama profesional 😃
    design:
      columns: '1'

  - block: collection
    id: papers
    content:
      title: Publikasi Utama
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2

  - block: collection
    content:
      title: Riwayat Jurnal Ilmiah
      text: ''
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation

  - block: collection
    id: talks
    content:
      title: Kegiatan & Seminar Terbaru
      filters:
        folders:
          - events
    design:
      view: card

  - block: collection
    id: news
    content:
      title: Catatan Blog & Berita Terbaru
      subtitle: ''
      text: ''
      # Jenis halaman yang akan ditampilkan (E.g. post, talk, publication...)
      page_type: blog
      # Tentukan berapa halaman yang ingin ditampilkan (0 = semua halaman)
      count: 10
      # Filter kriteria tampilan
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      offset: 0
      # Urutan halaman: desc (terbaru ke lama) atau asc (lama ke baru)
      order: desc
    design:
      view: card
      spacing:
        padding: [0, 0, 0, 0]
---