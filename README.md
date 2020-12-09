# SVHN-digit-detection
Use Retina Net to do SVHN digit detection
  ## Dataset
    
   SVHN is obtained from house numbers in Google Street View images. It contain 10 classes, 1 for each digit. Digit '1' has label 1, '9' has label 9 and '0' has label 10 instead of 0.
   
  ---

  <p align="center">
  <img src="svhn.png">
  </p>

  ---
  ## Enviornment
  ```
  torch version 1.7.0
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
   Run train.py by following command
      
    python train.py --dataset csv --csv_train <path/to/train_annots.csv>  --csv_classes <path/to/train/class_list.csv>  --csv_val <path/to/val_annots.csv>
 
    
  ## Visulaize
  pre-trained model is available at:
  https://drive.google.com/file/d/1OMCnOHyJt2DW_JStE0WtVpESOiW3-gEu/view?usp=sharing
  
  To visualize image, use:
  ```
  python inference.py --dataset csv --csv_classes <path/to/train/class_list.csv>  --csv_val <path/to/val_annots.csv> --model <path/to/model.pt>
  ```
  ## Credits
   1) -https://github.com/pavitrakumar78/Street-View-House-Numbers-SVHN-Detection-and-Classification-using-CNN/blob/master/train_digit_detection.py
   2) -https://github.com/AlessandroSaviolo/RetinaNET-Object-Detector/tree/master/src
   3) -https://github.com/yhenon/pytorch-retinanet</h3>
  ## Example
