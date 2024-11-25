# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|85.3789|87.6328|2.2539|2.64%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|95.2549|88.2342|-7.0208|-7.37%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|251.7842|254.6077|2.8235|1.12%|
|migraphx_ORT__distilgpt2_1|PASS|regression|31.561|36.3467|4.7857|15.16%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|88.824|83.544|-5.2801|-5.94%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|281.2738|243.4748|-37.7991|-13.44%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|42.7679|39.5702|-3.1977|-7.48%|
|migraphx_bert__bert-large-uncased|PASS|within tol|371.8883|373.2743|1.386|0.37%|
|migraphx_bert__bertsquad-12|PASS|within tol|82.5882|83.804|1.2158|1.47%|
|migraphx_cadene__dpn92i1|PASS|within tol|184.6085|179.7351|-4.8734|-2.64%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|6769.6225|6746.1436|-23.4789|-0.35%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|329.8314|341.3507|11.5193|3.49%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|404.6856|399.0766|-5.609|-1.39%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|446.566|420.1942|-26.3718|-5.91%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|99.2952|99.6124|0.3172|0.32%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|32.8038|34.7398|1.9359|5.9%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|196.3116|182.6774|-13.6342|-6.95%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|83.5107|83.3992|-0.1114|-0.13%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|42.4459|46.3989|3.953|9.31%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1330.6446|1328.3798|-2.2648|-0.17%|
|migraphx_torchvision__inceptioni1|PASS|progression|242.3683|217.3152|-25.0531|-10.34%|
|migraphx_torchvision__inceptioni32|PASS|within tol|6562.1364|6695.2145|133.0781|2.03%|
|migraphx_torchvision__resnet50i1|PASS|progression|102.6328|89.4112|-13.2216|-12.88%|
|migraphx_torchvision__resnet50i64|PASS|within tol|6052.1633|6219.2575|167.0943|2.76%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2718.2718|2710.1648|-8.107|-0.3%|
|migx_bench_bert-large-uncased_16_256|PASS|progression|4241.1567|4023.5635|-217.5931|-5.13%|
|migx_bench_bert-large-uncased_16_384|Numerics|regression|5850.6686|6182.3486|331.68|5.67%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|173.0572|173.7295|0.6722|0.39%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|294.8772|262.0503|-32.827|-11.13%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|377.7398|381.9356|4.1958|1.11%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|421.7127|422.2134|0.5006|0.12%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|598.7313|583.0038|-15.7275|-2.63%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|805.3156|866.2185|60.903|7.56%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5091.0538|5170.5053|79.4514|1.56%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|7884.0768|8144.2655|260.1887|3.3%|
|migx_bench_bert-large-uncased_32_384|Numerics|regression|11302.7939|12217.2744|914.4805|8.09%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|715.121|721.2307|6.1097|0.85%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1158.2945|1194.1016|35.8071|3.09%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|1537.9552|1628.646|90.6907|5.9%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|1296.8385|1366.4576|69.6191|5.37%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|2318.5807|2086.69|-231.8907|-10.0%|
|migx_bench_bert-large-uncased_8_384|PASS|regression|2946.3141|3125.8741|179.56|6.09%|

## No Regressions Found

## No Progressions Found

