# asgmt-3-visualization-with-modern-data-science

Assignment 3: Visualization with Modern Data Science 2025.

## 01. Write a SQL statement that is able to retrieve the table list given `taiwan_election_2024.db`.

```
table_name
aboriginal_legislators
candidates
districts
election_types
parties
party_legislators
polling_places
presidents
regional_legislators
villages
```

## 02. Write a SQL statement that is able to count the number of candidates for each election type given `taiwan_election_2024.db`.

```
election_type	number_of_candidate
總統/副總統	3
區域立委	309
山地立委	10
平地立委	9
```

## 03. Write a SQL statement that is able to count the number of polling places for each county given `taiwan_election_2024.db`.

```
county	number_of_polling_place
新北市	2681
高雄市	2038
臺中市	1902
臺北市	1764
臺南市	1548
桃園市	1384
彰化縣	1085
屏東縣	723
雲林縣	620
嘉義縣	535
南投縣	493
苗栗縣	484
新竹縣	470
宜蘭縣	431
新竹市	356
花蓮縣	337
基隆市	285
臺東縣	236
嘉義市	198
澎湖縣	120
金門縣	95
連江縣	10
```

## 04. Based on the previous query result, write a SQL statement that is able to filter counties with more than 1000 polling places given `taiwan_election_2024.db`.

```
county	number_of_polling_place
新北市	2681
高雄市	2038
臺中市	1902
臺北市	1764
臺南市	1548
桃園市	1384
彰化縣	1085
```

## 05. Write a SQL statement that is able to count the number of candidates for regional legislators for each party given `taiwan_election_2024.db`.

```
party_name	number_of_candidates
民主進步黨	69
無	65
中國國民黨	64
制度救世島	12
臺灣雙語無法黨	10
小民參政歐巴桑聯盟	10
司法改革黨	10
台灣維新	10
台灣民眾黨	10
人民最大黨	10
中華統一促進黨	10
復康聯盟黨	4
時代力量	2
台灣麻將最大黨	2
台灣基進	2
勞動黨	2
興中同盟會	1
經濟黨	1
社會民主黨	1
新黨	1
家庭基本收入	1
喜樂島聯盟	1
合一行動聯盟	1
司法正義黨	1
台灣革命黨	1
台灣綠黨	1
台灣整復師聯盟工黨	1
台灣國民黨	1
人民民主黨	1
中華聯合黨	1
中華文化共和黨	1
中華愛國同心黨	1
中華婦女黨	1
```

## 06. Based on the previous query result, write a SQL statement that is able to filter parties with more than 10 nominated candidates given `taiwan_election_2024.db`.

```
party_name	number_of_candidates
民主進步黨	69
無	65
中國國民黨	64
制度救世島	12
臺灣雙語無法黨	10
小民參政歐巴桑聯盟	10
司法改革黨	10
台灣維新	10
台灣民眾黨	10
人民最大黨	10
中華統一促進黨	10
```

## 07. Write a SQL statement that is able to show the result of regional legislators election in Taipei City given `taiwan_election_2024.db`.

