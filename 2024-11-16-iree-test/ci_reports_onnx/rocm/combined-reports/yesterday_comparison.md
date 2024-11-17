# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|114.7512|114.8676|0.1164|0.1%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|115.5932|115.2825|-0.3108|-0.27%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|368.5736|360.0215|-8.5521|-2.32%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|65.1017|64.4562|-0.6455|-0.99%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|72.0226|72.4398|0.4172|0.58%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|273.1728|273.7331|0.5603|0.21%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|39.4685|38.5686|-0.8999|-2.28%|
|migraphx_bert__bert-large-uncased|PASS|within tol|20.0508|20.0596|0.0088|0.04%|
|migraphx_bert__bertsquad-12|PASS|progression|212.4848|18.569|-193.9158|-91.26%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|151.4418|151.7209|0.2791|0.18%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|211.9861|212.5961|0.61|0.29%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.6124|7.4091|-0.2034|-2.67%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|44.7897|45.5008|0.7112|1.59%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|6.4801|6.5428|0.0626|0.97%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|30.9695|31.6899|0.7204|2.33%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|52.4298|52.7661|0.3363|0.64%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|27.8889|25.348|-2.5409|-9.11%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|19.8048|16.1594|-3.6453|-18.41%|
|migraphx_torchvision__densenet121i32|PASS|within tol|50.6606|50.6083|-0.0523|-0.1%|
|migraphx_torchvision__inceptioni1|PASS|within tol|15.7534|15.8588|0.1054|0.67%|
|migraphx_torchvision__inceptioni32|PASS|within tol|137.3149|137.7956|0.4807|0.35%|
|migraphx_torchvision__resnet50i64|PASS|within tol|182.3225|182.5002|0.1777|0.1%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|33.2674|33.2546|-0.0128|-0.04%|
|migx_bench_bert-large-uncased_16_256|PASS|regression|57.2588|156.8547|99.5959|173.94%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|72.79|73.1824|0.3923|0.54%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.595|13.5915|-0.0035|-0.03%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.8495|13.8302|-0.0193|-0.14%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.9148|19.9151|0.0003|0.0%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|13.4018|13.357|-0.0448|-0.33%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|14.0261|13.9461|-0.08|-0.57%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.5967|21.6128|0.016|0.07%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|68.3185|68.7629|0.4444|0.65%|
|migx_bench_bert-large-uncased_32_256|PASS|regression|103.6201|231.7549|128.1348|123.66%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|144.1594|144.5031|0.3437|0.24%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|15.0752|15.0368|-0.0384|-0.25%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|17.2922|17.4929|0.2007|1.16%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.4441|26.5176|0.0735|0.28%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|23.9578|19.8534|-4.1044|-17.13%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.8519|27.9047|0.0528|0.19%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|41.1818|41.342|0.1602|0.39%|

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

