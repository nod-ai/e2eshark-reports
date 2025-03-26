# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|104.1231|86.2396|-17.8835|-17.18%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|88.6753|89.9748|1.2995|1.47%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|252.1336|253.8065|1.6729|0.66%|
|migraphx_ORT__distilgpt2_1|PASS|regression|33.0538|163.4273|130.3736|394.43%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|85.9437|84.7156|-1.2281|-1.43%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|251.9738|248.6613|-3.3125|-1.31%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|46.1294|39.339|-6.7904|-14.72%|
|migraphx_bert__bert-large-uncased|PASS|within tol|372.1181|374.491|2.3729|0.64%|
|migraphx_cadene__dpn92i1|PASS|progression|247.0732|183.4573|-63.6158|-25.75%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5446.646|5335.4997|-111.1463|-2.04%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|318.9504|369.006|50.0556|15.69%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|406.5078|404.3991|-2.1088|-0.52%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|440.6401|426.1527|-14.4874|-3.29%|
|migraphx_mlperf__resnet50_v1|PASS|regression|95.1312|120.4701|25.3389|26.64%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|37.0447|34.0615|-2.9832|-8.05%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|179.4689|180.8929|1.4241|0.79%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|78.5607|78.965|0.4043|0.51%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|45.3408|52.5027|7.1619|15.8%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1473.7316|1471.0275|-2.7041|-0.18%|
|migraphx_torchvision__inceptioni1|PASS|within tol|197.5902|198.8351|1.2449|0.63%|
|migraphx_torchvision__resnet50i1|PASS|within tol|83.8205|84.1383|0.3178|0.38%|
|migx_bench_bert-large-uncased_16_128|PASS|regression|1414.1369|1491.5319|77.395|5.47%|
|migx_bench_bert-large-uncased_16_256|PASS|regression|2946.7691|3109.3525|162.5834|5.52%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|4873.0199|4953.4854|80.4655|1.65%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|162.8237|154.9077|-7.9159|-4.86%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|257.6866|256.4802|-1.2064|-0.47%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|360.0636|358.557|-1.5066|-0.42%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|239.2839|233.543|-5.741|-2.4%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|477.3336|446.2518|-31.0817|-6.51%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|675.119|768.9036|93.7846|13.89%|
|migx_bench_bert-large-uncased_32_128|PASS|regression|2785.9693|2971.5829|185.6136|6.66%|
|migx_bench_bert-large-uncased_32_256|PASS|regression|5827.351|6126.0749|298.7238|5.13%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|9095.5214|9333.2578|237.7364|2.61%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|417.3494|414.8363|-2.5131|-0.6%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|796.5356|831.682|35.1465|4.41%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|1233.2514|1316.2073|82.9559|6.73%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|753.2772|765.4156|12.1385|1.61%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1511.1661|1507.5061|-3.66|-0.24%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2401.1254|2444.6306|43.5052|1.81%|

## No Regressions Found

## No Progressions Found

