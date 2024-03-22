# ERA-Session-8

## Target:
* Create network with the following normalizations
  * Network with Group Normalization
  * Network with Layer Normalization
  * Network with Batch Normalization
* Keep the model params under 50k and achieve accuracy of >= 70% under 20 epochs

## Results

Normalization | Train Accuracy | Test Accuracy | Number of Params
| :---: | :---: | :---: | :---:
Group Normalization  | 79.53 | 73.73 | 25,168
Layer Normalization  | Content Cell | Content Cell | 45,560
Group Normalization (Group=1) | 85.07 | 76.02 | 25,168
Batch Normalization  | 74.80 | 72.19 | 25,168

## Group Normalization
- - - -
### Model Summary
![image](https://github.com/ShubhamVerma16/ERA-Session-8/assets/46774613/bc091e1d-6aed-4063-8aef-b15c6b5d53b3)
### Trainign curves Model Summary
![image](https://github.com/ShubhamVerma16/ERA-Session-8/assets/46774613/220dfa5d-d970-43ed-90a3-16a927a78512)
### Wrongly classifed Images
![image](https://github.com/ShubhamVerma16/ERA-Session-8/assets/46774613/224432ce-abb1-4e58-9e36-fcd02958bf29)

## Group Normalization (Group=1)
- - - -
### Model Summary
![image](https://github.com/ShubhamVerma16/ERA-Session-8/assets/46774613/20e22c5b-28c1-4c50-8855-43be03c94858)
### Trainign curves Model Summary
![image](https://github.com/ShubhamVerma16/ERA-Session-8/assets/46774613/c07f8cc7-35b0-4fdd-ab6b-1a0462e5f5b9)
### Wrongly classifed Images
![image](https://github.com/ShubhamVerma16/ERA-Session-8/assets/46774613/de376930-63e7-438e-951e-14b444d4944f)

## Layer Normalization
- - - -
### Model Summary
![image](https://github.com/ShubhamVerma16/ERA-Session-8/assets/46774613/a95ccd2b-3e8b-4da9-9c81-58c66b79cb7e)
### Trainign curves Model Summary
### Wrongly classifed Images

## Batch Normalization
- - - -
### Model Summary
![image](https://github.com/ShubhamVerma16/ERA-Session-8/assets/46774613/a2cb2e25-c702-49a7-9f04-23dd4bfc4fdc)
### Trainign curves Model Summary
![image](https://github.com/ShubhamVerma16/ERA-Session-8/assets/46774613/407f1b6e-c49d-491a-86a8-252efe9e96a4)
### Wrongly classifed Images
![image](https://github.com/ShubhamVerma16/ERA-Session-8/assets/46774613/2348753e-b196-4485-888d-4051a216f27b)

