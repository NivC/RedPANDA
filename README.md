
# [Red PANDA: Disambiguating Image Anomaly Detection by Removing Nuisance Factors](https://www.google.com)

We will include here details on the *NAGAD* anomaly detection setting proposed in our paper "Red PANDA: Disambiguating Anomaly Detection by Removing Nuisance Factors"

# *NAGAD* Benchmark 
The datasets we used to evaluate the *NAGAD* anomaly detection setting can be found in the following link:
https://drive.google.com/drive/folders/13EaXyf4XQvOenHgOJL1sn9UMdWRTijZ9?usp=sharing

In each file, the key `'imgs'` contain the samples; `'anom_label'` describes the ground truth label (0 - a normal seen sample, 1 - an anomaly, 2 - normal "pseudo anomaly"). The other keys described the attributes directly. They are not part of the setting but are used to evaluate the used disentanglement approach.

# Additional challenges:
We also supply in the script `mvtec_augment_data.py` which is used for the *MVTec-AD based anomaly detection with nuisance factors* benchmark (described in Sec.6 and App.A in the paper).
