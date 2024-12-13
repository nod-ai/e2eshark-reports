# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|97.6794|98.5099|0.8305|0.85%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|143.4788|98.6938|-44.785|-31.21%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|498.6834|496.6267|-2.0567|-0.41%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|53.5052|53.3837|-0.1214|-0.23%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|61.6097|61.5175|-0.0921|-0.15%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|270.2742|264.1973|-6.0769|-2.25%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|31.1684|30.8923|-0.2762|-0.89%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.5178|19.5344|0.0166|0.08%|
|migraphx_bert__bertsquad-12|PASS|within tol|7.7931|7.6325|-0.1606|-2.06%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|159.6211|159.5249|-0.0961|-0.06%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|185.4601|185.4665|0.0064|0.0%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|9.7533|7.2223|-2.5309|-25.95%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|24.9989|24.9989|0.0|0.0%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|6.0782|6.1233|0.0451|0.74%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|116.104|39.6276|-76.4764|-65.87%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|46.9677|46.9637|-0.004|-0.01%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|18.1158|14.9241|-3.1917|-17.62%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|6.3886|7.7407|1.3521|21.16%|
|migraphx_torchvision__densenet121i32|PASS|progression|83.0635|71.6195|-11.444|-13.78%|
|migraphx_torchvision__inceptioni1|PASS|regression|21.0498|96.8217|75.7719|359.97%|
|migraphx_torchvision__inceptioni32|PASS|within tol|137.0343|136.7435|-0.2908|-0.21%|
|migraphx_torchvision__resnet50i64|PASS|within tol|166.2221|166.024|-0.1981|-0.12%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|33.7214|33.6822|-0.0392|-0.12%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|58.9535|58.9102|-0.0432|-0.07%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|74.951|74.835|-0.116|-0.15%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.117|13.1244|0.0075|0.06%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.1306|13.246|0.1153|0.88%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.428|19.4655|0.0374|0.19%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.8732|12.9075|0.0344|0.27%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.5163|13.4572|-0.059|-0.44%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.3609|21.3369|-0.0239|-0.11%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|70.6411|70.6285|-0.0125|-0.02%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|107.1181|107.0307|-0.0874|-0.08%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|149.2199|149.0779|-0.142|-0.1%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.4801|14.4661|-0.014|-0.1%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|36.653|17.3266|-19.3264|-52.73%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.6558|27.3892|0.7333|2.75%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|19.9508|19.8435|-0.1073|-0.54%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|28.1284|28.1912|0.0628|0.22%|
|migx_bench_bert-large-uncased_8_384|PASS|progression|45.2793|41.8152|-3.4642|-7.65%|

## No Regressions Found

## 3 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|model--marian-finetuned-kde4-en-to-fr--amartyobanerjee|Numerics|PASS|
|model--spanbert-base-cased-few-shot-k-32-finetuned-squad-seed-10--anas-awadalla|Numerics|PASS|
|model--vmehlin_distilbert-finetuned-squad--vanme|Numerics|PASS|

