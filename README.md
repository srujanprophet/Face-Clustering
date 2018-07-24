# Face-Clustering

Face Clustering is an example of Unsupervised Learning.  
Given a flurry of faces, this clusters them.  

1. Create a virtual environment
2. Activate and install dependencies using : ``` pip install -r requirements.txt ```
3. Encode the dataset using : ``` python encode_faces.py --dataset dataset --encodings encodings.pickle ```
4. Perform the Clustering : ``` python cluster_faces.py --encodings encodings.pickle ```


For reference : https://www.pyimagesearch.com/2018/07/09/face-clustering-with-python/
