# Test Run Comparison Report

## Performance Comparison

regression tolerance: 10.0%

progression tolerance: 10.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|801.5506|84.3054|-717.2452|-89.48%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|1023.3911|99.6363|-923.7547|-90.26%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|2744.8385|249.8057|-2495.0328|-90.9%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|2436.3986|83.7247|-2352.6739|-96.56%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|7094.7893|271.6002|-6823.1891|-96.17%|
|migraphx_cadene__dpn92i1|PASS|progression|463.8861|204.8633|-259.0228|-55.84%|
|migraphx_cadene__inceptionv4i16|PASS|progression|28024.6677|6482.0748|-21542.5928|-76.87%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|1009.7442|325.6406|-684.1035|-67.75%|
|migraphx_cadene__resnext101_64x4di16|PASS|progression|6385.4546|5091.3026|-1294.152|-20.27%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|5784.2009|410.9806|-5373.2203|-92.89%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|8237.9007|467.01|-7770.8907|-94.33%|
|migraphx_mlperf__resnet50_v1|PASS|progression|163.9665|89.5858|-74.3807|-45.36%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|263.8879|31.4735|-232.4144|-88.07%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|72.414|80.4556|8.0416|11.11%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|26.8739|42.2112|15.3373|57.07%|
|migraphx_torchvision__inceptioni1|PASS|progression|614.4001|204.7779|-409.6222|-66.67%|
|migraphx_torchvision__inceptioni32|PASS|progression|23101.6265|6204.1964|-16897.4301|-73.14%|
|migraphx_torchvision__resnet50i1|PASS|progression|259.6859|85.8356|-173.8503|-66.95%|
|migraphx_torchvision__resnet50i64|PASS|progression|10339.7821|5249.1649|-5090.6172|-49.23%|

## 18 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|hrnet_w18_small_v2_vaiq|PASS|compiled_inference|
|hrnet_w18_small_vaiq|PASS|compiled_inference|
|hrnet_w18_vaiq|PASS|compiled_inference|
|hrnet_w30_vaiq|PASS|compiled_inference|
|hrnet_w32_vaiq|PASS|compiled_inference|
|hrnet_w40_vaiq|PASS|compiled_inference|
|hrnet_w44_vaiq|PASS|compiled_inference|
|hrnet_w48_vaiq|PASS|compiled_inference|
|hrnet_w64_vaiq|PASS|compiled_inference|
|migraphx_bert__bertsquad-12|Numerics|compilation|
|migraphx_mlperf__bert_large_mlperf|PASS|Numerics|
|migraphx_models__whisper-tiny-encoder|compiled_inference|compilation|
|model--ia-detection-tiny-random-gptj--arincon|Numerics|compiled_inference|
|model--my_awesome_gptj_model--anandshende|Numerics|compiled_inference|
|model--s2t-medium-librispeech-asr--facebook|compiled_inference|compilation|
|model--tiny-random-GPTJForQuestionAnswering--hf-tiny-model-private|Numerics|compiled_inference|
|model--tiny-random-gptj-for-sequence-classification--ydshieh|Numerics|compiled_inference|
|resnest50d_1s4x24d_vaiq|PASS|Numerics|

