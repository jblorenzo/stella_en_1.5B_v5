---
model-index:
- name: stella_en_1.5B_v5
  results:
  - dataset:
      config: en
      name: MTEB AmazonCounterfactualClassification (en)
      revision: e8379541af4e31359cca9fbcf4b00f2671dba205
      split: test
      type: mteb/amazon_counterfactual
    metrics:
    - type: accuracy
      value: 92.86567164179104
    - type: ap
      value: 72.13503907102613
    - type: ap_weighted
      value: 72.13503907102613
    - type: f1
      value: 89.5586886376355
    - type: f1_weighted
      value: 93.13621183004571
    - type: main_score
      value: 92.86567164179104
    task:
      type: Classification
  - dataset:
      config: default
      name: MTEB AmazonPolarityClassification
      revision: e2d317d38cd51312af73b3d32a06d1a08b442046
      split: test
      type: mteb/amazon_polarity
    metrics:
    - type: accuracy
      value: 97.16485
    - type: ap
      value: 96.05546315415225
    - type: ap_weighted
      value: 96.05546315415225
    - type: f1
      value: 97.16351087403213
    - type: f1_weighted
      value: 97.16351087403213
    - type: main_score
      value: 97.16485
    task:
      type: Classification
  - dataset:
      config: en
      name: MTEB AmazonReviewsClassification (en)
      revision: 1399c76144fd37290681b995c656ef9b2e06e26d
      split: test
      type: mteb/amazon_reviews_multi
    metrics:
    - type: accuracy
      value: 59.358
    - type: f1
      value: 59.0264615883114
    - type: f1_weighted
      value: 59.0264615883114
    - type: main_score
      value: 59.358
    task:
      type: Classification
  - dataset:
      config: en
      name: MTEB AmazonReviewsClassification (en)
      revision: 1399c76144fd37290681b995c656ef9b2e06e26d
      split: validation
      type: mteb/amazon_reviews_multi
    metrics:
    - type: accuracy
      value: 59.54200000000001
    - type: f1
      value: 59.20552246033062
    - type: f1_weighted
      value: 59.20552246033062
    - type: main_score
      value: 59.54200000000001
    task:
      type: Classification
  - dataset:
      config: default
      name: MTEB ArguAna
      revision: c22ab2a51041ffd869aaddef7af8d8215647e41a
      split: test
      type: mteb/arguana
    metrics:
    - type: main_score
      value: 65.269
    - type: map_at_1
      value: 41.607
    - type: map_at_10
      value: 57.104
    - type: map_at_100
      value: 57.621
    - type: map_at_1000
      value: 57.621
    - type: map_at_20
      value: 57.533
    - type: map_at_3
      value: 52.891999999999996
    - type: map_at_5
      value: 55.371
    - type: mrr_at_1
      value: 42.318634423897585
    - type: mrr_at_10
      value: 57.353970511865406
    - type: mrr_at_100
      value: 57.88398078476526
    - type: mrr_at_1000
      value: 57.88467807648422
    - type: mrr_at_20
      value: 57.796730533206166
    - type: mrr_at_3
      value: 53.200568990042775
    - type: mrr_at_5
      value: 55.6330014224753
    - type: nauc_map_at_1000_diff1
      value: 24.54414600428287
    - type: nauc_map_at_1000_max
      value: -8.389738078358459
    - type: nauc_map_at_1000_std
      value: -18.188787645801366
    - type: nauc_map_at_100_diff1
      value: 24.543138576462308
    - type: nauc_map_at_100_max
      value: -8.390896839752044
    - type: nauc_map_at_100_std
      value: -18.192549240185247
    - type: nauc_map_at_10_diff1
      value: 24.219607088995822
    - type: nauc_map_at_10_max
      value: -8.245734391254308
    - type: nauc_map_at_10_std
      value: -18.229706566466447
    - type: nauc_map_at_1_diff1
      value: 29.325201664812788
    - type: nauc_map_at_1_max
      value: -11.742800494823971
    - type: nauc_map_at_1_std
      value: -18.610215769702528
    - type: nauc_map_at_20_diff1
      value: 24.471097562798803
    - type: nauc_map_at_20_max
      value: -8.318035874000799
    - type: nauc_map_at_20_std
      value: -18.171541096773108
    - type: nauc_map_at_3_diff1
      value: 24.275846107642824
    - type: nauc_map_at_3_max
      value: -8.212242049581894
    - type: nauc_map_at_3_std
      value: -17.920379368937496
    - type: nauc_map_at_5_diff1
      value: 23.873692493209255
    - type: nauc_map_at_5_max
      value: -8.110347163828767
    - type: nauc_map_at_5_std
      value: -18.20863325596931
    - type: nauc_mrr_at_1000_diff1
      value: 22.656410956419975
    - type: nauc_mrr_at_1000_max
      value: -8.924888102233243
    - type: nauc_mrr_at_1000_std
      value: -18.103674384502526
    - type: nauc_mrr_at_100_diff1
      value: 22.655448817140968
    - type: nauc_mrr_at_100_max
      value: -8.926034318499038
    - type: nauc_mrr_at_100_std
      value: -18.10743930104164
    - type: nauc_mrr_at_10_diff1
      value: 22.297536272996872
    - type: nauc_mrr_at_10_max
      value: -8.836407556658274
    - type: nauc_mrr_at_10_std
      value: -18.1598393044477
    - type: nauc_mrr_at_1_diff1
      value: 27.419572424489708
    - type: nauc_mrr_at_1_max
      value: -11.42241314820691
    - type: nauc_mrr_at_1_std
      value: -18.54893865856313
    - type: nauc_mrr_at_20_diff1
      value: 22.590227214657418
    - type: nauc_mrr_at_20_max
      value: -8.849986456376993
    - type: nauc_mrr_at_20_std
      value: -18.0862391777352
    - type: nauc_mrr_at_3_diff1
      value: 22.415270167774988
    - type: nauc_mrr_at_3_max
      value: -8.692871854156435
    - type: nauc_mrr_at_3_std
      value: -17.6740102891955
    - type: nauc_mrr_at_5_diff1
      value: 21.96284578521464
    - type: nauc_mrr_at_5_max
      value: -8.757031535546025
    - type: nauc_mrr_at_5_std
      value: -18.210766964081294
    - type: nauc_ndcg_at_1000_diff1
      value: 23.939400161569115
    - type: nauc_ndcg_at_1000_max
      value: -7.866999120512983
    - type: nauc_ndcg_at_1000_std
      value: -17.981457019643617
    - type: nauc_ndcg_at_100_diff1
      value: 23.920033349619317
    - type: nauc_ndcg_at_100_max
      value: -7.889849409678031
    - type: nauc_ndcg_at_100_std
      value: -18.054931990360537
    - type: nauc_ndcg_at_10_diff1
      value: 22.543020461303534
    - type: nauc_ndcg_at_10_max
      value: -7.072111788010867
    - type: nauc_ndcg_at_10_std
      value: -18.26397604573537
    - type: nauc_ndcg_at_1_diff1
      value: 29.325201664812788
    - type: nauc_ndcg_at_1_max
      value: -11.742800494823971
    - type: nauc_ndcg_at_1_std
      value: -18.610215769702528
    - type: nauc_ndcg_at_20_diff1
      value: 23.551587021207972
    - type: nauc_ndcg_at_20_max
      value: -7.298056222649139
    - type: nauc_ndcg_at_20_std
      value: -18.056004880930608
    - type: nauc_ndcg_at_3_diff1
      value: 22.669089506345273
    - type: nauc_ndcg_at_3_max
      value: -7.278024373570137
    - type: nauc_ndcg_at_3_std
      value: -17.816657759914193
    - type: nauc_ndcg_at_5_diff1
      value: 21.72619728226575
    - type: nauc_ndcg_at_5_max
      value: -6.959741647471228
    - type: nauc_ndcg_at_5_std
      value: -18.35173705190235
    - type: nauc_precision_at_1000_diff1
      value: 5.0388241058076995
    - type: nauc_precision_at_1000_max
      value: 34.439879624882145
    - type: nauc_precision_at_1000_std
      value: 77.22610895194498
    - type: nauc_precision_at_100_diff1
      value: 1.340670767252794
    - type: nauc_precision_at_100_max
      value: 19.30870025961241
    - type: nauc_precision_at_100_std
      value: 35.37688289157788
    - type: nauc_precision_at_10_diff1
      value: 7.734227153124332
    - type: nauc_precision_at_10_max
      value: 4.202399088422237
    - type: nauc_precision_at_10_std
      value: -18.383890254046698
    - type: nauc_precision_at_1_diff1
      value: 29.325201664812788
    - type: nauc_precision_at_1_max
      value: -11.742800494823971
    - type: nauc_precision_at_1_std
      value: -18.610215769702528
    - type: nauc_precision_at_20_diff1
      value: 9.48070999361637
    - type: nauc_precision_at_20_max
      value: 19.056709637253025
    - type: nauc_precision_at_20_std
      value: -13.266821166159485
    - type: nauc_precision_at_3_diff1
      value: 17.245260303409747
    - type: nauc_precision_at_3_max
      value: -4.202455033452335
    - type: nauc_precision_at_3_std
      value: -17.514264039955332
    - type: nauc_precision_at_5_diff1
      value: 12.074628162049974
    - type: nauc_precision_at_5_max
      value: -1.9145501461107832
    - type: nauc_precision_at_5_std
      value: -19.162525528916344
    - type: nauc_recall_at_1000_diff1
      value: 5.038824105805915
    - type: nauc_recall_at_1000_max
      value: 34.43987962487738
    - type: nauc_recall_at_1000_std
      value: 77.22610895193765
    - type: nauc_recall_at_100_diff1
      value: 1.3406707672497025
    - type: nauc_recall_at_100_max
      value: 19.30870025960776
    - type: nauc_recall_at_100_std
      value: 35.37688289157515
    - type: nauc_recall_at_10_diff1
      value: 7.734227153124366
    - type: nauc_recall_at_10_max
      value: 4.202399088421976
    - type: nauc_recall_at_10_std
      value: -18.38389025404673
    - type: nauc_recall_at_1_diff1
      value: 29.325201664812788
    - type: nauc_recall_at_1_max
      value: -11.742800494823971
    - type: nauc_recall_at_1_std
      value: -18.610215769702528
    - type: nauc_recall_at_20_diff1
      value: 9.480709993616845
    - type: nauc_recall_at_20_max
      value: 19.05670963725301
    - type: nauc_recall_at_20_std
      value: -13.266821166158651
    - type: nauc_recall_at_3_diff1
      value: 17.24526030340978
    - type: nauc_recall_at_3_max
      value: -4.202455033452323
    - type: nauc_recall_at_3_std
      value: -17.51426403995538
    - type: nauc_recall_at_5_diff1
      value: 12.074628162049992
    - type: nauc_recall_at_5_max
      value: -1.914550146110865
    - type: nauc_recall_at_5_std
      value: -19.162525528916362
    - type: ndcg_at_1
      value: 41.607
    - type: ndcg_at_10
      value: 65.269
    - type: ndcg_at_100
      value: 67.289
    - type: ndcg_at_1000
      value: 67.29899999999999
    - type: ndcg_at_20
      value: 66.76299999999999
    - type: ndcg_at_3
      value: 56.604
    - type: ndcg_at_5
      value: 61.07900000000001
    - type: precision_at_1
      value: 41.607
    - type: precision_at_10
      value: 9.118
    - type: precision_at_100
      value: 0.996
    - type: precision_at_1000
      value: 0.1
    - type: precision_at_20
      value: 4.8469999999999995
    - type: precision_at_3
      value: 22.451
    - type: precision_at_5
      value: 15.647
    - type: recall_at_1
      value: 41.607
    - type: recall_at_10
      value: 91.181
    - type: recall_at_100
      value: 99.57300000000001
    - type: recall_at_1000
      value: 99.644
    - type: recall_at_20
      value: 96.942
    - type: recall_at_3
      value: 67.354
    - type: recall_at_5
      value: 78.236
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB ArxivClusteringP2P
      revision: a122ad7f3f0291bf49cc6f4d32aa80929df69d5d
      split: test
      type: mteb/arxiv-clustering-p2p
    metrics:
    - type: main_score
      value: 55.437138353189994
    - type: v_measure
      value: 55.437138353189994
    - type: v_measure_std
      value: 14.718556601335491
    task:
      type: Clustering
  - dataset:
      config: default
      name: MTEB ArxivClusteringS2S
      revision: f910caf1a6075f7329cdf8c1a6135696f37dbd53
      split: test
      type: mteb/arxiv-clustering-s2s
    metrics:
    - type: main_score
      value: 50.65858459544658
    - type: v_measure
      value: 50.65858459544658
    - type: v_measure_std
      value: 14.887033747525146
    task:
      type: Clustering
  - dataset:
      config: default
      name: MTEB AskUbuntuDupQuestions
      revision: 2000358ca161889fa9c082cb41daa8dcfb161a54
      split: test
      type: mteb/askubuntudupquestions-reranking
    metrics:
    - type: main_score
      value: 67.32597152838535
    - type: map
      value: 67.32597152838535
    - type: mrr
      value: 78.98683111286988
    - type: nAUC_map_diff1
      value: 16.8624639710487
    - type: nAUC_map_max
      value: 24.91996491142433
    - type: nAUC_map_std
      value: 17.91865808793225
    - type: nAUC_mrr_diff1
      value: 25.03766425631947
    - type: nAUC_mrr_max
      value: 41.64561939958336
    - type: nAUC_mrr_std
      value: 23.179909345891968
    task:
      type: Reranking
  - dataset:
      config: default
      name: MTEB BIOSSES
      revision: d3fb88f8f02e40887cd149695127462bbcf29b4a
      split: test
      type: mteb/biosses-sts
    metrics:
    - type: cosine_pearson
      value: 85.790820496042
    - type: cosine_spearman
      value: 83.10731534330517
    - type: euclidean_pearson
      value: 84.61741304343133
    - type: euclidean_spearman
      value: 83.17297949010973
    - type: main_score
      value: 83.10731534330517
    - type: manhattan_pearson
      value: 85.2137696526676
    - type: manhattan_spearman
      value: 84.39168195786738
    - type: pearson
      value: 85.790820496042
    - type: spearman
      value: 83.10731534330517
    task:
      type: STS
  - dataset:
      config: default
      name: MTEB Banking77Classification
      revision: 0fd18e25b25c072e09e0d92ab615fda904d66300
      split: test
      type: mteb/banking77
    metrics:
    - type: accuracy
      value: 89.78896103896105
    - type: f1
      value: 89.76107366333488
    - type: f1_weighted
      value: 89.76107366333488
    - type: main_score
      value: 89.78896103896105
    task:
      type: Classification
  - dataset:
      config: default
      name: MTEB BiorxivClusteringP2P
      revision: 65b79d1d13f80053f67aca9498d9402c2d9f1f40
      split: test
      type: mteb/biorxiv-clustering-p2p
    metrics:
    - type: main_score
      value: 50.68092296236376
    - type: v_measure
      value: 50.68092296236376
    - type: v_measure_std
      value: 0.7832640983085436
    task:
      type: Clustering
  - dataset:
      config: default
      name: MTEB BiorxivClusteringS2S
      revision: 258694dd0231531bc1fd9de6ceb52a0853c6d908
      split: test
      type: mteb/biorxiv-clustering-s2s
    metrics:
    - type: main_score
      value: 46.86629236732983
    - type: v_measure
      value: 46.86629236732983
    - type: v_measure_std
      value: 0.8784322236350974
    task:
      type: Clustering
  - dataset:
      config: default
      name: MTEB CQADupstackAndroidRetrieval
      revision: f46a197baaae43b4f621051089b82a364682dfeb
      split: test
      type: mteb/cqadupstack-android
    metrics:
    - type: main_score
      value: 55.698
    - type: map_at_1
      value: 34.943000000000005
    - type: map_at_10
      value: 48.412
    - type: map_at_100
      value: 50.015
    - type: map_at_1000
      value: 50.124
    - type: map_at_20
      value: 49.349
    - type: map_at_3
      value: 43.921
    - type: map_at_5
      value: 46.495999999999995
    - type: mrr_at_1
      value: 43.776824034334766
    - type: mrr_at_10
      value: 54.878568022344844
    - type: mrr_at_100
      value: 55.48878141977723
    - type: mrr_at_1000
      value: 55.52247635710942
    - type: mrr_at_20
      value: 55.24539198226065
    - type: mrr_at_3
      value: 52.122079160705745
    - type: mrr_at_5
      value: 53.69575584167856
    - type: nauc_map_at_1000_diff1
      value: 54.83637631494736
    - type: nauc_map_at_1000_max
      value: 35.52458743218728
    - type: nauc_map_at_1000_std
      value: -7.275819984945678
    - type: nauc_map_at_100_diff1
      value: 54.8368163650723
    - type: nauc_map_at_100_max
      value: 35.51429313293532
    - type: nauc_map_at_100_std
      value: -7.209081495342137
    - type: nauc_map_at_10_diff1
      value: 54.571251045523695
    - type: nauc_map_at_10_max
      value: 35.13594763369283
    - type: nauc_map_at_10_std
      value: -8.062736192082145
    - type: nauc_map_at_1_diff1
      value: 61.86437489279821
    - type: nauc_map_at_1_max
      value: 30.837576154277528
    - type: nauc_map_at_1_std
      value: -10.802149792652855
    - type: nauc_map_at_20_diff1
      value: 54.80239774838164
    - type: nauc_map_at_20_max
      value: 35.307069496896524
    - type: nauc_map_at_20_std
      value: -7.5590600480201084
    - type: nauc_map_at_3_diff1
      value: 56.30342166194192
    - type: nauc_map_at_3_max
      value: 33.93416925095916
    - type: nauc_map_at_3_std
      value: -9.895585975112043
    - type: nauc_map_at_5_diff1
      value: 55.13469955491529
    - type: nauc_map_at_5_max
      value: 34.56062736964534
    - type: nauc_map_at_5_std
      value: -8.468279768763258
    - type: nauc_mrr_at_1000_diff1
      value: 54.35779422379845
    - type: nauc_mrr_at_1000_max
      value: 38.00754831524994
    - type: nauc_mrr_at_1000_std
      value: -6.718471256413226
    - type: nauc_mrr_at_100_diff1
      value: 54.340708492510146
    - type: nauc_mrr_at_100_max
      value: 38.01292132503959
    - type: nauc_mrr_at_100_std
      value: -6.681495135209198
    - type: nauc_mrr_at_10_diff1
      value: 53.94275962175614
    - type: nauc_mrr_at_10_max
      value: 38.09414773152168
    - type: nauc_mrr_at_10_std
      value: -6.794616916068954
    - type: nauc_mrr_at_1_diff1
      value: 60.852338909452264
    - type: nauc_mrr_at_1_max
      value: 38.96584368509479
    - type: nauc_mrr_at_1_std
      value: -10.045964915794114
    - type: nauc_mrr_at_20_diff1
      value: 54.245719828208
    - type: nauc_mrr_at_20_max
      value: 37.98399031096221
    - type: nauc_mrr_at_20_std
      value: -6.631646361390074
    - type: nauc_mrr_at_3_diff1
      value: 54.943819112748315
    - type: nauc_mrr_at_3_max
      value: 38.72670310558506
    - type: nauc_mrr_at_3_std
      value: -7.3047984890023105
    - type: nauc_mrr_at_5_diff1
      value: 54.12052762196357
    - type: nauc_mrr_at_5_max
      value: 37.98864287763163
    - type: nauc_mrr_at_5_std
      value: -6.9053220503659265
    - type: nauc_ndcg_at_1000_diff1
      value: 53.168521840294005
    - type: nauc_ndcg_at_1000_max
      value: 36.25929234058774
    - type: nauc_ndcg_at_1000_std
      value: -5.01113875093572
    - type: nauc_ndcg_at_100_diff1
      value: 52.97172317197053
    - type: nauc_ndcg_at_100_max
      value: 36.292559404355615
    - type: nauc_ndcg_at_100_std
      value: -3.9936833034645867
    - type: nauc_ndcg_at_10_diff1
      value: 51.38148105179765
    - type: nauc_ndcg_at_10_max
      value: 35.88586827346375
    - type: nauc_ndcg_at_10_std
      value: -6.673784797732396
    - type: nauc_ndcg_at_1_diff1
      value: 60.852338909452264
    - type: nauc_ndcg_at_1_max
      value: 38.96584368509479
    - type: nauc_ndcg_at_1_std
      value: -10.045964915794114
    - type: nauc_ndcg_at_20_diff1
      value: 52.371052429309785
    - type: nauc_ndcg_at_20_max
      value: 35.6004937406994
    - type: nauc_ndcg_at_20_std
      value: -5.425915580039577
    - type: nauc_ndcg_at_3_diff1
      value: 53.2680031129826
    - type: nauc_ndcg_at_3_max
      value: 36.53325082761763
    - type: nauc_ndcg_at_3_std
      value: -7.827726412361283
    - type: nauc_ndcg_at_5_diff1
      value: 52.16973047122866
    - type: nauc_ndcg_at_5_max
      value: 35.54372983982979
    - type: nauc_ndcg_at_5_std
      value: -6.550536192290274
    - type: nauc_precision_at_1000_diff1
      value: -23.803635566071492
    - type: nauc_precision_at_1000_max
      value: -4.4680884323262084
    - type: nauc_precision_at_1000_std
      value: -5.4782877211099406
    - type: nauc_precision_at_100_diff1
      value: -15.735126039786982
    - type: nauc_precision_at_100_max
      value: 5.745419801082826
    - type: nauc_precision_at_100_std
      value: 7.527025248717274
    - type: nauc_precision_at_10_diff1
      value: 0.820392313600132
    - type: nauc_precision_at_10_max
      value: 22.514672565277618
    - type: nauc_precision_at_10_std
      value: 5.930871763593499
    - type: nauc_precision_at_1_diff1
      value: 60.852338909452264
    - type: nauc_precision_at_1_max
      value: 38.96584368509479
    - type: nauc_precision_at_1_std
      value: -10.045964915794114
    - type: nauc_precision_at_20_diff1
      value: -4.270036607143178
    - type: nauc_precision_at_20_max
      value: 16.365591570487123
    - type: nauc_precision_at_20_std
      value: 9.468602942722748
    - type: nauc_precision_at_3_diff1
      value: 26.02073484847779
    - type: nauc_precision_at_3_max
      value: 34.39412841152471
    - type: nauc_precision_at_3_std
      value: -1.2152655666245264
    - type: nauc_precision_at_5_diff1
      value: 13.669777177024686
    - type: nauc_precision_at_5_max
      value: 29.651219124693423
    - type: nauc_precision_at_5_std
      value: 4.454255364596209
    - type: nauc_recall_at_1000_diff1
      value: 37.8260265620583
    - type: nauc_recall_at_1000_max
      value: 17.510564767254742
    - type: nauc_recall_at_1000_std
      value: 53.12083608928702
    - type: nauc_recall_at_100_diff1
      value: 40.133033351680965
    - type: nauc_recall_at_100_max
      value: 30.191343697115702
    - type: nauc_recall_at_100_std
      value: 27.18528385298577
    - type: nauc_recall_at_10_diff1
      value: 38.05790273348577
    - type: nauc_recall_at_10_max
      value: 30.04513821395271
    - type: nauc_recall_at_10_std
      value: -3.5287672176113567
    - type: nauc_recall_at_1_diff1
      value: 61.86437489279821
    - type: nauc_recall_at_1_max
      value: 30.837576154277528
    - type: nauc_recall_at_1_std
      value: -10.802149792652855
    - type: nauc_recall_at_20_diff1
      value: 39.79776828661499
    - type: nauc_recall_at_20_max
      value: 27.6538881802111
    - type: nauc_recall_at_20_std
      value: 2.750348903039602
    - type: nauc_recall_at_3_diff1
      value: 48.62286391030405
    - type: nauc_recall_at_3_max
      value: 31.93639897872922
    - type: nauc_recall_at_3_std
      value: -8.01788709199078
    - type: nauc_recall_at_5_diff1
      value: 43.1218258316952
    - type: nauc_recall_at_5_max
      value: 29.31823884354994
    - type: nauc_recall_at_5_std
      value: -4.156997758846112
    - type: ndcg_at_1
      value: 43.777
    - type: ndcg_at_10
      value: 55.698
    - type: ndcg_at_100
      value: 60.681
    - type: ndcg_at_1000
      value: 61.966
    - type: ndcg_at_20
      value: 57.730000000000004
    - type: ndcg_at_3
      value: 49.725
    - type: ndcg_at_5
      value: 52.527
    - type: precision_at_1
      value: 43.777
    - type: precision_at_10
      value: 11.144
    - type: precision_at_100
      value: 1.685
    - type: precision_at_1000
      value: 0.209
    - type: precision_at_20
      value: 6.4879999999999995
    - type: precision_at_3
      value: 24.654
    - type: precision_at_5
      value: 18.026
    - type: recall_at_1
      value: 34.943000000000005
    - type: recall_at_10
      value: 69.333
    - type: recall_at_100
      value: 90.153
    - type: recall_at_1000
      value: 97.761
    - type: recall_at_20
      value: 76.753
    - type: recall_at_3
      value: 51.815999999999995
    - type: recall_at_5
      value: 59.589999999999996
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB CQADupstackEnglishRetrieval
      revision: ad9991cb51e31e31e430383c75ffb2885547b5f0
      split: test
      type: mteb/cqadupstack-english
    metrics:
    - type: main_score
      value: 54.730000000000004
    - type: map_at_1
      value: 36.288
    - type: map_at_10
      value: 48.618
    - type: map_at_100
      value: 49.9
    - type: map_at_1000
      value: 50.03300000000001
    - type: map_at_20
      value: 49.345
    - type: map_at_3
      value: 45.318000000000005
    - type: map_at_5
      value: 47.103
    - type: mrr_at_1
      value: 46.496815286624205
    - type: mrr_at_10
      value: 55.0120564149227
    - type: mrr_at_100
      value: 55.637173112842866
    - type: mrr_at_1000
      value: 55.669818563530114
    - type: mrr_at_20
      value: 55.42145889032171
    - type: mrr_at_3
      value: 53.078556263269704
    - type: mrr_at_5
      value: 54.161358811040415
    - type: nauc_map_at_1000_diff1
      value: 56.46689280524137
    - type: nauc_map_at_1000_max
      value: 39.66778030566005
    - type: nauc_map_at_1000_std
      value: -2.2939456265123828
    - type: nauc_map_at_100_diff1
      value: 56.40682470243544
    - type: nauc_map_at_100_max
      value: 39.56961568857141
    - type: nauc_map_at_100_std
      value: -2.3632146801518235
    - type: nauc_map_at_10_diff1
      value: 56.75288379552944
    - type: nauc_map_at_10_max
      value: 38.61429494642159
    - type: nauc_map_at_10_std
      value: -3.862190076586902
    - type: nauc_map_at_1_diff1
      value: 60.36308471991815
    - type: nauc_map_at_1_max
      value: 33.39652804870031
    - type: nauc_map_at_1_std
      value: -9.62291874243431
    - type: nauc_map_at_20_diff1
      value: 56.44462833837671
    - type: nauc_map_at_20_max
      value: 39.11778890218465
    - type: nauc_map_at_20_std
      value: -3.0343797268212054
    - type: nauc_map_at_3_diff1
      value: 57.34460734939674
    - type: nauc_map_at_3_max
      value: 36.695176518865495
    - type: nauc_map_at_3_std
      value: -5.8079837040109865
    - type: nauc_map_at_5_diff1
      value: 56.73705905593219
    - type: nauc_map_at_5_max
      value: 37.75982310638613
    - type: nauc_map_at_5_std
      value: -5.057985215317977
    - type: nauc_mrr_at_1000_diff1
      value: 56.016293504605805
    - type: nauc_mrr_at_1000_max
      value: 43.960790448380294
    - type: nauc_mrr_at_1000_std
      value: 1.5286262952131746
    - type: nauc_mrr_at_100_diff1
      value: 56.00993533595076
    - type: nauc_mrr_at_100_max
      value: 43.953682537073625
    - type: nauc_mrr_at_100_std
      value: 1.5310645990691607
    - type: nauc_mrr_at_10_diff1
      value: 56.181066861680215
    - type: nauc_mrr_at_10_max
      value: 43.95237703645959
    - type: nauc_mrr_at_10_std
      value: 1.3126969313493262
    - type: nauc_mrr_at_1_diff1
      value: 59.345462167260536
    - type: nauc_mrr_at_1_max
      value: 45.198742402012144
    - type: nauc_mrr_at_1_std
      value: -1.975434919304149
    - type: nauc_mrr_at_20_diff1
      value: 56.04021587849311
    - type: nauc_mrr_at_20_max
      value: 43.97948850003455
    - type: nauc_mrr_at_20_std
      value: 1.462103753821496
    - type: nauc_mrr_at_3_diff1
      value: 56.28010458787395
    - type: nauc_mrr_at_3_max
      value: 44.359236223927105
    - type: nauc_mrr_at_3_std
      value: 0.98947895791584
    - type: nauc_mrr_at_5_diff1
      value: 56.18152155505639
    - type: nauc_mrr_at_5_max
      value: 44.03436861076891
    - type: nauc_mrr_at_5_std
      value: 1.193246119558553
    - type: nauc_ndcg_at_1000_diff1
      value: 54.686969440539116
    - type: nauc_ndcg_at_1000_max
      value: 41.45245665688911
    - type: nauc_ndcg_at_1000_std
      value: 2.6709494808988894
    - type: nauc_ndcg_at_100_diff1
      value: 54.49115436097919
    - type: nauc_ndcg_at_100_max
      value: 40.84273939882796
    - type: nauc_ndcg_at_100_std
      value: 2.5232491452761003
    - type: nauc_ndcg_at_10_diff1
      value: 55.60099783321824
    - type: nauc_ndcg_at_10_max
      value: 40.687096005915954
    - type: nauc_ndcg_at_10_std
      value: 0.14134743575996547
    - type: nauc_ndcg_at_1_diff1
      value: 59.345462167260536
    - type: nauc_ndcg_at_1_max
      value: 45.198742402012144
    - type: nauc_ndcg_at_1_std
      value: -1.975434919304149
    - type: nauc_ndcg_at_20_diff1
      value: 54.91962043024918
    - type: nauc_ndcg_at_20_max
      value: 40.75948662832124
    - type: nauc_ndcg_at_20_std
      value: 1.281515340695552
    - type: nauc_ndcg_at_3_diff1
      value: 54.894656566662626
    - type: nauc_ndcg_at_3_max
      value: 40.98054458005936
    - type: nauc_ndcg_at_3_std
      value: -1.1958948027573943
    - type: nauc_ndcg_at_5_diff1
      value: 55.206210616924714
    - type: nauc_ndcg_at_5_max
      value: 40.81520447097436
    - type: nauc_ndcg_at_5_std
      value: -1.2189120404114255
    - type: nauc_precision_at_1000_diff1
      value: -11.06463142836882
    - type: nauc_precision_at_1000_max
      value: 16.85242202440994
    - type: nauc_precision_at_1000_std
      value: 22.254962216674095
    - type: nauc_precision_at_100_diff1
      value: -5.889681335605225
    - type: nauc_precision_at_100_max
      value: 25.013547959542688
    - type: nauc_precision_at_100_std
      value: 28.4550925229075
    - type: nauc_precision_at_10_diff1
      value: 9.552608749535276
    - type: nauc_precision_at_10_max
      value: 32.843831329780656
    - type: nauc_precision_at_10_std
      value: 20.18163651010038
    - type: nauc_precision_at_1_diff1
      value: 59.345462167260536
    - type: nauc_precision_at_1_max
      value: 45.198742402012144
    - type: nauc_precision_at_1_std
      value: -1.975434919304149
    - type: nauc_precision_at_20_diff1
      value: 1.1372325410271844
    - type: nauc_precision_at_20_max
      value: 30.110230673953435
    - type: nauc_precision_at_20_std
      value: 25.2301109507936
    - type: nauc_precision_at_3_diff1
      value: 26.68533863846986
    - type: nauc_precision_at_3_max
      value: 37.47926214115986
    - type: nauc_precision_at_3_std
      value: 11.249926202200013
    - type: nauc_precision_at_5_diff1
      value: 18.115625682122925
    - type: nauc_precision_at_5_max
      value: 36.15948376464767
    - type: nauc_precision_at_5_std
      value: 14.536836763909655
    - type: nauc_recall_at_1000_diff1
      value: 32.86834628418128
    - type: nauc_recall_at_1000_max
      value: 38.69690536529228
    - type: nauc_recall_at_1000_std
      value: 47.46864129153341
    - type: nauc_recall_at_100_diff1
      value: 40.31733126845487
    - type: nauc_recall_at_100_max
      value: 33.70215877935575
    - type: nauc_recall_at_100_std
      value: 22.203284375225383
    - type: nauc_recall_at_10_diff1
      value: 49.62184271256615
    - type: nauc_recall_at_10_max
      value: 33.829213165252064
    - type: nauc_recall_at_10_std
      value: 3.2762306444704583
    - type: nauc_recall_at_1_diff1
      value: 60.36308471991815
    - type: nauc_recall_at_1_max
      value: 33.39652804870031
    - type: nauc_recall_at_1_std
      value: -9.62291874243431
    - type: nauc_recall_at_20_diff1
      value: 45.34115505822894
    - type: nauc_recall_at_20_max
      value: 34.317797474261354
    - type: nauc_recall_at_20_std
      value: 8.91557086334875
    - type: nauc_recall_at_3_diff1
      value: 52.2159501674344
    - type: nauc_recall_at_3_max
      value: 33.78966220398346
    - type: nauc_recall_at_3_std
      value: -3.3004922521236666
    - type: nauc_recall_at_5_diff1
      value: 50.71854741865499
    - type: nauc_recall_at_5_max
      value: 33.89372486859709
    - type: nauc_recall_at_5_std
      value: -1.6247218933347045
    - type: ndcg_at_1
      value: 46.497
    - type: ndcg_at_10
      value: 54.730000000000004
    - type: ndcg_at_100
      value: 58.633
    - type: ndcg_at_1000
      value: 60.458
    - type: ndcg_at_20
      value: 56.345
    - type: ndcg_at_3
      value: 50.834
    - type: ndcg_at_5
      value: 52.410000000000004
    - type: precision_at_1
      value: 46.497
    - type: precision_at_10
      value: 10.535
    - type: precision_at_100
      value: 1.601
    - type: precision_at_1000
      value: 0.207
    - type: precision_at_20
      value: 6.127
    - type: precision_at_3
      value: 25.244
    - type: precision_at_5
      value: 17.503
    - type: recall_at_1
      value: 36.288
    - type: recall_at_10
      value: 64.816
    - type: recall_at_100
      value: 81.467
    - type: recall_at_1000
      value: 92.487
    - type: recall_at_20
      value: 70.88499999999999
    - type: recall_at_3
      value: 52.086
    - type: recall_at_5
      value: 57.269000000000005
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB CQADupstackGamingRetrieval
      revision: 4885aa143210c98657558c04aaf3dc47cfb54340
      split: test
      type: mteb/cqadupstack-gaming
    metrics:
    - type: main_score
      value: 62.852
    - type: map_at_1
      value: 43.505
    - type: map_at_10
      value: 56.849000000000004
    - type: map_at_100
      value: 57.928000000000004
    - type: map_at_1000
      value: 57.961
    - type: map_at_20
      value: 57.54899999999999
    - type: map_at_3
      value: 53.47
    - type: map_at_5
      value: 55.30199999999999
    - type: mrr_at_1
      value: 50.03134796238244
    - type: mrr_at_10
      value: 60.38080310494111
    - type: mrr_at_100
      value: 61.01234552272702
    - type: mrr_at_1000
      value: 61.02874712046066
    - type: mrr_at_20
      value: 60.812621173644466
    - type: mrr_at_3
      value: 58.171368861024106
    - type: mrr_at_5
      value: 59.40334378265425
    - type: nauc_map_at_1000_diff1
      value: 52.16816507227677
    - type: nauc_map_at_1000_max
      value: 38.98795133824293
    - type: nauc_map_at_1000_std
      value: -5.028867811195151
    - type: nauc_map_at_100_diff1
      value: 52.153625462396455
    - type: nauc_map_at_100_max
      value: 38.97014189874324
    - type: nauc_map_at_100_std
      value: -5.042246042866819
    - type: nauc_map_at_10_diff1
      value: 52.07923020675717
    - type: nauc_map_at_10_max
      value: 38.369009334557155
    - type: nauc_map_at_10_std
      value: -5.765857710696675
    - type: nauc_map_at_1_diff1
      value: 56.328478399142924
    - type: nauc_map_at_1_max
      value: 31.79021277811985
    - type: nauc_map_at_1_std
      value: -8.98608809438414
    - type: nauc_map_at_20_diff1
      value: 52.105964393726765
    - type: nauc_map_at_20_max
      value: 38.789873388059455
    - type: nauc_map_at_20_std
      value: -5.222700490302784
    - type: nauc_map_at_3_diff1
      value: 52.556616811996
    - type: nauc_map_at_3_max
      value: 37.320756821058495
    - type: nauc_map_at_3_std
      value: -6.894175453592076
    - type: nauc_map_at_5_diff1
      value: 52.378347112597204
    - type: nauc_map_at_5_max
      value: 37.93424310087063
    - type: nauc_map_at_5_std
      value: -6.460337027009615
    - type: nauc_mrr_at_1000_diff1
      value: 51.74183684789293
    - type: nauc_mrr_at_1000_max
      value: 40.58311804493183
    - type: nauc_mrr_at_1000_std
      value: -3.9613238660342964
    - type: nauc_mrr_at_100_diff1
      value: 51.73289955795495
    - type: nauc_mrr_at_100_max
      value: 40.586353253407744
    - type: nauc_mrr_at_100_std
      value: -3.958410058546806
    - type: nauc_mrr_at_10_diff1
      value: 51.64168509083105
    - type: nauc_mrr_at_10_max
      value: 40.399319537948756
    - type: nauc_mrr_at_10_std
      value: -4.116682321334815
    - type: nauc_mrr_at_1_diff1
      value: 55.333800435562765
    - type: nauc_mrr_at_1_max
      value: 39.35467448753652
    - type: nauc_mrr_at_1_std
      value: -5.800227044173351
    - type: nauc_mrr_at_20_diff1
      value: 51.64274061544686
    - type: nauc_mrr_at_20_max
      value: 40.58708648648336
    - type: nauc_mrr_at_20_std
      value: -3.9058072640562185
    - type: nauc_mrr_at_3_diff1
      value: 51.72326489785739
    - type: nauc_mrr_at_3_max
      value: 40.50521371391574
    - type: nauc_mrr_at_3_std
      value: -4.683890918062745
    - type: nauc_mrr_at_5_diff1
      value: 51.488693612711536
    - type: nauc_mrr_at_5_max
      value: 40.2882480652101
    - type: nauc_mrr_at_5_std
      value: -4.4622186125220855
    - type: nauc_ndcg_at_1000_diff1
      value: 51.12814658619273
    - type: nauc_ndcg_at_1000_max
      value: 40.81436571497994
    - type: nauc_ndcg_at_1000_std
      value: -2.43859867526075
    - type: nauc_ndcg_at_100_diff1
      value: 50.80615451234526
    - type: nauc_ndcg_at_100_max
      value: 40.80060641933624
    - type: nauc_ndcg_at_100_std
      value: -2.180605542718217
    - type: nauc_ndcg_at_10_diff1
      value: 50.22487173329537
    - type: nauc_ndcg_at_10_max
      value: 39.45527820611396
    - type: nauc_ndcg_at_10_std
      value: -3.5002205667350164
    - type: nauc_ndcg_at_1_diff1
      value: 55.333800435562765
    - type: nauc_ndcg_at_1_max
      value: 39.35467448753652
    - type: nauc_ndcg_at_1_std
      value: -5.800227044173351
    - type: nauc_ndcg_at_20_diff1
      value: 50.25557695939378
    - type: nauc_ndcg_at_20_max
      value: 40.28337678574298
    - type: nauc_ndcg_at_20_std
      value: -2.3263304856520417
    - type: nauc_ndcg_at_3_diff1
      value: 50.949381425183695
    - type: nauc_ndcg_at_3_max
      value: 38.95477985650601
    - type: nauc_ndcg_at_3_std
      value: -5.0088129038376685
    - type: nauc_ndcg_at_5_diff1
      value: 50.7047728064737
    - type: nauc_ndcg_at_5_max
      value: 39.203829151771686
    - type: nauc_ndcg_at_5_std
      value: -4.622918391428571
    - type: nauc_precision_at_1000_diff1
      value: -14.62405918427924
    - type: nauc_precision_at_1000_max
      value: 16.898489484573037
    - type: nauc_precision_at_1000_std
      value: 21.967747453605394
    - type: nauc_precision_at_100_diff1
      value: -11.448550678871408
    - type: nauc_precision_at_100_max
      value: 19.582209678979844
    - type: nauc_precision_at_100_std
      value: 21.726382460432053
    - type: nauc_precision_at_10_diff1
      value: 5.973035356282201
    - type: nauc_precision_at_10_max
      value: 28.48247102583669
    - type: nauc_precision_at_10_std
      value: 13.32433424892232
    - type: nauc_precision_at_1_diff1
      value: 55.333800435562765
    - type: nauc_precision_at_1_max
      value: 39.35467448753652
    - type: nauc_precision_at_1_std
      value: -5.800227044173351
    - type: nauc_precision_at_20_diff1
      value: -2.004268653238695
    - type: nauc_precision_at_20_max
      value: 25.80563708317859
    - type: nauc_precision_at_20_std
      value: 19.355969977571576
    - type: nauc_precision_at_3_diff1
      value: 25.9256226158056
    - type: nauc_precision_at_3_max
      value: 37.991696510180304
    - type: nauc_precision_at_3_std
      value: 3.5509351197742234
    - type: nauc_precision_at_5_diff1
      value: 17.985770390816665
    - type: nauc_precision_at_5_max
      value: 34.412743806278016
    - type: nauc_precision_at_5_std
      value: 7.26584737170119
    - type: nauc_recall_at_1000_diff1
      value: 38.18794217334074
    - type: nauc_recall_at_1000_max
      value: 80.75619706625903
    - type: nauc_recall_at_1000_std
      value: 68.96313345550892
    - type: nauc_recall_at_100_diff1
      value: 36.29648389156607
    - type: nauc_recall_at_100_max
      value: 51.864154739632916
    - type: nauc_recall_at_100_std
      value: 27.873950597785225
    - type: nauc_recall_at_10_diff1
      value: 40.432973576202755
    - type: nauc_recall_at_10_max
      value: 36.86537535706967
    - type: nauc_recall_at_10_std
      value: 2.6176373660691707
    - type: nauc_recall_at_1_diff1
      value: 56.328478399142924
    - type: nauc_recall_at_1_max
      value: 31.79021277811985
    - type: nauc_recall_at_1_std
      value: -8.98608809438414
    - type: nauc_recall_at_20_diff1
      value: 37.63177369720761
    - type: nauc_recall_at_20_max
      value: 41.908348681745714
    - type: nauc_recall_at_20_std
      value: 12.370515559816726
    - type: nauc_recall_at_3_diff1
      value: 46.14276186098413
    - type: nauc_recall_at_3_max
      value: 36.47844769030852
    - type: nauc_recall_at_3_std
      value: -4.049933832592178
    - type: nauc_recall_at_5_diff1
      value: 43.62405029318324
    - type: nauc_recall_at_5_max
      value: 36.6485145833116
    - type: nauc_recall_at_5_std
      value: -1.9773716947174675
    - type: ndcg_at_1
      value: 50.031000000000006
    - type: ndcg_at_10
      value: 62.852
    - type: ndcg_at_100
      value: 66.78699999999999
    - type: ndcg_at_1000
      value: 67.45
    - type: ndcg_at_20
      value: 64.763
    - type: ndcg_at_3
      value: 57.428999999999995
    - type: ndcg_at_5
      value: 59.911
    - type: precision_at_1
      value: 50.031000000000006
    - type: precision_at_10
      value: 10.138
    - type: precision_at_100
      value: 1.303
    - type: precision_at_1000
      value: 0.13899999999999998
    - type: precision_at_20
      value: 5.643
    - type: precision_at_3
      value: 25.768
    - type: precision_at_5
      value: 17.467
    - type: recall_at_1
      value: 43.505
    - type: recall_at_10
      value: 76.893
    - type: recall_at_100
      value: 93.652
    - type: recall_at_1000
      value: 98.386
    - type: recall_at_20
      value: 83.964
    - type: recall_at_3
      value: 62.253
    - type: recall_at_5
      value: 68.396
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB CQADupstackGisRetrieval
      revision: 5003b3064772da1887988e05400cf3806fe491f2
      split: test
      type: mteb/cqadupstack-gis
    metrics:
    - type: main_score
      value: 43.283
    - type: map_at_1
      value: 26.064999999999998
    - type: map_at_10
      value: 37.031
    - type: map_at_100
      value: 38.14
    - type: map_at_1000
      value: 38.218
    - type: map_at_20
      value: 37.716
    - type: map_at_3
      value: 33.629999999999995
    - type: map_at_5
      value: 35.461
    - type: mrr_at_1
      value: 28.587570621468927
    - type: mrr_at_10
      value: 39.29965922338802
    - type: mrr_at_100
      value: 40.18709583059303
    - type: mrr_at_1000
      value: 40.24310775012281
    - type: mrr_at_20
      value: 39.85344320292107
    - type: mrr_at_3
      value: 36.139359698681716
    - type: mrr_at_5
      value: 37.93032015065908
    - type: nauc_map_at_1000_diff1
      value: 42.42187211420457
    - type: nauc_map_at_1000_max
      value: 28.847889189178446
    - type: nauc_map_at_1000_std
      value: -4.478939123477985
    - type: nauc_map_at_100_diff1
      value: 42.39443063665968
    - type: nauc_map_at_100_max
      value: 28.826251270773728
    - type: nauc_map_at_100_std
      value: -4.48375519738342
    - type: nauc_map_at_10_diff1
      value: 42.35670401428237
    - type: nauc_map_at_10_max
      value: 28.523018011471322
    - type: nauc_map_at_10_std
      value: -4.858656652798197
    - type: nauc_map_at_1_diff1
      value: 50.5853813537782
    - type: nauc_map_at_1_max
      value: 28.95750694379388
    - type: nauc_map_at_1_std
      value: -5.473832706333683
    - type: nauc_map_at_20_diff1
      value: 42.296084034462886
    - type: nauc_map_at_20_max
      value: 28.735714452542755
    - type: nauc_map_at_20_std
      value: -4.483168458232437
    - type: nauc_map_at_3_diff1
      value: 43.60337075646144
    - type: nauc_map_at_3_max
      value: 27.799101868783293
    - type: nauc_map_at_3_std
      value: -5.8302242568306
    - type: nauc_map_at_5_diff1
      value: 42.7473439260839
    - type: nauc_map_at_5_max
      value: 27.585072158467383
    - type: nauc_map_at_5_std
      value: -6.311613977481642
    - type: nauc_mrr_at_1000_diff1
      value: 41.29593951356607
    - type: nauc_mrr_at_1000_max
      value: 30.22991709104691
    - type: nauc_mrr_at_1000_std
      value: -3.987347959936547
    - type: nauc_mrr_at_100_diff1
      value: 41.256998833399514
    - type: nauc_mrr_at_100_max
      value: 30.221534877082995
    - type: nauc_mrr_at_100_std
      value: -3.991703697507233
    - type: nauc_mrr_at_10_diff1
      value: 41.21410647118751
    - type: nauc_mrr_at_10_max
      value: 29.96023432319693
    - type: nauc_mrr_at_10_std
      value: -4.200960374925931
    - type: nauc_mrr_at_1_diff1
      value: 49.15433146229915
    - type: nauc_mrr_at_1_max
      value: 31.655305432241367
    - type: nauc_mrr_at_1_std
      value: -3.9137579419004287
    - type: nauc_mrr_at_20_diff1
      value: 41.18252761309007
    - type: nauc_mrr_at_20_max
      value: 30.24674358119394
    - type: nauc_mrr_at_20_std
      value: -3.9250468669030396
    - type: nauc_mrr_at_3_diff1
      value: 42.15780802979345
    - type: nauc_mrr_at_3_max
      value: 29.779940512045023
    - type: nauc_mrr_at_3_std
      value: -4.917542981232345
    - type: nauc_mrr_at_5_diff1
      value: 41.60404914882282
    - type: nauc_mrr_at_5_max
      value: 29.441296666344375
    - type: nauc_mrr_at_5_std
      value: -5.409222845458672
    - type: nauc_ndcg_at_1000_diff1
      value: 39.73817809472274
    - type: nauc_ndcg_at_1000_max
      value: 30.112132185905953
    - type: nauc_ndcg_at_1000_std
      value: -2.6914997195495762
    - type: nauc_ndcg_at_100_diff1
      value: 38.9523431140116
    - type: nauc_ndcg_at_100_max
      value: 29.988461610940597
    - type: nauc_ndcg_at_100_std
      value: -2.3452674909642197
    - type: nauc_ndcg_at_10_diff1
      value: 38.866521808107734
    - type: nauc_ndcg_at_10_max
      value: 28.98901997129894
    - type: nauc_ndcg_at_10_std
      value: -3.3577165697265516
    - type: nauc_ndcg_at_1_diff1
      value: 49.15433146229915
    - type: nauc_ndcg_at_1_max
      value: 31.655305432241367
    - type: nauc_ndcg_at_1_std
      value: -3.9137579419004287
    - type: nauc_ndcg_at_20_diff1
      value: 38.52149162968572
    - type: nauc_ndcg_at_20_max
      value: 29.784955189449324
    - type: nauc_ndcg_at_20_std
      value: -2.1550586757761963
    - type: nauc_ndcg_at_3_diff1
      value: 41.26556261344799
    - type: nauc_ndcg_at_3_max
      value: 28.076844796153555
    - type: nauc_ndcg_at_3_std
      value: -5.775777269440859
    - type: nauc_ndcg_at_5_diff1
      value: 39.92076501559221
    - type: nauc_ndcg_at_5_max
      value: 27.2798255916491
    - type: nauc_ndcg_at_5_std
      value: -6.6289089695351855
    - type: nauc_precision_at_1000_diff1
      value: -5.296580005564376
    - type: nauc_precision_at_1000_max
      value: 16.558230624538986
    - type: nauc_precision_at_1000_std
      value: 10.723628175442379
    - type: nauc_precision_at_100_diff1
      value: 6.447527156493023
    - type: nauc_precision_at_100_max
      value: 25.972188897251186
    - type: nauc_precision_at_100_std
      value: 13.06586853762115
    - type: nauc_precision_at_10_diff1
      value: 21.420583889218314
    - type: nauc_precision_at_10_max
      value: 30.910468456498453
    - type: nauc_precision_at_10_std
      value: 5.201964222877949
    - type: nauc_precision_at_1_diff1
      value: 49.15433146229915
    - type: nauc_precision_at_1_max
      value: 31.655305432241367
    - type: nauc_precision_at_1_std
      value: -3.9137579419004287
    - type: nauc_precision_at_20_diff1
      value: 15.950077846071602
    - type: nauc_precision_at_20_max
      value: 31.655197596985058
    - type: nauc_precision_at_20_std
      value: 11.246868894868724
    - type: nauc_precision_at_3_diff1
      value: 32.15869249918426
    - type: nauc_precision_at_3_max
      value: 29.45192678013276
    - type: nauc_precision_at_3_std
      value: -3.601077663834796
    - type: nauc_precision_at_5_diff1
      value: 26.916231048491916
    - type: nauc_precision_at_5_max
      value: 26.80734357882765
    - type: nauc_precision_at_5_std
      value: -4.505543292098691
    - type: nauc_recall_at_1000_diff1
      value: 14.958750440953253
    - type: nauc_recall_at_1000_max
      value: 43.514251968484686
    - type: nauc_recall_at_1000_std
      value: 19.974978865375515
    - type: nauc_recall_at_100_diff1
      value: 20.521208710453955
    - type: nauc_recall_at_100_max
      value: 32.98379725953528
    - type: nauc_recall_at_100_std
      value: 9.69206995924816
    - type: nauc_recall_at_10_diff1
      value: 26.815546511752796
    - type: nauc_recall_at_10_max
      value: 27.86212696549476
    - type: nauc_recall_at_10_std
      value: 1.7081361808897406
    - type: nauc_recall_at_1_diff1
      value: 50.5853813537782
    - type: nauc_recall_at_1_max
      value: 28.95750694379388
    - type: nauc_recall_at_1_std
      value: -5.473832706333683
    - type: nauc_recall_at_20_diff1
      value: 23.75470124208999
    - type: nauc_recall_at_20_max
      value: 31.388982709530495
    - type: nauc_recall_at_20_std
      value: 7.583586267131971
    - type: nauc_recall_at_3_diff1
      value: 34.408725099080065
    - type: nauc_recall_at_3_max
      value: 24.663819415905227
    - type: nauc_recall_at_3_std
      value: -6.090959685767185
    - type: nauc_recall_at_5_diff1
      value: 31.43375763159866
    - type: nauc_recall_at_5_max
      value: 23.3902533756189
    - type: nauc_recall_at_5_std
      value: -8.221510877005835
    - type: ndcg_at_1
      value: 28.588
    - type: ndcg_at_10
      value: 43.283
    - type: ndcg_at_100
      value: 48.187999999999995
    - type: ndcg_at_1000
      value: 49.968
    - type: ndcg_at_20
      value: 45.552
    - type: ndcg_at_3
      value: 36.673
    - type: ndcg_at_5
      value: 39.775
    - type: precision_at_1
      value: 28.588
    - type: precision_at_10
      value: 6.994
    - type: precision_at_100
      value: 0.985
    - type: precision_at_1000
      value: 0.117
    - type: precision_at_20
      value: 4.0280000000000005
    - type: precision_at_3
      value: 15.895000000000001
    - type: precision_at_5
      value: 11.48
    - type: recall_at_1
      value: 26.064999999999998
    - type: recall_at_10
      value: 60.305
    - type: recall_at_100
      value: 81.905
    - type: recall_at_1000
      value: 94.997
    - type: recall_at_20
      value: 68.863
    - type: recall_at_3
      value: 42.641
    - type: recall_at_5
      value: 49.889
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB CQADupstackMathematicaRetrieval
      revision: 90fceea13679c63fe563ded68f3b6f06e50061de
      split: test
      type: mteb/cqadupstack-mathematica
    metrics:
    - type: main_score
      value: 37.446
    - type: map_at_1
      value: 20.067
    - type: map_at_10
      value: 31.039
    - type: map_at_100
      value: 32.448
    - type: map_at_1000
      value: 32.568999999999996
    - type: map_at_20
      value: 31.862000000000002
    - type: map_at_3
      value: 27.511000000000003
    - type: map_at_5
      value: 29.401
    - type: mrr_at_1
      value: 25.0
    - type: mrr_at_10
      value: 35.78451986101241
    - type: mrr_at_100
      value: 36.753438697885464
    - type: mrr_at_1000
      value: 36.82003799858393
    - type: mrr_at_20
      value: 36.39663937700652
    - type: mrr_at_3
      value: 32.62852404643451
    - type: mrr_at_5
      value: 34.53772802653399
    - type: nauc_map_at_1000_diff1
      value: 36.05896529090642
    - type: nauc_map_at_1000_max
      value: 15.671309477610798
    - type: nauc_map_at_1000_std
      value: 4.475635751011654
    - type: nauc_map_at_100_diff1
      value: 36.019391595005004
    - type: nauc_map_at_100_max
      value: 15.66217063183362
    - type: nauc_map_at_100_std
      value: 4.508405110479613
    - type: nauc_map_at_10_diff1
      value: 35.84042671931317
    - type: nauc_map_at_10_max
      value: 15.368517303736223
    - type: nauc_map_at_10_std
      value: 3.876035429672711
    - type: nauc_map_at_1_diff1
      value: 40.48912661695433
    - type: nauc_map_at_1_max
      value: 13.69883279024985
    - type: nauc_map_at_1_std
      value: 3.744315387412784
    - type: nauc_map_at_20_diff1
      value: 35.99908585225915
    - type: nauc_map_at_20_max
      value: 15.314111789738066
    - type: nauc_map_at_20_std
      value: 4.008777800950492
    - type: nauc_map_at_3_diff1
      value: 36.60945838361659
    - type: nauc_map_at_3_max
      value: 14.917696303941232
    - type: nauc_map_at_3_std
      value: 3.3471768670108015
    - type: nauc_map_at_5_diff1
      value: 35.911911941121176
    - type: nauc_map_at_5_max
      value: 14.968695395330888
    - type: nauc_map_at_5_std
      value: 3.2515259862721932
    - type: nauc_mrr_at_1000_diff1
      value: 36.898068388598546
    - type: nauc_mrr_at_1000_max
      value: 18.461630278605405
    - type: nauc_mrr_at_1000_std
      value: 2.330762879933047
    - type: nauc_mrr_at_100_diff1
      value: 36.87417879467055
    - type: nauc_mrr_at_100_max
      value: 18.46567622846986
    - type: nauc_mrr_at_100_std
      value: 2.336737122580058
    - type: nauc_mrr_at_10_diff1
      value: 36.715555947183894
    - type: nauc_mrr_at_10_max
      value: 18.42263131138216
    - type: nauc_mrr_at_10_std
      value: 2.0495127830234163
    - type: nauc_mrr_at_1_diff1
      value: 41.536232116296794
    - type: nauc_mrr_at_1_max
      value: 17.224487449529438
    - type: nauc_mrr_at_1_std
      value: 0.5335760894600696
    - type: nauc_mrr_at_20_diff1
      value: 36.89224396954191
    - type: nauc_mrr_at_20_max
      value: 18.370891623861144
    - type: nauc_mrr_at_20_std
      value: 2.0679010433581846
    - type: nauc_mrr_at_3_diff1
      value: 36.84781218130023
    - type: nauc_mrr_at_3_max
      value: 17.787322385401254
    - type: nauc_mrr_at_3_std
      value: 1.4238966460667293
    - type: nauc_mrr_at_5_diff1
      value: 36.82828355006567
    - type: nauc_mrr_at_5_max
      value: 18.40427077231103
    - type: nauc_mrr_at_5_std
      value: 2.2181911860090313
    - type: nauc_ndcg_at_1000_diff1
      value: 35.437481163865776
    - type: nauc_ndcg_at_1000_max
      value: 18.20622883319508
    - type: nauc_ndcg_at_1000_std
      value: 6.314093567004441
    - type: nauc_ndcg_at_100_diff1
      value: 34.74558858596492
    - type: nauc_ndcg_at_100_max
      value: 17.897651102227037
    - type: nauc_ndcg_at_100_std
      value: 6.889044901306916
    - type: nauc_ndcg_at_10_diff1
      value: 34.25244637413115
    - type: nauc_ndcg_at_10_max
      value: 16.75821287616703
    - type: nauc_ndcg_at_10_std
      value: 4.107982711840355
    - type: nauc_ndcg_at_1_diff1
      value: 41.536232116296794
    - type: nauc_ndcg_at_1_max
      value: 17.224487449529438
    - type: nauc_ndcg_at_1_std
      value: 0.5335760894600696
    - type: nauc_ndcg_at_20_diff1
      value: 34.792910843723405
    - type: nauc_ndcg_at_20_max
      value: 16.500521917621107
    - type: nauc_ndcg_at_20_std
      value: 4.386742172400979
    - type: nauc_ndcg_at_3_diff1
      value: 35.905097590246896
    - type: nauc_ndcg_at_3_max
      value: 16.366456898662946
    - type: nauc_ndcg_at_3_std
      value: 2.284616986823101
    - type: nauc_ndcg_at_5_diff1
      value: 34.85002987514305
    - type: nauc_ndcg_at_5_max
      value: 16.301969698078135
    - type: nauc_ndcg_at_5_std
      value: 3.091621176782891
    - type: nauc_precision_at_1000_diff1
      value: 2.8643015655109076
    - type: nauc_precision_at_1000_max
      value: 10.492390885381257
    - type: nauc_precision_at_1000_std
      value: -1.8003804143743998
    - type: nauc_precision_at_100_diff1
      value: 9.777438987179002
    - type: nauc_precision_at_100_max
      value: 15.755495154710436
    - type: nauc_precision_at_100_std
      value: 8.144312169070117
    - type: nauc_precision_at_10_diff1
      value: 20.528805438704264
    - type: nauc_precision_at_10_max
      value: 18.505443699135714
    - type: nauc_precision_at_10_std
      value: 4.1194507188617
    - type: nauc_precision_at_1_diff1
      value: 41.536232116296794
    - type: nauc_precision_at_1_max
      value: 17.224487449529438
    - type: nauc_precision_at_1_std
      value: 0.5335760894600696
    - type: nauc_precision_at_20_diff1
      value: 17.655826225778
    - type: nauc_precision_at_20_max
      value: 15.968707387070893
    - type: nauc_precision_at_20_std
      value: 3.6471700411056074
    - type: nauc_precision_at_3_diff1
      value: 29.288368256814113
    - type: nauc_precision_at_3_max
      value: 19.393713628629918
    - type: nauc_precision_at_3_std
      value: 1.1678930849545104
    - type: nauc_precision_at_5_diff1
      value: 24.747039535895006
    - type: nauc_precision_at_5_max
      value: 19.37471463096941
    - type: nauc_precision_at_5_std
      value: 2.1072554494740587
    - type: nauc_recall_at_1000_diff1
      value: 25.348910046707175
    - type: nauc_recall_at_1000_max
      value: 46.655076967466215
    - type: nauc_recall_at_1000_std
      value: 51.80465296222736
    - type: nauc_recall_at_100_diff1
      value: 24.917032193154455
    - type: nauc_recall_at_100_max
      value: 21.546151283672067
    - type: nauc_recall_at_100_std
      value: 22.351525493151474
    - type: nauc_recall_at_10_diff1
      value: 27.1307328548228
    - type: nauc_recall_at_10_max
      value: 16.42721368396447
    - type: nauc_recall_at_10_std
      value: 4.830746601420713
    - type: nauc_recall_at_1_diff1
      value: 40.48912661695433
    - type: nauc_recall_at_1_max
      value: 13.69883279024985
    - type: nauc_recall_at_1_std
      value: 3.744315387412784
    - type: nauc_recall_at_20_diff1
      value: 27.80298416224803
    - type: nauc_recall_at_20_max
      value: 14.791741861498448
    - type: nauc_recall_at_20_std
      value: 5.769973222681834
    - type: nauc_recall_at_3_diff1
      value: 31.93453164205915
    - type: nauc_recall_at_3_max
      value: 15.680550835449104
    - type: nauc_recall_at_3_std
      value: 3.1696648883180476
    - type: nauc_recall_at_5_diff1
      value: 29.78902445025613
    - type: nauc_recall_at_5_max
      value: 15.277025908354966
    - type: nauc_recall_at_5_std
      value: 3.442734696498184
    - type: ndcg_at_1
      value: 25.0
    - type: ndcg_at_10
      value: 37.446
    - type: ndcg_at_100
      value: 43.309999999999995
    - type: ndcg_at_1000
      value: 45.872
    - type: ndcg_at_20
      value: 40.056000000000004
    - type: ndcg_at_3
      value: 31.304
    - type: ndcg_at_5
      value: 34.102
    - type: precision_at_1
      value: 25.0
    - type: precision_at_10
      value: 7.251
    - type: precision_at_100
      value: 1.154
    - type: precision_at_1000
      value: 0.15
    - type: precision_at_20
      value: 4.353
    - type: precision_at_3
      value: 15.423
    - type: precision_at_5
      value: 11.443
    - type: recall_at_1
      value: 20.067
    - type: recall_at_10
      value: 52.097
    - type: recall_at_100
      value: 76.44800000000001
    - type: recall_at_1000
      value: 94.352
    - type: recall_at_20
      value: 61.452
    - type: recall_at_3
      value: 35.13
    - type: recall_at_5
      value: 42.198
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB CQADupstackPhysicsRetrieval
      revision: 79531abbd1fb92d06c6d6315a0cbbbf5bb247ea4
      split: test
      type: mteb/cqadupstack-physics
    metrics:
    - type: main_score
      value: 55.415000000000006
    - type: map_at_1
      value: 34.589999999999996
    - type: map_at_10
      value: 48.723
    - type: map_at_100
      value: 50.144999999999996
    - type: map_at_1000
      value: 50.234
    - type: map_at_20
      value: 49.547999999999995
    - type: map_at_3
      value: 44.853
    - type: map_at_5
      value: 47.214
    - type: mrr_at_1
      value: 43.503368623676614
    - type: mrr_at_10
      value: 54.46258612524254
    - type: mrr_at_100
      value: 55.21475192497595
    - type: mrr_at_1000
      value: 55.24157667498575
    - type: mrr_at_20
      value: 54.977284672294616
    - type: mrr_at_3
      value: 51.876804619826736
    - type: mrr_at_5
      value: 53.426371511068346
    - type: nauc_map_at_1000_diff1
      value: 48.70811157700997
    - type: nauc_map_at_1000_max
      value: 33.60529368840378
    - type: nauc_map_at_1000_std
      value: -2.854935387108443
    - type: nauc_map_at_100_diff1
      value: 48.70594404740001
    - type: nauc_map_at_100_max
      value: 33.579717784765016
    - type: nauc_map_at_100_std
      value: -2.8791449718850277
    - type: nauc_map_at_10_diff1
      value: 48.79283083978676
    - type: nauc_map_at_10_max
      value: 33.26660403263183
    - type: nauc_map_at_10_std
      value: -3.5841120398185793
    - type: nauc_map_at_1_diff1
      value: 52.544771399002364
    - type: nauc_map_at_1_max
      value: 29.705116547453663
    - type: nauc_map_at_1_std
      value: -5.601562862373656
    - type: nauc_map_at_20_diff1
      value: 48.77748505048382
    - type: nauc_map_at_20_max
      value: 33.421562873302705
    - type: nauc_map_at_20_std
      value: -3.182579472737019
    - type: nauc_map_at_3_diff1
      value: 48.286108414395116
    - type: nauc_map_at_3_max
      value: 30.938497280994287
    - type: nauc_map_at_3_std
      value: -4.0236487836297625
    - type: nauc_map_at_5_diff1
      value: 48.519438148461305
    - type: nauc_map_at_5_max
      value: 33.00611184814483
    - type: nauc_map_at_5_std
      value: -3.7775481925049452
    - type: nauc_mrr_at_1000_diff1
      value: 48.277264994217425
    - type: nauc_mrr_at_1000_max
      value: 35.97266404049971
    - type: nauc_mrr_at_1000_std
      value: -2.123009634125046
    - type: nauc_mrr_at_100_diff1
      value: 48.273814689867066
    - type: nauc_mrr_at_100_max
      value: 35.96575330515099
    - type: nauc_mrr_at_100_std
      value: -2.109190098790991
    - type: nauc_mrr_at_10_diff1
      value: 48.19383487073961
    - type: nauc_mrr_at_10_max
      value: 35.98431226038537
    - type: nauc_mrr_at_10_std
      value: -2.2525468820243733
    - type: nauc_mrr_at_1_diff1
      value: 51.06156572507775
    - type: nauc_mrr_at_1_max
      value: 36.130071198744915
    - type: nauc_mrr_at_1_std
      value: -3.6987073278382097
    - type: nauc_mrr_at_20_diff1
      value: 48.17993843956302
    - type: nauc_mrr_at_20_max
      value: 35.883506987853444
    - type: nauc_mrr_at_20_std
      value: -2.2396794954983688
    - type: nauc_mrr_at_3_diff1
      value: 48.023787207245235
    - type: nauc_mrr_at_3_max
      value: 35.06522559840627
    - type: nauc_mrr_at_3_std
      value: -2.4196862666204586
    - type: nauc_mrr_at_5_diff1
      value: 47.99567629464062
    - type: nauc_mrr_at_5_max
      value: 36.287724757841104
    - type: nauc_mrr_at_5_std
      value: -2.3172197591354546
    - type: nauc_ndcg_at_1000_diff1
      value: 48.13267529689748
    - type: nauc_ndcg_at_1000_max
      value: 35.28926463903508
    - type: nauc_ndcg_at_1000_std
      value: -0.975275066914596
    - type: nauc_ndcg_at_100_diff1
      value: 48.08279554535348
    - type: nauc_ndcg_at_100_max
      value: 35.06918767828454
    - type: nauc_ndcg_at_100_std
      value: -0.9148919965139696
    - type: nauc_ndcg_at_10_diff1
      value: 47.88020216330185
    - type: nauc_ndcg_at_10_max
      value: 34.09860780369103
    - type: nauc_ndcg_at_10_std
      value: -3.211991208178331
    - type: nauc_ndcg_at_1_diff1
      value: 51.06156572507775
    - type: nauc_ndcg_at_1_max
      value: 36.130071198744915
    - type: nauc_ndcg_at_1_std
      value: -3.6987073278382097
    - type: nauc_ndcg_at_20_diff1
      value: 47.81204239679312
    - type: nauc_ndcg_at_20_max
      value: 34.08565346064627
    - type: nauc_ndcg_at_20_std
      value: -2.319094833112998
    - type: nauc_ndcg_at_3_diff1
      value: 46.62727837063755
    - type: nauc_ndcg_at_3_max
      value: 32.31694733238124
    - type: nauc_ndcg_at_3_std
      value: -2.8694697450791025
    - type: nauc_ndcg_at_5_diff1
      value: 47.163743819793716
    - type: nauc_ndcg_at_5_max
      value: 34.54508602063915
    - type: nauc_ndcg_at_5_std
      value: -3.065010213302116
    - type: nauc_precision_at_1000_diff1
      value: -15.363112865347068
    - type: nauc_precision_at_1000_max
      value: 1.0710258213837947
    - type: nauc_precision_at_1000_std
      value: 11.99888975386951
    - type: nauc_precision_at_100_diff1
      value: -11.003234253190557
    - type: nauc_precision_at_100_max
      value: 8.240198555273011
    - type: nauc_precision_at_100_std
      value: 13.695783311849826
    - type: nauc_precision_at_10_diff1
      value: 9.718261781558812
    - type: nauc_precision_at_10_max
      value: 23.187819865066686
    - type: nauc_precision_at_10_std
      value: 6.611311345607956
    - type: nauc_precision_at_1_diff1
      value: 51.06156572507775
    - type: nauc_precision_at_1_max
      value: 36.130071198744915
    - type: nauc_precision_at_1_std
      value: -3.6987073278382097
    - type: nauc_precision_at_20_diff1
      value: 0.7631719415782295
    - type: nauc_precision_at_20_max
      value: 16.967400845374932
    - type: nauc_precision_at_20_std
      value: 10.321820961212765
    - type: nauc_precision_at_3_diff1
      value: 22.865842308254884
    - type: nauc_precision_at_3_max
      value: 26.988123224415993
    - type: nauc_precision_at_3_std
      value: 2.9803381006113407
    - type: nauc_precision_at_5_diff1
      value: 16.647505624227946
    - type: nauc_precision_at_5_max
      value: 29.10928055358471
    - type: nauc_precision_at_5_std
      value: 4.519877361452181
    - type: nauc_recall_at_1000_diff1
      value: 47.230180388981175
    - type: nauc_recall_at_1000_max
      value: 63.59967720216338
    - type: nauc_recall_at_1000_std
      value: 39.61544752174729
    - type: nauc_recall_at_100_diff1
      value: 43.74771083625564
    - type: nauc_recall_at_100_max
      value: 36.24409622855235
    - type: nauc_recall_at_100_std
      value: 14.190250157642126
    - type: nauc_recall_at_10_diff1
      value: 42.70125356264119
    - type: nauc_recall_at_10_max
      value: 31.148765347668316
    - type: nauc_recall_at_10_std
      value: -3.8529781862684844
    - type: nauc_recall_at_1_diff1
      value: 52.544771399002364
    - type: nauc_recall_at_1_max
      value: 29.705116547453663
    - type: nauc_recall_at_1_std
      value: -5.601562862373656
    - type: nauc_recall_at_20_diff1
      value: 41.45436649923809
    - type: nauc_recall_at_20_max
      value: 28.88529838997527
    - type: nauc_recall_at_20_std
      value: -0.74118707258864
    - type: nauc_recall_at_3_diff1
      value: 42.38845270930942
    - type: nauc_recall_at_3_max
      value: 26.975128911610096
    - type: nauc_recall_at_3_std
      value: -3.9603003198517874
    - type: nauc_recall_at_5_diff1
      value: 41.926816165219435
    - type: nauc_recall_at_5_max
      value: 32.52234840278525
    - type: nauc_recall_at_5_std
      value: -3.930581158477037
    - type: ndcg_at_1
      value: 43.503
    - type: ndcg_at_10
      value: 55.415000000000006
    - type: ndcg_at_100
      value: 60.629
    - type: ndcg_at_1000
      value: 61.889
    - type: ndcg_at_20
      value: 57.794000000000004
    - type: ndcg_at_3
      value: 50.07
    - type: ndcg_at_5
      value: 52.917
    - type: precision_at_1
      value: 43.503
    - type: precision_at_10
      value: 10.212
    - type: precision_at_100
      value: 1.497
    - type: precision_at_1000
      value: 0.17600000000000002
    - type: precision_at_20
      value: 5.982
    - type: precision_at_3
      value: 24.735
    - type: precision_at_5
      value: 17.421
    - type: recall_at_1
      value: 34.589999999999996
    - type: recall_at_10
      value: 69.269
    - type: recall_at_100
      value: 90.193
    - type: recall_at_1000
      value: 97.78999999999999
    - type: recall_at_20
      value: 77.459
    - type: recall_at_3
      value: 53.910000000000004
    - type: recall_at_5
      value: 61.673
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB CQADupstackProgrammersRetrieval
      revision: 6184bc1440d2dbc7612be22b50686b8826d22b32
      split: test
      type: mteb/cqadupstack-programmers
    metrics:
    - type: main_score
      value: 50.519999999999996
    - type: map_at_1
      value: 31.580000000000002
    - type: map_at_10
      value: 43.742
    - type: map_at_100
      value: 45.196
    - type: map_at_1000
      value: 45.288000000000004
    - type: map_at_20
      value: 44.596000000000004
    - type: map_at_3
      value: 39.69
    - type: map_at_5
      value: 41.894
    - type: mrr_at_1
      value: 40.06849315068493
    - type: mrr_at_10
      value: 50.05866311516994
    - type: mrr_at_100
      value: 50.9108187845444
    - type: mrr_at_1000
      value: 50.94986370040752
    - type: mrr_at_20
      value: 50.61498736271569
    - type: mrr_at_3
      value: 47.39345509893453
    - type: mrr_at_5
      value: 48.88318112633176
    - type: nauc_map_at_1000_diff1
      value: 42.58190059221122
    - type: nauc_map_at_1000_max
      value: 42.24027580723332
    - type: nauc_map_at_1000_std
      value: 3.0856149046170005
    - type: nauc_map_at_100_diff1
      value: 42.55434873869965
    - type: nauc_map_at_100_max
      value: 42.253447954245566
    - type: nauc_map_at_100_std
      value: 3.1551662487791203
    - type: nauc_map_at_10_diff1
      value: 42.24482815355762
    - type: nauc_map_at_10_max
      value: 41.69105238949104
    - type: nauc_map_at_10_std
      value: 2.520799276313239
    - type: nauc_map_at_1_diff1
      value: 47.560851703744774
    - type: nauc_map_at_1_max
      value: 38.6248469791681
    - type: nauc_map_at_1_std
      value: -1.8170572347787832
    - type: nauc_map_at_20_diff1
      value: 42.46448256002967
    - type: nauc_map_at_20_max
      value: 42.122163883138676
    - type: nauc_map_at_20_std
      value: 2.8735074101432825
    - type: nauc_map_at_3_diff1
      value: 42.852783936850564
    - type: nauc_map_at_3_max
      value: 39.472931019277894
    - type: nauc_map_at_3_std
      value: -0.3475890309252013
    - type: nauc_map_at_5_diff1
      value: 42.585500010159514
    - type: nauc_map_at_5_max
      value: 40.45610693188885
    - type: nauc_map_at_5_std
      value: 1.4395701934604168
    - type: nauc_mrr_at_1000_diff1
      value: 42.423644717291154
    - type: nauc_mrr_at_1000_max
      value: 44.65054622179436
    - type: nauc_mrr_at_1000_std
      value: 4.232909363310718
    - type: nauc_mrr_at_100_diff1
      value: 42.4111985157921
    - type: nauc_mrr_at_100_max
      value: 44.64403905116052
    - type: nauc_mrr_at_100_std
      value: 4.270671488128001
    - type: nauc_mrr_at_10_diff1
      value: 42.15967299835129
    - type: nauc_mrr_at_10_max
      value: 44.59286101312794
    - type: nauc_mrr_at_10_std
      value: 3.9958749006290457
    - type: nauc_mrr_at_1_diff1
      value: 46.96021803898227
    - type: nauc_mrr_at_1_max
      value: 45.730628543873635
    - type: nauc_mrr_at_1_std
      value: 3.0321693147544266
    - type: nauc_mrr_at_20_diff1
      value: 42.28916367832821
    - type: nauc_mrr_at_20_max
      value: 44.62734577020967
    - type: nauc_mrr_at_20_std
      value: 4.096580770642528
    - type: nauc_mrr_at_3_diff1
      value: 42.35145293488433
    - type: nauc_mrr_at_3_max
      value: 44.250892891986474
    - type: nauc_mrr_at_3_std
      value: 2.888573667622583
    - type: nauc_mrr_at_5_diff1
      value: 41.978496839842855
    - type: nauc_mrr_at_5_max
      value: 44.12581663000585
    - type: nauc_mrr_at_5_std
      value: 3.578587338340754
    - type: nauc_ndcg_at_1000_diff1
      value: 41.77074346352433
    - type: nauc_ndcg_at_1000_max
      value: 43.58097356675654
    - type: nauc_ndcg_at_1000_std
      value: 5.602153215417836
    - type: nauc_ndcg_at_100_diff1
      value: 41.42926135953559
    - type: nauc_ndcg_at_100_max
      value: 43.75287565409255
    - type: nauc_ndcg_at_100_std
      value: 6.98655252924014
    - type: nauc_ndcg_at_10_diff1
      value: 40.720516948960025
    - type: nauc_ndcg_at_10_max
      value: 43.069417293025495
    - type: nauc_ndcg_at_10_std
      value: 4.523429060201205
    - type: nauc_ndcg_at_1_diff1
      value: 46.96021803898227
    - type: nauc_ndcg_at_1_max
      value: 45.730628543873635
    - type: nauc_ndcg_at_1_std
      value: 3.0321693147544266
    - type: nauc_ndcg_at_20_diff1
      value: 41.14839082748255
    - type: nauc_ndcg_at_20_max
      value: 43.67012537029431
    - type: nauc_ndcg_at_20_std
      value: 5.510489672585324
    - type: nauc_ndcg_at_3_diff1
      value: 41.427980208562126
    - type: nauc_ndcg_at_3_max
      value: 40.967307875582804
    - type: nauc_ndcg_at_3_std
      value: 0.7313507182329976
    - type: nauc_ndcg_at_5_diff1
      value: 41.16187520995125
    - type: nauc_ndcg_at_5_max
      value: 41.242001895631866
    - type: nauc_ndcg_at_5_std
      value: 2.7475504026736615
    - type: nauc_precision_at_1000_diff1
      value: -6.8969607107056765
    - type: nauc_precision_at_1000_max
      value: -1.604712187109837
    - type: nauc_precision_at_1000_std
      value: -2.0100930123166676
    - type: nauc_precision_at_100_diff1
      value: -2.481194803351693
    - type: nauc_precision_at_100_max
      value: 12.198658178689044
    - type: nauc_precision_at_100_std
      value: 10.381181740292977
    - type: nauc_precision_at_10_diff1
      value: 10.932641746185313
    - type: nauc_precision_at_10_max
      value: 32.74791233183574
    - type: nauc_precision_at_10_std
      value: 14.310676221226531
    - type: nauc_precision_at_1_diff1
      value: 46.96021803898227
    - type: nauc_precision_at_1_max
      value: 45.730628543873635
    - type: nauc_precision_at_1_std
      value: 3.0321693147544266
    - type: nauc_precision_at_20_diff1
      value: 5.5310216115349995
    - type: nauc_precision_at_20_max
      value: 26.444236097552743
    - type: nauc_precision_at_20_std
      value: 14.042626144032427
    - type: nauc_precision_at_3_diff1
      value: 25.443454094624084
    - type: nauc_precision_at_3_max
      value: 38.87053030012482
    - type: nauc_precision_at_3_std
      value: 5.723054837019903
    - type: nauc_precision_at_5_diff1
      value: 18.95365147558431
    - type: nauc_precision_at_5_max
      value: 35.371421600374156
    - type: nauc_precision_at_5_std
      value: 10.495239445400859
    - type: nauc_recall_at_1000_diff1
      value: 33.87920406348084
    - type: nauc_recall_at_1000_max
      value: 49.25430026483254
    - type: nauc_recall_at_1000_std
      value: 68.60869611967505
    - type: nauc_recall_at_100_diff1
      value: 31.480912514518483
    - type: nauc_recall_at_100_max
      value: 43.05135980241577
    - type: nauc_recall_at_100_std
      value: 38.36523764466429
    - type: nauc_recall_at_10_diff1
      value: 32.77114254594519
    - type: nauc_recall_at_10_max
      value: 40.447623194129676
    - type: nauc_recall_at_10_std
      value: 9.450100645814036
    - type: nauc_recall_at_1_diff1
      value: 47.560851703744774
    - type: nauc_recall_at_1_max
      value: 38.6248469791681
    - type: nauc_recall_at_1_std
      value: -1.8170572347787832
    - type: nauc_recall_at_20_diff1
      value: 33.132251568021246
    - type: nauc_recall_at_20_max
      value: 42.31031758105075
    - type: nauc_recall_at_20_std
      value: 15.147293205224663
    - type: nauc_recall_at_3_diff1
      value: 37.144923197664696
    - type: nauc_recall_at_3_max
      value: 35.80095936531684
    - type: nauc_recall_at_3_std
      value: -0.26602015775193216
    - type: nauc_recall_at_5_diff1
      value: 34.787180172569634
    - type: nauc_recall_at_5_max
      value: 35.6889420548128
    - type: nauc_recall_at_5_std
      value: 4.236319477919327
    - type: ndcg_at_1
      value: 40.068
    - type: ndcg_at_10
      value: 50.519999999999996
    - type: ndcg_at_100
      value: 56.059000000000005
    - type: ndcg_at_1000
      value: 57.619
    - type: ndcg_at_20
      value: 53.002
    - type: ndcg_at_3
      value: 44.525
    - type: ndcg_at_5
      value: 47.165
    - type: precision_at_1
      value: 40.068
    - type: precision_at_10
      value: 9.543
    - type: precision_at_100
      value: 1.426
    - type: precision_at_1000
      value: 0.172
    - type: precision_at_20
      value: 5.588
    - type: precision_at_3
      value: 21.651
    - type: precision_at_5
      value: 15.457
    - type: recall_at_1
      value: 31.580000000000002
    - type: recall_at_10
      value: 64.332
    - type: recall_at_100
      value: 87.339
    - type: recall_at_1000
      value: 97.41
    - type: recall_at_20
      value: 73.124
    - type: recall_at_3
      value: 47.253
    - type: recall_at_5
      value: 54.718
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB CQADupstackRetrieval
      revision: 4ffe81d471b1924886b33c7567bfb200e9eec5c4
      split: test
      type: mteb/cqadupstack
    metrics:
    - type: main_score
      value: 47.74883333333334
    - type: map_at_1
      value: 30.179249999999996
    - type: map_at_10
      value: 41.60824999999999
    - type: map_at_100
      value: 42.94008333333332
    - type: map_at_1000
      value: 43.04666666666667
    - type: map_at_20
      value: 42.36833333333334
    - type: map_at_3
      value: 38.23491666666666
    - type: map_at_5
      value: 40.10183333333333
    - type: mrr_at_1
      value: 36.47676085808166
    - type: mrr_at_10
      value: 46.300991916437155
    - type: mrr_at_100
      value: 47.12155753713262
    - type: mrr_at_1000
      value: 47.168033610799945
    - type: mrr_at_20
      value: 46.80405724560391
    - type: mrr_at_3
      value: 43.77000352801797
    - type: mrr_at_5
      value: 45.22295361704542
    - type: nauc_map_at_1000_diff1
      value: 46.953671666941524
    - type: nauc_map_at_1000_max
      value: 32.260396316089675
    - type: nauc_map_at_1000_std
      value: 0.6657766120094878
    - type: nauc_map_at_100_diff1
      value: 46.94717463394555
    - type: nauc_map_at_100_max
      value: 32.25088350678177
    - type: nauc_map_at_100_std
      value: 0.6257017014549283
    - type: nauc_map_at_10_diff1
      value: 46.974678429336464
    - type: nauc_map_at_10_max
      value: 31.862230807295504
    - type: nauc_map_at_10_std
      value: -0.14758828549579284
    - type: nauc_map_at_1_diff1
      value: 52.48913346466124
    - type: nauc_map_at_1_max
      value: 29.874374024967725
    - type: nauc_map_at_1_std
      value: -2.433547569836134
    - type: nauc_map_at_20_diff1
      value: 46.96088684217651
    - type: nauc_map_at_20_max
      value: 32.08954208613205
    - type: nauc_map_at_20_std
      value: 0.25946321113436527
    - type: nauc_map_at_3_diff1
      value: 47.703230121518345
    - type: nauc_map_at_3_max
      value: 30.977880095983107
    - type: nauc_map_at_3_std
      value: -1.342777563991804
    - type: nauc_map_at_5_diff1
      value: 47.1615010199957
    - type: nauc_map_at_5_max
      value: 31.420885812683284
    - type: nauc_map_at_5_std
      value: -0.8789297099444306
    - type: nauc_mrr_at_1000_diff1
      value: 46.69178645962615
    - type: nauc_mrr_at_1000_max
      value: 34.392807413340655
    - type: nauc_mrr_at_1000_std
      value: 1.6155464863667934
    - type: nauc_mrr_at_100_diff1
      value: 46.67417236349189
    - type: nauc_mrr_at_100_max
      value: 34.384607045512624
    - type: nauc_mrr_at_100_std
      value: 1.6259917384109652
    - type: nauc_mrr_at_10_diff1
      value: 46.60497560446239
    - type: nauc_mrr_at_10_max
      value: 34.32918897817958
    - type: nauc_mrr_at_10_std
      value: 1.39387793769014
    - type: nauc_mrr_at_1_diff1
      value: 51.61608573254137
    - type: nauc_mrr_at_1_max
      value: 35.18105023234596
    - type: nauc_mrr_at_1_std
      value: 0.17943702145478177
    - type: nauc_mrr_at_20_diff1
      value: 46.635943069860254
    - type: nauc_mrr_at_20_max
      value: 34.37050973118794
    - type: nauc_mrr_at_20_std
      value: 1.5346464678860607
    - type: nauc_mrr_at_3_diff1
      value: 47.154389369038334
    - type: nauc_mrr_at_3_max
      value: 34.41036411855465
    - type: nauc_mrr_at_3_std
      value: 0.924551812357872
    - type: nauc_mrr_at_5_diff1
      value: 46.6690101691763
    - type: nauc_mrr_at_5_max
      value: 34.29740388138466
    - type: nauc_mrr_at_5_std
      value: 1.0567184149139792
    - type: nauc_ndcg_at_1000_diff1
      value: 45.375448289173264
    - type: nauc_ndcg_at_1000_max
      value: 33.47957083714482
    - type: nauc_ndcg_at_1000_std
      value: 3.192251100225568
    - type: nauc_ndcg_at_100_diff1
      value: 44.93601014699499
    - type: nauc_ndcg_at_100_max
      value: 33.21249888295249
    - type: nauc_ndcg_at_100_std
      value: 3.609842852934217
    - type: nauc_ndcg_at_10_diff1
      value: 44.87893284011915
    - type: nauc_ndcg_at_10_max
      value: 32.384885249478515
    - type: nauc_ndcg_at_10_std
      value: 1.454493065035396
    - type: nauc_ndcg_at_1_diff1
      value: 51.61608573254137
    - type: nauc_ndcg_at_1_max
      value: 35.18105023234596
    - type: nauc_ndcg_at_1_std
      value: 0.17943702145478177
    - type: nauc_ndcg_at_20_diff1
      value: 44.867752179050605
    - type: nauc_ndcg_at_20_max
      value: 32.689535921840196
    - type: nauc_ndcg_at_20_std
      value: 2.337765158573901
    - type: nauc_ndcg_at_3_diff1
      value: 45.87485821381341
    - type: nauc_ndcg_at_3_max
      value: 32.33282450558947
    - type: nauc_ndcg_at_3_std
      value: 0.0681643829273283
    - type: nauc_ndcg_at_5_diff1
      value: 45.202902131892394
    - type: nauc_ndcg_at_5_max
      value: 32.1026971523917
    - type: nauc_ndcg_at_5_std
      value: 0.3565572833774486
    - type: nauc_precision_at_1000_diff1
      value: -8.935267931198956
    - type: nauc_precision_at_1000_max
      value: 6.464981960169269
    - type: nauc_precision_at_1000_std
      value: 10.662786182234633
    - type: nauc_precision_at_100_diff1
      value: -1.64091517847155
    - type: nauc_precision_at_100_max
      value: 15.175617871025024
    - type: nauc_precision_at_100_std
      value: 16.924256989248075
    - type: nauc_precision_at_10_diff1
      value: 15.676651966277047
    - type: nauc_precision_at_10_max
      value: 26.243734188847117
    - type: nauc_precision_at_10_std
      value: 10.601741034956333
    - type: nauc_precision_at_1_diff1
      value: 51.61608573254137
    - type: nauc_precision_at_1_max
      value: 35.18105023234596
    - type: nauc_precision_at_1_std
      value: 0.17943702145478177
    - type: nauc_precision_at_20_diff1
      value: 9.447267260198654
    - type: nauc_precision_at_20_max
      value: 23.024130858142723
    - type: nauc_precision_at_20_std
      value: 13.739145648899603
    - type: nauc_precision_at_3_diff1
      value: 30.11583572134629
    - type: nauc_precision_at_3_max
      value: 31.37321080069495
    - type: nauc_precision_at_3_std
      value: 4.705512374126024
    - type: nauc_precision_at_5_diff1
      value: 23.192015335996093
    - type: nauc_precision_at_5_max
      value: 29.415746835998764
    - type: nauc_precision_at_5_std
      value: 6.843498772798558
    - type: nauc_recall_at_1000_diff1
      value: 25.36573313426033
    - type: nauc_recall_at_1000_max
      value: 43.06672256524168
    - type: nauc_recall_at_1000_std
      value: 47.93664853815292
    - type: nauc_recall_at_100_diff1
      value: 31.222880916617406
    - type: nauc_recall_at_100_max
      value: 31.761159904172658
    - type: nauc_recall_at_100_std
      value: 23.034218976635877
    - type: nauc_recall_at_10_diff1
      value: 36.23439028915225
    - type: nauc_recall_at_10_max
      value: 28.473458977606438
    - type: nauc_recall_at_10_std
      value: 3.7797969934159
    - type: nauc_recall_at_1_diff1
      value: 52.48913346466124
    - type: nauc_recall_at_1_max
      value: 29.874374024967725
    - type: nauc_recall_at_1_std
      value: -2.433547569836134
    - type: nauc_recall_at_20_diff1
      value: 34.678676952584766
    - type: nauc_recall_at_20_max
      value: 29.04638392522168
    - type: nauc_recall_at_20_std
      value: 8.148894982082549
    - type: nauc_recall_at_3_diff1
      value: 41.31029996231311
    - type: nauc_recall_at_3_max
      value: 28.44199443414157
    - type: nauc_recall_at_3_std
      value: -0.747324057600377
    - type: nauc_recall_at_5_diff1
      value: 38.535873899920674
    - type: nauc_recall_at_5_max
      value: 27.942667805948375
    - type: nauc_recall_at_5_std
      value: 0.30652206930973686
    - type: ndcg_at_1
      value: 36.47675
    - type: ndcg_at_10
      value: 47.74883333333334
    - type: ndcg_at_100
      value: 52.902416666666674
    - type: ndcg_at_1000
      value: 54.69116666666667
    - type: ndcg_at_20
      value: 49.89758333333333
    - type: ndcg_at_3
      value: 42.462250000000004
    - type: ndcg_at_5
      value: 44.91841666666667
    - type: precision_at_1
      value: 36.47675
    - type: precision_at_10
      value: 8.582416666666665
    - type: precision_at_100
      value: 1.31475
    - type: precision_at_1000
      value: 0.16458333333333333
    - type: precision_at_20
      value: 5.021833333333333
    - type: precision_at_3
      value: 20.004499999999997
    - type: precision_at_5
      value: 14.178666666666665
    - type: recall_at_1
      value: 30.179249999999996
    - type: recall_at_10
      value: 60.950166666666675
    - type: recall_at_100
      value: 83.19025
    - type: recall_at_1000
      value: 95.27774999999998
    - type: recall_at_20
      value: 68.80175
    - type: recall_at_3
      value: 46.01841666666666
    - type: recall_at_5
      value: 52.482416666666666
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB CQADupstackStatsRetrieval
      revision: 65ac3a16b8e91f9cee4c9828cc7c335575432a2a
      split: test
      type: mteb/cqadupstack-stats
    metrics:
    - type: main_score
      value: 42.088
    - type: map_at_1
      value: 27.842
    - type: map_at_10
      value: 36.948
    - type: map_at_100
      value: 38.017
    - type: map_at_1000
      value: 38.109
    - type: map_at_20
      value: 37.516
    - type: map_at_3
      value: 34.111000000000004
    - type: map_at_5
      value: 35.69
    - type: mrr_at_1
      value: 31.901840490797547
    - type: mrr_at_10
      value: 40.27710828707761
    - type: mrr_at_100
      value: 41.149090448206785
    - type: mrr_at_1000
      value: 41.213796330959845
    - type: mrr_at_20
      value: 40.75757473043628
    - type: mrr_at_3
      value: 37.85787321063395
    - type: mrr_at_5
      value: 39.22290388548056
    - type: nauc_map_at_1000_diff1
      value: 54.61566029116032
    - type: nauc_map_at_1000_max
      value: 40.138557245628405
    - type: nauc_map_at_1000_std
      value: 1.3601229535722448
    - type: nauc_map_at_100_diff1
      value: 54.591685538932666
    - type: nauc_map_at_100_max
      value: 40.103258261336116
    - type: nauc_map_at_100_std
      value: 1.3193639839585527
    - type: nauc_map_at_10_diff1
      value: 54.877494201740575
    - type: nauc_map_at_10_max
      value: 39.858924128386356
    - type: nauc_map_at_10_std
      value: 1.043199544642079
    - type: nauc_map_at_1_diff1
      value: 61.23575497820379
    - type: nauc_map_at_1_max
      value: 40.509267645549016
    - type: nauc_map_at_1_std
      value: -2.501859215320505
    - type: nauc_map_at_20_diff1
      value: 54.646983639740945
    - type: nauc_map_at_20_max
      value: 40.00719058704446
    - type: nauc_map_at_20_std
      value: 1.168227947649819
    - type: nauc_map_at_3_diff1
      value: 56.14955028519406
    - type: nauc_map_at_3_max
      value: 40.59554072461519
    - type: nauc_map_at_3_std
      value: -0.640510661185155
    - type: nauc_map_at_5_diff1
      value: 55.025033173818336
    - type: nauc_map_at_5_max
      value: 40.31755086883854
    - type: nauc_map_at_5_std
      value: 0.3991058966794467
    - type: nauc_mrr_at_1000_diff1
      value: 55.55545769747445
    - type: nauc_mrr_at_1000_max
      value: 42.60411604361116
    - type: nauc_mrr_at_1000_std
      value: 2.573975721013623
    - type: nauc_mrr_at_100_diff1
      value: 55.53954363695672
    - type: nauc_mrr_at_100_max
      value: 42.58467449227468
    - type: nauc_mrr_at_100_std
      value: 2.554517920300089
    - type: nauc_mrr_at_10_diff1
      value: 55.74151557656298
    - type: nauc_mrr_at_10_max
      value: 42.5132399457698
    - type: nauc_mrr_at_10_std
      value: 2.3585516824867434
    - type: nauc_mrr_at_1_diff1
      value: 62.01205399308514
    - type: nauc_mrr_at_1_max
      value: 44.19608859806141
    - type: nauc_mrr_at_1_std
      value: 0.5061111299485684
    - type: nauc_mrr_at_20_diff1
      value: 55.62472789910339
    - type: nauc_mrr_at_20_max
      value: 42.644662244470084
    - type: nauc_mrr_at_20_std
      value: 2.56548024772991
    - type: nauc_mrr_at_3_diff1
      value: 57.43794390483703
    - type: nauc_mrr_at_3_max
      value: 43.297436510883905
    - type: nauc_mrr_at_3_std
      value: 1.4139624870962728
    - type: nauc_mrr_at_5_diff1
      value: 56.08859303784681
    - type: nauc_mrr_at_5_max
      value: 42.88164936954427
    - type: nauc_mrr_at_5_std
      value: 1.9227490057593364
    - type: nauc_ndcg_at_1000_diff1
      value: 51.90315173180464
    - type: nauc_ndcg_at_1000_max
      value: 40.56081270445609
    - type: nauc_ndcg_at_1000_std
      value: 4.375505052542293
    - type: nauc_ndcg_at_100_diff1
      value: 51.52704472018422
    - type: nauc_ndcg_at_100_max
      value: 40.04127748829899
    - type: nauc_ndcg_at_100_std
      value: 4.096234919083777
    - type: nauc_ndcg_at_10_diff1
      value: 52.527834518136316
    - type: nauc_ndcg_at_10_max
      value: 39.11422620672842
    - type: nauc_ndcg_at_10_std
      value: 2.5113743626930423
    - type: nauc_ndcg_at_1_diff1
      value: 62.01205399308514
    - type: nauc_ndcg_at_1_max
      value: 44.19608859806141
    - type: nauc_ndcg_at_1_std
      value: 0.5061111299485684
    - type: nauc_ndcg_at_20_diff1
      value: 51.78503805848182
    - type: nauc_ndcg_at_20_max
      value: 39.553253285969525
    - type: nauc_ndcg_at_20_std
      value: 3.1435512234873784
    - type: nauc_ndcg_at_3_diff1
      value: 55.17727016530467
    - type: nauc_ndcg_at_3_max
      value: 41.62220051468326
    - type: nauc_ndcg_at_3_std
      value: 0.170785014256851
    - type: nauc_ndcg_at_5_diff1
      value: 53.01310617471978
    - type: nauc_ndcg_at_5_max
      value: 40.37643667834214
    - type: nauc_ndcg_at_5_std
      value: 1.270149201159188
    - type: nauc_precision_at_1000_diff1
      value: -0.11996625198994583
    - type: nauc_precision_at_1000_max
      value: 16.866734452178175
    - type: nauc_precision_at_1000_std
      value: 11.552826379568124
    - type: nauc_precision_at_100_diff1
      value: 14.63054252341779
    - type: nauc_precision_at_100_max
      value: 26.965458398098264
    - type: nauc_precision_at_100_std
      value: 15.440647927645406
    - type: nauc_precision_at_10_diff1
      value: 34.56196869357697
    - type: nauc_precision_at_10_max
      value: 34.704664579952464
    - type: nauc_precision_at_10_std
      value: 11.839293378857143
    - type: nauc_precision_at_1_diff1
      value: 62.01205399308514
    - type: nauc_precision_at_1_max
      value: 44.19608859806141
    - type: nauc_precision_at_1_std
      value: 0.5061111299485684
    - type: nauc_precision_at_20_diff1
      value: 27.764170365573452
    - type: nauc_precision_at_20_max
      value: 33.57330325847278
    - type: nauc_precision_at_20_std
      value: 13.081677793643415
    - type: nauc_precision_at_3_diff1
      value: 46.88595265423412
    - type: nauc_precision_at_3_max
      value: 42.5885632193871
    - type: nauc_precision_at_3_std
      value: 4.683698609960498
    - type: nauc_precision_at_5_diff1
      value: 39.515700464802755
    - type: nauc_precision_at_5_max
      value: 40.17055596823263
    - type: nauc_precision_at_5_std
      value: 9.471526935004691
    - type: nauc_recall_at_1000_diff1
      value: 9.815704767870127
    - type: nauc_recall_at_1000_max
      value: 34.85267826940964
    - type: nauc_recall_at_1000_std
      value: 50.07053698113471
    - type: nauc_recall_at_100_diff1
      value: 31.542342038446332
    - type: nauc_recall_at_100_max
      value: 33.204804837272
    - type: nauc_recall_at_100_std
      value: 18.103348454879914
    - type: nauc_recall_at_10_diff1
      value: 42.17157104039057
    - type: nauc_recall_at_10_max
      value: 32.03520274748068
    - type: nauc_recall_at_10_std
      value: 5.6739508166433295
    - type: nauc_recall_at_1_diff1
      value: 61.23575497820379
    - type: nauc_recall_at_1_max
      value: 40.509267645549016
    - type: nauc_recall_at_1_std
      value: -2.501859215320505
    - type: nauc_recall_at_20_diff1
      value: 38.251645749760186
    - type: nauc_recall_at_20_max
      value: 32.32645924242071
    - type: nauc_recall_at_20_std
      value: 8.11256769262173
    - type: nauc_recall_at_3_diff1
      value: 49.53236305060202
    - type: nauc_recall_at_3_max
      value: 37.92318361460069
    - type: nauc_recall_at_3_std
      value: -0.5543411253371702
    - type: nauc_recall_at_5_diff1
      value: 44.08014119458319
    - type: nauc_recall_at_5_max
      value: 35.28363364060963
    - type: nauc_recall_at_5_std
      value: 2.000585201707296
    - type: ndcg_at_1
      value: 31.902
    - type: ndcg_at_10
      value: 42.088
    - type: ndcg_at_100
      value: 47.111999999999995
    - type: ndcg_at_1000
      value: 49.289
    - type: ndcg_at_20
      value: 43.936
    - type: ndcg_at_3
      value: 37.120999999999995
    - type: ndcg_at_5
      value: 39.507
    - type: precision_at_1
      value: 31.902
    - type: precision_at_10
      value: 6.779
    - type: precision_at_100
      value: 1.002
    - type: precision_at_1000
      value: 0.126
    - type: precision_at_20
      value: 3.857
    - type: precision_at_3
      value: 16.207
    - type: precision_at_5
      value: 11.379999999999999
    - type: recall_at_1
      value: 27.842
    - type: recall_at_10
      value: 54.462999999999994
    - type: recall_at_100
      value: 77.273
    - type: recall_at_1000
      value: 92.96900000000001
    - type: recall_at_20
      value: 61.392
    - type: recall_at_3
      value: 40.715
    - type: recall_at_5
      value: 46.763
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB CQADupstackTexRetrieval
      revision: 46989137a86843e03a6195de44b09deda022eec7
      split: test
      type: mteb/cqadupstack-tex
    metrics:
    - type: main_score
      value: 35.695
    - type: map_at_1
      value: 21.3
    - type: map_at_10
      value: 30.206
    - type: map_at_100
      value: 31.518
    - type: map_at_1000
      value: 31.641000000000002
    - type: map_at_20
      value: 30.956
    - type: map_at_3
      value: 27.372999999999998
    - type: map_at_5
      value: 28.872999999999998
    - type: mrr_at_1
      value: 26.634549208534068
    - type: mrr_at_10
      value: 34.99146538633813
    - type: mrr_at_100
      value: 35.963474572280546
    - type: mrr_at_1000
      value: 36.03093496246274
    - type: mrr_at_20
      value: 35.5864558592648
    - type: mrr_at_3
      value: 32.61642578573075
    - type: mrr_at_5
      value: 33.898256480844346
    - type: nauc_map_at_1000_diff1
      value: 36.574400394232335
    - type: nauc_map_at_1000_max
      value: 26.140103422500633
    - type: nauc_map_at_1000_std
      value: 6.560014457471597
    - type: nauc_map_at_100_diff1
      value: 36.532495247648114
    - type: nauc_map_at_100_max
      value: 26.119709494991945
    - type: nauc_map_at_100_std
      value: 6.531476971829413
    - type: nauc_map_at_10_diff1
      value: 36.787900510346496
    - type: nauc_map_at_10_max
      value: 26.012094027181433
    - type: nauc_map_at_10_std
      value: 5.958149844466696
    - type: nauc_map_at_1_diff1
      value: 41.12910465822455
    - type: nauc_map_at_1_max
      value: 24.922839565199613
    - type: nauc_map_at_1_std
      value: 4.133739487187822
    - type: nauc_map_at_20_diff1
      value: 36.670852346802775
    - type: nauc_map_at_20_max
      value: 26.04401134304956
    - type: nauc_map_at_20_std
      value: 6.276890221629242
    - type: nauc_map_at_3_diff1
      value: 36.9645976302353
    - type: nauc_map_at_3_max
      value: 25.23669772818175
    - type: nauc_map_at_3_std
      value: 4.847234233812939
    - type: nauc_map_at_5_diff1
      value: 36.88502579253138
    - type: nauc_map_at_5_max
      value: 25.579662002376235
    - type: nauc_map_at_5_std
      value: 5.373806788582024
    - type: nauc_mrr_at_1000_diff1
      value: 36.226802392893354
    - type: nauc_mrr_at_1000_max
      value: 26.845815630397148
    - type: nauc_mrr_at_1000_std
      value: 7.453084590273735
    - type: nauc_mrr_at_100_diff1
      value: 36.206650499203974
    - type: nauc_mrr_at_100_max
      value: 26.839285742065844
    - type: nauc_mrr_at_100_std
      value: 7.4531214081950665
    - type: nauc_mrr_at_10_diff1
      value: 36.30447424000286
    - type: nauc_mrr_at_10_max
      value: 26.82407721635929
    - type: nauc_mrr_at_10_std
      value: 7.128350859354006
    - type: nauc_mrr_at_1_diff1
      value: 40.33242024913157
    - type: nauc_mrr_at_1_max
      value: 27.091486246948644
    - type: nauc_mrr_at_1_std
      value: 6.651284050654496
    - type: nauc_mrr_at_20_diff1
      value: 36.25133940616511
    - type: nauc_mrr_at_20_max
      value: 26.80492854473064
    - type: nauc_mrr_at_20_std
      value: 7.357308723900899
    - type: nauc_mrr_at_3_diff1
      value: 36.56178278497094
    - type: nauc_mrr_at_3_max
      value: 26.778158065345036
    - type: nauc_mrr_at_3_std
      value: 6.6184108126324315
    - type: nauc_mrr_at_5_diff1
      value: 36.392351544524246
    - type: nauc_mrr_at_5_max
      value: 26.739980026222078
    - type: nauc_mrr_at_5_std
      value: 6.756111945913891
    - type: nauc_ndcg_at_1000_diff1
      value: 34.95079579203404
    - type: nauc_ndcg_at_1000_max
      value: 27.20208866490515
    - type: nauc_ndcg_at_1000_std
      value: 9.261368905154118
    - type: nauc_ndcg_at_100_diff1
      value: 34.23419180931321
    - type: nauc_ndcg_at_100_max
      value: 26.813354471991328
    - type: nauc_ndcg_at_100_std
      value: 9.32209446793392
    - type: nauc_ndcg_at_10_diff1
      value: 35.35968678440425
    - type: nauc_ndcg_at_10_max
      value: 26.46708774056249
    - type: nauc_ndcg_at_10_std
      value: 7.301241728262717
    - type: nauc_ndcg_at_1_diff1
      value: 40.33242024913157
    - type: nauc_ndcg_at_1_max
      value: 27.091486246948644
    - type: nauc_ndcg_at_1_std
      value: 6.651284050654496
    - type: nauc_ndcg_at_20_diff1
      value: 35.03849294787951
    - type: nauc_ndcg_at_20_max
      value: 26.409827567943882
    - type: nauc_ndcg_at_20_std
      value: 8.055637424086237
    - type: nauc_ndcg_at_3_diff1
      value: 35.65505388433528
    - type: nauc_ndcg_at_3_max
      value: 25.761188798312208
    - type: nauc_ndcg_at_3_std
      value: 5.904185852803786
    - type: nauc_ndcg_at_5_diff1
      value: 35.613042597941416
    - type: nauc_ndcg_at_5_max
      value: 25.91763716317898
    - type: nauc_ndcg_at_5_std
      value: 6.3359295002576825
    - type: nauc_precision_at_1000_diff1
      value: 9.984149195871025
    - type: nauc_precision_at_1000_max
      value: 13.706584530811504
    - type: nauc_precision_at_1000_std
      value: 10.808393484427647
    - type: nauc_precision_at_100_diff1
      value: 9.753861262312848
    - type: nauc_precision_at_100_max
      value: 17.538086631929836
    - type: nauc_precision_at_100_std
      value: 17.588307297546375
    - type: nauc_precision_at_10_diff1
      value: 22.178680553578857
    - type: nauc_precision_at_10_max
      value: 23.82005220714167
    - type: nauc_precision_at_10_std
      value: 12.210843300842786
    - type: nauc_precision_at_1_diff1
      value: 40.33242024913157
    - type: nauc_precision_at_1_max
      value: 27.091486246948644
    - type: nauc_precision_at_1_std
      value: 6.651284050654496
    - type: nauc_precision_at_20_diff1
      value: 18.20284235467181
    - type: nauc_precision_at_20_max
      value: 21.55994934799995
    - type: nauc_precision_at_20_std
      value: 14.823512635496444
    - type: nauc_precision_at_3_diff1
      value: 28.51175964422829
    - type: nauc_precision_at_3_max
      value: 26.036101082651903
    - type: nauc_precision_at_3_std
      value: 8.32337618430701
    - type: nauc_precision_at_5_diff1
      value: 26.03785153029795
    - type: nauc_precision_at_5_max
      value: 25.62122042616537
    - type: nauc_precision_at_5_std
      value: 10.010491130373877
    - type: nauc_recall_at_1000_diff1
      value: 21.16205088053666
    - type: nauc_recall_at_1000_max
      value: 37.893638759886564
    - type: nauc_recall_at_1000_std
      value: 34.61273354489395
    - type: nauc_recall_at_100_diff1
      value: 21.14198721349634
    - type: nauc_recall_at_100_max
      value: 25.920059670195094
    - type: nauc_recall_at_100_std
      value: 20.518028066597463
    - type: nauc_recall_at_10_diff1
      value: 29.73472729380844
    - type: nauc_recall_at_10_max
      value: 24.853019683450643
    - type: nauc_recall_at_10_std
      value: 8.89065056391719
    - type: nauc_recall_at_1_diff1
      value: 41.12910465822455
    - type: nauc_recall_at_1_max
      value: 24.922839565199613
    - type: nauc_recall_at_1_std
      value: 4.133739487187822
    - type: nauc_recall_at_20_diff1
      value: 27.673332407195627
    - type: nauc_recall_at_20_max
      value: 23.71384644501052
    - type: nauc_recall_at_20_std
      value: 11.300075581386578
    - type: nauc_recall_at_3_diff1
      value: 32.075174207271715
    - type: nauc_recall_at_3_max
      value: 23.714760452502023
    - type: nauc_recall_at_3_std
      value: 4.987005671759398
    - type: nauc_recall_at_5_diff1
      value: 31.33818717257691
    - type: nauc_recall_at_5_max
      value: 23.698331718798485
    - type: nauc_recall_at_5_std
      value: 6.167112844989579
    - type: ndcg_at_1
      value: 26.634999999999998
    - type: ndcg_at_10
      value: 35.695
    - type: ndcg_at_100
      value: 41.410000000000004
    - type: ndcg_at_1000
      value: 43.963
    - type: ndcg_at_20
      value: 38.023
    - type: ndcg_at_3
      value: 31.019000000000002
    - type: ndcg_at_5
      value: 33.054
    - type: precision_at_1
      value: 26.634999999999998
    - type: precision_at_10
      value: 6.654999999999999
    - type: precision_at_100
      value: 1.1039999999999999
    - type: precision_at_1000
      value: 0.15
    - type: precision_at_20
      value: 4.0280000000000005
    - type: precision_at_3
      value: 14.969
    - type: precision_at_5
      value: 10.75
    - type: recall_at_1
      value: 21.3
    - type: recall_at_10
      value: 47.274
    - type: recall_at_100
      value: 72.576
    - type: recall_at_1000
      value: 90.33099999999999
    - type: recall_at_20
      value: 55.852999999999994
    - type: recall_at_3
      value: 33.833999999999996
    - type: recall_at_5
      value: 39.306000000000004
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB CQADupstackUnixRetrieval
      revision: 6c6430d3a6d36f8d2a829195bc5dc94d7e063e53
      split: test
      type: mteb/cqadupstack-unix
    metrics:
    - type: main_score
      value: 48.254000000000005
    - type: map_at_1
      value: 31.058999999999997
    - type: map_at_10
      value: 42.184
    - type: map_at_100
      value: 43.486000000000004
    - type: map_at_1000
      value: 43.580999999999996
    - type: map_at_20
      value: 42.925000000000004
    - type: map_at_3
      value: 38.807
    - type: map_at_5
      value: 40.716
    - type: mrr_at_1
      value: 37.12686567164179
    - type: mrr_at_10
      value: 46.90539119876802
    - type: mrr_at_100
      value: 47.76243092540689
    - type: mrr_at_1000
      value: 47.81385590652854
    - type: mrr_at_20
      value: 47.43082203094801
    - type: mrr_at_3
      value: 44.21641791044772
    - type: mrr_at_5
      value: 45.7975746268656
    - type: nauc_map_at_1000_diff1
      value: 51.4558447015615
    - type: nauc_map_at_1000_max
      value: 38.45945877475137
    - type: nauc_map_at_1000_std
      value: 1.4496436945102138
    - type: nauc_map_at_100_diff1
      value: 51.433266542284095
    - type: nauc_map_at_100_max
      value: 38.442249480858834
    - type: nauc_map_at_100_std
      value: 1.4472006787823615
    - type: nauc_map_at_10_diff1
      value: 51.2169946617527
    - type: nauc_map_at_10_max
      value: 37.91575906488831
    - type: nauc_map_at_10_std
      value: 0.9395292392054411
    - type: nauc_map_at_1_diff1
      value: 57.06692954349093
    - type: nauc_map_at_1_max
      value: 37.52195301264229
    - type: nauc_map_at_1_std
      value: 1.0317959357152677
    - type: nauc_map_at_20_diff1
      value: 51.39166717137811
    - type: nauc_map_at_20_max
      value: 38.30425708455791
    - type: nauc_map_at_20_std
      value: 1.1678146894626718
    - type: nauc_map_at_3_diff1
      value: 52.284386388905205
    - type: nauc_map_at_3_max
      value: 37.77544254509988
    - type: nauc_map_at_3_std
      value: 0.4509178159923028
    - type: nauc_map_at_5_diff1
      value: 51.92099853890086
    - type: nauc_map_at_5_max
      value: 38.04410222885556
    - type: nauc_map_at_5_std
      value: 0.49356799186598777
    - type: nauc_mrr_at_1000_diff1
      value: 50.83672022787427
    - type: nauc_mrr_at_1000_max
      value: 40.40639302900314
    - type: nauc_mrr_at_1000_std
      value: 3.021173876177588
    - type: nauc_mrr_at_100_diff1
      value: 50.81622141227109
    - type: nauc_mrr_at_100_max
      value: 40.391753930357424
    - type: nauc_mrr_at_100_std
      value: 3.0149687206608435
    - type: nauc_mrr_at_10_diff1
      value: 50.610842445863504
    - type: nauc_mrr_at_10_max
      value: 40.292536027495906
    - type: nauc_mrr_at_10_std
      value: 2.8205411230714423
    - type: nauc_mrr_at_1_diff1
      value: 55.93133439246388
    - type: nauc_mrr_at_1_max
      value: 41.64878657954779
    - type: nauc_mrr_at_1_std
      value: 3.6875867041356862
    - type: nauc_mrr_at_20_diff1
      value: 50.800509011749874
    - type: nauc_mrr_at_20_max
      value: 40.37785685396547
    - type: nauc_mrr_at_20_std
      value: 2.861233504434791
    - type: nauc_mrr_at_3_diff1
      value: 51.32672688744832
    - type: nauc_mrr_at_3_max
      value: 40.68903973754008
    - type: nauc_mrr_at_3_std
      value: 2.491026086202177
    - type: nauc_mrr_at_5_diff1
      value: 50.87923319570954
    - type: nauc_mrr_at_5_max
      value: 40.56793174802199
    - type: nauc_mrr_at_5_std
      value: 2.3822611439240498
    - type: nauc_ndcg_at_1000_diff1
      value: 49.78740830809827
    - type: nauc_ndcg_at_1000_max
      value: 39.19945785583833
    - type: nauc_ndcg_at_1000_std
      value: 3.197089736978403
    - type: nauc_ndcg_at_100_diff1
      value: 49.176636212489264
    - type: nauc_ndcg_at_100_max
      value: 38.75259199237999
    - type: nauc_ndcg_at_100_std
      value: 3.5088596331762254
    - type: nauc_ndcg_at_10_diff1
      value: 48.67385674355404
    - type: nauc_ndcg_at_10_max
      value: 37.40965505388787
    - type: nauc_ndcg_at_10_std
      value: 1.4005200795238943
    - type: nauc_ndcg_at_1_diff1
      value: 55.93133439246388
    - type: nauc_ndcg_at_1_max
      value: 41.64878657954779
    - type: nauc_ndcg_at_1_std
      value: 3.6875867041356862
    - type: nauc_ndcg_at_20_diff1
      value: 49.23395020884403
    - type: nauc_ndcg_at_20_max
      value: 38.29413681599753
    - type: nauc_ndcg_at_20_std
      value: 2.0261582977308903
    - type: nauc_ndcg_at_3_diff1
      value: 50.37879167712567
    - type: nauc_ndcg_at_3_max
      value: 38.30708528778667
    - type: nauc_ndcg_at_3_std
      value: 0.7482238068027645
    - type: nauc_ndcg_at_5_diff1
      value: 49.7874793326571
    - type: nauc_ndcg_at_5_max
      value: 37.92115937776956
    - type: nauc_ndcg_at_5_std
      value: 0.3066787171114837
    - type: nauc_precision_at_1000_diff1
      value: -9.96531693883328
    - type: nauc_precision_at_1000_max
      value: 3.4627078237504634
    - type: nauc_precision_at_1000_std
      value: 3.6103904347228917
    - type: nauc_precision_at_100_diff1
      value: -1.3777100103786304
    - type: nauc_precision_at_100_max
      value: 13.644624976237932
    - type: nauc_precision_at_100_std
      value: 9.379466477252286
    - type: nauc_precision_at_10_diff1
      value: 18.868006929242437
    - type: nauc_precision_at_10_max
      value: 27.342748504326668
    - type: nauc_precision_at_10_std
      value: 2.250963665566955
    - type: nauc_precision_at_1_diff1
      value: 55.93133439246388
    - type: nauc_precision_at_1_max
      value: 41.64878657954779
    - type: nauc_precision_at_1_std
      value: 3.6875867041356862
    - type: nauc_precision_at_20_diff1
      value: 13.08070242743754
    - type: nauc_precision_at_20_max
      value: 25.586231504695878
    - type: nauc_precision_at_20_std
      value: 4.410767200400472
    - type: nauc_precision_at_3_diff1
      value: 36.315597960821385
    - type: nauc_precision_at_3_max
      value: 35.7897272478074
    - type: nauc_precision_at_3_std
      value: 0.5393014854836691
    - type: nauc_precision_at_5_diff1
      value: 28.951288404329766
    - type: nauc_precision_at_5_max
      value: 33.52407854361305
    - type: nauc_precision_at_5_std
      value: 0.6755786324554106
    - type: nauc_recall_at_1000_diff1
      value: 17.993868934514715
    - type: nauc_recall_at_1000_max
      value: 43.00675041530867
    - type: nauc_recall_at_1000_std
      value: 45.60811034522631
    - type: nauc_recall_at_100_diff1
      value: 32.66185575711067
    - type: nauc_recall_at_100_max
      value: 32.56190006302012
    - type: nauc_recall_at_100_std
      value: 16.814907489166366
    - type: nauc_recall_at_10_diff1
      value: 38.077558092701516
    - type: nauc_recall_at_10_max
      value: 29.919557204665566
    - type: nauc_recall_at_10_std
      value: 1.4252796105147276
    - type: nauc_recall_at_1_diff1
      value: 57.06692954349093
    - type: nauc_recall_at_1_max
      value: 37.52195301264229
    - type: nauc_recall_at_1_std
      value: 1.0317959357152677
    - type: nauc_recall_at_20_diff1
      value: 39.11878095285628
    - type: nauc_recall_at_20_max
      value: 31.98554679525679
    - type: nauc_recall_at_20_std
      value: 3.5833443797094557
    - type: nauc_recall_at_3_diff1
      value: 45.38872391135796
    - type: nauc_recall_at_3_max
      value: 33.91070676314719
    - type: nauc_recall_at_3_std
      value: -1.21372888057884
    - type: nauc_recall_at_5_diff1
      value: 42.9812450636276
    - type: nauc_recall_at_5_max
      value: 32.992197458198106
    - type: nauc_recall_at_5_std
      value: -1.6465957495550636
    - type: ndcg_at_1
      value: 37.126999999999995
    - type: ndcg_at_10
      value: 48.254000000000005
    - type: ndcg_at_100
      value: 53.547999999999995
    - type: ndcg_at_1000
      value: 55.425000000000004
    - type: ndcg_at_20
      value: 50.409000000000006
    - type: ndcg_at_3
      value: 42.69
    - type: ndcg_at_5
      value: 45.359
    - type: precision_at_1
      value: 37.126999999999995
    - type: precision_at_10
      value: 8.283999999999999
    - type: precision_at_100
      value: 1.224
    - type: precision_at_1000
      value: 0.147
    - type: precision_at_20
      value: 4.776
    - type: precision_at_3
      value: 19.714000000000002
    - type: precision_at_5
      value: 13.955
    - type: recall_at_1
      value: 31.058999999999997
    - type: recall_at_10
      value: 61.955000000000005
    - type: recall_at_100
      value: 83.994
    - type: recall_at_1000
      value: 96.75
    - type: recall_at_20
      value: 69.458
    - type: recall_at_3
      value: 46.394000000000005
    - type: recall_at_5
      value: 53.419000000000004
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB CQADupstackWebmastersRetrieval
      revision: 160c094312a0e1facb97e55eeddb698c0abe3571
      split: test
      type: mteb/cqadupstack-webmasters
    metrics:
    - type: main_score
      value: 47.625
    - type: map_at_1
      value: 28.828
    - type: map_at_10
      value: 40.934
    - type: map_at_100
      value: 42.762
    - type: map_at_1000
      value: 42.985
    - type: map_at_20
      value: 41.857
    - type: map_at_3
      value: 37.861
    - type: map_at_5
      value: 39.517
    - type: mrr_at_1
      value: 35.573122529644266
    - type: mrr_at_10
      value: 46.13032498902065
    - type: mrr_at_100
      value: 47.01689487158973
    - type: mrr_at_1000
      value: 47.05482579853294
    - type: mrr_at_20
      value: 46.618451847491315
    - type: mrr_at_3
      value: 43.741765480895936
    - type: mrr_at_5
      value: 45.1844532279315
    - type: nauc_map_at_1000_diff1
      value: 48.77406678111267
    - type: nauc_map_at_1000_max
      value: 29.14679611765707
    - type: nauc_map_at_1000_std
      value: 10.438826979520995
    - type: nauc_map_at_100_diff1
      value: 48.954012673349126
    - type: nauc_map_at_100_max
      value: 29.283862389807314
    - type: nauc_map_at_100_std
      value: 9.928399080485168
    - type: nauc_map_at_10_diff1
      value: 49.41573056795243
    - type: nauc_map_at_10_max
      value: 28.93790324706381
    - type: nauc_map_at_10_std
      value: 8.007413834048545
    - type: nauc_map_at_1_diff1
      value: 55.26744597511385
    - type: nauc_map_at_1_max
      value: 29.656962248604547
    - type: nauc_map_at_1_std
      value: 6.496654661609257
    - type: nauc_map_at_20_diff1
      value: 49.02827194771431
    - type: nauc_map_at_20_max
      value: 29.157466445395837
    - type: nauc_map_at_20_std
      value: 8.889368158106869
    - type: nauc_map_at_3_diff1
      value: 49.92449135372416
    - type: nauc_map_at_3_max
      value: 29.030070902700633
    - type: nauc_map_at_3_std
      value: 6.988810033527698
    - type: nauc_map_at_5_diff1
      value: 49.64125376372618
    - type: nauc_map_at_5_max
      value: 28.65366881384872
    - type: nauc_map_at_5_std
      value: 6.850897141779166
    - type: nauc_mrr_at_1000_diff1
      value: 47.51489572372838
    - type: nauc_mrr_at_1000_max
      value: 30.56703558832266
    - type: nauc_mrr_at_1000_std
      value: 11.003510282592163
    - type: nauc_mrr_at_100_diff1
      value: 47.4965726288855
    - type: nauc_mrr_at_100_max
      value: 30.547777150740252
    - type: nauc_mrr_at_100_std
      value: 11.024158632984479
    - type: nauc_mrr_at_10_diff1
      value: 47.44362412223882
    - type: nauc_mrr_at_10_max
      value: 30.457562402358583
    - type: nauc_mrr_at_10_std
      value: 10.724316125494697
    - type: nauc_mrr_at_1_diff1
      value: 52.148964351939576
    - type: nauc_mrr_at_1_max
      value: 33.678536351312744
    - type: nauc_mrr_at_1_std
      value: 11.470999800716983
    - type: nauc_mrr_at_20_diff1
      value: 47.34460523851512
    - type: nauc_mrr_at_20_max
      value: 30.469013865786103
    - type: nauc_mrr_at_20_std
      value: 10.921684889846375
    - type: nauc_mrr_at_3_diff1
      value: 47.95877258797435
    - type: nauc_mrr_at_3_max
      value: 30.692710281909562
    - type: nauc_mrr_at_3_std
      value: 10.808031142670313
    - type: nauc_mrr_at_5_diff1
      value: 47.341998958512335
    - type: nauc_mrr_at_5_max
      value: 30.233410609233097
    - type: nauc_mrr_at_5_std
      value: 10.168549484481513
    - type: nauc_ndcg_at_1000_diff1
      value: 46.799656036201796
    - type: nauc_ndcg_at_1000_max
      value: 29.92955740798368
    - type: nauc_ndcg_at_1000_std
      value: 12.623653956716705
    - type: nauc_ndcg_at_100_diff1
      value: 46.639657956193645
    - type: nauc_ndcg_at_100_max
      value: 29.70013635690556
    - type: nauc_ndcg_at_100_std
      value: 13.11403835564951
    - type: nauc_ndcg_at_10_diff1
      value: 46.32468486467343
    - type: nauc_ndcg_at_10_max
      value: 27.861763413803182
    - type: nauc_ndcg_at_10_std
      value: 10.936957612998238
    - type: nauc_ndcg_at_1_diff1
      value: 52.148964351939576
    - type: nauc_ndcg_at_1_max
      value: 33.678536351312744
    - type: nauc_ndcg_at_1_std
      value: 11.470999800716983
    - type: nauc_ndcg_at_20_diff1
      value: 45.54932609594158
    - type: nauc_ndcg_at_20_max
      value: 28.240601529603403
    - type: nauc_ndcg_at_20_std
      value: 11.976619987906291
    - type: nauc_ndcg_at_3_diff1
      value: 46.81299422826539
    - type: nauc_ndcg_at_3_max
      value: 29.15968647348599
    - type: nauc_ndcg_at_3_std
      value: 10.59911489835806
    - type: nauc_ndcg_at_5_diff1
      value: 46.5402791796294
    - type: nauc_ndcg_at_5_max
      value: 27.625492517670764
    - type: nauc_ndcg_at_5_std
      value: 9.801934353035088
    - type: nauc_precision_at_1000_diff1
      value: -21.018206351353395
    - type: nauc_precision_at_1000_max
      value: -9.576873873393701
    - type: nauc_precision_at_1000_std
      value: 40.79498444770508
    - type: nauc_precision_at_100_diff1
      value: -15.107718416928162
    - type: nauc_precision_at_100_max
      value: -1.493344374948485
    - type: nauc_precision_at_100_std
      value: 38.1823156861858
    - type: nauc_precision_at_10_diff1
      value: 9.530038329849683
    - type: nauc_precision_at_10_max
      value: 17.068430234988014
    - type: nauc_precision_at_10_std
      value: 22.723346258198585
    - type: nauc_precision_at_1_diff1
      value: 52.148964351939576
    - type: nauc_precision_at_1_max
      value: 33.678536351312744
    - type: nauc_precision_at_1_std
      value: 11.470999800716983
    - type: nauc_precision_at_20_diff1
      value: -1.8286624283740411
    - type: nauc_precision_at_20_max
      value: 11.189699167855812
    - type: nauc_precision_at_20_std
      value: 28.744505194131186
    - type: nauc_precision_at_3_diff1
      value: 29.590033615831874
    - type: nauc_precision_at_3_max
      value: 26.429375827797298
    - type: nauc_precision_at_3_std
      value: 15.5273969841391
    - type: nauc_precision_at_5_diff1
      value: 20.837334140704538
    - type: nauc_precision_at_5_max
      value: 21.53211730854718
    - type: nauc_precision_at_5_std
      value: 15.770254226373295
    - type: nauc_recall_at_1000_diff1
      value: 3.7913465372858397
    - type: nauc_recall_at_1000_max
      value: 37.37087655432564
    - type: nauc_recall_at_1000_std
      value: 53.383787573977635
    - type: nauc_recall_at_100_diff1
      value: 31.885773379839087
    - type: nauc_recall_at_100_max
      value: 27.119723474909435
    - type: nauc_recall_at_100_std
      value: 32.44128773357717
    - type: nauc_recall_at_10_diff1
      value: 38.48925653392728
    - type: nauc_recall_at_10_max
      value: 21.913297943445638
    - type: nauc_recall_at_10_std
      value: 9.670625471069304
    - type: nauc_recall_at_1_diff1
      value: 55.26744597511385
    - type: nauc_recall_at_1_max
      value: 29.656962248604547
    - type: nauc_recall_at_1_std
      value: 6.496654661609257
    - type: nauc_recall_at_20_diff1
      value: 32.775224475928454
    - type: nauc_recall_at_20_max
      value: 21.855898704010244
    - type: nauc_recall_at_20_std
      value: 15.279476236578427
    - type: nauc_recall_at_3_diff1
      value: 42.46793868969819
    - type: nauc_recall_at_3_max
      value: 23.97410619836597
    - type: nauc_recall_at_3_std
      value: 6.281096355003174
    - type: nauc_recall_at_5_diff1
      value: 40.19624293801811
    - type: nauc_recall_at_5_max
      value: 20.874090229546805
    - type: nauc_recall_at_5_std
      value: 5.640861998007423
    - type: ndcg_at_1
      value: 35.573
    - type: ndcg_at_10
      value: 47.625
    - type: ndcg_at_100
      value: 53.516
    - type: ndcg_at_1000
      value: 55.266999999999996
    - type: ndcg_at_20
      value: 49.809
    - type: ndcg_at_3
      value: 43.108999999999995
    - type: ndcg_at_5
      value: 45.222
    - type: precision_at_1
      value: 35.573
    - type: precision_at_10
      value: 9.447
    - type: precision_at_100
      value: 1.844
    - type: precision_at_1000
      value: 0.256
    - type: precision_at_20
      value: 5.888999999999999
    - type: precision_at_3
      value: 20.883
    - type: precision_at_5
      value: 15.059000000000001
    - type: recall_at_1
      value: 28.828
    - type: recall_at_10
      value: 59.476
    - type: recall_at_100
      value: 86.08
    - type: recall_at_1000
      value: 96.955
    - type: recall_at_20
      value: 67.951
    - type: recall_at_3
      value: 46.568
    - type: recall_at_5
      value: 52.092000000000006
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB CQADupstackWordpressRetrieval
      revision: 4ffe81d471b1924886b33c7567bfb200e9eec5c4
      split: test
      type: mteb/cqadupstack-wordpress
    metrics:
    - type: main_score
      value: 39.379999999999995
    - type: map_at_1
      value: 26.084000000000003
    - type: map_at_10
      value: 34.613
    - type: map_at_100
      value: 35.726
    - type: map_at_1000
      value: 35.817
    - type: map_at_20
      value: 35.201
    - type: map_at_3
      value: 32.274
    - type: map_at_5
      value: 33.555
    - type: mrr_at_1
      value: 29.02033271719039
    - type: mrr_at_10
      value: 37.43075726901975
    - type: mrr_at_100
      value: 38.36239433476147
    - type: mrr_at_1000
      value: 38.42736216591512
    - type: mrr_at_20
      value: 37.93355581794175
    - type: mrr_at_3
      value: 35.39741219963033
    - type: mrr_at_5
      value: 36.53419593345658
    - type: nauc_map_at_1000_diff1
      value: 38.781804068433686
    - type: nauc_map_at_1000_max
      value: 18.694752994022
    - type: nauc_map_at_1000_std
      value: 2.5519685366497864
    - type: nauc_map_at_100_diff1
      value: 38.78325405746408
    - type: nauc_map_at_100_max
      value: 18.685884092519192
    - type: nauc_map_at_100_std
      value: 2.59585073077414
    - type: nauc_map_at_10_diff1
      value: 38.75986643549505
    - type: nauc_map_at_10_max
      value: 18.653645568024267
    - type: nauc_map_at_10_std
      value: 2.0173660776842692
    - type: nauc_map_at_1_diff1
      value: 45.434297335562924
    - type: nauc_map_at_1_max
      value: 18.870845585854045
    - type: nauc_map_at_1_std
      value: 0.1963923383192026
    - type: nauc_map_at_20_diff1
      value: 38.90273902276131
    - type: nauc_map_at_20_max
      value: 18.753294787674115
    - type: nauc_map_at_20_std
      value: 2.210860501783562
    - type: nauc_map_at_3_diff1
      value: 39.559368485502965
    - type: nauc_map_at_3_max
      value: 18.018480187319938
    - type: nauc_map_at_3_std
      value: 1.6922481470404367
    - type: nauc_map_at_5_diff1
      value: 38.45140122170111
    - type: nauc_map_at_5_max
      value: 18.1849659275464
    - type: nauc_map_at_5_std
      value: 1.7201336631050346
    - type: nauc_mrr_at_1000_diff1
      value: 39.156719283573025
    - type: nauc_mrr_at_1000_max
      value: 20.4241142282454
    - type: nauc_mrr_at_1000_std
      value: 4.0326675443965865
    - type: nauc_mrr_at_100_diff1
      value: 39.13134596444042
    - type: nauc_mrr_at_100_max
      value: 20.401832653328036
    - type: nauc_mrr_at_100_std
      value: 4.067459959068112
    - type: nauc_mrr_at_10_diff1
      value: 39.11056900715075
    - type: nauc_mrr_at_10_max
      value: 20.456968932149042
    - type: nauc_mrr_at_10_std
      value: 3.701497341227079
    - type: nauc_mrr_at_1_diff1
      value: 44.724306948944644
    - type: nauc_mrr_at_1_max
      value: 21.297951813248098
    - type: nauc_mrr_at_1_std
      value: 1.7056093167974031
    - type: nauc_mrr_at_20_diff1
      value: 39.13758526011843
    - type: nauc_mrr_at_20_max
      value: 20.470602004704723
    - type: nauc_mrr_at_20_std
      value: 3.7856446687462473
    - type: nauc_mrr_at_3_diff1
      value: 40.239397311526425
    - type: nauc_mrr_at_3_max
      value: 20.992490395710238
    - type: nauc_mrr_at_3_std
      value: 3.7871606030059763
    - type: nauc_mrr_at_5_diff1
      value: 39.128696670419274
    - type: nauc_mrr_at_5_max
      value: 20.575506443481455
    - type: nauc_mrr_at_5_std
      value: 3.5549080224627607
    - type: nauc_ndcg_at_1000_diff1
      value: 37.0016517159043
    - type: nauc_ndcg_at_1000_max
      value: 19.1482194752052
    - type: nauc_ndcg_at_1000_std
      value: 5.378711500654773
    - type: nauc_ndcg_at_100_diff1
      value: 36.17557041559903
    - type: nauc_ndcg_at_100_max
      value: 18.59854501778945
    - type: nauc_ndcg_at_100_std
      value: 6.31248861720501
    - type: nauc_ndcg_at_10_diff1
      value: 36.73409325784973
    - type: nauc_ndcg_at_10_max
      value: 18.822390149084008
    - type: nauc_ndcg_at_10_std
      value: 3.2747769315176276
    - type: nauc_ndcg_at_1_diff1
      value: 44.724306948944644
    - type: nauc_ndcg_at_1_max
      value: 21.297951813248098
    - type: nauc_ndcg_at_1_std
      value: 1.7056093167974031
    - type: nauc_ndcg_at_20_diff1
      value: 36.98513332082282
    - type: nauc_ndcg_at_20_max
      value: 19.09199876979337
    - type: nauc_ndcg_at_20_std
      value: 3.8988673585749765
    - type: nauc_ndcg_at_3_diff1
      value: 38.1362287230064
    - type: nauc_ndcg_at_3_max
      value: 18.947600825842066
    - type: nauc_ndcg_at_3_std
      value: 3.0573764513266837
    - type: nauc_ndcg_at_5_diff1
      value: 36.30379048265372
    - type: nauc_ndcg_at_5_max
      value: 18.459993423164825
    - type: nauc_ndcg_at_5_std
      value: 2.8111098564769605
    - type: nauc_precision_at_1000_diff1
      value: -11.919196633256085
    - type: nauc_precision_at_1000_max
      value: -2.6791276321661734
    - type: nauc_precision_at_1000_std
      value: 3.5303729886014925
    - type: nauc_precision_at_100_diff1
      value: 2.74286346705139
    - type: nauc_precision_at_100_max
      value: 12.944870595453715
    - type: nauc_precision_at_100_std
      value: 19.504700491456116
    - type: nauc_precision_at_10_diff1
      value: 24.0347998139923
    - type: nauc_precision_at_10_max
      value: 22.79629546632503
    - type: nauc_precision_at_10_std
      value: 8.516200784820182
    - type: nauc_precision_at_1_diff1
      value: 44.724306948944644
    - type: nauc_precision_at_1_max
      value: 21.297951813248098
    - type: nauc_precision_at_1_std
      value: 1.7056093167974031
    - type: nauc_precision_at_20_diff1
      value: 21.385129497466938
    - type: nauc_precision_at_20_max
      value: 21.06338576408547
    - type: nauc_precision_at_20_std
      value: 10.496115050816298
    - type: nauc_precision_at_3_diff1
      value: 31.698631519409233
    - type: nauc_precision_at_3_max
      value: 21.0653812345273
    - type: nauc_precision_at_3_std
      value: 7.536571111521341
    - type: nauc_precision_at_5_diff1
      value: 25.92640855765465
    - type: nauc_precision_at_5_max
      value: 21.254782726051953
    - type: nauc_precision_at_5_std
      value: 7.3203658849399496
    - type: nauc_recall_at_1000_diff1
      value: 21.32646653121391
    - type: nauc_recall_at_1000_max
      value: 23.68975318221683
    - type: nauc_recall_at_1000_std
      value: 42.00822770724794
    - type: nauc_recall_at_100_diff1
      value: 20.028899844432022
    - type: nauc_recall_at_100_max
      value: 12.744369014395417
    - type: nauc_recall_at_100_std
      value: 26.67145389470723
    - type: nauc_recall_at_10_diff1
      value: 28.80817601158257
    - type: nauc_recall_at_10_max
      value: 16.334974224702982
    - type: nauc_recall_at_10_std
      value: 5.195951424061981
    - type: nauc_recall_at_1_diff1
      value: 45.434297335562924
    - type: nauc_recall_at_1_max
      value: 18.870845585854045
    - type: nauc_recall_at_1_std
      value: 0.1963923383192026
    - type: nauc_recall_at_20_diff1
      value: 29.41013933162779
    - type: nauc_recall_at_20_max
      value: 17.41848103768873
    - type: nauc_recall_at_20_std
      value: 7.715174946039472
    - type: nauc_recall_at_3_diff1
      value: 33.40119110199151
    - type: nauc_recall_at_3_max
      value: 16.45620877978056
    - type: nauc_recall_at_3_std
      value: 4.0480077397084
    - type: nauc_recall_at_5_diff1
      value: 28.433468467065047
    - type: nauc_recall_at_5_max
      value: 15.724712587196866
    - type: nauc_recall_at_5_std
      value: 3.7484297445312524
    - type: ndcg_at_1
      value: 29.020000000000003
    - type: ndcg_at_10
      value: 39.379999999999995
    - type: ndcg_at_100
      value: 44.956
    - type: ndcg_at_1000
      value: 47.128
    - type: ndcg_at_20
      value: 41.352
    - type: ndcg_at_3
      value: 35.048
    - type: ndcg_at_5
      value: 37.072
    - type: precision_at_1
      value: 29.020000000000003
    - type: precision_at_10
      value: 6.007
    - type: precision_at_100
      value: 0.9520000000000001
    - type: precision_at_1000
      value: 0.126
    - type: precision_at_20
      value: 3.5029999999999997
    - type: precision_at_3
      value: 14.911
    - type: precision_at_5
      value: 10.203
    - type: recall_at_1
      value: 26.084000000000003
    - type: recall_at_10
      value: 51.18899999999999
    - type: recall_at_100
      value: 77.203
    - type: recall_at_1000
      value: 93.145
    - type: recall_at_20
      value: 58.467
    - type: recall_at_3
      value: 39.621
    - type: recall_at_5
      value: 44.476
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB ClimateFEVER
      revision: 47f2ac6acb640fc46020b02a5b59fdda04d39380
      split: test
      type: mteb/climate-fever
    metrics:
    - type: main_score
      value: 46.113
    - type: map_at_1
      value: 20.122999999999998
    - type: map_at_10
      value: 35.474
    - type: map_at_100
      value: 37.592
    - type: map_at_1000
      value: 37.773
    - type: map_at_20
      value: 36.637
    - type: map_at_3
      value: 29.731
    - type: map_at_5
      value: 32.964
    - type: mrr_at_1
      value: 46.71009771986971
    - type: mrr_at_10
      value: 58.855669303552105
    - type: mrr_at_100
      value: 59.389249674038425
    - type: mrr_at_1000
      value: 59.408448104362364
    - type: mrr_at_20
      value: 59.23881203149016
    - type: mrr_at_3
      value: 56.18892508143328
    - type: mrr_at_5
      value: 57.85342019543985
    - type: nauc_map_at_1000_diff1
      value: 27.047031037721958
    - type: nauc_map_at_1000_max
      value: 43.25240279148033
    - type: nauc_map_at_1000_std
      value: 20.795849418696037
    - type: nauc_map_at_100_diff1
      value: 27.044739015116452
    - type: nauc_map_at_100_max
      value: 43.24042159787812
    - type: nauc_map_at_100_std
      value: 20.799952124137683
    - type: nauc_map_at_10_diff1
      value: 27.372696854670338
    - type: nauc_map_at_10_max
      value: 43.054456574721684
    - type: nauc_map_at_10_std
      value: 19.537162110136645
    - type: nauc_map_at_1_diff1
      value: 43.65424623953092
    - type: nauc_map_at_1_max
      value: 45.17986509998762
    - type: nauc_map_at_1_std
      value: 8.497107052335414
    - type: nauc_map_at_20_diff1
      value: 27.224535846566074
    - type: nauc_map_at_20_max
      value: 43.12222854561229
    - type: nauc_map_at_20_std
      value: 20.29982972202669
    - type: nauc_map_at_3_diff1
      value: 30.87847002319001
    - type: nauc_map_at_3_max
      value: 42.890027891707575
    - type: nauc_map_at_3_std
      value: 13.857451947580929
    - type: nauc_map_at_5_diff1
      value: 27.966867093591542
    - type: nauc_map_at_5_max
      value: 42.35826637592201
    - type: nauc_map_at_5_std
      value: 16.993102524058624
    - type: nauc_mrr_at_1000_diff1
      value: 30.191544077608164
    - type: nauc_mrr_at_1000_max
      value: 44.959438920351644
    - type: nauc_mrr_at_1000_std
      value: 24.065801376465114
    - type: nauc_mrr_at_100_diff1
      value: 30.170368115494
    - type: nauc_mrr_at_100_max
      value: 44.955868115761156
    - type: nauc_mrr_at_100_std
      value: 24.093510767847707
    - type: nauc_mrr_at_10_diff1
      value: 30.128430637520175
    - type: nauc_mrr_at_10_max
      value: 44.97689261350708
    - type: nauc_mrr_at_10_std
      value: 24.037049561818897
    - type: nauc_mrr_at_1_diff1
      value: 35.323351939108214
    - type: nauc_mrr_at_1_max
      value: 43.85026244855636
    - type: nauc_mrr_at_1_std
      value: 17.040662141218974
    - type: nauc_mrr_at_20_diff1
      value: 30.192006556160443
    - type: nauc_mrr_at_20_max
      value: 45.02814530774032
    - type: nauc_mrr_at_20_std
      value: 24.20885865448696
    - type: nauc_mrr_at_3_diff1
      value: 29.88250163424518
    - type: nauc_mrr_at_3_max
      value: 44.25768944883186
    - type: nauc_mrr_at_3_std
      value: 22.804183393364198
    - type: nauc_mrr_at_5_diff1
      value: 30.269824490420767
    - type: nauc_mrr_at_5_max
      value: 44.97443265796657
    - type: nauc_mrr_at_5_std
      value: 23.894159916141177
    - type: nauc_ndcg_at_1000_diff1
      value: 24.533764005407356
    - type: nauc_ndcg_at_1000_max
      value: 44.50902713386608
    - type: nauc_ndcg_at_1000_std
      value: 27.589506980238404
    - type: nauc_ndcg_at_100_diff1
      value: 24.209785073940353
    - type: nauc_ndcg_at_100_max
      value: 44.18257063893669
    - type: nauc_ndcg_at_100_std
      value: 27.963150866401943
    - type: nauc_ndcg_at_10_diff1
      value: 25.168069201989486
    - type: nauc_ndcg_at_10_max
      value: 43.84940910683214
    - type: nauc_ndcg_at_10_std
      value: 24.810707270956435
    - type: nauc_ndcg_at_1_diff1
      value: 35.323351939108214
    - type: nauc_ndcg_at_1_max
      value: 43.85026244855636
    - type: nauc_ndcg_at_1_std
      value: 17.040662141218974
    - type: nauc_ndcg_at_20_diff1
      value: 24.829924800466834
    - type: nauc_ndcg_at_20_max
      value: 43.738574327059716
    - type: nauc_ndcg_at_20_std
      value: 26.252370278684072
    - type: nauc_ndcg_at_3_diff1
      value: 27.321943393906274
    - type: nauc_ndcg_at_3_max
      value: 42.16584786993447
    - type: nauc_ndcg_at_3_std
      value: 18.24775079455969
    - type: nauc_ndcg_at_5_diff1
      value: 26.043785418347998
    - type: nauc_ndcg_at_5_max
      value: 42.874593895388344
    - type: nauc_ndcg_at_5_std
      value: 21.294004555506117
    - type: nauc_precision_at_1000_diff1
      value: -22.073027615308582
    - type: nauc_precision_at_1000_max
      value: -6.549723766317357
    - type: nauc_precision_at_1000_std
      value: 18.301749191241306
    - type: nauc_precision_at_100_diff1
      value: -15.654286887593619
    - type: nauc_precision_at_100_max
      value: 6.401516251421999
    - type: nauc_precision_at_100_std
      value: 29.170680324929805
    - type: nauc_precision_at_10_diff1
      value: -4.362381972892247
    - type: nauc_precision_at_10_max
      value: 22.10943515872447
    - type: nauc_precision_at_10_std
      value: 31.869699459530022
    - type: nauc_precision_at_1_diff1
      value: 35.323351939108214
    - type: nauc_precision_at_1_max
      value: 43.85026244855636
    - type: nauc_precision_at_1_std
      value: 17.040662141218974
    - type: nauc_precision_at_20_diff1
      value: -7.50749661117875
    - type: nauc_precision_at_20_max
      value: 16.80584016023257
    - type: nauc_precision_at_20_std
      value: 31.976755897112437
    - type: nauc_precision_at_3_diff1
      value: 7.402667538773083
    - type: nauc_precision_at_3_max
      value: 31.2088401330676
    - type: nauc_precision_at_3_std
      value: 24.287905698405662
    - type: nauc_precision_at_5_diff1
      value: 0.7479172565343901
    - type: nauc_precision_at_5_max
      value: 26.28427734237825
    - type: nauc_precision_at_5_std
      value: 28.246947120310317
    - type: nauc_recall_at_1000_diff1
      value: 2.4778431086370496
    - type: nauc_recall_at_1000_max
      value: 40.2231995797509
    - type: nauc_recall_at_1000_std
      value: 52.62124052183862
    - type: nauc_recall_at_100_diff1
      value: 8.960962419741463
    - type: nauc_recall_at_100_max
      value: 35.81132850291491
    - type: nauc_recall_at_100_std
      value: 40.020903251786166
    - type: nauc_recall_at_10_diff1
      value: 15.603400751376636
    - type: nauc_recall_at_10_max
      value: 37.570127529136485
    - type: nauc_recall_at_10_std
      value: 28.07128410238545
    - type: nauc_recall_at_1_diff1
      value: 43.65424623953092
    - type: nauc_recall_at_1_max
      value: 45.17986509998762
    - type: nauc_recall_at_1_std
      value: 8.497107052335414
    - type: nauc_recall_at_20_diff1
      value: 13.844820282832346
    - type: nauc_recall_at_20_max
      value: 36.0106148516309
    - type: nauc_recall_at_20_std
      value: 31.453103910565254
    - type: nauc_recall_at_3_diff1
      value: 24.359328154117748
    - type: nauc_recall_at_3_max
      value: 39.93774251377568
    - type: nauc_recall_at_3_std
      value: 16.214921517509648
    - type: nauc_recall_at_5_diff1
      value: 18.75788451360292
    - type: nauc_recall_at_5_max
      value: 38.177646107055516
    - type: nauc_recall_at_5_std
      value: 22.17196825834675
    - type: ndcg_at_1
      value: 46.71
    - type: ndcg_at_10
      value: 46.113
    - type: ndcg_at_100
      value: 53.035
    - type: ndcg_at_1000
      value: 55.724
    - type: ndcg_at_20
      value: 48.929
    - type: ndcg_at_3
      value: 39.501999999999995
    - type: ndcg_at_5
      value: 41.792
    - type: precision_at_1
      value: 46.71
    - type: precision_at_10
      value: 14.274000000000001
    - type: precision_at_100
      value: 2.1870000000000003
    - type: precision_at_1000
      value: 0.269
    - type: precision_at_20
      value: 8.375
    - type: precision_at_3
      value: 29.881
    - type: precision_at_5
      value: 22.697
    - type: recall_at_1
      value: 20.122999999999998
    - type: recall_at_10
      value: 52.22
    - type: recall_at_100
      value: 75.388
    - type: recall_at_1000
      value: 89.938
    - type: recall_at_20
      value: 60.077000000000005
    - type: recall_at_3
      value: 35.150999999999996
    - type: recall_at_5
      value: 42.748000000000005
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB DBPedia
      revision: c0f706b76e590d620bd6618b3ca8efdd34e2d659
      split: test
      type: mteb/dbpedia
    metrics:
    - type: main_score
      value: 52.276999999999994
    - type: map_at_1
      value: 9.949
    - type: map_at_10
      value: 24.891
    - type: map_at_100
      value: 37.111
    - type: map_at_1000
      value: 39.266
    - type: map_at_20
      value: 29.685
    - type: map_at_3
      value: 16.586000000000002
    - type: map_at_5
      value: 19.982
    - type: mrr_at_1
      value: 76.25
    - type: mrr_at_10
      value: 82.4518849206349
    - type: mrr_at_100
      value: 82.70302194564499
    - type: mrr_at_1000
      value: 82.70909729942254
    - type: mrr_at_20
      value: 82.60492765962964
    - type: mrr_at_3
      value: 81.33333333333331
    - type: mrr_at_5
      value: 82.14583333333331
    - type: nauc_map_at_1000_diff1
      value: 21.427201262456556
    - type: nauc_map_at_1000_max
      value: 35.357361590816076
    - type: nauc_map_at_1000_std
      value: 24.785419223353717
    - type: nauc_map_at_100_diff1
      value: 22.82358692021537
    - type: nauc_map_at_100_max
      value: 35.07399692072945
    - type: nauc_map_at_100_std
      value: 22.679878828987025
    - type: nauc_map_at_10_diff1
      value: 26.491769223479643
    - type: nauc_map_at_10_max
      value: 20.78079385443902
    - type: nauc_map_at_10_std
      value: -4.910406292079661
    - type: nauc_map_at_1_diff1
      value: 35.20851030208876
    - type: nauc_map_at_1_max
      value: 5.783003346365858
    - type: nauc_map_at_1_std
      value: -21.11679133835354
    - type: nauc_map_at_20_diff1
      value: 24.80097499300491
    - type: nauc_map_at_20_max
      value: 26.807021360774975
    - type: nauc_map_at_20_std
      value: 4.793103995429955
    - type: nauc_map_at_3_diff1
      value: 29.238193458890173
    - type: nauc_map_at_3_max
      value: 10.300839972189456
    - type: nauc_map_at_3_std
      value: -17.889666731981592
    - type: nauc_map_at_5_diff1
      value: 28.773624870573926
    - type: nauc_map_at_5_max
      value: 14.951435645422887
    - type: nauc_map_at_5_std
      value: -13.319697827173565
    - type: nauc_mrr_at_1000_diff1
      value: 55.232544856708785
    - type: nauc_mrr_at_1000_max
      value: 64.73225637682637
    - type: nauc_mrr_at_1000_std
      value: 37.57480399594188
    - type: nauc_mrr_at_100_diff1
      value: 55.219251601773735
    - type: nauc_mrr_at_100_max
      value: 64.73305063663611
    - type: nauc_mrr_at_100_std
      value: 37.56458562909293
    - type: nauc_mrr_at_10_diff1
      value: 55.123463838253464
    - type: nauc_mrr_at_10_max
      value: 64.91914041040233
    - type: nauc_mrr_at_10_std
      value: 37.76482503851598
    - type: nauc_mrr_at_1_diff1
      value: 56.45461238513347
    - type: nauc_mrr_at_1_max
      value: 63.11782510293676
    - type: nauc_mrr_at_1_std
      value: 33.592561284868985
    - type: nauc_mrr_at_20_diff1
      value: 55.15401961460458
    - type: nauc_mrr_at_20_max
      value: 64.77145835613156
    - type: nauc_mrr_at_20_std
      value: 37.471561418305804
    - type: nauc_mrr_at_3_diff1
      value: 54.64387438697658
    - type: nauc_mrr_at_3_max
      value: 64.27618995019164
    - type: nauc_mrr_at_3_std
      value: 39.391637295269014
    - type: nauc_mrr_at_5_diff1
      value: 55.08702591239485
    - type: nauc_mrr_at_5_max
      value: 64.6071475650635
    - type: nauc_mrr_at_5_std
      value: 37.97185134269896
    - type: nauc_ndcg_at_1000_diff1
      value: 31.696698876400387
    - type: nauc_ndcg_at_1000_max
      value: 52.12183760001191
    - type: nauc_ndcg_at_1000_std
      value: 40.197596211778716
    - type: nauc_ndcg_at_100_diff1
      value: 33.253120193433666
    - type: nauc_ndcg_at_100_max
      value: 49.47167758554746
    - type: nauc_ndcg_at_100_std
      value: 32.643833139756204
    - type: nauc_ndcg_at_10_diff1
      value: 27.065541392580013
    - type: nauc_ndcg_at_10_max
      value: 45.83504281289289
    - type: nauc_ndcg_at_10_std
      value: 27.11739500732328
    - type: nauc_ndcg_at_1_diff1
      value: 49.42808250022517
    - type: nauc_ndcg_at_1_max
      value: 53.502615048520354
    - type: nauc_ndcg_at_1_std
      value: 27.17555908836708
    - type: nauc_ndcg_at_20_diff1
      value: 29.374791382330308
    - type: nauc_ndcg_at_20_max
      value: 43.91246842479055
    - type: nauc_ndcg_at_20_std
      value: 23.419410620550316
    - type: nauc_ndcg_at_3_diff1
      value: 26.71550354496204
    - type: nauc_ndcg_at_3_max
      value: 43.9641457892003
    - type: nauc_ndcg_at_3_std
      value: 27.320024167947686
    - type: nauc_ndcg_at_5_diff1
      value: 27.020654974589487
    - type: nauc_ndcg_at_5_max
      value: 46.130417266030584
    - type: nauc_ndcg_at_5_std
      value: 28.392009019010068
    - type: nauc_precision_at_1000_diff1
      value: -21.47455482181002
    - type: nauc_precision_at_1000_max
      value: -9.721907229236024
    - type: nauc_precision_at_1000_std
      value: -1.061132062651487
    - type: nauc_precision_at_100_diff1
      value: -12.35759246101943
    - type: nauc_precision_at_100_max
      value: 15.509512444892168
    - type: nauc_precision_at_100_std
      value: 36.21183578592014
    - type: nauc_precision_at_10_diff1
      value: -6.136998947343125
    - type: nauc_precision_at_10_max
      value: 32.30037906748288
    - type: nauc_precision_at_10_std
      value: 41.4500302476981
    - type: nauc_precision_at_1_diff1
      value: 56.45461238513347
    - type: nauc_precision_at_1_max
      value: 63.11782510293676
    - type: nauc_precision_at_1_std
      value: 33.592561284868985
    - type: nauc_precision_at_20_diff1
      value: -7.335890123683174
    - type: nauc_precision_at_20_max
      value: 28.31417075291312
    - type: nauc_precision_at_20_std
      value: 41.405935715061815
    - type: nauc_precision_at_3_diff1
      value: 7.117255890225942
    - type: nauc_precision_at_3_max
      value: 39.19894132683829
    - type: nauc_precision_at_3_std
      value: 38.48255841994843
    - type: nauc_precision_at_5_diff1
      value: 1.861523090114206
    - type: nauc_precision_at_5_max
      value: 38.11649223007208
    - type: nauc_precision_at_5_std
      value: 40.52993530374645
    - type: nauc_recall_at_1000_diff1
      value: 26.497648584314636
    - type: nauc_recall_at_1000_max
      value: 44.48069746734414
    - type: nauc_recall_at_1000_std
      value: 53.16438130228715
    - type: nauc_recall_at_100_diff1
      value: 26.353456899511446
    - type: nauc_recall_at_100_max
      value: 37.57379787884197
    - type: nauc_recall_at_100_std
      value: 29.197468295989548
    - type: nauc_recall_at_10_diff1
      value: 22.80445738351114
    - type: nauc_recall_at_10_max
      value: 15.895630778449046
    - type: nauc_recall_at_10_std
      value: -8.746224797644501
    - type: nauc_recall_at_1_diff1
      value: 35.20851030208876
    - type: nauc_recall_at_1_max
      value: 5.783003346365858
    - type: nauc_recall_at_1_std
      value: -21.11679133835354
    - type: nauc_recall_at_20_diff1
      value: 22.34028867678706
    - type: nauc_recall_at_20_max
      value: 21.42373427646772
    - type: nauc_recall_at_20_std
      value: 0.4533036151015875
    - type: nauc_recall_at_3_diff1
      value: 24.96853445599229
    - type: nauc_recall_at_3_max
      value: 6.245185375804208
    - type: nauc_recall_at_3_std
      value: -20.200240127099622
    - type: nauc_recall_at_5_diff1
      value: 24.749259476710623
    - type: nauc_recall_at_5_max
      value: 11.024592845995942
    - type: nauc_recall_at_5_std
      value: -16.15683085641543
    - type: ndcg_at_1
      value: 64.125
    - type: ndcg_at_10
      value: 52.276999999999994
    - type: ndcg_at_100
      value: 57.440000000000005
    - type: ndcg_at_1000
      value: 64.082
    - type: ndcg_at_20
      value: 51.383
    - type: ndcg_at_3
      value: 55.769000000000005
    - type: ndcg_at_5
      value: 53.978
    - type: precision_at_1
      value: 76.25
    - type: precision_at_10
      value: 43.05
    - type: precision_at_100
      value: 14.09
    - type: precision_at_1000
      value: 2.662
    - type: precision_at_20
      value: 33.112
    - type: precision_at_3
      value: 59.833000000000006
    - type: precision_at_5
      value: 53.05
    - type: recall_at_1
      value: 9.949
    - type: recall_at_10
      value: 30.424
    - type: recall_at_100
      value: 64.062
    - type: recall_at_1000
      value: 85.916
    - type: recall_at_20
      value: 39.895
    - type: recall_at_3
      value: 17.876
    - type: recall_at_5
      value: 22.536
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB EmotionClassification
      revision: 4f58c6b202a23cf9a4da393831edf4f9183cad37
      split: test
      type: mteb/emotion
    metrics:
    - type: accuracy
      value: 84.29499999999999
    - type: f1
      value: 79.76188258172078
    - type: f1_weighted
      value: 84.96026012933847
    - type: main_score
      value: 84.29499999999999
    task:
      type: Classification
  - dataset:
      config: default
      name: MTEB FEVER
      revision: bea83ef9e8fb933d90a2f1d5515737465d613e12
      split: test
      type: mteb/fever
    metrics:
    - type: main_score
      value: 94.83200000000001
    - type: map_at_1
      value: 87.339
    - type: map_at_10
      value: 92.92099999999999
    - type: map_at_100
      value: 93.108
    - type: map_at_1000
      value: 93.116
    - type: map_at_20
      value: 93.041
    - type: map_at_3
      value: 92.219
    - type: map_at_5
      value: 92.664
    - type: mrr_at_1
      value: 93.99939993999399
    - type: mrr_at_10
      value: 96.55188137861403
    - type: mrr_at_100
      value: 96.5652366009286
    - type: mrr_at_1000
      value: 96.5652625550811
    - type: mrr_at_20
      value: 96.5601781754844
    - type: mrr_at_3
      value: 96.45714571457142
    - type: mrr_at_5
      value: 96.544904490449
    - type: nauc_map_at_1000_diff1
      value: 51.81676454961933
    - type: nauc_map_at_1000_max
      value: 24.904822914926118
    - type: nauc_map_at_1000_std
      value: -3.8110347821630404
    - type: nauc_map_at_100_diff1
      value: 51.77514975011158
    - type: nauc_map_at_100_max
      value: 24.912497341800094
    - type: nauc_map_at_100_std
      value: -3.76229517662447
    - type: nauc_map_at_10_diff1
      value: 51.29608296382479
    - type: nauc_map_at_10_max
      value: 24.78704970246707
    - type: nauc_map_at_10_std
      value: -3.723130815783328
    - type: nauc_map_at_1_diff1
      value: 59.90813138005125
    - type: nauc_map_at_1_max
      value: 24.58479295693794
    - type: nauc_map_at_1_std
      value: -8.056152492777027
    - type: nauc_map_at_20_diff1
      value: 51.428639331678326
    - type: nauc_map_at_20_max
      value: 24.849214517705086
    - type: nauc_map_at_20_std
      value: -3.685550123874596
    - type: nauc_map_at_3_diff1
      value: 50.94399923719279
    - type: nauc_map_at_3_max
      value: 24.359700180006207
    - type: nauc_map_at_3_std
      value: -5.407767408816422
    - type: nauc_map_at_5_diff1
      value: 50.767302682959546
    - type: nauc_map_at_5_max
      value: 24.491113461892215
    - type: nauc_map_at_5_std
      value: -4.058336127339082
    - type: nauc_mrr_at_1000_diff1
      value: 79.86042313551833
    - type: nauc_mrr_at_1000_max
      value: 23.20960445633933
    - type: nauc_mrr_at_1000_std
      value: -23.54334295120471
    - type: nauc_mrr_at_100_diff1
      value: 79.85991247027636
    - type: nauc_mrr_at_100_max
      value: 23.210085926780106
    - type: nauc_mrr_at_100_std
      value: -23.542508200789197
    - type: nauc_mrr_at_10_diff1
      value: 79.71095155563415
    - type: nauc_mrr_at_10_max
      value: 23.24128650883908
    - type: nauc_mrr_at_10_std
      value: -23.408502781834102
    - type: nauc_mrr_at_1_diff1
      value: 82.6349900233902
    - type: nauc_mrr_at_1_max
      value: 21.994548214014227
    - type: nauc_mrr_at_1_std
      value: -22.549769792179262
    - type: nauc_mrr_at_20_diff1
      value: 79.76465012873038
    - type: nauc_mrr_at_20_max
      value: 23.17575026523213
    - type: nauc_mrr_at_20_std
      value: -23.492660166315048
    - type: nauc_mrr_at_3_diff1
      value: 79.91074933379953
    - type: nauc_mrr_at_3_max
      value: 24.14246499097892
    - type: nauc_mrr_at_3_std
      value: -25.22601708389664
    - type: nauc_mrr_at_5_diff1
      value: 79.62092651565847
    - type: nauc_mrr_at_5_max
      value: 23.315937737034425
    - type: nauc_mrr_at_5_std
      value: -23.317659360058403
    - type: nauc_ndcg_at_1000_diff1
      value: 54.404537986779225
    - type: nauc_ndcg_at_1000_max
      value: 25.38408304128995
    - type: nauc_ndcg_at_1000_std
      value: -4.916709117696968
    - type: nauc_ndcg_at_100_diff1
      value: 53.2448598868241
    - type: nauc_ndcg_at_100_max
      value: 25.75325255295546
    - type: nauc_ndcg_at_100_std
      value: -3.680507005630751
    - type: nauc_ndcg_at_10_diff1
      value: 50.81057355170232
    - type: nauc_ndcg_at_10_max
      value: 25.006448273343807
    - type: nauc_ndcg_at_10_std
      value: -2.8979899112515577
    - type: nauc_ndcg_at_1_diff1
      value: 82.6349900233902
    - type: nauc_ndcg_at_1_max
      value: 21.994548214014227
    - type: nauc_ndcg_at_1_std
      value: -22.549769792179262
    - type: nauc_ndcg_at_20_diff1
      value: 51.205023097166304
    - type: nauc_ndcg_at_20_max
      value: 25.22133626556826
    - type: nauc_ndcg_at_20_std
      value: -2.9506328244150155
    - type: nauc_ndcg_at_3_diff1
      value: 51.79780256736321
    - type: nauc_ndcg_at_3_max
      value: 24.81137324438439
    - type: nauc_ndcg_at_3_std
      value: -6.881223858227807
    - type: nauc_ndcg_at_5_diff1
      value: 50.290038260564565
    - type: nauc_ndcg_at_5_max
      value: 24.57250792165796
    - type: nauc_ndcg_at_5_std
      value: -3.5124628344654596
    - type: nauc_precision_at_1000_diff1
      value: -20.215211396894333
    - type: nauc_precision_at_1000_max
      value: -14.165452298769171
    - type: nauc_precision_at_1000_std
      value: -2.0952871214470816
    - type: nauc_precision_at_100_diff1
      value: -22.340257474494607
    - type: nauc_precision_at_100_max
      value: -12.697885641360282
    - type: nauc_precision_at_100_std
      value: 1.0688624940286244
    - type: nauc_precision_at_10_diff1
      value: -24.78271817420798
    - type: nauc_precision_at_10_max
      value: -12.625257500222656
    - type: nauc_precision_at_10_std
      value: 3.223250450607087
    - type: nauc_precision_at_1_diff1
      value: 82.6349900233902
    - type: nauc_precision_at_1_max
      value: 21.994548214014227
    - type: nauc_precision_at_1_std
      value: -22.549769792179262
    - type: nauc_precision_at_20_diff1
      value: -24.375756227194177
    - type: nauc_precision_at_20_max
      value: -12.341015011563536
    - type: nauc_precision_at_20_std
      value: 2.7475274619387955
    - type: nauc_precision_at_3_diff1
      value: -24.8251306777365
    - type: nauc_precision_at_3_max
      value: -13.109579709589042
    - type: nauc_precision_at_3_std
      value: -1.2233442335420748
    - type: nauc_precision_at_5_diff1
      value: -26.955418583344894
    - type: nauc_precision_at_5_max
      value: -13.598630838071015
    - type: nauc_precision_at_5_std
      value: 2.545780631940738
    - type: nauc_recall_at_1000_diff1
      value: 0.2542680835344437
    - type: nauc_recall_at_1000_max
      value: 49.38194243035277
    - type: nauc_recall_at_1000_std
      value: 57.021502715846026
    - type: nauc_recall_at_100_diff1
      value: 5.062154815367015
    - type: nauc_recall_at_100_max
      value: 45.41178380188437
    - type: nauc_recall_at_100_std
      value: 50.78382225901813
    - type: nauc_recall_at_10_diff1
      value: 20.429153629007818
    - type: nauc_recall_at_10_max
      value: 27.516855026155508
    - type: nauc_recall_at_10_std
      value: 21.367491371755467
    - type: nauc_recall_at_1_diff1
      value: 59.90813138005125
    - type: nauc_recall_at_1_max
      value: 24.58479295693794
    - type: nauc_recall_at_1_std
      value: -8.056152492777027
    - type: nauc_recall_at_20_diff1
      value: 13.072430858896942
    - type: nauc_recall_at_20_max
      value: 29.5522659183247
    - type: nauc_recall_at_20_std
      value: 28.70569974090291
    - type: nauc_recall_at_3_diff1
      value: 30.419084482663617
    - type: nauc_recall_at_3_max
      value: 25.627389580252835
    - type: nauc_recall_at_3_std
      value: 2.5557690877637054
    - type: nauc_recall_at_5_diff1
      value: 22.92561435069869
    - type: nauc_recall_at_5_max
      value: 25.545265063475455
    - type: nauc_recall_at_5_std
      value: 14.736172663072786
    - type: ndcg_at_1
      value: 93.999
    - type: ndcg_at_10
      value: 94.83200000000001
    - type: ndcg_at_100
      value: 95.363
    - type: ndcg_at_1000
      value: 95.478
    - type: ndcg_at_20
      value: 95.077
    - type: ndcg_at_3
      value: 94.143
    - type: ndcg_at_5
      value: 94.525
    - type: precision_at_1
      value: 93.999
    - type: precision_at_10
      value: 11.029
    - type: precision_at_100
      value: 1.1560000000000001
    - type: precision_at_1000
      value: 0.11800000000000001
    - type: precision_at_20
      value: 5.62
    - type: precision_at_3
      value: 35.219
    - type: precision_at_5
      value: 21.584
    - type: recall_at_1
      value: 87.339
    - type: recall_at_10
      value: 97.026
    - type: recall_at_100
      value: 98.936
    - type: recall_at_1000
      value: 99.599
    - type: recall_at_20
      value: 97.744
    - type: recall_at_3
      value: 95.069
    - type: recall_at_5
      value: 96.177
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB FiQA2018
      revision: 27a168819829fe9bcd655c2df245fb19452e8e06
      split: test
      type: mteb/fiqa
    metrics:
    - type: main_score
      value: 60.480000000000004
    - type: map_at_1
      value: 31.529
    - type: map_at_10
      value: 52.081
    - type: map_at_100
      value: 54.342
    - type: map_at_1000
      value: 54.449000000000005
    - type: map_at_20
      value: 53.479
    - type: map_at_3
      value: 45.471000000000004
    - type: map_at_5
      value: 49.164
    - type: mrr_at_1
      value: 60.03086419753087
    - type: mrr_at_10
      value: 67.73754409171075
    - type: mrr_at_100
      value: 68.332432152368
    - type: mrr_at_1000
      value: 68.34150941774908
    - type: mrr_at_20
      value: 68.14780993838725
    - type: mrr_at_3
      value: 65.6378600823045
    - type: mrr_at_5
      value: 66.88014403292176
    - type: nauc_map_at_1000_diff1
      value: 45.36598134579052
    - type: nauc_map_at_1000_max
      value: 31.891451119906943
    - type: nauc_map_at_1000_std
      value: -15.41454384137943
    - type: nauc_map_at_100_diff1
      value: 45.31268291874018
    - type: nauc_map_at_100_max
      value: 31.811055683002092
    - type: nauc_map_at_100_std
      value: -15.348503855591417
    - type: nauc_map_at_10_diff1
      value: 45.22606983565892
    - type: nauc_map_at_10_max
      value: 30.46108534749699
    - type: nauc_map_at_10_std
      value: -16.618086029682555
    - type: nauc_map_at_1_diff1
      value: 49.94952823753276
    - type: nauc_map_at_1_max
      value: 13.770377574254548
    - type: nauc_map_at_1_std
      value: -14.946357968858653
    - type: nauc_map_at_20_diff1
      value: 45.29274207897926
    - type: nauc_map_at_20_max
      value: 31.27332015148257
    - type: nauc_map_at_20_std
      value: -15.782946115613129
    - type: nauc_map_at_3_diff1
      value: 47.94248233566038
    - type: nauc_map_at_3_max
      value: 24.022838776825456
    - type: nauc_map_at_3_std
      value: -17.103518542262208
    - type: nauc_map_at_5_diff1
      value: 45.85345590031722
    - type: nauc_map_at_5_max
      value: 27.78341379004547
    - type: nauc_map_at_5_std
      value: -17.490850791756326
    - type: nauc_mrr_at_1000_diff1
      value: 58.225141047822824
    - type: nauc_mrr_at_1000_max
      value: 43.39606904140525
    - type: nauc_mrr_at_1000_std
      value: -14.64093518199122
    - type: nauc_mrr_at_100_diff1
      value: 58.22137274179545
    - type: nauc_mrr_at_100_max
      value: 43.39567568136935
    - type: nauc_mrr_at_100_std
      value: -14.62512313985582
    - type: nauc_mrr_at_10_diff1
      value: 58.03217329957151
    - type: nauc_mrr_at_10_max
      value: 43.633561683075186
    - type: nauc_mrr_at_10_std
      value: -14.563703576023808
    - type: nauc_mrr_at_1_diff1
      value: 61.48979902647692
    - type: nauc_mrr_at_1_max
      value: 43.1938079066948
    - type: nauc_mrr_at_1_std
      value: -15.808138277440465
    - type: nauc_mrr_at_20_diff1
      value: 58.13185370150794
    - type: nauc_mrr_at_20_max
      value: 43.35607721183147
    - type: nauc_mrr_at_20_std
      value: -14.635812702971263
    - type: nauc_mrr_at_3_diff1
      value: 58.698963168321264
    - type: nauc_mrr_at_3_max
      value: 43.633129249785405
    - type: nauc_mrr_at_3_std
      value: -15.733246346983854
    - type: nauc_mrr_at_5_diff1
      value: 57.94156745229547
    - type: nauc_mrr_at_5_max
      value: 43.14152462640525
    - type: nauc_mrr_at_5_std
      value: -15.318685307750895
    - type: nauc_ndcg_at_1000_diff1
      value: 47.871896043731496
    - type: nauc_ndcg_at_1000_max
      value: 37.159845167533426
    - type: nauc_ndcg_at_1000_std
      value: -13.067288160833485
    - type: nauc_ndcg_at_100_diff1
      value: 47.046171407204426
    - type: nauc_ndcg_at_100_max
      value: 36.422514360855835
    - type: nauc_ndcg_at_100_std
      value: -11.636859259571441
    - type: nauc_ndcg_at_10_diff1
      value: 46.232628149078096
    - type: nauc_ndcg_at_10_max
      value: 34.82402625088358
    - type: nauc_ndcg_at_10_std
      value: -14.768545542980114
    - type: nauc_ndcg_at_1_diff1
      value: 61.48979902647692
    - type: nauc_ndcg_at_1_max
      value: 43.1938079066948
    - type: nauc_ndcg_at_1_std
      value: -15.808138277440465
    - type: nauc_ndcg_at_20_diff1
      value: 46.51116172390955
    - type: nauc_ndcg_at_20_max
      value: 35.36362650568298
    - type: nauc_ndcg_at_20_std
      value: -12.849406209182826
    - type: nauc_ndcg_at_3_diff1
      value: 47.39832263785871
    - type: nauc_ndcg_at_3_max
      value: 35.67466264628456
    - type: nauc_ndcg_at_3_std
      value: -17.257717349296943
    - type: nauc_ndcg_at_5_diff1
      value: 45.91049493804232
    - type: nauc_ndcg_at_5_max
      value: 33.8405091138445
    - type: nauc_ndcg_at_5_std
      value: -17.477069902735895
    - type: nauc_precision_at_1000_diff1
      value: -12.037873000917767
    - type: nauc_precision_at_1000_max
      value: 26.043220150002295
    - type: nauc_precision_at_1000_std
      value: 6.84910668321572
    - type: nauc_precision_at_100_diff1
      value: -9.383403459051864
    - type: nauc_precision_at_100_max
      value: 29.68713170610003
    - type: nauc_precision_at_100_std
      value: 10.079531587056152
    - type: nauc_precision_at_10_diff1
      value: 3.3433323353925135
    - type: nauc_precision_at_10_max
      value: 38.31790111725993
    - type: nauc_precision_at_10_std
      value: 0.7888123304710856
    - type: nauc_precision_at_1_diff1
      value: 61.48979902647692
    - type: nauc_precision_at_1_max
      value: 43.1938079066948
    - type: nauc_precision_at_1_std
      value: -15.808138277440465
    - type: nauc_precision_at_20_diff1
      value: -2.083500986294448
    - type: nauc_precision_at_20_max
      value: 35.77143835726343
    - type: nauc_precision_at_20_std
      value: 5.318547021874003
    - type: nauc_precision_at_3_diff1
      value: 23.335617788912586
    - type: nauc_precision_at_3_max
      value: 39.81973275320871
    - type: nauc_precision_at_3_std
      value: -8.442769390555561
    - type: nauc_precision_at_5_diff1
      value: 11.521087842589482
    - type: nauc_precision_at_5_max
      value: 39.527792539828255
    - type: nauc_precision_at_5_std
      value: -5.412729503701626
    - type: nauc_recall_at_1000_diff1
      value: 10.6830893047453
    - type: nauc_recall_at_1000_max
      value: 8.834504311238423
    - type: nauc_recall_at_1000_std
      value: 24.670754304859692
    - type: nauc_recall_at_100_diff1
      value: 20.646020385527358
    - type: nauc_recall_at_100_max
      value: 20.121595011523294
    - type: nauc_recall_at_100_std
      value: 19.42307459311791
    - type: nauc_recall_at_10_diff1
      value: 33.01029313733417
    - type: nauc_recall_at_10_max
      value: 27.948634980368702
    - type: nauc_recall_at_10_std
      value: -10.239767371462975
    - type: nauc_recall_at_1_diff1
      value: 49.94952823753276
    - type: nauc_recall_at_1_max
      value: 13.770377574254548
    - type: nauc_recall_at_1_std
      value: -14.946357968858653
    - type: nauc_recall_at_20_diff1
      value: 30.040111045267963
    - type: nauc_recall_at_20_max
      value: 25.984919302418184
    - type: nauc_recall_at_20_std
      value: -1.4998001817460804
    - type: nauc_recall_at_3_diff1
      value: 42.24410559113653
    - type: nauc_recall_at_3_max
      value: 20.269503583626914
    - type: nauc_recall_at_3_std
      value: -17.09578532600584
    - type: nauc_recall_at_5_diff1
      value: 36.124149735848945
    - type: nauc_recall_at_5_max
      value: 22.708022306002622
    - type: nauc_recall_at_5_std
      value: -16.966976847236193
    - type: ndcg_at_1
      value: 60.031
    - type: ndcg_at_10
      value: 60.480000000000004
    - type: ndcg_at_100
      value: 66.94099999999999
    - type: ndcg_at_1000
      value: 68.303
    - type: ndcg_at_20
      value: 63.536
    - type: ndcg_at_3
      value: 55.903999999999996
    - type: ndcg_at_5
      value: 57.387
    - type: precision_at_1
      value: 60.031
    - type: precision_at_10
      value: 16.682
    - type: precision_at_100
      value: 2.336
    - type: precision_at_1000
      value: 0.259
    - type: precision_at_20
      value: 9.66
    - type: precision_at_3
      value: 37.191
    - type: precision_at_5
      value: 27.253
    - type: recall_at_1
      value: 31.529
    - type: recall_at_10
      value: 68.035
    - type: recall_at_100
      value: 90.925
    - type: recall_at_1000
      value: 98.688
    - type: recall_at_20
      value: 77.453
    - type: recall_at_3
      value: 50.221000000000004
    - type: recall_at_5
      value: 58.209999999999994
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB HotpotQA
      revision: ab518f4d6fcca38d87c25209f94beba119d02014
      split: test
      type: mteb/hotpotqa
    metrics:
    - type: main_score
      value: 76.67399999999999
    - type: map_at_1
      value: 43.822
    - type: map_at_10
      value: 68.82000000000001
    - type: map_at_100
      value: 69.659
    - type: map_at_1000
      value: 69.714
    - type: map_at_20
      value: 69.305
    - type: map_at_3
      value: 65.517
    - type: map_at_5
      value: 67.633
    - type: mrr_at_1
      value: 87.643484132343
    - type: mrr_at_10
      value: 91.28134679485098
    - type: mrr_at_100
      value: 91.37985230614755
    - type: mrr_at_1000
      value: 91.38202467630681
    - type: mrr_at_20
      value: 91.34718855278429
    - type: mrr_at_3
      value: 90.75849651136599
    - type: mrr_at_5
      value: 91.10961062345235
    - type: nauc_map_at_1000_diff1
      value: 3.7670405082837477
    - type: nauc_map_at_1000_max
      value: 14.410594409695182
    - type: nauc_map_at_1000_std
      value: 7.94738583292685
    - type: nauc_map_at_100_diff1
      value: 3.738796209193936
    - type: nauc_map_at_100_max
      value: 14.408029101534694
    - type: nauc_map_at_100_std
      value: 7.979641077687816
    - type: nauc_map_at_10_diff1
      value: 3.334917978089454
    - type: nauc_map_at_10_max
      value: 13.975255289147748
    - type: nauc_map_at_10_std
      value: 7.491959628012161
    - type: nauc_map_at_1_diff1
      value: 75.35066482050009
    - type: nauc_map_at_1_max
      value: 53.573503488571475
    - type: nauc_map_at_1_std
      value: -6.542030594426993
    - type: nauc_map_at_20_diff1
      value: 3.5197129341582083
    - type: nauc_map_at_20_max
      value: 14.159880698006816
    - type: nauc_map_at_20_std
      value: 7.856574384998483
    - type: nauc_map_at_3_diff1
      value: 3.0992333232864064
    - type: nauc_map_at_3_max
      value: 12.513959281222112
    - type: nauc_map_at_3_std
      value: 4.352912866014865
    - type: nauc_map_at_5_diff1
      value: 3.0351688998572537
    - type: nauc_map_at_5_max
      value: 13.21599457624529
    - type: nauc_map_at_5_std
      value: 6.246882983214777
    - type: nauc_mrr_at_1000_diff1
      value: 75.23953736361132
    - type: nauc_mrr_at_1000_max
      value: 56.64260717262164
    - type: nauc_mrr_at_1000_std
      value: -4.865932053762276
    - type: nauc_mrr_at_100_diff1
      value: 75.24091372816497
    - type: nauc_mrr_at_100_max
      value: 56.64831104504846
    - type: nauc_mrr_at_100_std
      value: -4.850966297943324
    - type: nauc_mrr_at_10_diff1
      value: 75.26540178053416
    - type: nauc_mrr_at_10_max
      value: 56.828755673428965
    - type: nauc_mrr_at_10_std
      value: -4.8401126970944635
    - type: nauc_mrr_at_1_diff1
      value: 75.35066482050009
    - type: nauc_mrr_at_1_max
      value: 53.573503488571475
    - type: nauc_mrr_at_1_std
      value: -6.542030594426993
    - type: nauc_mrr_at_20_diff1
      value: 75.24453050729845
    - type: nauc_mrr_at_20_max
      value: 56.69220588401435
    - type: nauc_mrr_at_20_std
      value: -4.843700730832108
    - type: nauc_mrr_at_3_diff1
      value: 74.98411648336175
    - type: nauc_mrr_at_3_max
      value: 56.766537573537114
    - type: nauc_mrr_at_3_std
      value: -4.909712671649337
    - type: nauc_mrr_at_5_diff1
      value: 75.20599020991028
    - type: nauc_mrr_at_5_max
      value: 56.64236207782237
    - type: nauc_mrr_at_5_std
      value: -5.208907367513977
    - type: nauc_ndcg_at_1000_diff1
      value: 11.48307079099774
    - type: nauc_ndcg_at_1000_max
      value: 20.893326881675176
    - type: nauc_ndcg_at_1000_std
      value: 10.43489838692119
    - type: nauc_ndcg_at_100_diff1
      value: 10.395588735754927
    - type: nauc_ndcg_at_100_max
      value: 20.529573302516912
    - type: nauc_ndcg_at_100_std
      value: 11.252973083654268
    - type: nauc_ndcg_at_10_diff1
      value: 8.596739352741972
    - type: nauc_ndcg_at_10_max
      value: 18.475863682540673
    - type: nauc_ndcg_at_10_std
      value: 9.175831033463352
    - type: nauc_ndcg_at_1_diff1
      value: 75.35066482050009
    - type: nauc_ndcg_at_1_max
      value: 53.573503488571475
    - type: nauc_ndcg_at_1_std
      value: -6.542030594426993
    - type: nauc_ndcg_at_20_diff1
      value: 8.998033972471749
    - type: nauc_ndcg_at_20_max
      value: 18.892085875404522
    - type: nauc_ndcg_at_20_std
      value: 10.3241608901084
    - type: nauc_ndcg_at_3_diff1
      value: 8.796384949533579
    - type: nauc_ndcg_at_3_max
      value: 16.515261419885274
    - type: nauc_ndcg_at_3_std
      value: 4.081902976576701
    - type: nauc_ndcg_at_5_diff1
      value: 8.277259464605025
    - type: nauc_ndcg_at_5_max
      value: 17.163053202909527
    - type: nauc_ndcg_at_5_std
      value: 6.652669449704474
    - type: nauc_precision_at_1000_diff1
      value: -3.490556596304827
    - type: nauc_precision_at_1000_max
      value: 31.0473259001597
    - type: nauc_precision_at_1000_std
      value: 52.36921397692622
    - type: nauc_precision_at_100_diff1
      value: -6.420747959222489
    - type: nauc_precision_at_100_max
      value: 20.555887056005936
    - type: nauc_precision_at_100_std
      value: 36.119132870798495
    - type: nauc_precision_at_10_diff1
      value: -6.461726057290426
    - type: nauc_precision_at_10_max
      value: 12.161081825341915
    - type: nauc_precision_at_10_std
      value: 17.961318451839993
    - type: nauc_precision_at_1_diff1
      value: 75.35066482050009
    - type: nauc_precision_at_1_max
      value: 53.573503488571475
    - type: nauc_precision_at_1_std
      value: -6.542030594426993
    - type: nauc_precision_at_20_diff1
      value: -7.361461296416161
    - type: nauc_precision_at_20_max
      value: 12.663621261696733
    - type: nauc_precision_at_20_std
      value: 23.312476851670286
    - type: nauc_precision_at_3_diff1
      value: -3.299056912774522
    - type: nauc_precision_at_3_max
      value: 9.85602375812038
    - type: nauc_precision_at_3_std
      value: 6.4962782003155475
    - type: nauc_precision_at_5_diff1
      value: -5.3155827772027795
    - type: nauc_precision_at_5_max
      value: 10.32907751171833
    - type: nauc_precision_at_5_std
      value: 11.384098087196932
    - type: nauc_recall_at_1000_diff1
      value: -3.4905565963043332
    - type: nauc_recall_at_1000_max
      value: 31.04732590016041
    - type: nauc_recall_at_1000_std
      value: 52.36921397692641
    - type: nauc_recall_at_100_diff1
      value: -6.420747959222586
    - type: nauc_recall_at_100_max
      value: 20.55588705600596
    - type: nauc_recall_at_100_std
      value: 36.11913287079825
    - type: nauc_recall_at_10_diff1
      value: -6.461726057290347
    - type: nauc_recall_at_10_max
      value: 12.161081825342022
    - type: nauc_recall_at_10_std
      value: 17.96131845184002
    - type: nauc_recall_at_1_diff1
      value: 75.35066482050009
    - type: nauc_recall_at_1_max
      value: 53.573503488571475
    - type: nauc_recall_at_1_std
      value: -6.542030594426993
    - type: nauc_recall_at_20_diff1
      value: -7.361461296416054
    - type: nauc_recall_at_20_max
      value: 12.66362126169679
    - type: nauc_recall_at_20_std
      value: 23.312476851670382
    - type: nauc_recall_at_3_diff1
      value: -3.2990569127745886
    - type: nauc_recall_at_3_max
      value: 9.856023758120296
    - type: nauc_recall_at_3_std
      value: 6.496278200315444
    - type: nauc_recall_at_5_diff1
      value: -5.315582777202729
    - type: nauc_recall_at_5_max
      value: 10.329077511718229
    - type: nauc_recall_at_5_std
      value: 11.384098087196932
    - type: ndcg_at_1
      value: 87.643
    - type: ndcg_at_10
      value: 76.67399999999999
    - type: ndcg_at_100
      value: 79.462
    - type: ndcg_at_1000
      value: 80.43599999999999
    - type: ndcg_at_20
      value: 77.83
    - type: ndcg_at_3
      value: 72.256
    - type: ndcg_at_5
      value: 74.789
    - type: precision_at_1
      value: 87.643
    - type: precision_at_10
      value: 15.726999999999999
    - type: precision_at_100
      value: 1.791
    - type: precision_at_1000
      value: 0.192
    - type: precision_at_20
      value: 8.236
    - type: precision_at_3
      value: 45.919
    - type: precision_at_5
      value: 29.558
    - type: recall_at_1
      value: 43.822
    - type: recall_at_10
      value: 78.636
    - type: recall_at_100
      value: 89.527
    - type: recall_at_1000
      value: 95.868
    - type: recall_at_20
      value: 82.363
    - type: recall_at_3
      value: 68.879
    - type: recall_at_5
      value: 73.896
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB ImdbClassification
      revision: 3d86128a09e091d6018b6d26cad27f2739fc2db7
      split: test
      type: mteb/imdb
    metrics:
    - type: accuracy
      value: 96.6608
    - type: ap
      value: 95.14657820401189
    - type: ap_weighted
      value: 95.14657820401189
    - type: f1
      value: 96.66029695623422
    - type: f1_weighted
      value: 96.66029695623423
    - type: main_score
      value: 96.6608
    task:
      type: Classification
  - dataset:
      config: default
      name: MTEB MSMARCO
      revision: c5a29a104738b98a9e76336939199e264163d4a0
      split: dev
      type: mteb/msmarco
    metrics:
    - type: main_score
      value: 45.217
    - type: map_at_1
      value: 24.728
    - type: map_at_10
      value: 37.933
    - type: map_at_100
      value: 39.074999999999996
    - type: map_at_1000
      value: 39.115
    - type: map_at_20
      value: 38.663
    - type: map_at_3
      value: 33.904
    - type: map_at_5
      value: 36.217
    - type: mrr_at_1
      value: 25.44412607449857
    - type: mrr_at_10
      value: 38.52640196479737
    - type: mrr_at_100
      value: 39.60462889736067
    - type: mrr_at_1000
      value: 39.638904296248526
    - type: mrr_at_20
      value: 39.2234365827559
    - type: mrr_at_3
      value: 34.59646609360076
    - type: mrr_at_5
      value: 36.8801337153773
    - type: nauc_map_at_1000_diff1
      value: 37.645652178132174
    - type: nauc_map_at_1000_max
      value: 9.953357023361367
    - type: nauc_map_at_1000_std
      value: -20.800238036721503
    - type: nauc_map_at_100_diff1
      value: 37.643073495974555
    - type: nauc_map_at_100_max
      value: 9.95921239641703
    - type: nauc_map_at_100_std
      value: -20.76517765535793
    - type: nauc_map_at_10_diff1
      value: 37.44380763335014
    - type: nauc_map_at_10_max
      value: 9.917273043055342
    - type: nauc_map_at_10_std
      value: -21.467951225710898
    - type: nauc_map_at_1_diff1
      value: 41.02118887981969
    - type: nauc_map_at_1_max
      value: 8.301113449711778
    - type: nauc_map_at_1_std
      value: -19.436814224415027
    - type: nauc_map_at_20_diff1
      value: 37.58156586490493
    - type: nauc_map_at_20_max
      value: 9.972927967610659
    - type: nauc_map_at_20_std
      value: -20.951374218839387
    - type: nauc_map_at_3_diff1
      value: 37.67246795684178
    - type: nauc_map_at_3_max
      value: 9.307031378909478
    - type: nauc_map_at_3_std
      value: -21.77026217965021
    - type: nauc_map_at_5_diff1
      value: 37.39086482095963
    - type: nauc_map_at_5_max
      value: 9.732739107368566
    - type: nauc_map_at_5_std
      value: -21.8424296893692
    - type: nauc_mrr_at_1000_diff1
      value: 37.36666719603192
    - type: nauc_mrr_at_1000_max
      value: 9.79040465289953
    - type: nauc_mrr_at_1000_std
      value: -20.590147245965568
    - type: nauc_mrr_at_100_diff1
      value: 37.36560296629318
    - type: nauc_mrr_at_100_max
      value: 9.798113710672162
    - type: nauc_mrr_at_100_std
      value: -20.556791838504292
    - type: nauc_mrr_at_10_diff1
      value: 37.19257605840734
    - type: nauc_mrr_at_10_max
      value: 9.749429811638063
    - type: nauc_mrr_at_10_std
      value: -21.206407664327276
    - type: nauc_mrr_at_1_diff1
      value: 40.98478651095172
    - type: nauc_mrr_at_1_max
      value: 8.173841799119707
    - type: nauc_mrr_at_1_std
      value: -19.530027987868017
    - type: nauc_mrr_at_20_diff1
      value: 37.29973172861245
    - type: nauc_mrr_at_20_max
      value: 9.815127660001345
    - type: nauc_mrr_at_20_std
      value: -20.700860112175928
    - type: nauc_mrr_at_3_diff1
      value: 37.282848009425734
    - type: nauc_mrr_at_3_max
      value: 9.172741713108193
    - type: nauc_mrr_at_3_std
      value: -21.563630513502996
    - type: nauc_mrr_at_5_diff1
      value: 37.08609827303586
    - type: nauc_mrr_at_5_max
      value: 9.604643424273284
    - type: nauc_mrr_at_5_std
      value: -21.580110806494094
    - type: nauc_ndcg_at_1000_diff1
      value: 37.086587020218545
    - type: nauc_ndcg_at_1000_max
      value: 10.696860688467472
    - type: nauc_ndcg_at_1000_std
      value: -19.50989939916873
    - type: nauc_ndcg_at_100_diff1
      value: 37.03794531268128
    - type: nauc_ndcg_at_100_max
      value: 10.940820719182339
    - type: nauc_ndcg_at_100_std
      value: -18.28651832370893
    - type: nauc_ndcg_at_10_diff1
      value: 36.21062857920633
    - type: nauc_ndcg_at_10_max
      value: 10.845172882571733
    - type: nauc_ndcg_at_10_std
      value: -21.454301679510106
    - type: nauc_ndcg_at_1_diff1
      value: 40.98478651095172
    - type: nauc_ndcg_at_1_max
      value: 8.173841799119707
    - type: nauc_ndcg_at_1_std
      value: -19.530027987868017
    - type: nauc_ndcg_at_20_diff1
      value: 36.583262733100526
    - type: nauc_ndcg_at_20_max
      value: 11.10492720898974
    - type: nauc_ndcg_at_20_std
      value: -19.41753284137609
    - type: nauc_ndcg_at_3_diff1
      value: 36.57271365035382
    - type: nauc_ndcg_at_3_max
      value: 9.56073433062999
    - type: nauc_ndcg_at_3_std
      value: -22.324263670932915
    - type: nauc_ndcg_at_5_diff1
      value: 36.09419372820154
    - type: nauc_ndcg_at_5_max
      value: 10.357384992631271
    - type: nauc_ndcg_at_5_std
      value: -22.389578276324894
    - type: nauc_precision_at_1000_diff1
      value: -2.7435338714030597
    - type: nauc_precision_at_1000_max
      value: 4.302274933383809
    - type: nauc_precision_at_1000_std
      value: 8.456846348638948
    - type: nauc_precision_at_100_diff1
      value: 15.149466332615983
    - type: nauc_precision_at_100_max
      value: 12.501013731673163
    - type: nauc_precision_at_100_std
      value: 15.909667509021785
    - type: nauc_precision_at_10_diff1
      value: 28.699788688314214
    - type: nauc_precision_at_10_max
      value: 13.024586051842347
    - type: nauc_precision_at_10_std
      value: -19.197658937078703
    - type: nauc_precision_at_1_diff1
      value: 40.98478651095172
    - type: nauc_precision_at_1_max
      value: 8.173841799119707
    - type: nauc_precision_at_1_std
      value: -19.530027987868017
    - type: nauc_precision_at_20_diff1
      value: 26.519292942353395
    - type: nauc_precision_at_20_max
      value: 14.389979272056438
    - type: nauc_precision_at_20_std
      value: -7.030956994938155
    - type: nauc_precision_at_3_diff1
      value: 32.87913492278213
    - type: nauc_precision_at_3_max
      value: 9.673660161387776
    - type: nauc_precision_at_3_std
      value: -23.905612656592172
    - type: nauc_precision_at_5_diff1
      value: 30.903850113238597
    - type: nauc_precision_at_5_max
      value: 11.482375434154898
    - type: nauc_precision_at_5_std
      value: -23.828657095254247
    - type: nauc_recall_at_1000_diff1
      value: 35.80765639589219
    - type: nauc_recall_at_1000_max
      value: 50.94532805969448
    - type: nauc_recall_at_1000_std
      value: 66.79910877083275
    - type: nauc_recall_at_100_diff1
      value: 34.96182828311028
    - type: nauc_recall_at_100_max
      value: 21.729699631790556
    - type: nauc_recall_at_100_std
      value: 23.509439011686474
    - type: nauc_recall_at_10_diff1
      value: 31.88371369567137
    - type: nauc_recall_at_10_max
      value: 14.425389702697073
    - type: nauc_recall_at_10_std
      value: -20.95578001880924
    - type: nauc_recall_at_1_diff1
      value: 41.02118887981969
    - type: nauc_recall_at_1_max
      value: 8.301113449711778
    - type: nauc_recall_at_1_std
      value: -19.436814224415027
    - type: nauc_recall_at_20_diff1
      value: 32.42718780622455
    - type: nauc_recall_at_20_max
      value: 16.90686126329399
    - type: nauc_recall_at_20_std
      value: -9.38158227016737
    - type: nauc_recall_at_3_diff1
      value: 33.68966646043966
    - type: nauc_recall_at_3_max
      value: 10.336277419708532
    - type: nauc_recall_at_3_std
      value: -23.80165869168538
    - type: nauc_recall_at_5_diff1
      value: 32.26258807452426
    - type: nauc_recall_at_5_max
      value: 12.303713005399935
    - type: nauc_recall_at_5_std
      value: -23.87721891164968
    - type: ndcg_at_1
      value: 25.444
    - type: ndcg_at_10
      value: 45.217
    - type: ndcg_at_100
      value: 50.575
    - type: ndcg_at_1000
      value: 51.519999999999996
    - type: ndcg_at_20
      value: 47.786
    - type: ndcg_at_3
      value: 37.067
    - type: ndcg_at_5
      value: 41.184
    - type: precision_at_1
      value: 25.444
    - type: precision_at_10
      value: 7.07
    - type: precision_at_100
      value: 0.9730000000000001
    - type: precision_at_1000
      value: 0.106
    - type: precision_at_20
      value: 4.072
    - type: precision_at_3
      value: 15.754999999999999
    - type: precision_at_5
      value: 11.544
    - type: recall_at_1
      value: 24.728
    - type: recall_at_10
      value: 67.607
    - type: recall_at_100
      value: 92.094
    - type: recall_at_1000
      value: 99.165
    - type: recall_at_20
      value: 77.529
    - type: recall_at_3
      value: 45.535
    - type: recall_at_5
      value: 55.394
    task:
      type: Retrieval
  - dataset:
      config: en
      name: MTEB MTOPDomainClassification (en)
      revision: d80d48c1eb48d3562165c59d59d0034df9fff0bf
      split: test
      type: mteb/mtop_domain
    metrics:
    - type: accuracy
      value: 99.01276789785682
    - type: f1
      value: 98.9288649250924
    - type: f1_weighted
      value: 99.01406884928141
    - type: main_score
      value: 99.01276789785682
    task:
      type: Classification
  - dataset:
      config: en
      name: MTEB MTOPIntentClassification (en)
      revision: ae001d0e6b1228650b7bd1c2c65fb50ad11a8aba
      split: test
      type: mteb/mtop_intent
    metrics:
    - type: accuracy
      value: 92.78385772913816
    - type: f1
      value: 79.78115704297824
    - type: f1_weighted
      value: 93.90424147486428
    - type: main_score
      value: 92.78385772913816
    task:
      type: Classification
  - dataset:
      config: en
      name: MTEB MassiveIntentClassification (en)
      revision: 4672e20407010da34463acc759c162ca9734bca6
      split: test
      type: mteb/amazon_massive_intent
    metrics:
    - type: accuracy
      value: 85.83053127101546
    - type: f1
      value: 82.72036139888232
    - type: f1_weighted
      value: 85.81759723866098
    - type: main_score
      value: 85.83053127101546
    task:
      type: Classification
  - dataset:
      config: en
      name: MTEB MassiveIntentClassification (en)
      revision: 4672e20407010da34463acc759c162ca9734bca6
      split: validation
      type: mteb/amazon_massive_intent
    metrics:
    - type: accuracy
      value: 86.41416625676341
    - type: f1
      value: 83.89525778024213
    - type: f1_weighted
      value: 86.17934075018363
    - type: main_score
      value: 86.41416625676341
    task:
      type: Classification
  - dataset:
      config: en
      name: MTEB MassiveScenarioClassification (en)
      revision: fad2c6e8459f9e1c45d9315f4953d921437d70f8
      split: test
      type: mteb/amazon_massive_scenario
    metrics:
    - type: accuracy
      value: 90.19838601210489
    - type: f1
      value: 89.55260197964978
    - type: f1_weighted
      value: 90.11422965504119
    - type: main_score
      value: 90.19838601210489
    task:
      type: Classification
  - dataset:
      config: en
      name: MTEB MassiveScenarioClassification (en)
      revision: fad2c6e8459f9e1c45d9315f4953d921437d70f8
      split: validation
      type: mteb/amazon_massive_scenario
    metrics:
    - type: accuracy
      value: 89.89178553861288
    - type: f1
      value: 89.15362501094349
    - type: f1_weighted
      value: 89.78021435879828
    - type: main_score
      value: 89.89178553861288
    task:
      type: Classification
  - dataset:
      config: default
      name: MTEB MedrxivClusteringP2P
      revision: e7a26af6f3ae46b30dde8737f02c07b1505bcc73
      split: test
      type: mteb/medrxiv-clustering-p2p
    metrics:
    - type: main_score
      value: 46.866746897607094
    - type: v_measure
      value: 46.866746897607094
    - type: v_measure_std
      value: 1.0966477896919726
    task:
      type: Clustering
  - dataset:
      config: default
      name: MTEB MedrxivClusteringS2S
      revision: 35191c8c0dca72d8ff3efcd72aa802307d469663
      split: test
      type: mteb/medrxiv-clustering-s2s
    metrics:
    - type: main_score
      value: 44.6538827415503
    - type: v_measure
      value: 44.6538827415503
    - type: v_measure_std
      value: 1.1649569936599116
    task:
      type: Clustering
  - dataset:
      config: default
      name: MTEB MindSmallReranking
      revision: 59042f120c80e8afa9cdbb224f67076cec0fc9a7
      split: test
      type: mteb/mind_small
    metrics:
    - type: main_score
      value: 33.05449204940555
    - type: map
      value: 33.05449204940555
    - type: mrr
      value: 34.32562058439585
    - type: nAUC_map_diff1
      value: 11.465656013162807
    - type: nAUC_map_max
      value: -20.400088169502308
    - type: nAUC_map_std
      value: -2.638964886362445
    - type: nAUC_mrr_diff1
      value: 10.644290702481207
    - type: nAUC_mrr_max
      value: -15.304687384645769
    - type: nAUC_mrr_std
      value: -0.519919931348978
    task:
      type: Reranking
  - dataset:
      config: default
      name: MTEB NFCorpus
      revision: ec0fa4fe99da2ff19ca1214b7966684033a58814
      split: test
      type: mteb/nfcorpus
    metrics:
    - type: main_score
      value: 41.998000000000005
    - type: map_at_1
      value: 6.907000000000001
    - type: map_at_10
      value: 16.397000000000002
    - type: map_at_100
      value: 21.69
    - type: map_at_1000
      value: 23.652
    - type: map_at_20
      value: 18.629
    - type: map_at_3
      value: 11.969000000000001
    - type: map_at_5
      value: 13.894
    - type: mrr_at_1
      value: 53.25077399380805
    - type: mrr_at_10
      value: 61.8561108653988
    - type: mrr_at_100
      value: 62.42447851935404
    - type: mrr_at_1000
      value: 62.459626424428095
    - type: mrr_at_20
      value: 62.287236389990696
    - type: mrr_at_3
      value: 60.42311661506711
    - type: mrr_at_5
      value: 61.36738906088753
    - type: nauc_map_at_1000_diff1
      value: 17.159461939643844
    - type: nauc_map_at_1000_max
      value: 32.42764938789903
    - type: nauc_map_at_1000_std
      value: 11.039427848422093
    - type: nauc_map_at_100_diff1
      value: 19.089532984187503
    - type: nauc_map_at_100_max
      value: 31.96721085058713
    - type: nauc_map_at_100_std
      value: 6.947468655726444
    - type: nauc_map_at_10_diff1
      value: 25.77255342629802
    - type: nauc_map_at_10_max
      value: 26.163590320961543
    - type: nauc_map_at_10_std
      value: -5.2588093720998375
    - type: nauc_map_at_1_diff1
      value: 46.31602607957798
    - type: nauc_map_at_1_max
      value: 11.807757660801942
    - type: nauc_map_at_1_std
      value: -13.984889089354317
    - type: nauc_map_at_20_diff1
      value: 22.308161130465365
    - type: nauc_map_at_20_max
      value: 29.070587307827722
    - type: nauc_map_at_20_std
      value: -1.0103056620851558
    - type: nauc_map_at_3_diff1
      value: 33.580827849617506
    - type: nauc_map_at_3_max
      value: 17.661630885799042
    - type: nauc_map_at_3_std
      value: -11.463282544041888
    - type: nauc_map_at_5_diff1
      value: 30.32603342696912
    - type: nauc_map_at_5_max
      value: 20.938905485667245
    - type: nauc_map_at_5_std
      value: -10.537086968155755
    - type: nauc_mrr_at_1000_diff1
      value: 24.45065397805829
    - type: nauc_mrr_at_1000_max
      value: 48.17519860927417
    - type: nauc_mrr_at_1000_std
      value: 30.350767549118903
    - type: nauc_mrr_at_100_diff1
      value: 24.444061606534486
    - type: nauc_mrr_at_100_max
      value: 48.1922894212229
    - type: nauc_mrr_at_100_std
      value: 30.379257816584094
    - type: nauc_mrr_at_10_diff1
      value: 24.25598717198779
    - type: nauc_mrr_at_10_max
      value: 48.10437607774264
    - type: nauc_mrr_at_10_std
      value: 30.090202482685996
    - type: nauc_mrr_at_1_diff1
      value: 26.907595285201264
    - type: nauc_mrr_at_1_max
      value: 44.006974050369955
    - type: nauc_mrr_at_1_std
      value: 26.921001962861062
    - type: nauc_mrr_at_20_diff1
      value: 24.462771570553738
    - type: nauc_mrr_at_20_max
      value: 48.264688196799746
    - type: nauc_mrr_at_20_std
      value: 30.498095141265914
    - type: nauc_mrr_at_3_diff1
      value: 24.76829388237229
    - type: nauc_mrr_at_3_max
      value: 48.213758704739924
    - type: nauc_mrr_at_3_std
      value: 30.1502853918892
    - type: nauc_mrr_at_5_diff1
      value: 24.476494932330247
    - type: nauc_mrr_at_5_max
      value: 47.977250552198804
    - type: nauc_mrr_at_5_std
      value: 29.65248143104835
    - type: nauc_ndcg_at_1000_diff1
      value: 13.055818920426246
    - type: nauc_ndcg_at_1000_max
      value: 46.00986444256306
    - type: nauc_ndcg_at_1000_std
      value: 29.622662054922085
    - type: nauc_ndcg_at_100_diff1
      value: 12.260551238228816
    - type: nauc_ndcg_at_100_max
      value: 39.89783048267698
    - type: nauc_ndcg_at_100_std
      value: 23.806961617956613
    - type: nauc_ndcg_at_10_diff1
      value: 11.002915931619567
    - type: nauc_ndcg_at_10_max
      value: 39.79323759244374
    - type: nauc_ndcg_at_10_std
      value: 23.053072152911046
    - type: nauc_ndcg_at_1_diff1
      value: 27.560910719974434
    - type: nauc_ndcg_at_1_max
      value: 41.21084046258119
    - type: nauc_ndcg_at_1_std
      value: 26.112891742912893
    - type: nauc_ndcg_at_20_diff1
      value: 10.085854089024496
    - type: nauc_ndcg_at_20_max
      value: 37.88629173784684
    - type: nauc_ndcg_at_20_std
      value: 23.17664322248358
    - type: nauc_ndcg_at_3_diff1
      value: 16.58969583405987
    - type: nauc_ndcg_at_3_max
      value: 41.282222954101435
    - type: nauc_ndcg_at_3_std
      value: 21.080670648392747
    - type: nauc_ndcg_at_5_diff1
      value: 13.893127947909885
    - type: nauc_ndcg_at_5_max
      value: 40.21188015992804
    - type: nauc_ndcg_at_5_std
      value: 21.417443978842652
    - type: nauc_precision_at_1000_diff1
      value: -17.227504530334564
    - type: nauc_precision_at_1000_max
      value: 3.798554468439066
    - type: nauc_precision_at_1000_std
      value: 35.73617809452683
    - type: nauc_precision_at_100_diff1
      value: -17.63388230218776
    - type: nauc_precision_at_100_max
      value: 15.079399882407094
    - type: nauc_precision_at_100_std
      value: 41.83698491321226
    - type: nauc_precision_at_10_diff1
      value: -11.850925959645156
    - type: nauc_precision_at_10_max
      value: 35.93283968364352
    - type: nauc_precision_at_10_std
      value: 34.391271855921296
    - type: nauc_precision_at_1_diff1
      value: 27.730860778824823
    - type: nauc_precision_at_1_max
      value: 43.97462471516834
    - type: nauc_precision_at_1_std
      value: 27.491068270978896
    - type: nauc_precision_at_20_diff1
      value: -14.281328840943347
    - type: nauc_precision_at_20_max
      value: 29.469099781759006
    - type: nauc_precision_at_20_std
      value: 38.54703022340941
    - type: nauc_precision_at_3_diff1
      value: 3.486986910413196
    - type: nauc_precision_at_3_max
      value: 41.21107780473768
    - type: nauc_precision_at_3_std
      value: 24.057479124531216
    - type: nauc_precision_at_5_diff1
      value: -3.0623787872866233
    - type: nauc_precision_at_5_max
      value: 37.49266386466702
    - type: nauc_precision_at_5_std
      value: 26.894454268004935
    - type: nauc_recall_at_1000_diff1
      value: -2.446891864334283
    - type: nauc_recall_at_1000_max
      value: 23.867293584643377
    - type: nauc_recall_at_1000_std
      value: 16.34707128224595
    - type: nauc_recall_at_100_diff1
      value: 4.891133690841179
    - type: nauc_recall_at_100_max
      value: 24.56727964996522
    - type: nauc_recall_at_100_std
      value: 9.847212953200797
    - type: nauc_recall_at_10_diff1
      value: 19.211912363585288
    - type: nauc_recall_at_10_max
      value: 24.825344777920737
    - type: nauc_recall_at_10_std
      value: -5.447989195041898
    - type: nauc_recall_at_1_diff1
      value: 46.31602607957798
    - type: nauc_recall_at_1_max
      value: 11.807757660801942
    - type: nauc_recall_at_1_std
      value: -13.984889089354317
    - type: nauc_recall_at_20_diff1
      value: 12.233372054304805
    - type: nauc_recall_at_20_max
      value: 22.284108685207148
    - type: nauc_recall_at_20_std
      value: -4.317138366746209
    - type: nauc_recall_at_3_diff1
      value: 28.394631527225815
    - type: nauc_recall_at_3_max
      value: 15.593864852625462
    - type: nauc_recall_at_3_std
      value: -12.383531804314593
    - type: nauc_recall_at_5_diff1
      value: 24.457441304950343
    - type: nauc_recall_at_5_max
      value: 19.080049396281623
    - type: nauc_recall_at_5_std
      value: -11.879747703626627
    - type: ndcg_at_1
      value: 51.548
    - type: ndcg_at_10
      value: 41.998000000000005
    - type: ndcg_at_100
      value: 39.626
    - type: ndcg_at_1000
      value: 48.707
    - type: ndcg_at_20
      value: 40.181
    - type: ndcg_at_3
      value: 48.06
    - type: ndcg_at_5
      value: 45.829
    - type: precision_at_1
      value: 52.941
    - type: precision_at_10
      value: 31.330999999999996
    - type: precision_at_100
      value: 10.421
    - type: precision_at_1000
      value: 2.428
    - type: precision_at_20
      value: 24.118000000000002
    - type: precision_at_3
      value: 45.408
    - type: precision_at_5
      value: 39.938
    - type: recall_at_1
      value: 6.907000000000001
    - type: recall_at_10
      value: 20.51
    - type: recall_at_100
      value: 40.857
    - type: recall_at_1000
      value: 73.616
    - type: recall_at_20
      value: 26.52
    - type: recall_at_3
      value: 13.267999999999999
    - type: recall_at_5
      value: 16.141
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB NQ
      revision: b774495ed302d8c44a3a7ea25c90dbce03968f31
      split: test
      type: mteb/nq
    metrics:
    - type: main_score
      value: 71.8
    - type: map_at_1
      value: 47.629
    - type: map_at_10
      value: 64.846
    - type: map_at_100
      value: 65.40899999999999
    - type: map_at_1000
      value: 65.416
    - type: map_at_20
      value: 65.239
    - type: map_at_3
      value: 61.185
    - type: map_at_5
      value: 63.583
    - type: mrr_at_1
      value: 53.15758980301275
    - type: mrr_at_10
      value: 67.12880961577366
    - type: mrr_at_100
      value: 67.44006405426018
    - type: mrr_at_1000
      value: 67.44519150402294
    - type: mrr_at_20
      value: 67.34317135515428
    - type: mrr_at_3
      value: 64.5905755117805
    - type: mrr_at_5
      value: 66.24613750482806
    - type: nauc_map_at_1000_diff1
      value: 45.73812106517133
    - type: nauc_map_at_1000_max
      value: 35.21262031755756
    - type: nauc_map_at_1000_std
      value: -5.549443574026027
    - type: nauc_map_at_100_diff1
      value: 45.74254652176879
    - type: nauc_map_at_100_max
      value: 35.22349167515518
    - type: nauc_map_at_100_std
      value: -5.53697496044773
    - type: nauc_map_at_10_diff1
      value: 45.62837128377087
    - type: nauc_map_at_10_max
      value: 35.3261562342222
    - type: nauc_map_at_10_std
      value: -5.761924414031163
    - type: nauc_map_at_1_diff1
      value: 48.69187848570499
    - type: nauc_map_at_1_max
      value: 28.687996096473476
    - type: nauc_map_at_1_std
      value: -7.518605958272523
    - type: nauc_map_at_20_diff1
      value: 45.702303442220035
    - type: nauc_map_at_20_max
      value: 35.30719944705456
    - type: nauc_map_at_20_std
      value: -5.59505654742681
    - type: nauc_map_at_3_diff1
      value: 45.376813726832474
    - type: nauc_map_at_3_max
      value: 34.68452149643597
    - type: nauc_map_at_3_std
      value: -7.329014950379634
    - type: nauc_map_at_5_diff1
      value: 45.29528861989316
    - type: nauc_map_at_5_max
      value: 35.35741440869229
    - type: nauc_map_at_5_std
      value: -6.028788612259288
    - type: nauc_mrr_at_1000_diff1
      value: 46.11808147912517
    - type: nauc_mrr_at_1000_max
      value: 35.59241850411947
    - type: nauc_mrr_at_1000_std
      value: -3.4072428526109317
    - type: nauc_mrr_at_100_diff1
      value: 46.121345545514046
    - type: nauc_mrr_at_100_max
      value: 35.60147795073431
    - type: nauc_mrr_at_100_std
      value: -3.3965322447588826
    - type: nauc_mrr_at_10_diff1
      value: 46.0920068210502
    - type: nauc_mrr_at_10_max
      value: 35.79649987854354
    - type: nauc_mrr_at_10_std
      value: -3.339624589368137
    - type: nauc_mrr_at_1_diff1
      value: 49.101364605656194
    - type: nauc_mrr_at_1_max
      value: 31.500796071482146
    - type: nauc_mrr_at_1_std
      value: -4.183818500718156
    - type: nauc_mrr_at_20_diff1
      value: 46.088076630465594
    - type: nauc_mrr_at_20_max
      value: 35.682131663053205
    - type: nauc_mrr_at_20_std
      value: -3.35939023178519
    - type: nauc_mrr_at_3_diff1
      value: 45.47570812708642
    - type: nauc_mrr_at_3_max
      value: 35.741892517632984
    - type: nauc_mrr_at_3_std
      value: -4.135335963822013
    - type: nauc_mrr_at_5_diff1
      value: 45.78903474184014
    - type: nauc_mrr_at_5_max
      value: 35.91273593700205
    - type: nauc_mrr_at_5_std
      value: -3.467873421286869
    - type: nauc_ndcg_at_1000_diff1
      value: 45.5056583000012
    - type: nauc_ndcg_at_1000_max
      value: 36.34328379251593
    - type: nauc_ndcg_at_1000_std
      value: -4.0759698229323345
    - type: nauc_ndcg_at_100_diff1
      value: 45.61918946477166
    - type: nauc_ndcg_at_100_max
      value: 36.675460335836235
    - type: nauc_ndcg_at_100_std
      value: -3.6795334726235986
    - type: nauc_ndcg_at_10_diff1
      value: 45.15343994274541
    - type: nauc_ndcg_at_10_max
      value: 37.48139242964657
    - type: nauc_ndcg_at_10_std
      value: -4.287039084554882
    - type: nauc_ndcg_at_1_diff1
      value: 49.101364605656194
    - type: nauc_ndcg_at_1_max
      value: 31.500796071482146
    - type: nauc_ndcg_at_1_std
      value: -4.183818500718156
    - type: nauc_ndcg_at_20_diff1
      value: 45.310026313402375
    - type: nauc_ndcg_at_20_max
      value: 37.32177497902133
    - type: nauc_ndcg_at_20_std
      value: -3.8214360391282587
    - type: nauc_ndcg_at_3_diff1
      value: 44.27064370528994
    - type: nauc_ndcg_at_3_max
      value: 36.380294033571396
    - type: nauc_ndcg_at_3_std
      value: -6.844263370898355
    - type: nauc_ndcg_at_5_diff1
      value: 44.29933499225583
    - type: nauc_ndcg_at_5_max
      value: 37.46477041822136
    - type: nauc_ndcg_at_5_std
      value: -4.866548530467956
    - type: nauc_precision_at_1000_diff1
      value: -14.666553359142306
    - type: nauc_precision_at_1000_max
      value: -0.5599759853201481
    - type: nauc_precision_at_1000_std
      value: 16.8370925526591
    - type: nauc_precision_at_100_diff1
      value: -11.816251306246278
    - type: nauc_precision_at_100_max
      value: 2.969819268208207
    - type: nauc_precision_at_100_std
      value: 18.59422946634747
    - type: nauc_precision_at_10_diff1
      value: 1.2050200086029401
    - type: nauc_precision_at_10_max
      value: 17.59930352911209
    - type: nauc_precision_at_10_std
      value: 13.714495717588985
    - type: nauc_precision_at_1_diff1
      value: 49.101364605656194
    - type: nauc_precision_at_1_max
      value: 31.500796071482146
    - type: nauc_precision_at_1_std
      value: -4.183818500718156
    - type: nauc_precision_at_20_diff1
      value: -5.263476664822757
    - type: nauc_precision_at_20_max
      value: 11.42004823600046
    - type: nauc_precision_at_20_std
      value: 16.510514518664994
    - type: nauc_precision_at_3_diff1
      value: 20.116460379305828
    - type: nauc_precision_at_3_max
      value: 31.32235038301311
    - type: nauc_precision_at_3_std
      value: 2.7486717133871923
    - type: nauc_precision_at_5_diff1
      value: 9.57451645335723
    - type: nauc_precision_at_5_max
      value: 25.28449126580587
    - type: nauc_precision_at_5_std
      value: 9.955736162466767
    - type: nauc_recall_at_1000_diff1
      value: -21.632253065978794
    - type: nauc_recall_at_1000_max
      value: 70.14409090958776
    - type: nauc_recall_at_1000_std
      value: 65.61658090892989
    - type: nauc_recall_at_100_diff1
      value: 51.83161124806711
    - type: nauc_recall_at_100_max
      value: 77.49921361841523
    - type: nauc_recall_at_100_std
      value: 48.352508746719444
    - type: nauc_recall_at_10_diff1
      value: 39.86695231362791
    - type: nauc_recall_at_10_max
      value: 50.12029094799474
    - type: nauc_recall_at_10_std
      value: 0.1650940628131058
    - type: nauc_recall_at_1_diff1
      value: 48.69187848570499
    - type: nauc_recall_at_1_max
      value: 28.687996096473476
    - type: nauc_recall_at_1_std
      value: -7.518605958272523
    - type: nauc_recall_at_20_diff1
      value: 39.14155398061627
    - type: nauc_recall_at_20_max
      value: 56.78559423716229
    - type: nauc_recall_at_20_std
      value: 7.9728224572344075
    - type: nauc_recall_at_3_diff1
      value: 38.69589523432158
    - type: nauc_recall_at_3_max
      value: 39.53271258375579
    - type: nauc_recall_at_3_std
      value: -8.646925065787512
    - type: nauc_recall_at_5_diff1
      value: 37.45922652959002
    - type: nauc_recall_at_5_max
      value: 44.4911958995867
    - type: nauc_recall_at_5_std
      value: -3.5659842556375594
    - type: ndcg_at_1
      value: 53.15800000000001
    - type: ndcg_at_10
      value: 71.8
    - type: ndcg_at_100
      value: 73.85199999999999
    - type: ndcg_at_1000
      value: 74.017
    - type: ndcg_at_20
      value: 72.933
    - type: ndcg_at_3
      value: 65.479
    - type: ndcg_at_5
      value: 69.182
    - type: precision_at_1
      value: 53.15800000000001
    - type: precision_at_10
      value: 10.805
    - type: precision_at_100
      value: 1.2
    - type: precision_at_1000
      value: 0.122
    - type: precision_at_20
      value: 5.694
    - type: precision_at_3
      value: 28.939999999999998
    - type: precision_at_5
      value: 19.641000000000002
    - type: recall_at_1
      value: 47.629
    - type: recall_at_10
      value: 90.204
    - type: recall_at_100
      value: 98.66
    - type: recall_at_1000
      value: 99.874
    - type: recall_at_20
      value: 94.24
    - type: recall_at_3
      value: 74.394
    - type: recall_at_5
      value: 82.711
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB QuoraRetrieval
      revision: e4e08e0b7dbe3c8700f0daef558ff32256715259
      split: test
      type: mteb/quora
    metrics:
    - type: main_score
      value: 90.025
    - type: map_at_1
      value: 72.222
    - type: map_at_10
      value: 86.58500000000001
    - type: map_at_100
      value: 87.176
    - type: map_at_1000
      value: 87.188
    - type: map_at_20
      value: 86.97399999999999
    - type: map_at_3
      value: 83.736
    - type: map_at_5
      value: 85.554
    - type: mrr_at_1
      value: 83.04
    - type: mrr_at_10
      value: 89.05599603174585
    - type: mrr_at_100
      value: 89.12398891419457
    - type: mrr_at_1000
      value: 89.12434072241001
    - type: mrr_at_20
      value: 89.10416280692111
    - type: mrr_at_3
      value: 88.23833333333312
    - type: mrr_at_5
      value: 88.82233333333308
    - type: nauc_map_at_1000_diff1
      value: 78.29348113313218
    - type: nauc_map_at_1000_max
      value: 32.31386754277228
    - type: nauc_map_at_1000_std
      value: -50.47543661484052
    - type: nauc_map_at_100_diff1
      value: 78.29618548618575
    - type: nauc_map_at_100_max
      value: 32.301475680947846
    - type: nauc_map_at_100_std
      value: -50.50303428814228
    - type: nauc_map_at_10_diff1
      value: 78.47383776440803
    - type: nauc_map_at_10_max
      value: 31.839339990133563
    - type: nauc_map_at_10_std
      value: -52.832713555976
    - type: nauc_map_at_1_diff1
      value: 82.46330147467418
    - type: nauc_map_at_1_max
      value: 23.497664918373538
    - type: nauc_map_at_1_std
      value: -43.824657665520704
    - type: nauc_map_at_20_diff1
      value: 78.34772176474422
    - type: nauc_map_at_20_max
      value: 32.16495182893947
    - type: nauc_map_at_20_std
      value: -51.503292726558605
    - type: nauc_map_at_3_diff1
      value: 79.07823813069432
    - type: nauc_map_at_3_max
      value: 29.395911687513976
    - type: nauc_map_at_3_std
      value: -54.16377546873304
    - type: nauc_map_at_5_diff1
      value: 78.73076619520454
    - type: nauc_map_at_5_max
      value: 30.700453118585237
    - type: nauc_map_at_5_std
      value: -54.130514177664054
    - type: nauc_mrr_at_1000_diff1
      value: 79.04736184471865
    - type: nauc_mrr_at_1000_max
      value: 34.43004593837643
    - type: nauc_mrr_at_1000_std
      value: -46.137269068195316
    - type: nauc_mrr_at_100_diff1
      value: 79.04698704288086
    - type: nauc_mrr_at_100_max
      value: 34.4305553741175
    - type: nauc_mrr_at_100_std
      value: -46.13786687786434
    - type: nauc_mrr_at_10_diff1
      value: 79.04490677485934
    - type: nauc_mrr_at_10_max
      value: 34.38170181522227
    - type: nauc_mrr_at_10_std
      value: -46.38129875681807
    - type: nauc_mrr_at_1_diff1
      value: 79.87159215719124
    - type: nauc_mrr_at_1_max
      value: 34.05882339253136
    - type: nauc_mrr_at_1_std
      value: -43.56093395137571
    - type: nauc_mrr_at_20_diff1
      value: 79.04384174535653
    - type: nauc_mrr_at_20_max
      value: 34.442136494675005
    - type: nauc_mrr_at_20_std
      value: -46.205458519638654
    - type: nauc_mrr_at_3_diff1
      value: 78.78154519155487
    - type: nauc_mrr_at_3_max
      value: 34.74995000500305
    - type: nauc_mrr_at_3_std
      value: -46.36264203155416
    - type: nauc_mrr_at_5_diff1
      value: 79.02631187177
    - type: nauc_mrr_at_5_max
      value: 34.538698249632205
    - type: nauc_mrr_at_5_std
      value: -46.468881576157465
    - type: nauc_ndcg_at_1000_diff1
      value: 78.25260097014645
    - type: nauc_ndcg_at_1000_max
      value: 33.68584498704271
    - type: nauc_ndcg_at_1000_std
      value: -48.44716779494868
    - type: nauc_ndcg_at_100_diff1
      value: 78.25115412256716
    - type: nauc_ndcg_at_100_max
      value: 33.63652663447088
    - type: nauc_ndcg_at_100_std
      value: -48.489243909024715
    - type: nauc_ndcg_at_10_diff1
      value: 78.23875101557334
    - type: nauc_ndcg_at_10_max
      value: 32.65217430043823
    - type: nauc_ndcg_at_10_std
      value: -52.57770468845309
    - type: nauc_ndcg_at_1_diff1
      value: 79.87159215719124
    - type: nauc_ndcg_at_1_max
      value: 34.05882339253136
    - type: nauc_ndcg_at_1_std
      value: -43.56093395137571
    - type: nauc_ndcg_at_20_diff1
      value: 78.23478552311765
    - type: nauc_ndcg_at_20_max
      value: 33.30691737901109
    - type: nauc_ndcg_at_20_std
      value: -50.78412614854527
    - type: nauc_ndcg_at_3_diff1
      value: 77.66134485470224
    - type: nauc_ndcg_at_3_max
      value: 32.19504710373125
    - type: nauc_ndcg_at_3_std
      value: -52.01636728550155
    - type: nauc_ndcg_at_5_diff1
      value: 78.04734137324255
    - type: nauc_ndcg_at_5_max
      value: 31.94593625591248
    - type: nauc_ndcg_at_5_std
      value: -53.02169800690546
    - type: nauc_precision_at_1000_diff1
      value: -45.771948123542636
    - type: nauc_precision_at_1000_max
      value: -5.182406190477681
    - type: nauc_precision_at_1000_std
      value: 41.14460438707817
    - type: nauc_precision_at_100_diff1
      value: -45.64767154261461
    - type: nauc_precision_at_100_max
      value: -5.046308286851713
    - type: nauc_precision_at_100_std
      value: 41.07186716587844
    - type: nauc_precision_at_10_diff1
      value: -42.26779562305825
    - type: nauc_precision_at_10_max
      value: -1.1264852893323076
    - type: nauc_precision_at_10_std
      value: 27.62275729822392
    - type: nauc_precision_at_1_diff1
      value: 79.87159215719124
    - type: nauc_precision_at_1_max
      value: 34.05882339253136
    - type: nauc_precision_at_1_std
      value: -43.56093395137571
    - type: nauc_precision_at_20_diff1
      value: -44.24293221128388
    - type: nauc_precision_at_20_max
      value: -3.1345628837361867
    - type: nauc_precision_at_20_std
      value: 34.23625492740366
    - type: nauc_precision_at_3_diff1
      value: -24.925251389823348
    - type: nauc_precision_at_3_max
      value: 6.622188833369412
    - type: nauc_precision_at_3_std
      value: 6.424741786858512
    - type: nauc_precision_at_5_diff1
      value: -36.1407949990387
    - type: nauc_precision_at_5_max
      value: 1.7533948968374462
    - type: nauc_precision_at_5_std
      value: 17.914083278982634
    - type: nauc_recall_at_1000_diff1
      value: 52.26815466244496
    - type: nauc_recall_at_1000_max
      value: 69.73611104239443
    - type: nauc_recall_at_1000_std
      value: 73.18969965863008
    - type: nauc_recall_at_100_diff1
      value: 70.80557513785271
    - type: nauc_recall_at_100_max
      value: 33.333440086544556
    - type: nauc_recall_at_100_std
      value: -38.75992366905504
    - type: nauc_recall_at_10_diff1
      value: 74.45948457438163
    - type: nauc_recall_at_10_max
      value: 26.64948512428989
    - type: nauc_recall_at_10_std
      value: -82.90334292052363
    - type: nauc_recall_at_1_diff1
      value: 82.46330147467418
    - type: nauc_recall_at_1_max
      value: 23.497664918373538
    - type: nauc_recall_at_1_std
      value: -43.824657665520704
    - type: nauc_recall_at_20_diff1
      value: 73.80140280887753
    - type: nauc_recall_at_20_max
      value: 30.361616426734965
    - type: nauc_recall_at_20_std
      value: -81.1418804447414
    - type: nauc_recall_at_3_diff1
      value: 75.19854736087834
    - type: nauc_recall_at_3_max
      value: 26.12298005045584
    - type: nauc_recall_at_3_std
      value: -63.42583714745169
    - type: nauc_recall_at_5_diff1
      value: 74.16423451950358
    - type: nauc_recall_at_5_max
      value: 25.552390331018987
    - type: nauc_recall_at_5_std
      value: -71.15891947773912
    - type: ndcg_at_1
      value: 83.04
    - type: ndcg_at_10
      value: 90.025
    - type: ndcg_at_100
      value: 91.006
    - type: ndcg_at_1000
      value: 91.061
    - type: ndcg_at_20
      value: 90.556
    - type: ndcg_at_3
      value: 87.493
    - type: ndcg_at_5
      value: 88.955
    - type: precision_at_1
      value: 83.04
    - type: precision_at_10
      value: 13.667000000000002
    - type: precision_at_100
      value: 1.542
    - type: precision_at_1000
      value: 0.157
    - type: precision_at_20
      value: 7.221
    - type: precision_at_3
      value: 38.433
    - type: precision_at_5
      value: 25.228
    - type: recall_at_1
      value: 72.222
    - type: recall_at_10
      value: 96.604
    - type: recall_at_100
      value: 99.786
    - type: recall_at_1000
      value: 99.996
    - type: recall_at_20
      value: 98.253
    - type: recall_at_3
      value: 89.276
    - type: recall_at_5
      value: 93.46
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB RedditClustering
      revision: 24640382cdbf8abc73003fb0fa6d111a705499eb
      split: test
      type: mteb/reddit-clustering
    metrics:
    - type: main_score
      value: 72.86492101891123
    - type: v_measure
      value: 72.86492101891123
    - type: v_measure_std
      value: 2.778711445144635
    task:
      type: Clustering
  - dataset:
      config: default
      name: MTEB RedditClusteringP2P
      revision: 385e3cb46b4cfa89021f56c4380204149d0efe33
      split: test
      type: mteb/reddit-clustering-p2p
    metrics:
    - type: main_score
      value: 75.27316726548479
    - type: v_measure
      value: 75.27316726548479
    - type: v_measure_std
      value: 8.87871936725338
    task:
      type: Clustering
  - dataset:
      config: default
      name: MTEB SCIDOCS
      revision: f8c2fcf00f625baaa80f62ec5bd9e1fff3b8ae88
      split: test
      type: mteb/scidocs
    metrics:
    - type: main_score
      value: 26.638
    - type: map_at_1
      value: 6.128
    - type: map_at_10
      value: 16.472
    - type: map_at_100
      value: 19.522000000000002
    - type: map_at_1000
      value: 19.898
    - type: map_at_20
      value: 18.098
    - type: map_at_3
      value: 11.283
    - type: map_at_5
      value: 13.771
    - type: mrr_at_1
      value: 30.2
    - type: mrr_at_10
      value: 42.621150793650735
    - type: mrr_at_100
      value: 43.740858712021954
    - type: mrr_at_1000
      value: 43.762699500220904
    - type: mrr_at_20
      value: 43.383639927753634
    - type: mrr_at_3
      value: 38.83333333333331
    - type: mrr_at_5
      value: 41.14833333333326
    - type: nauc_map_at_1000_diff1
      value: 13.13534664124808
    - type: nauc_map_at_1000_max
      value: 29.346654566149795
    - type: nauc_map_at_1000_std
      value: 18.08121186982413
    - type: nauc_map_at_100_diff1
      value: 13.098072728041538
    - type: nauc_map_at_100_max
      value: 29.299084480697523
    - type: nauc_map_at_100_std
      value: 17.961620202918464
    - type: nauc_map_at_10_diff1
      value: 14.001743720394682
    - type: nauc_map_at_10_max
      value: 28.04128290996403
    - type: nauc_map_at_10_std
      value: 13.744481555974716
    - type: nauc_map_at_1_diff1
      value: 22.1926640424872
    - type: nauc_map_at_1_max
      value: 21.32609279586034
    - type: nauc_map_at_1_std
      value: 6.566596302915438
    - type: nauc_map_at_20_diff1
      value: 13.57313142419664
    - type: nauc_map_at_20_max
      value: 28.93840146319476
    - type: nauc_map_at_20_std
      value: 16.50869367365676
    - type: nauc_map_at_3_diff1
      value: 17.707700541948462
    - type: nauc_map_at_3_max
      value: 26.058174051376238
    - type: nauc_map_at_3_std
      value: 9.943924560735267
    - type: nauc_map_at_5_diff1
      value: 17.11844492157723
    - type: nauc_map_at_5_max
      value: 27.865247403049388
    - type: nauc_map_at_5_std
      value: 11.372588172121546
    - type: nauc_mrr_at_1000_diff1
      value: 21.11248719936198
    - type: nauc_mrr_at_1000_max
      value: 26.734172102201466
    - type: nauc_mrr_at_1000_std
      value: 11.766121765437228
    - type: nauc_mrr_at_100_diff1
      value: 21.107109982277702
    - type: nauc_mrr_at_100_max
      value: 26.741616065723267
    - type: nauc_mrr_at_100_std
      value: 11.789802686224208
    - type: nauc_mrr_at_10_diff1
      value: 20.74108639793207
    - type: nauc_mrr_at_10_max
      value: 26.920838463358333
    - type: nauc_mrr_at_10_std
      value: 11.849217361926522
    - type: nauc_mrr_at_1_diff1
      value: 22.177437860573356
    - type: nauc_mrr_at_1_max
      value: 21.88074521417754
    - type: nauc_mrr_at_1_std
      value: 6.776011900101789
    - type: nauc_mrr_at_20_diff1
      value: 21.126633710175994
    - type: nauc_mrr_at_20_max
      value: 26.860736480370974
    - type: nauc_mrr_at_20_std
      value: 11.815411633726338
    - type: nauc_mrr_at_3_diff1
      value: 21.689245200066466
    - type: nauc_mrr_at_3_max
      value: 26.187305092831625
    - type: nauc_mrr_at_3_std
      value: 10.895380313134332
    - type: nauc_mrr_at_5_diff1
      value: 20.898811082479778
    - type: nauc_mrr_at_5_max
      value: 26.939217247104036
    - type: nauc_mrr_at_5_std
      value: 11.77832949822472
    - type: nauc_ndcg_at_1000_diff1
      value: 13.251184947898546
    - type: nauc_ndcg_at_1000_max
      value: 30.879594164526146
    - type: nauc_ndcg_at_1000_std
      value: 23.125206047366625
    - type: nauc_ndcg_at_100_diff1
      value: 12.549100649053676
    - type: nauc_ndcg_at_100_max
      value: 30.634680845419123
    - type: nauc_ndcg_at_100_std
      value: 23.296226055422984
    - type: nauc_ndcg_at_10_diff1
      value: 14.475144549294322
    - type: nauc_ndcg_at_10_max
      value: 29.450349815417336
    - type: nauc_ndcg_at_10_std
      value: 15.94068314781612
    - type: nauc_ndcg_at_1_diff1
      value: 22.177437860573356
    - type: nauc_ndcg_at_1_max
      value: 21.88074521417754
    - type: nauc_ndcg_at_1_std
      value: 6.776011900101789
    - type: nauc_ndcg_at_20_diff1
      value: 14.173669585802266
    - type: nauc_ndcg_at_20_max
      value: 30.475890854725
    - type: nauc_ndcg_at_20_std
      value: 19.863898148221704
    - type: nauc_ndcg_at_3_diff1
      value: 18.93971261196868
    - type: nauc_ndcg_at_3_max
      value: 27.3707298720736
    - type: nauc_ndcg_at_3_std
      value: 11.439810510051224
    - type: nauc_ndcg_at_5_diff1
      value: 17.89535958094687
    - type: nauc_ndcg_at_5_max
      value: 29.272740466638425
    - type: nauc_ndcg_at_5_std
      value: 13.402467626635909
    - type: nauc_precision_at_1000_diff1
      value: -3.811547048784123
    - type: nauc_precision_at_1000_max
      value: 22.55165337197117
    - type: nauc_precision_at_1000_std
      value: 35.98524999650108
    - type: nauc_precision_at_100_diff1
      value: 0.6474234774922896
    - type: nauc_precision_at_100_max
      value: 25.06920726527032
    - type: nauc_precision_at_100_std
      value: 32.31439698982313
    - type: nauc_precision_at_10_diff1
      value: 7.943127218139508
    - type: nauc_precision_at_10_max
      value: 28.571937636787197
    - type: nauc_precision_at_10_std
      value: 18.8472620918488
    - type: nauc_precision_at_1_diff1
      value: 22.177437860573356
    - type: nauc_precision_at_1_max
      value: 21.88074521417754
    - type: nauc_precision_at_1_std
      value: 6.776011900101789
    - type: nauc_precision_at_20_diff1
      value: 6.981574259607366
    - type: nauc_precision_at_20_max
      value: 28.986094397038727
    - type: nauc_precision_at_20_std
      value: 25.83129974001146
    - type: nauc_precision_at_3_diff1
      value: 17.197490724039355
    - type: nauc_precision_at_3_max
      value: 29.17569320583099
    - type: nauc_precision_at_3_std
      value: 13.430554945991846
    - type: nauc_precision_at_5_diff1
      value: 14.952364330739362
    - type: nauc_precision_at_5_max
      value: 31.053243354846977
    - type: nauc_precision_at_5_std
      value: 15.856312752807822
    - type: nauc_recall_at_1000_diff1
      value: -4.8224253128926975
    - type: nauc_recall_at_1000_max
      value: 21.3989024429911
    - type: nauc_recall_at_1000_std
      value: 39.152234275603604
    - type: nauc_recall_at_100_diff1
      value: 0.11936808422867201
    - type: nauc_recall_at_100_max
      value: 24.261739241957823
    - type: nauc_recall_at_100_std
      value: 32.62984573938928
    - type: nauc_recall_at_10_diff1
      value: 7.851256165018388
    - type: nauc_recall_at_10_max
      value: 27.936406600938746
    - type: nauc_recall_at_10_std
      value: 18.683634320636113
    - type: nauc_recall_at_1_diff1
      value: 22.1926640424872
    - type: nauc_recall_at_1_max
      value: 21.32609279586034
    - type: nauc_recall_at_1_std
      value: 6.566596302915438
    - type: nauc_recall_at_20_diff1
      value: 6.8107211705182165
    - type: nauc_recall_at_20_max
      value: 28.286284094687787
    - type: nauc_recall_at_20_std
      value: 25.932013268120862
    - type: nauc_recall_at_3_diff1
      value: 17.04156818427151
    - type: nauc_recall_at_3_max
      value: 28.645439108719216
    - type: nauc_recall_at_3_std
      value: 13.346047828494411
    - type: nauc_recall_at_5_diff1
      value: 14.906284329771822
    - type: nauc_recall_at_5_max
      value: 30.58628602415921
    - type: nauc_recall_at_5_std
      value: 15.755157478191755
    - type: ndcg_at_1
      value: 30.2
    - type: ndcg_at_10
      value: 26.638
    - type: ndcg_at_100
      value: 37.135
    - type: ndcg_at_1000
      value: 42.576
    - type: ndcg_at_20
      value: 30.75
    - type: ndcg_at_3
      value: 24.675
    - type: ndcg_at_5
      value: 21.836
    - type: precision_at_1
      value: 30.2
    - type: precision_at_10
      value: 14.06
    - type: precision_at_100
      value: 2.904
    - type: precision_at_1000
      value: 0.42
    - type: precision_at_20
      value: 9.4
    - type: precision_at_3
      value: 23.233
    - type: precision_at_5
      value: 19.439999999999998
    - type: recall_at_1
      value: 6.128
    - type: recall_at_10
      value: 28.471999999999998
    - type: recall_at_100
      value: 58.952000000000005
    - type: recall_at_1000
      value: 85.137
    - type: recall_at_20
      value: 38.17
    - type: recall_at_3
      value: 14.127999999999998
    - type: recall_at_5
      value: 19.673
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB SICK-R
      revision: 20a6d6f312dd54037fe07a32d58e5e168867909d
      split: test
      type: mteb/sickr-sts
    metrics:
    - type: cosine_pearson
      value: 86.86608529160739
    - type: cosine_spearman
      value: 82.88625166203383
    - type: euclidean_pearson
      value: 84.15494418856142
    - type: euclidean_spearman
      value: 82.88449294676421
    - type: main_score
      value: 82.88625166203383
    - type: manhattan_pearson
      value: 84.39068623474428
    - type: manhattan_spearman
      value: 82.88065412169463
    - type: pearson
      value: 86.86608529160739
    - type: spearman
      value: 82.88625166203383
    task:
      type: STS
  - dataset:
      config: default
      name: MTEB STS12
      revision: a0d554a64d88156834ff5ae9920b964011b16384
      split: test
      type: mteb/sts12-sts
    metrics:
    - type: cosine_pearson
      value: 87.0445014940449
    - type: cosine_spearman
      value: 80.0880365116599
    - type: euclidean_pearson
      value: 83.80250772928852
    - type: euclidean_spearman
      value: 80.0892465260778
    - type: main_score
      value: 80.0880365116599
    - type: manhattan_pearson
      value: 83.96793981929336
    - type: manhattan_spearman
      value: 80.24881789268238
    - type: pearson
      value: 87.0445014940449
    - type: spearman
      value: 80.0880365116599
    task:
      type: STS
  - dataset:
      config: default
      name: MTEB STS13
      revision: 7e90230a92c190f1bf69ae9002b8cea547a64cca
      split: test
      type: mteb/sts13-sts
    metrics:
    - type: cosine_pearson
      value: 89.33900828959968
    - type: cosine_spearman
      value: 89.68256358526733
    - type: euclidean_pearson
      value: 89.29188708262265
    - type: euclidean_spearman
      value: 89.68204344658601
    - type: main_score
      value: 89.68256358526733
    - type: manhattan_pearson
      value: 89.13996588193149
    - type: manhattan_spearman
      value: 89.61372804425623
    - type: pearson
      value: 89.33900828959968
    - type: spearman
      value: 89.68256358526733
    task:
      type: STS
  - dataset:
      config: default
      name: MTEB STS14
      revision: 6031580fec1f6af667f0bd2da0a551cf4f0b2375
      split: test
      type: mteb/sts14-sts
    metrics:
    - type: cosine_pearson
      value: 86.42029843639123
    - type: cosine_spearman
      value: 85.0707889220723
    - type: euclidean_pearson
      value: 85.75114239552562
    - type: euclidean_spearman
      value: 85.06858160270725
    - type: main_score
      value: 85.0707889220723
    - type: manhattan_pearson
      value: 85.86461900459038
    - type: manhattan_spearman
      value: 85.28671103475605
    - type: pearson
      value: 86.42029843639123
    - type: spearman
      value: 85.0707889220723
    task:
      type: STS
  - dataset:
      config: default
      name: MTEB STS15
      revision: ae752c7c21bf194d8b67fd573edf7ae58183cbe3
      split: test
      type: mteb/sts15-sts
    metrics:
    - type: cosine_pearson
      value: 88.3660081271444
    - type: cosine_spearman
      value: 89.39375083609528
    - type: euclidean_pearson
      value: 89.21818482894895
    - type: euclidean_spearman
      value: 89.39361588875443
    - type: main_score
      value: 89.39375083609528
    - type: manhattan_pearson
      value: 89.53535068014057
    - type: manhattan_spearman
      value: 89.81077130567752
    - type: pearson
      value: 88.3660081271444
    - type: spearman
      value: 89.39375083609528
    task:
      type: STS
  - dataset:
      config: default
      name: MTEB STS16
      revision: 4d8694f8f0e0100860b497b999b3dbed754a0513
      split: test
      type: mteb/sts16-sts
    metrics:
    - type: cosine_pearson
      value: 85.60708247171874
    - type: cosine_spearman
      value: 87.15234952832193
    - type: euclidean_pearson
      value: 86.21743555548137
    - type: euclidean_spearman
      value: 87.14450217418016
    - type: main_score
      value: 87.15234952832193
    - type: manhattan_pearson
      value: 86.2467748746084
    - type: manhattan_spearman
      value: 87.2197479717654
    - type: pearson
      value: 85.60708247171874
    - type: spearman
      value: 87.15234952832193
    task:
      type: STS
  - dataset:
      config: en-en
      name: MTEB STS17 (en-en)
      revision: faeb762787bd10488a50c8b5be4a3b82e411949c
      split: test
      type: mteb/sts17-crosslingual-sts
    metrics:
    - type: cosine_pearson
      value: 91.25898556808458
    - type: cosine_spearman
      value: 91.35372390581641
    - type: euclidean_pearson
      value: 91.319520321348
    - type: euclidean_spearman
      value: 91.30821135416925
    - type: main_score
      value: 91.35372390581641
    - type: manhattan_pearson
      value: 91.14800959939069
    - type: manhattan_spearman
      value: 91.09775424245629
    - type: pearson
      value: 91.25898556808458
    - type: spearman
      value: 91.35372390581641
    task:
      type: STS
  - dataset:
      config: en
      name: MTEB STS22 (en)
      revision: de9d86b3b84231dc21f76c7b7af1f28e2f57f6e3
      split: test
      type: mteb/sts22-crosslingual-sts
    metrics:
    - type: cosine_pearson
      value: 67.61637111515797
    - type: cosine_spearman
      value: 68.10379096526697
    - type: euclidean_pearson
      value: 69.2652309491375
    - type: euclidean_spearman
      value: 68.18436357033228
    - type: main_score
      value: 68.10379096526697
    - type: manhattan_pearson
      value: 69.52531340510775
    - type: manhattan_spearman
      value: 68.17874790391862
    - type: pearson
      value: 67.61637111515797
    - type: spearman
      value: 68.10379096526697
    task:
      type: STS
  - dataset:
      config: default
      name: MTEB STSBenchmark
      revision: b0fddb56ed78048fa8b90373c8a3cfc37b684831
      split: test
      type: mteb/stsbenchmark-sts
    metrics:
    - type: cosine_pearson
      value: 87.81592853782297
    - type: cosine_spearman
      value: 88.2302550329183
    - type: euclidean_pearson
      value: 88.01165144519526
    - type: euclidean_spearman
      value: 88.23342148890097
    - type: main_score
      value: 88.2302550329183
    - type: manhattan_pearson
      value: 88.148592564938
    - type: manhattan_spearman
      value: 88.49226317320988
    - type: pearson
      value: 87.81592853782297
    - type: spearman
      value: 88.2302550329183
    task:
      type: STS
  - dataset:
      config: default
      name: MTEB SciDocsRR
      revision: d3c5e1fc0b855ab6097bf1cda04dd73947d7caab
      split: test
      type: mteb/scidocs-reranking
    metrics:
    - type: main_score
      value: 89.196009707431
    - type: map
      value: 89.196009707431
    - type: mrr
      value: 97.07198121413808
    - type: nAUC_map_diff1
      value: -14.066667940115352
    - type: nAUC_map_max
      value: 49.73702475027407
    - type: nAUC_map_std
      value: 64.0986775782592
    - type: nAUC_mrr_diff1
      value: 21.96846389417319
    - type: nAUC_mrr_max
      value: 86.38341077184032
    - type: nAUC_mrr_std
      value: 75.38945014727746
    task:
      type: Reranking
  - dataset:
      config: default
      name: MTEB SciFact
      revision: 0228b52cf27578f30900b9e5271d331663a030d7
      split: test
      type: mteb/scifact
    metrics:
    - type: main_score
      value: 80.08999999999999
    - type: map_at_1
      value: 63.161
    - type: map_at_10
      value: 75.163
    - type: map_at_100
      value: 75.408
    - type: map_at_1000
      value: 75.409
    - type: map_at_20
      value: 75.332
    - type: map_at_3
      value: 71.839
    - type: map_at_5
      value: 74.32600000000001
    - type: mrr_at_1
      value: 66.33333333333333
    - type: mrr_at_10
      value: 75.95978835978836
    - type: mrr_at_100
      value: 76.15647881281473
    - type: mrr_at_1000
      value: 76.15736533763744
    - type: mrr_at_20
      value: 76.08557368557368
    - type: mrr_at_3
      value: 73.55555555555556
    - type: mrr_at_5
      value: 75.4888888888889
    - type: nauc_map_at_1000_diff1
      value: 77.31229383811176
    - type: nauc_map_at_1000_max
      value: 58.848319058605156
    - type: nauc_map_at_1000_std
      value: -14.290090263454985
    - type: nauc_map_at_100_diff1
      value: 77.31325400213969
    - type: nauc_map_at_100_max
      value: 58.848885054155275
    - type: nauc_map_at_100_std
      value: -14.285806618869273
    - type: nauc_map_at_10_diff1
      value: 77.1806705504232
    - type: nauc_map_at_10_max
      value: 59.02905805134415
    - type: nauc_map_at_10_std
      value: -14.132954900037467
    - type: nauc_map_at_1_diff1
      value: 81.03932970557837
    - type: nauc_map_at_1_max
      value: 49.02073230264529
    - type: nauc_map_at_1_std
      value: -22.977452975845512
    - type: nauc_map_at_20_diff1
      value: 77.22581364818562
    - type: nauc_map_at_20_max
      value: 58.90740400399768
    - type: nauc_map_at_20_std
      value: -14.245079150986745
    - type: nauc_map_at_3_diff1
      value: 76.99793243255563
    - type: nauc_map_at_3_max
      value: 54.9930733886623
    - type: nauc_map_at_3_std
      value: -19.297708446082407
    - type: nauc_map_at_5_diff1
      value: 77.1671608360295
    - type: nauc_map_at_5_max
      value: 57.27757489519526
    - type: nauc_map_at_5_std
      value: -15.446338357667708
    - type: nauc_mrr_at_1000_diff1
      value: 77.4806080821202
    - type: nauc_mrr_at_1000_max
      value: 60.9213776129792
    - type: nauc_mrr_at_1000_std
      value: -12.139599632228343
    - type: nauc_mrr_at_100_diff1
      value: 77.48158073865281
    - type: nauc_mrr_at_100_max
      value: 60.9218657185361
    - type: nauc_mrr_at_100_std
      value: -12.13532070453677
    - type: nauc_mrr_at_10_diff1
      value: 77.32428546014407
    - type: nauc_mrr_at_10_max
      value: 61.018407010343466
    - type: nauc_mrr_at_10_std
      value: -12.143193773309347
    - type: nauc_mrr_at_1_diff1
      value: 80.99806778887115
    - type: nauc_mrr_at_1_max
      value: 59.17855969530095
    - type: nauc_mrr_at_1_std
      value: -12.30545640831458
    - type: nauc_mrr_at_20_diff1
      value: 77.3811067653992
    - type: nauc_mrr_at_20_max
      value: 60.9648880366335
    - type: nauc_mrr_at_20_std
      value: -12.124066076541853
    - type: nauc_mrr_at_3_diff1
      value: 77.31304316321959
    - type: nauc_mrr_at_3_max
      value: 60.75536766404163
    - type: nauc_mrr_at_3_std
      value: -12.997876030849623
    - type: nauc_mrr_at_5_diff1
      value: 77.12952864141742
    - type: nauc_mrr_at_5_max
      value: 60.995943754968685
    - type: nauc_mrr_at_5_std
      value: -11.353447465605694
    - type: nauc_ndcg_at_1000_diff1
      value: 76.81788665683746
    - type: nauc_ndcg_at_1000_max
      value: 60.35947755262391
    - type: nauc_ndcg_at_1000_std
      value: -12.884942372460362
    - type: nauc_ndcg_at_100_diff1
      value: 76.87388230365198
    - type: nauc_ndcg_at_100_max
      value: 60.38813162962434
    - type: nauc_ndcg_at_100_std
      value: -12.64384717800478
    - type: nauc_ndcg_at_10_diff1
      value: 75.87713506026317
    - type: nauc_ndcg_at_10_max
      value: 61.39356554675667
    - type: nauc_ndcg_at_10_std
      value: -12.144227584144218
    - type: nauc_ndcg_at_1_diff1
      value: 80.99806778887115
    - type: nauc_ndcg_at_1_max
      value: 59.17855969530095
    - type: nauc_ndcg_at_1_std
      value: -12.30545640831458
    - type: nauc_ndcg_at_20_diff1
      value: 76.09913944506627
    - type: nauc_ndcg_at_20_max
      value: 61.01644448834147
    - type: nauc_ndcg_at_20_std
      value: -12.456209267623857
    - type: nauc_ndcg_at_3_diff1
      value: 75.52717946614608
    - type: nauc_ndcg_at_3_max
      value: 58.96433090721983
    - type: nauc_ndcg_at_3_std
      value: -15.849280494339556
    - type: nauc_ndcg_at_5_diff1
      value: 75.69026981016921
    - type: nauc_ndcg_at_5_max
      value: 58.924044405851326
    - type: nauc_ndcg_at_5_std
      value: -13.182728827923107
    - type: nauc_precision_at_1000_diff1
      value: -31.634022001609914
    - type: nauc_precision_at_1000_max
      value: 31.46271490784504
    - type: nauc_precision_at_1000_std
      value: 60.44801276891442
    - type: nauc_precision_at_100_diff1
      value: -29.722363469948103
    - type: nauc_precision_at_100_max
      value: 32.05464592020074
    - type: nauc_precision_at_100_std
      value: 60.832570595613554
    - type: nauc_precision_at_10_diff1
      value: -11.91731376599939
    - type: nauc_precision_at_10_max
      value: 45.43646553157129
    - type: nauc_precision_at_10_std
      value: 52.962408871791276
    - type: nauc_precision_at_1_diff1
      value: 80.99806778887115
    - type: nauc_precision_at_1_max
      value: 59.17855969530095
    - type: nauc_precision_at_1_std
      value: -12.30545640831458
    - type: nauc_precision_at_20_diff1
      value: -18.43293701721667
    - type: nauc_precision_at_20_max
      value: 39.53434874203934
    - type: nauc_precision_at_20_std
      value: 53.6291982468461
    - type: nauc_precision_at_3_diff1
      value: 30.84789043003892
    - type: nauc_precision_at_3_max
      value: 55.660727758110376
    - type: nauc_precision_at_3_std
      value: 17.87243920840355
    - type: nauc_precision_at_5_diff1
      value: 4.099395181445625
    - type: nauc_precision_at_5_max
      value: 50.346770968709386
    - type: nauc_precision_at_5_std
      value: 44.66722483255029
    - type: nauc_recall_at_1000_diff1
      value: .nan
    - type: nauc_recall_at_1000_max
      value: .nan
    - type: nauc_recall_at_1000_std
      value: .nan
    - type: nauc_recall_at_100_diff1
      value: 100.0
    - type: nauc_recall_at_100_max
      value: 72.2222222222207
    - type: nauc_recall_at_100_std
      value: 86.92810457516407
    - type: nauc_recall_at_10_diff1
      value: 62.18887555022005
    - type: nauc_recall_at_10_max
      value: 75.14339068960916
    - type: nauc_recall_at_10_std
      value: -1.4912631719357108
    - type: nauc_recall_at_1_diff1
      value: 81.03932970557837
    - type: nauc_recall_at_1_max
      value: 49.02073230264529
    - type: nauc_recall_at_1_std
      value: -22.977452975845512
    - type: nauc_recall_at_20_diff1
      value: 59.27414444038499
    - type: nauc_recall_at_20_max
      value: 76.32241302318047
    - type: nauc_recall_at_20_std
      value: -0.8322169447488666
    - type: nauc_recall_at_3_diff1
      value: 69.58783002593157
    - type: nauc_recall_at_3_max
      value: 55.89660919896563
    - type: nauc_recall_at_3_std
      value: -21.183005510917862
    - type: nauc_recall_at_5_diff1
      value: 65.53660499878802
    - type: nauc_recall_at_5_max
      value: 58.218018535135805
    - type: nauc_recall_at_5_std
      value: -8.328952210032455
    - type: ndcg_at_1
      value: 66.333
    - type: ndcg_at_10
      value: 80.08999999999999
    - type: ndcg_at_100
      value: 81.24900000000001
    - type: ndcg_at_1000
      value: 81.28800000000001
    - type: ndcg_at_20
      value: 80.625
    - type: ndcg_at_3
      value: 74.98700000000001
    - type: ndcg_at_5
      value: 78.553
    - type: precision_at_1
      value: 66.333
    - type: precision_at_10
      value: 10.667
    - type: precision_at_100
      value: 1.127
    - type: precision_at_1000
      value: 0.11299999999999999
    - type: precision_at_20
      value: 5.45
    - type: precision_at_3
      value: 29.555999999999997
    - type: precision_at_5
      value: 20.133000000000003
    - type: recall_at_1
      value: 63.161
    - type: recall_at_10
      value: 94.167
    - type: recall_at_100
      value: 99.667
    - type: recall_at_1000
      value: 100.0
    - type: recall_at_20
      value: 96.167
    - type: recall_at_3
      value: 80.972
    - type: recall_at_5
      value: 89.90599999999999
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB SprintDuplicateQuestions
      revision: d66bd1f72af766a5cc4b0ca5e00c162f89e8cc46
      split: test
      type: mteb/sprintduplicatequestions-pairclassification
    metrics:
    - type: cosine_accuracy
      value: 99.81881188118813
    - type: cosine_accuracy_threshold
      value: 85.55081486701965
    - type: cosine_ap
      value: 96.0359661816236
    - type: cosine_f1
      value: 90.6584992343032
    - type: cosine_f1_threshold
      value: 84.82859134674072
    - type: cosine_precision
      value: 92.59645464025026
    - type: cosine_recall
      value: 88.8
    - type: dot_accuracy
      value: 99.81881188118813
    - type: dot_accuracy_threshold
      value: 84.91908311843872
    - type: dot_ap
      value: 96.05740121094365
    - type: dot_f1
      value: 90.81885856079404
    - type: dot_f1_threshold
      value: 83.84919166564941
    - type: dot_precision
      value: 90.14778325123153
    - type: dot_recall
      value: 91.5
    - type: euclidean_accuracy
      value: 99.82079207920792
    - type: euclidean_accuracy_threshold
      value: 54.49706315994263
    - type: euclidean_ap
      value: 96.03223527068818
    - type: euclidean_f1
      value: 90.72270630445925
    - type: euclidean_f1_threshold
      value: 54.49706315994263
    - type: euclidean_precision
      value: 93.05993690851734
    - type: euclidean_recall
      value: 88.5
    - type: main_score
      value: 96.32671902439806
    - type: manhattan_accuracy
      value: 99.83267326732673
    - type: manhattan_accuracy_threshold
      value: 3818.192672729492
    - type: manhattan_ap
      value: 96.32671902439806
    - type: manhattan_f1
      value: 91.52032112393378
    - type: manhattan_f1_threshold
      value: 3818.192672729492
    - type: manhattan_precision
      value: 91.8429003021148
    - type: manhattan_recall
      value: 91.2
    - type: max_ap
      value: 96.32671902439806
    - type: max_f1
      value: 91.52032112393378
    - type: max_precision
      value: 93.05993690851734
    - type: max_recall
      value: 91.5
    - type: similarity_accuracy
      value: 99.81881188118813
    - type: similarity_accuracy_threshold
      value: 85.55081486701965
    - type: similarity_ap
      value: 96.0359661816236
    - type: similarity_f1
      value: 90.6584992343032
    - type: similarity_f1_threshold
      value: 84.82859134674072
    - type: similarity_precision
      value: 92.59645464025026
    - type: similarity_recall
      value: 88.8
    task:
      type: PairClassification
  - dataset:
      config: default
      name: MTEB StackExchangeClustering
      revision: 6cbc1f7b2bc0622f2e39d2c77fa502909748c259
      split: test
      type: mteb/stackexchange-clustering
    metrics:
    - type: main_score
      value: 80.28558559137414
    - type: v_measure
      value: 80.28558559137414
    - type: v_measure_std
      value: 2.795276520287584
    task:
      type: Clustering
  - dataset:
      config: default
      name: MTEB StackExchangeClusteringP2P
      revision: 815ca46b2622cec33ccafc3735d572c266efdb44
      split: test
      type: mteb/stackexchange-clustering-p2p
    metrics:
    - type: main_score
      value: 49.57135582416209
    - type: v_measure
      value: 49.57135582416209
    - type: v_measure_std
      value: 1.6414135468423754
    task:
      type: Clustering
  - dataset:
      config: default
      name: MTEB StackOverflowDupQuestions
      revision: e185fbe320c72810689fc5848eb6114e1ef5ec69
      split: test
      type: mteb/stackoverflowdupquestions-reranking
    metrics:
    - type: main_score
      value: 55.253002583598644
    - type: map
      value: 55.253002583598644
    - type: mrr
      value: 56.24172396231219
    - type: nAUC_map_diff1
      value: 40.00053248203427
    - type: nAUC_map_max
      value: 10.05441740585869
    - type: nAUC_map_std
      value: 8.227169286387552
    - type: nAUC_mrr_diff1
      value: 40.250446264233744
    - type: nAUC_mrr_max
      value: 10.586310195339053
    - type: nAUC_mrr_std
      value: 8.47326494370076
    task:
      type: Reranking
  - dataset:
      config: default
      name: MTEB SummEval
      revision: cda12ad7615edc362dbf25a00fdd61d3b1eaf93c
      split: test
      type: mteb/summeval
    metrics:
    - type: cosine_pearson
      value: 31.19874648747059
    - type: cosine_spearman
      value: 31.493550648844863
    - type: dot_pearson
      value: 31.157847680289407
    - type: dot_spearman
      value: 31.575299712180538
    - type: main_score
      value: 31.493550648844863
    - type: pearson
      value: 31.19874648747059
    - type: spearman
      value: 31.493550648844863
    task:
      type: Summarization
  - dataset:
      config: default
      name: MTEB TRECCOVID
      revision: bb9466bac8153a0349341eb1b22e06409e78ef4e
      split: test
      type: mteb/trec-covid
    metrics:
    - type: main_score
      value: 85.983
    - type: map_at_1
      value: 0.247
    - type: map_at_10
      value: 2.177
    - type: map_at_100
      value: 14.804
    - type: map_at_1000
      value: 37.045
    - type: map_at_20
      value: 4.12
    - type: map_at_3
      value: 0.7000000000000001
    - type: map_at_5
      value: 1.1320000000000001
    - type: mrr_at_1
      value: 96.0
    - type: mrr_at_10
      value: 98.0
    - type: mrr_at_100
      value: 98.0
    - type: mrr_at_1000
      value: 98.0
    - type: mrr_at_20
      value: 98.0
    - type: mrr_at_3
      value: 98.0
    - type: mrr_at_5
      value: 98.0
    - type: nauc_map_at_1000_diff1
      value: -0.9165125200337213
    - type: nauc_map_at_1000_max
      value: 40.260117798042764
    - type: nauc_map_at_1000_std
      value: 71.72789335831554
    - type: nauc_map_at_100_diff1
      value: 20.493827311583953
    - type: nauc_map_at_100_max
      value: 21.005742079276462
    - type: nauc_map_at_100_std
      value: 62.53815607831659
    - type: nauc_map_at_10_diff1
      value: 31.289297684528215
    - type: nauc_map_at_10_max
      value: 7.86554294370268
    - type: nauc_map_at_10_std
      value: 37.26191657133897
    - type: nauc_map_at_1_diff1
      value: 25.57568148849456
    - type: nauc_map_at_1_max
      value: -5.9767435623941445
    - type: nauc_map_at_1_std
      value: 30.849871717506755
    - type: nauc_map_at_20_diff1
      value: 30.896018204532087
    - type: nauc_map_at_20_max
      value: 8.667077299744314
    - type: nauc_map_at_20_std
      value: 41.512687168412924
    - type: nauc_map_at_3_diff1
      value: 29.44724521006598
    - type: nauc_map_at_3_max
      value: 1.597496889532064
    - type: nauc_map_at_3_std
      value: 32.25013773854697
    - type: nauc_map_at_5_diff1
      value: 27.387036605618825
    - type: nauc_map_at_5_max
      value: 5.402983746211454
    - type: nauc_map_at_5_std
      value: 33.940523962472184
    - type: nauc_mrr_at_1000_diff1
      value: -14.122315592903503
    - type: nauc_mrr_at_1000_max
      value: 33.84687208216605
    - type: nauc_mrr_at_1000_std
      value: 86.11111111111092
    - type: nauc_mrr_at_100_diff1
      value: -14.122315592903503
    - type: nauc_mrr_at_100_max
      value: 33.84687208216605
    - type: nauc_mrr_at_100_std
      value: 86.11111111111092
    - type: nauc_mrr_at_10_diff1
      value: -14.122315592903503
    - type: nauc_mrr_at_10_max
      value: 33.84687208216605
    - type: nauc_mrr_at_10_std
      value: 86.11111111111092
    - type: nauc_mrr_at_1_diff1
      value: -14.122315592903831
    - type: nauc_mrr_at_1_max
      value: 33.84687208216637
    - type: nauc_mrr_at_1_std
      value: 86.11111111111124
    - type: nauc_mrr_at_20_diff1
      value: -14.122315592903503
    - type: nauc_mrr_at_20_max
      value: 33.84687208216605
    - type: nauc_mrr_at_20_std
      value: 86.11111111111092
    - type: nauc_mrr_at_3_diff1
      value: -14.122315592903503
    - type: nauc_mrr_at_3_max
      value: 33.84687208216605
    - type: nauc_mrr_at_3_std
      value: 86.11111111111092
    - type: nauc_mrr_at_5_diff1
      value: -14.122315592903503
    - type: nauc_mrr_at_5_max
      value: 33.84687208216605
    - type: nauc_mrr_at_5_std
      value: 86.11111111111092
    - type: nauc_ndcg_at_1000_diff1
      value: 8.745907669561928
    - type: nauc_ndcg_at_1000_max
      value: 45.43307237994533
    - type: nauc_ndcg_at_1000_std
      value: 74.93357447176336
    - type: nauc_ndcg_at_100_diff1
      value: -3.9719350773353765
    - type: nauc_ndcg_at_100_max
      value: 44.43705332397461
    - type: nauc_ndcg_at_100_std
      value: 61.59493812371758
    - type: nauc_ndcg_at_10_diff1
      value: 15.230915878367348
    - type: nauc_ndcg_at_10_max
      value: 48.332840970836635
    - type: nauc_ndcg_at_10_std
      value: 46.888785065125774
    - type: nauc_ndcg_at_1_diff1
      value: 13.219732337379442
    - type: nauc_ndcg_at_1_max
      value: 45.19919078742603
    - type: nauc_ndcg_at_1_std
      value: 64.68253968253977
    - type: nauc_ndcg_at_20_diff1
      value: 12.479648691964865
    - type: nauc_ndcg_at_20_max
      value: 48.76688248450331
    - type: nauc_ndcg_at_20_std
      value: 51.450399755887545
    - type: nauc_ndcg_at_3_diff1
      value: 6.165414201871464
    - type: nauc_ndcg_at_3_max
      value: 45.089689347691035
    - type: nauc_ndcg_at_3_std
      value: 41.08249161845213
    - type: nauc_ndcg_at_5_diff1
      value: 7.411245806844721
    - type: nauc_ndcg_at_5_max
      value: 47.818748093538076
    - type: nauc_ndcg_at_5_std
      value: 45.907685763676575
    - type: nauc_precision_at_1000_diff1
      value: -30.574290219847345
    - type: nauc_precision_at_1000_max
      value: 32.56926126118719
    - type: nauc_precision_at_1000_std
      value: 14.584504392628874
    - type: nauc_precision_at_100_diff1
      value: -10.199740234718847
    - type: nauc_precision_at_100_max
      value: 41.0213226769777
    - type: nauc_precision_at_100_std
      value: 56.975760776771324
    - type: nauc_precision_at_10_diff1
      value: 7.865792689701161
    - type: nauc_precision_at_10_max
      value: 52.00432275201737
    - type: nauc_precision_at_10_std
      value: 43.89512276413724
    - type: nauc_precision_at_1_diff1
      value: -14.122315592903831
    - type: nauc_precision_at_1_max
      value: 33.84687208216637
    - type: nauc_precision_at_1_std
      value: 86.11111111111124
    - type: nauc_precision_at_20_diff1
      value: 5.481424191880084
    - type: nauc_precision_at_20_max
      value: 46.86629331792725
    - type: nauc_precision_at_20_std
      value: 49.245692667517496
    - type: nauc_precision_at_3_diff1
      value: -5.870408807869163
    - type: nauc_precision_at_3_max
      value: 48.73657612128875
    - type: nauc_precision_at_3_std
      value: 41.15152062088262
    - type: nauc_precision_at_5_diff1
      value: -4.550610529125413
    - type: nauc_precision_at_5_max
      value: 60.390115878205386
    - type: nauc_precision_at_5_std
      value: 44.16494295055696
    - type: nauc_recall_at_1000_diff1
      value: 8.047794367079034
    - type: nauc_recall_at_1000_max
      value: 37.07551482870489
    - type: nauc_recall_at_1000_std
      value: 66.20862163364201
    - type: nauc_recall_at_100_diff1
      value: 25.08104923597475
    - type: nauc_recall_at_100_max
      value: 9.971294642165734
    - type: nauc_recall_at_100_std
      value: 51.737814074891254
    - type: nauc_recall_at_10_diff1
      value: 32.33148478369628
    - type: nauc_recall_at_10_max
      value: 1.3767192150014917
    - type: nauc_recall_at_10_std
      value: 30.801926742876308
    - type: nauc_recall_at_1_diff1
      value: 25.57568148849456
    - type: nauc_recall_at_1_max
      value: -5.9767435623941445
    - type: nauc_recall_at_1_std
      value: 30.849871717506755
    - type: nauc_recall_at_20_diff1
      value: 31.716580022934654
    - type: nauc_recall_at_20_max
      value: -0.1281270579464631
    - type: nauc_recall_at_20_std
      value: 33.76185294993676
    - type: nauc_recall_at_3_diff1
      value: 29.758810004388348
    - type: nauc_recall_at_3_max
      value: -1.9442985017191816
    - type: nauc_recall_at_3_std
      value: 27.45550076962206
    - type: nauc_recall_at_5_diff1
      value: 27.047710181576672
    - type: nauc_recall_at_5_max
      value: 1.5237000700880248
    - type: nauc_recall_at_5_std
      value: 28.235297950159698
    - type: ndcg_at_1
      value: 94.0
    - type: ndcg_at_10
      value: 85.983
    - type: ndcg_at_100
      value: 69.195
    - type: ndcg_at_1000
      value: 62.541000000000004
    - type: ndcg_at_20
      value: 83.405
    - type: ndcg_at_3
      value: 89.98899999999999
    - type: ndcg_at_5
      value: 87.905
    - type: precision_at_1
      value: 96.0
    - type: precision_at_10
      value: 89.4
    - type: precision_at_100
      value: 71.54
    - type: precision_at_1000
      value: 27.594
    - type: precision_at_20
      value: 87.2
    - type: precision_at_3
      value: 92.667
    - type: precision_at_5
      value: 90.8
    - type: recall_at_1
      value: 0.247
    - type: recall_at_10
      value: 2.315
    - type: recall_at_100
      value: 17.574
    - type: recall_at_1000
      value: 59.336999999999996
    - type: recall_at_20
      value: 4.491
    - type: recall_at_3
      value: 0.7250000000000001
    - type: recall_at_5
      value: 1.1820000000000002
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB Touche2020
      revision: a34f9a33db75fa0cbb21bb5cfc3dae8dc8bec93f
      split: test
      type: mteb/touche2020
    metrics:
    - type: main_score
      value: 29.944
    - type: map_at_1
      value: 3.064
    - type: map_at_10
      value: 11.501999999999999
    - type: map_at_100
      value: 18.736
    - type: map_at_1000
      value: 20.333000000000002
    - type: map_at_20
      value: 14.057
    - type: map_at_3
      value: 6.300999999999999
    - type: map_at_5
      value: 8.463
    - type: mrr_at_1
      value: 44.89795918367347
    - type: mrr_at_10
      value: 58.41188856494979
    - type: mrr_at_100
      value: 58.93964266413245
    - type: mrr_at_1000
      value: 58.93964266413245
    - type: mrr_at_20
      value: 58.767485349118
    - type: mrr_at_3
      value: 54.42176870748299
    - type: mrr_at_5
      value: 56.666666666666664
    - type: nauc_map_at_1000_diff1
      value: 11.478593385608479
    - type: nauc_map_at_1000_max
      value: 10.309889845044324
    - type: nauc_map_at_1000_std
      value: 21.16721939940238
    - type: nauc_map_at_100_diff1
      value: 11.570438543562418
    - type: nauc_map_at_100_max
      value: 8.426183648064834
    - type: nauc_map_at_100_std
      value: 18.56231985033613
    - type: nauc_map_at_10_diff1
      value: 22.37735506247481
    - type: nauc_map_at_10_max
      value: 5.455946239060806
    - type: nauc_map_at_10_std
      value: -4.2848826518388154
    - type: nauc_map_at_1_diff1
      value: 27.853645380676824
    - type: nauc_map_at_1_max
      value: 7.30739948053113
    - type: nauc_map_at_1_std
      value: -0.2773663157814586
    - type: nauc_map_at_20_diff1
      value: 14.724669779924648
    - type: nauc_map_at_20_max
      value: 10.12882779173533
    - type: nauc_map_at_20_std
      value: 4.4803777672120875
    - type: nauc_map_at_3_diff1
      value: 31.891173385921263
    - type: nauc_map_at_3_max
      value: 4.889652271827218
    - type: nauc_map_at_3_std
      value: -9.477460238651643
    - type: nauc_map_at_5_diff1
      value: 31.489012040465003
    - type: nauc_map_at_5_max
      value: 1.7330092417337482
    - type: nauc_map_at_5_std
      value: -8.137018608469637
    - type: nauc_mrr_at_1000_diff1
      value: 24.411522237082416
    - type: nauc_mrr_at_1000_max
      value: 11.286971076556688
    - type: nauc_mrr_at_1000_std
      value: 23.443174210894043
    - type: nauc_mrr_at_100_diff1
      value: 24.411522237082416
    - type: nauc_mrr_at_100_max
      value: 11.286971076556688
    - type: nauc_mrr_at_100_std
      value: 23.443174210894043
    - type: nauc_mrr_at_10_diff1
      value: 23.948152308265186
    - type: nauc_mrr_at_10_max
      value: 12.22420979621155
    - type: nauc_mrr_at_10_std
      value: 23.557939024705544
    - type: nauc_mrr_at_1_diff1
      value: 17.902334894536107
    - type: nauc_mrr_at_1_max
      value: 17.36969662861018
    - type: nauc_mrr_at_1_std
      value: 19.425714969048734
    - type: nauc_mrr_at_20_diff1
      value: 24.635893795899797
    - type: nauc_mrr_at_20_max
      value: 11.330541067194913
    - type: nauc_mrr_at_20_std
      value: 23.74518583400233
    - type: nauc_mrr_at_3_diff1
      value: 25.045536328282587
    - type: nauc_mrr_at_3_max
      value: 7.497967004732733
    - type: nauc_mrr_at_3_std
      value: 24.167153007320078
    - type: nauc_mrr_at_5_diff1
      value: 24.328479930592454
    - type: nauc_mrr_at_5_max
      value: 10.037126854938336
    - type: nauc_mrr_at_5_std
      value: 25.236208055346136
    - type: nauc_ndcg_at_1000_diff1
      value: 15.555347444667389
    - type: nauc_ndcg_at_1000_max
      value: 13.356591700655718
    - type: nauc_ndcg_at_1000_std
      value: 42.42395845935052
    - type: nauc_ndcg_at_100_diff1
      value: 13.110526060413708
    - type: nauc_ndcg_at_100_max
      value: 3.140006440162515
    - type: nauc_ndcg_at_100_std
      value: 39.02733288398033
    - type: nauc_ndcg_at_10_diff1
      value: 20.68853369009725
    - type: nauc_ndcg_at_10_max
      value: 2.435389817058852
    - type: nauc_ndcg_at_10_std
      value: 10.038202768784316
    - type: nauc_ndcg_at_1_diff1
      value: 20.17287594582385
    - type: nauc_ndcg_at_1_max
      value: 12.487205168273196
    - type: nauc_ndcg_at_1_std
      value: 20.639827614373075
    - type: nauc_ndcg_at_20_diff1
      value: 16.987577348502985
    - type: nauc_ndcg_at_20_max
      value: 2.9978717644469266
    - type: nauc_ndcg_at_20_std
      value: 13.015690866750354
    - type: nauc_ndcg_at_3_diff1
      value: 32.392223079245575
    - type: nauc_ndcg_at_3_max
      value: 1.587587110582544
    - type: nauc_ndcg_at_3_std
      value: 12.850592473446609
    - type: nauc_ndcg_at_5_diff1
      value: 32.80244517369626
    - type: nauc_ndcg_at_5_max
      value: 5.8939933777508084
    - type: nauc_ndcg_at_5_std
      value: 15.779687411463414
    - type: nauc_precision_at_1000_diff1
      value: -14.314031720452537
    - type: nauc_precision_at_1000_max
      value: 32.87886666567266
    - type: nauc_precision_at_1000_std
      value: 21.49347046886851
    - type: nauc_precision_at_100_diff1
      value: -9.4034008613839
    - type: nauc_precision_at_100_max
      value: 16.784075123309645
    - type: nauc_precision_at_100_std
      value: 73.14688535393604
    - type: nauc_precision_at_10_diff1
      value: 6.855101404043058
    - type: nauc_precision_at_10_max
      value: 6.52491228645612
    - type: nauc_precision_at_10_std
      value: 16.104602266016744
    - type: nauc_precision_at_1_diff1
      value: 17.902334894536107
    - type: nauc_precision_at_1_max
      value: 17.36969662861018
    - type: nauc_precision_at_1_std
      value: 19.425714969048734
    - type: nauc_precision_at_20_diff1
      value: -5.337534613602212
    - type: nauc_precision_at_20_max
      value: 17.722925454767218
    - type: nauc_precision_at_20_std
      value: 34.26680462132849
    - type: nauc_precision_at_3_diff1
      value: 31.054623397809255
    - type: nauc_precision_at_3_max
      value: -0.92038600946826
    - type: nauc_precision_at_3_std
      value: 8.326997076862916
    - type: nauc_precision_at_5_diff1
      value: 29.784942296920462
    - type: nauc_precision_at_5_max
      value: 6.337469263434779
    - type: nauc_precision_at_5_std
      value: 12.789597196020974
    - type: nauc_recall_at_1000_diff1
      value: -3.8177981862041364
    - type: nauc_recall_at_1000_max
      value: 14.206064332229163
    - type: nauc_recall_at_1000_std
      value: 74.18853420771269
    - type: nauc_recall_at_100_diff1
      value: 0.7677996771461106
    - type: nauc_recall_at_100_max
      value: -4.139924106878441
    - type: nauc_recall_at_100_std
      value: 48.319930706362896
    - type: nauc_recall_at_10_diff1
      value: 12.038835537494322
    - type: nauc_recall_at_10_max
      value: -2.0498983557854418
    - type: nauc_recall_at_10_std
      value: -2.0339180690854493
    - type: nauc_recall_at_1_diff1
      value: 27.853645380676824
    - type: nauc_recall_at_1_max
      value: 7.30739948053113
    - type: nauc_recall_at_1_std
      value: -0.2773663157814586
    - type: nauc_recall_at_20_diff1
      value: 0.7907893667756708
    - type: nauc_recall_at_20_max
      value: 0.8795499810558195
    - type: nauc_recall_at_20_std
      value: 11.512483291688282
    - type: nauc_recall_at_3_diff1
      value: 33.19440392639576
    - type: nauc_recall_at_3_max
      value: -1.5494237697432613
    - type: nauc_recall_at_3_std
      value: -8.560408808376984
    - type: nauc_recall_at_5_diff1
      value: 27.42193873870941
    - type: nauc_recall_at_5_max
      value: -4.74350293281128
    - type: nauc_recall_at_5_std
      value: -7.618060131179654
    - type: ndcg_at_1
      value: 42.857
    - type: ndcg_at_10
      value: 29.944
    - type: ndcg_at_100
      value: 42.624
    - type: ndcg_at_1000
      value: 53.384
    - type: ndcg_at_20
      value: 30.135
    - type: ndcg_at_3
      value: 34.847
    - type: ndcg_at_5
      value: 32.573
    - type: precision_at_1
      value: 44.897999999999996
    - type: precision_at_10
      value: 25.306
    - type: precision_at_100
      value: 8.694
    - type: precision_at_1000
      value: 1.616
    - type: precision_at_20
      value: 19.082
    - type: precision_at_3
      value: 34.014
    - type: precision_at_5
      value: 31.019999999999996
    - type: recall_at_1
      value: 3.064
    - type: recall_at_10
      value: 17.849999999999998
    - type: recall_at_100
      value: 53.217999999999996
    - type: recall_at_1000
      value: 87.095
    - type: recall_at_20
      value: 26.111
    - type: recall_at_3
      value: 7.383000000000001
    - type: recall_at_5
      value: 11.434
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB ToxicConversationsClassification
      revision: edfaf9da55d3dd50d43143d90c1ac476895ae6de
      split: test
      type: mteb/toxic_conversations_50k
    metrics:
    - type: accuracy
      value: 88.759765625
    - type: ap
      value: 36.49152357863017
    - type: ap_weighted
      value: 36.49152357863017
    - type: f1
      value: 74.4692714448641
    - type: f1_weighted
      value: 90.54372649306606
    - type: main_score
      value: 88.759765625
    task:
      type: Classification
  - dataset:
      config: default
      name: MTEB TweetSentimentExtractionClassification
      revision: d604517c81ca91fe16a244d1248fc021f9ecee7a
      split: test
      type: mteb/tweet_sentiment_extraction
    metrics:
    - type: accuracy
      value: 74.8443689869836
    - type: f1
      value: 75.1139662898148
    - type: f1_weighted
      value: 74.7369003946243
    - type: main_score
      value: 74.8443689869836
    task:
      type: Classification
  - dataset:
      config: default
      name: MTEB TwentyNewsgroupsClustering
      revision: 6125ec4e24fa026cec8a478383ee943acfbd5449
      split: test
      type: mteb/twentynewsgroups-clustering
    metrics:
    - type: main_score
      value: 61.42918790942448
    - type: v_measure
      value: 61.42918790942448
    - type: v_measure_std
      value: 1.0156550098843082
    task:
      type: Clustering
  - dataset:
      config: default
      name: MTEB TwitterSemEval2015
      revision: 70970daeab8776df92f5ea462b6173c0b46fd2d1
      split: test
      type: mteb/twittersemeval2015-pairclassification
    metrics:
    - type: cosine_accuracy
      value: 88.22197055492639
    - type: cosine_accuracy_threshold
      value: 83.30042362213135
    - type: cosine_ap
      value: 80.57754959194938
    - type: cosine_f1
      value: 73.70579190158894
    - type: cosine_f1_threshold
      value: 81.04978799819946
    - type: cosine_precision
      value: 71.64922770303936
    - type: cosine_recall
      value: 75.8839050131926
    - type: dot_accuracy
      value: 88.23985217857782
    - type: dot_accuracy_threshold
      value: 83.31039547920227
    - type: dot_ap
      value: 80.57533213448181
    - type: dot_f1
      value: 73.61309601143302
    - type: dot_f1_threshold
      value: 81.33968114852905
    - type: dot_precision
      value: 72.51087791144101
    - type: dot_recall
      value: 74.74934036939314
    - type: euclidean_accuracy
      value: 88.22197055492639
    - type: euclidean_accuracy_threshold
      value: 58.290231227874756
    - type: euclidean_ap
      value: 80.57982723880139
    - type: euclidean_f1
      value: 73.63426519620417
    - type: euclidean_f1_threshold
      value: 61.55576705932617
    - type: euclidean_precision
      value: 71.63173652694611
    - type: euclidean_recall
      value: 75.75197889182058
    - type: main_score
      value: 80.57982723880139
    - type: manhattan_accuracy
      value: 88.14448351910353
    - type: manhattan_accuracy_threshold
      value: 3907.2471618652344
    - type: manhattan_ap
      value: 80.3538079655539
    - type: manhattan_f1
      value: 73.40466675261054
    - type: manhattan_f1_threshold
      value: 4103.794097900391
    - type: manhattan_precision
      value: 71.76707839677337
    - type: manhattan_recall
      value: 75.11873350923483
    - type: max_ap
      value: 80.57982723880139
    - type: max_f1
      value: 73.70579190158894
    - type: max_precision
      value: 72.51087791144101
    - type: max_recall
      value: 75.8839050131926
    - type: similarity_accuracy
      value: 88.22197055492639
    - type: similarity_accuracy_threshold
      value: 83.30042362213135
    - type: similarity_ap
      value: 80.57754959194938
    - type: similarity_f1
      value: 73.70579190158894
    - type: similarity_f1_threshold
      value: 81.04978799819946
    - type: similarity_precision
      value: 71.64922770303936
    - type: similarity_recall
      value: 75.8839050131926
    task:
      type: PairClassification
  - dataset:
      config: default
      name: MTEB TwitterURLCorpus
      revision: 8b6510b0b1fa4e4c4f879467980e9be563ec1cdf
      split: test
      type: mteb/twitterurlcorpus-pairclassification
    metrics:
    - type: cosine_accuracy
      value: 89.88628866379477
    - type: cosine_accuracy_threshold
      value: 80.8050274848938
    - type: cosine_ap
      value: 87.57594591596816
    - type: cosine_f1
      value: 80.0812257707218
    - type: cosine_f1_threshold
      value: 77.990061044693
    - type: cosine_precision
      value: 76.93126197063205
    - type: cosine_recall
      value: 83.50015398829689
    - type: dot_accuracy
      value: 89.87852679784221
    - type: dot_accuracy_threshold
      value: 80.84419965744019
    - type: dot_ap
      value: 87.56136742222151
    - type: dot_f1
      value: 80.05898617511521
    - type: dot_f1_threshold
      value: 77.92385816574097
    - type: dot_precision
      value: 76.80554573106035
    - type: dot_recall
      value: 83.60024638127503
    - type: euclidean_accuracy
      value: 89.86882446540149
    - type: euclidean_accuracy_threshold
      value: 62.08193898200989
    - type: euclidean_ap
      value: 87.57517549192228
    - type: euclidean_f1
      value: 80.05286925872892
    - type: euclidean_f1_threshold
      value: 66.65036082267761
    - type: euclidean_precision
      value: 76.51063232507545
    - type: euclidean_recall
      value: 83.93902063443178
    - type: main_score
      value: 87.64162614197194
    - type: manhattan_accuracy
      value: 89.8959909962355
    - type: manhattan_accuracy_threshold
      value: 4176.108169555664
    - type: manhattan_ap
      value: 87.64162614197194
    - type: manhattan_f1
      value: 80.17116279069768
    - type: manhattan_f1_threshold
      value: 4433.153533935547
    - type: manhattan_precision
      value: 77.57615035644848
    - type: manhattan_recall
      value: 82.94579611949491
    - type: max_ap
      value: 87.64162614197194
    - type: max_f1
      value: 80.17116279069768
    - type: max_precision
      value: 77.57615035644848
    - type: max_recall
      value: 83.93902063443178
    - type: similarity_accuracy
      value: 89.88628866379477
    - type: similarity_accuracy_threshold
      value: 80.8050274848938
    - type: similarity_ap
      value: 87.57594591596816
    - type: similarity_f1
      value: 80.0812257707218
    - type: similarity_f1_threshold
      value: 77.990061044693
    - type: similarity_precision
      value: 76.93126197063205
    - type: similarity_recall
      value: 83.50015398829689
    task:
      type: PairClassification
