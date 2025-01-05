# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|91.9672|96.9976|5.0304|5.47%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|87.1762|94.8758|7.6995|8.83%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|541.0773|269.4994|-271.5779|-50.19%|
|migraphx_ORT__distilgpt2_1|PASS|regression|30.3333|32.0201|1.6868|5.56%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|959.1258|84.3165|-874.8093|-91.21%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|250.4315|249.0687|-1.3628|-0.54%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|39.8866|39.5226|-0.364|-0.91%|
|migraphx_bert__bert-large-uncased|PASS|within tol|371.6078|372.8474|1.2396|0.33%|
|migraphx_cadene__dpn92i1|PASS|within tol|171.0548|170.5803|-0.4745|-0.28%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|6087.5121|6135.4577|47.9456|0.79%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|323.83|323.5875|-0.2425|-0.07%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5111.673|5088.8498|-22.8232|-0.45%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|379.6692|384.8777|5.2084|1.37%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|417.6888|421.825|4.1362|0.99%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|90.765|89.616|-1.149|-1.27%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|31.9087|31.8281|-0.0807|-0.25%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|179.7218|182.5747|2.8529|1.59%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|81.8773|82.1684|0.2911|0.36%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|38.6591|47.0339|8.3748|21.66%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1571.7705|1608.8869|37.1165|2.36%|
|migraphx_torchvision__inceptioni1|PASS|within tol|194.6044|202.3287|7.7243|3.97%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5307.9437|5366.6648|58.7211|1.11%|
|migraphx_torchvision__resnet50i1|PASS|within tol|84.6763|86.854|2.1777|2.57%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5018.2133|4973.9337|-44.2796|-0.88%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2578.3211|2595.9211|17.6|0.68%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4177.3741|4034.0855|-143.2886|-3.43%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5781.9092|5656.1432|-125.766|-2.18%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|157.997|156.4215|-1.5755|-1.0%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|267.6755|257.7263|-9.9492|-3.72%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|378.0154|376.8285|-1.1869|-0.31%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|397.9221|391.051|-6.8711|-1.73%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|581.773|585.6455|3.8725|0.67%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|863.6119|809.8717|-53.7402|-6.22%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5077.4302|4949.824|-127.6062|-2.51%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|7882.1856|7960.1966|78.011|0.99%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11402.9321|11258.0007|-144.9314|-1.27%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|722.458|718.2766|-4.1813|-0.58%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1107.7837|1067.5879|-40.1958|-3.63%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1547.69|1561.2212|13.5312|0.87%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1288.2528|1319.4355|31.1827|2.42%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2137.6659|2041.0109|-96.655|-4.52%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2889.9112|2931.7642|41.853|1.45%|

## No Regressions Found

## 3 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|migraphx_bert__bertsquad-12|compilation|PASS|
|migraphx_sd__unet__model|import_model|compilation|
|migraphx_sdxl__unet__model|import_model|compilation|

