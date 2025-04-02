# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|115.0972|114.4737|-0.6235|-0.54%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|115.5218|115.9419|0.4201|0.36%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|521.4706|523.5156|2.045|0.39%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|68.6885|69.0812|0.3928|0.57%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|62.0075|61.968|-0.0394|-0.06%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|328.2383|327.5712|-0.6671|-0.2%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.2024|34.6128|0.4104|1.2%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.3157|19.369|0.0533|0.28%|
|migraphx_cadene__dpn92i1|PASS|within tol|5.0412|5.0513|0.0101|0.2%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|29.1076|29.4283|0.3207|1.1%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|6.4126|6.009|-0.4036|-6.29%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.2661|7.3183|0.0521|0.72%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|26.4234|29.6943|3.271|12.38%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|4.7936|4.7766|-0.017|-0.35%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|38.661|39.3873|0.7263|1.88%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|47.0004|46.0736|-0.9268|-1.97%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|18.5641|18.3079|-0.2563|-1.38%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|8.2851|9.2765|0.9914|11.97%|
|migraphx_torchvision__densenet121i32|PASS|within tol|17.8612|17.8158|-0.0454|-0.25%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.9537|4.8868|-0.0669|-1.35%|
|migraphx_torchvision__resnet50i1|PASS|within tol|3.2224|3.1604|-0.062|-1.92%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|27.0488|27.037|-0.0118|-0.04%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|38.2858|38.423|0.1372|0.36%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|58.1067|58.178|0.0713|0.12%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.2567|12.0354|-0.2213|-1.81%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.743|12.4539|-0.2891|-2.27%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.3511|19.3899|0.0388|0.2%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.8482|12.7513|-0.097|-0.75%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.5359|19.3917|-0.1441|-0.74%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.3008|20.26|-0.0407|-0.2%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|36.8475|37.0726|0.2251|0.61%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|77.735|77.506|-0.229|-0.29%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|118.7661|118.998|0.2319|0.2%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.6576|19.5194|-0.1382|-0.7%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.7094|20.7687|0.0592|0.29%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|24.1388|24.0805|-0.0584|-0.24%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.7937|20.9492|0.1555|0.75%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.3391|27.6829|0.3438|1.26%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|34.7744|34.8274|0.0531|0.15%|

## No Regressions Found

## No Progressions Found

