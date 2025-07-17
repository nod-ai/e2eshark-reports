# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_bert__bert-large-uncased|PASS|regression|844.0106|1217.6099|373.5993|44.26%|
|migraphx_cadene__dpn92i1|PASS|progression|178.9237|167.7466|-11.1771|-6.25%|
|migraphx_cadene__inceptionv4i16|PASS|regression|5156.4291|5557.5233|401.0942|7.78%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|333.4802|316.7114|-16.7689|-5.03%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|453.0948|406.5554|-46.5393|-10.27%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|425.6061|428.0714|2.4653|0.58%|
|migraphx_mlperf__resnet50_v1|PASS|regression|86.7376|92.7257|5.9881|6.9%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|69.9233|64.8724|-5.0509|-7.22%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|211.07|256.0504|44.9804|21.31%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|59.5636|219.3771|159.8135|268.31%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|19.9958|19.8721|-0.1236|-0.62%|
|migraphx_torchvision__densenet121i32|PASS|regression|1442.0176|1517.7902|75.7726|5.25%|
|migraphx_torchvision__inceptioni1|PASS|progression|212.8718|189.967|-22.9048|-10.76%|
|migraphx_torchvision__resnet50i1|PASS|within tol|85.1198|83.9178|-1.202|-1.41%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1557.5842|1584.9867|27.4025|1.76%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5172.8402|5382.1731|209.333|4.05%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9523.2832|9566.8636|43.5804|0.46%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|306.3556|235.8701|-70.4855|-23.01%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|250.2113|390.6584|140.447|56.13%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|456.7516|365.5857|-91.1659|-19.96%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|258.9406|240.3459|-18.5947|-7.18%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|434.423|565.007|130.5841|30.06%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|665.2961|655.8313|-9.4648|-1.42%|
|migx_bench_bert-large-uncased_32_128|PASS|regression|5165.1558|5461.5429|296.3871|5.74%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|13798.1614|13868.5515|70.3901|0.51%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|24045.8405|23539.0715|-506.769|-2.11%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|433.8792|412.9934|-20.8858|-4.81%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|800.6764|810.7135|10.0371|1.25%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|1241.923|1316.5863|74.6632|6.01%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|786.1219|744.0918|-42.0301|-5.35%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1663.6506|1650.7039|-12.9467|-0.78%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3444.8753|3414.7021|-30.1732|-0.88%|

## No Regressions Found

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|feastconv_Opset17_graph_convolutions|compilation|PASS|

