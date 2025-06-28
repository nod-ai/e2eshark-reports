# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_bert__bert-large-uncased|PASS|regression|369.9888|466.5033|96.5145|26.09%|
|migraphx_cadene__dpn92i1|PASS|regression|165.5501|184.7785|19.2284|11.61%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5413.4343|5511.6325|98.1982|1.81%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|329.5718|385.8875|56.3157|17.09%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|399.3836|408.0765|8.6928|2.18%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|470.6991|426.6326|-44.0666|-9.36%|
|migraphx_mlperf__resnet50_v1|PASS|regression|85.5723|97.2511|11.6789|13.65%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|65.4538|58.5479|-6.9059|-10.55%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|206.9714|214.9811|8.0098|3.87%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|58.2698|59.679|1.4092|2.42%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|19.7353|19.9046|0.1693|0.86%|
|migraphx_torchvision__densenet121i32|PASS|regression|1551.4422|1637.9141|86.4718|5.57%|
|migraphx_torchvision__inceptioni1|PASS|within tol|207.5123|208.6352|1.1229|0.54%|
|migraphx_torchvision__resnet50i1|PASS|within tol|83.5537|85.3521|1.7984|2.15%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1559.7311|1576.0271|16.296|1.04%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5363.6121|5350.8211|-12.791|-0.24%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9330.185|9553.9544|223.7694|2.4%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|163.3177|152.9555|-10.3622|-6.34%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|251.5215|282.9672|31.4456|12.5%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|363.7108|487.9642|124.2534|34.16%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|245.7161|250.1946|4.4785|1.82%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|761.74|430.6255|-331.1144|-43.47%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|711.2231|654.0521|-57.171|-8.04%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5034.4835|5073.0014|38.5179|0.77%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|13840.072|13803.0895|-36.9825|-0.27%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|22971.2893|23989.2069|1017.9175|4.43%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|406.9765|419.4667|12.4901|3.07%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|851.6941|814.7591|-36.935|-4.34%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1299.433|1265.8846|-33.5483|-2.58%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|749.4212|819.6319|70.2107|9.37%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1639.8571|1643.2824|3.4253|0.21%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3371.7451|3367.8312|-3.9139|-0.12%|

## No Regressions Found

## No Progressions Found

