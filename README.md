# Graph Spectral Clustering Repository

## Learning Objective

Our goal is to help students understand the graph spectral clustering algorithm, including the motivation behind the clustering technique and its strengths and weaknesses when compared to other clustering methods taught during the same instructional week, such as k-means clustering. Students should be able to implement graph spectral clustering given a dataset, and understand what scenarios would be graph spectral clustering be used, as opposed to another clustering method.

The lecture notes and presentation emphasize the motivation of graph spectral clustering. Both resources provide a review on prerequisite topics including graphs and k-means. Then, the notes/presentation explain the clustering algorithm, walking through a simple, concrete example. Given the fact that EECS16ML is a 2-unit, introductory class with an emphasis on coding, we will not expect students to need to understand all the mathematical justifications behind the algorithm (e.g. the math behind why k-means is performed on the rows of the eigenvector matrix).

In the coding assignment, students will need to implement a large portion of the graph spectral clustering themselves, including functions that generate the Laplacian matrix, populate the matrix using the RBF kernel and other similarity metrics, and perform k-means clustering on the eigenvector matrix. We have organized the notebook to accomplish the objective of having students work with two datasets (Gaussian mixture and `two_moons` from `sklearn`), write spectral clustering code, create visualizations of the clustering results, and analyze their results. By structuring the notebook in this format, students will be able to recognize what cases are suitable for graph spectral clustering, which will be useful when they encounter similar datasets in the real world. Although students will most likely use built-in graph spectral clustering functions, having them implement the functions in this assignment will reinforce their understanding of what the clustering is actually doing. Finally, exploring the clustering result through visualizations and analyses resembles work that will need to be done in a real world scenario, and allows students to experience the outcomes of this specific clustering technique.

The purpose of the quiz is to evaluate students' understanding of the algorithm implementation details, with a focus on making sure students will be able to implement graph spectral clustering on their own should the situation arise. The mix of true/false, multiple choice, and short answer questions will re-emphasize the content taught in the notes/presentation. Good performance on this quiz will show a strong mastery of this material, and the objectives mentioned in our Assignment Learning Objectives document under `assignment`.

## Navigation

`assignment` contains the Jupyter notebook coding assignment for the students to complete, along with a working solution file. There is also a corresponding PDF explaining the learning objectives being accomplished by each section in the assignment.

`notes` contains the lecture notes and lecture slides, which would be used to accompany the lectures for that week.

`quiz` contains the PDF with the quiz questions, as well as a detailed solutions PDF. 
