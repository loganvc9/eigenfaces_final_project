# eigenfaces_final_project
Simple Exploration of Eigenfaces and Image Compression

We started our exploration using SVD Image Compression.

By doing this we gained a basic understanding of how compressing an image 
can be useful and how the amounts of components kept in the compression affects the quality of the image.
We learned that most of the data in an iamge is contained in less than half of the components so you can 
get rid of a lot of the image and still be able to see what is in it.

We continued our exploration by moving onto Eigenfaces.

We were able to use the knowledge we gained doing SVD, and switch over to PCA.
By using PCA on a dataset of faces, we were able to construct an Eigenface which was
the average face of all the dataset containing the most important and relevant facial features.

We then used this to reconstruct another face that hadn't been used to train the Eigenface,
and we re-constructed it using different amounts of components to see accurate the re-construction
could get to the original face.
