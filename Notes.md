## PCA (Principal Component Analysis)
- Unsupervised
- Complex Technique

> Feature extraction technique -> Counters curse of dimenstionality (COD)
> Faster exectution of Algorithms
> Visualiztion (reduces 10D to 3D data)
> Select that column whose spread is higher (Shadow on the axis)


### House price prediction
- `No. of Rooms` and `No. of Washrooms` => `Area/size`
- `No. of Rooms` and `No. od Grocery Shops` => Remove grocery shops feature

PCA finds new set of coordinate axis
![image](https://user-images.githubusercontent.com/86161735/188265634-1aa731ed-fc52-4cd6-95cc-ba479fd21f4b.png)
No of `Principal Components` = No. of Columns <= No of Original features in data (`n`)
### Importance of Variance (vs Mean vs MSD)
- Mod fxn is not diff at 0. MSD is not used therefore.

### End goal is to maximize variance during PCA
### Covariance and Cov Matrix
### Eigen Values and Vectors
> Linear Transformations [Tool](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbWxaNy1TU255M0ZmWGhWN29HcEMycjJZZzV0d3xBQ3Jtc0tsb2JJMFMwNHg3bkFSSl9yY1g5eHRVbkEyc1IyY2Z4dW5nRnhsTHV1cEo5MHB4ZktxRG1uWEdZaE1SSUhFNEVob3ROVzJTSG43dGNRRzM0UTgtY1lmZ2xHdlBSMVFpNTZkTGhOU0Z4bkhiOU9jTWllTQ&q=https%3A%2F%2Fwww.geogebra.org%2Fm%2FYCZa8TAH&v=tXXnxjj2wM4)
> Direction and Magnitude may (or not) change.
- Eigen Vectors -> Direction don't change. (Min 2 in nos.)
- Eigen Values -> Streching Factors (-ve means shrinking)
$A\vec{v}=\lambda\vec{v}$
$\lambda$ is eigen value.

### Eigen Decomposition of Covariance Matrix
### Steps
1. Mean Centering
2. Covariance Matrix
3. Eigen Values/ Vectors `(np.linalg)`

### Plotly for 3D Visualizations

$\frac{\lambda_1}{\lambda_1+\lambda_2+\lambda_3+\lambda_4+\dots}\times 100$

## Linear Regression
