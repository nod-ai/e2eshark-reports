# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|801.5506|51.9513|-749.5993|-93.52%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|1023.3911|50.4501|-972.941|-95.07%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|2744.8385|150.1526|-2594.6859|-94.53%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|2436.3986|66.0111|-2370.3875|-97.29%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|7094.7893|170.8058|-6923.9836|-97.59%|
|migraphx_cadene__dpn92i1|PASS|progression|463.8861|66.6065|-397.2796|-85.64%|
|migraphx_cadene__inceptionv4i16|PASS|progression|28024.6677|4622.2376|-23402.4301|-83.51%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|1009.7442|129.1027|-880.6415|-87.21%|
|migraphx_cadene__resnext101_64x4di16|PASS|progression|6385.4546|2361.5147|-4023.9399|-63.02%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|5784.2009|180.7637|-5603.4372|-96.87%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|8237.9007|292.6401|-7945.2606|-96.45%|
|migraphx_mlperf__resnet50_v1|PASS|progression|163.9665|27.0913|-136.8752|-83.48%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|263.8879|23.5827|-240.3052|-91.06%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|72.414|41.896|-30.518|-42.14%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|26.8739|25.0955|-1.7784|-6.62%|
|migraphx_torchvision__inceptioni1|PASS|progression|614.4001|133.3021|-481.098|-78.3%|
|migraphx_torchvision__inceptioni32|PASS|progression|23101.6265|4578.5795|-18523.047|-80.18%|
|migraphx_torchvision__resnet50i1|PASS|progression|259.6859|26.2456|-233.4404|-89.89%|
|migraphx_torchvision__resnet50i64|PASS|progression|10339.7821|1250.7444|-9089.0377|-87.9%|

## 13 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|DenseNet201_vaiq_int8|PASS|Numerics|
|hrnet_w18_small_v2_vaiq|PASS|compilation|
|hrnet_w18_small_vaiq|PASS|compilation|
|hrnet_w18_vaiq|PASS|compilation|
|hrnet_w30_vaiq|PASS|compilation|
|hrnet_w32_vaiq|PASS|compilation|
|hrnet_w40_vaiq|PASS|compilation|
|hrnet_w44_vaiq|PASS|compilation|
|hrnet_w48_vaiq|PASS|compilation|
|hrnet_w64_vaiq|PASS|compilation|
|migraphx_bert__bertsquad-12|Numerics|compilation|
|migraphx_mlperf__bert_large_mlperf|PASS|Numerics|
|resnet50_gn_vaiq|PASS|Numerics|

## 30 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|migraphx_torchvision__densenet121i32|compilation|PASS|
|model--BART--Shubham09|compilation|compiled_inference|
|model--CodeGen-350M-Multi--xhyi|preprocessing|Numerics|
|model--Microllama_Char_200k_step--Corianas|compiled_inference|PASS|
|model--TinyMistral-248M-v2-cleaner--M4-ai|compiled_inference|PASS|
|model--codegen-350M-mono--Salesforce|preprocessing|Numerics|
|model--codegen-350M-mono-4bit-qlora--iamtarun|preprocessing|Numerics|
|model--deberta-italian-question-answering--osiria|preprocessing|PASS|
|model--deberta-v3-base-qa-en--LLukas22|preprocessing|compiled_inference|
|model--deberta-v3-base-squad2--deepset|preprocessing|compiled_inference|
|model--deberta-v3-base-squad2--navteca|preprocessing|compiled_inference|
|model--deberta-v3-base__sst2__all-train--SetFit|preprocessing|compiled_inference|
|model--deberta-v3-large-squad2--deepset|preprocessing|compiled_inference|
|model--deberta-v3-large-squad2--sjrhuschlee|preprocessing|compiled_inference|
|model--deberta-v3-xsmall-squad2--nlpconnect|preprocessing|compiled_inference|
|model--deberta_squadnewsqa--sophiebottani|preprocessing|compiled_inference|
|model--gemma-tiny-random--yujiepan|compiled_inference|PASS|
|model--llama-160m--JackFram|compiled_inference|PASS|
|model--llama-wikitext--manu|compiled_inference|PASS|
|model--mdeberta-v3-base-squad2--sjrhuschlee|preprocessing|PASS|
|model--microsoft-deberta-v3-large_ner_conll2003--Gladiator|preprocessing|compiled_inference|
|model--microsoft_deberta-base_squad--Palak|preprocessing|PASS|
|model--microsoft_deberta-large_squad--Palak|preprocessing|PASS|
|model--opt-125m-finetuned-squad-assignment--Isente|compilation|compiled_inference|
|model--outputs--ankitkupadhyay|preprocessing|compiled_inference|
|model--reward-model-deberta-v3-large-v2--OpenAssistant|preprocessing|compiled_inference|
|model--smol_llama-220M-GQA--BEE-spoke-data|compiled_inference|PASS|
|model--smol_llama-81M-tied--BEE-spoke-data|compiled_inference|PASS|
|model--tiny-random-llama--IlyasMoutawwakil|compiled_inference|PASS|
|resnetv2_50x1_bit.goog_distilled_in1k_vaiq|Numerics|PASS|

