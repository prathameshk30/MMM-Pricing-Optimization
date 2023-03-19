# Text-Similarity-NLU
### Techstack used:-
### Git, PyTorch, Scikit-learn, Docker, AWS Sagemaker 
<image src="https://user-images.githubusercontent.com/89546195/225781842-22fb4c61-dfe6-46d8-b5b8-6b00dedee6e3.png" width=15% height=15%><image src="https://user-images.githubusercontent.com/89546195/225764006-ce83be94-53a6-4312-83a5-ff67b98788cf.png" width=20% height=20%> <image src="https://user-images.githubusercontent.com/89546195/225781255-f5ec1e01-a055-4297-ad1c-0b0df5ad16b0.png" width=20% height=20%> <image src="https://user-images.githubusercontent.com/89546195/225764601-6166b326-c5a1-4da1-8048-35586b9493bd.png" width=20% height=20%> <image src="https://user-images.githubusercontent.com/89546195/225781413-acd30481-de8f-4f73-84d7-dea8d7a4edb8.png" width=20% height=20%>


### This Github repository is managed using version control:-
 <image src="https://user-images.githubusercontent.com/89546195/225790576-59df3439-dee3-44ff-ad7a-bbb8d159a5c9.png" width=20% height=20%> 

### Description:-
Training-the-model
This project will help to understand the basics of NLP. The main goal of  this project is to understand the different methods used in measuring the similarity of a given text data. 
The need to compute teh similarity between texts arises due to:-
1) Search Engines:- need to model the relevance of a document to a query, beyond the overlap in words between the two. For instance, question-and-answer sites such as Quora or Stackoverflow need to determine whether a question has already been asked before.
2) In legal matters, text similarity task allow to mitigate risks on a new contract, based on the assumption that if a new contract is similar to a existent one that has been proved to be resilient, the risk of this new contract being the cause of financial loss is minimised. Here is the principle of Case Law principle. Automatic linking of related documents ensures that identical situations are treated similarly in every case. Text similarity foster fairness and equality. Precedence retrieval of legal documents is an information retrieval task to retrieve prior case documents that are related to a given case document.

### Context:-
In this competition, you will train your models on a novel semantic similarity dataset to extract relevant information by matching key phrases in patent documents. Determining the semantic similarity between phrases is critically important during the patent search and examination process to determine if an invention has been described before. For example, if one invention claims "television set" and a prior publication describes "TV set", a model would ideally recognize these are the same and assist a patent attorney or examiner in retrieving relevant documents. This extends beyond paraphrase identification; if one invention claims a "strong material" and another uses "steel", that may also be a match. What counts as a "strong material" varies per domain (it may be steel in one domain and ripstop fabric in another, but you wouldn't want your parachute made of steel). We have included the Cooperative Patent Classification as the technical domain context as an additional feature to help you disambiguate these situations.

Can you build a model to match phrases in order to extract contextual information, thereby helping the patent community connect the dots between millions of patent documents?

