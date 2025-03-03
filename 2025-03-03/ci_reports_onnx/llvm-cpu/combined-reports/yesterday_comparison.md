# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|88.0024|90.0171|2.0147|2.29%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|89.103|95.603|6.5|7.29%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|330.3382|443.0506|112.7124|34.12%|
|migraphx_ORT__distilgpt2_1|PASS|progression|35.4669|31.4087|-4.0582|-11.44%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|85.8865|86.0763|0.1898|0.22%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|266.1409|250.5385|-15.6024|-5.86%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|40.5977|39.1013|-1.4965|-3.69%|
|migraphx_agentmodel__AgentModel|Numerics|regression|1.0021|1.5799|0.5778|57.66%|
|migraphx_bert__bert-large-uncased|PASS|within tol|370.5118|369.9705|-0.5413|-0.15%|
|migraphx_cadene__dpn92i1|PASS|within tol|166.385|164.2028|-2.1821|-1.31%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5540.2689|5530.2062|-10.0626|-0.18%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|313.131|322.2318|9.1008|2.91%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5065.0065|5054.0824|-10.9242|-0.22%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|408.5702|404.1393|-4.4309|-1.08%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|490.993|424.4358|-66.5572|-13.56%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|96.5288|94.7289|-1.7999|-1.86%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|31.7878|30.9146|-0.8731|-2.75%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|190.1601|208.595|18.4349|9.69%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|79.9234|79.8292|-0.0942|-0.12%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|46.1244|47.2102|1.0858|2.35%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1479.6867|1479.7073|0.0206|0.0%|
|migraphx_torchvision__inceptioni1|PASS|within tol|206.0128|198.0347|-7.9781|-3.87%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5765.7019|5811.2581|45.5562|0.79%|
|migraphx_torchvision__resnet50i1|PASS|within tol|84.3858|87.3936|3.0078|3.56%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5397.366|5445.7488|48.3827|0.9%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2608.9548|2624.0425|15.0877|0.58%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4149.4161|4089.1084|-60.3077|-1.45%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5824.2451|5979.4735|155.2284|2.67%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|156.4944|190.2601|33.7657|21.58%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|259.1403|301.0191|41.8788|16.16%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|402.2906|371.518|-30.7726|-7.65%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|402.785|403.0104|0.2254|0.06%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|1058.2447|631.5445|-426.7002|-40.32%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|1427.4974|848.3846|-579.1128|-40.57%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5001.805|5164.0269|162.2219|3.24%|
|migx_bench_bert-large-uncased_32_256|PASS|regression|8073.7328|8653.0714|579.3386|7.18%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11504.8505|11205.763|-299.0875|-2.6%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|748.3207|747.623|-0.6977|-0.09%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1100.9354|1110.0888|9.1534|0.83%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|1605.3455|1824.3679|219.0223|13.64%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1308.9831|1311.9948|3.0117|0.23%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2166.4212|2167.8661|1.4449|0.07%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2952.8459|2903.1881|-49.6578|-1.68%|

## No Regressions Found

## No Progressions Found

