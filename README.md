# Dockerfileたち

## ファイル一覧
用意したファイルの一覧を示す.  

* pipenv_base
  - Ubuntu18.04LTSベース
  - python3.9
  - pipenvがインストールされているので, pythonのバージョンを変えたい場合はpipenvを使うと良い
  - pipenvの使い方: https://qiita.com/y-tsutsu/items/54c10e0b2c6b565c887a
* pipenv_jupyter
  - pipenv_baseベース
  - jupyterがインストールされている
  - kernelはpython2.7とpython3.6, python3.9
- pipenv_cuda
- pipenv_cuda_mecab
