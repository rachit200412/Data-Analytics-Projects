library(tidyverse)
library(readxl)
library(janitor)
library(stringr)


customers <- read_csv("data/QVI_purchase_behaviour.csv")
transactions <- read_excel("data/QVI_transaction_data.xlsx")


dim(transactions)
names(transactions)
glimpse(transactions)
summary(transactions)

colSums(is.na(transactions))

sum(duplicated(transactions))

transactions <- distinct(transactions)

sum(duplicated(transactions))

transactions <- transactions %>%
  mutate(BRAND = word(PROD_NAME,1))

transactions <- transactions %>%
  mutate(PACK_SIZE = str_extract(PROD_NAME,"\\d")%>%
           as.numeric())

write_csv(
  transactions,
  "data/cleaned_transaction.csv"
)

