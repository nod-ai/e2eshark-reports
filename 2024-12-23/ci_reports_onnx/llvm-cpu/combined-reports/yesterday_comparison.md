# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|85.0416|91.9651|6.9234|8.14%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|86.4673|89.8483|3.381|3.91%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|254.59|260.1904|5.6004|2.2%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|30.2295|31.5065|1.277|4.22%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|88.6986|83.9261|-4.7725|-5.38%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|248.3013|240.7538|-7.5476|-3.04%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|39.7069|40.3626|0.6557|1.65%|
|migraphx_bert__bert-large-uncased|PASS|regression|374.0686|404.0118|29.9432|8.0%|
|migraphx_cadene__dpn92i1|PASS|progression|204.5195|171.0632|-33.4563|-16.36%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5732.0416|5674.2483|-57.7933|-1.01%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|331.9551|319.8017|-12.1534|-3.66%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5150.5486|5188.7771|38.2286|0.74%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|407.3491|379.8405|-27.5086|-6.75%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|423.7259|615.0845|191.3585|45.16%|
|migraphx_mlperf__resnet50_v1|PASS|progression|101.3832|87.5187|-13.8645|-13.68%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|36.357|33.2301|-3.1269|-8.6%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|182.5415|197.0663|14.5248|7.96%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|96.8026|86.5258|-10.2768|-10.62%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|48.7918|43.9293|-4.8625|-9.97%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1480.5859|1481.0982|0.5124|0.03%|
|migraphx_torchvision__inceptioni1|PASS|within tol|212.4165|212.5907|0.1742|0.08%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5750.6082|5786.9648|36.3566|0.63%|
|migraphx_torchvision__resnet50i1|PASS|within tol|86.5777|87.8327|1.2549|1.45%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5864.2356|5937.4086|73.173|1.25%|
|migx_bench_bert-large-uncased_16_128|PASS|regression|2604.2009|2741.5058|137.3049|5.27%|
|migx_bench_bert-large-uncased_16_256|PASS|progression|4275.3763|4038.2567|-237.1196|-5.55%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5763.0567|5797.9821|34.9254|0.61%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|158.9675|320.2883|161.3208|101.48%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|277.2089|260.7635|-16.4454|-5.93%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|372.0555|368.0642|-3.9912|-1.07%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|415.8409|400.246|-15.5949|-3.75%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|594.5353|596.3193|1.784|0.3%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|810.2451|828.275|18.0299|2.23%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5170.5499|5221.4575|50.9076|0.98%|
|migx_bench_bert-large-uncased_32_256|PASS|progression|9202.2481|8206.6131|-995.635|-10.82%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11390.7227|11264.9895|-125.7332|-1.1%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|728.8025|719.082|-9.7205|-1.33%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1084.629|1126.6969|42.0679|3.88%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1606.2082|1579.0317|-27.1764|-1.69%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1295.7835|1283.7215|-12.062|-0.93%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2043.3792|2104.2903|60.9111|2.98%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3063.8086|2988.8713|-74.9373|-2.45%|

## No Regressions Found

## No Progressions Found

