# IMDB_CNN_binary_classification
IMDB 리뷰 데이터를 이용하여, 같은 장르의 영화를 이진분류하는 저장소 입니다.

This Repo is binary classfication the movie, using IMDB review data




# 0. few precautions

There is no way to determine the accuracy of the classification.

in horror movies, for example, it is too unrealistic to clearly distinguish one’s feelings to fears and cruelty. (objectively)

therefore, we have tried some customizations for deep learning, but that was pointless.


It is nonsense in itself to conclude a particular movie to particular(second) category

if the category of comedy "Joker" (2019) is divided into "Black Comedy" and "Just Comedy."

my personal view is definitely is "Black Comedy."

but, may be some people judge it as 'Just Comedy.'

therefore, to provide such an objective definition, 

an survey is needed to determine whether a large number of people recognize 'joker' as 'black comedy' or 'comedy'.

only then can objectify the classification of a movie.

however, do not currently have such clear information because we have not gone through the survey process.

#### In conclusion, unverified data is used in training sets, so accuracy cannot be measured.



### but

I think that the accuracy of the simple binary classification is about 65-70 percent. (not objectively, it's just personal conjecture.) 





# 1. Required data.

To use this code, you need the following review data:

![주석 2019-11-26 225156](https://user-images.githubusercontent.com/16573620/69639298-9a223900-109f-11ea-8bc2-7f8745bdae37.png)

the data are organized as follows:

**STAR | USER ID | REVIEW TITLE | REVIEW CONTENT**

in fact, I don't need information about [STAR, USER ID, review TITLE], 

however [STAR, USER ID, review TITLE] are useful information.

so I thought someone could be useful use, so included it.



# 2. result data

![1111](https://user-images.githubusercontent.com/16573620/71164302-1e786e00-2292-11ea-81d8-c8fc3cf3cd5d.png)

The output is as shown above.

And

You can check the binary classification of the entire horror movie by watching the poster.

The closer to 0%, the scarier (maybe include supernatural content) horror movie,

and closer to 100%, the more cruel the horror movie, click on the image to view the video.

[![주석 2019-12-19 205728](https://user-images.githubusercontent.com/16573620/71173636-951f6680-22a6-11ea-9563-c9056fe3dede.png)](https://www.youtube.com/watch?v=OTeKfsTBfqg)

