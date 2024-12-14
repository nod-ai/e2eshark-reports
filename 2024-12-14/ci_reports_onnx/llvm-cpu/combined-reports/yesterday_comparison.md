# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|94.7967|90.8713|-3.9254|-4.14%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|89.961|87.752|-2.209|-2.46%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|278.1225|253.6789|-24.4436|-8.79%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|31.1493|30.4876|-0.6618|-2.12%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|91.2386|84.4226|-6.8161|-7.47%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|270.0427|244.3155|-25.7272|-9.53%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|42.1865|43.075|0.8885|2.11%|
|migraphx_bert__bert-large-uncased|PASS|within tol|399.6764|407.5057|7.8293|1.96%|
|migraphx_bert__bertsquad-12|PASS|within tol|89.5165|85.4887|-4.0277|-4.5%|
|migraphx_cadene__dpn92i1|PASS|within tol|174.4636|174.9017|0.4381|0.25%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5765.4185|5940.3475|174.929|3.03%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|317.5065|353.9452|36.4387|11.48%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5083.541|5173.375|89.834|1.77%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|1467.3172|389.396|-1077.9212|-73.46%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|464.6443|441.186|-23.4583|-5.05%|
|migraphx_mlperf__resnet50_v1|PASS|progression|94.0177|87.9021|-6.1156|-6.5%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|35.9429|31.7997|-4.1433|-11.53%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|950.8281|194.1748|-756.6534|-79.58%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|83.0847|112.063|28.9783|34.88%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|89.5228|43.104|-46.4188|-51.85%|
|migraphx_torchvision__densenet121i32|PASS|regression|1652.0718|1785.3344|133.2626|8.07%|
|migraphx_torchvision__inceptioni1|PASS|within tol|213.6682|203.3006|-10.3676|-4.85%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5878.121|5872.5554|-5.5656|-0.09%|
|migraphx_torchvision__resnet50i1|PASS|progression|94.6007|85.9645|-8.6362|-9.13%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5966.7406|6027.3714|60.6308|1.02%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2692.6237|2666.3104|-26.3133|-0.98%|
|migx_bench_bert-large-uncased_16_256|PASS|regression|3942.4433|4399.8424|457.399|11.6%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5809.3705|5893.4285|84.058|1.45%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|154.6039|168.2351|13.6312|8.82%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|270.1317|263.714|-6.4178|-2.38%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|425.0584|366.8157|-58.2427|-13.7%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|416.7535|400.9772|-15.7763|-3.79%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|591.0844|630.2853|39.2009|6.63%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|844.6552|824.0976|-20.5575|-2.43%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5139.1905|5151.8158|12.6253|0.25%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8146.081|8158.8374|12.7564|0.16%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|12336.882|12273.8599|-63.0221|-0.51%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|705.6838|705.1223|-0.5615|-0.08%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1081.7549|1097.3568|15.6019|1.44%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|1498.9066|1615.9651|117.0586|7.81%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|1303.4308|1468.6469|165.2161|12.68%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2107.7125|2067.6784|-40.0341|-1.9%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2859.5586|2881.313|21.7544|0.76%|

## One Regression Found:

|model name|old_status|new_status|
|---|---|---|
|xcit_nano_12_p16_224|PASS|Numerics|

## No Progressions Found

