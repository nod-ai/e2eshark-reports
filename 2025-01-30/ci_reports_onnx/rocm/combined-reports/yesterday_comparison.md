# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|108.0088|106.1075|-1.9014|-1.76%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|107.9622|105.8246|-2.1376|-1.98%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|1189.7704|467.0218|-722.7487|-60.75%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|58.0489|57.1207|-0.9282|-1.6%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|64.1313|62.7029|-1.4284|-2.23%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|273.819|268.3473|-5.4717|-2.0%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.4628|33.7669|-0.6959|-2.02%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.4022|18.8607|-0.5415|-2.79%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.1245|6.9446|-0.1799|-2.52%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|55.7116|27.0294|-28.6822|-51.48%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|44.2181|42.6908|-1.5273|-3.45%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|143.014|142.5906|-0.4234|-0.3%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|18.0578|17.7569|-0.3009|-1.67%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|9.4439|6.6451|-2.7988|-29.64%|
|migraphx_torchvision__inceptioni1|PASS|within tol|60.9876|61.0002|0.0126|0.02%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|32.5203|31.5563|-0.964|-2.96%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|54.6723|53.3968|-1.2755|-2.33%|
|migx_bench_bert-large-uncased_16_384|Numerics|progression|84.0034|69.93|-14.0734|-16.75%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|47.7605|11.9233|-35.8371|-75.04%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.6312|12.2179|-0.4133|-3.27%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.4529|19.0708|-0.3821|-1.96%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.7226|12.8968|0.1741|1.37%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.262|13.5578|0.2958|2.23%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.2245|20.745|-0.4794|-2.26%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|67.0982|65.6473|-1.4509|-2.16%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|100.1944|98.0734|-2.121|-2.12%|
|migx_bench_bert-large-uncased_32_384|Numerics|progression|148.5016|138.7628|-9.7388|-6.56%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.3493|14.2615|-0.0878|-0.61%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|16.7647|16.4909|-0.2738|-1.63%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.26|25.9216|-0.3383|-1.29%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|19.1491|18.9072|-0.2419|-1.26%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.3562|26.2691|-1.0871|-3.97%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|40.6284|39.1913|-1.4372|-3.54%|

## No Regressions Found

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|migraphx_mlperf__resnet50_v1|compilation|Numerics|

