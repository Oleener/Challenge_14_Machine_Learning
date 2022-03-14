# Challenge_14_Machine_Learning
This is a Jupyter Notebook that uses financial Python programming and machine learning to create an algorithmic trading bot that learns and adapts to new data and evolving markets. This notebook will Implement an algorithmic trading strategy that uses machine learning to automate the trade decisions, Adjust the input parameters to optimize the trading algorithm, and Train a new machine learning model and compare its performance to that of a baseline model.

---

## Technologies 

This project leverages python 3.7 with the following packages:

```
Jupyter Notebook 
NumPy
Pandas
hvPlot
matplotlib
scikit-learn
```

---

## Installation Guide 

Before running the application first install the following dependencies.

Install Anaconda Package
```
Pip intall Jupyter 
```

---

## Usage 

To create an algorithmic trading bot, clone the repository and run **Jupyter Lab** in python: 

```python
Jupyter Lab
```

Jupyter lab should launch in a web browser, if it doesnt select one one of the hyperlinks it provides copy it and paste it into a web browser page.  

---

## Tune the Baseline Trading Algorithm

### Adjusted Training Dataset Model

What impact resulted from increasing or decreasing the training window? 

![adjusted](https://github.com/Oleener/Challenge_14_Machine_Learning/blob/main/Models/Adjusted%20Traing%20dataset.png)

### Adjusted SMA Input Model

What impact resulted from increasing or decreasing either or both of the SMA windows?

![SMA](https://github.com/Oleener/Challenge_14_Machine_Learning/blob/main/Models/Adjusted%20SMA%20Imput.png)

### Parameters that best improved the trading algorithm returns

![Model_3](https://github.com/Oleener/Challenge_14_Machine_Learning/blob/main/Models/Model_3.png)

---

## Evaluation Report

### Baseline Performance Model 
![Model_1](https://github.com/Oleener/Challenge_14_Machine_Learning/blob/main/Models/Model_1.png)

### New Machine Learning Classifier Model
![Model_2](https://github.com/Oleener/Challenge_14_Machine_Learning/blob/main/Models/Model_2.png)

### Conclusion 

After increasing the training window from 3 months to 24 there was a significant change in the plot. When Looking at the plot it is visable that the actual returns and strategy returns had a strong correlation in the begining however after about 2020 they began widening. When comparing this model to the baseline performance model this model began widening much later. Resulting in a higher return then the baseline performance model. To tune the trading algorithm by adjusting the SMA input features, I decided to increase both of the SMA windows. I increased the short window to 50 and long window to 200 during a 3 month period. The model significantly improved. Both the actual returns and strategy returns were in a strong correlation of one another. This model performed significantly better then the baseline performance model. After tightening the training window and tweaking the SMA inputs resulted in some improvement but the model is still only showing predictive strength through limited slices of the time series. Overall the New Model Performed better than the provided baseline model. However when comparing the new model to the tuned trading algorithm model it is only showing predictive strength through limited slices of the time series. 

---

## Contributor

Brought to you by Olena Shemedyuk.

email: Olenashemedyuk@gmail.com

---

## License

MIT