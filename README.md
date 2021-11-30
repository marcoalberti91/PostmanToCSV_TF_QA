# PostmanToCSV_TF_QA
- Postman collection created, with test condition to print out Pokemon name with normal type.
- The collection run on the first 30 Pokemon using the data file Poke.csv, as iteration data.
- The collection is executed using newman (v5.3.0) and the reporting package "newman-reporter-csv". The command is the following: "newman run Poke.postman_collection.json -d poke.csv -r csv"
- This command enables to create a csv output where positive test results and negative test results are save on two separate column, which allows to extract the following list of Pokemn with normal type:

pidgey,pidgeotto,pidgeot,rattata,raticate,spearow,fearow