# JUPYTER ROAD LINE DETECTION

Project ini ditujukan untuk memenuhi syarat penilaian ujian akhir matakuliah Pengolahan Citra

## Teori

Pengolahan Citra adalah ilmu komputer yang mempelajari tentang pemrosesan gambar digital melalui algoritma, dengan tujuan  pemrosesan citra menjadi citra lain untuk tujuan tertentu, misalnya mendapatkan kualitas citra yang lebih baik. Adapun beberapa tingkatan Pengolahan Citra dibagi menjadi tiga; Pengolahan Tingkat Rendah (Low-Level Processing), Pengolahan Tingkat Menengah (Mid-Level Processing), dan Pengolahan Tingkat Tinggi (High-Level Processing).

Beberapa operasi pada Pengolahan Citra meliputi; Preprocessing, Peningkatan citra, Segmentasi, Pendeteksian objek, Pengenalan pola.

Pengolahan citra memiliki banyak aplikasi praktis, termasuk pengolahan medis (misalnya, deteksi tumor), pengolahan citra satelit (misalnya, pemantauan bencana alam), pengolahan citra forensik (misalnya, identifikasi wajah)

Adapun teknik road line detection pada pengolahan citra ini ditujukan untuk beberapa pengetahuan/teknologi yang akan diimplementasikan pada kehidupan, contohnya road line detection ini digunakan pada sistem mobil auto-pilot untuk mendeteksi lajur jalan didepan dengan demikian teknologi ini dapat mempermudah ataupun membantu beberapa orang yang kesulitan dalam mengemudikan kendaraan mobil mereka.

Adapun beberapa variabel yang digunakan di projek ini yaitu; asx, canny_image, cropped_image, fig, gray_image, height, image, image_with_lines, lines, region_of_interest, width.

## Cara Penyelesaian
1. Download IDE yang mendukung bahasa pemrograman Python seperti (Jupyter Notebook, Visual Studio Code, Pycharm)
2. Siapkan sample foto jalan dengan garis marka
3. Download/import library OpenCV, matplotlib.pylab, Numpy
4. Definisikan "region_of_interest" untuk mengatur wilayah gambar dan Definisikan "draw_the_lines" untuk menggambar garis
5. Import gambar dengan "imread" dan warna dengan "cvtColor"
6. Gunakan fungsi "Height" dan "Width" untuk mengetahui tinggi dan lebarnya gambar
7. Mendefinisikan "region_of_interest_vertices" untuk mengatur posisi/koordinat gambar dengan bentuk segitiga
8. membuat variabel "gray_image" dan "canny_image" untuk menapilkan garis tepi pada gambar
9. membuat variabel "cropped_image = region_of_interest" untuk menapilkan gambar dengan bentuk segitiga
10. membuat variabel "lines" dengan fungsi "cv2.HoughLinesP" untuk mengatur garis yang digunakan untuk mendeteksi marka jalan
11. membuat variabel "image_with_lines" dengan mendefinisikan ulang "draw_the_lines" dan menambah variabel "(image, lines)"
12. Yang terakhir membuat variabel "fig" dan "axs" dengan fungsi "plt.subplots" untuk menapilkan hasil perbandingan gambar side-by-side.

## Jurnal Terkait 
Beberapa Jurnal yang terkait dalam bidang ke ilmuan Pengolahan Citra mengenai deteksi garis marka jalan.

https://www.irjmets.com/uploadedfiles/paper/issue_5_may_2022/23299/final/fin_irjmets1652765861.pdf

https://journalppw.com/index.php/jpsp/article/view/4261/2809

## Authors

- [@ElanAryaAdiwidya](https://github.com/ElanAryaAdiwidya)
