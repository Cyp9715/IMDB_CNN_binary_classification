# IMDB_CNN_binary_classification
IMDB 리뷰 데이터를 이용하여, 같은 장르의 영화를 이진분류하는 저장소 입니다.

This Repo is binary classfication the movie, using IMDB review data




# 0. there are a few precautions

There is no way to determine the accuracy of the classification.

in horror movies, for example, it is too unrealistic to clearly distinguish one’s feelings, fears and cruelty. (objectively)

therefore, we have tried some customizations for deep learning, but there is no way to measure accuracy


It is nonsense in itself to conclude a particular movie with a particular category

if the category of comedy "Joker" (2019) is divided into "Black Comedy" and "Just Comedy."

my personal view is definitely is "Black Comedy."

but, may be some people who judge it as just 'Just Comedy.'

Therefore, giving such an objective definition requires a survey to determine whether the film is perceived by countless people as being "Black Comedy" or "Comedy."

only then can we objectify the classification of a movie.

however, we do not currently have such clear information because we have not gone through the survey process.


but

personally think that the accuracy of the simple dichotomy is about 65-70 percent.





# 1. Required data.

To use this code, you need the following review data:

![주석 2019-11-26 225156](https://user-images.githubusercontent.com/16573620/69639298-9a223900-109f-11ea-8bc2-7f8745bdae37.png)

the data are organized as follows:

**STAR | USER ID | REVIEW TITLE | REVIEW CONTENT**

in fact, we don't need information about [STAR, USER ID, review TITLE], 

however [STAR, USER ID, review TITLE] are useful information.

so I thought someone could be useful use, so included it.



# 2. result data


