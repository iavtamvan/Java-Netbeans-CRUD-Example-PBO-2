# Java-Netbeans-CRUD-Example-PBO-2

1. Download / clone projek https://github.com/iavtamvan/Java-Netbeans-CRUD-Example-PBO-2/
2. Bikin database bernama (delta_db).
3. Bikin table nya :
CREATE TABLE `karyawan` (
  `id_karyawan` int(11) NOT NULL,
  `nama_karyawan` varchar(50) DEFAULT NULL,
  `nik` varchar(20) DEFAULT NULL,
  `jabatan` varchar(20) DEFAULT NULL,
  `no_telphone` varchar(20) DEFAULT NULL,
  `alamat` varchar(100) DEFAULT NULL
)
4. Right click on folder Libraries ->choose ADD JAR Folder…. (cari nama file yg bernama rs2xml.jar)
5. kemudian RUN form nya.
