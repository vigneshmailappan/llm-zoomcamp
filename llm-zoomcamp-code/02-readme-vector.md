
Vectors: 

d.shape v1.shape v2.shape : all giving 384. because of the model we have choosen. it has ability to explain things in 384 different way. 

vector vs martix : need for speed

    Encoded resluts vector in a generic py list where as matrix is numpy array. numpy array stores elements continiously in mem but py list stores random place in mem. We convert to numpy array for speed.


Flow :
vector search with numpy
    sentence transformer 
        -> model 
            -> encode ( vectorization ) 
                -> dot product ( compare )

matrix :
    argmax
    argsort
