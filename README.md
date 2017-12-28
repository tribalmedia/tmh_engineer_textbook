# TMH engineer textbook
このリポジトリはTribal Media Houseにおけるエンジニア向け教科書です。

## 対象者
Tribal Media House におけるビギナーエンジニア、特にWeb開発の初学者に向けてのテキストを目指します。
各ステップは、関連性を持ち前後関係を必要とする場合もあります。基本的には各ステップのみでも理解できる様に可能な限り解説に努めます．

## 目次
1. [AboutTMH](About-TMH)
2. [About Solution Development Department](About-Solution-Development-Department)
3. [About Software Engineer](About-Software-Engineer)
4. [Operation System](Operation-System)
5. [Container](Container)
6. [Web Server](Web-Server)
7. [Database System](Database-System)
8. [HTML](HTML)
9. [Git](Git)
10. [PHP](PHP)
11. [JavaScript](JavaScript)
12. [Swift](Swift)
13. [Android](Android)
14. [UI](UI)
15. [Hardware](Hardware)
16. [Network](Network)

## About TMH
トライバルメディアハウスは顧客を熱狂させる全くあたらしいマーケティングを創造するマーケティングデザインカンパニーです。   
従来の手法にとらわれないストラテジーと斬新なアイデア、それを実現するためのテクノロジーで、企業のマーケティングとユーザー体験に変革をもたらします。

## About Solution Development Department
Tribal Media Houseにおけるソリューション開発部門は、Web技術を用いてマーケティングツールを開発しています。
開発にはいくつかのチームと役割がありますが、ソリューション開発部のすべてのメンバーは「エンジニア」であると定義されています。
そんな「エンジニア」の使命は、「エンジニア」であることに誇りと自信と情熱を持って、世界をより良くしていくことです。

## About Software Engineer
トライバルメディアハウスの開発部において”ソフトウェアエンジニア”に求められる領域を以下の通り定義します。
1. Operation System
1. Container
1. Web Server
1. Database System
1. HTML
1. Git
1. PHP
1. JavaScript
1. Swift
1. Android
1. UI

これらの領域の中から、特に得意とする領域の特性によって以下の通り分類を行います。
1. System Engineer
1. Application Engineer

更に専門的な領域を得意とするエンジニアの場合、詳細に分類を行います。
1. Middleware Engineer
1. Web Application Engineer
1. Mobile Application Engineer

また、以下の領域はトライバルメディアハウスにおいても関与する領域ではありますが、Software Engineerの領域外であると定義します。
1. Hardware
1. Network

## Operation System
Operation Systemにおいて、特に大切な項目を以下にピックアップします。
必要に応じて、UNIX,Linuxについての知識も必要となる為、Oparation Systemについては広域な知識が必要とされます。

### Topics
- File System
- Security System
- Device Driver
- Memory Access
- Interrupt
- Job Scheduler
- Process Model

