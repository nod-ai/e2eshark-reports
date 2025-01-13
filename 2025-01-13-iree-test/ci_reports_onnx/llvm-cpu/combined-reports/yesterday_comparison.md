# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|94.591|94.6725|0.0814|0.09%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|99.1618|87.8871|-11.2746|-11.37%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|307.5093|354.1212|46.6118|15.16%|
|migraphx_ORT__distilgpt2_1|PASS|regression|31.2634|64.1823|32.9189|105.3%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|90.8611|83.4067|-7.4543|-8.2%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|255.5002|243.9782|-11.522|-4.51%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|41.2648|40.1111|-1.1537|-2.8%|
|migraphx_bert__bert-large-uncased|PASS|within tol|376.7673|368.9965|-7.7708|-2.06%|
|migraphx_cadene__dpn92i1|PASS|progression|180.7198|167.422|-13.2978|-7.36%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5298.7747|5446.3851|147.6104|2.79%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|325.1031|851.1454|526.0423|161.81%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5169.2461|5124.0005|-45.2456|-0.88%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|379.2727|378.6486|-0.6241|-0.16%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|419.9236|414.6368|-5.2868|-1.26%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|92.1754|95.7034|3.528|3.83%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|32.1896|67.5502|35.3606|109.85%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|180.4443|180.3916|-0.0527|-0.03%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|78.9201|81.4633|2.5431|3.22%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|44.7953|75.4156|30.6203|68.36%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1571.2533|1628.3772|57.1239|3.64%|
|migraphx_torchvision__inceptioni1|PASS|within tol|200.9115|205.7156|4.8041|2.39%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5393.3811|5375.5067|-17.8744|-0.33%|
|migraphx_torchvision__resnet50i1|PASS|regression|85.0429|90.4494|5.4064|6.36%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5158.7965|5032.6233|-126.1732|-2.45%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2621.6992|2695.0836|73.3844|2.8%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4152.8231|4259.3065|106.4835|2.56%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|6013.1026|5779.4806|-233.622|-3.89%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|157.8816|159.1961|1.3145|0.83%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|268.2074|299.9919|31.7845|11.85%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|391.8161|379.5425|-12.2736|-3.13%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|388.2297|389.364|1.1344|0.29%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|582.4516|579.7434|-2.7082|-0.46%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|868.6022|815.4308|-53.1714|-6.12%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5299.6859|5200.5467|-99.1393|-1.87%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8065.2761|8029.406|-35.8702|-0.44%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11359.361|11176.5617|-182.7993|-1.61%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|711.9372|750.7163|38.7791|5.45%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|1079.8959|1153.003|73.1071|6.77%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|1636.9526|1526.4216|-110.531|-6.75%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1317.8031|1308.0986|-9.7045|-0.74%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2077.0844|2067.4855|-9.5989|-0.46%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2850.3582|2835.0928|-15.2654|-0.54%|

## No Regressions Found

## No Progressions Found

