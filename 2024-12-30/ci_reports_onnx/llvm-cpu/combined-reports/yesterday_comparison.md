# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|87.3601|85.0964|-2.2637|-2.59%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|86.5697|84.8927|-1.677|-1.94%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|283.8232|257.1412|-26.682|-9.4%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|31.4465|30.4674|-0.9791|-3.11%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|83.7462|91.0195|7.2733|8.68%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|250.7931|273.8865|23.0933|9.21%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|41.7647|39.9136|-1.8512|-4.43%|
|migraphx_bert__bert-large-uncased|PASS|regression|370.8577|426.8874|56.0298|15.11%|
|migraphx_cadene__dpn92i1|PASS|within tol|175.393|168.8203|-6.5727|-3.75%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5526.9511|5640.8639|113.9128|2.06%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|324.646|333.5177|8.8718|2.73%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5147.9712|5211.845|63.8738|1.24%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|374.0734|386.6697|12.5963|3.37%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|418.6286|421.6453|3.0168|0.72%|
|migraphx_mlperf__resnet50_v1|PASS|regression|88.0216|97.3847|9.3631|10.64%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|32.0663|34.8567|2.7904|8.7%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|179.1758|201.6122|22.4364|12.52%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|81.5066|123.9133|42.4067|52.03%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|41.9623|44.6877|2.7254|6.49%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1507.6316|1472.1829|-35.4487|-2.35%|
|migraphx_torchvision__inceptioni1|PASS|within tol|208.6278|209.0187|0.3909|0.19%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5741.2846|5833.6956|92.411|1.61%|
|migraphx_torchvision__resnet50i1|PASS|within tol|87.7254|89.7042|1.9788|2.26%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5916.5359|5926.6415|10.1056|0.17%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2635.2374|2589.9476|-45.2898|-1.72%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4166.5806|4097.4531|-69.1275|-1.66%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5892.4938|5743.6347|-148.8591|-2.53%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|150.3619|155.3754|5.0135|3.33%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|260.9988|261.8931|0.8943|0.34%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|374.8113|378.5557|3.7444|1.0%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|380.9713|411.4698|30.4985|8.01%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|595.8973|608.7073|12.81|2.15%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|810.9225|807.6678|-3.2546|-0.4%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|4978.0283|5079.4617|101.4334|2.04%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|7982.9904|7962.6332|-20.3572|-0.26%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11366.008|11220.226|-145.782|-1.28%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|714.4058|715.7591|1.3534|0.19%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|1166.5726|1072.7861|-93.7865|-8.04%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1534.7671|1570.7743|36.0072|2.35%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1348.023|1306.0531|-41.9699|-3.11%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2113.101|2040.0518|-73.0492|-3.46%|
|migx_bench_bert-large-uncased_8_384|PASS|progression|3035.8959|2879.5242|-156.3716|-5.15%|

## No Regressions Found

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|xcit_nano_12_p8_384_dist|Numerics|PASS|

