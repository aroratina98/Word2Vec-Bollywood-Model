# Word2Vec-Bollywood-Pretrained-Model

In the word analogy task, we complete the sentence "a is to b as c is to __".

An example is 'MAN is to WOMAN as KING is to QUEEN' . In detail, we are trying to find a word d, such that the associated word vectors ea,eb,ec,ed are related in the following manner: eb−ea≈ed−ec. We will measure the similarity between eb−ea and ed−ec using cosine similarity.

Examples-

man -> woman ::     prince -> princess    ,    italy -> italian ::     spain -> spanish                             
india -> delhi ::     japan -> tokyo    ,    
man -> woman ::     boy -> girl ,                                            
small -> smaller ::     large -> larger 

Here we are training our own Word2Vec model. We picked some Bollywood news from Google as "bollywood_news.txt". 
We have our word vectors in "bollywood.bin". 

Now we find some interesting relations such as: 

If RANVEER is to DEEPIKA, then NICK is to _____________ , and our model will predict the suitable result.
