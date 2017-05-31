# Introduction to the Open Service Broker API

https://www.openservicebrokerapi.org/

* IBMや富士通などが参加
*

## cloud foundry

* 非常に単純なコマンドでアプリを管理できる(push/scale)
* codingにフォーカス、インフラはあまり考えていない
  * ただソフトは色々なものに依存する
    * データベースなど
  * アプリの成功にはアプリの管理も重要となる
    * アプリの管理は簡単ではない
      * チームをまたがるのでチーム間の連携も必要となる
    * Service Broker
      * Serviceを管理するサービス

### service broker api

* platform <-> Service broker
* abstracts the service lifecycle api


## Open service broker api

* CFのService Broker APIをオープン化し,　CF以外にもKubernetsやOpenShiftでも使えるようにした。
  * CF-Kubernets間の連携も可能
* 富士通やGoogle, IBMなど主要なメーカーが参加

### 今後の予定

* actionの拡張
  * backup/restoreもできるようにする
* RESTful
* 非同期


##
