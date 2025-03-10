# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|93.7953|94.7269|0.9315|0.99%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|95.0403|84.2209|-10.8195|-11.38%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|280.1274|508.3621|228.2348|81.48%|
|migraphx_ORT__distilgpt2_1|PASS|regression|29.8679|41.5201|11.6522|39.01%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|85.5621|96.3803|10.8182|12.64%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|249.0118|573.0344|324.0226|130.12%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|39.6749|39.6832|0.0083|0.02%|
|migraphx_agentmodel__AgentModel|Numerics|progression|1.2085|1.12|-0.0885|-7.33%|
|migraphx_bert__bert-large-uncased|PASS|within tol|385.6719|383.0133|-2.6586|-0.69%|
|migraphx_cadene__dpn92i1|PASS|regression|164.2473|175.3971|11.1498|6.79%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5523.6181|5576.1358|52.5177|0.95%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|329.1116|326.7288|-2.3828|-0.72%|
|migraphx_cadene__resnext101_64x4di16|PASS|progression|5947.2453|5260.8316|-686.4137|-11.54%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|405.6228|406.046|0.4232|0.1%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|429.6432|1781.1989|1351.5557|314.58%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|96.3923|99.2631|2.8708|2.98%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|46.2907|78.2236|31.9329|68.98%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|185.1168|181.2993|-3.8176|-2.06%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|73.8956|83.3788|9.4832|12.83%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|46.0277|45.4312|-0.5965|-1.3%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1555.2953|1603.2242|47.9289|3.08%|
|migraphx_torchvision__inceptioni1|PASS|progression|211.0803|197.6425|-13.4378|-6.37%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5847.7441|5720.6154|-127.1287|-2.17%|
|migraphx_torchvision__resnet50i1|PASS|within tol|87.1547|85.1865|-1.9682|-2.26%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5477.2962|5431.3844|-45.9118|-0.84%|
|migx_bench_bert-large-uncased_16_128|PASS|progression|1624.5271|1443.8254|-180.7018|-11.12%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|2983.4854|2949.8514|-33.634|-1.13%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|4892.5365|4781.8086|-110.7279|-2.26%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|150.6327|150.2997|-0.333|-0.22%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|250.6552|264.1217|13.4665|5.37%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|374.8319|378.903|4.0711|1.09%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|236.4836|248.1355|11.6519|4.93%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|448.3504|439.784|-8.5664|-1.91%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|655.5266|662.9584|7.4318|1.13%|
|migx_bench_bert-large-uncased_32_128|PASS|regression|2810.8615|3221.7447|410.8832|14.62%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|5869.0566|5824.0415|-45.0151|-0.77%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|9429.077|9193.3977|-235.6792|-2.5%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|407.5545|406.4168|-1.1376|-0.28%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|797.5468|848.5686|51.0218|6.4%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|1254.7033|1327.947|73.2437|5.84%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|734.8352|747.2699|12.4346|1.69%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1534.499|1553.7891|19.2901|1.26%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2428.4467|2424.6058|-3.8409|-0.16%|

## No Regressions Found

## No Progressions Found

