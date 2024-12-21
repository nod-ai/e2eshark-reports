# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|85.8436|85.4862|-0.3574|-0.42%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|93.8485|93.8911|0.0426|0.05%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|301.9024|256.8509|-45.0515|-14.92%|
|migraphx_ORT__distilgpt2_1|PASS|progression|33.2996|31.1281|-2.1715|-6.52%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|83.2105|83.2056|-0.0049|-0.01%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|867.9162|258.5599|-609.3563|-70.21%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|41.5829|43.3838|1.8009|4.33%|
|migraphx_bert__bert-large-uncased|PASS|progression|564.1679|372.0176|-192.1503|-34.06%|
|migraphx_cadene__dpn92i1|PASS|within tol|172.681|174.123|1.442|0.84%|
|migraphx_cadene__inceptionv4i16|PASS|regression|5529.002|5881.9923|352.9904|6.38%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|348.486|323.3166|-25.1694|-7.22%|
|migraphx_cadene__resnext101_64x4di16|PASS|progression|6030.6278|5221.6904|-808.9373|-13.41%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|379.8547|380.2396|0.3849|0.1%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|741.9981|473.1031|-268.8951|-36.24%|
|migraphx_mlperf__resnet50_v1|PASS|progression|200.3245|94.3202|-106.0044|-52.92%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|33.9655|35.0129|1.0474|3.08%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|185.2826|182.5444|-2.7382|-1.48%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|81.9754|79.4329|-2.5425|-3.1%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|43.5102|46.7708|3.2606|7.49%|
|migraphx_torchvision__densenet121i32|PASS|regression|1529.3484|1618.9022|89.5538|5.86%|
|migraphx_torchvision__inceptioni1|PASS|within tol|209.155|210.2569|1.1019|0.53%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5737.7901|5820.9041|83.114|1.45%|
|migraphx_torchvision__resnet50i1|PASS|regression|88.4952|97.1802|8.685|9.81%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5848.7687|5899.4495|50.6808|0.87%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2652.3647|2709.4695|57.1047|2.15%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4364.1104|4208.5571|-155.5533|-3.56%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5737.5476|5744.122|6.5745|0.11%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|155.7103|161.7904|6.08|3.9%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|260.3823|272.8219|12.4396|4.78%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|424.0541|390.0011|-34.053|-8.03%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|420.6936|385.2918|-35.4018|-8.42%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|694.2905|602.2742|-92.0163|-13.25%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|838.1043|812.0593|-26.045|-3.11%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5232.9756|5217.7097|-15.2659|-0.29%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8049.5532|8263.6508|214.0976|2.66%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11303.1054|11265.1011|-38.0043|-0.34%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|742.6884|721.8659|-20.8225|-2.8%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|1088.7478|1172.4057|83.6578|7.68%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1516.7793|1534.8556|18.0763|1.19%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1342.9962|1288.0556|-54.9407|-4.09%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|2051.5672|2322.2128|270.6456|13.19%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2948.4013|2955.212|6.8108|0.23%|

## No Regressions Found

## No Progressions Found

