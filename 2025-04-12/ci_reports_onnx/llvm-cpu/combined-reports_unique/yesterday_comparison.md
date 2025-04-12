# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|196.8534|196.3078|-0.5456|-0.28%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|199.6074|194.2354|-5.372|-2.69%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|812.6561|634.7825|-177.8736|-21.89%|
|migraphx_ORT__distilgpt2_1|PASS|progression|92.9584|79.7475|-13.2109|-14.21%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|191.2581|188.5122|-2.746|-1.44%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|661.5367|546.1783|-115.3584|-17.44%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|101.9138|90.1068|-11.807|-11.59%|
|migraphx_bert__bert-large-uncased|PASS|within tol|379.8137|373.2974|-6.5162|-1.72%|
|migraphx_cadene__dpn92i1|PASS|regression|163.5116|183.7551|20.2434|12.38%|
|migraphx_cadene__inceptionv4i16|PASS|regression|5497.3955|6094.0757|596.6802|10.85%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|317.0837|484.8264|167.7427|52.9%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|423.3469|407.3888|-15.9581|-3.77%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|466.8703|466.6633|-0.2071|-0.04%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|97.5261|94.0019|-3.5242|-3.61%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|58.1519|64.5251|6.3732|10.96%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|235.8728|208.0098|-27.8631|-11.81%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|61.8857|63.3848|1.499|2.42%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|21.3836|21.5458|0.1622|0.76%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1491.3067|1477.4029|-13.9038|-0.93%|
|migraphx_torchvision__inceptioni1|PASS|within tol|198.9616|190.2193|-8.7423|-4.39%|
|migraphx_torchvision__resnet50i1|PASS|within tol|83.6203|85.5249|1.9047|2.28%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1559.4576|1567.9455|8.4879|0.54%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5377.7884|5473.9794|96.191|1.79%|
|migx_bench_bert-large-uncased_16_384|Numerics|regression|9708.5894|12833.5773|3124.9879|32.19%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|149.7534|148.0701|-1.6833|-1.12%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|283.7824|288.5092|4.7268|1.67%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|360.981|370.8039|9.8229|2.72%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|243.5625|239.1912|-4.3713|-1.79%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|453.544|458.4973|4.9533|1.09%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|744.6898|690.918|-53.7718|-7.22%|
|migx_bench_bert-large-uncased_32_128|PASS|regression|4990.6867|5272.9485|282.2619|5.66%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|14416.2138|13891.374|-524.8398|-3.64%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|24780.3475|24419.1185|-361.229|-1.46%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|438.9796|454.6897|15.7101|3.58%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|839.3946|883.2385|43.8439|5.22%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1268.9544|1264.5436|-4.4108|-0.35%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|756.138|837.2387|81.1007|10.73%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1712.5621|1717.9336|5.3716|0.31%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3467.6612|3461.5938|-6.0674|-0.17%|

## 12 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|convit_base_Opset16_timm|PASS|Numerics|
|convit_base_Opset17_timm|PASS|Numerics|
|mosaic-9|Numerics|compilation|
|regnetz_c16_evos.ch_in1k_train_vaiq|PASS|Numerics|
|regnetz_c16_evos.ch_in1k_vaiq|PASS|Numerics|
|regnetz_c16_evos_Opset16_timm|PASS|Numerics|
|regnetz_d8_evos.ch_in1k_train_vaiq|PASS|Numerics|
|regnetz_d8_evos.ch_in1k_vaiq|PASS|Numerics|
|regnetz_d8_evos_Opset16_timm|PASS|Numerics|
|resnetv2_50d_evos.ah_in1k_train_vaiq|PASS|Numerics|
|resnetv2_50d_evos.ah_in1k_vaiq|PASS|Numerics|
|resnetv2_50d_evos_Opset17_timm|PASS|Numerics|

## No Progressions Found

