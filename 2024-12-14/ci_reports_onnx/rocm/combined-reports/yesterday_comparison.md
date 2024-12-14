# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|98.5099|97.8961|-0.6139|-0.62%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|98.6938|98.3238|-0.37|-0.37%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|496.6267|494.0389|-2.5878|-0.52%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|53.3837|53.9888|0.6051|1.13%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|61.5175|61.5802|0.0626|0.1%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|264.1973|263.8973|-0.3001|-0.11%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|30.8923|30.9226|0.0304|0.1%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.5344|19.4997|-0.0347|-0.18%|
|migraphx_bert__bertsquad-12|PASS|regression|7.6325|8.1289|0.4964|6.5%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|159.5249|159.522|-0.003|-0.0%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|185.4665|185.2716|-0.1949|-0.11%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.2223|7.23|0.0077|0.11%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|24.9989|24.1157|-0.8832|-3.53%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|6.1233|6.1402|0.0169|0.28%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|39.6276|40.0611|0.4335|1.09%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|46.9637|46.7876|-0.1761|-0.37%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|14.9241|14.5687|-0.3554|-2.38%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|7.7407|6.0145|-1.7262|-22.3%|
|migraphx_torchvision__densenet121i32|PASS|within tol|71.6195|71.7279|0.1085|0.15%|
|migraphx_torchvision__inceptioni1|PASS|progression|96.8217|18.9451|-77.8766|-80.43%|
|migraphx_torchvision__inceptioni32|PASS|within tol|136.7435|136.8613|0.1178|0.09%|
|migraphx_torchvision__resnet50i64|PASS|within tol|166.024|166.1349|0.1109|0.07%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|33.6822|33.7763|0.0941|0.28%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|58.9102|58.9717|0.0615|0.1%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|74.835|74.9692|0.1342|0.18%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.1244|13.1136|-0.0108|-0.08%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.246|13.3151|0.0691|0.52%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.4655|19.4343|-0.0312|-0.16%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.9075|12.8969|-0.0106|-0.08%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.4572|13.5101|0.0528|0.39%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.3369|21.359|0.0221|0.1%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|70.6285|70.5895|-0.039|-0.06%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|107.0307|106.9894|-0.0413|-0.04%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|149.0779|149.1144|0.0365|0.02%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.4661|14.4903|0.0242|0.17%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|17.3266|17.2734|-0.0532|-0.31%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|27.3892|26.6831|-0.706|-2.58%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|19.8435|19.8649|0.0214|0.11%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|28.1912|28.2009|0.0097|0.03%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|41.8152|41.8477|0.0325|0.08%|

## No Regressions Found

## No Progressions Found

