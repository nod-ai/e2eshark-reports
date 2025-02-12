# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|95.3542|91.4571|-3.8971|-4.09%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|92.0965|87.2637|-4.8328|-5.25%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|268.6228|259.8306|-8.7922|-3.27%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|30.6057|31.9022|1.2966|4.24%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|84.9673|84.3611|-0.6062|-0.71%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|248.8509|285.6893|36.8385|14.8%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|43.0542|44.43|1.3757|3.2%|
|migraphx_bert__bert-large-uncased|PASS|within tol|386.8141|377.463|-9.351|-2.42%|
|migraphx_cadene__dpn92i1|PASS|regression|164.9006|213.1705|48.2699|29.27%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5568.9351|5589.8876|20.9525|0.38%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|323.8049|327.6704|3.8655|1.19%|
|migraphx_cadene__resnext101_64x4di16|PASS|regression|5105.9581|5447.6034|341.6452|6.69%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|396.4346|396.7168|0.2822|0.07%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|422.3221|853.1963|430.8742|102.03%|
|migraphx_mlperf__resnet50_v1|PASS|progression|105.6898|99.3097|-6.38|-6.04%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|31.2187|32.7719|1.5532|4.98%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|184.6311|190.8732|6.2421|3.38%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|77.0818|81.6663|4.5845|5.95%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|54.2754|48.6452|-5.6302|-10.37%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1500.5231|1459.8546|-40.6685|-2.71%|
|migraphx_torchvision__inceptioni1|PASS|within tol|206.9669|212.6344|5.6675|2.74%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5788.2096|5760.1653|-28.0443|-0.48%|
|migraphx_torchvision__resnet50i1|PASS|regression|84.1824|92.517|8.3346|9.9%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5377.8785|5547.3481|169.4696|3.15%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2687.3981|2568.8803|-118.5177|-4.41%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4061.0236|4150.9137|89.8902|2.21%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5871.2278|5750.3374|-120.8904|-2.06%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|174.9462|196.5953|21.649|12.37%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|259.3032|267.7863|8.483|3.27%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|367.0282|397.7102|30.682|8.36%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|429.8498|413.4168|-16.433|-3.82%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|601.461|581.1754|-20.2856|-3.37%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|815.4325|861.5294|46.0969|5.65%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5135.9175|5280.3679|144.4505|2.81%|
|migx_bench_bert-large-uncased_32_256|PASS|regression|8212.7286|8791.4271|578.6985|7.05%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11542.6226|12055.7389|513.1162|4.45%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|713.3931|727.5331|14.1401|1.98%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1102.5263|1073.8776|-28.6486|-2.6%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1536.0955|1538.3225|2.2271|0.14%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1523.8907|1499.4313|-24.4594|-1.61%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|2554.8697|2195.4659|-359.4038|-14.07%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2940.3196|2859.1175|-81.202|-2.76%|

## No Regressions Found

## No Progressions Found

