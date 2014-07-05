# Androidオープンソースライブラリ徹底活用サンプルに対するbuild.gradleファイル集(MITライセンス編)


## 使い方

IntelliJ IDEA(あるいは、Android Studio。ただし、Android Studioでのビルドは未検証)で、Androidプロジェクトを作り、このリポジトリのbuild.gradleファイルの内容に従って、ファイルを編集する。libsにjarファイルを配置してあるプロジェクトに関しては、jarファイルを配置する。ライブラリモジュールが含まれているプロジェクトに関しては、それをプロジェクトにコピーする。また、settings.gradleファイルを編集する。なお、マニフェストファイル、ライブラリモジュールのbuild.gradle、アプリモジュールのbuild.gradleで、minSdkVersionやtargetSdkVersionを同じにしないとビルドできないケースもあった。Project Structureで設定する必要はない(と思う)。

## 注意

原則的に、アプリモジュールのソースファイルは著作権の問題で含めていないが、scribejavasample に関しては、本のサンプルのままでは動かなかったので、改変したものを含めた。