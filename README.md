# DonorResponse
This project builds a supervised machine-learning model using logistic regression to predict if a donor in a charity will respond with a gift.

The data "donorgift.csv" contains information on donors' behaviours and their charitable contributions through mailers. It contains 4268 observations on 8 variables.
-   response: indicates if the donor responded with a gift. (respond =
    yes if responded with gift, otherwise no)
-   gift: the amount of gift in Dutch guilders
-   responselast: indicates if the donor responded to the most recent
    mailing (1 if responded to most recent mailing, otherwise 0)
-   weekslast: number of weeks since donor's last response
-   propresp: the response rate to mailings
-   mailsfreqyear: represents the frequency of mailings per year (low,
    medium, high, very high)
-   giftlast: the amount of most recent gift
-   avggift: average of past gifts

Charities rely on donors' willingness to contribute. This dataset contains information on 4268 donors from previous donation drives. Each observation describes a donor's behaviour and response to prior donation mailers. It is important for charities to know which donors to divert their attention to. This project builds a logistic regression model to do so.
