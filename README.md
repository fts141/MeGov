# MeGov
eGov で配布されている法令 XML ファイルを Markdown（.md）ファイルに変換する Python コード
## 💬ストーリー
法令こそ Git 管理した方が便利なのでは？と思い作成しました。
## 🙇免責事項
- 図表の抽出など一部機能が実装されていません。コード更新次第、Markdown ファイルも随時更新致します。
- 私は本業がプログラマーではなく、素人コードです。
# Python コード
## 🐍使い方
python3 megov.py eGovXML.xml exportDirectory
## 📚ライブラリ
- 🥣BeautifulSoup4(bs4)
# 関連レポジトリ
- [WeGov](https://github.com/fts141/WeGov)  
eGov で配布されている法令 XML ファイルを Word（.docx）ファイルに変換する Python コード