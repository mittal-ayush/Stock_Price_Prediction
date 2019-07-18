# Stock_Price_Prediction
Broadly, stock market analysis is divided into two parts – Fundamental Analysis and Technical Analysis.

    Fundamental Analysis involves analyzing the company’s future profitability on the basis of its current business environment and financial performance.
    Technical Analysis, on the other hand, includes reading the charts and using statistical figures to identify the trends in the stock market.
    
Our focus here, will be on the technical analysis part. I’ll be using a dataset from Quandl and for this particular project, I have used the data for ‘Tata Global Beverages’.

# Long Short Term Memory (LSTM)
Introduction:

LSTMs are widely used for sequence prediction problems and have proven to be extremely effective. The reason they work so well is because LSTM is able to store past information that is important, and forget the information that is not. LSTM has three gates:

    The input gate: The input gate adds information to the cell state
    The forget gate: It removes the information that is no longer required by the model
    The output gate: Output Gate at LSTM selects the information to be shown as output
    
The LSTM model can be tuned for various parameters such as changing the number of LSTM layers, adding dropout value or increasing the number of epochs. But are the predictions from LSTM enough to identify whether the stock price will increase or decrease? Certainly not!
