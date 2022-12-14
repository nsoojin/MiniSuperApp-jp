<a href="https://coloso.jp/programming/iosengineer-rosoojin-jp?utm_source=soojin-github&utm_medium=readme&utm_campaign=soojin">
  <img src="https://github.com/nsoojin/MiniSuperApp-jp/blob/main/assets/rosoojin-point-web.png?raw=true" />
</a>

<div align = "center">
  <a href="https://soojin.ro">
    <img src="https://img.shields.io/badge/iOSエンジニア-ノ・スジン-orange?style=flat" />
  </a>
</div>

### モバイル開発者にとってスケーラビリティとは

モバイルチームとアプリの規模が拡大し続けても、ユーザーエクスペリエンスとデベロッパーエクスペリエンスの両方を安定して維持できることだと思います。

開発者の技術力は、開発中に発生するボトルネックをいかにうまく処理するかによって確認できます。サーバーの場合は、多くのユーザーが集中する時にボトルネックが発生しますが、モバイルの場合は１つのプログラムに多数の開発者のコードが集中する時、ボトルネックが発生します。

関連：[モバイル開発者にとってスケーラビリティとは何だろうか](https://soojin.ro/blog/scalability-jp)

<br>

# 講義内容

### PART 1. コードレベルアーキテクチャ：再利用可能なコードを作成するスキル

小さなオブジェクトを作成し、そのオブジェクトを組み合わせて複雑な機能にまとめるのがアーキテクチャの始まりです。
Massive View Controller、Masive View Model、Massive Interactorはアーキテクチャだけの問題ではなく、
開発者がコンポジションを活用する能力によって異なります。 
強力なコンポジション機能に対応しているアーキテクチャフレームワークのRIBsに基づいてミニスーパーアプリを作成してみましょう。

関連１：[Swiftで振り返るオブジェクト指向プログラミング：避けるべきコーディング習慣](https://soojin.ro/blog/solid-principles-in-swift-jp)
<br>
関連２：[開発者とインスタントラーメンのレシピ](https://soojin.ro/blog/programmer-and-ramyun-jp)
<br>
関連３：[google/promisesを活用したSwift非同期プログラミングとエラー処理](https://soojin.ro/blog/using-google-promises-swift-jp)

### PART 2. モジュールレベルのアーキテクチャ：メンテナンスと開発速度を考慮したモジュール化

「疎結合のモジュール構造」は、「スケーラブルなアーキテクチャ」と同じ言葉である。200人のiOSアプリ開発者が貢献するスーパーアプリのGrab、約75人が貢献する[Airbnb](https://medium.com/airbnb-engineering/designing-for-productivity-in-a-large-scale-ios-application-9376a430a0bf)などの企業の開発者が生産性を守る方法である。モジュール化すればどうしてビルド時間が短くなり生産性が上がるのかという原理を学習し、実習を通じてミニスーパーアプリに適用してみる。


関連１：[モバイルアプリの疎結合](https://soojin.ro/blog/loose-coupling-jp)
<br>
関連２：[Sourcery開発者から学ぶモバイルアーキテクチャと開発者エクスペリエンス](https://soojin.ro/blog/pragmatic-programmer-jp)

### PART 3. 自動化テスト

実務を担当する開発者がテストを始めるのが難しい理由は、レガシーコードがテスト不可能な構造で作成されているためです。それに対して、この実習で作成するコードは99％がテスト可能なコードです。テスト可能なコードの特徴を身につけて直接テストを書いてみると、レガシーコードに少しずつ導入するのも簡単です。単体テスト、スナップショットテスト、UIテスト、統合テストを作成してみましょう。

関連１：[テストと良い設計の関係、そして悪い設計の影響](https://soojin.ro/blog/tests-and-design-jp)
<br>
関連２：[テストコード作成の利点](https://soojin.ro/blog/writing-test-code-jp)
<br>
関連３：[uber/RIBs 単体テストの作成](https://soojin.ro/blog/unit-testing-ribs-jp)
<br>
関連４：[XCTest所要時間を短縮する](https://soojin.ro/blog/application-library-test-jp)

### PART 4. スケーラブルなインフラ：コードだけで解決できない問題

スケーラブルなアーキテクチャを作成して維持するには、コードだけでなく開発プロセスもサポートする必要があります。フィーチャーフラグと品質モニタリングを導入して得られるものと、私が経験した優秀な開発文化の事例を共有します。

関連１：[アプリの安定性に向けたたゆまない旅程](https://soojin.ro/blog/journey-to-app-stability-jp)
<br>
関連２：[チームワーク](https://soojin.ro/blog/teamwork-jp)
<br>
関連３：[個人とチームが成長するモバイル開発環境](https://soojin.ro/blog/mobile-platform-jp)
