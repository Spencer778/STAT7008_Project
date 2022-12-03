The presentation video has been posted on YouTube
Please refer to: https://youtu.be/QclAUeRFAr4

For item-based filering system:

This system is run on jupyter notebook. 
If you are going to check the result, please run the file, item_based_system.ipynb, in Item-based-system folder.
Its corresponding data is in the folder, too, named 'item_based_data.csv'.

For content-based system:

1. Intro of files:

1.1 In data_processing folder:
    ① movie_dataset.ipynb is to request data to build our movie database, whose result is saved as "main_data.csv " at the outer folder.
    ② sentiment.ipynb is to analyze reviews, and the train_data.csv is for this part.

1.2  In static folder:
    ① This folder saves some elements and files, like js files and css file, to render our website.

1.3 In template folder:
    ① The two html files are to  construct the page of our website. 
    ② One for the home page, the other for the recommend page.

1.4 Outer：
    ① main.py: the main body of our system, we define recommend function and build flask frame in this file.
    ② main_data.csv: our movie database, the result of movie_dataset.ipynb introduced before.
    ③ nlp_model.pkl: a file saving our sentiment model, logistic regression, produced by sentiment.ipynb
    ④ tranform.pkl: a file saving our vectorization method in sentiment analysis part, also produced by sentiment.ipynb

2. Runing Steps:

2.1 Required lib:
    Flask / gunicorn / Jinja2 / MarkupSafe / Werkzeug / numpy / scipy / nltk / scikit-learn
    pandas / beautifulsoup4 / jsonschema / tmdbv3api / lxml / urllib3 / requests / pickleshare

One of the following methods is OK
2.2 Method 1:
    Step 1: Download this repository to your local machine.
    Step 2: Install all the libraries mentioned above
    Step 3: Open your terminal/command prompt from your project directory, e.g. C:\xxx\Desktop\Content-based-system
    Step 4: Run the file 'main.py' by executing the command 'python main.py'.
    Step 5: Go to your browser and type 'http://127.0.0.1:5000/' in the address bar.

2.3 Method 2:
    Step 1: Download this repository to your local machine.
    Step 2: Install all the libraries mentioned above
    Step 3: Open the main.py with our own IDE
    Step 4: Run the file `main.py`.
    Step 5: Go to your browser and type `http://127.0.0.1:5000/` in the address bar.




