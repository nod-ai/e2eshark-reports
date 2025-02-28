# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|109.0737|113.043|3.9693|3.64%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|109.7362|106.9895|-2.7467|-2.5%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|463.6887|454.4254|-9.2633|-2.0%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|60.5984|59.9569|-0.6415|-1.06%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|61.3912|61.1207|-0.2705|-0.44%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|239.7181|241.066|1.348|0.56%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|40.5043|39.4521|-1.0521|-2.6%|
|migraphx_agentmodel__AgentModel|Numerics|progression|2.0523|1.915|-0.1373|-6.69%|
|migraphx_bert__bert-large-uncased|PASS|within tol|18.9389|18.9551|0.0162|0.09%|
|migraphx_cadene__dpn92i1|PASS|progression|5.0786|4.7483|-0.3304|-6.5%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|32.0376|31.7625|-0.2751|-0.86%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|6.2822|6.3145|0.0323|0.51%|
|migraphx_cadene__resnext101_64x4di16|PASS|regression|30.3212|67.3364|37.0152|122.08%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.543|7.2198|-0.3232|-4.28%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|26.7562|26.3561|-0.4001|-1.5%|
|migraphx_mlperf__resnet50_v1|PASS|progression|5.1941|4.8317|-0.3624|-6.98%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|44.7987|46.1557|1.357|3.03%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|45.6185|45.2408|-0.3777|-0.83%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|17.6779|17.9076|0.2296|1.3%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|7.8421|7.7458|-0.0963|-1.23%|
|migraphx_torchvision__densenet121i32|PASS|within tol|20.1092|20.0427|-0.0665|-0.33%|
|migraphx_torchvision__inceptioni1|PASS|within tol|5.0|4.8684|-0.1316|-2.63%|
|migraphx_torchvision__inceptioni32|PASS|within tol|30.7382|30.6464|-0.0918|-0.3%|
|migraphx_torchvision__resnet50i1|PASS|within tol|3.7255|3.5769|-0.1486|-3.99%|
|migraphx_torchvision__resnet50i64|PASS|within tol|21.1234|21.0321|-0.0914|-0.43%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|32.3153|32.0587|-0.2565|-0.79%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|53.2748|52.5394|-0.7354|-1.38%|
|migx_bench_bert-large-uncased_16_384|PASS|progression|74.4357|67.396|-7.0398|-9.46%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.085|12.3048|0.2198|1.82%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.5009|12.5288|0.0278|0.22%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|43.5868|19.3266|-24.2603|-55.66%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.934|12.9226|-0.0113|-0.09%|
|migx_bench_bert-large-uncased_2_256|Numerics|regression|13.4062|22.602|9.1958|68.59%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|20.6821|186.914|166.2319|803.75%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|66.101|65.0659|-1.0351|-1.57%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|98.7815|96.935|-1.8465|-1.87%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|138.7715|136.6251|-2.1464|-1.55%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.9117|14.5082|-0.4035|-2.71%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|16.5042|16.5962|0.092|0.56%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|24.9858|24.9138|-0.072|-0.29%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|44.1883|18.9188|-25.2695|-57.19%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.2691|26.2834|-0.9857|-3.61%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|38.8862|38.6409|-0.2453|-0.63%|

