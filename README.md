# IMDB Sentiment Analysis
This app loads a sentiment analysis classification model that has been trained on IMDB text reviews and labels of 'positive' or 'negative', allows a user to input a movie review, and uses the classification model to output a predicted sentiment and the predicted probabilities.

## Prerequisites
To get this app up and running Docker and python must be installed on your machine. Access to a web browser is also required.

## How To Run
- 'git clone' this repo in project directory of choice.
- Run 'make build' to build the Docker image.
- Run 'make run' to run the Docker container.
- Navigate to http://localhost:8501/.
- Input movie reviews into the text area and play around!
- When finished press Ctrl+C to stop the application from running.
- Run 'make clean' to remove the Docker image.
