# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|76.0591|93.9268|17.8677|23.49%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|77.1963|74.6443|-2.552|-3.31%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|211.4477|960.973|749.5253|354.47%|
|migraphx_ORT__distilgpt2_1|PASS|progression|32.5201|27.2594|-5.2607|-16.18%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|99.9934|121.6343|21.6409|21.64%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|258.7148|664.6782|405.9634|156.92%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|360.4961|45.424|-315.0721|-87.4%|
|migraphx_bert__bert-large-uncased|PASS|regression|421.017|982.1124|561.0955|133.27%|
|migraphx_cadene__dpn92i1|PASS|within tol|181.0579|188.3194|7.2615|4.01%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|8842.0155|8826.45|-15.5655|-0.18%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|677.8561|314.4395|-363.4166|-53.61%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|696.9842|450.1052|-246.8789|-35.42%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|554.0199|466.2621|-87.7578|-15.84%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|128.5882|128.4616|-0.1266|-0.1%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|31.7809|32.187|0.4061|1.28%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|134.7497|120.2354|-14.5142|-10.77%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|67.4765|67.5281|0.0515|0.08%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|21.167|24.5943|3.4273|16.19%|
|migraphx_torchvision__densenet121i32|PASS|within tol|2704.9867|2773.4801|68.4935|2.53%|
|migraphx_torchvision__inceptioni1|PASS|within tol|329.3619|314.2074|-15.1545|-4.6%|
|migraphx_torchvision__resnet50i1|PASS|regression|138.6947|146.3294|7.6348|5.5%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1675.659|1619.5991|-56.0599|-3.35%|
|migx_bench_bert-large-uncased_16_256|PASS|progression|5745.0328|5238.1989|-506.8339|-8.82%|
|migx_bench_bert-large-uncased_16_384|Numerics|progression|12626.6234|9480.2962|-3146.3273|-24.92%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|165.1038|220.8321|55.7283|33.75%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|306.2243|324.2091|17.9848|5.87%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|381.7424|362.3257|-19.4167|-5.09%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|240.1971|393.9297|153.7325|64.0%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|652.9631|455.1262|-197.8369|-30.3%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|667.1089|866.674|199.5652|29.91%|
|migx_bench_bert-large-uncased_32_128|PASS|progression|5356.0779|4923.311|-432.7669|-8.08%|
|migx_bench_bert-large-uncased_32_256|PASS|regression|13635.9332|14410.9243|774.9911|5.68%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|23281.5892|23825.8557|544.2665|2.34%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|488.0407|400.6106|-87.4301|-17.91%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|789.365|844.6714|55.3064|7.01%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|1243.5156|1335.5995|92.0839|7.41%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|764.8219|771.5889|6.767|0.88%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|1693.1827|1779.7091|86.5264|5.11%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3452.7081|3364.2253|-88.4828|-2.56%|

## No Regressions Found

## No Progressions Found

