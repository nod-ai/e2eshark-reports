# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|106.7398|107.0306|0.2908|0.27%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|106.6588|106.6436|-0.0151|-0.01%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|574.9832|473.6884|-101.2948|-17.62%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|60.5996|61.6802|1.0806|1.78%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|64.3291|65.6258|1.2967|2.02%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|538.3309|275.4226|-262.9083|-48.84%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|33.2048|37.156|3.9512|11.9%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.2796|19.2836|0.004|0.02%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.0829|7.0631|-0.0198|-0.28%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|72.3884|27.5769|-44.8115|-61.9%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|44.8105|44.0332|-0.7773|-1.73%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|144.0767|146.872|2.7953|1.94%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|16.886|16.0137|-0.8723|-5.17%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|7.0787|7.4321|0.3534|4.99%|
|migraphx_torchvision__inceptioni1|PASS|within tol|61.1588|60.3198|-0.8391|-1.37%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|31.9747|32.5593|0.5846|1.83%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|53.3633|54.559|1.1956|2.24%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|72.1987|73.1134|0.9148|1.27%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|11.94|11.9067|-0.0333|-0.28%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.6244|12.8985|0.2742|2.17%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.925|19.8889|-0.0361|-0.18%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|22.287|12.9783|-9.3087|-41.77%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.5585|13.1997|-0.3588|-2.65%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.9663|21.1592|0.1929|0.92%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|65.4476|67.1602|1.7126|2.62%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|99.1167|98.0949|-1.0219|-1.03%|
|migx_bench_bert-large-uncased_32_384|Numerics|regression|146.4728|284.7153|138.2425|94.38%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.3232|14.3149|-0.0083|-0.06%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|16.2602|17.3841|1.1239|6.91%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|25.7287|26.8944|1.1657|4.53%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|18.9164|19.2423|0.3258|1.72%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.6894|27.1126|0.4231|1.59%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|39.4935|40.6474|1.154|2.92%|

## 2 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|efficientnet_b2_pruned.in1k|PASS|compilation|
|tf_efficientnet_l2.ns_jft_in1k_475|PASS|compilation|

## No Progressions Found

