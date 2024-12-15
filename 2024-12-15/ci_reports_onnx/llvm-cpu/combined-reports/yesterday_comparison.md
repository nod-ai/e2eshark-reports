# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|90.8713|87.5157|-3.3556|-3.69%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|87.752|85.0333|-2.7187|-3.1%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|253.6789|258.0792|4.4003|1.73%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|30.4876|30.7278|0.2403|0.79%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|84.4226|88.9658|4.5432|5.38%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|244.3155|248.6222|4.3067|1.76%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|43.075|52.3164|9.2414|21.45%|
|migraphx_bert__bert-large-uncased|PASS|progression|407.5057|375.3887|-32.117|-7.88%|
|migraphx_bert__bertsquad-12|PASS|within tol|85.4887|89.3944|3.9057|4.57%|
|migraphx_cadene__dpn92i1|PASS|within tol|174.9017|175.2435|0.3418|0.2%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5940.3475|5794.5377|-145.8098|-2.45%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|353.9452|337.6519|-16.2933|-4.6%|
|migraphx_cadene__resnext101_64x4di16|PASS|regression|5173.375|5474.2719|300.897|5.82%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|389.396|380.7048|-8.6912|-2.23%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|441.186|433.5501|-7.6359|-1.73%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|87.9021|90.8172|2.915|3.32%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|31.7997|32.6425|0.8428|2.65%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|194.1748|278.0565|83.8818|43.2%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|112.063|83.3182|-28.7448|-25.65%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|43.104|46.9026|3.7986|8.81%|
|migraphx_torchvision__densenet121i32|PASS|progression|1785.3344|1624.4999|-160.8345|-9.01%|
|migraphx_torchvision__inceptioni1|PASS|within tol|203.3006|203.0027|-0.2979|-0.15%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5872.5554|5926.675|54.1196|0.92%|
|migraphx_torchvision__resnet50i1|PASS|within tol|85.9645|87.126|1.1615|1.35%|
|migraphx_torchvision__resnet50i64|PASS|within tol|6027.3714|5970.224|-57.1474|-0.95%|
|migx_bench_bert-large-uncased_16_128|PASS|progression|2666.3104|2518.0225|-148.2879|-5.56%|
|migx_bench_bert-large-uncased_16_256|PASS|progression|4399.8424|4173.4586|-226.3838|-5.15%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5893.4285|5724.1341|-169.2944|-2.87%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|168.2351|161.467|-6.7681|-4.02%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|263.714|289.7519|26.0379|9.87%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|366.8157|373.8116|6.9959|1.91%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|400.9772|429.3175|28.3403|7.07%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|630.2853|633.9986|3.7133|0.59%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|824.0976|800.8108|-23.2868|-2.83%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5151.8158|5109.2564|-42.5594|-0.83%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8158.8374|8099.4264|-59.411|-0.73%|
|migx_bench_bert-large-uncased_32_384|Numerics|progression|12273.8599|11364.87|-908.9899|-7.41%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|705.1223|701.7126|-3.4097|-0.48%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1097.3568|1075.3553|-22.0016|-2.0%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|1615.9651|1516.4968|-99.4683|-6.16%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1468.6469|1475.9714|7.3245|0.5%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|2067.6784|2277.293|209.6146|10.14%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2881.313|2835.9332|-45.3798|-1.57%|

## No Regressions Found

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|xcit_nano_12_p16_224|Numerics|PASS|

