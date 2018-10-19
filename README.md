# Summary

This is a Mule 4 application that retrieves Crunchbase news articles in batches of 250 and uploads the articles to a PostGresSQL Database.

The program first retrieves a list of companies to retrieve news articles related to that company and proceeds to build the necessary parameters to connect to the Crunchbase API via HTTP.

The application then maps the data returned from the API and uploads the data into a PostGresSQL server.
