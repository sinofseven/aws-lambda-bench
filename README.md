# aws-lambda-bench
!!! 現在 開発計画立案中 !!!  
AWS Lambdaのベンチマークに使用する。

# 具体的にやること
ベンチマークを取るFunctionをダウンロードして、新たにベンチマーク対象のメモリ容量のFunctionを作成、並列実行で情報を集めて、結果を表示する。  
(作成したFunctionは終了時に削除する)

# 開発計画
1. 技術検証
   1. Golangの文法
   1. Golangの自動ビルド
   1. GolangのTDD
   1. GolangをCLIとして使用する際のパラメータの指定方法
   1. Golangの並列実行
   1. Golangの標準出力、Loggerの使い方
   1. Golangのtmp dir
   1. GolangでAWSを触る
   1. GolangでAWS LambdaのFunctionをダウンロードする
   1. GolangでAWS LambdaのFunctionを作成する
   1. GolangでAWS LambdaのFunctionを削除する
   1. GolangでAWS LambdaのFunctionを実行し、実行時のデータを取る
1. CLIツールの作成
   1. 必要そうなオプションとパラメータ取得の実装
   1. tmp dirへのFunction download
   1. AWS LambdaのFunctionを作成する
   1. 並列実行してデータを集める
   1. AWS LambdaのFunctionを削除する
   1. 画面表示、ログの仕組みを整える
