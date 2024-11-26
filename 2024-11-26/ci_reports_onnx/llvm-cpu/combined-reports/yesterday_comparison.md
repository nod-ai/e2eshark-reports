# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|87.6328|97.0104|9.3776|10.7%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|88.2342|88.6564|0.4222|0.48%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|254.6077|267.9819|13.3743|5.25%|
|migraphx_ORT__distilgpt2_1|PASS|progression|36.3467|31.7572|-4.5895|-12.63%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|83.544|85.2966|1.7526|2.1%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|243.4748|255.9586|12.4838|5.13%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|39.5702|41.1689|1.5988|4.04%|
|migraphx_bert__bert-large-uncased|PASS|within tol|373.2743|383.8607|10.5863|2.84%|
|migraphx_bert__bertsquad-12|PASS|regression|83.804|106.5644|22.7604|27.16%|
|migraphx_cadene__dpn92i1|PASS|regression|179.7351|200.2046|20.4695|11.39%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|6746.1436|6805.5641|59.4205|0.88%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|341.3507|333.1547|-8.1959|-2.4%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|399.0766|380.4035|-18.6731|-4.68%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|420.1942|497.5433|77.3491|18.41%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|99.6124|100.9538|1.3413|1.35%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|34.7398|35.4394|0.6996|2.01%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|182.6774|191.6728|8.9954|4.92%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|83.3992|81.5074|-1.8918|-2.27%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|46.3989|42.534|-3.8648|-8.33%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1328.3798|1343.1806|14.8008|1.11%|
|migraphx_torchvision__inceptioni1|PASS|regression|217.3152|233.0985|15.7833|7.26%|
|migraphx_torchvision__inceptioni32|PASS|within tol|6695.2145|6581.7695|-113.445|-1.69%|
|migraphx_torchvision__resnet50i1|PASS|within tol|89.4112|89.5124|0.1012|0.11%|
|migraphx_torchvision__resnet50i64|PASS|within tol|6219.2575|6112.4826|-106.775|-1.72%|
|migx_bench_bert-large-uncased_16_128|PASS|regression|2710.1648|3074.6249|364.4601|13.45%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4023.5635|4154.7231|131.1596|3.26%|
|migx_bench_bert-large-uncased_16_384|Numerics|progression|6182.3486|5645.488|-536.8607|-8.68%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|173.7295|153.5714|-20.158|-11.6%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|262.0503|264.9155|2.8652|1.09%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|381.9356|384.8431|2.9074|0.76%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|422.2134|523.564|101.3506|24.0%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|583.0038|715.4069|132.4031|22.71%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|866.2185|819.9747|-46.2438|-5.34%|
|migx_bench_bert-large-uncased_32_128|PASS|regression|5170.5053|5494.0886|323.5833|6.26%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8144.2655|8236.9395|92.674|1.14%|
|migx_bench_bert-large-uncased_32_384|Numerics|progression|12217.2744|11361.5392|-855.7352|-7.0%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|721.2307|729.7492|8.5185|1.18%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|1194.1016|1133.1388|-60.9628|-5.11%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|1628.646|1507.3179|-121.3281|-7.45%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1366.4576|1330.6263|-35.8312|-2.62%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2086.69|2098.5529|11.8629|0.57%|
|migx_bench_bert-large-uncased_8_384|PASS|progression|3125.8741|2927.9945|-197.8796|-6.33%|

## No Regressions Found

## No Progressions Found

