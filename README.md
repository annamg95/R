library(help=datasets)

install.packages("sqldf")
library(sqldf)
sqldf("select distinct Petal.Width from iris")
View(iris3)
