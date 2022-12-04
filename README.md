# An Unsupervised Learning Approach for Categorising Research Proposals and Recommending Papers

Research writing can be technical and difficult to understand. Manual assignments of research areas and related faculties can be timeconsuming and error-prone. Therefore, the first goal of this project is to build an unsupervised model to classify an unseen project proposal. We explored unsupervised learning methods such as K-means and topic models as well as a combination of Latent Dirichlet Annotation (LDA) and Bidirectional Encoder Representations from Transformers (BERT) and K-means to cluster project proposals into different categories. The second goal is to recommend papers for particular project proposals based on other similar publications. We can assume that the authors of the closest papers can be suitable supervisors for the research project. After investigating different features that can be used as numerical vector representation of documents and apply cosine similarity method to f ind matching pairs of paper and proposal, the features outputted by TF-IDF show the most accurate results.

<img src="https://user-images.githubusercontent.com/60076593/205468802-332bd72a-f16d-417a-8011-a88b2f05c0ca.png" width="400" height="300" />
<span>Fig 1: Proposed approach for clustering project</span>

<img src="https://user-images.githubusercontent.com/60076593/205469109-1b46fb69-fce2-4337-a5a0-a6ed6c60fa58.png" width="400" height="300" />
<span>Fig 2: Categories visualization</span>

<hr>

<img src="https://user-images.githubusercontent.com/60076593/205469372-783c3404-e078-499b-973c-411d83644a9f.jpg" width="500" height="300" />
<span>Fig 3: Examples of recommended papers based on the content of project and paper abstracts</span>
