# jitsi-meet-android

## 入門
第一次 克隆下來建議需要把 專案底下 ```node_modules``` 刪除

然後 ```npm install```

就會根據你自己node版本安裝 ```node_modules```


## Android
用 android studio IDE 開啟RN專案的 android 目錄，他其實就是一個完整的 android 專案，IDE會自動幫你編譯 你自己的 gradle version，
開啟 [Terminal] ```cd android``` 到 android 目錄下，清除 gradle 的緩存 ```./gradlew clean```，這個動作如果在 run 專案有問題的話就進來清除緩存，
如果清除時遇到錯誤訊息：Unrecognized VM option 'MaxPermSize=512m'，那就從IDE中，全域搜尋：-XX:MaxPermSize=512m，將其刪除，就可以清除緩存，
回到 最外層目錄，也就是 android 目錄上一層，執行指令：```npx react-native run-android```終端機會同時跑出兩個視窗，等他跑完就可以看到 jitsi 畫面




