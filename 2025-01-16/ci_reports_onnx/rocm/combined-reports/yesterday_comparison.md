# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|106.7912|104.9154|-1.8759|-1.76%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|106.956|104.2585|-2.6975|-2.52%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|469.9882|468.659|-1.3292|-0.28%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|60.8035|59.9171|-0.8865|-1.46%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|66.5975|64.8662|-1.7313|-2.6%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|278.3697|272.163|-6.2067|-2.23%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|32.5886|32.1215|-0.4671|-1.43%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.48|19.4497|-0.0304|-0.16%|
|migraphx_cadene__dpn92i1|Numerics|within tol|64.436|64.7155|0.2795|0.43%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|154.7808|154.1809|-0.5999|-0.39%|
|migraphx_cadene__resnext101_64x4di1|Numerics|within tol|173.6102|173.5548|-0.0554|-0.03%|
|migraphx_cadene__resnext101_64x4di16|Numerics|within tol|391.2444|387.5817|-3.6627|-0.94%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.2965|7.1895|-0.107|-1.47%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|25.3623|24.8883|-0.4739|-1.87%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|43.5477|42.8731|-0.6746|-1.55%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|144.3968|142.8684|-1.5284|-1.06%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|15.657|16.6375|0.9805|6.26%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|6.0838|7.9748|1.891|31.08%|
|migraphx_torchvision__densenet121i32|Numerics|within tol|70.0343|69.0149|-1.0194|-1.46%|
|migraphx_torchvision__inceptioni1|PASS|within tol|62.3198|62.2161|-0.1037|-0.17%|
|migraphx_torchvision__inceptioni32|PASS|within tol|106.4352|105.7796|-0.6556|-0.62%|
|migraphx_torchvision__resnet50i1|Numerics|within tol|17.0042|17.124|0.1199|0.7%|
|migraphx_torchvision__resnet50i64|Numerics|within tol|149.7679|148.077|-1.6909|-1.13%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|34.7524|33.4837|-1.2686|-3.65%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|58.7717|57.0522|-1.7195|-2.93%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|78.4374|75.8827|-2.5547|-3.26%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.0885|12.1022|0.0138|0.11%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.6976|12.7756|0.0779|0.61%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.6719|19.6206|-0.0512|-0.26%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.8294|12.8439|0.0144|0.11%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.402|13.3652|-0.0369|-0.28%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.8711|21.6407|-0.2303|-1.05%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|69.7849|69.0899|-0.695|-1.0%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|107.8695|104.6748|-3.1947|-2.96%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|159.378|154.1271|-5.2508|-3.29%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.4559|14.4459|-0.01|-0.07%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|17.5615|17.0856|-0.4758|-2.71%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|27.5827|27.0122|-0.5705|-2.07%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.1661|19.6553|-0.5108|-2.53%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|29.0643|28.1444|-0.9199|-3.16%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|43.3259|42.1224|-1.2034|-2.78%|

## One Regression Found:

|model name|old_status|new_status|
|---|---|---|
|mvitv2_small|PASS|compilation|

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|pit_s_distilled_224|compilation|PASS|

