# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|550.9856|506.7391|-44.2465|-8.03%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|552.7894|552.5071|-0.2824|-0.05%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|2455.3515|2498.3086|42.9571|1.75%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|279.2746|276.3876|-2.887|-1.03%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|343.5054|321.5355|-21.9698|-6.4%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|1773.2744|1409.6859|-363.5885|-20.5%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|168.6865|168.5818|-0.1046|-0.06%|
|migraphx_bert__bert-large-uncased|PASS|within tol|106.1678|108.3696|2.2018|2.07%|
|migraphx_cadene__dpn92i1|Numerics|regression|176.9268|233.596|56.6692|32.03%|
|migraphx_cadene__inceptionv4i16|PASS|regression|589.8728|670.3489|80.4761|13.64%|
|migraphx_cadene__resnext101_64x4di1|Numerics|within tol|484.0452|503.8487|19.8035|4.09%|
|migraphx_cadene__resnext101_64x4di16|Numerics|progression|1959.4795|1855.9692|-103.5104|-5.28%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|33.9845|36.4804|2.4959|7.34%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|135.5171|116.5571|-18.96|-13.99%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|189.1269|171.1169|-18.0101|-9.52%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|766.7576|667.1114|-99.6462|-13.0%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|85.9321|81.682|-4.2501|-4.95%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|39.1959|37.0467|-2.1491|-5.48%|
|migraphx_torchvision__densenet121i32|Numerics|progression|278.1864|263.7032|-14.4832|-5.21%|
|migraphx_torchvision__inceptioni1|PASS|regression|187.9186|232.12|44.2014|23.52%|
|migraphx_torchvision__inceptioni32|PASS|regression|481.4043|589.9365|108.5322|22.54%|
|migraphx_torchvision__resnet50i1|Numerics|progression|84.9594|63.1454|-21.814|-25.68%|
|migraphx_torchvision__resnet50i64|Numerics|progression|666.6741|586.2726|-80.4015|-12.06%|
|migx_bench_bert-large-uncased_16_128|PASS|progression|193.0014|162.5153|-30.4861|-15.8%|
|migx_bench_bert-large-uncased_16_256|PASS|progression|479.7287|288.4807|-191.248|-39.87%|
|migx_bench_bert-large-uncased_16_384|Numerics|progression|692.3996|449.94|-242.4596|-35.02%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|73.5146|73.3682|-0.1464|-0.2%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|73.5762|68.2838|-5.2924|-7.19%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|164.9939|108.6058|-56.3882|-34.18%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|67.4921|33.7286|-33.7636|-50.03%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|79.3143|69.9835|-9.3308|-11.76%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|137.1929|107.2306|-29.9623|-21.84%|
|migx_bench_bert-large-uncased_32_128|PASS|progression|408.163|376.9242|-31.2388|-7.65%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|619.2813|618.9305|-0.3508|-0.06%|
|migx_bench_bert-large-uncased_32_384|Numerics|regression|761.0092|824.1947|63.1855|8.3%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|80.688|67.3424|-13.3456|-16.54%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|97.0175|97.0858|0.0683|0.07%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|155.9559|156.4461|0.4901|0.31%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|95.5472|109.3222|13.775|14.42%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|159.4493|157.501|-1.9482|-1.22%|
|migx_bench_bert-large-uncased_8_384|PASS|progression|249.7899|218.1185|-31.6714|-12.68%|

## No Regressions Found

## No Progressions Found

