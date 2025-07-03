# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_bert__bert-large-uncased|PASS|within tol|371.3831|376.2203|4.8372|1.3%|
|migraphx_cadene__dpn92i1|PASS|within tol|163.8095|171.4343|7.6248|4.65%|
|migraphx_cadene__inceptionv4i16|PASS|progression|6271.4528|5285.7738|-985.679|-15.72%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|367.1598|313.877|-53.2828|-14.51%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|682.5319|404.4398|-278.0922|-40.74%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|434.0889|483.6769|49.588|11.42%|
|migraphx_mlperf__resnet50_v1|PASS|progression|105.8073|93.5837|-12.2235|-11.55%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|58.2708|57.9563|-0.3145|-0.54%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|273.3459|208.5557|-64.7901|-23.7%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|57.2531|78.082|20.8289|36.38%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|18.2563|72.9041|54.6479|299.34%|
|migraphx_torchvision__densenet121i32|PASS|regression|1568.2771|2073.7538|505.4768|32.23%|
|migraphx_torchvision__inceptioni1|PASS|within tol|219.0242|213.564|-5.4602|-2.49%|
|migraphx_torchvision__resnet50i1|PASS|regression|82.9492|106.7972|23.848|28.75%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1559.7128|1612.8758|53.163|3.41%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5160.355|5392.0632|231.7081|4.49%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9433.9747|9400.3828|-33.5919|-0.36%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|166.9145|148.0392|-18.8754|-11.31%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|345.2077|266.3521|-78.8556|-22.84%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|381.8995|432.5491|50.6496|13.26%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|256.5434|341.487|84.9436|33.11%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|429.8277|821.1071|391.2794|91.03%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|674.8351|684.5703|9.7352|1.44%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5238.9189|5229.7681|-9.1508|-0.17%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|14081.7321|13929.4273|-152.3048|-1.08%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|24184.3488|23118.6354|-1065.7134|-4.41%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|409.7059|408.3042|-1.4018|-0.34%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|791.8012|787.3886|-4.4126|-0.56%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1230.6828|1287.4411|56.7583|4.61%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|755.9761|737.0489|-18.9272|-2.5%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1669.0871|1652.7038|-16.3833|-0.98%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3553.7549|3380.3077|-173.4473|-4.88%|

## No Regressions Found

## No Progressions Found

