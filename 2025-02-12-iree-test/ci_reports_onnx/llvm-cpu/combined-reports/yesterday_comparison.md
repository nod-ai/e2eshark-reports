# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|91.4571|96.402|4.9448|5.41%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|87.2637|90.2421|2.9784|3.41%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|259.8306|351.831|92.0005|35.41%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|31.9022|30.7296|-1.1726|-3.68%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|84.3611|87.4168|3.0557|3.62%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|285.6893|248.3184|-37.3709|-13.08%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|44.43|39.6539|-4.7761|-10.75%|
|migraphx_bert__bert-large-uncased|PASS|regression|377.463|447.2084|69.7453|18.48%|
|migraphx_cadene__dpn92i1|PASS|progression|213.1705|165.5948|-47.5757|-22.32%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5589.8876|5646.8224|56.9348|1.02%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|327.6704|466.3588|138.6884|42.33%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5447.6034|5398.9055|-48.6979|-0.89%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|396.7168|411.7654|15.0485|3.79%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|853.1963|431.1312|-422.0651|-49.47%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|99.3097|104.132|4.8223|4.86%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|32.7719|647.3216|614.5497|1875.23%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|190.8732|180.3133|-10.5598|-5.53%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|81.6663|75.5527|-6.1136|-7.49%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|48.6452|40.0678|-8.5775|-17.63%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1459.8546|1523.5102|63.6556|4.36%|
|migraphx_torchvision__inceptioni1|PASS|progression|212.6344|196.612|-16.0223|-7.54%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5760.1653|5843.7728|83.6075|1.45%|
|migraphx_torchvision__resnet50i1|PASS|progression|92.517|85.4582|-7.0588|-7.63%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5547.3481|5453.2149|-94.1332|-1.7%|
|migx_bench_bert-large-uncased_16_128|PASS|regression|2568.8803|2726.9641|158.0838|6.15%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4150.9137|4113.1342|-37.7795|-0.91%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5750.3374|5807.9082|57.5708|1.0%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|196.5953|161.7966|-34.7986|-17.7%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|267.7863|291.4299|23.6436|8.83%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|397.7102|391.1321|-6.578|-1.65%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|413.4168|397.9135|-15.5033|-3.75%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|581.1754|633.0082|51.8329|8.92%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|861.5294|803.9618|-57.5676|-6.68%|
|migx_bench_bert-large-uncased_32_128|PASS|regression|5280.3679|5714.8889|434.521|8.23%|
|migx_bench_bert-large-uncased_32_256|PASS|progression|8791.4271|8037.9143|-753.5128|-8.57%|
|migx_bench_bert-large-uncased_32_384|Numerics|progression|12055.7389|11322.2789|-733.46|-6.08%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|727.5331|713.7916|-13.7416|-1.89%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1073.8776|1097.8601|23.9824|2.23%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1538.3225|1533.7531|-4.5695|-0.3%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|1499.4313|1334.18|-165.2514|-11.02%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|2195.4659|2870.1305|674.6646|30.73%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2859.1175|2963.7843|104.6668|3.66%|

## No Regressions Found

## No Progressions Found

