# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|91.4571|107.9024|16.4452|17.98%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|87.2637|88.3373|1.0736|1.23%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|259.8306|254.1094|-5.7211|-2.2%|
|migraphx_ORT__distilgpt2_1|PASS|progression|31.9022|30.2544|-1.6478|-5.17%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|84.3611|93.9782|9.6172|11.4%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|285.6893|1220.6149|934.9255|327.25%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|44.43|39.9261|-4.5039|-10.14%|
|migraphx_bert__bert-large-uncased|PASS|regression|377.463|413.0928|35.6297|9.44%|
|migraphx_cadene__dpn92i1|PASS|progression|213.1705|168.1157|-45.0548|-21.14%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5589.8876|5573.6152|-16.2725|-0.29%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|327.6704|315.7709|-11.8995|-3.63%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5447.6034|5544.1129|96.5095|1.77%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|396.7168|399.108|2.3912|0.6%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|853.1963|888.3055|35.1092|4.12%|
|migraphx_mlperf__resnet50_v1|PASS|regression|99.3097|271.6774|172.3676|173.57%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|32.7719|44.2754|11.5035|35.1%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|190.8732|181.8094|-9.0638|-4.75%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|81.6663|81.1393|-0.527|-0.65%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|48.6452|40.21|-8.4353|-17.34%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1459.8546|1455.4684|-4.3862|-0.3%|
|migraphx_torchvision__inceptioni1|PASS|regression|212.6344|234.6354|22.0011|10.35%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5760.1653|5816.4497|56.2844|0.98%|
|migraphx_torchvision__resnet50i1|PASS|progression|92.517|84.7126|-7.8044|-8.44%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5547.3481|5485.6705|-61.6775|-1.11%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2568.8803|2530.3166|-38.5637|-1.5%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4150.9137|4122.3622|-28.5516|-0.69%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5750.3374|5909.3393|159.0019|2.77%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|196.5953|159.8075|-36.7877|-18.71%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|267.7863|261.9293|-5.8569|-2.19%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|397.7102|388.7546|-8.9555|-2.25%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|413.4168|443.2074|29.7906|7.21%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|581.1754|602.1995|21.0241|3.62%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|861.5294|810.496|-51.0334|-5.92%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5280.3679|5080.4809|-199.8871|-3.79%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8791.4271|8981.1545|189.7274|2.16%|
|migx_bench_bert-large-uncased_32_384|Numerics|progression|12055.7389|11437.1269|-618.6119|-5.13%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|727.5331|708.8474|-18.6857|-2.57%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1073.8776|1085.742|11.8644|1.1%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1538.3225|1553.2269|14.9043|0.97%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|1499.4313|1336.9308|-162.5005|-10.84%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2195.4659|2107.7603|-87.7056|-3.99%|
|migx_bench_bert-large-uncased_8_384|PASS|regression|2859.1175|3181.5787|322.4611|11.28%|

## No Regressions Found

## No Progressions Found

