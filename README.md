# Buckeyes-Football-Face-Recognition-Web-App
This model classifies and recognizes sports personalities using OpenCV library and SVM algorithm after Wavelet transformation.

In this data science and machine learning project, we classify sports personalities. We restrict classification to only 20 people. In this model firstly we collected images of the athletes from the internet and then cropped all the face detected in images using OpenCV. Then we Wavelets transformed the images to extract the key feature of the faces. Then we created a training set to train the data. We tried many algorithms but chose SVM as it was giving the best results. Then we created a flask application as a backend to handle the input and return output.

### Football Players
1. Deontae Armstrong
2. Devontae Armstrong
3. Mylan Graham
4. Eddrick Houston
5. Dominic Kirks
6. Max LeBlanc
7. Miles Lockhart
8. Jaylen McClain
9. Eric Mensah
10. Ian Moore
11. Air Noland
12. James Peoples
13. Payton Pierce
14. Leroy Roker
15. Aaron Scott
16. Chip Trayanum
17. Marvin Harrison Jr.
18. Kyle McCord
19. Carson Hinzman
20. TreVeyon Henderson

### Technologies utilized
- Python
- Numpy and OpenCV for cleaning
- Seaborn for visualization
- sklearn for model building
- Jupyter notebooks, Visual Code Studio, Pycharm as IDE
- Python Flask for HTTP Server
- HTML, CSS, JS for UI

### Deployment
This Model is deployed on Heroku Server
