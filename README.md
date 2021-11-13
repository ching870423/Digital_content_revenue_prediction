# Digital_content_revenue_prediction
A research project creates a prediction model to help content providers leverage social media more efficiently.

## Background
Workinsa as a Data Science research assistant at Academia Sinica, I teamed up with [Szu-Chuang Li](http://www.ic.tku.edu.tw/index.php/component/sppagebuilder/page/50-tommy.html) to conduct another innovative research: Predicting Advertisement Revenue of Social Media DrivenContent Websites: Toward More Efficient and SustainableSocial Media Posting.

In the research project, I conducted feature engineering in image properties and word embedding of NLP. I also take information before posting as input features, such as fans of pages, posts category, and teimline of posting, to build up three machine learning classifiers: Decision Tree, XGBoost, and Deep Neuron Network. To improve the performance of the classifiers, I deal with imbalanced issue of our customised labeled data set.

The research figure out the model that can minimize the amount of social media posting while retaining most of the advertisement revenue13and user engagement. The best model found is an XGBoost classification model, which can reduce 70% of the total posting number while maintaining 70% of the advertisement revenue. The model15can help a content website post much less and minimize the revenue loss due to less posting, which is beneficial for its continuous traffic redirection from social media platforms.

## Project Structure

Overall, Python is the main language for implementation and the result is run on Jupyter Notebook platform. I only present main part of projcet experiments as example.

In the file, [05_advertisement_image_feature_googleAPI.ipynb](https://github.com/ching870423/Digital_content_revenue_prediction/blob/main/05_advertisement_image_feature_googleAPI.ipynb), I extracted features of main pictures, such as topic colors or labels, in each posts using [Google Vision API-Detect image properites](https://cloud.google.com/vision/docs/detecting-properties) and [Google Vision API-Detect labels](https://cloud.google.com/vision/docs/labels).