### Reference
[詳解 Linuxカーネル 第3版 ISBN978-4-87311-313-5](https://www.oreilly.co.jp/books/9784873113135/)
[ふつうのLinuxプログラミング 第2版　Linuxの仕組みから学べるgccプログラミングの王道](https://www.amazon.co.jp/dp/B075ST51Y5)
[動くメカニズムを図解&実験! Linux超入門 (My Linuxシリーズ)](https://www.amazon.co.jp/dp/4789844722/)

## Container
ContainerにおいてはDockerを中心にコンテナ技術についての知識が必要になります。
合わせて、仮想化技術などについても必要に応じて学習して下さい。

### Topics
- Docker

### Reference
[Docker - Build, Ship, and Run Any App, Anywhere](https://www.docker.com/)

## Web Server
Web Serverについて項目を整理した場合、UNIX・Process・Network APIとの関係性が深くなります。
リクエスト処理においては複数のモデルが存在する為、なぜそのモデルが必要とされるのかを抑える必要があります。

### Topics
- UNIX Process Model
- UNIX Network API
	- Socket Model
		- Listen
		- Accept
		- TCP echo Server
		- Port
- Parent / Child Process
- Program execution
- ps command
- Request Proccessing
	- RPC / gRPC
	- Serial Model
	- Multi Process Model
	- Multi Thread Model
	- Event Driven Model
	- Hybrid Model

### Reference
[なるほどUnixプロセス ― Rubyで学ぶUnixの基礎 - 達人出版会](https://tatsu-zine.com/books/naruhounix)
[ふつうのLinuxプログラミング 第2版　Linuxの仕組みから学べるgccプログラミングの王道](https://www.amazon.co.jp/dp/B075ST51Y5)
[Webを支える技術 -HTTP、URI、HTML、そしてREST (WEB+DB PRESS plus)](https://www.amazon.co.jp/dp/4774142042/)
[Web API: The Good Parts](https://www.amazon.co.jp/dp/4873116864/)

## Database System
Database Systemについて、特にRDBMSはしっかりと習得しておく必要があります。
データモデリングなどの要素もありますが、まずはRDBMSを網羅的に学習をして下さい。

### Topics
- RDBMS
	- MySQL
	- PostgreSQL
	- SQL
	- MetaData
	- Integrity Rules
	- Result Sets and Cursors
	- Transactions
	- Stored Procedures
- NoSQL
	- Schema Less
	- Distributing Models
	- CAP theorem
	- Aggregate Data Models
	- Document
		- MongoDB
	- Key Value
		- MemcacheDB
		- Redis
	- Column Family Stores
	- Graph Database
- Time Stamped Database
	- double-delta-encoding
	- XOR encoding
	- InfluxDB

### Reference
[A Relational Database Overview (The Java™ Tutorials > JDBC(TM) Database Access > JDBC Introduction)](https://docs.oracle.com/javase/tutorial/jdbc/overview/database.html)
[NoSQL Databases: An Overview | ThoughtWorks](https://www.thoughtworks.com/insights/blog/nosql-databases-overview)
[Webエンジニアのための データベース技術[実践]入門 (Software Design plus)](https://www.amazon.co.jp/dp/4774150207)
[理論から学ぶデータベース実践入門 ~リレーショナルモデルによる効率的なSQL (WEB+DB PRESS plus)](https://www.amazon.co.jp/dp/4774171972/)
[SQL実践入門──高速でわかりやすいクエリの書き方 (WEB+DB PRESS plus)](https://www.amazon.co.jp/dp/4774173010/)

## HTML
HTMLについては奥が深い領域です。
単純にマークアップ言語の羅列を行うだけではなく、さまざまな周辺プロトコルや周辺技術もしっかりと学習する必要があります。

### Topics
- Mark Up Language
- Tag

### Reference
ドットインストール

## Git
バージョンコントロールについては、Gitを用います。
延長線上にGitHubも存在していると考えている為、とても重要な項目であると考えます。

### Topics
- Version Control

### Reference
Gitアリスとボブ

## PHP
サーバサイド言語として、PHPをメイン言語として採用しています。
比較的敷居が低く、初学者であってもいきなり挫折する事が少ない言語であると認識しています。
しかし、習得の為には他の言語と同様に簡単ではない為、大切なポイントをまずは学習して下さい。

### Topics
- CGI
- PHP-FPM
- PDO
- CakePHP

### Reference
パーフェクトPHP

**MEMOS**

CGI
PHP-FPM

## JavaScript
Webブラウザ上で実行するスクリプト言語としてはJavaScriptは重要であると考えます。
昨今のWebシステム・Webサービスにおいて、JavaScriptが担う役割はとても大きくなっていると考えます。
周辺技術としても毎年新しい技術が注目されますが、基本となる部分をしっかりと学習していきましょう。

### Topics
- Web Browse Engine
- Event Driven
- DOM
- JSON
- Node.js

### Reference
パーフェクトJavaScript

## Swift
iOS上で動かすアプリケーションの開発において、Swiftは重要な静的型付け言語であると考えます。
タイプセーフである言語の開発と、プログラムを実行形式にコンパイルするという開発フローにも慣れていきましょう。

### Topics
- iOS
- XCode

### Reference
Swift実践入門

## Android
Swift同様にモバイル端末上で動かすアプリケーションの開発としてAndroidも重要です。
歴史が深い技術であり、Javaに関する知識が必要になります。
限られたリソースにおいて、パフォーマンスを発揮する為のチューニングについても技術が必要になります。

### Topics
- Jave
- Kotlin

### Reference
Androidを支える技術

## UI

### Topics
- User Interface

### Reference
パフォーマンス向上のためのデザイン設計
緑色の本

## Hardware

### Topics
- Device
- Device Driver

### Reference
コンピュータはなぜ動くか

## Network

### Topics
- IP Address
- Routing

### Reference
3min Networing