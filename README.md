To run this app inside your laptop
- clone the repo/download
- create a virtual environment in your IDE(where you want to store the dependencies)
- run this command('conda create -p venv python==3.8 -y')
- conda activate venv/
- now just run(pip install -r requirements.txt)
- and here you go run(python run app.py)
- go to your browser write(127.0.0.5000/predictdata)

  
1) Problem statement
- This project understands how the student's performance (test scores) is affected by other variables such as Gender, Ethnicity, Parental level of education, Lunch and Test preparation course.

=> terms used
- Gender
- parental_level_of_education
- race_ethnicity: this term divides the student into different groups based on various educational and family background.
- lunch:- the term used as the student will take lunch of which category before giving the exam whether it is standard or normal/free.
- test_preparation_course:- the course provided has been completed by student or not
- reding score
- writing score

2) Data Collection
- Dataset Source - https://www.kaggle.com/datasets/spscientist/students-performance-in-exams?datasetId=74977
- The data consists of 8 column and 1000 rows.
