# SAN_RPGMV_PluginCatalog
これはSanshiroが公開するRPGツクールMV向けプラグインの一覧です。

## ゲーム機能追加プラグイン
|名称|最新ver|公開日|更新日|概要|  
|--- |:-:|:-:|:-:|---|  
|[SAN_AnalogMove](https://github.com/rev2nym/SAN_AnalogMove)|3.1.5|2015/11/06|2018/08/14|パーティキャラクターの移動をタイルによらないドット移動に変更します。方向キー操作、タッチ操作に対応しています。|  
|[SAN_MapGenerator](https://github.com/rev2nym/SAN_MapGenerator)|1.1.9|2015/11/29|2018/08/14|ランダム形状のマップを自動的に生成し、ランダムにイベントを配置し、 プレイヤーを入口イベントの場所に移動させます。|  
|[SAN_ActorGraphicsReactor](https://github.com/rev2nym/SAN_ActorGraphicsReactor)|2.1.4|2016/04/10|2018/08/09|アクターのグラフィックをレイヤー状に表示し、装備やステートなどの状態に応じてグラフィックを変化させます。レイヤーデータの編集機能を備えます。|  
|[SAN_ActorBodysizeReactor](https://github.com/rev2nym/SAN_ActorBodysizeReactor)|2.1.3|2016/06/28|2018/08/10|アクターに性別、年齢、身長、体重、スリーサイズなどのボディサイズパラメータを追加し、装備やステートなどの状態に応じてボディサイズを変化させます。設定データの編集機能を備えます。|  
|[SAN_ExtendedEventPage](https://github.com/rev2nym/SAN_ExtendedEventPage)|1.1.0|2016/10/27|2018/09/02|イベントページの出現条件と出現時の機能を拡張します。さまざまなイベントページ出現条件を記述できるようになります。|  
|[SAN_TileToner](https://github.com/rev2nym/SAN_TileToner)|1.1.6|2016/12/19|2017/12/11|マップ上の指定されたタイルを染色します。染色したタイルには波紋のようなアニメーションを表示します。RGBとアルファ値を設定できます。|  
|[SAN_ResidualSprites](https://github.com/rev2nym/SAN_ResidualSprites)|1.0.2|2017/02/23|2017/02/23|キャラクターやバトラーの残像を表示します。RGBとアルファ値を設定できます。|  
|[SAN_ParallaxPicture](https://github.com/rev2nym/SAN_ParallaxPicture)|1.0.2|2018/02/01|2018/02/17|ピクチャを遠景のようにスクロール表示します。他のピクチャとの表示前後関係を調整することができます。|  
|[SAN_ParallaxMap](https://github.com/rev2nym/SAN_ParallaxMap)|1.1.2|2018/02/02|2018/04/23|ピクチャを遠景のようにスクロール表示します。他のピクチャとの表示前後関係を調整することができます。|  
|[SAN_EasingPicture](https://github.com/rev2nym/SAN_EasingPicture)|1.1.0|2018/02/17|2018/04/05|ピクチャ毎のモーション毎にイージングを設定します。イージングとはアニメーションの進み具合を滑らかに制御することで、動きをよりリアルに見せる手法のことです。|  
|[SAN_TouchAnimation](https://github.com/rev2nym/SAN_TouchAnimation)|1.0.0|2017/08/27|2017/08/27|タッチ操作にアニメーションを表示します。 アニメーションの設定はゲーム中も変更することができます。|  
|[SAN_DestinationAnimation](https://github.com/rev2nym/SAN_DestinationAnimation)|1.0.1|2018/08/20|2018/08/20|マップ上の目標地点にアニメーションを表示します。 アニメーションの設定はゲーム中でも変更することができます。|  

## システム補助プラグイン
|名称|最新ver|公開日|更新日|概要|  
|--- |:-:|:-:|:-:|---|  
|[SAN_AnalogStick](https://github.com/rev2nym/SAN_AnalogStick)|1.0.0|2017/03/01|2017/03/01|ゲームパッドのアナログスティックの入力値を利用可能にします。|  

## コアスクリプト改善・修正プラグイン
|名称|最新ver|公開日|更新日|概要|  
|--- |:-:|:-:|:-:|---|  
|[SAN_Imp_SkipParallelEventPreload](https://github.com/rev2nym/SAN_Imp_SkipParallelEventPreload)|1.0.0|2018/10/01|2018/10/01|並列イベントの画像プリロード処理をスキップすることで処理速度の改善を図ります。|  
|[SAN_Imp_ColorCache](https://github.com/rev2nym/SAN_Imp_ColorCache)|1.0.0|2018/10/01|2018/10/01|色データの取得結果をキャッシュ化することでゲームの処理速度の改善を図ります。|  
|[SAN_Fix_SeBuffers](https://github.com/rev2nym/SAN_Fix_SeBuffers)|1.0.0|2018/10/08|2018/10/08|複数の演奏中のSEを正常に停止できない不具合を修正します。|  

## 開発補助プラグイン
|名称|最新ver|公開日|更新日|概要|  
|--- |:-:|:-:|:-:|---|  
|[SAN_FileDeleter](https://github.com/rev2nym/SAN_FileDeleter)|1.1.1|2016/07/05|2016/12/16|未使用の素材ファイルを削除して容量削減を図ります。|  
|[SAN_SoundTuner](https://github.com/rev2nym/SAN_SoundTuner)|1.0.0|2016/11/23|2016/11/23|音声ファイル毎に相対音量、ピッチ、位相(パン)を設定して調整できるようにします。|  
|[SAN_ScriptImporter](https://github.com/rev2nym/SAN_ScriptImporter)|1.0.0|2018/08/25|2018/08/25|プラグインやスクリプトの前提スクリプトを読み込みます。RPGツクールMVのプラグイン機能において`import`文のような機能を代替することが目的です。|  
