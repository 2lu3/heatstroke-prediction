# ai-watch-data
data for ai-watch

## heatstroke data

Reference : http://www.fdma.go.jp/

## メモ

### 予測に使用するパラメーター
 * 3hごとの気温
 * 3hごとの気圧
 * 3hごとの風速
 * 3hごとの湿度
 * 平均気温
 * 最高気温
 * 最低気温
 * 日の出/日の入り
    * 日照時間
 * 人口
 * 先月の旅行客数
    * https://www.jnto.go.jp/jpn/statistics/visitor_trends/
    * 出典：日本政府観光局(JNTO)
 * アスリートの対象データ？
    * 競馬？
 * PM2.5との関係

### 仮説

* 1度大規模な熱中症が起きると、同じ条件でも数は少なくなる
* 熱中症でググったときの記事の数
* 

### 予測の方法

* 一般的な予測
  * 気象情報からの熱中症患者数の予測
  * 気象情報からの体調予測
  * 体の弱さは正規分布？
* 個々の人に合わせた予測
  * 個人の～に弱いを反映していない
  * 入力してもらう（主観的なものを）
  * 体調を把握するために、様々なことを記録する
    * 加速度センサで動き検出
    * Google Homeで家の音を把握
    * スマートウォッチの加速度センサで何をしているか