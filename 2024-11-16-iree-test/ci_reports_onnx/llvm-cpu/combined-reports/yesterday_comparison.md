# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|90.6437|88.6374|-2.0064|-2.21%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|89.877|93.6869|3.8099|4.24%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|298.1253|260.1549|-37.9704|-12.74%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|32.4918|33.4786|0.9868|3.04%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|85.3121|86.8756|1.5636|1.83%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|261.3374|254.4416|-6.8958|-2.64%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|39.6175|40.7668|1.1493|2.9%|
|migraphx_bert__bert-large-uncased|PASS|within tol|398.7672|386.0762|-12.691|-3.18%|
|migraphx_bert__bertsquad-12|PASS|within tol|89.3713|90.5307|1.1594|1.3%|
|migraphx_cadene__dpn92i1|PASS|progression|255.577|187.4836|-68.0934|-26.64%|
|migraphx_cadene__inceptionv4i16|PASS|regression|6452.9146|7572.0356|1119.1209|17.34%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|373.1304|387.9044|14.774|3.96%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|1043.8922|412.1807|-631.7115|-60.52%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|513.2748|459.2714|-54.0034|-10.52%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|86.1592|89.0314|2.8721|3.33%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|33.5085|57.3726|23.8641|71.22%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|181.4769|188.2072|6.7302|3.71%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|75.5628|73.5345|-2.0283|-2.68%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|48.9473|51.7133|2.766|5.65%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1362.0064|1361.1236|-0.8828|-0.06%|
|migraphx_torchvision__inceptioni1|PASS|within tol|209.0909|218.164|9.0731|4.34%|
|migraphx_torchvision__inceptioni32|PASS|within tol|6134.7584|6135.0096|0.2511|0.0%|
|migraphx_torchvision__resnet50i1|PASS|within tol|85.2605|88.2423|2.9818|3.5%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5212.5126|5243.7682|31.2556|0.6%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2626.4118|2704.9488|78.537|2.99%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4153.9255|4128.9933|-24.9322|-0.6%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5982.1335|5768.1232|-214.0102|-3.58%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|159.658|173.9565|14.2985|8.96%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|267.833|257.7257|-10.1074|-3.77%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|373.119|376.2723|3.1533|0.85%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|431.1777|472.023|40.8453|9.47%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|597.1035|611.0602|13.9567|2.34%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|853.4895|846.7863|-6.7032|-0.79%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5183.0206|5200.8218|17.8012|0.34%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8091.1391|8175.4398|84.3007|1.04%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11337.5176|11368.5036|30.986|0.27%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|723.5142|753.9553|30.4411|4.21%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1107.4869|1081.0205|-26.4664|-2.39%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1585.3593|1591.5477|6.1884|0.39%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1328.4378|1304.4585|-23.9792|-1.81%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2105.9574|2073.0932|-32.8643|-1.56%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3023.5928|3006.6997|-16.8931|-0.56%|

## No Regressions Found

## 47 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|dm_nfnet_f3.dm_in1k|import_model|PASS|
|dm_nfnet_f4.dm_in1k|import_model|PASS|
|model--YuisekinAI-mistral-0.7B--yuiseki|import_model|PASS|
|model--financial-summarization-pegasus--human-centered-summarization|import_model|PASS|
|model--finetuned_gpt2-large_sst2_negation0.0001_pretrainedTrue_epochs1--jhaochenz|import_model|PASS|
|model--finetuned_gpt2-large_sst2_negation0.001_pretrainedTrue_epochs1--jhaochenz|import_model|PASS|
|model--finetuned_gpt2-large_sst2_negation0.001_pretrainedTrue_epochs2--jhaochenz|import_model|PASS|
|model--finetuned_gpt2-large_sst2_negation0.001_pretrainedTrue_epochs3--jhaochenz|import_model|PASS|
|model--finetuned_gpt2-large_sst2_negation0.01--yuhuizhang|import_model|PASS|
|model--finetuned_gpt2-large_sst2_negation0.01_pretrainedFalse_epochs10--jhaochenz|import_model|PASS|
|model--finetuned_gpt2-large_sst2_negation0.01_pretrainedTrue_epochs1--jhaochenz|import_model|PASS|
|model--finetuned_gpt2-large_sst2_negation0.05--yuhuizhang|import_model|PASS|
|model--finetuned_gpt2-large_sst2_negation0.0_pretrainedFalse--yuhuizhang|import_model|PASS|
|model--finetuned_gpt2-large_sst2_negation0.1_pretrainedFalse_epochs10--jhaochenz|import_model|PASS|
|model--finetuned_gpt2-large_sst2_negation0.1_pretrainedTrue_epochs1--jhaochenz|import_model|PASS|
|model--finetuned_gpt2-large_sst2_negation0.2--yuhuizhang|import_model|PASS|
|model--finetuned_gpt2-large_sst2_negation0.5--yuhuizhang|import_model|PASS|
|model--finetuned_gpt2-large_sst2_negation0.5_pretrainedFalse--yuhuizhang|import_model|PASS|
|model--finetuned_gpt2-large_sst2_negation0.8--yuhuizhang|import_model|PASS|
|model--finetuned_gpt2-large_sst2_negation0.8_pretrainedFalse--yuhuizhang|import_model|PASS|
|model--flan-t5-large-samsum--oguuzhansahin|import_model|Numerics|
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP--pszemraj|import_model|Numerics|
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP13--pszemraj|import_model|Numerics|
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP14--pszemraj|import_model|Numerics|
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP15--pszemraj|import_model|Numerics|
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP17--pszemraj|import_model|Numerics|
|model--m2m100_418M-finetuned-kde4-en-to-pt_BR--danhsf|import_model|PASS|
|model--m2m100_418M-fr--Jour|import_model|PASS|
|model--m2m100_418M-fr--NDugar|import_model|PASS|
|model--m2m100_418M-ja--vivek-307306|import_model|Numerics|
|model--mT5-base-HunSum-1--SZTAKI-HLT|import_model|Numerics|
|model--mT5_multilingual_XLSum--csebuetnlp|import_model|Numerics|
|model--manifestoberta-xlm-roberta-56policy-topics-sentence-2023-1-1--manifesto-project|import_model|Numerics|
|model--my_xlm-roberta-large-finetuned-conll03--BahAdoR0101|import_model|Numerics|
|model--pegasus-cnn_dailymail--google|import_model|PASS|
|model--pegasus-large-book-summary--pszemraj|import_model|PASS|
|model--pegasus-large-booksum--cnicu|import_model|PASS|
|model--pegasus-large-summary-explain--pszemraj|import_model|PASS|
|model--pegasus-xsum--google|import_model|PASS|
|model--pegasus_summarizer--tuner007|import_model|PASS|
|model--roberta-ner-multilingual--julian-schelb|import_model|Numerics|
|model--t5-large-finetuned-xsum-cnn--sysresearch101|import_model|Numerics|
|model--tglobal-large-booksum-WIP4-r1--pszemraj|import_model|Numerics|
|model--xlm-roberta-large-squad2--deepset|import_model|Numerics|
|model--xlmr-large-qa-fa--m3hrdadfi|import_model|Numerics|
|vit_large_r50_s32_224.augreg_in21k_ft_in1k|import_model|PASS|
|vit_large_r50_s32_384.augreg_in21k_ft_in1k|import_model|PASS|

