# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|99.2801|550.9856|451.7055|454.98%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|99.5075|552.7894|453.2819|455.53%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|503.809|2455.3515|1951.5425|387.36%|
|migraphx_ORT__distilgpt2_1|PASS|regression|53.2057|279.2746|226.0689|424.9%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|60.9294|343.5054|282.5759|463.78%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|294.8988|1773.2744|1478.3756|501.32%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|31.068|168.6865|137.6185|442.96%|
|migraphx_bert__bert-large-uncased|PASS|regression|19.3046|106.1678|86.8631|449.96%|
|migraphx_cadene__dpn92i1|Numerics|regression|42.5613|176.9268|134.3655|315.7%|
|migraphx_cadene__inceptionv4i16|PASS|regression|155.6412|589.8728|434.2316|279.0%|
|migraphx_cadene__resnext101_64x4di1|Numerics|regression|117.9113|484.0452|366.1338|310.52%|
|migraphx_cadene__resnext101_64x4di16|Numerics|regression|388.2204|1959.4795|1571.2592|404.73%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|7.6668|33.9845|26.3177|343.27%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|23.7886|135.5171|111.7284|469.67%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|33.6487|189.1269|155.4782|462.06%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|140.5332|766.7576|626.2244|445.61%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|15.8212|85.9321|70.111|443.15%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|7.2313|39.1959|31.9645|442.03%|
|migraphx_torchvision__densenet121i32|Numerics|regression|74.1352|278.1864|204.0511|275.24%|
|migraphx_torchvision__inceptioni1|PASS|regression|41.0722|187.9186|146.8464|357.53%|
|migraphx_torchvision__inceptioni32|PASS|regression|106.9578|481.4043|374.4465|350.09%|
|migraphx_torchvision__resnet50i1|Numerics|regression|12.1852|84.9594|72.7742|597.23%|
|migraphx_torchvision__resnet50i64|Numerics|regression|152.0449|666.6741|514.6292|338.47%|
|migx_bench_bert-large-uncased_16_128|PASS|regression|35.2241|193.0014|157.7773|447.92%|
|migx_bench_bert-large-uncased_16_256|PASS|regression|58.3498|479.7287|421.3789|722.16%|
|migx_bench_bert-large-uncased_16_384|Numerics|regression|79.3782|692.3996|613.0213|772.28%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|13.0927|73.5146|60.4219|461.49%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|13.3805|73.5762|60.1957|449.88%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|19.4681|164.9939|145.5258|747.51%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|12.6565|67.4921|54.8357|433.26%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|13.2517|79.3143|66.0626|498.52%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|21.6623|137.1929|115.5306|533.33%|
|migx_bench_bert-large-uncased_32_128|PASS|regression|70.9566|408.163|337.2064|475.23%|
|migx_bench_bert-large-uncased_32_256|PASS|regression|111.5232|619.2813|507.7582|455.29%|
|migx_bench_bert-large-uncased_32_384|Numerics|regression|159.5802|761.0092|601.429|376.88%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|14.3091|80.688|66.3789|463.89%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|17.6211|97.0175|79.3963|450.57%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|26.4608|155.9559|129.4952|489.39%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|20.1226|95.5472|75.4246|374.82%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|29.5623|159.4493|129.887|439.37%|
|migx_bench_bert-large-uncased_8_384|PASS|regression|43.3051|249.7899|206.4848|476.81%|

## No Regressions Found

## No Progressions Found

