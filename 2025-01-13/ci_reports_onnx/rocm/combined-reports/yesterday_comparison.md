# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|550.9856|99.0166|-451.9689|-82.03%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|552.7894|101.8009|-450.9886|-81.58%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|2455.3515|504.738|-1950.6136|-79.44%|
|migraphx_ORT__distilgpt2_1|PASS|progression|279.2746|52.3639|-226.9107|-81.25%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|343.5054|61.0983|-282.407|-82.21%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|1773.2744|303.236|-1470.0384|-82.9%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|168.6865|31.1346|-137.5519|-81.54%|
|migraphx_bert__bert-large-uncased|PASS|progression|106.1678|19.3055|-86.8622|-81.82%|
|migraphx_cadene__dpn92i1|Numerics|progression|176.9268|42.614|-134.3129|-75.91%|
|migraphx_cadene__inceptionv4i16|PASS|progression|589.8728|155.892|-433.9807|-73.57%|
|migraphx_cadene__resnext101_64x4di1|Numerics|progression|484.0452|118.184|-365.8611|-75.58%|
|migraphx_cadene__resnext101_64x4di16|Numerics|progression|1959.4795|388.8154|-1570.6642|-80.16%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|33.9845|7.2126|-26.7719|-78.78%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|135.5171|24.717|-110.8001|-81.76%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|189.1269|33.4194|-155.7075|-82.33%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|766.7576|140.3432|-626.4144|-81.7%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|85.9321|15.6975|-70.2346|-81.73%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|39.1959|6.6718|-32.5241|-82.98%|
|migraphx_torchvision__densenet121i32|Numerics|progression|278.1864|73.92|-204.2664|-73.43%|
|migraphx_torchvision__inceptioni1|PASS|progression|187.9186|41.161|-146.7576|-78.1%|
|migraphx_torchvision__inceptioni32|PASS|progression|481.4043|107.1674|-374.2369|-77.74%|
|migraphx_torchvision__resnet50i1|Numerics|progression|84.9594|12.203|-72.7564|-85.64%|
|migraphx_torchvision__resnet50i64|Numerics|progression|666.6741|152.0062|-514.6679|-77.2%|
|migx_bench_bert-large-uncased_16_128|PASS|progression|193.0014|35.3169|-157.6845|-81.7%|
|migx_bench_bert-large-uncased_16_256|PASS|progression|479.7287|58.2498|-421.4789|-87.86%|
|migx_bench_bert-large-uncased_16_384|Numerics|progression|692.3996|82.3876|-610.012|-88.1%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|73.5146|13.0695|-60.4451|-82.22%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|73.5762|13.3016|-60.2746|-81.92%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|164.9939|19.496|-145.4979|-88.18%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|67.4921|12.7756|-54.7166|-81.07%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|79.3143|13.2144|-66.0999|-83.34%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|137.1929|21.7278|-115.4651|-84.16%|
|migx_bench_bert-large-uncased_32_128|PASS|progression|408.163|70.8905|-337.2724|-82.63%|
|migx_bench_bert-large-uncased_32_256|PASS|progression|619.2813|110.8591|-508.4222|-82.1%|
|migx_bench_bert-large-uncased_32_384|Numerics|progression|761.0092|159.2059|-601.8034|-79.08%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|80.688|14.2435|-66.4445|-82.35%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|97.0175|17.6682|-79.3493|-81.79%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|155.9559|26.7153|-129.2406|-82.87%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|95.5472|20.0435|-75.5037|-79.02%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|159.4493|29.6701|-129.7792|-81.39%|
|migx_bench_bert-large-uncased_8_384|PASS|progression|249.7899|43.305|-206.4848|-82.66%|

## No Regressions Found

## No Progressions Found

