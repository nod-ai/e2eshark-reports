# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|94.591|86.9859|-7.6051|-8.04%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|99.1618|111.4118|12.25|12.35%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|307.5093|255.9107|-51.5986|-16.78%|
|migraphx_ORT__distilgpt2_1|PASS|regression|31.2634|39.784|8.5206|27.25%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|90.8611|88.9209|-1.9401|-2.14%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|255.5002|411.1309|155.6308|60.91%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|41.2648|43.2856|2.0208|4.9%|
|migraphx_bert__bert-large-uncased|PASS|regression|376.7673|562.0908|185.3235|49.19%|
|migraphx_cadene__dpn92i1|PASS|progression|180.7198|166.7437|-13.9761|-7.73%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5298.7747|5334.0722|35.2974|0.67%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|325.1031|323.2283|-1.8748|-0.58%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5169.2461|5172.0243|2.7783|0.05%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|379.2727|375.708|-3.5647|-0.94%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|419.9236|482.0326|62.1089|14.79%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|92.1754|93.2712|1.0957|1.19%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|32.1896|31.2626|-0.927|-2.88%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|180.4443|195.6759|15.2316|8.44%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|78.9201|81.6861|2.7659|3.5%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|44.7953|46.7298|1.9345|4.32%|
|migraphx_torchvision__densenet121i32|PASS|regression|1571.2533|1683.3049|112.0516|7.13%|
|migraphx_torchvision__inceptioni1|PASS|within tol|200.9115|194.9449|-5.9666|-2.97%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5393.3811|5420.4419|27.0608|0.5%|
|migraphx_torchvision__resnet50i1|PASS|regression|85.0429|90.4322|5.3893|6.34%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5158.7965|5045.7177|-113.0788|-2.19%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2621.6992|2584.914|-36.7852|-1.4%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4152.8231|4292.3684|139.5453|3.36%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|6013.1026|5773.9899|-239.1127|-3.98%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|157.8816|156.6176|-1.264|-0.8%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|268.2074|263.3612|-4.8462|-1.81%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|391.8161|380.8744|-10.9416|-2.79%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|388.2297|387.9495|-0.2801|-0.07%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|582.4516|583.6216|1.17|0.2%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|868.6022|881.1548|12.5526|1.45%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5299.6859|5095.3965|-204.2894|-3.85%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8065.2761|8071.408|6.1319|0.08%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11359.361|11212.8186|-146.5424|-1.29%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|711.9372|696.8227|-15.1145|-2.12%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1079.8959|1073.9302|-5.9657|-0.55%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|1636.9526|1553.41|-83.5426|-5.1%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1317.8031|1303.8075|-13.9956|-1.06%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2077.0844|2096.0584|18.974|0.91%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2850.3582|2901.1065|50.7483|1.78%|

## No Regressions Found

## No Progressions Found

