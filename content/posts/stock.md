+++
date = '2024-12-22T21:57:28+08:00'
draft = false
title = 'The main capital flow calculation of the stock market'
tags = ["Java"]
+++

In the stock market, the major capital refers to a trader who has concentrated a large amount of money and has the ability to lead the rise and fall of a stock. Therefore, it is important to identify the major capital in the stock market.

This project aims to output the main net inflow, main inflow, main outflow and individual volume and turnover of each time interval divided by T-window in the continuous bidding and closing aggregate bidding stages according to the given stock code and T-window.

Datasets include:
+ **Delegate data table**: It records the orders issued by investors to buy or sell a specific number of stocks to brokerages, including the index of orders, security code, price of orders, quantity of orders, trading direction and other information.
+ **Transaction data table**: The transaction information of each order is recorded, including transaction price, transaction quantity, buyer and seller entrustment index, transaction time and other information.

Using mapreduce technology in Java, we feed in the data and process the calculations, output the results as CSV tables, and visualize them.

*[Calculation of main capital flow in stock market](https://drive.google.com/drive/folders/1Vp9MeeBtfN1mioeMUuncgN9XTKgUXsOC?usp=sharing)*