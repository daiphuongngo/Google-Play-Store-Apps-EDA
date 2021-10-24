# Google-Play-Store-Apps-EDA


## Overview:

Conducted different Explanatory Data Analysis methods to preprocess the dataset's each variables and deploy a Machine Learning model, namely the Linear Regression to calculate the RSME.

### Language & Tool: 

- Python

- Tableau

### Dataset:

Source link: https://www.kaggle.com/lava18/google-play-store-apps

| App | Category | Rating | Reviews | Size | Installs | Type | Price | Content Rating | Genres | Last Updated | Current Ver | Android Ver |
|-|-|-|-|-|-|-|-|-|-|-|-|-|

### Exploratory Data Analytis:

#### Data Engineering:

- Import Libraries

- Load Data

- Check data shape

- Check null sum

- Check duplicates

#### Process Data Columns:

- Type

- Review

- Category

- Genres

- Size

- Installs

- Price

- Content Rating

- Last Update

- Android Ver

### Visualization in both Python (as per Notebook) and Tableau (as below):

Bar - Content Rating vs Rating

![Bar - Content Rating vs Rating](https://user-images.githubusercontent.com/70437668/138580405-822d5c2a-e78b-44e3-98ea-39509813ed25.jpg)

Boxplot - Price filtered by Paid Type

![Boxplot - Price filtered by Paid Type](https://user-images.githubusercontent.com/70437668/138580421-2cdabed7-1a5a-483c-be53-5657fe9dd450.jpg)

Boxplot - Sum of Reviews 0-150K

![Boxplot - Sum of Reviews 0-150K](https://user-images.githubusercontent.com/70437668/138580425-ee5f67f9-79a6-42e2-b8fe-277417c073d8.jpg)

Boxplot of Rating vs Category with Types

![Boxplot of Rating VS Category with Types](https://user-images.githubusercontent.com/70437668/138580430-85d3d1c4-5023-4448-9996-f2b30d6bbe04.jpg)

Boxplot of Rating vs Category

![Boxplot of Rating VS Category](https://user-images.githubusercontent.com/70437668/138580434-662d9c9e-71f6-452b-a675-61017f4cc3b7.jpg)

Boxplot of Rating vs Genre with Types 

![Boxplot of Rating vs Genre with Types ](https://user-images.githubusercontent.com/70437668/138580437-123cd379-833c-4290-b919-e2bdbd135eac.jpg)

Distribution of Rating

![Distribution of Rating](https://user-images.githubusercontent.com/70437668/138580440-bfbd0a42-f058-416a-af14-03329b8bca3b.jpg)

Heatmap - Rating  

![Heatmap - Rating  ](https://user-images.githubusercontent.com/70437668/138580444-24d35f17-2ba0-47f8-bf3b-4256100a7574.jpg)

Heatmap - Rating bin vs Content Rating

![Heatmap - Rating bin vs Content Rating](https://user-images.githubusercontent.com/70437668/138580450-407bf428-9891-4a55-8343-701fea36d4fd.jpg)

Histogram - Rating group by Content Rating

![Histogram - Rating group by Content Rating](https://user-images.githubusercontent.com/70437668/138580454-e5c399c3-5e06-4e34-8e68-047d847291e8.jpg)

Line - Rating vs Sum Size

![Line - Rating vs Sum Size](https://user-images.githubusercontent.com/70437668/138580458-06e37b8d-3010-4867-999e-8e196eb67290.jpg)

Scatter Plot - Rating vs Count Size

![Scatter Plot - Rating vs Count Size](https://user-images.githubusercontent.com/70437668/138580462-52f1d9db-9adb-4998-a7cf-7a27e5011d88.jpg)


### Build Model:

- Pre-processing

- Featuring

- Predicting
