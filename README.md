# Wavelet-Integrated U-Net for Large-Scale Underwater Image Enhancement

This project implements a Wavelet-based U-Net architecture (EWU-Net) for enhancing degraded underwater images. The model integrates wavelet decomposition into a deep learning framework, allowing it to extract multiscale spatial information and preserve both structural and textural image details.

## Datasets

- **LSUI** (Large-Scale Underwater Image dataset)
- **EUVP** (Enhancing Underwater Visual Perception dataset)

Both datasets offer diverse underwater scenes under various lighting and water conditions.

## Results

| Dataset | PSNR   | SSIM   |
|---------|--------|--------|
| LSUI    | 23.47  | 0.9127 |
| EUVP    | 23.59  | 0.8572 |  <!-- You can update this after checking EUVP notebook -->

### Sample Outputs

#### LSUI
![image](https://github.com/user-attachments/assets/620d3541-4044-45e0-81c9-48c9c9084442)



#### EUVP
![image](https://github.com/user-attachments/assets/b558b935-ee78-442f-ad16-b83f806e5ece)



## How to Run

1. Clone this repo:
    ```bash
    git clone https://github.com/yourusername/Underwater-Image-Enhancement-EWU-Net.git
    cd Underwater-Image-Enhancement-EWU-Net
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Download datasets and place them accordingly.

4. Run the notebooks.

## Acknowledgements

- [LSUI Dataset](https://www.kaggle.com/datasets/cbhavik/lsui-dataset)
- [EUVP Dataset](https://www.kaggle.com/datasets/pamuduranasinghe/euvp-dataset)
- Gonzalez, R. C., & Woods, R. E. (2008). Digital Image Processing.

#
