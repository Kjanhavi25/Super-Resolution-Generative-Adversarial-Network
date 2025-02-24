# SRGAN-Super Resolution GAN



### Train

```python
!python main.py --LR_path Data/train_LR --GT_path Data/train_HR
```

### Test
```python
!python main.py --mode test_only --LR_path test_data --generator_path pretrained_models/SRGAN.pt
```

Model User Interface

Home Page:
![image alt]("https://github.com/Kjanhavi25/Super-Resolution-Generative-Adversarial-Network/blob/d2c07b18335f70915c8b5d0c6bbe09bf3012a826/Home%20Page.jpg")

Image Enhancement: 
![image alt]("https://github.com/Kjanhavi25/Super-Resolution-Generative-Adversarial-Network/blob/d2c07b18335f70915c8b5d0c6bbe09bf3012a826/Converted%20Image.jpg")

Metric Home Page:
![image alt]("https://github.com/Kjanhavi25/Super-Resolution-Generative-Adversarial-Network/blob/d2c07b18335f70915c8b5d0c6bbe09bf3012a826/Metric%20Home%20Page.jpg")

Calculated Metrics:
![image alt]("https://github.com/Kjanhavi25/Super-Resolution-Generative-Adversarial-Network/blob/d2c07b18335f70915c8b5d0c6bbe09bf3012a826/Calculated%20Metrics.jpg")
