# Udemy:実践的!作って学ぶReactNative入門

## 進捗
### 環境構築
- NodeJSインストール
    - node,npm使えるようになる
- yarnインストール
- reactnative CLIインストール
    - `npm install -g react-native-cli`
- JDkインストール
    - https://www.techfun.co.jp/services/magazine/java/windows-jdk-pathset.html
- android sdkインストール
    - https://reactnative.dev/docs/environment-setup?platform=android
- adbパスと押す
- Genymotion,VirtualBoxインストール

### Hello world
- プロジェクト作成
    - `react-native init hello_world`
- 実行
    - `react-native run-android`->`a`
    - SDKでエラー出た
        - `hello_world/Android/local_properties`に以下追記
        - `sdk.dir = C:\\Users\\(ユーザー名)\\AppData\\Local\\Android\\Sdk`
    - No connected devicesというエラー出た
        - simulator起動した状態で実行すればよい
        - genymotionでandroidシミュレータ起動してから実行
        - genymotionでandroidシミュレータのactionsがtrueになるまで実行まつ
            - simulatorが完全に立ち上がってからrun-androidしないといけない
    - welcome to React Nativeと表示された
    - run-iosはxcode周りでエラーが出て実行できない
- 編集
    - App.tsxを編集してRを2回タップすると反映される
    - 日本語対応しておらず、文字化けする
- onPress
- style
- flex-layout
- reloadの種類