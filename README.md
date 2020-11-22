# SVHN-digit-detection
Use Retina Net to do SVHN digit detection
  <h2>Dataset
  
  <h2>Installation</h2>
    Download dataset from official site
    <p>http://ufldl.stanford.edu/housenumbers/</p>
  <h2>Training</h2>
    Run train.py by fololwing command
      
    python train.py --dataset csv --csv_train <path/to/train_annots.csv>  --csv_classes <path/to/train/class_list.csv>  --csv_val <path/to/val_annots.csv>
 
    
  <h2>Pre-trained model  
  <h2>References</h2>
    1. https://github.com/pavitrakumar78/Street-View-House-Numbers-SVHN-Detection-and-Classification-using-CNN/blob/master/train_digit_detection.py
    2. https://github.com/AlessandroSaviolo/RetinaNET-Object-Detector/tree/master/src
    3. https://github.com/yhenon/pytorch-retinanet
