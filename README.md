# super-resolution : 超解像
<概要> \
16bit PCM 音声に対して, 短時間フーリエ変換をすることで得られるスペクトログラムを入出力として2D-Conv からなる GANを用いて学習を行います. \
また, 最近は非可逆圧縮音声に対してGANを用いて超解像する研究をしています.

卒業研究の際に作成したモデルを簡潔にまとめたファイルを順次作成しているので, 完成し次第, 以下に追加していきます.


<ファイル内容> \
・super-resolutin.ipynb : 2D-Conv を用いて超解像を行う. (2022/04/07)

・gan_8k_8k.ipynb : 非可逆圧縮(celp)などを施したサンプリングレート8kHz の音声に対して, 2D-Conv からなる GAN を用いて失われた成分を復元する. このときの入出力は8kHz の音声の振幅スペクトログラムである. (2022/06/06)

・gan_8k_16k_half.ipynb : サンプリングレート8kHz の音声を bicubic 補間した16kHz の音声に対して, 2D-Conv からなる GAN を用いて超解像を行う. このときの入力は16kHz の音声の振幅スペクトログラムの下半分, 出力は上半分である. (2022/06/08)
