# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|113.043|106.9966|-6.0464|-5.35%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|106.9895|108.3312|1.3417|1.25%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|454.4254|458.2663|3.8408|0.85%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|59.9569|60.0962|0.1392|0.23%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|61.1207|61.4061|0.2854|0.47%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|241.066|240.8885|-0.1776|-0.07%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|39.4521|35.617|-3.8352|-9.72%|
|migraphx_agentmodel__AgentModel|Numerics|regression|1.915|2.178|0.263|13.73%|
|migraphx_bert__bert-large-uncased|PASS|within tol|18.9551|19.402|0.4469|2.36%|
|migraphx_cadene__dpn92i1|PASS|regression|4.7483|5.0366|0.2883|6.07%|
|migraphx_cadene__inceptionv4i16|PASS|progression|31.7625|29.2359|-2.5266|-7.95%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|6.3145|6.5973|0.2828|4.48%|
|migraphx_cadene__resnext101_64x4di16|PASS|progression|67.3364|29.9669|-37.3694|-55.5%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.2198|7.1167|-0.1031|-1.43%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|26.3561|26.4311|0.0751|0.28%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|4.8317|4.8247|-0.007|-0.14%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|46.1557|46.3026|0.1469|0.32%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|45.2408|48.5011|3.2602|7.21%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|17.9076|19.031|1.1235|6.27%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|7.7458|8.2104|0.4646|6.0%|
|migraphx_torchvision__densenet121i32|PASS|progression|20.0427|18.1035|-1.9391|-9.68%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.8684|4.9123|0.0439|0.9%|
|migraphx_torchvision__inceptioni32|PASS|progression|30.6464|28.11|-2.5364|-8.28%|
|migraphx_torchvision__resnet50i1|PASS|within tol|3.5769|3.5736|-0.0034|-0.09%|
|migraphx_torchvision__resnet50i64|PASS|within tol|21.0321|20.7298|-0.3023|-1.44%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|32.0587|32.2106|0.1518|0.47%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|52.5394|53.4772|0.9378|1.78%|
|migx_bench_bert-large-uncased_16_384|PASS|regression|67.396|70.8668|3.4708|5.15%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.3048|12.1063|-0.1985|-1.61%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.5288|12.4914|-0.0374|-0.3%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.3266|19.332|0.0055|0.03%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.9226|12.8593|-0.0633|-0.49%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|22.602|13.7821|-8.8199|-39.02%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|186.914|20.6222|-166.2918|-88.97%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|65.0659|66.0849|1.019|1.57%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|96.935|97.6741|0.7391|0.76%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|136.6251|137.4404|0.8154|0.6%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.5082|14.436|-0.0722|-0.5%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|16.5962|16.7463|0.1502|0.9%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|24.9138|25.1369|0.2232|0.9%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|18.9188|32.8056|13.8868|73.4%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.2834|26.695|0.4116|1.57%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|38.6409|38.9152|0.2743|0.71%|

## 57 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|eca_nfnet_l0.ra2_in1k_train_vaiq|PASS|compiled_inference|
|eca_nfnet_l0.ra2_in1k_vaiq|PASS|compiled_inference|
|eca_nfnet_l1.ra2_in1k_train_vaiq|PASS|compiled_inference|
|eca_nfnet_l1.ra2_in1k_vaiq|PASS|compiled_inference|
|eca_nfnet_l2.ra3_in1k_vaiq|PASS|compiled_inference|
|eca_resnext26ts.ch_in1k_train_vaiq|PASS|compiled_inference|
|eca_resnext26ts.ch_in1k_vaiq|PASS|compiled_inference|
|ecaresnet101d_test_vaiq|PASS|compiled_inference|
|ecaresnet101d_vaiq|PASS|compiled_inference|
|ecaresnet269d|PASS|compiled_inference|
|ecaresnet26t_train_vaiq|PASS|compiled_inference|
|ecaresnet26t_vaiq|PASS|compiled_inference|
|ecaresnet50d_test_vaiq|PASS|compiled_inference|
|ecaresnet50d_vaiq|PASS|compiled_inference|
|ecaresnet50t_train_vaiq|PASS|compiled_inference|
|ecaresnet50t_vaiq|PASS|compiled_inference|
|ecaresnetlight_test_vaiq|PASS|compiled_inference|
|ecaresnetlight_vaiq|PASS|compiled_inference|
|model--Learning-sentiment-analysis-through-imdb-ds--SeNSiTivE|PASS|Numerics|
|model--bert-base-uncased-few-shot-k-64-finetuned-squad-seed-2--anas-awadalla|PASS|Numerics|
|model--bert-finetuned-ner--alwaysgetbetter|PASS|Numerics|
|model--bert-finetuned-ner--amartyobanerjee|PASS|Numerics|
|model--bert-finetuned-ner--bbbbearczx|PASS|Numerics|
|model--bert-finetuned-ner--huggingface-course|PASS|Numerics|
|model--bert-finetuned-ner--jatinshah|PASS|Numerics|
|model--bert-finetuned-ner--jfarmerphd|PASS|Numerics|
|model--bert-finetuned-ner--lddczcn|PASS|Numerics|
|model--bert-finetuned-ner--mldev|PASS|Numerics|
|model--bert-finetuned-ner--phijve|PASS|Numerics|
|model--bert-finetuned-ner--the-bee|PASS|Numerics|
|model--bert-finetuned-squad--Akihiro2|PASS|Numerics|
|model--bert-finetuned-squad--Neulvo|PASS|Numerics|
|model--bert-finetuned-squad--RyanM-R|PASS|Numerics|
|model--bert-finetuned-squad--Shanny|PASS|Numerics|
|model--bert-finetuned-squad--ZoeDuan|PASS|Numerics|
|model--bert-finetuned-squad--andrew234|PASS|Numerics|
|model--bert-finetuned-squad--ihfaudsip|PASS|Numerics|
|model--camembert_squadFR_question_answering_tools_fr--AntoineD|PASS|Numerics|
|model--finetuned_gpt2-medium_sst2_negation0.01--yuhuizhang|PASS|Numerics|
|model--finetuned_gpt2_sst2_negation0.0001_pretrainedTrue--yuhuizhang|PASS|Numerics|
|model--finetuned_gpt2_sst2_negation0.2_pretrainedFalse--yuhuizhang|PASS|Numerics|
|model--finetuned_gpt2_sst2_negation0.8_pretrainedFalse--yuhuizhang|PASS|Numerics|
|model--lsg-bart-base-4096-booksum--ccdv|PASS|Numerics|
|model--m2m100_418M-finetuned-kde4-en-to-pt_BR--danhsf|PASS|Numerics|
|model--marian-finetuned-kde4-en-to-fr--Thinkcru|PASS|Numerics|
|model--marian-finetuned-kde4-en-to-vi--huanvo88|PASS|Numerics|
|model--roberta-base-few-shot-k-128-finetuned-squad-seed-0--anas-awadalla|PASS|Numerics|
|model--roberta-base-few-shot-k-128-finetuned-squad-seed-42--anas-awadalla|PASS|Numerics|
|model--roberta-base-finetuned-squad-1--huxxx657|PASS|Numerics|
|model--roberta-base-squad2-nq--nlpconnect|PASS|Numerics|
|model--roberta-l-squadv1.1--vuiseng9|PASS|Numerics|
|model--roberta-large-few-shot-k-16-finetuned-squad-seed-2--anas-awadalla|PASS|Numerics|
|model--roberta-large_ner_conll2003--Gladiator|PASS|Numerics|
|model--roberta_large-unbalanced_simple-ner-conll2003_0908_v0--mariolinml|PASS|Numerics|
|model--tinyroberta-squad2--deepset|PASS|Numerics|
|vit_base_patch16_clip_384.laion2b_ft_in12k_in1k|PASS|Numerics|
|vit_large_patch14_clip_224.openai|PASS|Numerics|

