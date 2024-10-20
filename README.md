
# GAN based on MNIST
* This model is trained on the MNIST Dataset.
* The model tries to create images similar to that present in the dataset.



## Dependencies and Output Generation:

* Install required dependencies [make sure to install Jupyter Notebook]
```text
  torch
  torchvision
  tensorboard
```

```bash
  pip install -r requirements.txt
```

* Run the Jupyter Notebook
```bash
  jupyter nbconvert --to notebook --execute GAN_MNIST.ipynb
```

* Run TensorBoard
```bash
  tensorboard --logdir=runs
```


  
## Input: (Real Image)
https://github.com/user-attachments/assets/7eeb53b7-8ecc-41a9-b4b5-04371d86ea6d

## Output: (Generated Image)
https://github.com/user-attachments/assets/51255216-7a49-48d5-b584-9b498ea6e92e
