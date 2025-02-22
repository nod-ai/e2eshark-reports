# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|104.3419|91.5449|-12.797|-12.26%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|85.0618|87.8266|2.7648|3.25%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|256.8631|249.9015|-6.9616|-2.71%|
|migraphx_ORT__distilgpt2_1|PASS|regression|31.4953|34.6557|3.1604|10.03%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|90.395|85.9944|-4.4005|-4.87%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|851.2767|262.0962|-589.1806|-69.21%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|41.4409|42.3684|0.9275|2.24%|
|migraphx_agentmodel__AgentModel|Numerics|regression|1.1295|1.308|0.1785|15.8%|
|migraphx_bert__bert-large-uncased|PASS|regression|384.1138|549.7967|165.6829|43.13%|
|migraphx_cadene__dpn92i1|PASS|within tol|165.7343|168.9562|3.2218|1.94%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5574.6922|5536.1291|-38.5631|-0.69%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|318.5306|316.9309|-1.5997|-0.5%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5767.7399|5928.6173|160.8773|2.79%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|399.969|399.1102|-0.8588|-0.21%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|421.6152|429.4993|7.8841|1.87%|
|migraphx_mlperf__resnet50_v1|PASS|regression|95.1567|142.0625|46.9057|49.29%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|35.9921|31.6228|-4.3693|-12.14%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|180.0004|181.2247|1.2243|0.68%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|77.504|81.0787|3.5747|4.61%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|44.7171|40.6156|-4.1015|-9.17%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1457.7086|1490.5381|32.8295|2.25%|
|migraphx_torchvision__inceptioni1|PASS|regression|200.6413|216.2288|15.5875|7.77%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5703.6337|5756.4926|52.8589|0.93%|
|migraphx_torchvision__resnet50i1|PASS|within tol|85.2602|87.8225|2.5624|3.01%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5535.0329|5440.4295|-94.6034|-1.71%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2592.3137|2694.4844|102.1707|3.94%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4053.2332|4126.142|72.9088|1.8%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5839.3693|5867.0249|27.6556|0.47%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|174.3313|177.299|2.9677|1.7%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|264.8865|270.6244|5.7379|2.17%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|368.4024|391.0447|22.6422|6.15%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|380.8976|411.0434|30.1457|7.91%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|583.0226|586.5902|3.5676|0.61%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|809.8994|886.9463|77.0468|9.51%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5480.3554|5645.8186|165.4632|3.02%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8180.3774|8202.6742|22.2968|0.27%|
|migx_bench_bert-large-uncased_32_384|Numerics|regression|11226.8535|12032.2511|805.3976|7.17%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|850.0702|796.2476|-53.8226|-6.33%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|1198.2075|1109.9145|-88.293|-7.37%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|1728.6346|1521.9305|-206.7042|-11.96%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1298.4034|1280.0147|-18.3886|-1.42%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|2055.4114|2186.0272|130.6158|6.35%|
|migx_bench_bert-large-uncased_8_384|PASS|regression|2947.3611|3099.2709|151.9098|5.15%|

## No Regressions Found

## No Progressions Found

