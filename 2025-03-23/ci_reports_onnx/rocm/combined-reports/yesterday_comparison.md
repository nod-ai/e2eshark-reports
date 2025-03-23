# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|116.1343|115.4644|-0.6698|-0.58%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|115.846|116.3287|0.4827|0.42%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|519.6439|773.2034|253.5595|48.79%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|68.0165|69.4178|1.4013|2.06%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|63.8287|66.9322|3.1035|4.86%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|331.9572|329.3035|-2.6537|-0.8%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.9253|33.8792|-1.046|-3.0%|
|migraphx_agentmodel__AgentModel|Numerics|progression|2.1852|1.5536|-0.6317|-28.91%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.3433|19.3637|0.0204|0.11%|
|migraphx_cadene__dpn92i1|PASS|within tol|5.0342|5.0592|0.025|0.5%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|29.3663|29.2689|-0.0975|-0.33%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|6.3022|5.9194|-0.3828|-6.07%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|29.5913|29.5886|-0.0027|-0.01%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|7.7001|7.1668|-0.5333|-6.93%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|25.4892|28.0655|2.5764|10.11%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|4.754|4.8152|0.0612|1.29%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|40.2896|38.3082|-1.9814|-4.92%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|46.74|46.3327|-0.4074|-0.87%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|17.6309|17.9767|0.3458|1.96%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|7.5093|8.1037|0.5945|7.92%|
|migraphx_torchvision__densenet121i32|PASS|within tol|18.0043|17.8623|-0.142|-0.79%|
|migraphx_torchvision__inceptioni1|PASS|regression|4.8582|7.204|2.3458|48.28%|
|migraphx_torchvision__inceptioni32|PASS|within tol|28.0163|27.9652|-0.0511|-0.18%|
|migraphx_torchvision__resnet50i1|PASS|regression|3.2157|4.6945|1.4788|45.99%|
|migraphx_torchvision__resnet50i64|PASS|within tol|20.7043|20.5197|-0.1846|-0.89%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|27.6052|26.9057|-0.6995|-2.53%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|39.3083|38.5985|-0.7099|-1.81%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|59.4603|58.5457|-0.9146|-1.54%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.1702|12.0593|-0.1109|-0.91%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.6476|12.5977|-0.0499|-0.39%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.3687|19.408|0.0393|0.2%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.4806|12.5882|0.1076|0.86%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.549|19.5792|0.0302|0.15%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.5927|20.3661|-0.2267|-1.1%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|37.8109|37.193|-0.6178|-1.63%|
|migx_bench_bert-large-uncased_32_256|PASS|regression|79.9782|129.163|49.1848|61.5%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|121.8731|120.3554|-1.5177|-1.25%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|20.0035|19.5676|-0.4359|-2.18%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|21.1478|20.4934|-0.6543|-3.09%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|24.5322|24.0793|-0.4528|-1.85%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|21.0649|20.8792|-0.1857|-0.88%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|28.251|27.3896|-0.8614|-3.05%|
|migx_bench_bert-large-uncased_8_384|PASS|progression|38.5325|34.9883|-3.5442|-9.2%|

