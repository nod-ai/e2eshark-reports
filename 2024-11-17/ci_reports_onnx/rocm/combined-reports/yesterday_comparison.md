# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|114.7512|114.8946|0.1433|0.12%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|115.5932|114.7017|-0.8915|-0.77%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|368.5736|369.7793|1.2057|0.33%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|65.1017|63.0527|-2.049|-3.15%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|72.0226|72.1546|0.132|0.18%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|273.1728|274.5443|1.3715|0.5%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|39.4685|38.8575|-0.611|-1.55%|
|migraphx_bert__bert-large-uncased|PASS|within tol|20.0508|20.1554|0.1046|0.52%|
|migraphx_bert__bertsquad-12|PASS|within tol|212.4848|211.9121|-0.5727|-0.27%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|151.4418|152.1637|0.7218|0.48%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|211.9861|212.9788|0.9927|0.47%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.6124|7.5527|-0.0598|-0.78%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|44.7897|44.069|-0.7206|-1.61%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|6.4801|6.5736|0.0935|1.44%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|30.9695|33.2317|2.2622|7.3%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|52.4298|52.611|0.1812|0.35%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|27.8889|28.3214|0.4325|1.55%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|19.8048|18.1577|-1.6471|-8.32%|
|migraphx_torchvision__densenet121i32|PASS|within tol|50.6606|50.8828|0.2222|0.44%|
|migraphx_torchvision__inceptioni1|PASS|within tol|15.7534|15.8115|0.0581|0.37%|
|migraphx_torchvision__inceptioni32|PASS|within tol|137.3149|138.5917|1.2768|0.93%|
|migraphx_torchvision__resnet50i64|PASS|within tol|182.3225|182.7947|0.4722|0.26%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|33.2674|33.4548|0.1875|0.56%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|57.2588|57.7776|0.5188|0.91%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|72.79|73.558|0.768|1.06%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.595|13.5703|-0.0248|-0.18%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.8495|13.8497|0.0002|0.0%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.9148|20.0889|0.1741|0.87%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|13.4018|13.334|-0.0678|-0.51%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|14.0261|13.8804|-0.1458|-1.04%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.5967|21.6231|0.0264|0.12%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|68.3185|69.5853|1.2668|1.85%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|103.6201|104.9378|1.3177|1.27%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|144.1594|145.4364|1.277|0.89%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|15.0752|15.0161|-0.0591|-0.39%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|17.2922|17.4611|0.1689|0.98%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.4441|26.7998|0.3557|1.35%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|23.9578|20.1483|-3.8096|-15.9%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.8519|27.9555|0.1035|0.37%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|41.1818|41.451|0.2692|0.65%|

## No Regressions Found

## 45 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|dm_nfnet_f3.dm_in1k|import_model|compilation|
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
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP--pszemraj|import_model|compilation|
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP13--pszemraj|import_model|compilation|
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP14--pszemraj|import_model|compilation|
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP15--pszemraj|import_model|compilation|
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP17--pszemraj|import_model|compilation|
|model--m2m100_418M-finetuned-kde4-en-to-pt_BR--danhsf|import_model|PASS|
|model--m2m100_418M-fr--Jour|import_model|PASS|
|model--m2m100_418M-ja--vivek-307306|import_model|Numerics|
|model--mT5-base-HunSum-1--SZTAKI-HLT|import_model|Numerics|
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
|model--tglobal-large-booksum-WIP4-r1--pszemraj|import_model|compilation|
|model--xlm-roberta-large-squad2--deepset|import_model|Numerics|
|model--xlmr-large-qa-fa--m3hrdadfi|import_model|Numerics|
|vit_large_r50_s32_224.augreg_in21k_ft_in1k|import_model|Numerics|
|vit_large_r50_s32_384.augreg_in21k_ft_in1k|import_model|Numerics|

