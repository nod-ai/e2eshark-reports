# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|1257.9933|92.6268|-1165.3665|-92.64%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|947.1005|88.3532|-858.7474|-90.67%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|559.8424|259.9632|-299.8792|-53.56%|
|migraphx_ORT__distilgpt2_1|PASS|progression|632.1863|34.0513|-598.135|-94.61%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|88.0503|90.3399|2.2897|2.6%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|1585.5022|493.279|-1092.2232|-68.89%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|39.4468|40.5825|1.1357|2.88%|
|migraphx_agentmodel__AgentModel|Numerics|progression|1.9899|1.2685|-0.7214|-36.25%|
|migraphx_bert__bert-large-uncased|PASS|progression|1327.9508|576.5169|-751.4339|-56.59%|
|migraphx_cadene__dpn92i1|PASS|progression|652.7317|163.8061|-488.9256|-74.9%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5768.7073|5563.864|-204.8432|-3.55%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|353.5471|333.0607|-20.4864|-5.79%|
|migraphx_cadene__resnext101_64x4di16|PASS|regression|5009.3722|5804.8561|795.4839|15.88%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|825.8016|406.0491|-419.7525|-50.83%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|2355.7245|436.7366|-1918.9879|-81.46%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|96.0867|99.8887|3.802|3.96%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|36.1796|31.3808|-4.7988|-13.26%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|628.3482|210.2591|-418.0891|-66.54%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|78.4655|78.7046|0.2391|0.3%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|41.6088|38.4034|-3.2054|-7.7%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1490.5608|1530.4909|39.9301|2.68%|
|migraphx_torchvision__inceptioni1|PASS|progression|557.7054|197.8333|-359.8722|-64.53%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5731.4828|5859.1149|127.6321|2.23%|
|migraphx_torchvision__resnet50i1|PASS|progression|127.0706|83.7108|-43.3598|-34.12%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5384.7119|5367.4552|-17.2567|-0.32%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2589.4483|2557.9255|-31.5228|-1.22%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4292.9136|4087.0692|-205.8443|-4.79%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5600.3251|5591.2762|-9.0489|-0.16%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|158.3179|164.5648|6.2469|3.95%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|275.1554|286.0742|10.9188|3.97%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|396.6643|383.9588|-12.7055|-3.2%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|404.6734|384.953|-19.7203|-4.87%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|583.1809|617.2624|34.0815|5.84%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|826.5659|871.5607|44.9948|5.44%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5104.6245|5227.4805|122.856|2.41%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8220.8697|8023.4599|-197.4099|-2.4%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11544.3794|11498.8985|-45.4809|-0.39%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|730.1665|935.8842|205.7177|28.17%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|1121.2258|1180.625|59.3992|5.3%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|1546.6103|1969.2588|422.6484|27.33%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|1286.096|3127.0548|1840.9588|143.14%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|2418.3065|2085.7149|-332.5916|-13.75%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2911.2881|2989.9098|78.6216|2.7%|

## One Regression Found:

|model name|old_status|new_status|
|---|---|---|
|xcit_nano_12_p16_224_dist|PASS|Numerics|

## No Progressions Found

