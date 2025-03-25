# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|117.2693|117.1399|-0.1294|-0.11%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|116.4475|116.7285|0.2809|0.24%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|523.4457|522.8982|-0.5475|-0.1%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|68.1661|69.208|1.0419|1.53%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|63.5595|63.8649|0.3054|0.48%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|331.7657|332.4008|0.6351|0.19%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.834|35.067|0.233|0.67%|
|migraphx_agentmodel__AgentModel|Numerics|regression|1.7838|1.9493|0.1655|9.28%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.7626|19.8313|0.0687|0.35%|
|migraphx_cadene__dpn92i1|PASS|within tol|5.0452|5.0534|0.0082|0.16%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|29.7778|29.3458|-0.4319|-1.45%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|5.8986|6.0094|0.1108|1.88%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|29.8243|29.5845|-0.2398|-0.8%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.3677|7.0964|-0.2713|-3.68%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|26.776|27.6765|0.9004|3.36%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|4.7766|5.0093|0.2327|4.87%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|39.9726|40.2264|0.2538|0.64%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|48.382|46.7591|-1.6228|-3.35%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|17.2018|17.5147|0.3129|1.82%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|6.0581|9.009|2.9509|48.71%|
|migraphx_torchvision__densenet121i32|PASS|within tol|17.8482|17.9842|0.136|0.76%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.869|4.8879|0.0189|0.39%|
|migraphx_torchvision__inceptioni32|PASS|within tol|28.1792|28.0343|-0.1449|-0.51%|
|migraphx_torchvision__resnet50i1|PASS|regression|3.1898|3.7584|0.5685|17.82%|
|migraphx_torchvision__resnet50i64|PASS|within tol|20.7608|20.6596|-0.1012|-0.49%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|27.5105|27.8119|0.3014|1.1%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|39.4089|39.2676|-0.1412|-0.36%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|59.4938|60.7276|1.2338|2.07%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|11.9466|12.2664|0.3198|2.68%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.4612|12.4699|0.0087|0.07%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.4164|19.3727|-0.0437|-0.22%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.548|12.5963|0.0483|0.39%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.5009|19.4012|-0.0997|-0.51%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.5468|20.5879|0.0411|0.2%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|37.8733|37.8856|0.0123|0.03%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|79.943|79.8018|-0.1411|-0.18%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|121.8958|122.3364|0.4407|0.36%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.4973|19.6311|0.1338|0.69%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.9746|21.0974|0.1228|0.59%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|24.8369|24.5823|-0.2547|-1.03%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|21.0774|21.2019|0.1245|0.59%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|28.1358|28.1641|0.0283|0.1%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|35.6541|36.1435|0.4894|1.37%|

## 3 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|coatnet_2_rw_224.sw_in12k|PASS|Numerics|
|model--Learning-sentiment-analysis-through-imdb-ds--SeNSiTivE|PASS|Numerics|
|model--m2m100_418M-finetuned-kde4-en-to-pt_BR--danhsf|PASS|Numerics|

## No Progressions Found

