# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|242.7406|199.5497|-43.1909|-17.79%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|200.3591|195.784|-4.5751|-2.28%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|569.8298|559.6408|-10.1891|-1.79%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|78.2189|78.6985|0.4797|0.61%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|190.2835|191.8899|1.6064|0.84%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|551.3446|546.2256|-5.119|-0.93%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|105.3453|100.1207|-5.2246|-4.96%|
|migraphx_bert__bert-large-uncased|PASS|within tol|367.6111|370.9923|3.3812|0.92%|
|migraphx_cadene__dpn92i1|PASS|within tol|181.7319|180.6562|-1.0757|-0.59%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5454.704|5336.4382|-118.2659|-2.17%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|361.5867|328.8302|-32.7566|-9.06%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|432.7529|420.1606|-12.5923|-2.91%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|497.1717|563.8923|66.7206|13.42%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|92.1886|94.5376|2.349|2.55%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|70.4606|62.7|-7.7606|-11.01%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|215.2725|212.9795|-2.293|-1.07%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|107.2358|65.3549|-41.8809|-39.05%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|18.8483|20.738|1.8897|10.03%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1506.8981|1432.953|-73.9452|-4.91%|
|migraphx_torchvision__inceptioni1|PASS|progression|296.0864|202.2308|-93.8556|-31.7%|
|migraphx_torchvision__resnet50i1|PASS|within tol|83.1276|83.386|0.2584|0.31%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1540.3336|1548.6553|8.3217|0.54%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5380.3373|5311.2397|-69.0975|-1.28%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9948.2189|9707.3202|-240.8987|-2.42%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|155.6458|199.3471|43.7012|28.08%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|295.2577|290.9419|-4.3158|-1.46%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|406.4338|440.0205|33.5866|8.26%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|288.1385|293.166|5.0275|1.74%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|555.467|424.2699|-131.1971|-23.62%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|658.8255|774.7084|115.883|17.59%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|4985.7115|5056.6193|70.9079|1.42%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|13695.9374|13985.7947|289.8573|2.12%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|23803.0909|24014.3654|211.2745|0.89%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|1076.7315|649.1701|-427.5615|-39.71%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|787.8997|852.5437|64.6439|8.2%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1261.468|1242.1063|-19.3617|-1.53%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|1188.5729|1760.0685|571.4956|48.08%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1656.0572|1643.8856|-12.1715|-0.73%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3447.4894|3421.7528|-25.7366|-0.75%|

## No Regressions Found

## No Progressions Found

