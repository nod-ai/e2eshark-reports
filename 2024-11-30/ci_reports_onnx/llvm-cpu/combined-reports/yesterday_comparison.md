# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|85.3842|89.8916|4.5074|5.28%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|89.591|85.1816|-4.4094|-4.92%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|257.4052|256.0638|-1.3414|-0.52%|
|migraphx_ORT__distilgpt2_1|PASS|regression|31.2472|33.3817|2.1345|6.83%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|98.7786|84.5201|-14.2585|-14.43%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|248.0021|251.7971|3.7949|1.53%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|43.3367|45.563|2.2263|5.14%|
|migraphx_bert__bert-large-uncased|PASS|within tol|390.5077|392.0753|1.5676|0.4%|
|migraphx_bert__bertsquad-12|PASS|within tol|86.8825|85.5971|-1.2854|-1.48%|
|migraphx_cadene__dpn92i1|PASS|within tol|178.1699|179.4707|1.3008|0.73%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|6794.1704|6956.8683|162.6979|2.39%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|376.782|413.7348|36.9528|9.81%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|390.6549|378.4233|-12.2316|-3.13%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|430.0274|477.6531|47.6257|11.08%|
|migraphx_mlperf__resnet50_v1|PASS|progression|119.2004|113.0269|-6.1736|-5.18%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|32.2664|34.046|1.7797|5.52%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|182.493|237.2332|54.7402|30.0%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|77.5851|79.7208|2.1357|2.75%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|44.3579|44.7527|0.3948|0.89%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1307.341|1345.3629|38.0219|2.91%|
|migraphx_torchvision__inceptioni1|PASS|progression|238.0094|219.3302|-18.6792|-7.85%|
|migraphx_torchvision__inceptioni32|PASS|within tol|6677.8886|6631.3472|-46.5413|-0.7%|
|migraphx_torchvision__resnet50i1|PASS|progression|121.9718|90.353|-31.6188|-25.92%|
|migraphx_torchvision__resnet50i64|PASS|within tol|6019.9044|6061.1269|41.2225|0.68%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2759.5673|2691.0461|-68.5213|-2.48%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4117.2409|4308.8355|191.5946|4.65%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5824.2386|5797.7072|-26.5314|-0.46%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|171.8359|156.789|-15.0469|-8.76%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|262.7133|281.3423|18.629|7.09%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|447.5602|371.5205|-76.0397|-16.99%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|374.9969|380.417|5.4201|1.45%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|596.9295|587.905|-9.0245|-1.51%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|835.907|808.8258|-27.0813|-3.24%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5103.7411|5143.8313|40.0902|0.79%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8176.8404|8270.9624|94.122|1.15%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11525.9705|11553.9552|27.9847|0.24%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|721.951|753.9786|32.0276|4.44%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1119.9822|1113.7307|-6.2515|-0.56%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|1650.3227|1520.0476|-130.2751|-7.89%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|1540.8992|1407.5527|-133.3465|-8.65%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|2115.1777|3388.4574|1273.2796|60.2%|
|migx_bench_bert-large-uncased_8_384|PASS|regression|2980.8059|3165.3496|184.5437|6.19%|

## No Regressions Found

## No Progressions Found

