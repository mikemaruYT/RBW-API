  # RBW-API
  このフォージのモッドは、Ranked Bedwarsを快適にプレイするためのAPI MODです。

  RBWサーバー:  
  [Ranked Bedwars Discord server](https://discord.com/invite/rankedbw)  
  [JP Ranked Bedwars Discord server](https://discord.com/invite/CMbFRVqS8)  

  ## Commands
  このMODのコマンド一覧です。
  基本的な構文は、 `/rbw <パラメータ1> <パラメータ2>`です。

  # `/rbw help`
  このコマンドを実行すると、Helpが表示されます。  
  `[RBW] /rbw help : show helps(this command)`  
  `      /rbw start : start game call`  
  `      /rbw stats : show your stats`  
  `      /rbw reset : reset all memory`  

# `/rbw start`
このコマンドを実行すると、試合が終わるまでの時間を計測されます。  
試合が終了すると、Hypixelのタイトル表示とスコアボードに基づいて、試合時間とKill数、Final Kill数、Bed gone、試合時間、日付、チーム構成をメモリに保存します。  
***試合中の誰かがNICKしていた場合はNICKNAMEが刻まれます。***  

# `/rbw stats`
このコマンドを実行すると、いままでの試合から以下の情報をチャットに表示します。  
`KDR`  
`FKDR`  
`WDR`  
`BB/BG DR`

# `/rbw reset`
このコマンドを実行すると、メモリの中に入っているすべての情報が削除されます。  
***このコマンドは危険です!十分に気を付けて扱ってください。***  
実行した後に、確認のためのメッセージが出ます。`Are you sure you want to delete the memory? To confirm, please run `/rbw confirm` within 10 seconds.`
