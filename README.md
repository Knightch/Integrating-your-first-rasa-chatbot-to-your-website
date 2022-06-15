## This project following medium article

- https://medium.com/@pratikmukherjee32/integrating-your-first-rasa-chatbot-to-your-website-3ee32f482950

## To create an environment download conda

- https://www.anaconda.com/products/individual#windows

## create an environment and activate it

- conda create -n newenv python=3
- conda activate newenv

## it’s time to install libraries

- conda install tensorflow
- conda install ujson==1.35
- pip install rasa

## now you can start creating your chatbot.

- rasa init

## for rasa server

- rasa run --enable-api --cors "\*"

## for python3 server

- python -m http.server 8000

## for python2 server

- python -m SimpleHTTPServer 8000