## 35 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|convnext_large_mlp.clip_laion2b_ft_soup_320|Numerics|PASS|
|gluon_xception65|Numerics|PASS|
|maxvit_base_tf_224.in1k|Numerics|PASS|
|maxvit_rmlp_base_rw_224.sw_in12k_ft_in1k|Numerics|PASS|
|migx_bench_bert-large-uncased_2_256|Numerics|PASS|
|model--MEDIA_NLU-flaubert_oral_mixed--vpelloin|Numerics|PASS|
|model--bart-base-few-shot-k-128-finetuned-squad-seed-2--anas-awadalla|Numerics|PASS|
|model--bert-base-uncased-few-shot-k-1024-finetuned-squad-seed-4--anas-awadalla|Numerics|PASS|
|model--bert-base-uncased-few-shot-k-512-finetuned-squad-seed-6--anas-awadalla|Numerics|PASS|
|model--bert-finetuned-ner--DaveMSE|Numerics|PASS|
|model--bert-finetuned-ner--TofuNumber1|Numerics|PASS|
|model--bert-finetuned-ner--abkbvknv|Numerics|PASS|
|model--bert-finetuned-ner--carmeco|Numerics|PASS|
|model--bert-finetuned-ner--fancyerii|Numerics|PASS|
|model--bert-finetuned-ner--kosec39|Numerics|PASS|
|model--bert-finetuned-squad--arjunvinod|Numerics|PASS|
|model--bert-finetuned-squad--cxia47|compiled_inference|PASS|
|model--bert-finetuned-squad--mrp|Numerics|PASS|
|model--bert-large-qa--srcocotero|Numerics|PASS|
|model--distilbert-base-NER--51la5|Numerics|PASS|
|model--distilbert-base-uncased-finetuned-squad--en|Numerics|PASS|
|model--distilbert-base-uncased-finetuned-squad--kaggleodin|Numerics|PASS|
|model--electra-base-discriminator-finetuned-conll03-english--bhadresh-savani|Numerics|PASS|
|model--environmental-claims--climatebert|Numerics|PASS|
|model--finetuned-opt-squad-dataset-3--choohan|Numerics|PASS|
|model--finetuned_distilgpt2_sst2_negation0.001_pretrainedTrue_epochs3--jhaochenz|Numerics|PASS|
|model--finetuned_distilgpt2_sst2_negation0.01_pretrainedTrue_epochs1--jhaochenz|Numerics|PASS|
|model--finetuned_gpt2-large_sst2_negation0.01_pretrainedTrue_epochs1--jhaochenz|Numerics|PASS|
|model--finetuning-sentiment-model-3000-samples--Heer|Numerics|PASS|
|model--gpt2--openai-community|Numerics|PASS|
|model--marian-finetuned-kde4-en-to-ja--Hoax0930|Numerics|PASS|
|model--spanbert-base-cased-few-shot-k-128-finetuned-squad-seed-0--anas-awadalla|Numerics|PASS|
|model--splinter-large-few-shot-k-32-finetuned-squad-seed-2--anas-awadalla|Numerics|PASS|
|model--unisumm_3--vishw2703|Numerics|PASS|
|vit_base_patch16_384.augreg_in21k_ft_in1k|Numerics|PASS|

