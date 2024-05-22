README_ch.md

cd ./deploy
python python/predict_system_change.py -c configs/inference_custom.yaml -o Global.infer_imgs="./dataset_test/test_images/1.jpg" -o Global.use_gpu=False
