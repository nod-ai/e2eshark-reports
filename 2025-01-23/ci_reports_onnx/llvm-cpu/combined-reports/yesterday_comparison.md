# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|316.0892|86.5177|-229.5715|-72.63%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|88.3764|104.7788|16.4024|18.56%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|257.3437|551.4142|294.0705|114.27%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|32.1769|31.1537|-1.0232|-3.18%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|85.6786|83.8933|-1.7853|-2.08%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|251.2444|357.2686|106.0242|42.2%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|39.2839|42.9277|3.6438|9.28%|
|migraphx_bert__bert-large-uncased|PASS|within tol|370.9885|386.6633|15.6748|4.23%|
|migraphx_cadene__dpn92i1|PASS|progression|188.3243|164.8382|-23.4861|-12.47%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5270.3503|5424.8068|154.4565|2.93%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|323.2081|368.4533|45.2452|14.0%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5030.2179|5067.1839|36.966|0.73%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|380.6691|376.9841|-3.685|-0.97%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|481.0273|445.4785|-35.5488|-7.39%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|95.0616|91.1688|-3.8928|-4.1%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|32.591|31.7365|-0.8545|-2.62%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|178.9|182.2197|3.3197|1.86%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|82.3244|170.9736|88.6492|107.68%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|47.8541|42.7938|-5.0603|-10.57%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1572.0151|1573.0265|1.0114|0.06%|
|migraphx_torchvision__inceptioni1|PASS|progression|231.7039|194.9643|-36.7396|-15.86%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5345.1872|5363.9508|18.7636|0.35%|
|migraphx_torchvision__resnet50i1|PASS|regression|85.8666|90.6828|4.8162|5.61%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5996.0105|6058.0197|62.0092|1.03%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2627.1869|2728.6056|101.4188|3.86%|
|migx_bench_bert-large-uncased_16_256|PASS|progression|5036.1442|4150.6378|-885.5064|-17.58%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5766.4796|5665.1267|-101.3529|-1.76%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|160.2202|156.5047|-3.7155|-2.32%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|307.3985|262.5742|-44.8243|-14.58%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|380.7842|396.3209|15.5366|4.08%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|404.3908|383.1536|-21.2373|-5.25%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|586.8256|618.1456|31.3201|5.34%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|828.0356|876.2057|48.1701|5.82%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5048.9124|4946.4058|-102.5067|-2.03%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|7785.743|8054.5409|268.7979|3.45%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11194.2393|11354.5662|160.3269|1.43%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|711.8375|703.5675|-8.27|-1.16%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1062.964|1091.2601|28.2961|2.66%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1501.3643|1516.3018|14.9375|0.99%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|1295.2564|1442.9367|147.6803|11.4%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2062.9427|2060.9935|-1.9492|-0.09%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2840.7831|2883.2058|42.4228|1.49%|

## No Regressions Found

## No Progressions Found

