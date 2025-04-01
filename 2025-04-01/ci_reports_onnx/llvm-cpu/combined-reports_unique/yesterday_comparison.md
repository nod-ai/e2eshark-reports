# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|85.7147|87.9337|2.2189|2.59%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|96.0273|88.4826|-7.5446|-7.86%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|257.8159|249.3528|-8.4631|-3.28%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|30.7264|31.4996|0.7732|2.52%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|85.3099|85.4584|0.1485|0.17%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|669.1133|250.8241|-418.2891|-62.51%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|41.7017|44.5704|2.8687|6.88%|
|migraphx_bert__bert-large-uncased|PASS|within tol|367.9653|369.869|1.9037|0.52%|
|migraphx_cadene__dpn92i1|PASS|within tol|161.1645|160.545|-0.6195|-0.38%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5322.2093|5458.452|136.2427|2.56%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|318.641|316.8869|-1.7542|-0.55%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|403.119|404.3841|1.2651|0.31%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|438.9154|448.9047|9.9893|2.28%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|96.6337|94.9171|-1.7167|-1.78%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|36.3051|30.7629|-5.5423|-15.27%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|179.2213|177.1292|-2.0921|-1.17%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|66.7658|61.3385|-5.4273|-8.13%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|22.1051|20.3579|-1.7472|-7.9%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1482.9891|1551.5861|68.5971|4.63%|
|migraphx_torchvision__inceptioni1|PASS|progression|204.1836|190.2132|-13.9703|-6.84%|
|migraphx_torchvision__resnet50i1|PASS|progression|93.8285|88.5635|-5.265|-5.61%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1408.0578|1415.273|7.2152|0.51%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|2967.3415|2967.5434|0.2019|0.01%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|4613.4909|4625.4001|11.9091|0.26%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|150.5733|149.3784|-1.1949|-0.79%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|265.4025|251.1327|-14.2697|-5.38%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|383.6589|356.6167|-27.0422|-7.05%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|238.7939|242.1887|3.3948|1.42%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|450.2394|426.8844|-23.355|-5.19%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|936.9508|669.0304|-267.9204|-28.59%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|2812.3423|2760.8474|-51.495|-1.83%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|5728.978|5677.8681|-51.11|-0.89%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|9072.5179|9091.2521|18.7343|0.21%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|421.6322|401.0472|-20.5851|-4.88%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|787.3961|799.0986|11.7025|1.49%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|2389.608|1237.22|-1152.388|-48.22%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|769.4958|745.276|-24.2197|-3.15%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1538.4552|1502.2704|-36.1848|-2.35%|
|migx_bench_bert-large-uncased_8_384|PASS|progression|2590.4614|2379.9502|-210.5113|-8.13%|

## No Regressions Found

## No Progressions Found

