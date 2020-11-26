# SVHN-digit-detection
Use Retina Net to do SVHN digit detection
  ## Dataset
  ![img]https://github.com/crystal0523/SVHN-digit-detection/svhn.png
  ## Enviornment
  ```
  ```
  ## Installation
   1) Download dataset from official site
    http://ufldl.stanford.edu/housenumbers/
   2) Clone this repo
   3) Install Python packages
   ```
   pip install pandas
   pip install pycocotools
   pip install opencv-python
   pip install requests
   ```
  ## Training
    Run train.py by fololwing command
      
    python train.py --dataset csv --csv_train <path/to/train_annots.csv>  --csv_classes <path/to/train/class_list.csv>  --csv_val <path/to/val_annots.csv>
 
    
  ## Pre-trained model  
  pre-trained model is available at:
  
  The state dict model can be loaded using:
  ```
  retinanet = model.resnet50(num_classes=dataset_train.num_classes(),)
  retinanet.load_state_dict(torch.load(PATH_TO_WEIGHTS))
  ```
  ## Credits
   1) -https://github.com/pavitrakumar78/Street-View-House-Numbers-SVHN-Detection-and-Classification-using-CNN/blob/master/train_digit_detection.py
   2) -https://github.com/AlessandroSaviolo/RetinaNET-Object-Detector/tree/master/src
   3) -https://github.com/yhenon/pytorch-retinanet</h3>
  ## Example
