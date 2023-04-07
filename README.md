Data for Doing Data Science
=======================================

Data sets from [Doing Data Science](https://www.amazon.com/Doing-Data-Science-Straight-Frontline/dp/1449358659) by [Cathy O'Neil](https://mathbabe.org/) and [Rachel Schutt](https://industry.datascience.columbia.edu/profile/rachel-schutt). I highly recommended picking up a copy for yourself.

On pages 37-38:

This [folder](https://github.com/oreillymedia/doing_data_science) contains 31 simulated days of ads shown and clicks recorded on the New York Times home page. Rows represent users, and the variables are: `Age`, `Gender` (0 = female, 1 = male), `Impressions` (number impressions), `Clicks` (number clicks), and a binary indicator for signed in or not `Signed_in`. We need to create two new variables: `age_group`, which contains six levels of `Age` ("&lt;18", "18-24", "25-34", "35-44", "45-54", "55-64", and "65+"), and `CTR` or clickthrough-rate, calculated as the number of clicks / the number of impressions.
