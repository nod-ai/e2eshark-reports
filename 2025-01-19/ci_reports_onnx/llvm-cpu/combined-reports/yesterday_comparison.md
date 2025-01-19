# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|91.7547|92.9307|1.1759|1.28%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|86.5356|85.8013|-0.7343|-0.85%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|541.6491|261.3686|-280.2805|-51.75%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|30.705|31.778|1.0731|3.49%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|83.624|108.9472|25.3233|30.28%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|264.1709|247.3442|-16.8268|-6.37%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|40.3178|42.7711|2.4533|6.08%|
|migraphx_bert__bert-large-uncased|PASS|progression|444.8301|369.5771|-75.253|-16.92%|
|migraphx_cadene__dpn92i1|PASS|within tol|174.9191|166.8955|-8.0236|-4.59%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5345.1252|5335.8651|-9.2601|-0.17%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|328.6785|844.6229|515.9445|156.98%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5004.5062|5087.6852|83.179|1.66%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|398.3325|388.5548|-9.7777|-2.45%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|424.9254|417.4707|-7.4547|-1.75%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|95.7298|96.4481|0.7183|0.75%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|31.199|31.4212|0.2222|0.71%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|180.9015|190.9703|10.0687|5.57%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|80.3945|83.8562|3.4618|4.31%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|64.3721|47.7809|-16.5912|-25.77%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1578.332|1626.3623|48.0303|3.04%|
|migraphx_torchvision__inceptioni1|PASS|within tol|194.1241|194.7609|0.6367|0.33%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5329.4263|5325.3166|-4.1097|-0.08%|
|migraphx_torchvision__resnet50i1|PASS|within tol|88.2643|86.317|-1.9473|-2.21%|
|migraphx_torchvision__resnet50i64|PASS|within tol|6081.8676|6013.2977|-68.5699|-1.13%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2614.7611|2565.7295|-49.0317|-1.88%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|3959.449|4038.0908|78.6418|1.99%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5776.5579|5735.8028|-40.755|-0.71%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|160.0401|171.9284|11.8883|7.43%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|273.9423|263.4822|-10.46|-3.82%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|370.0822|393.4271|23.3449|6.31%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|390.5834|385.3544|-5.229|-1.34%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|586.8237|660.8301|74.0065|12.61%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|808.8921|826.641|17.7489|2.19%|
|migx_bench_bert-large-uncased_32_128|PASS|regression|4929.883|5205.8054|275.9223|5.6%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8027.867|7964.1528|-63.7142|-0.79%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11108.0077|11402.9632|294.9555|2.66%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|705.1562|700.4958|-4.6604|-0.66%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1072.6122|1079.9231|7.3109|0.68%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1594.9906|1588.1259|-6.8647|-0.43%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1344.3944|1309.5138|-34.8806|-2.59%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2092.3495|2038.8041|-53.5454|-2.56%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3023.8316|2896.9156|-126.916|-4.2%|

## No Regressions Found

## No Progressions Found

