# Virtual-TryOn

__A computer vision and deep learning based project that enables the user to try on spectacles, watches and other accessories virtually.Uses MTCNN Model for Face detection and Custom YOLOv5 Object Detection model to detect fingers.__

**Run the .ipynb files in Google Colab to prevent any errors in the code**
**Do Change the image file names in the source code if custom images are used**



## Ring Try On

1. Open RingFitting.ipynb file in Google Colab
2. Upload the best.pt file i.e the weights of the Neural Network employed.
3. Upload ring.png (The png image of the ring to be tried on)
4. Upload a image of hand downwards with fingers pointing downwards
5. Run the .ipynb file and check the results



 * Test Folder has Images of hand that can be used
 * Results Folder has images of hands with ring after being processed through the model
 *   Make Sure the hand and the fingers is straight to obtain good results

## Watch Try On

1. Open Watch_Fitting.ipynb file in Google Colab
2. Upload the best.pt file i.e the weights of the Neural Network employed.
3. Upload watch.png or watch2.png (The png image of the watch to be tried on)
4. Upload a image of hand downwards with fingers pointing downwards and wrist visible
5. Run the .ipynb file and check the results



 * Test Folder has Images of hand that can be used
 
 * Result Folder has images of hands with watch after being processed through the model
 * Make Sure the hand,fingers and the wrist is straight to obtain good results


## Spectacles Try On

1. Open Glasses_TryON.ipynb file in Google Colab
2. Upload glasses.png (The png image of the glasses to be tried on)
3. Upload image of a face 
4. Run the .ipynb file and check the results



 * Test Images Folder has Images of face that can be used
 * Results Folder has images of faces with spectacles after being processed through the model
 


