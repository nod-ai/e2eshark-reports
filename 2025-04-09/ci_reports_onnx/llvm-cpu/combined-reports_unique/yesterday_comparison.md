# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|89.6266|90.1445|0.5178|0.58%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|87.8732|86.3181|-1.5551|-1.77%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|269.414|257.268|-12.146|-4.51%|
|migraphx_ORT__distilgpt2_1|PASS|progression|38.1673|31.9336|-6.2337|-16.33%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|95.4824|85.5371|-9.9453|-10.42%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|290.637|270.8114|-19.8257|-6.82%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|40.0937|40.7105|0.6168|1.54%|
|migraphx_bert__bert-large-uncased|PASS|progression|454.0518|371.7758|-82.276|-18.12%|
|migraphx_cadene__dpn92i1|PASS|progression|174.4034|162.7646|-11.6388|-6.67%|
|migraphx_cadene__inceptionv4i16|PASS|progression|5935.2292|5555.7248|-379.5044|-6.39%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|323.961|316.1996|-7.7614|-2.4%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|811.8873|399.7299|-412.1574|-50.77%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|428.6127|468.9354|40.3226|9.41%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|100.6456|99.4587|-1.1868|-1.18%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|35.1011|263.7718|228.6707|651.46%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|182.0952|184.0313|1.936|1.06%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|66.8025|59.8983|-6.9042|-10.34%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|17.6512|22.0018|4.3506|24.65%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1622.008|1561.7506|-60.2574|-3.71%|
|migraphx_torchvision__inceptioni1|PASS|within tol|190.5891|191.3145|0.7254|0.38%|
|migraphx_torchvision__resnet50i1|PASS|regression|87.0555|92.0099|4.9544|5.69%|
|migx_bench_bert-large-uncased_16_128|PASS|progression|1594.9716|1464.4268|-130.5448|-8.18%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|3068.5955|3098.5444|29.9489|0.98%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|4780.0587|4818.8901|38.8314|0.81%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|214.9722|176.6561|-38.3161|-17.82%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|303.6901|310.3933|6.7031|2.21%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|364.2066|671.7079|307.5013|84.43%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|234.1372|234.0589|-0.0783|-0.03%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|525.3074|432.5686|-92.7388|-17.65%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|686.2236|715.0709|28.8473|4.2%|
|migx_bench_bert-large-uncased_32_128|PASS|progression|3146.5683|2976.0152|-170.5531|-5.42%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|5799.3292|5850.2532|50.924|0.88%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|9136.4175|9166.474|30.0565|0.33%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|419.5926|408.385|-11.2076|-2.67%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|887.5051|789.9531|-97.552|-10.99%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1236.3552|1241.1948|4.8396|0.39%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|759.5424|743.3449|-16.1975|-2.13%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1648.908|1602.1945|-46.7135|-2.83%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2372.1739|2399.0547|26.8807|1.13%|

## No Regressions Found

## 3 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|mosaic-9|compilation|Numerics|
|rain-princess-8|compilation|PASS|
|squeezenet1.0-13-qdq|compilation|Numerics|

