# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|90.0171|87.159|-2.8581|-3.18%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|95.603|90.4069|-5.1961|-5.44%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|443.0506|318.0841|-124.9665|-28.21%|
|migraphx_ORT__distilgpt2_1|PASS|progression|31.4087|29.6196|-1.7892|-5.7%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|86.0763|86.124|0.0477|0.06%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|250.5385|1549.2265|1298.688|518.36%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|39.1013|610.3166|571.2153|1460.86%|
|migraphx_agentmodel__AgentModel|Numerics|progression|1.5799|1.0897|-0.4902|-31.03%|
|migraphx_bert__bert-large-uncased|PASS|within tol|369.9705|371.8707|1.9002|0.51%|
|migraphx_cadene__dpn92i1|PASS|within tol|164.2028|160.677|-3.5259|-2.15%|
|migraphx_cadene__inceptionv4i16|PASS|regression|5530.2062|5838.1713|307.965|5.57%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|322.2318|330.9954|8.7636|2.72%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5054.0824|5089.6047|35.5224|0.7%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|404.1393|398.9091|-5.2302|-1.29%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|424.4358|433.0781|8.6423|2.04%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|94.7289|97.5502|2.8214|2.98%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|30.9146|30.8954|-0.0192|-0.06%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|208.595|178.0937|-30.5013|-14.62%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|79.8292|79.2617|-0.5675|-0.71%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|47.2102|48.874|1.6638|3.52%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1479.7073|1453.3712|-26.3361|-1.78%|
|migraphx_torchvision__inceptioni1|PASS|within tol|198.0347|195.7053|-2.3293|-1.18%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5811.2581|5709.5645|-101.6935|-1.75%|
|migraphx_torchvision__resnet50i1|PASS|within tol|87.3936|83.8237|-3.5699|-4.08%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5445.7488|5330.6785|-115.0703|-2.11%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2624.0425|2525.1413|-98.9012|-3.77%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4089.1084|4120.521|31.4126|0.77%|
|migx_bench_bert-large-uncased_16_384|Numerics|progression|5979.4735|5631.4582|-348.0153|-5.82%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|190.2601|160.4146|-29.8456|-15.69%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|301.0191|284.8919|-16.1272|-5.36%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|371.518|371.2228|-0.2952|-0.08%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|403.0104|385.0154|-17.9951|-4.47%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|631.5445|592.5857|-38.9588|-6.17%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|848.3846|836.449|-11.9356|-1.41%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5164.0269|5100.8826|-63.1444|-1.22%|
|migx_bench_bert-large-uncased_32_256|PASS|progression|8653.0714|7853.7232|-799.3482|-9.24%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11205.763|11272.7321|66.9691|0.6%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|747.623|723.7637|-23.8593|-3.19%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1110.0888|1113.2305|3.1417|0.28%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|1824.3679|1514.5709|-309.797|-16.98%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1311.9948|1305.6576|-6.3372|-0.48%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|2167.8661|2039.7561|-128.11|-5.91%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2903.1881|2919.4315|16.2434|0.56%|

## No Regressions Found

## No Progressions Found

