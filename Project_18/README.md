# Project 18 - Development of the model for search of image by text query

Photo hosting for the professinal photographers wants to develop the service of the searching tool for the search of similar photos by text query. Users of hosting can upload the photos with full decription such as place, date, camera model, etc and also can add a description to the photos of others users. Based on the provided data from hosting it's required to develop preliminary version of tool which could find the most suitable image by text query.

Main goal of the project is to develop demo version on image search by text query.

The tasks to be completed for goal achievement:
1) import of data and exploratory data analysis;
2) data preparation:
    - to creat the list of words for censore recognition;
    - deletion of censored
    - to vectorize the text;
    - to vectorize the images;
3) to train the models -linear regression and neural networks;
4) Test the vest model and prepare the demo version of it image search;
5) to draw a conclusion.

Provided data includes five datasets:
- `train_dataset.csv` 
- `CrowdAnnotations.tsv`
- `ExpertAnnotations.tsv`
- `test_queries.csv`
- `test_images.csv`

and two folders with 5822 and 1000 images.

## Data description
Data provided in folder /datasets/image_search/.

File train_dataset.csv has the required information for models training:

image file name;
query id;
query text.
One image could have up to 5 text queries. Query id has the following format: - <image file name>#<query_number>.

Folder train_images has images for models training;

File CrowdAnnotations.tsv - has data with infromation of correspondence of the image and query, obtained from crouwdsource. The columns numbers following:

Image file name.
Query id..
Percentage of people who confirmed the image and query correspondance.
Quantity of pepole who confirm that query fit to image.
Quantity of pepole who does not confirm that query fit to image.
File ExpertAnnotations.tsv has data on has data with infromation of correspondence of the image and query, obtained during the expers questionnaire. The columns are following:

Image file name.
Query id.
3, 4, 5 - Experts rating.

Experts are rate the correspendance of image in query using the following scale:

1) - image does not match query;

2) - query has a desription of a few elements of image, but overall not related to image;

3) - query and image correspond to each other with descreption of the details;

4) - query and image match on 100%.

File test_queries.csv has the data required for model testing: query id, query text, image file name. One image could have up to 5 text queries. Query if has the following format: - <image file name>#<query_number>.

Folder test_images has images for testing.
