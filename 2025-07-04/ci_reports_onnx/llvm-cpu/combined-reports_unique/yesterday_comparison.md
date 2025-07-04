# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_bert__bert-large-uncased|PASS|within tol|376.2203|370.5624|-5.6579|-1.5%|
|migraphx_cadene__dpn92i1|PASS|within tol|171.4343|169.3593|-2.075|-1.21%|
|migraphx_cadene__inceptionv4i16|PASS|regression|5285.7738|5660.7976|375.0238|7.09%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|313.877|327.4252|13.5483|4.32%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|404.4398|482.6561|78.2163|19.34%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|483.6769|474.7672|-8.9097|-1.84%|
|migraphx_mlperf__resnet50_v1|PASS|regression|93.5837|101.2016|7.6178|8.14%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|57.9563|400.316|342.3597|590.72%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|208.5557|315.4341|106.8783|51.25%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|78.082|60.3766|-17.7055|-22.68%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|72.9041|19.1593|-53.7448|-73.72%|
|migraphx_torchvision__densenet121i32|PASS|progression|2073.7538|1427.0278|-646.726|-31.19%|
|migraphx_torchvision__inceptioni1|PASS|within tol|213.564|221.084|7.52|3.52%|
|migraphx_torchvision__resnet50i1|PASS|progression|106.7972|98.0332|-8.764|-8.21%|
|migx_bench_bert-large-uncased_16_128|PASS|progression|1612.8758|1524.0601|-88.8157|-5.51%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5392.0632|5481.3136|89.2505|1.66%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9400.3828|9484.7264|84.3436|0.9%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|148.0392|151.0266|2.9874|2.02%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|266.3521|248.0611|-18.2911|-6.87%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|432.5491|365.9438|-66.6053|-15.4%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|341.487|246.072|-95.415|-27.94%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|821.1071|543.7837|-277.3235|-33.77%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|684.5703|680.9912|-3.5791|-0.52%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5229.7681|5384.5511|154.7829|2.96%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|13929.4273|14037.127|107.6998|0.77%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|23118.6354|23842.8501|724.2147|3.13%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|408.3042|409.7915|1.4874|0.36%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|787.3886|905.4618|118.0732|15.0%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1287.4411|1235.7249|-51.7163|-4.02%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|737.0489|743.1281|6.0791|0.82%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|1652.7038|2162.648|509.9442|30.86%|
|migx_bench_bert-large-uncased_8_384|PASS|regression|3380.3077|3743.4392|363.1316|10.74%|

## No Regressions Found

## No Progressions Found

