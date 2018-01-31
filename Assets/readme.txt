Resourcesに含まれるテキストの確認。
パッケージに含まれているが、特に暗号化・難読化されているわけではない。

(例)Android
apkファイルの拡張子を変えて解凍する。

$ cp test.apk test.zip
$ unzip test.zip -d android

以下のファイルの内容を見ると、Resourcesに含めたテキストの内容が見れる。

android/assets/bin/Data/3abb5fe340fb54ab59337916410ae57c


(例)Mac
*.appファイルの内容を見れば、同様にテキストの内容が見れる。

ResourcesTest.app/Contents/Resources/Data/resources.assets

