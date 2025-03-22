# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|115.3427|116.1343|0.7915|0.69%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|115.9063|115.846|-0.0604|-0.05%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|518.027|519.6439|1.6169|0.31%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|68.9103|68.0165|-0.8938|-1.3%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|62.1858|63.8287|1.643|2.64%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|329.0408|331.9572|2.9164|0.89%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|35.3159|34.9253|-0.3906|-1.11%|
|migraphx_agentmodel__AgentModel|Numerics|within tol|2.1325|2.1852|0.0528|2.47%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.4587|19.3433|-0.1154|-0.59%|
|migraphx_cadene__dpn92i1|PASS|within tol|5.0455|5.0342|-0.0113|-0.22%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|29.6543|29.3663|-0.288|-0.97%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|6.1741|6.3022|0.1281|2.07%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|29.3962|29.5913|0.1952|0.66%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|6.9061|7.7001|0.794|11.5%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|27.1742|25.4892|-1.685|-6.2%|
|migraphx_mlperf__resnet50_v1|PASS|progression|5.1717|4.754|-0.4177|-8.08%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|38.0968|40.2896|2.1928|5.76%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|48.1533|46.74|-1.4133|-2.93%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|18.2589|17.6309|-0.628|-3.44%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|9.0826|7.5093|-1.5733|-17.32%|
|migraphx_torchvision__densenet121i32|PASS|within tol|17.8435|18.0043|0.1608|0.9%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.919|4.8582|-0.0608|-1.24%|
|migraphx_torchvision__inceptioni32|PASS|within tol|27.985|28.0163|0.0313|0.11%|
|migraphx_torchvision__resnet50i1|PASS|within tol|3.1727|3.2157|0.043|1.36%|
|migraphx_torchvision__resnet50i64|PASS|within tol|20.5284|20.7043|0.1759|0.86%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|26.914|27.6052|0.6912|2.57%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|38.5298|39.3083|0.7785|2.02%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|58.9187|59.4603|0.5416|0.92%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.1047|12.1702|0.0655|0.54%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.8209|12.6476|-0.1733|-1.35%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.5944|19.3687|-0.2258|-1.15%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.6382|12.4806|-0.1576|-1.25%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.582|19.549|-0.033|-0.17%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.3064|20.5927|0.2863|1.41%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|37.1624|37.8109|0.6484|1.74%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|77.8961|79.9782|2.082|2.67%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|119.822|121.8731|2.0511|1.71%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.5966|20.0035|0.4068|2.08%|
|migx_bench_bert-large-uncased_4_256|Numerics|within tol|20.7497|21.1478|0.398|1.92%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|24.0649|24.5322|0.4672|1.94%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.7979|21.0649|0.2669|1.28%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.4093|28.251|0.8417|3.07%|
|migx_bench_bert-large-uncased_8_384|PASS|regression|34.9555|38.5325|3.577|10.23%|

## 33 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|coatnet_3_rw_224.sw_in12k|PASS|Numerics|
|convnext_large_mlp.clip_laion2b_ft_soup_320|PASS|Numerics|
|migx_bench_bert-large-uncased_4_256|PASS|Numerics|
|model--SAE-distilbert-base-uncased-squad--jgammack|PASS|Numerics|
|model--bert-finetuned-ner--canLiu|PASS|Numerics|
|model--bert-finetuned-ner--jperezv|PASS|Numerics|
|model--bert-finetuned-ner--lyk0013|PASS|Numerics|
|model--bert-finetuned-ner--manoharahuggingface|PASS|Numerics|
|model--bert-finetuned-ner--mldev|PASS|Numerics|
|model--bert-finetuned-ner--mxalmeida|PASS|Numerics|
|model--bert-finetuned-ner--phijve|PASS|Numerics|
|model--bert-finetuned-ner--vikasaeta|PASS|Numerics|
|model--bert-finetuned-ner-trainer--marcellodomenis|PASS|Numerics|
|model--bert-finetuned-squad--MyMild|PASS|Numerics|
|model--bert-finetuned-squad--OMEGAROFLING|PASS|Numerics|
|model--bert-finetuned-squad--Shabdansh01|PASS|Numerics|
|model--bert-finetuned-squad--ZoeDuan|PASS|Numerics|
|model--bert-finetuned-squad--alvintu|PASS|Numerics|
|model--bert-finetuned-squad--andrew234|PASS|Numerics|
|model--bert-finetuned-squad--arjunvinod|PASS|Numerics|
|model--bert-finetuned-squad--gallyamovi|PASS|Numerics|
|model--bert-finetuned-squad-legalbert--Jasu|PASS|Numerics|
|model--bert-finetuned-squad22--makdong|PASS|Numerics|
|model--distilbert-base-uncased-finetuned-imdb--sahn|PASS|Numerics|
|model--finetuned_gpt2-medium_sst2_negation0.5_pretrainedFalse--yuhuizhang|PASS|Numerics|
|model--finetuned_gpt2_sst2_negation0.0001_pretrainedTrue--yuhuizhang|PASS|Numerics|
|model--m2m100_418M-fr--Jour|PASS|Numerics|
|model--marian-finetuned-kde4-en-to-es--tmobaggins|PASS|Numerics|
|model--marian-finetuned-kde4-en-to-fr--Yuch|PASS|Numerics|
|model--megatron-gpt2-345m--robowaifudev|PASS|Numerics|
|model--ner-bert-large-cased-pt-lenerbr--pierreguillou|PASS|Numerics|
|model--sentiment-model-imdb-small-demo--sachinshinde|PASS|Numerics|
|swinv2_large_window12to16_192to256.ms_in22k_ft_in1k|PASS|Numerics|

## 13 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|model--BERT_summary--Shobhank-iiitdwd|Numerics|PASS|
|model--bert-base-turkish-128k-cased-finetuned_lr-2e-05_epochs-3TQUAD2-finetuned_lr-2e-05_epochs-1--husnu|Numerics|PASS|
|model--bert-base-uncased-few-shot-k-256-finetuned-squad-seed-10--anas-awadalla|Numerics|PASS|
|model--bert-base-uncased-few-shot-k-256-finetuned-squad-seed-8--anas-awadalla|Numerics|PASS|
|model--bert-base-uncased-few-shot-k-32-finetuned-squad-seed-10--anas-awadalla|Numerics|PASS|
|model--bert-base-uncased-few-shot-k-32-finetuned-squad-seed-8--anas-awadalla|Numerics|PASS|
|model--bert-base-uncased-few-shot-k-512-finetuned-squad-seed-4--anas-awadalla|Numerics|PASS|
|model--bert-base-uncased-squad-v1--helenai|Numerics|PASS|
|model--bert-base-uncased-squadv1.1-sparse-80-1x4-block-pruneofa--Intel|Numerics|PASS|
|model--bert-finetuned-squad--rainanabul|Numerics|PASS|
|model--marian-finetuned-kde4-en-to-fr-2--Siqi|Numerics|PASS|
|model--nd-qna--Trisert|Numerics|PASS|
|poolformer_m36|Numerics|PASS|

