#### Preprocessing 
- concantenate address, city, state, country 
- lower the string 
- remove the number and permutation   

#### Tokenize 
- Tokening address strings with NLTK tokenizer 

#### Similarity 
- calculate the jaccard similarity of two token lists (only compare two records in same city, state and country)
- Time complexity $O(N^2)$  

#### Filter  
- Filtering the samples whose similarity is larger than threshold  


#### Problems 
- The threshold depends on experience 
- Essentially, it a unsupervised method. Evaluation is based on mannual review. 