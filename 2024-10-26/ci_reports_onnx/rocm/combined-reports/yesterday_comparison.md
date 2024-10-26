# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|124.6908|111.859|-12.8318|-10.29%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|84.0062|71.8539|-12.1522|-14.47%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|304.9534|277.0779|-27.8756|-9.14%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|157.2636|154.2233|-3.0403|-1.93%|
|migraphx_cadene__resnext101_64x4di16|PASS|progression|278.6266|216.4475|-62.1791|-22.32%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.0801|7.0431|-0.0371|-0.52%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|63.9077|41.4604|-22.4473|-35.12%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|5.2599|5.269|0.0091|0.17%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|32.0079|28.2833|-3.7246|-11.64%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|63.5509|63.0772|-0.4737|-0.75%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|8.0345|8.0325|-0.002|-0.02%|
|migraphx_torchvision__densenet121i32|PASS|progression|60.0486|49.3517|-10.6969|-17.81%|
|migraphx_torchvision__inceptioni1|PASS|progression|28.2531|18.0108|-10.2423|-36.25%|
|migraphx_torchvision__inceptioni32|PASS|within tol|125.908|129.7607|3.8526|3.06%|
|migraphx_torchvision__resnet50i64|PASS|progression|234.8899|202.184|-32.7059|-13.92%|

## 11 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|MobileNetV3_large_vaiq|PASS|Numerics|
|efficientnet_el.ra_in1k_vaiq|Numerics|compiled_inference|
|efficientnet_el_pruned.in1k_vaiq|Numerics|compiled_inference|
|migraphx_bert__bertsquad-12|Numerics|compiled_inference|
|migraphx_cadene__dpn92i1|Numerics|compilation|
|migraphx_cadene__resnext101_64x4di1|PASS|compilation|
|migraphx_torchvision__resnet50i1|PASS|compilation|
|regnetz_040.ra3_in1k_train_vaiq|PASS|Numerics|
|regnetz_040_h.ra3_in1k_train_vaiq|PASS|Numerics|
|tf_efficientnet_el.in1k_vaiq|Numerics|compiled_inference|
|tf_mobilenetv3_large_minimal_100.in1k_vaiq|PASS|Numerics|

