# ML from scratch

Classic machine learning algorithms implemented from first principles in Python, without scikit-learn models. Written as coursework for the machine learning course in my MS at UMass Amherst.

| Folder | Algorithm | Script | Dataset |
| --- | --- | --- | --- |
| `knn/` | k-nearest neighbours with Euclidean distance, accuracy plotted against k | `KNN.py` | Iris |
| `decision_tree/` | Decision tree classifier | `DecisiontreeAlgo.py` | 1984 House votes |
| `random_forest/` | Random forest built on a decision tree, evaluated with k-fold cross-validation | `RandomForest_housevotes.py`, `RandomForest_wine.py` | 1984 House votes, Wine |
| `naive_bayes/` | Naive Bayes classifier with evaluation metrics | `naivebayes.py` | Not included in this repo |
| `neural_network/` | Feed-forward neural network trained with backpropagation | `NeuralNetworkCancer.py`, `NeuralNetworkVotes.py`, `NeuralNetworkWine.py` | Breast cancer, 1984 House votes, Wine |

## Run

Each script reads its CSV from the current directory, so run it from inside its folder:

```sh
pip install numpy pandas matplotlib

cd knn && python3 KNN.py
cd ../random_forest && python3 RandomForest_wine.py
cd ../neural_network && python3 NeuralNetworkCancer.py
```

## History

These were previously five separate repositories (KNN, DecisionTree, RandomForest, NaiveBayes, NeuralNetwork), now archived.
