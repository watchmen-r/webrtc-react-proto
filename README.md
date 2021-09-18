# このアプリについて
WebRTCを用いたアプリ作成を素早くするための雛形アプリ。
最大4人でビデオ通話できるようする

# シグナリング仕様について
特にWebRTCでのシグナリングは方法が策定されていないらしい(SDPなどが渡せられればなんでも良い)。
当アプリではFirebaseのRealtimeDatabaseを用いている
1. Offer
```

```

2. Answer

```
```

3. Candidate
```
```

部屋用のroomuserというオブジェクト
また、同列で人の名前配下にシグナリングを置いた方が、シグナルを管理しやすい気がする