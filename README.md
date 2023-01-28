## Quora Question Pairs

This project aims to quickly find the top k most similar questions to a given input question using fine-tuned BERT model and sentence embeddings similarity. The project is implemented in Google Colab and follows these main steps:

- Fine-tune BERT model on the Quora Question Pairs (qqp) dataset.
- Calculate sentence embeddings using the fine-tuned model.
- Build a data structure for Approximate Nearest Neighbor (ANN) to find top 100 similar embeddings to a given input.
- Compare the top 100 sentence embeddings using the fine-tuned model to find the most similar questions.

The searching engine implemented in this project can find the top k questions from the dataset in less than 1 second.  
### Getting Started

This project is written in Google Colab, so you will need to have a Google account and access to Colab in order to run the code. Once you have access, you can simply open the notebook file in Colab and run the code cells to reproduce the results.  
[Colab link](https://colab.research.google.com/drive/1LIDoZ_mbzad9EHWuh7PRsqbvfKF1Tgxw?usp=sharing)

### Results

As an example, the input question "How can I use R for machine learning?" returns the following similar questions:

    How can Python be used in machine learning?
    What are some computer vision libraries for R?
    How should I go about learning Machine Learning?

### Conclusion

Overall, this project demonstrates the ability of fine-tuned BERT models to solve sentence similarity tasks and the potential for sentence embeddings and ANNs to be used in searching engines for quickly finding similar questions in a large dataset. The combination of sentence embeddings similarity and fine-tuned BERT model allows for accurate and fast results.

