# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|106.6488|106.0087|-0.6401|-0.6%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|33354.5501|108.4098|-33246.1403|-99.67%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|27357.0383|458.0777|-26898.9606|-98.33%|
|migraphx_ORT__distilgpt2_1|PASS|progression|249006.7839|58.8161|-248947.9678|-99.98%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|62444.7149|60.9848|-62383.7302|-99.9%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|16196.7202|239.5074|-15957.2128|-98.52%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|36.7135|33.8411|-2.8724|-7.82%|
|migraphx_agentmodel__AgentModel|Numerics|progression|2.1817|1.9756|-0.2061|-9.45%|
|migraphx_bert__bert-large-uncased|PASS|within tol|18.9857|18.9934|0.0077|0.04%|
|migraphx_cadene__dpn92i1|PASS|regression|5.0533|5.4614|0.408|8.07%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|29.5092|29.2953|-0.2139|-0.72%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|6.2805|6.2561|-0.0244|-0.39%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|29.8421|29.7133|-0.1289|-0.43%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.1351|7.0832|-0.0519|-0.73%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|29.1661|27.3609|-1.8053|-6.19%|
|migraphx_mlperf__resnet50_v1|PASS|progression|5.2436|4.7777|-0.4659|-8.89%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|43.6424|44.0056|0.3632|0.83%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|46.3967|46.7473|0.3506|0.76%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|17.3371|18.1575|0.8203|4.73%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|8.0024|7.9532|-0.0492|-0.61%|
|migraphx_torchvision__densenet121i32|PASS|within tol|18.0183|18.0167|-0.0016|-0.01%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.9135|4.9063|-0.0071|-0.15%|
|migraphx_torchvision__inceptioni32|PASS|within tol|28.1657|28.1037|-0.0619|-0.22%|
|migraphx_torchvision__resnet50i1|PASS|within tol|3.5828|3.56|-0.0227|-0.63%|
|migraphx_torchvision__resnet50i64|PASS|within tol|20.9186|20.8095|-0.1091|-0.52%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|25.5427|25.6768|0.1341|0.53%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|37.6983|37.7962|0.0979|0.26%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|57.8863|57.8045|-0.0818|-0.14%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.6074|12.1578|-0.4495|-3.57%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.4385|12.3511|-0.0875|-0.7%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.077|19.0038|-0.0732|-0.38%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.4321|12.3472|-0.085|-0.68%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.065|18.7221|-0.3429|-1.8%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|19.5653|19.503|-0.0623|-0.32%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|36.2001|36.1455|-0.0545|-0.15%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|71.8472|72.1299|0.2827|0.39%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|112.3466|113.5034|1.1568|1.03%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.2059|19.1389|-0.067|-0.35%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|19.8337|19.8388|0.0051|0.03%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|23.7731|23.1695|-0.6036|-2.54%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|19.8834|19.9976|0.1143|0.57%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.0354|26.0856|0.0501|0.19%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|33.1463|33.2494|0.1031|0.31%|

## No Regressions Found

## No Progressions Found

