# Calendar-Generator

[武蔵野大学のポータルサイト](https://muscat.musashino-u.ac.jp/portal/top.do)から履修情報を取得し、自動でカレンダーを作成するスクリプトです。~~下のURLからも利用可能です。~~(現在は稼働停止中です。現状のMUSCATの仕様に合わせて適宜修正して利用してください。)

~~[https://rintaro-fukui-calendar-generator-appapp-dty2mz.streamlit.app/](https://rintaro-fukui-calendar-generator-appapp-dty2mz.streamlit.app/)~~

## Getting Started

このリポジトリをクローンする。
```shell
$ git clone https://github.com/Rintaro-Fukui/Calendar-Generator.git
```

`Calendar-Generator/app/`に移動して仮想環境を作る。
```shell
$ cd ./Calendar-Generator/app
$ python3 -m venv venv
$ source ./venv/bin/activate
$ pip install -r requirements.txt
```

アプリケーションを起動する。
```shell
$ streamlit run app.py
```
