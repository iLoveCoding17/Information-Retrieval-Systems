# Information Retrieval Systems
 
Four Python retrieval systems in one repo: keyword search, image search, semantic search with recommenders, and retrieval-augmented generation (RAG). Each module is a self-contained notebook.

## Note
- If you see the error "Unable to render code block". Please try to open the repo in an incognito/private window.
 
## Modules
 
| Module | What it does | Techniques | Data |
|---|---|---|---|
| [Text Retrieval](text-retrieval.ipynb) | Finds recipes that match a set of query ingredients | Term-document incidence matrix, inverted index (map-reduce and tree-based), Jaccard similarity, TF-IDF with cosine ranking, Whoosh | Food recipes CSV |
| [Image Retrieval](image-retrieval.ipynb) | Finds images similar to a query image | SIFT, VGG16 features, cosine vs. Euclidean similarity, bag of visual words (k-means), Pinecone vector index | CIFAR-10 |
| [Semantic Search and Recommenders](semantic-search-recsys.ipynb) | Searches by meaning and recommends movies | Sentence embeddings with Annoy, OpenCLIP text-to-image search, content-based and baseline recommenders | Food recipes, Flickr8k, MovieLens 100K |
| [RAG](rag.ipynb) | Answers recipe questions from retrieved context | Chunking, FAISS, TinyLlama, query expansion, prompt design, zero-shot classification | Food recipes (first 1,000) |


## Tech stack
 
Python, pandas, NumPy, scikit-learn, NLTK, Whoosh, PyTorch, torchvision, OpenCV, Pinecone, Annoy, sentence-transformers, OpenCLIP, FAISS, LangChain text splitters, Hugging Face Transformers

## Acknowledgements
 
This project was developed with support from the [DAMLR Lab](https://web.cs.dal.ca/~gaw/) and the [Dalhousie Faculty of Computer Science](https://www.dal.ca/faculty/computerscience.html).
 

<img width="221" height="63" alt="image" src="https://github.com/user-attachments/assets/49e20174-59fb-4a9b-8ace-2983ef8d9eae" />

[DAMLR Lab]

<br>
<img width="314" height="161" alt="image" src="https://github.com/user-attachments/assets/87a6f1aa-9955-4e84-9328-cfd0bfa3d3ae" />

[Dalhousie Faculty of Computer Science]

