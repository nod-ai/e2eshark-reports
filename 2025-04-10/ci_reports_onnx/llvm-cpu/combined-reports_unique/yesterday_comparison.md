# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|90.1445|198.333|108.1885|120.02%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|86.3181|219.1964|132.8783|153.94%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|257.268|906.8217|649.5537|252.48%|
|migraphx_ORT__distilgpt2_1|PASS|regression|31.9336|78.0636|46.13|144.46%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|85.5371|189.1175|103.5804|121.09%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|270.8114|542.844|272.0326|100.45%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|40.7105|89.4388|48.7283|119.69%|
|migraphx_bert__bert-large-uncased|PASS|within tol|371.7758|374.4301|2.6543|0.71%|
|migraphx_cadene__dpn92i1|PASS|within tol|162.7646|166.3398|3.5753|2.2%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5555.7248|5510.0282|-45.6966|-0.82%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|316.1996|323.3957|7.1961|2.28%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|399.7299|1181.1437|781.4138|195.49%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|468.9354|470.8776|1.9422|0.41%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|99.4587|103.5922|4.1335|4.16%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|263.7718|57.6426|-206.1292|-78.15%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|184.0313|993.3223|809.2911|439.76%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|59.8983|58.5954|-1.3029|-2.18%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|22.0018|21.139|-0.8628|-3.92%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1561.7506|1523.4136|-38.337|-2.45%|
|migraphx_torchvision__inceptioni1|PASS|within tol|191.3145|198.7223|7.4077|3.87%|
|migraphx_torchvision__resnet50i1|PASS|progression|92.0099|83.6334|-8.3765|-9.1%|
|migx_bench_bert-large-uncased_16_128|PASS|regression|1464.4268|1567.7768|103.35|7.06%|
|migx_bench_bert-large-uncased_16_256|PASS|regression|3098.5444|5488.5402|2389.9958|77.13%|
|migx_bench_bert-large-uncased_16_384|Numerics|regression|4818.8901|9680.9487|4862.0586|100.9%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|176.6561|151.5526|-25.1035|-14.21%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|310.3933|259.7859|-50.6073|-16.3%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|671.7079|738.5777|66.8698|9.96%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|234.0589|257.5849|23.526|10.05%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|432.5686|445.7015|13.1329|3.04%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|715.0709|656.4262|-58.6446|-8.2%|
|migx_bench_bert-large-uncased_32_128|PASS|regression|2976.0152|5122.6527|2146.6375|72.13%|
|migx_bench_bert-large-uncased_32_256|PASS|regression|5850.2532|14155.0114|8304.7582|141.96%|
|migx_bench_bert-large-uncased_32_384|Numerics|regression|9166.474|23595.8928|14429.4188|157.42%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|408.385|431.8543|23.4693|5.75%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|789.9531|884.6091|94.656|11.98%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1241.1948|1238.1712|-3.0237|-0.24%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|743.3449|827.2495|83.9046|11.29%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|1602.1945|1685.5392|83.3447|5.2%|
|migx_bench_bert-large-uncased_8_384|PASS|regression|2399.0547|3406.5113|1007.4566|41.99%|

## No Regressions Found

## No Progressions Found

