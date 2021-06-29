federated-ml-health

This colab implements side-by-side comparison of models and their interpretations trained in a centralized machine learning (a.k.a. classical) way vs. the federated (distributed) way. Specifically, we concentrate on binary inference problems and evaluate several approaches: 

1.   regression models trained in a traditional way using various optimizers on centralized datasets
2.   equivalent models expressed in tensorflow and trained using available optimizers therein
3.   equivalent models trained in tensorflow_federated where each device keeps its data local and private
4.   all of the above with differential privacy added

This is not an officially supported Google product.