## 35 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|convnext_large_mlp.clip_laion2b_ft_soup_320|PASS|Numerics|
|gluon_xception65|PASS|Numerics|
|maxvit_base_tf_224.in1k|PASS|Numerics|
|maxvit_rmlp_base_rw_224.sw_in12k_ft_in1k|PASS|Numerics|
|migx_bench_bert-large-uncased_2_256|PASS|Numerics|
|model--MEDIA_NLU-flaubert_oral_mixed--vpelloin|PASS|Numerics|
|model--bart-base-few-shot-k-128-finetuned-squad-seed-2--anas-awadalla|PASS|Numerics|
|model--bert-base-uncased-few-shot-k-1024-finetuned-squad-seed-4--anas-awadalla|PASS|Numerics|
|model--bert-base-uncased-few-shot-k-512-finetuned-squad-seed-6--anas-awadalla|PASS|Numerics|
|model--bert-finetuned-ner--DaveMSE|PASS|Numerics|
|model--bert-finetuned-ner--TofuNumber1|PASS|Numerics|
|model--bert-finetuned-ner--abkbvknv|PASS|Numerics|
|model--bert-finetuned-ner--carmeco|PASS|Numerics|
|model--bert-finetuned-ner--fancyerii|PASS|Numerics|
|model--bert-finetuned-ner--kosec39|PASS|Numerics|
|model--bert-finetuned-squad--arjunvinod|PASS|Numerics|
|model--bert-finetuned-squad--cxia47|PASS|compiled_inference|
|model--bert-finetuned-squad--mrp|PASS|Numerics|
|model--bert-large-qa--srcocotero|PASS|Numerics|
|model--distilbert-base-NER--51la5|PASS|Numerics|
|model--distilbert-base-uncased-finetuned-squad--en|PASS|Numerics|
|model--distilbert-base-uncased-finetuned-squad--kaggleodin|PASS|Numerics|
|model--electra-base-discriminator-finetuned-conll03-english--bhadresh-savani|PASS|Numerics|
|model--environmental-claims--climatebert|PASS|Numerics|
|model--finetuned-opt-squad-dataset-3--choohan|PASS|Numerics|
|model--finetuned_distilgpt2_sst2_negation0.001_pretrainedTrue_epochs3--jhaochenz|PASS|Numerics|
|model--finetuned_distilgpt2_sst2_negation0.01_pretrainedTrue_epochs1--jhaochenz|PASS|Numerics|
|model--finetuned_gpt2-large_sst2_negation0.01_pretrainedTrue_epochs1--jhaochenz|PASS|Numerics|
|model--finetuning-sentiment-model-3000-samples--Heer|PASS|Numerics|
|model--gpt2--openai-community|PASS|Numerics|
|model--marian-finetuned-kde4-en-to-ja--Hoax0930|PASS|Numerics|
|model--spanbert-base-cased-few-shot-k-128-finetuned-squad-seed-0--anas-awadalla|PASS|Numerics|
|model--splinter-large-few-shot-k-32-finetuned-squad-seed-2--anas-awadalla|PASS|Numerics|
|model--unisumm_3--vishw2703|PASS|Numerics|
|vit_base_patch16_384.augreg_in21k_ft_in1k|PASS|Numerics|

