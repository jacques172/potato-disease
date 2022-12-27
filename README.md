# potato-disease detection




![photo](https://user-images.githubusercontent.com/96381612/209697522-1348152c-eddf-44b5-8557-0c7cf1aabcc8.png)




Farmers face economic loss due and crop waste due to various diseases in potato plants.

Built a website that will enable farmers to find out whether a potato plant has a disease or not by uploading a photo to the website.

-Collected the dataset(2152 Images) from kaggle website
- Used the dataset to train the model 50 times with the help of Convolutional Neural Network and Tensorflow with Maxpooling of size 2 and Softmax activation in the output layer
- Achieved an accuracy of 0.974 and a loss value:0.44
- Used MatplotLib for data visualization 
- Used Data augmentation to create more training samples
- Built a website using React Js that calls the model Api using FastAPI as the backend server

other technologies used: NumPy, pillow, uvicorn, TensorFlow-serving-api
