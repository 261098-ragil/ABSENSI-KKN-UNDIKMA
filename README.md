# ABSENSI-KKN-UNDIKMA
Berikut adalah absensi mahasiswa KKN UNDIKMA didesa SEKOTONG BARAT thn 2024/2025
CREATE TABLE absensi (
    id INT AUTO_INCREMENT PRIMARY KEY,
    nama VARCHAR(100) NOT NULL,
    prodi VARCHAR(100) NOT NULL,
    jurusan VARCHAR(100) NOT NULL,
    latitude VARCHAR(50) NOT NULL,
    longitude VARCHAR(50) NOT NULL,
    waktu_absensi TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);

