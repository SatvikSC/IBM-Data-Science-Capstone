# Peer-graded Assignment: Capstone Project - Car accident severity (Week 1)

### 1. Clearly define a problem or an idea of your choice. Remember that data science problems always target an audience and are meant to help a group of stakeholders solve a problem, so make sure that you explicitly describe your audience and why they would care about your problem.

**ANS:** Street traffic wounds are at present assessed to be the eighth driving reason for death over all age bunches all around the world and are anticipated to turn into the seventh driving reason for death by 2030.

Breaking down a huge scope of components, including climate conditions, unique occasions, roadworks, gridlocks among others, a precise forecast of the seriousness of the mishaps can be performed.

These bits of knowledge could permit law implementation bodies to apportion their assets all the more adequately ahead of time of possible mishaps, forestalling when and where serious mishaps can happen just as sparing both, time and cash. Moreover, this information on an extreme mishap circumstance can be cautioned to drivers with the goal that they would drive all the more cautiously or even change their course on the off chance that it is conceivable or to the medical clinic which might have set everything prepared for a serious intercession ahead of time.

Governments ought to be profoundly inspired by, exact expectations of the seriousness of a mishap, so as to diminish the hour of appearance and subsequently spare a lot of individuals every year. Others intrigued could be privately owned businesses putting resources into advancements meaning to improve street safeness.

This task comprises of a few sections separated into two unique note pads.


### 2. Describe the data that you will be using to solve the problem or execute your idea. So make sure that you provide adequate explanation and discussion, with examples, of the data that you will be using.

**ANS:** The original data for this project comes from the following Kaggle data set. In a previous notebook, Feature Selection, I performed a selection of the most relevant features for the prediction of traffic accident severity.

The features of the dataset resulting are the following:

In the characteristics dataset, I will keep the features: "lighting", "localisation"(agg), "type of intersection", "atmospheric conditions", "type of collisions", "department", "adress", "time" and the coordinates. I added two new features from this original dataset: "date" and "weekend" indicating if the accident occurred during the weekend or not.

In the places dataset, I will keep only the features: "road categorie", "traffic regime", "number of traffic lanes", "road profile", "road shape", "surface condition", "situation", "school nearby" and "infrastructure".

From the users dataset, I have created the following features:

num_us: total number of users involved in the accident.
ped: Wether there are pedestrians involved or not.
critic_age: If there is any user in between 17 and 31 y.o.
sev : maximum gravity suffered by any user involved in the accident:
0 = Unscathered or Light injury
1 = Hospitalized wonded or Death
I used the holiday dataset to craft a new feature indicating the accident accurred during a holiday
