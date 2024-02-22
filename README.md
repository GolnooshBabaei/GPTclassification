# GPT Classifications, with Application to Credit Lending

This Github repo is based on the following paper:

Babaei, Golnoosh and Giudici, Paolo, GPT Classifications, with Application to Credit Lending (2024), Machine Learning with Applications. [https://doi.org/10.1016/j.mlwa.2024.100534](https://doi.org/10.1016/j.mlwa.2024.100534).


# Code Settings

In this work, we consider a credit lending problem in this paper. To find the predictions for this problem, we utilized a GPT model which is used via the Openai API. Therefore, considering the data explained in the paper, we predict the status of the unseen observations using a GPT model by sending the requests via the API. 

Through this code, we analyze a simple "GPT" model, an "informed GPT" model and a "Logistic regressor". We use "informed GPT" to refer to the scenario in which we use our considered data in the prompt which is sent to the GPT model to inform the model about our data.

## Openai API 
To run the code, it is needed to use the Openai API. For this purpose, an API key is needed which can be found on the Openai website: [https://openai.com/blog/openai-api](https://openai.com/blog/openai-api). 

## Data
You can use the following link to access the data:
[final_accepted_rejected_df.csv](https://drive.google.com/file/d/1BZob6Uxd0aVyXZd4yR5bsFdh5-mK-Gxr/view?usp=drive_link)


# Contact

If you face any questions or you have suggestions to improve this work, please contact us using the following email address:
Golnoosh.babaei@unipv.it