## 188 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|EfficientNet_b1_vaiq|Numerics|PASS|
|EfficientNet_b6_vaiq|Numerics|PASS|
|FCN_vaiq_int8|compilation|PASS|
|KeypointRCNN_vaiq_int8|preprocessing|compilation|
|ResNet101_vaiq|compilation|PASS|
|ResNet152_vaiq|compilation|PASS|
|ResNet152_vaiq_int8|compilation|PASS|
|ResNet50_vaiq|compilation|PASS|
|WideResNet_101_2_vaiq|compilation|PASS|
|WideResNet_50_2_vaiq|compilation|PASS|
|WideResNet_50_2_vaiq_int8|compilation|PASS|
|dla102_vaiq|compilation|Numerics|
|dla102x2_vaiq|compilation|Numerics|
|dla102x_vaiq|compilation|Numerics|
|dla169_vaiq|compilation|Numerics|
|dla46_c_vaiq|compilation|Numerics|
|dla46x_c_vaiq|compilation|Numerics|
|dla60_res2net_vaiq|compilation|Numerics|
|dla60_res2next_vaiq|compilation|Numerics|
|dla60_vaiq|compilation|Numerics|
|dla60x_c_vaiq|compilation|Numerics|
|dla60x_vaiq|compilation|Numerics|
|dm_nfnet_f0.dm_in1k_vaiq|compilation|PASS|
|dpn68_vaiq|compilation|Numerics|
|dpn68b_test_vaiq|compilation|Numerics|
|dpn68b_vaiq|compilation|Numerics|
|eca_nfnet_l1.ra2_in1k_train_vaiq|compilation|PASS|
|eca_resnet33ts.ra2_in1k_train_vaiq|compilation|PASS|
|eca_resnext26ts.ch_in1k_train_vaiq|compilation|PASS|
|ecaresnet26t_train_vaiq|compilation|PASS|
|ecaresnet50t_train_vaiq|compilation|PASS|
|efficientnet_b1.ft_in1k_vaiq|Numerics|PASS|
|gcresnet33ts.ra2_in1k_train_vaiq|compilation|PASS|
|gcresnet33ts.ra2_in1k_vaiq|compilation|Numerics|
|gcresnet50t.ra2_in1k_train_vaiq|compilation|Numerics|
|gcresnet50t.ra2_in1k_vaiq|compilation|Numerics|
|gcresnext26ts.ch_in1k_train_vaiq|compilation|Numerics|
|gcresnext26ts.ch_in1k_vaiq|compilation|Numerics|
|gcresnext50ts.ch_in1k_train_vaiq|compilation|Numerics|
|gcresnext50ts.ch_in1k_vaiq|compilation|Numerics|
|gluon_resnet101_v1b_vaiq|compilation|PASS|
|gluon_resnet101_v1c_vaiq|compilation|PASS|
|gluon_resnet101_v1d_vaiq|compilation|PASS|
|gluon_resnet101_v1s_vaiq|compilation|PASS|
|gluon_resnet152_v1b_vaiq|compilation|PASS|
|gluon_resnet152_v1c_vaiq|compilation|PASS|
|gluon_resnet152_v1d_vaiq|compilation|PASS|
|gluon_resnet152_v1s_vaiq|compilation|PASS|
|gluon_resnet50_v1b_vaiq|compilation|PASS|
|gluon_resnet50_v1c_vaiq|compilation|PASS|
|gluon_resnet50_v1d_vaiq|compilation|PASS|
|gluon_resnet50_v1s_vaiq|compilation|PASS|
|gluon_resnext101_32x4d_vaiq|compilation|PASS|
|gluon_resnext101_64x4d_vaiq|compilation|PASS|
|gluon_resnext50_32x4d_vaiq|compilation|PASS|
|ig_resnext101_32x16d_vaiq|compilation|PASS|
|ig_resnext101_32x32d_vaiq|compilation|PASS|
|ig_resnext101_32x8d_vaiq|compilation|PASS|
|migraphx_ORT__bert_base_uncased_1|compiled_inference|PASS|
|migraphx_ORT__bert_large_uncased_1|compiled_inference|PASS|
|migraphx_bert__bert-large-uncased|preprocessing|compilation|
|migraphx_models__whisper-tiny-encoder|compiled_inference|Numerics|
|migraphx_onnx-model-zoo__gpt2-10|preprocessing|compilation|
|model--BERT_summary--Shobhank-iiitdwd|compiled_inference|PASS|
|model--Electra-Large-SQUADV2--titanbot|compiled_inference|Numerics|
|model--electra-large-synqa--mbartolo|compiled_inference|Numerics|
|model--mobilebert-squadv2--aware-ai|compiled_inference|Numerics|
|model--mobilebert-uncased-finetuned-squadv2--mrm8488|compiled_inference|Numerics|
|model--mobilebert_cola--Alireza1044|compiled_inference|Numerics|
|model--mobilebert_mnli--Alireza1044|compiled_inference|Numerics|
|model--mobilebert_mrpc--Alireza1044|compiled_inference|Numerics|
|model--mobilebert_rte--Alireza1044|compiled_inference|Numerics|
|model--mobilebert_sst2--Alireza1044|compiled_inference|Numerics|
|model--roberta-l-squadv1.1--vuiseng9|compiled_inference|Numerics|
|model--roberta-large-bne-sqac--PlanTL-GOB-ES|compiled_inference|Numerics|
|model--roberta-large-few-shot-k-1024-finetuned-squad-seed-2--anas-awadalla|compiled_inference|Numerics|
|model--roberta-large-few-shot-k-1024-finetuned-squad-seed-4--anas-awadalla|compiled_inference|Numerics|
|model--roberta-large-few-shot-k-128-finetuned-squad-seed-4--anas-awadalla|compiled_inference|Numerics|
|model--roberta-large-few-shot-k-16-finetuned-squad-seed-0--anas-awadalla|compiled_inference|Numerics|
|model--roberta-large-few-shot-k-16-finetuned-squad-seed-2--anas-awadalla|compiled_inference|Numerics|
|model--roberta-large-few-shot-k-64-finetuned-squad-seed-4--anas-awadalla|compiled_inference|Numerics|
|model--roberta-large-finetuned-ner--romainlhardy|compiled_inference|Numerics|
|model--roberta-large-ner-english--Jean-Baptiste|compiled_inference|Numerics|
|model--roberta-large-synqa--mbartolo|compiled_inference|Numerics|
|model--roberta-large-synqa-ext--mbartolo|compiled_inference|Numerics|
|model--roberta-large-tweetner7-all--tner|compiled_inference|Numerics|
|model--roberta-large_ner_conll2003--Gladiator|compiled_inference|Numerics|
|model--roberta-med-small_shared-finetuned-bbc_xsum-summarization--mrm8488|compiled_inference|PASS|
|model--roberta_large-filtered_simple-chunk-conll2003_0907_v1--mariolinml|compiled_inference|Numerics|
|model--roberta_large-ner-conll2003_0818_v0--mariolinml|compiled_inference|Numerics|
|model--roberta_large-unbalanced_simple-ner-conll2003_0908_v0--mariolinml|compiled_inference|Numerics|
|model--roberta_shared_bbc_xsum--patrickvonplaten|compiled_inference|PASS|
|model--splinter-large-few-shot-k-16-finetuned-squad-seed-0--anas-awadalla|preprocessing|compilation|
|model--splinter-large-few-shot-k-16-finetuned-squad-seed-2--anas-awadalla|preprocessing|compilation|
|model--splinter-large-few-shot-k-16-finetuned-squad-seed-4--anas-awadalla|preprocessing|compilation|
|model--splinter-large-few-shot-k-32-finetuned-squad-seed-2--anas-awadalla|preprocessing|compilation|
|model--squeezebert-uncased-finetuned-squad--SupriyaArun|preprocessing|compilation|
|nf_regnet_b1.ra2_in1k_train_vaiq|compilation|Numerics|
|nf_resnet50.ra2_in1k_train_vaiq|compilation|Numerics|
|nf_resnet50.ra2_in1k_vaiq|compilation|Numerics|
|res2net101_26w_4s_vaiq|compilation|Numerics|
|res2net50_14w_8s_vaiq|compilation|Numerics|
|res2net50_26w_4s_vaiq|compilation|Numerics|
|res2net50_26w_6s_vaiq|compilation|Numerics|
|res2net50_26w_8s_vaiq|compilation|Numerics|
|res2net50_48w_2s_vaiq|compilation|PASS|
|res2next50_vaiq|compilation|PASS|
|resnest101e_vaiq|compilation|PASS|
|resnest14d_vaiq|compilation|PASS|
|resnest26d_vaiq|compilation|PASS|
|resnest50d_4s2x40d_vaiq|compilation|Numerics|
|resnest50d_vaiq|compilation|PASS|
|resnet101_test_vaiq|compilation|PASS|
|resnet101_vaiq|compilation|PASS|
|resnet101d_train_vaiq|compilation|PASS|
|resnet101d_vaiq|compilation|PASS|
|resnet14t_train_vaiq|compilation|PASS|
|resnet14t_vaiq|compilation|PASS|
|resnet152_test_vaiq|compilation|PASS|
|resnet152_vaiq|compilation|PASS|
|resnet152d_train_vaiq|compilation|PASS|
|resnet152d_vaiq|compilation|PASS|
|resnet200d_train_vaiq|compilation|PASS|
|resnet200d_vaiq|compilation|PASS|
|resnet26_test_vaiq|compilation|PASS|
|resnet26_vaiq|compilation|PASS|
|resnet26d_test_vaiq|compilation|PASS|
|resnet26d_vaiq|compilation|PASS|
|resnet26t_test_vaiq|compilation|PASS|
|resnet26t_vaiq|compilation|PASS|
|resnet32ts.ra2_in1k_train_vaiq|compilation|PASS|
|resnet32ts.ra2_in1k_vaiq|compilation|PASS|
|resnet33ts.ra2_in1k_train_vaiq|compilation|PASS|
|resnet33ts.ra2_in1k_vaiq|compilation|PASS|
|resnet50.a1_in1k_vaiq|compilation|PASS|
|resnet50_test_vaiq|compilation|PASS|
|resnet50_vaiq|compilation|PASS|
|resnet50_vaiq_int8|compilation|PASS|
|resnet50d_test_vaiq|compilation|PASS|
|resnet50d_vaiq|compilation|PASS|
|resnet51q.ra2_in1k_train_vaiq|compilation|PASS|
|resnet51q.ra2_in1k_vaiq|compilation|PASS|
|resnet61q.ra2_in1k_train_vaiq|compilation|PASS|
|resnet61q.ra2_in1k_vaiq|compilation|PASS|
|resnetaa50_train_vaiq|compilation|PASS|
|resnetaa50_vaiq|compilation|PASS|
|resnetblur50_test_vaiq|compilation|PASS|
|resnetblur50_vaiq|compilation|PASS|
|resnetrs152_train_vaiq|compilation|PASS|
|resnetrs200_train_vaiq|compilation|PASS|
|resnetv2_101.a1h_in1k_train_vaiq|compilation|PASS|
|resnetv2_101.a1h_in1k_vaiq|compilation|PASS|
|resnetv2_50.a1h_in1k_train_vaiq|compilation|PASS|
|resnetv2_50.a1h_in1k_vaiq|compilation|PASS|
|resnetv2_50x3_bit.goog_in21k_ft_in1k_vaiq|compilation|Numerics|
|resnext101_32x8d_vaiq|compilation|PASS|
|resnext101_64x4d_train_vaiq|compilation|PASS|
|resnext101_64x4d_vaiq|compilation|PASS|
|resnext26ts.ra2_in1k_train_vaiq|compilation|PASS|
|resnext26ts.ra2_in1k_vaiq|compilation|PASS|
|resnext50_32x4d_test_vaiq|compilation|PASS|
|resnext50_32x4d_vaiq|compilation|PASS|
|resnext50d_32x4d_test_vaiq|compilation|PASS|
|resnext50d_32x4d_vaiq|compilation|PASS|
|retinanet_resnet50_fpn_vaiq_int8|preprocessing|compilation|
|sequencer2d_m_vaiq|compilation|Numerics|
|sequencer2d_s_vaiq|compilation|Numerics|
|seresnet152d_train_vaiq|compilation|PASS|
|seresnet33ts.ra2_in1k_train_vaiq|compilation|PASS|
|seresnext26ts.ch_in1k_train_vaiq|compilation|PASS|
|skresnext50_32x4d_vaiq|compilation|PASS|
|ssl_resnet50_vaiq|compilation|PASS|
|ssl_resnext101_32x16d_vaiq|compilation|PASS|
|ssl_resnext101_32x4d_vaiq|compilation|PASS|
|ssl_resnext101_32x8d_vaiq|compilation|PASS|
|ssl_resnext50_32x4d_vaiq|compilation|PASS|
|swsl_resnet50_vaiq|compilation|PASS|
|swsl_resnext101_32x16d_vaiq|compilation|PASS|
|swsl_resnext101_32x4d_vaiq|compilation|PASS|
|swsl_resnext101_32x8d_vaiq|compilation|PASS|
|swsl_resnext50_32x4d_vaiq|compilation|PASS|
|tv_resnet101_vaiq|compilation|PASS|
|tv_resnet152_vaiq|compilation|PASS|
|tv_resnet50_vaiq|compilation|PASS|
|tv_resnext50_32x4d_vaiq|compilation|PASS|
|wide_resnet101_2_vaiq|compilation|PASS|
|wide_resnet50_2_test_vaiq|compilation|PASS|
|wide_resnet50_2_vaiq|compilation|PASS|

