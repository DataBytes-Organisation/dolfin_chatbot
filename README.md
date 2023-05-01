# DolFin Chatbot Repo

There are 3 important files within the repo:
- chatbot_train.ipynb - creates, trains and saves chatbot model
- chatbot_load.ipynb - loads chatbot model and activates so user can make inputs (this will be the code called by the DolFin website)
- intents.json - contains the desired input and output sentences for the chatbot

# To Run the Code:
1. Use a Python code editor (Google Colab or Jupyter Notebook) and ensure it has access to the location where intents.json is stored.
2. Run all cells in chatbot_train.ipynb.
3. Run all cells in chatbot_load.ipynb.
4. Input desired sentence in final cell of chatbot_load.ipynb.
5. When finished, stop cell running to stop the chatbot.

# To add Code:
1. Clone the repo and make your code changes.
2. Push your code to a new branch of the repo using:
git checkout -b feature_branch_name
git add .
git commit -m “some message about what you have done”
git push -u origin feature_branch_name
3. Create a pull request to merge your branch to master branch

# Code adapted from:
https://www.geeksforgeeks.org/deploy-a-chatbot-using-tensorflow-in-python/

# Things to keep in mind:
The Zen of Python: https://peps.python.org/pep-0020/
