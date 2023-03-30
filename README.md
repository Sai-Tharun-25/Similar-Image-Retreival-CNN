# Similar-Image-Retreival-CNN

Training an auto-encoder model to reconstruct the input images fed to the algorithm to produce an output. The input is put under dimensionality reduction, to a very small vector (Latent Space) and Euclidean distance is calculated between the model's latent space and the query image's latent space to find similar images from the trained dataset. ​

## Requirements
* Pandas
* Numpy
* tqdm
* requests
* Tensorflow
* pillow
* Matplotlib

## Test Results
### QUERY:
![image](https://user-images.githubusercontent.com/92200301/228864571-2723d8e8-ecc8-479e-adfc-c2281076a0f5.png)

### RESULTS:
![image](https://user-images.githubusercontent.com/92200301/228864735-d2e97c98-9169-4211-84d0-2236362ae964.png)
![image](https://user-images.githubusercontent.com/92200301/228864852-ef6dde19-35da-49ce-a2cb-82b43084df44.png)
![image](https://user-images.githubusercontent.com/92200301/228864961-fa6f13f4-f2bc-46e8-b6aa-74cfd5764378.png)

## Training Conditions
* **TRAINING DATASET SIZE:** 10% OF ORIGINAL PRODUCTS-10K DATA (15,000 IMAGES)​
* **VALIDATION DATASET SIZE:** 9,000 IMAGES​
* **NUMBER OF EPOCHS:** 1
**Reduced size of data and training epochs due to hardware constraints.**
