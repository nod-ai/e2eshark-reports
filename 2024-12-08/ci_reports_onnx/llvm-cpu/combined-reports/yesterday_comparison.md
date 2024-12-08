# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|88.1143|85.0892|-3.0252|-3.43%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|92.1134|86.3704|-5.7431|-6.23%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|257.9402|282.6826|24.7424|9.59%|
|migraphx_ORT__distilgpt2_1|PASS|regression|30.2069|35.5755|5.3686|17.77%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|85.541|84.1125|-1.4286|-1.67%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|249.5407|250.797|1.2563|0.5%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|42.9687|43.0209|0.0522|0.12%|
|migraphx_bert__bert-large-uncased|PASS|regression|372.6801|527.8217|155.1416|41.63%|
|migraphx_bert__bertsquad-12|PASS|progression|95.5721|85.3197|-10.2524|-10.73%|
|migraphx_cadene__dpn92i1|PASS|within tol|186.0975|183.6186|-2.4789|-1.33%|
|migraphx_cadene__inceptionv4i16|PASS|progression|7396.3936|6389.1483|-1007.2453|-13.62%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|337.6411|380.5771|42.9361|12.72%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|385.3724|383.7925|-1.58|-0.41%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|413.3401|431.316|17.9759|4.35%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|100.076|103.8959|3.8199|3.82%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|33.2578|32.7171|-0.5407|-1.63%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|190.3476|194.6398|4.2922|2.25%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|81.6643|86.8854|5.2212|6.39%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|45.5978|41.6922|-3.9055|-8.57%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1354.9973|1362.4453|7.4479|0.55%|
|migraphx_torchvision__inceptioni1|PASS|regression|192.5129|213.0347|20.5218|10.66%|
|migraphx_torchvision__inceptioni32|PASS|within tol|6095.496|6091.832|-3.6639|-0.06%|
|migraphx_torchvision__resnet50i1|PASS|within tol|98.9653|95.9875|-2.9778|-3.01%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5382.6193|5539.1471|156.5277|2.91%|
|migx_bench_bert-large-uncased_16_128|PASS|progression|2748.0463|2574.6706|-173.3757|-6.31%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4300.6982|4138.0227|-162.6755|-3.78%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5910.7496|5894.7975|-15.952|-0.27%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|162.4369|159.5659|-2.871|-1.77%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|281.724|266.6393|-15.0847|-5.35%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|493.2867|388.7391|-104.5476|-21.19%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|379.0621|435.7871|56.725|14.96%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|603.1932|592.4903|-10.7029|-1.77%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|827.897|808.5197|-19.3774|-2.34%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5142.7665|5197.2017|54.4352|1.06%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8053.2541|8140.9782|87.7241|1.09%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11816.9586|11669.7002|-147.2584|-1.25%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|718.6601|733.1534|14.4933|2.02%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|1154.1107|1259.6062|105.4955|9.14%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|1672.0311|1524.6127|-147.4184|-8.82%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|1317.1224|1480.9059|163.7836|12.43%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|2079.9368|2375.6801|295.7433|14.22%|
|migx_bench_bert-large-uncased_8_384|PASS|progression|3171.1774|2975.7977|-195.3797|-6.16%|

## No Regressions Found

## 8 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|pit_b_224|compilation|PASS|
|pit_b_distilled_224|compilation|PASS|
|pit_s_224|compilation|PASS|
|pit_s_distilled_224|compilation|PASS|
|pit_ti_224|compilation|PASS|
|pit_ti_distilled_224|compilation|PASS|
|pit_xs_224|compilation|PASS|
|pit_xs_distilled_224|compilation|PASS|

