# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|103.2997|93.7953|-9.5044|-9.2%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|88.5885|95.0403|6.4518|7.28%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|437.8921|280.1274|-157.7648|-36.03%|
|migraphx_ORT__distilgpt2_1|PASS|progression|36.273|29.8679|-6.4051|-17.66%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|85.515|85.5621|0.0471|0.06%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|262.8737|249.0118|-13.8619|-5.27%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|41.4548|39.6749|-1.7799|-4.29%|
|migraphx_agentmodel__AgentModel|Numerics|regression|1.1335|1.2085|0.075|6.61%|
|migraphx_bert__bert-large-uncased|PASS|within tol|385.0846|385.6719|0.5872|0.15%|
|migraphx_cadene__dpn92i1|PASS|within tol|168.6049|164.2473|-4.3576|-2.58%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5512.2636|5523.6181|11.3545|0.21%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|319.1209|329.1116|9.9907|3.13%|
|migraphx_cadene__resnext101_64x4di16|PASS|regression|5019.0306|5947.2453|928.2147|18.49%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|408.8359|405.6228|-3.2132|-0.79%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|424.3165|429.6432|5.3267|1.26%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|95.6426|96.3923|0.7497|0.78%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|30.9707|46.2907|15.3201|49.47%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|179.6917|185.1168|5.4251|3.02%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|88.8424|73.8956|-14.9468|-16.82%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|44.1178|46.0277|1.9099|4.33%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1493.5831|1555.2953|61.7121|4.13%|
|migraphx_torchvision__inceptioni1|PASS|regression|200.0485|211.0803|11.0318|5.51%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5766.6281|5847.7441|81.1161|1.41%|
|migraphx_torchvision__resnet50i1|PASS|within tol|90.8226|87.1547|-3.6679|-4.04%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5428.3199|5477.2962|48.9763|0.9%|
|migx_bench_bert-large-uncased_16_128|PASS|progression|2650.3482|1624.5271|-1025.8211|-38.71%|
|migx_bench_bert-large-uncased_16_256|PASS|progression|4087.5658|2983.4854|-1104.0805|-27.01%|
|migx_bench_bert-large-uncased_16_384|Numerics|progression|5843.0735|4892.5365|-950.537|-16.27%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|168.0857|150.6327|-17.4531|-10.38%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|268.3661|250.6552|-17.7109|-6.6%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|379.1812|374.8319|-4.3493|-1.15%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|382.5437|236.4836|-146.0601|-38.18%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|582.2661|448.3504|-133.9157|-23.0%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|820.371|655.5266|-164.8444|-20.09%|
|migx_bench_bert-large-uncased_32_128|PASS|progression|5081.4056|2810.8615|-2270.5441|-44.68%|
|migx_bench_bert-large-uncased_32_256|PASS|progression|8551.9135|5869.0566|-2682.8569|-31.37%|
|migx_bench_bert-large-uncased_32_384|Numerics|progression|11253.5777|9429.077|-1824.5007|-16.21%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|744.6127|407.5545|-337.0582|-45.27%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|1101.108|797.5468|-303.5612|-27.57%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|1564.2564|1254.7033|-309.5531|-19.79%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|1305.01|734.8352|-570.1748|-43.69%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|2099.0933|1534.499|-564.5942|-26.9%|
|migx_bench_bert-large-uncased_8_384|PASS|progression|3088.0083|2428.4467|-659.5616|-21.36%|

## 3 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|model--Bartlarge--Shubham09|PASS|Numerics|
|resnet10t_train_vaiq|PASS|Numerics|
|resnet14t_train_vaiq|PASS|Numerics|

## 14 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|model--deberta-italian-question-answering--osiria|Numerics|PASS|
|model--deberta-v3-base-qa-en--LLukas22|Numerics|PASS|
|model--deberta-v3-base-squad2--deepset|Numerics|PASS|
|model--deberta-v3-base-squad2--navteca|Numerics|PASS|
|model--deberta-v3-base__sst2__all-train--SetFit|Numerics|PASS|
|model--deberta-v3-large-squad2--deepset|Numerics|PASS|
|model--deberta-v3-large-squad2--sjrhuschlee|Numerics|PASS|
|model--deberta-v3-xsmall-squad2--nlpconnect|Numerics|PASS|
|model--deberta_squadnewsqa--sophiebottani|Numerics|PASS|
|model--mdeberta-v3-base-squad2--sjrhuschlee|Numerics|PASS|
|model--microsoft-deberta-v3-large_ner_conll2003--Gladiator|Numerics|PASS|
|model--outputs--ankitkupadhyay|Numerics|PASS|
|model--pegasus-large-booksum--cnicu|Numerics|PASS|
|model--reward-model-deberta-v3-large-v2--OpenAssistant|Numerics|PASS|

