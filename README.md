# Sport Classification Model

Our primary objective is to develop a supervised classification model that accurately predicts the sport type (bike ride, run, walk, etc) of a given activity based on its recorded metrics.

GPS watches record an athlete’s location, distance, time spent moving, elevation gain, and more. However, the sport type is not programmatically set; before starting their workouts, athletes using GPS watches must first manually select from a list of sports on the device. The need to manually select a sport type often leads to user error: 

Our classification model will accurately classify the sport type of workouts - primarily Ride, Run, Walk, Hike, and an “Other” bucket. The model will leverage features such as distance, moving time, elapsed time, elevation gain, average speed, start date, start coordinates, and GPS traces. 

An additional stretch goal is to distinguish between standard bicycle rides and e-bike rides. Distinguishing e-bike rides from standard bicycle rides is a growing concern on platforms like Strava, where e-bike users may unfairly claim leaderboard positions. A robust classification model can flag suspicious activities for review.

# Files

01-data-cleaning-and-feature-engineering.ipynb

02-eda.ipynb

03-modeling.ipynb
