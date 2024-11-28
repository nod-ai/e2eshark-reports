# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|90.7649|90.5208|-0.2441|-0.27%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|122.5892|88.5503|-34.039|-27.77%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|280.9099|285.9162|5.0063|1.78%|
|migraphx_ORT__distilgpt2_1|PASS|regression|32.5339|34.4445|1.9106|5.87%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|85.1283|86.8567|1.7284|2.03%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|248.303|302.6657|54.3626|21.89%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|39.1168|40.9478|1.831|4.68%|
|migraphx_bert__bert-large-uncased|PASS|regression|371.907|762.6833|390.7763|105.07%|
|migraphx_bert__bertsquad-12|PASS|within tol|86.1339|86.7035|0.5697|0.66%|
|migraphx_cadene__dpn92i1|PASS|within tol|180.7464|181.0374|0.291|0.16%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|6701.4802|6634.3361|-67.1441|-1.0%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|332.6039|543.7047|211.1009|63.47%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|384.2881|412.1433|27.8551|7.25%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|445.2474|434.7994|-10.448|-2.35%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|100.169|96.9481|-3.2209|-3.22%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|32.1294|32.9723|0.8429|2.62%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|183.3109|188.8142|5.5033|3.0%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|84.1869|79.4703|-4.7166|-5.6%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|55.3045|48.7868|-6.5176|-11.79%|
|migraphx_torchvision__densenet121i32|PASS|progression|1630.4017|1335.9883|-294.4134|-18.06%|
|migraphx_torchvision__inceptioni1|PASS|progression|246.4476|217.8568|-28.5908|-11.6%|
|migraphx_torchvision__inceptioni32|PASS|within tol|6719.806|6790.4379|70.6318|1.05%|
|migraphx_torchvision__resnet50i1|PASS|regression|92.2682|102.1274|9.8592|10.69%|
|migraphx_torchvision__resnet50i64|PASS|within tol|6004.586|6095.6932|91.1072|1.52%|
|migx_bench_bert-large-uncased_16_128|PASS|progression|2919.5237|2576.2003|-343.3234|-11.76%|
|migx_bench_bert-large-uncased_16_256|PASS|progression|4450.2131|4151.446|-298.767|-6.71%|
|migx_bench_bert-large-uncased_16_384|Numerics|progression|6245.8297|5806.1065|-439.7232|-7.04%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|175.6768|160.1658|-15.511|-8.83%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|275.802|266.6018|-9.2002|-3.34%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|381.9974|397.372|15.3746|4.02%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|421.089|405.5461|-15.5429|-3.69%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|668.3821|587.6715|-80.7106|-12.08%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|833.1787|920.0325|86.8538|10.42%|
|migx_bench_bert-large-uncased_32_128|PASS|progression|5695.5263|5241.113|-454.4133|-7.98%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8552.6904|8129.5684|-423.122|-4.95%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11761.3705|11746.0397|-15.3308|-0.13%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|1059.5387|707.084|-352.4547|-33.26%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1138.017|1133.8213|-4.1957|-0.37%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|1661.6247|1548.8315|-112.7932|-6.79%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1451.2537|1489.2101|37.9564|2.62%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|2066.0848|2257.3062|191.2215|9.26%|
|migx_bench_bert-large-uncased_8_384|PASS|regression|3133.6533|3303.48|169.8267|5.42%|

## No Regressions Found

## 7 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|resmlp_12_224.fb_distilled_in1k_vaiq|compilation|PASS|
|resmlp_12_224.fb_in1k_vaiq|compilation|PASS|
|resmlp_24_224.fb_distilled_in1k_vaiq|compilation|PASS|
|resmlp_24_224.fb_in1k_vaiq|compilation|PASS|
|resmlp_36_224.fb_distilled_in1k_vaiq|compilation|PASS|
|resmlp_36_224.fb_in1k_vaiq|compilation|PASS|
|resmlp_big_24_224.fb_distilled_in1k_vaiq|compilation|PASS|

