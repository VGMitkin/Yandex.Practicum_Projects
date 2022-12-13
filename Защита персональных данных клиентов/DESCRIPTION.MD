## Project. Protection of personal data of clients of the insurance company
### Description of the project
It is necessary to protect the data of clients of the insurance company "Though the Flood". Develop a data transformation method to make it difficult to recover personal information from them. Justify the correctness of his work.

You need to protect the data so that the quality of the machine learning models does not deteriorate during the transformation.


### Content of the project
1. Exploring general information about the data
2. Answer the question
    The features are multiplied by an invertible matrix. Will the quality of linear regression change? (It can be retrained.)
         - Will change. Give examples of matrices.
         - Will not change. Specify how the linear regression parameters are related in the original problem and in the transformed one.
3. Suggest a data transformation algorithm for solving the problem. Justify why the quality of linear regression will not change.
4. Program this algorithm by applying matrix operations. Check that the quality of the linear regression from sklearn is not different before and after the transformation. Apply metric R2.

### Libraries used in the project:
- pandas
- Numpy
- matplotlib
- Seaborn
- SKlearn