tags:
- mteb
---


# Updates

New open-source models and ToDoList will be listed on https://github.com/DunZhang/Stella/blob/main/news_and_todo.md.

You can also find these models on my [homepage](https://huggingface.co/infgrad).

# Introduction

The models are trained based on `Alibaba-NLP/gte-large-en-v1.5` and `Alibaba-NLP/gte-Qwen2-1.5B-instruct`. Thanks for
their contributions!

**We simplify usage of prompts, providing two prompts for most general tasks, one is for s2p, another one is for s2s.**

Prompt of s2p task(e.g. retrieve task):

```text
Instruct: Given a web search query, retrieve relevant passages that answer the query.\nQuery: {query}
```

Prompt of s2s task(e.g. semantic textual similarity task):

```text
Instruct: Retrieve semantically similar text.\nQuery: {query}
```

The models are finally trained by [MRL]((https://arxiv.org/abs/2205.13147)), so they have multiple dimensions: 512, 768,
1024, 2048, 4096, 6144 and 8192.

The higher the dimension, the better the performance.
**Generally speaking, 1024d is good enough.** The MTEB score of 1024d is only 0.001 lower than 8192d.

# Model directory structure

The model directory structure is very simple, it is a standard SentenceTransformer directory **with a series
of `2_Dense_{dims}`
folders**, where `dims` represents the final vector dimension.

For example, the `2_Dense_256` folder stores Linear weights that convert vector dimensions to 256 dimensions.
Please refer to the following chapters for specific instructions on how to use them.

# Usage

You can use `SentenceTransformer` or `transformer` library to encode text.

```python
import os
import torch
from transformers import AutoModel, AutoTokenizer
from sentence_transformers import SentenceTransformer
from sklearn.preprocessing import normalize

prompt = "Instruct: Given a web search query, retrieve relevant passages that answer the query.\nQuery: {query}"
queries = ["query1", "query2"]
queries = [prompt.replace("{query}", query) for query in queries]

# doc do not need any prompts
docs = ["doc1", "doc2"]

model_dir = "{Your MODEL_PATH}"

#### method1: SentenceTransformer
# ！！！！The default dimension is 8192，if you need other dimensions, please copy the files from the `2_Dense_{dims}` folder to overwrite them. For example, `copy -r ./2_Dense_1024/* ./2_Dense/` ！！！！
model = SentenceTransformer(model_dir, trust_remote_code=True).cuda()
vectors = model.encode(queries, convert_to_numpy=True, normalize_embeddings=True)
print(vectors.shape)
print(vectors[:, :4])

#### method2：transformers
vector_linear_directory = "2_Dense"
vector_dim = 8192
model = AutoModel.from_pretrained(model_dir, trust_remote_code=True).cuda().eval()
tokenizer = AutoTokenizer.from_pretrained(model_dir, trust_remote_code=True)
vector_linear = torch.nn.Linear(in_features=model.config.hidden_size, out_features=vector_dim)
vector_linear_dict = {
    k.replace("linear.", ""): v for k, v in
    torch.load(os.path.join(model_dir, f"{vector_linear_directory}/pytorch_model.bin")).items()
}
vector_linear.load_state_dict(vector_linear_dict)
vector_linear.cuda()
with torch.no_grad():
    input_data = tokenizer(queries, padding="longest", truncation=True, max_length=512, return_tensors="pt")
    input_data = {k: v.cuda() for k, v in input_data.items()}
    attention_mask = input_data["attention_mask"]
    last_hidden_state = model(**input_data)[0]
    last_hidden = last_hidden_state.masked_fill(~attention_mask[..., None].bool(), 0.0)
    vectors = last_hidden.sum(dim=1) / attention_mask.sum(dim=1)[..., None]
    vectors = normalize(vector_linear(vectors).cpu().numpy())
print(vectors.shape)
print(vectors[:, :4])

```

# FAQ

Q: The details of training?

A: The training method and datasets will be released in the future. (specific time unknown, may be provided in a paper)

Q: How to choose a suitable prompt for my own task?

A: In most cases, please use the s2p and s2s prompts. These two prompts account for the vast majority of the training
data.

Q: How to reproduce MTEB results?

A: Please use evaluation scripts in `Alibaba-NLP/gte-Qwen2-1.5B-instruct` or `intfloat/e5-mistral-7b-instruct`

Q: Why each dimension has a linear weight?

A: MRL has multiple training methods, we choose this method which has the best performance.

Q: What is the sequence length of models?

A: 512 is recommended, in our experiments, almost all models perform poorly on specialized long text retrieval datasets. Besides, the
model is trained on datasets of 512 length. This may be an optimization term.

If you have any questions, please start a discussion on community.