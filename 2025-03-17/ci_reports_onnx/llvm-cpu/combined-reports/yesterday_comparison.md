# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|102.0499|97.5489|-4.501|-4.41%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|97.2563|86.9645|-10.2918|-10.58%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|254.4634|256.0567|1.5933|0.63%|
|migraphx_ORT__distilgpt2_1|PASS|progression|34.9234|29.868|-5.0555|-14.48%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|86.204|85.1552|-1.0488|-1.22%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|278.5817|250.5181|-28.0636|-10.07%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|43.1043|39.5649|-3.5394|-8.21%|
|migraphx_agentmodel__AgentModel|Numerics|regression|1.0566|1.1562|0.0996|9.43%|
|migraphx_bert__bert-large-uncased|PASS|within tol|368.1973|372.9889|4.7916|1.3%|
|migraphx_cadene__dpn92i1|PASS|within tol|164.5718|165.1794|0.6076|0.37%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5546.953|5345.3681|-201.5849|-3.63%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|316.1282|316.3328|0.2046|0.06%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|4968.3|5062.5124|94.2124|1.9%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|402.4076|410.3033|7.8957|1.96%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|433.995|520.2648|86.2697|19.88%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|100.7491|98.9963|-1.7528|-1.74%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|38.7436|32.7567|-5.9869|-15.45%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|196.6128|180.3975|-16.2153|-8.25%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|92.2103|85.1713|-7.0391|-7.63%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|43.2795|45.882|2.6024|6.01%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1507.279|1437.3393|-69.9397|-4.64%|
|migraphx_torchvision__inceptioni1|PASS|progression|219.8628|199.1026|-20.7602|-9.44%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5723.2646|5671.2832|-51.9813|-0.91%|
|migraphx_torchvision__resnet50i1|PASS|progression|95.5359|86.0205|-9.5153|-9.96%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5416.842|5607.3652|190.5232|3.52%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1481.7862|1452.8607|-28.9255|-1.95%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|3080.0038|3018.147|-61.8568|-2.01%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|4799.1969|4645.3119|-153.885|-3.21%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|152.384|154.2038|1.8198|1.19%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|269.5962|262.5308|-7.0654|-2.62%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|359.8169|367.6944|7.8775|2.19%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|239.2491|239.8279|0.5789|0.24%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|428.7239|430.6453|1.9214|0.45%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|663.5285|666.6263|3.0977|0.47%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|2806.4176|2935.5547|129.1371|4.6%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|5955.039|5868.1964|-86.8425|-1.46%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|9180.8185|9298.8113|117.9928|1.29%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|406.0785|406.7856|0.707|0.17%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|811.0931|800.5221|-10.571|-1.3%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1250.0325|1267.924|17.8914|1.43%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|746.2524|782.2931|36.0406|4.83%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1511.3481|1519.7304|8.3822|0.55%|
|migx_bench_bert-large-uncased_8_384|PASS|progression|3034.1497|2360.7518|-673.3979|-22.19%|

## No Regressions Found

## No Progressions Found

