# Gesture Phase Segmentation Using Support Vector Machine (SVM) Classifier
The SVM model gives a representation of data samples in the form of data points in n-dimensional space.  Thus, the samples fall into various categories, separated by a gap that is as large as possible. In addition to performing linear categorization, SVM can also perform nonlinear categorization efficiently and map inputs to high-dimensional data space, each belonging to a specific category. The SVM builds a model during the training process that assigns new instances to one category or another. What the suport vector machine does is the consideration of an area of definite width that distinguishes data sets.

<br/><br/>

<p align="center">
  <img width="450" height="350" src="https://user-images.githubusercontent.com/66460485/130227389-a9f4fece-5a46-4ee8-a6a6-e76265d3a998.jpg">
</p>

SVM algorithms use a set of mathematical functions defined as kernels. Their core task is to take the data as input and convert it into the required form. Different SVM algorithms use different types of kernel functions. These functions can have different types: linear, nonlinear, polynomial, radial basis function (RBF), and sigmoid functions.


## Dataset
The data set contains features extracted from a video of people's gestures, intending to study Gesture Phase Segmentation. These features include speed and acceleration of the hands and wrists and are divided into 32 feature categories and one phase category.

   1. Vectorial velocity of left hand (x coordinate)
   2. Vectorial velocity of left hand (y coordinate)
   3. Vectorial velocity of left hand (z coordinate)
   4. Vectorial velocity of right hand (x coordinate)
   5. Vectorial velocity of right hand (y coordinate)
   6. Vectorial velocity of right hand (z coordinate)
   7. Vectorial velocity of left wrist (x coordinate)
   8. Vectorial velocity of left wrist (y coordinate)
   9. Vectorial velocity of left wrist (z coordinate)
   10. Vectorial velocity of right wrist (x coordinate)
   11. Vectorial velocity of right wrist (y coordinate)
   12. Vectorial velocity of right wrist (z coordinate)
   13. Vectorial acceleration of left hand (x coordinate)
   14. Vectorial acceleration of left hand (y coordinate)
   15. Vectorial acceleration of left hand (z coordinate)
   16. Vectorial acceleration of right hand (x coordinate)
   17. Vectorial acceleration of right hand (y coordinate)
   18. Vectorial acceleration of right hand (z coordinate)
   19. Vectorial acceleration of left wrist (x coordinate)
   20. Vectorial acceleration of left wrist (y coordinate)
   21. Vectorial acceleration of left wrist (z coordinate)
   22. Vectorial acceleration of right wrist (x coordinate)
   23. Vectorial acceleration of right wrist (y coordinate)
   24. Vectorial acceleration of right wrist (z coordinate)
   25. Scalar velocity of left hand
   26. Scalar velocity of right hand
   27. Scalar velocity of left wrist
   28. Scalar velocity of right wrist
   29. Scalar velocity of left hand
   30. Scalar velocity of right hand
   31. Scalar velocity of left wrist
   32. Scalar velocity of right wrist
   33. Gesture Phase:
- D (rest position, from portuguese "descanso")
- P (preparation)
- S (stroke)
- H (hold)
- R (retraction)
