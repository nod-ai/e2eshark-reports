# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|85.6354|85.9956|0.3602|0.42%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|90.05|86.8472|-3.2028|-3.56%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|257.8653|262.5148|4.6496|1.8%|
|migraphx_ORT__distilgpt2_1|PASS|regression|30.6471|34.0404|3.3933|11.07%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|87.2111|85.4163|-1.7948|-2.06%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|498.8842|248.4035|-250.4807|-50.21%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|39.6674|39.3711|-0.2963|-0.75%|
|migraphx_bert__bert-large-uncased|PASS|progression|404.8893|382.4668|-22.4225|-5.54%|
|migraphx_cadene__dpn92i1|PASS|within tol|164.2045|168.2515|4.047|2.46%|
|migraphx_cadene__inceptionv4i16|PASS|progression|6078.8385|5392.1103|-686.7282|-11.3%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|322.7273|324.9342|2.2069|0.68%|
|migraphx_cadene__resnext101_64x4di16|PASS|regression|5088.3962|5804.3444|715.9482|14.07%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|371.6306|390.7573|19.1268|5.15%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|418.5758|426.3122|7.7363|1.85%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|91.9156|91.5566|-0.359|-0.39%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|42.3405|32.6898|-9.6507|-22.79%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|186.0104|183.3277|-2.6827|-1.44%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|83.4654|79.7833|-3.682|-4.41%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|49.8363|70.574|20.7376|41.61%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1612.4539|1600.2778|-12.1761|-0.76%|
|migraphx_torchvision__inceptioni1|PASS|within tol|202.9915|212.9889|9.9974|4.93%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5373.2301|5350.9444|-22.2856|-0.41%|
|migraphx_torchvision__resnet50i1|PASS|within tol|84.8826|85.6121|0.7294|0.86%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5007.7643|5100.3372|92.5728|1.85%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2496.795|2574.5739|77.7789|3.12%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4213.2965|4047.9266|-165.3699|-3.92%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5712.8762|5818.8567|105.9805|1.86%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|178.1273|202.809|24.6817|13.86%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|261.1311|269.4797|8.3487|3.2%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|373.4917|374.9438|1.4521|0.39%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|423.1505|501.965|78.8145|18.63%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|598.4826|585.3933|-13.0894|-2.19%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|816.2125|817.8905|1.6779|0.21%|
|migx_bench_bert-large-uncased_32_128|PASS|progression|5641.9187|5105.7627|-536.1559|-9.5%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|7967.6437|8111.095|143.4514|1.8%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11383.4274|11364.5552|-18.8722|-0.17%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|789.8769|742.4208|-47.4561|-6.01%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1091.3267|1095.5023|4.1756|0.38%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1512.3499|1499.9333|-12.4166|-0.82%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1304.7716|1314.8844|10.1129|0.78%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2015.6957|2087.8032|72.1076|3.58%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2917.0481|2905.4752|-11.5729|-0.4%|

## No Regressions Found

## No Progressions Found

