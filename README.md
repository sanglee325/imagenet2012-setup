# ImageNet2012

## Directory Structure Setup

### Train

* Unzip `ILSVRC2012_img_train.tar`.
    ```bash
    mkdir -p train
    tar -xvf ILSVRC2012_img_train.tar -C train
    ```

* Run `train_setup.sh` in `train/` directory.
    ```bash
    train/
    ├── n01440764/
    │   ├── n01440764_10026.JPEG
    │   ├── n01440764_10027.JPEG
    │   ├── ...
    ├── ...
    ```


### Validation

* Unzip `ILSVRC2012_img_val.tar`.
    ```bash
    mkdir -p val
    tar -xvf ILSVRC2012_img_val.tar -C val
    ```

* Run `val_setup.sh` in `val/` directory.
    ```bash
    val/
    ├── n01440764/
    │   ├── ILSVRC2012_val_00000293.JPEG 
    │   ├── ILSVRC2012_val_00002138.JPEG
    │   ├── ...
    ├── ...
    ```