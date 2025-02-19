# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|92.6268|90.107|-2.5198|-2.72%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|88.3532|98.3526|9.9994|11.32%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|259.9632|253.7578|-6.2054|-2.39%|
|migraphx_ORT__distilgpt2_1|PASS|progression|34.0513|29.9983|-4.0531|-11.9%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|90.3399|98.455|8.115|8.98%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|493.279|247.7446|-245.5344|-49.78%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|40.5825|46.963|6.3806|15.72%|
|migraphx_agentmodel__AgentModel|Numerics|within tol|1.2685|1.2915|0.023|1.81%|
|migraphx_bert__bert-large-uncased|PASS|progression|576.5169|368.8739|-207.643|-36.02%|
|migraphx_cadene__dpn92i1|PASS|regression|163.8061|206.1696|42.3636|25.86%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5563.864|5709.3226|145.4585|2.61%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|333.0607|430.8039|97.7433|29.35%|
|migraphx_cadene__resnext101_64x4di16|PASS|progression|5804.8561|5347.9202|-456.9358|-7.87%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|406.0491|429.3336|23.2845|5.73%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|436.7366|423.0554|-13.6812|-3.13%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|99.8887|95.3134|-4.5752|-4.58%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|31.3808|31.3252|-0.0556|-0.18%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|210.2591|189.3354|-20.9237|-9.95%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|78.7046|85.5542|6.8495|8.7%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|38.4034|42.059|3.6557|9.52%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1530.4909|1491.6357|-38.8552|-2.54%|
|migraphx_torchvision__inceptioni1|PASS|regression|197.8333|208.4257|10.5924|5.35%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5859.1149|5803.32|-55.7949|-0.95%|
|migraphx_torchvision__resnet50i1|PASS|regression|83.7108|90.9667|7.2559|8.67%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5367.4552|5489.2342|121.7789|2.27%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2557.9255|2653.0898|95.1643|3.72%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4087.0692|4067.1079|-19.9613|-0.49%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5591.2762|5799.6702|208.3939|3.73%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|164.5648|159.8623|-4.7025|-2.86%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|286.0742|308.2058|22.1316|7.74%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|383.9588|442.2308|58.272|15.18%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|384.953|409.1579|24.2048|6.29%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|617.2624|582.4399|-34.8225|-5.64%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|871.5607|808.1645|-63.3962|-7.27%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5227.4805|5085.3763|-142.1042|-2.72%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8023.4599|8073.1429|49.683|0.62%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11498.8985|11115.7651|-383.1334|-3.33%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|935.8842|743.8905|-191.9937|-20.51%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1180.625|1186.8215|6.1965|0.52%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|1969.2588|1545.5732|-423.6856|-21.51%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|3127.0548|1322.9528|-1804.102|-57.69%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2085.7149|2098.6461|12.9312|0.62%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2989.9098|2912.7922|-77.1176|-2.58%|

## No Regressions Found

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|xcit_nano_12_p16_224_dist|Numerics|PASS|

