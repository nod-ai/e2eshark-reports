# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|99.102|88.0024|-11.0996|-11.2%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|88.3669|89.103|0.7361|0.83%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|251.4167|330.3382|78.9215|31.39%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|34.0865|35.4669|1.3804|4.05%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|92.0651|85.8865|-6.1786|-6.71%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|250.8175|266.1409|15.3234|6.11%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|41.6967|40.5977|-1.099|-2.64%|
|migraphx_agentmodel__AgentModel|Numerics|progression|1.2045|1.0021|-0.2024|-16.8%|
|migraphx_bert__bert-large-uncased|PASS|within tol|389.4774|370.5118|-18.9656|-4.87%|
|migraphx_cadene__dpn92i1|PASS|within tol|162.7133|166.385|3.6716|2.26%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5549.922|5540.2689|-9.6531|-0.17%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|360.0584|313.131|-46.9274|-13.03%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5185.8881|5065.0065|-120.8816|-2.33%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|401.3073|408.5702|7.2629|1.81%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|2068.0058|490.993|-1577.0128|-76.26%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|96.8108|96.5288|-0.282|-0.29%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|36.1224|31.7878|-4.3347|-12.0%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|185.6731|190.1601|4.4871|2.42%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|74.9819|79.9234|4.9415|6.59%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|46.408|46.1244|-0.2836|-0.61%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1550.032|1479.6867|-70.3454|-4.54%|
|migraphx_torchvision__inceptioni1|PASS|regression|196.0999|206.0128|9.9129|5.06%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5789.3658|5765.7019|-23.664|-0.41%|
|migraphx_torchvision__resnet50i1|PASS|within tol|85.727|84.3858|-1.3413|-1.56%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5362.7119|5397.366|34.6542|0.65%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2608.0395|2608.9548|0.9153|0.04%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4245.9807|4149.4161|-96.5645|-2.27%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5862.0465|5824.2451|-37.8014|-0.64%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|161.4252|156.4944|-4.9308|-3.05%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|283.1746|259.1403|-24.0343|-8.49%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|372.1469|402.2906|30.1437|8.1%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|384.9579|402.785|17.8271|4.63%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|620.6578|1058.2447|437.5869|70.5%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|826.2266|1427.4974|601.2708|72.77%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|4894.4229|5001.805|107.3822|2.19%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8010.0282|8073.7328|63.7046|0.8%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11241.8571|11504.8505|262.9935|2.34%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|735.6813|748.3207|12.6394|1.72%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1108.7672|1100.9354|-7.8318|-0.71%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|1514.201|1605.3455|91.1445|6.02%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1291.2673|1308.9831|17.7158|1.37%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2169.7596|2166.4212|-3.3384|-0.15%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2945.0092|2952.8459|7.8367|0.27%|

## No Regressions Found

## No Progressions Found

