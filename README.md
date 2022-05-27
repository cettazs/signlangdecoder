# signlangdecoder
SIBI (Sistem Isyarat Bahasa Indonesia) Sign Language Decoder. Made for TF4012 Image Based Measurement project.

Langkah-langkah pengujian *script* *real-time*:
1. Pastikan sudah menginstall **tensorflow**, **keras**, **openCV**, dan **numpy**.
2. File yang harus didownload: [test_signdecoder.ipynb](https://github.com/cettazs/signlangdecoder/blob/main/test_signdecoder.ipynb) dan [signdecoderv2.h5](https://github.com/cettazs/signlangdecoder/blob/main/signdecoderv2.h5).
3. *Run* seluruh *cells* pada file [test_signdecoder.ipynb](https://github.com/cettazs/signlangdecoder/blob/main/test_signdecoder.ipynb).
4. Uji program dengan cara memeragakan bahasa isyarat SIBI huruf A, C, I, R, atau T pada _region of interest_ yang ditandai dengan kotak berwarna biru di tampilan video saat program dijalankan. Hasil prediksi dapat dilihat pada bagian atas dari tampilan video.

Other files guide:
1. [train_ds.ipynb](https://github.com/cettazs/signlangdecoder/blob/main/train_ds.ipynb): extracting frames from video dataset to get training dataset
2. [train_signdecoder.ipynb](https://github.com/cettazs/signlangdecoder/blob/main/train_signdecoder.ipynb): training model
3. [test_signdecoder.ipynb](https://github.com/cettazs/signlangdecoder/blob/main/test_signdecoder.ipynb): real-time testing code
4. [evaluate_signdecoder.ipynb](https://github.com/cettazs/signlangdecoder/blob/main/evaluate_signdecoder.ipynb): metrics evaluation for the trained model
5. [signdecoderv2.h5](https://github.com/cettazs/signlangdecoder/blob/main/signdecoderv2.h5): trained model
