# super-resolution
<概要>
卒業研究の研究内容を簡潔にまとめたファイルを作成したので添付しました.\
ここでは 16bit PCM 音声に対して2D-Convを用いた超解像を行っていますが, 最近は非可逆圧縮音声に対してGANを用いて超解像する研究をしています.

<ファイル内容>
super-resolutin.ipynb : スペクトログラムに対して, 2D-Conv を用いて超解像を行った.\
GAN_celp_to_wav_8000.ipynb : サンプリングレート8k の 非可逆圧縮(celp)を施した音声を, GAN を用いて超解像を行った.
