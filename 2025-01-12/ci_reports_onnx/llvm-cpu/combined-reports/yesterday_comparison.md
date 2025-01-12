# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|101.346|94.591|-6.755|-6.67%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|95.5034|99.1618|3.6583|3.83%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|290.4439|307.5093|17.0655|5.88%|
|migraphx_ORT__distilgpt2_1|PASS|progression|35.1049|31.2634|-3.8415|-10.94%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|84.7752|90.8611|6.0859|7.18%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|249.3368|255.5002|6.1634|2.47%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|39.3233|41.2648|1.9415|4.94%|
|migraphx_bert__bert-large-uncased|PASS|within tol|387.8339|376.7673|-11.0665|-2.85%|
|migraphx_cadene__dpn92i1|PASS|regression|171.3971|180.7198|9.3227|5.44%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5298.7931|5298.7747|-0.0183|-0.0%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|324.3148|325.1031|0.7882|0.24%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5154.7909|5169.2461|14.4551|0.28%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|380.4204|379.2727|-1.1476|-0.3%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|445.5365|419.9236|-25.6128|-5.75%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|91.4229|92.1754|0.7526|0.82%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|32.7553|32.1896|-0.5657|-1.73%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|183.9992|180.4443|-3.555|-1.93%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|82.4427|78.9201|-3.5226|-4.27%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|43.7445|44.7953|1.0508|2.4%|
|migraphx_torchvision__densenet121i32|PASS|progression|1673.4347|1571.2533|-102.1814|-6.11%|
|migraphx_torchvision__inceptioni1|PASS|progression|221.348|200.9115|-20.4365|-9.23%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5388.9789|5393.3811|4.4023|0.08%|
|migraphx_torchvision__resnet50i1|PASS|within tol|85.5755|85.0429|-0.5326|-0.62%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5126.1681|5158.7965|32.6284|0.64%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2641.8773|2621.6992|-20.1781|-0.76%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4073.775|4152.8231|79.0481|1.94%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5809.7522|6013.1026|203.3504|3.5%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|176.9675|157.8816|-19.086|-10.79%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|267.4712|268.2074|0.7362|0.28%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|369.0756|391.8161|22.7405|6.16%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|402.2398|388.2297|-14.0101|-3.48%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|578.1443|582.4516|4.3073|0.75%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|983.5079|868.6022|-114.9056|-11.68%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5096.0184|5299.6859|203.6675|4.0%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|7975.8941|8065.2761|89.382|1.12%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11607.9535|11359.361|-248.5925|-2.14%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|714.5921|711.9372|-2.6549|-0.37%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1115.7697|1079.8959|-35.8739|-3.22%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|1518.8999|1636.9526|118.0527|7.77%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1296.358|1317.8031|21.4451|1.65%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2048.0947|2077.0844|28.9897|1.42%|
|migx_bench_bert-large-uncased_8_384|PASS|progression|3012.4891|2850.3582|-162.1309|-5.38%|

## No Regressions Found

## No Progressions Found

