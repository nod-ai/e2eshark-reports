# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|92.9307|85.7525|-7.1782|-7.72%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|85.8013|89.721|3.9197|4.57%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|261.3686|260.1338|-1.2348|-0.47%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|31.778|31.9025|0.1244|0.39%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|108.9472|84.1024|-24.8449|-22.8%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|247.3442|2283.2288|2035.8846|823.1%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|42.7711|39.3188|-3.4524|-8.07%|
|migraphx_bert__bert-large-uncased|PASS|regression|369.5771|406.0754|36.4983|9.88%|
|migraphx_cadene__dpn92i1|PASS|within tol|166.8955|169.3313|2.4358|1.46%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5335.8651|5244.3095|-91.5556|-1.72%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|844.6229|323.4675|-521.1555|-61.7%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5087.6852|5005.3084|-82.3768|-1.62%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|388.5548|390.4895|1.9347|0.5%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|417.4707|414.9974|-2.4733|-0.59%|
|migraphx_mlperf__resnet50_v1|PASS|progression|96.4481|89.7692|-6.679|-6.92%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|31.4212|31.631|0.2098|0.67%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|190.9703|180.1081|-10.8621|-5.69%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|83.8562|79.0902|-4.7661|-5.68%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|47.7809|48.0243|0.2434|0.51%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1626.3623|1553.0156|-73.3467|-4.51%|
|migraphx_torchvision__inceptioni1|PASS|within tol|194.7609|195.1233|0.3625|0.19%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5325.3166|5325.6552|0.3386|0.01%|
|migraphx_torchvision__resnet50i1|PASS|within tol|86.317|86.7679|0.4509|0.52%|
|migraphx_torchvision__resnet50i64|PASS|within tol|6013.2977|5940.4804|-72.8173|-1.21%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2565.7295|2541.7333|-23.9962|-0.94%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4038.0908|4009.5006|-28.5902|-0.71%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5735.8028|5720.4797|-15.3231|-0.27%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|171.9284|155.6448|-16.2837|-9.47%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|263.4822|266.7615|3.2793|1.24%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|393.4271|372.324|-21.1031|-5.36%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|385.3544|389.3338|3.9794|1.03%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|660.8301|584.916|-75.9142|-11.49%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|826.641|805.4045|-21.2365|-2.57%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5205.8054|5039.3142|-166.4912|-3.2%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|7964.1528|8078.3551|114.2023|1.43%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11402.9632|11399.0615|-3.9017|-0.03%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|700.4958|713.9392|13.4434|1.92%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1079.9231|1068.7346|-11.1885|-1.04%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1588.1259|1530.3898|-57.7361|-3.64%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1309.5138|1302.6312|-6.8826|-0.53%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2038.8041|2136.3976|97.5935|4.79%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2896.9156|2936.3184|39.4028|1.36%|

## No Regressions Found

## No Progressions Found

