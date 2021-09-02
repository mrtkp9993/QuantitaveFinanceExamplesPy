# QuantitaveFinanceExamplesPy

Financial analysis, algorithmic trading, portfolio optimization examples with Python 

DISCLAIMER - No Investment Advice Provided

YASAL UYARI - Burada yer alan yatırım bilgi, yorum ve tavsiyeleri yatırım danışmanlığı kapsamında değildir.

## References (for both methods and some code fragments)

* Hilpisch, Y. J. (2021). Python for algorithmic trading: From idea to cloud deployment. O'Reilly.
* Jansen, S. (2020). Machine learning for algorithmic trading: Predictive models to extract signals from market and alternative data for systematic trading strategies with python. Packt Publishing.
* Pik, J., &amp; Ghosh, S. (2021). Hands-on financial trading with python. Packt Publishing.
* Velu, R. P., Hardy, M., &amp; Nehren, D. (2020). Algorithmic trading and quantitative strategies. CRC Press, Taylor &amp; Francis Group.

## Contact

Murat Koptur, [LinkedIn](https://www.linkedin.com/in/muratkoptur/)

Email: [muratkoptur@yandex.com](mailto:muratkoptur@yandex.com?subject=QuantitativeFinanceGithub)

## Examples

### Calculation Alpha and Beta factors

![01_01](imgs/01_01.png)

### Cointegration

```
ARCLK.IS and TOASO.IS has cointegration, p-value: 0.04903369798110527
AYGAZ.IS and KCHOL.IS has cointegration, p-value: 0.007029900251131765
FROTO.IS and MAALT.IS has cointegration, p-value: 0.015757028038897322
FROTO.IS and OTKAR.IS has cointegration, p-value: 0.004399007493986555
KCHOL.IS and AYGAZ.IS has cointegration, p-value: 0.007101145930953294
MAALT.IS and FROTO.IS has cointegration, p-value: 0.00783799297255268
OTKAR.IS and FROTO.IS has cointegration, p-value: 0.003094678911810982
OTKAR.IS and TTRAK.IS has cointegration, p-value: 0.04185601871282213
OTKAR.IS and YKGYO.IS has cointegration, p-value: 0.00282083357242191
TTRAK.IS and OTKAR.IS has cointegration, p-value: 0.03639137062922606
TTRAK.IS and YKGYO.IS has cointegration, p-value: 0.03834839887528665
YKGYO.IS and OTKAR.IS has cointegration, p-value: 0.0017665073676291331
YKGYO.IS and TOASO.IS has cointegration, p-value: 0.046004150077470406
YKGYO.IS and TTRAK.IS has cointegration, p-value: 0.027200620035757236
```

### PCA on Returns

![03_01](imgs/03_01.png)


### Volatility calculations

```
Std.Dev. Estimator:          0.16988244687319595
Classical Estimator:         0.0013349197336295028
Rogers - Satchell Estimator: 0.0009643228704150725
Yang - Zang estimator:       0.0016329397449278639
```

### Volatility-Volume Relationship

![05_01](imgs/05_01.png)

### AR-ARCH models for volatility

![06_01](imgs/06_01.png)

### VWAP 

![07_01](imgs/07_01.svg)

### Technical Indicators

![08_01](imgs/08_01.png)
