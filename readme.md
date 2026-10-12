# [MATLAB] EEMD-ARIMA Joint Time Series Forecasting Algorithm, Preferred Research and Innovation Algorithm

Intention to obtain the code, please watch the code acquisition method at the end of this message~
1. EEMD Signal Decomposition Algorithm
EEMD decomposition, also known as Ensemble Empirical Mode Decomposition, is an English abbreviation for Ensemble Empirical Mode Decomposition.
EEMD is an improvement over EMD, capable of overcoming some of the shortcomings of EMD. The main idea of EEMD is to obtain multiple sets of EMD decompositions through multiple noise perturbations on the original dataset, and then average these EMD sets to obtain the final EEMD decomposition results. The main steps of EEMD are as follows:
Randomly perturb the original signal several times to obtain multiple noise perturbation datasets.
Perform EMD decomposition on each noise perturbation dataset to obtain multiple EMD decomposition sets.
Average the corresponding components of each EMD decomposition set to obtain the final EEMD decomposition result. The advantage of EEMD decomposition is that it can overcome the limitations of EMD, such as the selection of base functions and mode overlap issues. At the same time, EEMD can also provide better signal-to-noise ratio and higher decomposition accuracy. Therefore, EEMD has been widely used in fields such as signal processing, image processing, and pattern recognition.
To use EMD decomposition in MATLAB, you first need to install the EMD decomposition MATLAB toolkit.
Installation of EMD Toolkit: Open the package_emd folder in MATLAB, run install_emd. M and index_emd. M as shown in the figure below to complete the installation of the toolkit.
MATLAB Signal Decomposition Second Session - EEMD:
For more details about the entire family of signal decomposition tools, please refer to:
2. ARIMA Time Series Forecasting Algorithm
The ARIMA (Autoregressive Integrated Moving Average) model is a predictive model based on time series analysis, suitable for analyzing and forecasting data with both time-dependent and stochastic characteristics. The ARIMA model was first proposed by Box and Jenkins in 1976 and has since become a widely used time series model for data prediction in production and finance sectors. The core idea of the ARIMA model is to decompose the time series data through differencing, making the sequence stationary, and then establish the model by combining autoregression (AR) and moving average (MA), using this model for forecasting. The "AR" in the ARIMA model represents autoregression, indicating that current data are related to previous several moments of data; the "I" denotes differencing, which makes the data stationary; and the "MA" stands for moving average, representing that current data are related to previous errors.
The establishment process of the ARIMA model includes three steps: model identification, parameter estimation, and model verification. In the model identification phase, it is necessary to determine the order of the ARIMA model and the number of differencing times; in the parameter estimation phase, the model parameters need to be estimated; in the model verification phase, the model needs to be verified and judged whether the prediction accuracy meets the requirements. The ARIMA model has the advantage of fully utilizing historical information of time series data for prediction, can adapt to various types of time series data, and has good explanatory power. However, there are some disadvantages to the ARIMA model, such as the need to perform differencing on non-stationary time series data, and the process of parameter estimation is relatively complex.
MATLAB | Time Series Forecasting | ARIMA Forecast Model:
For more details about five time series forecasting schemes, please refer to:
3. EEMD-ARIMA Joint Time Series Forecasting Algorithm Next, we will introduce in detail the principle and thought behind the latest EEMD-ARIMA joint time series forecasting algorithm.
Signal decomposition can break down raw data into N layers of imf components. In this study, we expand the ARIMA time series prediction for each layer's imf component and then reconstruct the predicted values of the imf components to obtain the EEMD-ARIMA joint time series prediction values.

By comparing the EEMD-ARIMA joint time series prediction values with the pure ARIMA time series prediction values against the true values, we find that the EEMD-ARIMA joint time series prediction algorithm has a good predictive effect. The reason is not hard to see; signal decomposition breaks down the original data into different frequency components, which means that the frequencies of each layer's imf component are roughly the same, making it a data with good periodicity and regularity. Therefore, when using the ARIMA time series prediction algorithm to predict each layer's imf component, its predictive results will be closer to the true value.

Below is a brief video tutorial.

\n\n\n\n\n\nTo view this video please enable JavaScript, and consider upgrading to a\nweb browser that\nsupports HTML5 video\n

## Images

![(MATLAB)EEMD-ARIMA Joint Time Series Forecasting Algorithm, Preferred Research and Innovation Algorithm](cover.jpg)

<!-- PAYMENT_BLOCK -->

## Get this dataset

- Payment link (Stripe): [Buy now](https://buy.stripe.com/3cs8yP7sY87d0vu9AB)
- Payment QR code: ![Payment QR code](pay.png)

<!-- /PAYMENT_BLOCK -->