## 30 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|maxvit_base_tf_512.in21k_ft_in1k|PASS|Numerics|
|model--BERT_summary--Shobhank-iiitdwd|PASS|Numerics|
|model--Jasmine-350M--UBC-NLP|PASS|Numerics|
|model--MEDIA_NLU-flaubert_oral_mixed--vpelloin|PASS|Numerics|
|model--bart-base-few-shot-k-128-finetuned-squad-seed-4--anas-awadalla|PASS|Numerics|
|model--bart-base-few-shot-k-512-finetuned-squad-seed-4--anas-awadalla|PASS|Numerics|
|model--bart-large-cnn-samsum--philschmid|PASS|Numerics|
|model--bart-large-finetuned-squadv1--valhalla|PASS|Numerics|
|model--bert-base-uncased-few-shot-k-128-finetuned-squad-seed-2--anas-awadalla|PASS|Numerics|
|model--bert-finetuned-ner--azuresonance|PASS|Numerics|
|model--bert-finetuned-ner--chandrasutrisnotjhong|PASS|Numerics|
|model--bert-finetuned-ner--yinxiaoz|PASS|Numerics|
|model--bert-finetuned-squad--Lexie79|PASS|Numerics|
|model--bert-finetuned-squad--lewtun|PASS|Numerics|
|model--bert-finetuned-squad--rghosh8|PASS|Numerics|
|model--bert-finetuned-squad--spasis|PASS|Numerics|
|model--bert-finetuned-squad--tmgondal|PASS|Numerics|
|model--bert-qa-en--srcocotero|PASS|Numerics|
|model--biobert-base-cased-v1.2_ncbi_disease-softmax-labelall-ner--jordyvl|PASS|Numerics|
|model--deberta-v3-base-squad2--deepset|PASS|Numerics|
|model--deberta-v3-large-squad2--deepset|PASS|Numerics|
|model--distilbert-base-cased-finetuned-conll03-english--elastic|PASS|Numerics|
|model--finetuned_gpt2-medium_sst2_negation0.0_pretrainedFalse--yuhuizhang|PASS|Numerics|
|model--finetuned_gpt2-medium_sst2_negation0.2_pretrainedFalse--yuhuizhang|PASS|Numerics|
|model--finetuning-sentiment-model-3000-samples--rh-jayson|PASS|Numerics|
|model--m2m100_418M-finetuned-kde4-en-to-pt_BR--danhsf|PASS|Numerics|
|model--xlm-roberta-base-kyrgyzNER--the-cramer-project|PASS|Numerics|
|tf_efficientnet_l2.ns_jft_in1k_475|PASS|Numerics|
|vit_relpos_base_patch16_clsgap_224.sw_in1k|PASS|Numerics|
|xcit_large_24_p8_224_dist|PASS|Numerics|

## 33 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|coatnet_3_rw_224.sw_in12k|Numerics|PASS|
|convnext_large_mlp.clip_laion2b_ft_soup_320|Numerics|PASS|
|migx_bench_bert-large-uncased_4_256|Numerics|PASS|
|model--SAE-distilbert-base-uncased-squad--jgammack|Numerics|PASS|
|model--bert-finetuned-ner--canLiu|Numerics|PASS|
|model--bert-finetuned-ner--jperezv|Numerics|PASS|
|model--bert-finetuned-ner--lyk0013|Numerics|PASS|
|model--bert-finetuned-ner--manoharahuggingface|Numerics|PASS|
|model--bert-finetuned-ner--mldev|Numerics|PASS|
|model--bert-finetuned-ner--mxalmeida|Numerics|PASS|
|model--bert-finetuned-ner--phijve|Numerics|PASS|
|model--bert-finetuned-ner--vikasaeta|Numerics|PASS|
|model--bert-finetuned-ner-trainer--marcellodomenis|Numerics|PASS|
|model--bert-finetuned-squad--MyMild|Numerics|PASS|
|model--bert-finetuned-squad--OMEGAROFLING|Numerics|PASS|
|model--bert-finetuned-squad--Shabdansh01|Numerics|PASS|
|model--bert-finetuned-squad--ZoeDuan|Numerics|PASS|
|model--bert-finetuned-squad--alvintu|Numerics|PASS|
|model--bert-finetuned-squad--andrew234|Numerics|PASS|
|model--bert-finetuned-squad--arjunvinod|Numerics|PASS|
|model--bert-finetuned-squad--gallyamovi|Numerics|PASS|
|model--bert-finetuned-squad-legalbert--Jasu|Numerics|PASS|
|model--bert-finetuned-squad22--makdong|Numerics|PASS|
|model--distilbert-base-uncased-finetuned-imdb--sahn|Numerics|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.5_pretrainedFalse--yuhuizhang|Numerics|PASS|
|model--finetuned_gpt2_sst2_negation0.0001_pretrainedTrue--yuhuizhang|Numerics|PASS|
|model--m2m100_418M-fr--Jour|Numerics|PASS|
|model--marian-finetuned-kde4-en-to-es--tmobaggins|Numerics|PASS|
|model--marian-finetuned-kde4-en-to-fr--Yuch|Numerics|PASS|
|model--megatron-gpt2-345m--robowaifudev|Numerics|PASS|
|model--ner-bert-large-cased-pt-lenerbr--pierreguillou|Numerics|PASS|
|model--sentiment-model-imdb-small-demo--sachinshinde|Numerics|PASS|
|swinv2_large_window12to16_192to256.ms_in22k_ft_in1k|Numerics|PASS|

