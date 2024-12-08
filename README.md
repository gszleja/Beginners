# Beginners

## Hipoteka

### Trzeba ustalić co ma najwiekszy wpływ na otrzymanie kredytu hipotocznego
getwd()

table(Hipoteczny)

library(tidyverse)
library(dlookr)
library(VIM)
library(validate)
attach(Hipoteczny)
reguly<-editset(c(
"Dependents>=3"

))
summary(violatedEdits(regulu,Hipoteczny))

bledy<-valiotedEdits(reguly,Hipoteczny)
plot(bledy)
dane[localizeErrors(reguly,Hipoteczny$adapt)] <- NA

czyste_dane



