# Identifikasi Lajur Jalan Raya Melalui Citra Fotografi

<div style="text-align: justify"> Program ini bertujuan untuk mengindentifikasi lajur jalan raya yang kosong secara statik melalui foto dan video. Saya menggunakan <i> library </i> openCV dan numPy. Oleh karena itu pastikan anda telah melakukan instalasi berikut ini: </div> <br />

* ```pip install numpy``` <br />

* ```pip install opencv-contrib-python```

<br />

<div style="text-align: justify"> Tahapan yang dikerjakan oleh program ini berturut - turut adalah sebagai berikut: </div>

1. <i> Grayscaling </i>

2. <i> Image Smoothing </i>

3. <i> Edge Detection </i>

4. Pendefinisian <i> Region of Interest </i> (ROI)

5. Transformasi <i> Hough Line </i>

6. Penggambaran garis jalan pada foto

7. Eksekusi program untuk video.

<br />

<div style="text-align: justify"> Diperlukan pengembangan lebih lanjut dari program <i> Computer Vision </i> ini. Saya terbuka jika ada yang hendak menulis makalah bersama tentang pengembangan program ini, misalnya untuk aplikasi <i> self-driving car </i> atau yang lainnya. </div> <br />

Referensi:

* Aly M. Real time Detection of Lane Markers in Urban Streets. <i> Proceeding IEEE Intelligent Vehicles Symposium </i> hal. 8-12, 4-6 Jun. 2008.

* Yu B., A.K. Jain. Lane Boundary Detection Using A Multiresolution Hough Transform. <i> Proceedings of IEEE International Conference on Image Processing </i> hal 748 - 751, 26 - 29 Okt. 1997.