```
county	legislator_region	number	party	name	sum_votes
臺北市	臺北市第1選舉區	1	民主進步黨	吳思瑤	91958
臺北市	臺北市第1選舉區	2	中國國民黨	張斯綱	71837
臺北市	臺北市第1選舉區	3	人民民主黨	賴宗育	836
臺北市	臺北市第1選舉區	4	無	侯漢廷	28510
臺北市	臺北市第1選舉區	5	人民最大黨	張臺勝	161
臺北市	臺北市第1選舉區	6	人民最大黨	胡金城	255
臺北市	臺北市第1選舉區	7	無	許盛鋒	231
臺北市	臺北市第1選舉區	8	臺灣雙語無法黨	陳執中	950
臺北市	臺北市第2選舉區	1	制度救世島	熊嘉玲	968
臺北市	臺北市第2選舉區	2	人民最大黨	何梅娟	1741
臺北市	臺北市第2選舉區	3	民主進步黨	王世堅	111605
臺北市	臺北市第2選舉區	4	中華統一促進黨	郭啟源	305
臺北市	臺北市第2選舉區	5	中國國民黨	游淑慧	69754
臺北市	臺北市第3選舉區	1	人民最大黨	余新造	596
臺北市	臺北市第3選舉區	2	無	陳源發	1851
臺北市	臺北市第3選舉區	3	民主進步黨	謝佩芬	89850
臺北市	臺北市第3選舉區	4	制度救世島	高士恩	195
臺北市	臺北市第3選舉區	5	中國國民黨	王鴻薇	105050
臺北市	臺北市第3選舉區	6	台灣維新	楊時睿	1378
臺北市	臺北市第3選舉區	7	臺灣雙語無法黨	陳一郎	1107
臺北市	臺北市第4選舉區	1	中國國民黨	李彥秀	112743
臺北市	臺北市第4選舉區	2	台灣基進	吳欣岱	26382
臺北市	臺北市第4選舉區	3	民主進步黨	高嘉瑜	95241
臺北市	臺北市第4選舉區	4	制度救世島	黃啟彬	422
臺北市	臺北市第4選舉區	5	台灣整復師聯盟工黨	林秋彤	1881
臺北市	臺北市第5選舉區	1	中國國民黨	鍾小平	57634
臺北市	臺北市第5選舉區	2	無	陳燕玉	194
臺北市	臺北市第5選舉區	3	合一行動聯盟	許敬民	174
臺北市	臺北市第5選舉區	4	無	林志成	138
臺北市	臺北市第5選舉區	5	無	于美人	38913
臺北市	臺北市第5選舉區	6	經濟黨	蘇諍	472
臺北市	臺北市第5選舉區	7	民主進步黨	吳沛憶	66932
臺北市	臺北市第5選舉區	8	無	孫智麗	1489
臺北市	臺北市第5選舉區	9	台灣麻將最大黨	張華特	692
臺北市	臺北市第5選舉區	10	司法改革黨	李慧曦	1502
臺北市	臺北市第6選舉區	1	制度救世島	張雪卿	896
臺北市	臺北市第6選舉區	2	社會民主黨	苗博雅	74375
臺北市	臺北市第6選舉區	3	臺灣雙語無法黨	崔建章	2202
臺北市	臺北市第6選舉區	4	中國國民黨	羅智強	87973
臺北市	臺北市第6選舉區	5	台灣維新	朱翊銘	660
臺北市	臺北市第7選舉區	1	中華愛國同心黨	李承龍	310
臺北市	臺北市第7選舉區	2	中國國民黨	徐巧芯	89727
臺北市	臺北市第7選舉區	3	台灣維新	羅丹	1073
臺北市	臺北市第7選舉區	4	無	陳韋安	3286
臺北市	臺北市第7選舉區	5	民主進步黨	許淑華	76113
臺北市	臺北市第8選舉區	1	台灣維新	劉佩玲	1122
臺北市	臺北市第8選舉區	2	中國國民黨	賴士葆	87099
臺北市	臺北市第8選舉區	3	民主進步黨	王閔生	59490
臺北市	臺北市第8選舉區	4	小民參政歐巴桑聯盟	賴宣任	6374
臺北市	臺北市第8選舉區	5	無	夏萬浪	761
臺北市	臺北市第8選舉區	6	台灣民眾黨	張其祿	28335
臺北市	臺北市第8選舉區	7	無	張維學	201
臺北市	臺北市第8選舉區	8	興中同盟會	胡之壯	136
```

## 08. Based on the previous query result, write a SQL statement that is able to show the regional legislators elected in Taipei City given `taiwan_election_2024.db`.

```
county	legislator_region	number	party	name	sum_votes
臺北市	臺北市第1選舉區	1	民主進步黨	吳思瑤	91958
臺北市	臺北市第2選舉區	3	民主進步黨	王世堅	111605
臺北市	臺北市第3選舉區	5	中國國民黨	王鴻薇	105050
臺北市	臺北市第4選舉區	1	中國國民黨	李彥秀	112743
臺北市	臺北市第5選舉區	7	民主進步黨	吳沛憶	66932
臺北市	臺北市第6選舉區	4	中國國民黨	羅智強	87973
臺北市	臺北市第7選舉區	2	中國國民黨	徐巧芯	89727
臺北市	臺北市第8選舉區	2	中國國民黨	賴士葆	87099
```

## 09. Write a SQL statement that is able to show the vote percentage of party legislators for each party and re-group party that is not gonna receive subsidies as `'其他'` given `taiwan_election_2024.db`.

```
party	votes_percentage
民主進步黨	0.3616
中國國民黨	0.3458
台灣民眾黨	0.2207
其他	0.0718
```

## 10. Write a SQL statement that is able to show the vote percentage of presidential, regional legislators and party legislators for 3 major parties given `taiwan_election_2024.db`.

```
election_type	party	votes_percentage
不分區立委	中國國民黨	0.3458
不分區立委	台灣民眾黨	0.2207
不分區立委	民主進步黨	0.3616
區域立委	中國國民黨	0.4042
區域立委	台灣民眾黨	0.0297
區域立委	民主進步黨	0.4517
總統/副總統	中國國民黨	0.3349
總統/副總統	台灣民眾黨	0.2646
總統/副總統	民主進步黨	0.4005
```