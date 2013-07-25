# redmine-checker

Redmineのチケットを日毎に集計するJenkinsプラグイン

## 機能

 * プロジェクトページのトップにRedmineのプロジェクトのチケットを集計した結果を表として出力する

 * 毎日以下の値を定時に取得して表に記載する

   - 不具合発生数
   - 保留数
   - 解決数 
   - 終了数 
   - 総保留数 
   - 総終了数 
   - 総不具合数 
   - 総未対応数 
   - 総解決数 

 * 手動で入力するカスタムのフィールドを追加できる（例：実施数）

