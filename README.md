# dl_labwork1

Using previous model to train cats & dogs
Picture when serialize have the same properties
Ofc this is a Transformer model not CNN :)))
CNN model is in the ipynb file

The necessary Python packages to run the code is installed by running:
```shell
pip install -r requirements.txt
```

To train
```bash
python3 train.py --conf KWT_configs/kwt1_baseline_mean_config.yaml
```

To run inference make sure to put the dataset (inference_file) into gsc folder with the inference_list in the right path and run it as test files just like in train data

#TODO:
Fix training pipline
