FRUIT CUT TEZ - Android project (WebView)

1. Android Studio (latest) install karo, phir File > Open > ye FruitCutTez folder chuno.
   Gradle sync khud ho jayega (internet chahiye).
2. Icon: app/src/main/res par right-click > New > Image Asset, apna icon banao,
   phir AndroidManifest.xml ke <application> mein android:icon="@mipmap/ic_launcher" jodo.
3. Phone par test: USB se phone jodo aur Run dabao.
4. Play Store ke liye: Build > Generate Signed App Bundle / APK > Android App Bundle (.aab).
   Keystore file bana ke SAFE rakho - ye kho gayi to app update nahi kar paogi.
5. Play Console mein .aab upload karo, store listing (screenshots, description),
   privacy policy link, aur content rating bharo.

Game ka code: app/src/main/assets/index.html
App name badalna ho: AndroidManifest.xml mein android:label.
Package name (com.fruitcuttez.game) Play Store par unique hona chahiye; chahe to badal lo.
