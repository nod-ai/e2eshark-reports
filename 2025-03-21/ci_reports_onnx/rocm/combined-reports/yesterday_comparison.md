# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|116.9974|115.3427|-1.6546|-1.41%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|116.2794|115.9063|-0.373|-0.32%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|519.5249|518.027|-1.4979|-0.29%|
|migraphx_ORT__distilgpt2_1|PASS|progression|73.459|68.9103|-4.5487|-6.19%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|63.6401|62.1858|-1.4543|-2.29%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|331.4301|329.0408|-2.3893|-0.72%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|37.202|35.3159|-1.8861|-5.07%|
|migraphx_agentmodel__AgentModel|Numerics|regression|1.8384|2.1325|0.2941|16.0%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.3285|19.4587|0.1302|0.67%|
|migraphx_cadene__dpn92i1|PASS|within tol|5.0515|5.0455|-0.0059|-0.12%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|29.3417|29.6543|0.3126|1.07%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|5.8766|6.1741|0.2975|5.06%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|30.2299|29.3962|-0.8338|-2.76%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.0566|6.9061|-0.1505|-2.13%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|27.423|27.1742|-0.2489|-0.91%|
|migraphx_mlperf__resnet50_v1|PASS|regression|4.7431|5.1717|0.4287|9.04%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|40.465|38.0968|-2.3683|-5.85%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|46.8871|48.1533|1.2662|2.7%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|16.3322|18.2589|1.9267|11.8%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|9.0149|9.0826|0.0677|0.75%|
|migraphx_torchvision__densenet121i32|PASS|within tol|18.0245|17.8435|-0.1809|-1.0%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.8855|4.919|0.0335|0.69%|
|migraphx_torchvision__inceptioni32|PASS|within tol|28.0444|27.985|-0.0595|-0.21%|
|migraphx_torchvision__resnet50i1|PASS|within tol|3.1461|3.1727|0.0266|0.85%|
|migraphx_torchvision__resnet50i64|PASS|within tol|20.6455|20.5284|-0.1171|-0.57%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|27.6707|26.914|-0.7566|-2.73%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|39.2221|38.5298|-0.6923|-1.77%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|59.4712|58.9187|-0.5525|-0.93%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|11.9564|12.1047|0.1483|1.24%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.5369|12.8209|0.284|2.27%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.3559|19.5944|0.2385|1.23%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|15.0428|12.6382|-2.4046|-15.98%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.4514|19.582|0.1306|0.67%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.6052|20.3064|-0.2988|-1.45%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|37.9011|37.1624|-0.7387|-1.95%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|79.7014|77.8961|-1.8053|-2.27%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|121.767|119.822|-1.945|-1.6%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.5855|19.5966|0.0112|0.06%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|21.1552|20.7497|-0.4055|-1.92%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|24.7057|24.0649|-0.6407|-2.59%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|21.068|20.7979|-0.2701|-1.28%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|28.6473|27.4093|-1.238|-4.32%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|35.6655|34.9555|-0.7099|-1.99%|

## 13 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|model--BERT_summary--Shobhank-iiitdwd|PASS|Numerics|
|model--bert-base-turkish-128k-cased-finetuned_lr-2e-05_epochs-3TQUAD2-finetuned_lr-2e-05_epochs-1--husnu|PASS|Numerics|
|model--bert-base-uncased-few-shot-k-256-finetuned-squad-seed-10--anas-awadalla|PASS|Numerics|
|model--bert-base-uncased-few-shot-k-256-finetuned-squad-seed-8--anas-awadalla|PASS|Numerics|
|model--bert-base-uncased-few-shot-k-32-finetuned-squad-seed-10--anas-awadalla|PASS|Numerics|
|model--bert-base-uncased-few-shot-k-32-finetuned-squad-seed-8--anas-awadalla|PASS|Numerics|
|model--bert-base-uncased-few-shot-k-512-finetuned-squad-seed-4--anas-awadalla|PASS|Numerics|
|model--bert-base-uncased-squad-v1--helenai|PASS|Numerics|
|model--bert-base-uncased-squadv1.1-sparse-80-1x4-block-pruneofa--Intel|PASS|Numerics|
|model--bert-finetuned-squad--rainanabul|PASS|Numerics|
|model--marian-finetuned-kde4-en-to-fr-2--Siqi|PASS|Numerics|
|model--nd-qna--Trisert|PASS|Numerics|
|poolformer_m36|PASS|Numerics|

## No Progressions Found

