# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|86.7434|87.6334|0.8901|1.03%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|120.0247|85.3994|-34.6253|-28.85%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|287.67|256.5969|-31.073|-10.8%|
|migraphx_ORT__distilgpt2_1|PASS|progression|95.476|30.7755|-64.7005|-67.77%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|87.1228|86.3572|-0.7656|-0.88%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|265.1438|253.9125|-11.2312|-4.24%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|39.9035|47.5236|7.6201|19.1%|
|migraphx_bert__bert-large-uncased|PASS|within tol|390.7993|391.3823|0.5829|0.15%|
|migraphx_bert__bertsquad-12|PASS|progression|1418.8174|95.0233|-1323.7941|-93.3%|
|migraphx_cadene__dpn92i1|PASS|regression|185.374|216.5309|31.1569|16.81%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|6595.9829|6484.9076|-111.0753|-1.68%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|338.1451|433.132|94.9869|28.09%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|412.8859|410.4351|-2.4507|-0.59%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|457.5796|735.5786|277.999|60.75%|
|migraphx_mlperf__resnet50_v1|PASS|regression|90.9894|95.932|4.9427|5.43%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|33.9066|32.7376|-1.169|-3.45%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|182.5028|182.9053|0.4026|0.22%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|73.9583|75.3095|1.3512|1.83%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|47.3197|40.4146|-6.9051|-14.59%|
|migraphx_torchvision__densenet121i32|PASS|regression|1344.119|1520.7474|176.6284|13.14%|
|migraphx_torchvision__inceptioni1|PASS|within tol|218.8821|207.9864|-10.8957|-4.98%|
|migraphx_torchvision__inceptioni32|PASS|within tol|6161.4929|6147.702|-13.7909|-0.22%|
|migraphx_torchvision__resnet50i1|PASS|progression|89.0368|83.9822|-5.0546|-5.68%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5145.5514|5294.3099|148.7585|2.89%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2657.1492|2619.4048|-37.7444|-1.42%|
|migx_bench_bert-large-uncased_16_256|PASS|regression|4420.2847|4790.3523|370.0675|8.37%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|6122.5721|5909.4044|-213.1677|-3.48%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|158.0368|167.4284|9.3916|5.94%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|263.897|277.8511|13.9541|5.29%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|376.0995|417.6275|41.528|11.04%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|397.3612|397.0189|-0.3423|-0.09%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|592.6357|606.1018|13.4661|2.27%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|828.9566|955.4131|126.4565|15.25%|
|migx_bench_bert-large-uncased_32_128|PASS|regression|5184.0374|5674.5633|490.5258|9.46%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8443.6431|8091.1831|-352.46|-4.17%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11646.1385|11395.1832|-250.9553|-2.15%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|737.7744|726.0484|-11.7259|-1.59%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|1229.0214|1137.2611|-91.7603|-7.47%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1613.1708|1570.3202|-42.8506|-2.66%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|1445.2389|1343.2826|-101.9563|-7.05%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|2488.9669|2100.1059|-388.861|-15.62%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3046.0351|3025.6443|-20.3908|-0.67%|

## No Regressions Found

## No Progressions Found

