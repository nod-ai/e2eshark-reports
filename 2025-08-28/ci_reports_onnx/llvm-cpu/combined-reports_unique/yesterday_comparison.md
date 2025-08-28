# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|271.5351|75.8451|-195.69|-72.07%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|209.7386|75.7314|-134.0072|-63.89%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|729.1955|232.3661|-496.8294|-68.13%|
|migraphx_ORT__distilgpt2_1|PASS|progression|78.1823|28.2609|-49.9214|-63.85%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|353.6352|98.0428|-255.5924|-72.28%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|710.2558|263.074|-447.1818|-62.96%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|89.3512|46.0211|-43.3302|-48.49%|
|migraphx_bert__bert-large-uncased|PASS|within tol|368.2974|368.2873|-0.0101|-0.0%|
|migraphx_cadene__dpn92i1|PASS|regression|169.4309|183.8986|14.4677|8.54%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5372.8189|5305.9003|-66.9187|-1.25%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|316.5025|325.4318|8.9294|2.82%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|494.7667|437.3374|-57.4293|-11.61%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|609.9032|446.4525|-163.4507|-26.8%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|95.3747|93.1705|-2.2042|-2.31%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|60.6554|32.9671|-27.6883|-45.65%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|214.1322|191.0291|-23.103|-10.79%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|82.4969|65.1952|-17.3016|-20.97%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|22.4371|21.7085|-0.7286|-3.25%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1592.682|1536.5491|-56.1329|-3.52%|
|migraphx_torchvision__inceptioni1|PASS|progression|227.5839|202.9955|-24.5884|-10.8%|
|migraphx_torchvision__resnet50i1|PASS|progression|98.3367|90.9189|-7.4179|-7.54%|
|migx_bench_bert-large-uncased_16_128|PASS|progression|1792.9719|1537.1317|-255.8402|-14.27%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5443.9905|5221.7564|-222.2341|-4.08%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9569.1981|9432.6012|-136.5969|-1.43%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|149.4971|145.8343|-3.6628|-2.45%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|426.4872|251.1498|-175.3374|-41.11%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|382.908|360.1375|-22.7705|-5.95%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|245.6805|241.7825|-3.898|-1.59%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|471.576|428.3362|-43.2398|-9.17%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|651.3348|653.8565|2.5216|0.39%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5138.3938|4960.9175|-177.4763|-3.45%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|13928.4917|13605.2374|-323.2543|-2.32%|
|migx_bench_bert-large-uncased_32_384|Numerics|progression|23674.1796|21981.0272|-1693.1524|-7.15%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|407.2898|404.9637|-2.3262|-0.57%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|821.2128|792.5787|-28.6341|-3.49%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|1294.6171|1225.0351|-69.582|-5.37%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|742.9678|743.57|0.6022|0.08%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1626.9508|1657.8442|30.8934|1.9%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3333.5744|3350.3266|16.7522|0.5%|

## 11 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|model--MTL-distilbert-base-uncased-squad--jgammack|PASS|compilation|
|model--bert-engonly-sentiment-test--SiddharthaM|PASS|compilation|
|model--distilBERT-infoExtract--tony4194|PASS|compilation|
|model--distilbert-base-NER--51la5|PASS|compilation|
|model--distilbert-base-cased-distilled-squad--distilbert|PASS|compilation|
|model--distilbert-base-german-cased-finetuned-ner--FabianWillner|PASS|compilation|
|model--distilbert-base-multilingual-cased-finetuned-squad--monakth|PASS|compilation|
|model--distilbert-base-uncased-finetuned-ner--dbsamu|PASS|compilation|
|model--distilbert-srb-ner--Aleksandar|PASS|compilation|
|model--finetuning-sentiment-imdb--Timothy1337|PASS|compilation|
|model--finetuning-sentiment-model-3000-samples--DuboiJ|PASS|compilation|

## 5 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|convbert_Opset16_transformers|compilation|PASS|
|convbert_Opset17_transformers|compilation|PASS|
|mvitv2_base|compilation|Numerics|
|mvitv2_small|compilation|Numerics|
|mvitv2_tiny|compilation|Numerics|

