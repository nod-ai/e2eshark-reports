# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|90.6437|86.7434|-3.9004|-4.3%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|89.877|120.0247|30.1476|33.54%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|298.1253|287.67|-10.4553|-3.51%|
|migraphx_ORT__distilgpt2_1|PASS|regression|32.4918|95.476|62.9842|193.85%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|85.3121|87.1228|1.8107|2.12%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|261.3374|265.1438|3.8064|1.46%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|39.6175|39.9035|0.286|0.72%|
|migraphx_bert__bert-large-uncased|PASS|within tol|398.7672|390.7993|-7.9679|-2.0%|
|migraphx_bert__bertsquad-12|PASS|regression|89.3713|1418.8174|1329.4461|1487.55%|
|migraphx_cadene__dpn92i1|PASS|progression|255.577|185.374|-70.203|-27.47%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|6452.9146|6595.9829|143.0683|2.22%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|373.1304|338.1451|-34.9853|-9.38%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|1043.8922|412.8859|-631.0064|-60.45%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|513.2748|457.5796|-55.6952|-10.85%|
|migraphx_mlperf__resnet50_v1|PASS|regression|86.1592|90.9894|4.8301|5.61%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|33.5085|33.9066|0.3981|1.19%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|181.4769|182.5028|1.0258|0.57%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|75.5628|73.9583|-1.6045|-2.12%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|48.9473|47.3197|-1.6276|-3.33%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1362.0064|1344.119|-17.8874|-1.31%|
|migraphx_torchvision__inceptioni1|PASS|within tol|209.0909|218.8821|9.7913|4.68%|
|migraphx_torchvision__inceptioni32|PASS|within tol|6134.7584|6161.4929|26.7345|0.44%|
|migraphx_torchvision__resnet50i1|PASS|within tol|85.2605|89.0368|3.7762|4.43%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5212.5126|5145.5514|-66.9612|-1.28%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2626.4118|2657.1492|30.7374|1.17%|
|migx_bench_bert-large-uncased_16_256|PASS|regression|4153.9255|4420.2847|266.3592|6.41%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5982.1335|6122.5721|140.4386|2.35%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|159.658|158.0368|-1.6211|-1.02%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|267.833|263.897|-3.936|-1.47%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|373.119|376.0995|2.9805|0.8%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|431.1777|397.3612|-33.8166|-7.84%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|597.1035|592.6357|-4.4678|-0.75%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|853.4895|828.9566|-24.533|-2.87%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5183.0206|5184.0374|1.0168|0.02%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8091.1391|8443.6431|352.504|4.36%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11337.5176|11646.1385|308.6209|2.72%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|723.5142|737.7744|14.2602|1.97%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|1107.4869|1229.0214|121.5346|10.97%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1585.3593|1613.1708|27.8116|1.75%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|1328.4378|1445.2389|116.8011|8.79%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|2105.9574|2488.9669|383.0095|18.19%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3023.5928|3046.0351|22.4422|0.74%|

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

