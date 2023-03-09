# Stock-market-Pattern-Recognition-Mathematical-model
This is a mathematical computational model which extracted defined patterns from the CSV of stock market OHLC data 

Work-By-Nihar Patel Multiple Pattern recongniton of a time series data without use of CNN ->By usign the concept of identifying local minima as maxima, visually determining the transition points for occurence of patterns and generating functions for identification of various patterns. ->Use of Sliding window of variable size with exponential moving average to detect both long term and short term patterns.

**The program runs over the input of a csv file and a user defined input for the time interval for which patterns are to be detected. **The program returns the datapoints at which the particular pattern started and ended in the time span entered.

##The Repository also includes a CNN Model approach for pattern recongnition with a full fledged code working code for patterns image extraction with respective ID's and inclusion of a pretrained model for Pattern Detection with an overall good accuracy and Validation accuracy.

##The model accurately identifies the patterns extracted from the csv data but encounters the problem of superimposition to the csv data for identifying the start and end of the pattern for identifying dates.