## 72 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|convnext_large.fb_in22k_ft_in1k_384|Numerics|PASS|
|convnext_xlarge.fb_in22k_ft_in1k_384|Numerics|PASS|
|convnextv2_base.fcmae_ft_in22k_in1k|Numerics|PASS|
|deit_base_distilled_patch16_384.fb_in1k|Numerics|PASS|
|maxvit_rmlp_small_rw_224.sw_in1k|Numerics|PASS|
|migx_bench_bert-large-uncased_4_256|Numerics|PASS|
|model--MTL-bert-base-uncased-ww-squad--jgammack|Numerics|PASS|
|model--MetaQA--haritzpuerto|Numerics|PASS|
|model--bert-base-cased-finetuned-squad--Seongkyu|Numerics|PASS|
|model--bert-base-cased-finetuned-squad--ss756|compiled_inference|PASS|
|model--bert-base-uncased-finetuned-squad--harveyagraphcore|Numerics|PASS|
|model--bert-finetuned-ner--Hasanmurad|Numerics|PASS|
|model--bert-finetuned-ner--JAS100|Numerics|PASS|
|model--bert-finetuned-ner--amartyobanerjee|Numerics|PASS|
|model--bert-finetuned-ner--mxalmeida|Numerics|PASS|
|model--bert-finetuned-ner--suonbo|Numerics|PASS|
|model--bert-finetuned-ner--tomjam|Numerics|PASS|
|model--bert-finetuned-ner--yixi|Numerics|PASS|
|model--bert-finetuned-squad--Asmit|Numerics|PASS|
|model--bert-finetuned-squad--Dylan1999|Numerics|PASS|
|model--bert-finetuned-squad--OMEGAROFLING|Numerics|PASS|
|model--bert-finetuned-squad--Pranath|Numerics|PASS|
|model--bert-finetuned-squad--TheWayEX|Numerics|PASS|
|model--bert-finetuned-squad--bbbbearczx|Numerics|PASS|
|model--bert-finetuned-squad--jfarmerphd|Numerics|PASS|
|model--bert-finetuned-squad--jmoraes|Numerics|PASS|
|model--bert-finetuned-squad--nickong|Numerics|PASS|
|model--bert-finetuned-squad--spasis|Numerics|PASS|
|model--bert-finetuned-squad-legalbert--Jasu|Numerics|PASS|
|model--bert-large-NER--51la5|Numerics|PASS|
|model--distilbert-base-cased-finetuned-conll03-english--elastic|Numerics|PASS|
|model--distilbert-base-uncased-finetuned-conll03-english--elastic|Numerics|PASS|
|model--distilbert-base-uncased-finetuned-squad--emre|Numerics|PASS|
|model--distilbert-base-uncased-finetuned-squad--gudjonk93|Numerics|PASS|
|model--distilbert-base-uncased-finetuned-squad--kenlevine|Numerics|PASS|
|model--electra-finetuned-cpgqa--hung200504|Numerics|PASS|
|model--finetuned-opt-squad-dataset--choohan|Numerics|PASS|
|model--finetuned_gpt2-large_sst2_negation0.2--yuhuizhang|Numerics|PASS|
|model--finetuned_gpt2-large_sst2_negation0.5_pretrainedFalse--yuhuizhang|Numerics|PASS|
|model--finetuned_gpt2-large_sst2_negation0.8_pretrainedFalse--yuhuizhang|Numerics|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.01_pretrainedFalse_epochs3--jhaochenz|Numerics|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.01_pretrainedTrue_epochs1--jhaochenz|Numerics|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.2_pretrainedFalse--yuhuizhang|Numerics|PASS|
|model--finetuned_gpt2_sst2_negation0.0001_pretrainedTrue--yuhuizhang|Numerics|PASS|
|model--finetuned_gpt2_sst2_negation0.8_pretrainedFalse--yuhuizhang|Numerics|PASS|
|model--finetuning-movie-sentiment-model-9000-samples--Manishkalra|Numerics|PASS|
|model--finetuning-sentiment-model-3000-samples--Hackerino|Numerics|PASS|
|model--finetuning-sentiment-model-3000-samples--KarimKhalil|Numerics|PASS|
|model--finetuning-sentiment-model-3000-samples--PeterKh|Numerics|PASS|
|model--finetuning-sentiment-model-3000-samples--csam|Numerics|PASS|
|model--finetuning-sentiment-model-3000-samples--monusingh|compiled_inference|PASS|
|model--first_finetuning-sentiment-model-3000-samples--Positroniy|Numerics|PASS|
|model--gpt2_wikitext37_7k_pretrained_iphone_1e4--himanshubeniwal|Numerics|PASS|
|model--marian-finetuned-kde4-en-to-fr--miesnerjacob|Numerics|PASS|
|model--marian-finetuned-kde4-en-to-fr--mxalmeida|Numerics|PASS|
|model--my_awesome_qa_model--satyamverma|Numerics|PASS|
|model--ov-gpt2-fp32-kv-cache--vuiseng9|Numerics|PASS|
|model--roberta-base-few-shot-k-128-finetuned-squad-seed-8--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-32-finetuned-squad-seed-10--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-512-finetuned-squad-seed-8--anas-awadalla|Numerics|PASS|
|model--roberta-base-finetuned-squad--Firat|Numerics|PASS|
|model--roberta-base-finetuned-squad-3--huxxx657|Numerics|PASS|
|model--roberta-base-spanish-squades--IIC|Numerics|PASS|
|model--roberta-large-finetuned-ner--romainlhardy|Numerics|PASS|
|model--roberta-large-synqa-ext--mbartolo|Numerics|PASS|
|model--roberta_shared_bbc_xsum--patrickvonplaten|Numerics|PASS|
|model--sentiment-model-sample--jkhan447|Numerics|PASS|
|model--spanbert-base-cased-few-shot-k-16-finetuned-squad-seed-8--anas-awadalla|Numerics|PASS|
|model--spanbert-base-cased-few-shot-k-32-finetuned-squad-seed-2--anas-awadalla|Numerics|PASS|
|model--xlm-roberta-base-squad2--deepset|Numerics|PASS|
|model--xlm-roberta-ner-japanese--tsmatz|Numerics|PASS|
|swin_small_patch4_window7_224.ms_in1k|Numerics|PASS|