## 274 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|KeypointRCNN_vaiq_int8|preprocessing|compilation|
|bat_resnext26ts.ch_in1k|preprocessing|compilation|
|botnet26t_256|preprocessing|compiled_inference|
|coat_lite_mini|compilation|Numerics|
|coat_lite_small|compilation|Numerics|
|coat_lite_tiny|compilation|Numerics|
|coat_mini|preprocessing|compilation|
|coat_tiny|preprocessing|compilation|
|coatnet_2_rw_224.sw_in12k|compilation|Numerics|
|coatnet_2_rw_224.sw_in12k_ft_in1k|compilation|Numerics|
|coatnet_3_rw_224.sw_in12k|compilation|Numerics|
|coatnet_nano_rw_224.sw_in1k|compilation|Numerics|
|coatnet_rmlp_2_rw_224.sw_in12k|compilation|Numerics|
|coatnet_rmlp_2_rw_224.sw_in12k_ft_in1k|compilation|Numerics|
|coatnet_rmlp_2_rw_224.sw_in1k|compilation|Numerics|
|coatnet_rmlp_2_rw_384.sw_in12k_ft_in1k|compilation|Numerics|
|coatnet_rmlp_nano_rw_224.sw_in1k|compilation|Numerics|
|crossvit_15_240|preprocessing|compilation|
|crossvit_15_dagger_240|preprocessing|compilation|
|crossvit_15_dagger_408|preprocessing|compilation|
|crossvit_18_240|preprocessing|compilation|
|crossvit_18_dagger_240|preprocessing|compilation|
|crossvit_18_dagger_408|preprocessing|compilation|
|crossvit_9_240|preprocessing|compilation|
|crossvit_9_dagger_240|preprocessing|compilation|
|crossvit_base_240|preprocessing|compilation|
|crossvit_small_240|preprocessing|compilation|
|crossvit_tiny_240|preprocessing|compilation|
|eca_botnext26ts_256|preprocessing|compiled_inference|
|edgenext_base|preprocessing|Numerics|
|edgenext_small|preprocessing|Numerics|
|edgenext_small_rw|preprocessing|PASS|
|edgenext_x_small|preprocessing|Numerics|
|edgenext_xx_small|preprocessing|Numerics|
|efficientformerv2_l.snap_dist_in1k|compilation|Numerics|
|efficientformerv2_s0.snap_dist_in1k|compilation|Numerics|
|efficientformerv2_s1.snap_dist_in1k|compilation|Numerics|
|efficientformerv2_s2.snap_dist_in1k|compilation|Numerics|
|efficientnet_b1_pruned.in1k|compilation|Numerics|
|efficientnet_b2_pruned.in1k|compilation|Numerics|
|efficientnet_b3_pruned.in1k|compilation|Numerics|
|gluon_xception65|compilation|Numerics|
|jx_nest_base|compilation|PASS|
|jx_nest_small|compilation|PASS|
|jx_nest_tiny|compilation|PASS|
|maxvit_base_tf_224.in1k|compilation|compiled_inference|
|maxvit_base_tf_384.in1k|compilation|compiled_inference|
|maxvit_base_tf_384.in21k_ft_in1k|compilation|compiled_inference|
|maxvit_base_tf_512.in1k|compilation|compiled_inference|
|maxvit_base_tf_512.in21k_ft_in1k|compilation|compiled_inference|
|maxvit_large_tf_224.in1k|compilation|compiled_inference|
|maxvit_large_tf_384.in1k|compilation|compiled_inference|
|maxvit_large_tf_384.in21k_ft_in1k|compilation|compiled_inference|
|maxvit_large_tf_512.in1k|compilation|compiled_inference|
|maxvit_large_tf_512.in21k_ft_in1k|compilation|compiled_inference|
|maxvit_small_tf_224.in1k|compilation|compiled_inference|
|maxvit_small_tf_384.in1k|compilation|compiled_inference|
|maxvit_small_tf_512.in1k|compilation|compiled_inference|
|maxvit_tiny_tf_224.in1k|compilation|compiled_inference|
|maxvit_tiny_tf_384.in1k|compilation|compiled_inference|
|maxvit_tiny_tf_512.in1k|compilation|compiled_inference|
|maxvit_xlarge_tf_384.in21k_ft_in1k|compilation|compiled_inference|
|maxvit_xlarge_tf_512.in21k_ft_in1k|compilation|compiled_inference|
|migraphx_bert__bert-large-uncased|preprocessing|PASS|
|migraphx_onnx-model-zoo__gpt2-10|preprocessing|compilation|
|migraphx_torchvision__densenet121i32|compilation|PASS|
|model--BART--Shubham09|compilation|Numerics|
|model--BERT_summary--Shobhank-iiitdwd|compiled_inference|PASS|
|model--Bartlarge--Shubham09|compiled_inference|Numerics|
|model--CodeGen-350M-Multi--xhyi|preprocessing|compiled_inference|
|model--Microllama_Char_200k_step--Corianas|compiled_inference|PASS|
|model--TinyMistral-248M-v2-cleaner--M4-ai|compiled_inference|PASS|
|model--Translation--shed-e|compiled_inference|PASS|
|model--bart-CaPE-xsum--praf-choub|compiled_inference|Numerics|
|model--bart-base-booksum--KamilAin|compiled_inference|PASS|
|model--bart-base-cnn--ainize|compiled_inference|PASS|
|model--bart-base-few-shot-k-1024-finetuned-squad-seed-2--anas-awadalla|compiled_inference|PASS|
|model--bart-base-few-shot-k-1024-finetuned-squad-seed-4--anas-awadalla|compiled_inference|PASS|
|model--bart-base-few-shot-k-128-finetuned-squad-seed-2--anas-awadalla|compiled_inference|PASS|
|model--bart-base-few-shot-k-128-finetuned-squad-seed-4--anas-awadalla|compiled_inference|PASS|
|model--bart-base-few-shot-k-16-finetuned-squad-seed-0--anas-awadalla|compiled_inference|PASS|
|model--bart-base-few-shot-k-16-finetuned-squad-seed-2--anas-awadalla|compiled_inference|PASS|
|model--bart-base-few-shot-k-16-finetuned-squad-seed-4--anas-awadalla|compiled_inference|PASS|
|model--bart-base-few-shot-k-256-finetuned-squad-seed-0--anas-awadalla|compiled_inference|PASS|
|model--bart-base-few-shot-k-256-finetuned-squad-seed-4--anas-awadalla|compiled_inference|PASS|
|model--bart-base-few-shot-k-32-finetuned-squad-seed-4--anas-awadalla|compiled_inference|PASS|
|model--bart-base-few-shot-k-512-finetuned-squad-seed-0--anas-awadalla|compiled_inference|PASS|
|model--bart-base-few-shot-k-512-finetuned-squad-seed-4--anas-awadalla|compiled_inference|PASS|
|model--bart-base-few-shot-k-64-finetuned-squad-seed-0--anas-awadalla|compiled_inference|PASS|
|model--bart-base-few-shot-k-64-finetuned-squad-seed-2--anas-awadalla|compiled_inference|PASS|
|model--bart-base-finetuned-squad--huxxx657|compiled_inference|PASS|
|model--bart-base-samsum--philschmid|compiled_inference|PASS|
|model--bart-base-squad2--sjrhuschlee|compiled_inference|PASS|
|model--bart-base-xsum--harouzie|compiled_inference|PASS|
|model--bart-base-xsum--morenolq|compiled_inference|PASS|
|model--bart-german--Shahm|compiled_inference|PASS|
|model--bart-large-cnn--facebook|compiled_inference|PASS|
|model--bart-large-cnn-samsum--philschmid|compiled_inference|Numerics|
|model--bart-large-finetuned-squadv1--valhalla|compiled_inference|PASS|
|model--bart-large-xsum--facebook|compiled_inference|PASS|
|model--bart-mofe-rl-xsum--praf-choub|compiled_inference|PASS|
|model--bart_lfqa_sqaud--Shubham09|compiled_inference|PASS|
|model--codegen-350M-mono--Salesforce|preprocessing|compiled_inference|
|model--codegen-350M-mono-4bit-qlora--iamtarun|preprocessing|compiled_inference|
|model--deberta-italian-question-answering--osiria|preprocessing|PASS|
|model--deberta-v3-base-qa-en--LLukas22|preprocessing|PASS|
|model--deberta-v3-base-squad2--deepset|preprocessing|PASS|
|model--deberta-v3-base-squad2--navteca|preprocessing|PASS|
|model--deberta-v3-base__sst2__all-train--SetFit|preprocessing|PASS|
|model--deberta-v3-large-squad2--deepset|preprocessing|PASS|
|model--deberta-v3-large-squad2--sjrhuschlee|preprocessing|PASS|
|model--deberta-v3-xsmall-squad2--nlpconnect|preprocessing|PASS|
|model--deberta_squadnewsqa--sophiebottani|preprocessing|PASS|
|model--distilbart-cnn-12-3--sshleifer|compiled_inference|PASS|
|model--distilbart-cnn-12-6-samsum--philschmid|compiled_inference|PASS|
|model--distilbart-cnn-6-6--sshleifer|compiled_inference|PASS|
|model--distilbart-xsum-1-1--sshleifer|compiled_inference|PASS|
|model--distilbart-xsum-12-1--sshleifer|compiled_inference|PASS|
|model--distilbart-xsum-12-3--sshleifer|compiled_inference|PASS|
|model--distilbart-xsum-12-6--sshleifer|compiled_inference|PASS|
|model--distilbart-xsum-6-6--sshleifer|compiled_inference|PASS|
|model--distilbart-xsum-9-6--sshleifer|compiled_inference|PASS|
|model--gemma-tiny-random--yujiepan|compiled_inference|PASS|
|model--llama-160m--JackFram|compiled_inference|PASS|
|model--llama-wikitext--manu|compiled_inference|PASS|
|model--lsg-bart-base-4096-booksum--ccdv|compiled_inference|PASS|
|model--marian-finetuned-kde4-cs2sv--ksaml|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-fr--RajkNakka|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-ar--anibahug|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-es--tmobaggins|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-es--zainnaved|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--Abelll|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--Alesteba|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--DarioLopes|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--Dewa|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--Eitanli|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--Fredvv|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--Leisa|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--Mikey8943|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--Molka11|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--Najeen|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--Neulvo|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--Student3342|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--Thinkcru|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--Yuch|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--aaraki|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--amartyobanerjee|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--aneeshmb02|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--anjankumar|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--apatidar0|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--bishalbaaniya|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--chandrasutrisnotjhong|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--clboetticher|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--coreyabs-db|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--evincent18|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--feeeper|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--jatinshah|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--jfarmerphd|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--kbalde|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--kosec39|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--lewtun|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--libalabala|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--lsimon|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--luhui|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--mbateman|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--miesnerjacob|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--mrp|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--mxalmeida|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--ncduy|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--ornil1|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--raisin2402|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--rootacess|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--sgugger|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--sofa566|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--sungchun71|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--thucdangvan020999|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--tmatup|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--ttri-pruiu|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr--vsrinivas|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr-2--Siqi|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-fr3--Ghost1|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-hi--vsrinivas|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-ja--Hoax0930|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-vi--VanHoan|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-vi--huanvo88|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-vi--huynguyen208|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-zh--DrY|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-zh--chenyanjin|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-zh--luoyixin|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-zh_TW--peterhsu|compiled_inference|PASS|
|model--marian-finetuned-kde4-en-to-zh_TW-accelerate--peterhsu|compiled_inference|PASS|
|model--mdeberta-v3-base-squad2--sjrhuschlee|preprocessing|PASS|
|model--microsoft-deberta-v3-large_ner_conll2003--Gladiator|preprocessing|PASS|
|model--microsoft_deberta-base_squad--Palak|preprocessing|PASS|
|model--microsoft_deberta-large_squad--Palak|preprocessing|PASS|
|model--opt-125m-finetuned-squad-assignment--Isente|compilation|compiled_inference|
|model--outputs--ankitkupadhyay|preprocessing|PASS|
|model--pythia-410mn-ntoxic--skrishna|compiled_inference|PASS|
|model--pythia-70-m-finetuned--selinerdem|compiled_inference|PASS|
|model--pythia-70m-toxicity-model--skrishna|compiled_inference|PASS|
|model--really-tiny-falcon-testing--fxmarty|compiled_inference|PASS|
|model--reward-model-deberta-v3-large-v2--OpenAssistant|preprocessing|PASS|
|model--roberta_shared_bbc_xsum--patrickvonplaten|compiled_inference|PASS|
|model--smol_llama-220M-GQA--BEE-spoke-data|compiled_inference|PASS|
|model--smol_llama-81M-tied--BEE-spoke-data|compiled_inference|PASS|
|model--splinter-large-few-shot-k-16-finetuned-squad-seed-0--anas-awadalla|preprocessing|Numerics|
|model--splinter-large-few-shot-k-16-finetuned-squad-seed-2--anas-awadalla|preprocessing|Numerics|
|model--splinter-large-few-shot-k-16-finetuned-squad-seed-4--anas-awadalla|preprocessing|Numerics|
|model--splinter-large-few-shot-k-32-finetuned-squad-seed-2--anas-awadalla|preprocessing|Numerics|
|model--squeezebert-uncased-finetuned-squad--SupriyaArun|preprocessing|compilation|
|model--tiny-gpt2--taufeeque|compiled_inference|Numerics|
|model--tiny-gpt2-magicprompt--pszemraj|compiled_inference|Numerics|
|model--tiny-random-FalconForCausalLM--illuin|compiled_inference|PASS|
|model--tiny-random-llama--IlyasMoutawwakil|compiled_inference|PASS|
|model--tiny-testing-falcon-alibi--fxmarty|compiled_inference|PASS|
|model--unisumm_3--vishw2703|compiled_inference|PASS|
|nasnetalarge|compilation|Numerics|
|pnasnet5large|compilation|Numerics|
|pytorch-3dunet_vaiq_int8|Numerics|PASS|
|resnetv2_50d_gn.ah_in1k_vaiq|Numerics|PASS|
|resnetv2_50x1_bit.goog_distilled_in1k_vaiq|Numerics|PASS|
|retinanet_resnet50_fpn_vaiq_int8|preprocessing|compilation|
|sebotnet33ts_256|preprocessing|compiled_inference|
|sequencer2d_l|preprocessing|compilation|
|swinv2_cr_small_224.sw_in1k|compilation|PASS|
|swinv2_cr_small_ns_224.sw_in1k|compilation|PASS|
|swinv2_cr_tiny_ns_224.sw_in1k|compilation|PASS|
|tf_efficientnet_b0.aa_in1k|compilation|Numerics|
|tf_efficientnet_b0.ap_in1k|compilation|Numerics|
|tf_efficientnet_b0.ns_jft_in1k|compilation|Numerics|
|tf_efficientnet_b1.aa_in1k|compilation|Numerics|
|tf_efficientnet_b1.ap_in1k|compilation|Numerics|
|tf_efficientnet_b1.ns_jft_in1k|compilation|Numerics|
|tf_efficientnet_b2.aa_in1k|compilation|Numerics|
|tf_efficientnet_b2.ap_in1k|compilation|Numerics|
|tf_efficientnet_b2.ns_jft_in1k|compilation|Numerics|
|tf_efficientnet_b3.aa_in1k|compilation|Numerics|
|tf_efficientnet_b3.ap_in1k|compilation|Numerics|
|tf_efficientnet_b3.ns_jft_in1k|compilation|Numerics|
|tf_efficientnet_b4.aa_in1k|compilation|Numerics|
|tf_efficientnet_b4.ap_in1k|compilation|Numerics|
|tf_efficientnet_b4.ns_jft_in1k|compilation|Numerics|
|tf_efficientnet_b5.ap_in1k|compilation|Numerics|
|tf_efficientnet_b5.ns_jft_in1k|compilation|Numerics|
|tf_efficientnet_b5.ra_in1k|compilation|Numerics|
|tf_efficientnet_b6.aa_in1k|compilation|Numerics|
|tf_efficientnet_b6.ap_in1k|compilation|Numerics|
|tf_efficientnet_b6.ns_jft_in1k|compilation|Numerics|
|tf_efficientnet_b7.ap_in1k|compilation|Numerics|
|tf_efficientnet_b7.ns_jft_in1k|compilation|Numerics|
|tf_efficientnet_b7.ra_in1k|compilation|Numerics|
|tf_efficientnet_b8.ap_in1k|compilation|Numerics|
|tf_efficientnet_b8.ra_in1k|compilation|Numerics|
|tf_efficientnet_l2.ns_jft_in1k|compilation|Numerics|
|tf_efficientnet_l2.ns_jft_in1k_475|compilation|Numerics|
|tf_efficientnetv2_l.in1k|compilation|Numerics|
|tf_efficientnetv2_l.in21k_ft_in1k|compilation|Numerics|
|tf_efficientnetv2_m.in1k|compilation|Numerics|
|tf_efficientnetv2_m.in21k_ft_in1k|compilation|Numerics|
|tf_efficientnetv2_s.in1k|compilation|Numerics|
|tf_efficientnetv2_s.in21k_ft_in1k|compilation|Numerics|
|tf_efficientnetv2_xl.in21k_ft_in1k|compilation|Numerics|
|tf_mixnet_l.in1k|compilation|Numerics|
|tf_mixnet_m.in1k|compilation|Numerics|
|tf_mixnet_s.in1k|compilation|Numerics|
|tf_mobilenetv3_large_075.in1k|compilation|Numerics|
|tf_mobilenetv3_large_100.in1k|compilation|Numerics|
|tnt_s_patch16_224|preprocessing|PASS|
|twins_svt_base|compilation|Numerics|
|twins_svt_large|compilation|Numerics|
|twins_svt_small|compilation|Numerics|
|visformer_small|compilation|PASS|
|vit_relpos_base_patch16_clsgap_224.sw_in1k|compilation|PASS|
|vit_relpos_medium_patch16_cls_224.sw_in1k|compilation|PASS|
