#https://youtu.be/vRp-AYmvldE (video dokumentasi)
# projek-uas-program
#menu_makanan dan menu_minuman:
        Ini adalah dua dictionary yang berisi menu makanan dan minuman beserta harganya.

#print("Menu Makanan dan Minuman:"):
        Menggunakan fungsi print() untuk menampilkan teks di layar, yaitu "Menu Makanan dan Minuman:".
#for item, harga in menu_makanan.items(): dan for item, harga in menu_minuman.items()::
        Menggunakan loop for untuk iterasi melalui pasangan kunci-nilai dalam dictionary menu makanan dan minuman. Ini digunakan untuk menampilkan item dan harganya.

#print(f"{item} - Harga: {harga}"):
        Menggunakan f-string untuk memformat dan menampilkan item dan harganya.

#pilih_makanan = input("Masukkan pilihan makanan: ") dan pilihan_minuman = input("Masukkan pilihan minuman: "):
        Menggunakan fungsi input() untuk meminta pengguna memasukkan pilihan makanan dan minuman. Nilai yang dimasukkan oleh pengguna disimpan dalam variabel pilihan_makanan dan pilihan_minuman.

#if pilih_makanan in menu_makanan and pilih_minuman in menu_minuman::
        Melakukan pemeriksaan apakah pilihan makanan dan minuman yang dimasukkan oleh pengguna ada di dalam menu. Jika keduanya valid, program akan melanjutkan.

#total_pembelian = menu_makanan[pilih_makanan] + menu_minuman[pilih_minuman]:
        Menghitung total pembelian berdasarkan harga dari menu makanan dan minuman yang dipilih oleh pengguna.

#print("\nStruk Pembelian:"):
        Menampilkan teks "Struk Pembelian" dengan menggunakan fungsi print() dan karakter newline (\n) untuk membuat baris baru.

#print(f"Pilih Makanan: {pilih_makanan} - Harga: {menu_makanan[pilih_makanan]}") dan print(f"Pilih Minuman: {pilih_minuman} - Harga: {menu_minuman[pilih_minuman]}"):
        Menampilkan detail pilihan makanan dan minuman menggunakan f-string.

#else: print("Maaf, memilihan menu tidak valid."):
        Jika pilihan makanan atau minuman tidak valid (tidak ada di dalam menu), program akan menampilkan pesan bahwa pilihan tidak valid.
