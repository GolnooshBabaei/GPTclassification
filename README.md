# GPT Classifications, with Application to Credit Lending

This Github repo is based on the following paper:

Babaei, Golnoosh and Giudici, Paolo, GPT Classifications, with Application to Credit Lending (November 30, 2023). Available at SSRN: 
[https://ssrn.com/abstract=4649285](https://ssrn.com/abstract=4649285) or 
[http://dx.doi.org/10.2139/ssrn.4649285](http://dx.doi.org/10.2139/ssrn.4649285)


# Code Settings

To run the code, it is needed to use the Openai API. For this purpose, an API key is needed which can be found on the Openai website: [https://openai.com/blog/openai-api](https://openai.com/blog/openai-api). 

In particular, we consider a credit lending problem in this paper. To find the predictions for this problem, we utilized a GPT model which is used via the Openai API. Therefore, considering the data explained in the paper, we predict the status of the unseen observations using a GPT model by sending the requests via the API. 

Through this code, we analyze a simple "GPT" model, an "informed GPT" model and a "Logistic regressor". We use "informed GPT" to refer to the scenario in which we use our considered data in the prompt which is sent to the GPT model to inform the model about our data.

# Contact

If you face any questions or you have suggestions to improve this work, please contact us using the following email address:
Golnoosh.babaei@unipv.it
