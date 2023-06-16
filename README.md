# Real-Estate-Price-Prediction
This project is about predicting house prices in Ho Chi Minh city, Vietnam. It was originally a real-life project that I was assigned to do during my internship in summer 2020. My roles for the project were only about data pre-processing and data analysis, so I never had to build models. 

The data set is taken from multiple sources of real estate websites. The customers hold their real data and only agree to provide once the credible evidences are shown to prove that the predictive models work fine on sample sets.
## IMPORTANT NOTES
I will submit two parts of the project. The first one is all about data pre-processing using raw dataset. Since the original dataset is confidential according to the law of my previous company, so it was no longer available for you to run the codes, but you can still see all the works that I myself did by then. Fortunately, I'm still able to access to the cleaned dataset - the sales data (I divided the original dataset into two subsets for lease and for sale, as you can see later).

The second part will continue on where I have never had the chance to complete, which are data analysis and model building.

## PART 1
Import libraries and objects we will use

<img width="490" alt="image" src="https://github.com/namphamspjain/Real-Estate-Price-Prediction/assets/72693967/d8eb7381-e172-4496-88a7-3d215089c2d7">

## Explore the dataset further
<img width="1113" alt="image" src="https://github.com/namphamspjain/Real-Estate-Price-Prediction/assets/72693967/5a6ba1a2-bd27-44fd-b3fe-9c6a12c7d6b7">

## Now, we would define a function that tells how many NA and their percentage in each column
<img width="613" alt="image" src="https://github.com/namphamspjain/Real-Estate-Price-Prediction/assets/72693967/d23baa1c-362a-4d70-a347-131a9171670e">
<img width="432" alt="image" src="https://github.com/namphamspjain/Real-Estate-Price-Prediction/assets/72693967/8566f948-4f78-4888-a6f8-c167f31633bb">

## Comment
It seems like there are a lot of columns with no values or just one unique value, we will drop all of these since they are not useful for data analysis

## Cleaning data by removing unneccessary null values
<img width="1009" alt="image" src="https://github.com/namphamspjain/Real-Estate-Price-Prediction/assets/72693967/6bcec3e9-5ae4-4aaa-9a7e-c4c6dcc25d3d">

