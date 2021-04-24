# Project_2_ETL
Repo for Project_2_ETL

# Video Game "Collection"
Challenge: A friend has an extensive collection of video games and has asked for help setting a website to display them (and maybe sell them later). For now he has sent a list of 228 of his favorites to see if I can develop a method to gather possible web-page elements for each game to begin automating creation of the pages.

For each game, the following elements were extracted from the data source using the method listed:
* Release Year (imported from given csv)
* Title (imported from given csv)
* Publisher (imported from given csv)
* Platform (imported from given csv)
* Release Details (Web scraped, Wikipedia)
* Game Standard/Box's Cover Image (Web scraped, Wikipedia)
* Description of the Gameplay (API Calls, RAWG.io)
* Gameplay Screenshot URLs (API Calls, RAWG.io)

The data was aggregated into a pandas dataframe, cleaned/quality checked to validate the method and then loaded to cloud-based MongoDB for future use in creating the site.

## Cover Art (source Wikipedia)

![Super_Mario_Cart_Cover](https://upload.wikimedia.org/wikipedia/en/thumb/3/38/Supermariokart_box.JPG/220px-Supermariokart_box.JPG)


## In-Game Screen Shots (source RAWG.io)

![Super_Mario_Cart_Screenshot_1](https://media.rawg.io/media/screenshots/ca2/ca2f8c6488f8204c9f6371043a8e3414.jpg)

![Super_Mario_Cart_Screenshot_2](https://media.rawg.io/media/screenshots/971/971f8d29b7babb8955823b02e7ebb1d9.jpg)

![Super_Mario_Cart_Screenshot_3](https://media.rawg.io/media/screenshots/3fe/3fe623feeb8cf55a25845d56522c877e.jpg)