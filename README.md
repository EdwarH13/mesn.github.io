#Ruby-Based Clustering of Pre-trained Language Model (PLM) for Low-Resource Programming Languages
This project explores using Ruby, a low-resource programming language, for text clustering using pre-trained language models (PLMs) like BERT.#

Technologies Used
Ruby: The primary programming language used for this project.
BERT (Bidirectional Encoder Representations from Transformers): A pre-trained language model used for generating sentence embeddings.
KMeans Clusterer: Ruby library used to cluster sentences based on their embeddings.
Tokenizer: Ruby library used for tokenizing sentences into words.
FileUtils: Ruby module used for handling file operations.
Installation
Follow these steps to set up and run the project:

Clone the Repository:

bash
Copy code
git clone https://github.com/yourusername/ruby-plm-clustering.git
cd ruby-plm-clustering
Install Required Gems: Ensure you have Ruby installed, and then install the required gems by running:

bash
Copy code
gem install tokenizer bert kmeans-clusterer fileutils
Prepare Necessary Files:

Create a stopwords.txt file containing common stopwords (one per line).
Place the input text file named nfr (1).txt containing the sentences to be clustered in the project directory.
Usage
Run the script to perform text clustering using the command below:

bash
Copy code
ruby main.rb
This command will read the input text file, preprocess the text, generate sentence embeddings using BERT, cluster the sentences, and save the results into the requirements_clustersInRuby directory.

Features
Text Preprocessing: The script splits input text into sentences, tokenizes them, removes stopwords, and filters non-alphabetic words.
Sentence Embedding: Uses the BERT model to generate numerical embedding vectors for each sentence.
Clustering: Performs K-means clustering on the sentence embeddings to group similar sentences together.
Cluster Output: Saves clustered sentences and a representative example sentence from each cluster into separate text files.
References
For additional context and information on the project's background and presentation, please refer to the following document:

Project Presentation and Background
