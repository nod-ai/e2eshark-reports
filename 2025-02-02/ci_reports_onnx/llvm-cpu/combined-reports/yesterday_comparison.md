# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|93.6034|97.3714|3.768|4.03%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|87.3918|87.2448|-0.147|-0.17%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|279.8347|249.7634|-30.0713|-10.75%|
|migraphx_ORT__distilgpt2_1|PASS|progression|51.6228|30.4943|-21.1285|-40.93%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|93.6087|92.6502|-0.9585|-1.02%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|251.4606|249.6452|-1.8154|-0.72%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|42.9796|39.0852|-3.8945|-9.06%|
|migraphx_bert__bert-large-uncased|PASS|progression|392.611|372.9105|-19.7005|-5.02%|
|migraphx_cadene__dpn92i1|PASS|within tol|165.6938|169.903|4.2092|2.54%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5584.9792|5556.4357|-28.5435|-0.51%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|425.8464|315.4768|-110.3695|-25.92%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5013.6402|4992.2189|-21.4213|-0.43%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|415.8072|374.6086|-41.1986|-9.91%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|434.6814|427.1206|-7.5608|-1.74%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|99.1927|97.6386|-1.5541|-1.57%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|31.2939|31.801|0.5072|1.62%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|179.6455|180.706|1.0605|0.59%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|82.9025|77.1404|-5.7621|-6.95%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|47.1193|66.078|18.9587|40.24%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1454.8366|1460.52|5.6834|0.39%|
|migraphx_torchvision__inceptioni1|PASS|within tol|198.923|196.6109|-2.3121|-1.16%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5837.725|5840.355|2.63|0.05%|
|migraphx_torchvision__resnet50i1|PASS|regression|83.469|89.1939|5.7249|6.86%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5402.4285|5378.6044|-23.824|-0.44%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2621.3475|2603.9475|-17.4|-0.66%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4123.8152|4035.6569|-88.1584|-2.14%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5780.994|5683.9282|-97.0658|-1.68%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|158.2048|156.2683|-1.9365|-1.22%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|256.8508|264.5621|7.7113|3.0%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|391.7179|409.7602|18.0423|4.61%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|392.6117|377.1223|-15.4894|-3.95%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|596.606|576.1605|-20.4456|-3.43%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|813.5868|928.9371|115.3503|14.18%|
|migx_bench_bert-large-uncased_32_128|PASS|regression|5134.1014|5677.5669|543.4654|10.59%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8436.0579|8733.2243|297.1664|3.52%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11636.2777|11256.0748|-380.2029|-3.27%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|715.1699|774.481|59.3111|8.29%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1124.4092|1099.3818|-25.0274|-2.23%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1569.1662|1511.3734|-57.7928|-3.68%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1311.3925|1313.8345|2.442|0.19%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2044.5282|2028.3634|-16.1648|-0.79%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2853.8381|2924.8414|71.0033|2.49%|

## No Regressions Found

## No Progressions Found

