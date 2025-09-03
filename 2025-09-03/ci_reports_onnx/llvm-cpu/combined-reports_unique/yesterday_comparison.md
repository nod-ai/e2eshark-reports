# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|93.9268|76.5731|-17.3537|-18.48%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|74.6443|74.3915|-0.2527|-0.34%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|960.973|209.2272|-751.7458|-78.23%|
|migraphx_ORT__distilgpt2_1|PASS|regression|27.2594|31.9707|4.7113|17.28%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|121.6343|97.6259|-24.0084|-19.74%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|664.6782|266.8543|-397.8239|-59.85%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|45.424|44.9565|-0.4675|-1.03%|
|migraphx_bert__bert-large-uncased|PASS|progression|982.1124|366.6464|-615.466|-62.67%|
|migraphx_cadene__dpn92i1|PASS|regression|188.3194|200.0304|11.711|6.22%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|8826.45|8831.7309|5.2809|0.06%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|314.4395|298.4827|-15.9568|-5.07%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|450.1052|1042.3007|592.1955|131.57%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|466.2621|441.1086|-25.1535|-5.39%|
|migraphx_mlperf__resnet50_v1|PASS|regression|128.4616|150.4|21.9384|17.08%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|32.187|31.7376|-0.4493|-1.4%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|120.2354|119.6922|-0.5433|-0.45%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|67.5281|110.8246|43.2965|64.12%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|24.5943|19.7641|-4.8302|-19.64%|
|migraphx_torchvision__densenet121i32|PASS|within tol|2773.4801|2681.7979|-91.6823|-3.31%|
|migraphx_torchvision__inceptioni1|PASS|progression|314.2074|291.7335|-22.4738|-7.15%|
|migraphx_torchvision__resnet50i1|PASS|regression|146.3294|227.8563|81.5268|55.71%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1619.5991|1556.6367|-62.9624|-3.89%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5238.1989|5197.6745|-40.5245|-0.77%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9480.2962|9647.2629|166.9667|1.76%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|220.8321|149.9048|-70.9273|-32.12%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|324.2091|248.4374|-75.7716|-23.37%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|362.3257|490.5176|128.1919|35.38%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|393.9297|239.7457|-154.1839|-39.14%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|455.1262|464.8755|9.7493|2.14%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|866.674|652.1172|-214.5568|-24.76%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|4923.311|5049.5832|126.2721|2.56%|
|migx_bench_bert-large-uncased_32_256|PASS|progression|14410.9243|13382.0351|-1028.8893|-7.14%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|23825.8557|24166.3532|340.4975|1.43%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|400.6106|427.1145|26.5039|6.62%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|844.6714|794.7549|-49.9165|-5.91%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|1335.5995|1236.3867|-99.2128|-7.43%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|771.5889|784.8432|13.2543|1.72%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|1779.7091|1644.2385|-135.4706|-7.61%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3364.2253|3452.2292|88.0039|2.62%|

## No Regressions Found

## No Progressions Found

