<template>
  <div class="container-fluid p-0">
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-light bg-light shadow-sm">
      <div class="container-fluid">
        <!-- Logo dan Judul -->
        <a class="navbar-brand d-flex align-items-center" href="/">
          <img src="/assets/img.jpeg" alt="Logo" width="50" height="50" class="me-2">
          <span>SMKN 4 Tasikmalaya</span>
        </a>
        <!-- Tombol Toggle untuk Mobile -->
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <!-- Menu Navbar -->
        <div class="collapse navbar-collapse" id="navbarNavDropdown">
          <ul class="navbar-nav ms-auto align-items-center">
            <!-- Menu Home -->
            <li class="nav-item">
              <a class="nav-link d-flex align-items-center active" aria-current="page" href="/">
                <i class="bi bi-house-door me-1"></i> Home
              </a>
            </li>
            <!-- Dropdown Artikel -->
            <li class="nav-item dropdown">
              <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownArtikel" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                Artikel
              </a>
              <ul class="dropdown-menu" aria-labelledby="navbarDropdownArtikel">
                <li><a class="dropdown-item" href="/visi-misi">Berita</a></li>
                <li><a class="dropdown-item" href="/sejarah">Pengumuman</a></li>
                <li><a class="dropdown-item" href="/struktur-organisasi">Umum</a></li>
              </ul>
            </li>
            <!-- Dropdown Profil -->
            <li class="nav-item dropdown">
              <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownProfil" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                Profil
              </a>
              <ul class="dropdown-menu" aria-labelledby="navbarDropdownProfil">
                <li><a class="dropdown-item" href="/visi-misi">Visi & Misi</a></li>
                <li><a class="dropdown-item" href="/sejarah">Sejarah</a></li>
                <li><a class="dropdown-item" href="/struktur-organisasi">Struktur Organisasi</a></li>
              </ul>
            </li>
            <!-- Dropdown Kurikulum --> 
            <li class="nav-item dropdown">
              <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownKurikulum" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                Kurikulum
              </a>
              <ul class="dropdown-menu" aria-labelledby="navbarDropdownKurikulum">
                <li><a class="dropdown-item" href="/kurikulum-2024">Kompetensi Keahlian</a></li>
                <li><a class="dropdown-item" href="/kurikulum-2023">Buku Pembelajaran</a></li>
                <li><a class="dropdown-item" href="/kurikulum-2023">Pembelajaran & Jadwal</a></li>
              </ul>
            </li>

            <li class="nav-item dropdown">
              <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownSarpras" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                Sarpras
              </a>
              <ul class="dropdown-menu" aria-labelledby="navbarDropdownSarpras">
                <li><a class="dropdown-item" href="/kurikulum-2024">Tanah</a></li>
                <li><a class="dropdown-item" href="/kurikulum-2023">Ruang Kelas</a></li>
                <li><a class="dropdown-item" href="/kurikulum-2023">Ruang praktek Siswa</a></li>
                <li><a class="dropdown-item" href="/kurikulum-2023">Ruang Penunjang</a></li>
                <li><a class="dropdown-item" href="/kurikulum-2023">-------------------</a></li>
                <li><a class="dropdown-item" href="/kurikulum-2023">Peralatan dan Aset</a></li>
              </ul>
            </li>

            <li class="nav-item dropdown">
              <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownSiswa" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                Siswa
              </a>
              <ul class="dropdown-menu" aria-labelledby="navbarDropdownSiswa">
                <li><a class="dropdown-item" href="/kurikulum-2024">Rombongan Belajar</a></li>
                <li><a class="dropdown-item" href="/kurikulum-2023">Ekstrakulikuler</a></li>
                <li><a class="dropdown-item" href="/kurikulum-2023">Prestasi</a></li>
              </ul>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>

<style scoped>
/* Styling Navbar */
.navbar {
  background-color: #f8f9fa;
}

.navbar-brand {
  font-weight: bold;
  font-size: 18px;
}

.nav-link {
  font-size: 14px;
  font-weight: 500;
  text-transform: capitalize;
}

.nav-item .nav-link.active {
  font-weight: bold;
  color: #0056b3;
}

.navbar-toggler-icon {
  color: #000;
}

/* Styling Dropdown */
.dropdown-menu {
  min-width: 200px;
  border-radius: 0;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

.dropdown-item:hover {
  background-color: #e9ecef;
  color: #0056b3;
}

/* Ikon di Navbar */
.nav-link i {
  font-size: 18px;
}
</style>