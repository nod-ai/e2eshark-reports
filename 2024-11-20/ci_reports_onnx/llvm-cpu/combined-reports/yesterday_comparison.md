# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|87.6334|85.632|-2.0014|-2.28%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|85.3994|86.1524|0.753|0.88%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|256.5969|260.9527|4.3558|1.7%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|30.7755|31.2671|0.4916|1.6%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|86.3572|83.0977|-3.2595|-3.77%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|253.9125|244.0676|-9.845|-3.88%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|47.5236|40.5572|-6.9664|-14.66%|
|migraphx_bert__bert-large-uncased|PASS|within tol|391.3823|410.0501|18.6678|4.77%|
|migraphx_bert__bertsquad-12|PASS|within tol|95.0233|95.476|0.4527|0.48%|
|migraphx_cadene__dpn92i1|PASS|progression|216.5309|186.2736|-30.2573|-13.97%|
|migraphx_cadene__inceptionv4i16|PASS|regression|6484.9076|7257.2016|772.294|11.91%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|433.132|330.1171|-103.015|-23.78%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|410.4351|420.8|10.3649|2.53%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|735.5786|456.7549|-278.8237|-37.91%|
|migraphx_mlperf__resnet50_v1|PASS|regression|95.932|100.8666|4.9345|5.14%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|32.7376|40.8811|8.1435|24.88%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|182.9053|182.9736|0.0683|0.04%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|75.3095|70.2852|-5.0243|-6.67%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|40.4146|41.0543|0.6397|1.58%|
|migraphx_torchvision__densenet121i32|PASS|progression|1520.7474|1377.2882|-143.4593|-9.43%|
|migraphx_torchvision__inceptioni1|PASS|regression|207.9864|258.7426|50.7562|24.4%|
|migraphx_torchvision__inceptioni32|PASS|regression|6147.702|6648.7116|501.0096|8.15%|
|migraphx_torchvision__resnet50i1|PASS|regression|83.9822|99.4756|15.4934|18.45%|
|migraphx_torchvision__resnet50i64|PASS|regression|5294.3099|6088.0794|793.7695|14.99%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2619.4048|2688.5782|69.1734|2.64%|
|migx_bench_bert-large-uncased_16_256|PASS|progression|4790.3523|4097.8175|-692.5348|-14.46%|
|migx_bench_bert-large-uncased_16_384|Numerics|regression|5909.4044|6359.273|449.8686|7.61%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|167.4284|188.254|20.8255|12.44%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|277.8511|380.8856|103.0345|37.08%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|417.6275|392.6775|-24.95|-5.97%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|397.0189|464.1775|67.1586|16.92%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|606.1018|646.0645|39.9627|6.59%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|955.4131|845.906|-109.5072|-11.46%|
|migx_bench_bert-large-uncased_32_128|PASS|progression|5674.5633|5134.5125|-540.0507|-9.52%|
|migx_bench_bert-large-uncased_32_256|PASS|regression|8091.1831|8841.4288|750.2457|9.27%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11395.1832|11939.3575|544.1743|4.78%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|726.0484|745.4025|19.3541|2.67%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1137.2611|1125.1086|-12.1525|-1.07%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|1570.3202|1749.2347|178.9145|11.39%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|1343.2826|1532.455|189.1724|14.08%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|2100.1059|2403.9663|303.8603|14.47%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3025.6443|3127.1362|101.492|3.35%|

## 9 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|pit_b_224|PASS|compilation|
|pit_b_distilled_224|PASS|compilation|
|pit_s_224|PASS|compilation|
|pit_s_distilled_224|PASS|compilation|
|pit_ti_224|PASS|compilation|
|pit_ti_distilled_224|PASS|compilation|
|pit_xs_224|PASS|compilation|
|pit_xs_distilled_224|PASS|compilation|
|resnest50d_1s4x24d_vaiq|Numerics|compilation|

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|U-2-Net_vaiq_int8|compilation|Numerics|

