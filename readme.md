https://github.com/Syavaprd/mcl-wic
Go to this link.
Run this line
!python ./run_model.py --do_train --do_validation --data_dir data/ --output_dir ./log_dir 
  --model_name xlm-roberta-base --loss cosine_similarity --num_train_epochs 30 
    --add_fc_layer True --emb_size_for_cosine 1024 --local_config_path ./local_config.json
    --lr_scheduler linear_warmup
