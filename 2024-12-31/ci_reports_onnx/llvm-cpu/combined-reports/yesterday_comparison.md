# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|85.0964|85.0019|-0.0945|-0.11%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|84.8927|84.5967|-0.2959|-0.35%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|257.1412|250.1246|-7.0166|-2.73%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|30.4674|30.7637|0.2963|0.97%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|91.0195|88.0997|-2.9198|-3.21%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|273.8865|250.246|-23.6405|-8.63%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|39.9136|40.92|1.0064|2.52%|
|migraphx_bert__bert-large-uncased|PASS|progression|426.8874|373.1287|-53.7588|-12.59%|
|migraphx_cadene__dpn92i1|PASS|regression|168.8203|231.5999|62.7796|37.19%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5640.8639|5406.0539|-234.8101|-4.16%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|333.5177|331.0227|-2.495|-0.75%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5211.845|5127.6439|-84.2012|-1.62%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|386.6697|391.6717|5.002|1.29%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|421.6453|419.5827|-2.0627|-0.49%|
|migraphx_mlperf__resnet50_v1|PASS|progression|97.3847|87.5977|-9.7871|-10.05%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|34.8567|37.3687|2.512|7.21%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|201.6122|178.2975|-23.3147|-11.56%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|123.9133|77.4479|-46.4653|-37.5%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|44.6877|45.2212|0.5335|1.19%|
|migraphx_torchvision__densenet121i32|PASS|regression|1472.1829|1623.4995|151.3166|10.28%|
|migraphx_torchvision__inceptioni1|PASS|regression|209.0187|225.763|16.7443|8.01%|
|migraphx_torchvision__inceptioni32|PASS|progression|5833.6956|5459.3306|-374.3649|-6.42%|
|migraphx_torchvision__resnet50i1|PASS|within tol|89.7042|92.4655|2.7613|3.08%|
|migraphx_torchvision__resnet50i64|PASS|progression|5926.6415|5028.7966|-897.8449|-15.15%|
|migx_bench_bert-large-uncased_16_128|PASS|regression|2589.9476|4259.674|1669.7263|64.47%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4097.4531|4129.5236|32.0705|0.78%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5743.6347|5697.074|-46.5607|-0.81%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|155.3754|153.338|-2.0374|-1.31%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|261.8931|260.7901|-1.1031|-0.42%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|378.5557|379.1138|0.5581|0.15%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|411.4698|423.3889|11.9191|2.9%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|608.7073|590.5217|-18.1856|-2.99%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|807.6678|810.0644|2.3965|0.3%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5079.4617|5020.7625|-58.6992|-1.16%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|7962.6332|8020.7419|58.1088|0.73%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11220.226|11301.452|81.226|0.72%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|715.7591|730.7774|15.0183|2.1%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|1072.7861|1133.8222|61.0361|5.69%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1570.7743|1534.0752|-36.6991|-2.34%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1306.0531|1297.5198|-8.5333|-0.65%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2040.0518|2067.5193|27.4675|1.35%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2879.5242|2942.8847|63.3605|2.2%|

## No Regressions Found

## No Progressions Found

