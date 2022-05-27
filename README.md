# signlangdecoder
SIBI (Sistem Isyarat Bahasa Indonesia) Sign Language Decoder. Made for TF4012 Image Based Measurement project.

Langkah-langkah pengujian *script* *real-time*:
1. Pastikan sudah menginstall **tensorflow**, **keras**, **openCV**, dan **numpy**.
2. File yang harus didownload: **test_signdecoder.ipynb** dan **signdecoderv2.h5**.
3. *Run* seluruh *cells* pada file **test_signdecoder.ipynb**.
4. Uji program dengan cara memeragakan bahasa isyarat SIBI huruf A, C, I, R, atau T pada _region of interest_ yang ditandai dengan kotak berwarna biru di tampilan video saat program dijalankan. Hasil prediksi dapat dilihat pada bagian atas dari tampilan video.