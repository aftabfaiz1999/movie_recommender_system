# movie_recommender_system

how to run this at your machine locally 



prerequisite

python
jupyter
streamlit
pickle
pandas
numpy
scikit-learn


firstly 
clone repo or download zip file 
pip install all the prerequisite mention above 

in command prompt
pip install install python

pip install install jupyter

pip install install streamlit

pip install install scikit-learn



Now go the folder where project is located
open command prompt type jupyter notebook 
after notebook opened search for .ipynb file
run the file after running you will get two .pkl file
mow open new command prompt type streamlit run app.py




#Project Discription
This project based on content based recommand system 
fistly we import the data from data folder merge both csv into one df
notebook contain column as overview,genres,keywords	,cast	,crew all in the form of dictionary  and with the help of ast library we convert the dic to list 
after that making all converted list into one column name as tags for feature_extraction will use CountVectorizer to make all movies into vectors 
..now using cosine_similarity to calculate vectors angle for the closest movie if a vectors angle is less from the other movie vector it will suggest the surroundig vectors movie name eg.if we search avatar model will search for the closest movie vector and measure the angle less the angle it will good for recommand 
