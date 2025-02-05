# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|86.904|102.46|15.556|17.9%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|86.3333|97.3489|11.0156|12.76%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|275.7825|286.3767|10.5942|3.84%|
|migraphx_ORT__distilgpt2_1|PASS|progression|35.8878|32.4292|-3.4586|-9.64%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|85.0855|86.752|1.6665|1.96%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|251.2094|368.9529|117.7434|46.87%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|43.6912|39.5546|-4.1366|-9.47%|
|migraphx_bert__bert-large-uncased|PASS|within tol|387.1571|381.5297|-5.6275|-1.45%|
|migraphx_cadene__dpn92i1|PASS|within tol|165.0114|169.6817|4.6703|2.83%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5464.101|5685.8814|221.7804|4.06%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|319.2752|313.3412|-5.934|-1.86%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5092.7284|5075.3745|-17.3539|-0.34%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|416.9623|402.8741|-14.0882|-3.38%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|500.6059|446.8885|-53.7174|-10.73%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|97.9492|97.8305|-0.1188|-0.12%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|37.1189|30.8571|-6.2617|-16.87%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|184.0171|180.849|-3.1681|-1.72%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|122.9011|75.4455|-47.4556|-38.61%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|44.1418|41.4305|-2.7113|-6.14%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1491.5596|1497.0353|5.4757|0.37%|
|migraphx_torchvision__inceptioni1|PASS|within tol|208.9262|198.6133|-10.3129|-4.94%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5768.4141|5731.2718|-37.1423|-0.64%|
|migraphx_torchvision__resnet50i1|PASS|progression|90.557|84.7783|-5.7787|-6.38%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5340.2176|5480.234|140.0164|2.62%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2581.728|2604.0863|22.3583|0.87%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4326.2975|4385.5687|59.2712|1.37%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5808.0554|5825.9498|17.8945|0.31%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|163.7189|176.7491|13.0302|7.96%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|261.9843|278.5329|16.5486|6.32%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|378.7901|381.0063|2.2162|0.59%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|410.9864|379.0164|-31.97|-7.78%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|639.4657|616.4723|-22.9934|-3.6%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|809.5715|849.253|39.6815|4.9%|
|migx_bench_bert-large-uncased_32_128|PASS|progression|5679.5036|5125.9828|-553.5208|-9.75%|
|migx_bench_bert-large-uncased_32_256|PASS|progression|8795.6805|8013.2104|-782.4701|-8.9%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11924.8403|11334.7272|-590.113|-4.95%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|800.9497|718.461|-82.4887|-10.3%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1082.1753|1097.0802|14.9049|1.38%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|1648.3646|1512.302|-136.0626|-8.25%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1288.4553|1332.6846|44.2293|3.43%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2087.3922|2181.5539|94.1618|4.51%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2891.427|2987.6832|96.2562|3.33%|

## No Regressions Found

## No Progressions Found

