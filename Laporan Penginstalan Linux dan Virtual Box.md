## Laporan: Langkah-langkah Penginstalan Linux dan VirtualBox
I. Pengantar
VirtualBox adalah perangkat lunak virtualisasi yang memungkinkan Anda menjalankan sistem operasi lain di dalam lingkungan sistem operasi yang ada. Dalam laporan ini, kami akan menjelaskan langkah-langkah untuk menginstal VirtualBox dan menginstal Linux di dalamnya.

## II. Persiapan
Komputer dengan sistem operasi host (Windows, macOS, atau Linux).
Koneksi internet.
File ISO dari distribusi Linux yang ingin diinstal (misalnya, Ubuntu, Fedora, atau Debian).
VirtualBox installer yang dapat diunduh dari situs resmi VirtualBox.

## III. Langkah-langkah Penginstalan VirtualBox
Unduh VirtualBox:

Kunjungi situs resmi VirtualBox.
Unduh versi VirtualBox yang sesuai dengan sistem operasi host Anda.
Instal VirtualBox:

Jalankan installer VirtualBox yang telah diunduh.
Ikuti petunjuk instalasi pada layar. Pilih opsi default kecuali Anda memiliki preferensi khusus.
Setelah instalasi selesai, buka aplikasi VirtualBox.

## IV. Langkah-langkah Penginstalan Linux di VirtualBox
Buat Mesin Virtual Baru:

Buka VirtualBox dan klik tombol "New" untuk membuat mesin virtual baru.
Masukkan nama untuk mesin virtual Anda (misalnya, "Ubuntu VM").
Pilih jenis sistem operasi ("Linux") dan versi yang sesuai dengan file ISO Linux Anda (misalnya, "Ubuntu (64-bit)").
Klik "Next".
Konfigurasi Memori:

Tentukan jumlah RAM yang ingin dialokasikan untuk mesin virtual. Disarankan minimal 2GB (2048 MB) untuk distribusi Linux modern.
Klik "Next".
Buat Hard Disk Virtual:

Pilih opsi "Create a virtual hard disk now" dan klik "Create".
Pilih format hard disk virtual (VDI adalah pilihan default) dan klik "Next".
Pilih opsi "Dynamically allocated" agar ukuran hard disk tumbuh seiring penggunaan.
Tentukan ukuran hard disk (minimal 20GB direkomendasikan).
Klik "Create".
Konfigurasi Mesin Virtual:

Klik kanan pada mesin virtual yang baru dibuat dan pilih "Settings".
Di tab "Storage", klik ikon CD dan pilih "Choose a disk file" untuk menambahkan file ISO Linux yang telah diunduh sebelumnya.
Di tab "System", pastikan "Floppy" tidak dipilih dalam Boot Order.
Klik "OK" untuk menyimpan konfigurasi.
Mulai Instalasi Linux:

Klik "Start" pada mesin virtual untuk memulai.
Mesin virtual akan boot dari file ISO Linux.
Ikuti langkah-langkah instalasi Linux yang muncul di layar, yang biasanya meliputi pemilihan bahasa, zona waktu, dan pengaturan partisi.
Selesaikan Instalasi:

Setelah instalasi selesai, Anda akan diminta untuk restart mesin virtual.
Eject file ISO dari mesin virtual dengan mengklik menu Devices > Optical Drives > Remove disk from virtual drive.
Restart mesin virtual dan sistem operasi Linux yang baru diinstal akan mulai berjalan.

## V. Penutup
Dengan mengikuti langkah-langkah di atas, 
Anda seharusnya dapat menginstal Linux di dalam VirtualBox dengan lancar. 
VirtualBox menyediakan cara yang efisien untuk menjalankan berbagai sistem operasi secara bersamaan di satu komputer, 
membuatnya menjadi alat yang berguna bagi pengembang, tester, dan pengguna yang ingin bereksperimen dengan sistem operasi yang berbeda.