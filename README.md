# OracleDBhandsON
2023/02/28 HandsOnLab.Meeting


以下の手順で対応を実施すること。

①「00_資材」フォルダより「sqldeveloper-22.2.1.234.1810-x64.zip」を取得しzipファイルを解凍する。

②AWSで「01_CloudFormation」の中にあるyamlファイルをCloudFormatinで実行する。

③CloudFormationの出力タブより「RDSPublicIP」の値を取得する。

④「①」で回答したフォルダの中に存在する「sqldeveloper.exe」をダブルクリックしコンソールツールを起動する。

⑤「sqldeveloper」にて以下の情報を入力し「テスト」を押下し正常に動作することを確認したのち「接続」を実施する。  
・[Name (接続名)] ：HandosON-Oracle-RDS  
・[Username (ユーザーネーム)] ：admin  
・[Password (パスワード)]：HandsONPassword  
・[Hostname (ホスト名)] ：「③」の値を入力する  
・[Port (ポート)] ：1521  
・[SID] ：ORCL  
