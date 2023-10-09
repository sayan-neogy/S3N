## Contents

- [Evaluation Metrics](#evaluation-metrics)
  - [Classification](#classification)
  - [Detection](#detection)
- [Sample Images and Interpretability Plots](#sample-images-and-interpretability-plots)
  - [Validation Dataset](#validation-dataset)
    - [Classification and Detection Images (Top 10)](#classification-and-detection-images-top-10)
    - [Interpretability Plots (Top 10)](#interpretability-plots-top-10)
  - [Testing Dataset 1](#testing-dataset-1)
    - [Classification and Detection Images (Top 5)](#classification-and-detection-images-top-5)
    - [Interpretability Plots (Top 5)](#interpretability-plots-top-5)
  - [Testing Dataset 2](#testing-dataset-2)
    - [Classification and Detection Images (Top 5)](#classification-and-detection-images-top-5)
    - [Interpretability Plots (Top 5)](#interpretability-plots-top-5)


## Evaluation Metrics

### Classification:

| Metric    | Value           |
|-----------|-----------------|
| Accuracy  | 0.9959          |
| Precision | 0.9959          |
| Recall    | 0.9959          |
| F1-Score  | 0.9959          |

### Detection:

| Metric                        | Value                                   |
|-------------------------------|-----------------------------------------|
| Average Precision (AP50)      | 0.7464 (Bleeding), 1.0000 (Non Bleeding) |
| Average Precision (AP75)      | 0.6021 (Bleeding), 1.0000 (Non Bleeding) |
| Mean Average Precision (mAP)  | mAP_50: 0.8732, mAP_75: 0.8010          |
| Intersection over Union (IoU): |                           |
| IoU Results for Threshold 0.5  |                           |
| Overall IoU for Bleeding class | 0.8588652482269504                    |
| Overall IoU for Non-Bleeding class | 1.0                                   |
| IoU Results for Threshold 0.75 |                           |
| Overall IoU for Bleeding class | 0.773758865248227                     |
| Overall IoU for Non-Bleeding class | 1.0                                   |


## Sample Images and Interpretability Plots

### Validation Dataset:

#### Classification and Detection Images (Top 10):

1.  <img src="images/validation_set/img-1085-_png.jpg" raw=true alt="img-1085" style="margin-right: 10px;" />
2.  <img src="images/validation_set/img-1262-_png.jpg" raw=true alt="img-1262" style="margin-right: 10px;" />
3.  <img src="images/validation_set/img-238-_png.jpg" raw=true alt="img-238" style="margin-right: 10px;" />
4.  <img src="images/validation_set/img-254-_png.jpg" raw=true alt="img-254" style="margin-right: 10px;" />
5.  <img src="images/validation_set/img-301-_png.jpg" raw=true alt="img-301" style="margin-right: 10px;" />
6.  <img src="images/validation_set/img-450-_png.jpg" raw=true alt="img-450" style="margin-right: 10px;" />
7.  <img src="images/validation_set/img-466-_png.jpg" raw=true alt="img-466" style="margin-right: 10px;" />
8.  <img src="images/validation_set/img-553-_png.jpg" raw=true alt="img-553" style="margin-right: 10px;" />
9.  <img src="images/validation_set/img-765-_png.jpg" raw=true alt="img-765" style="margin-right: 10px;" />
10.  <img src="images/validation_set/img-860-_png.jpg" raw=true alt="img-860" style="margin-right: 10px;" />


#### Interpretability Plots (Top 10):

1.  <img src="interpretability_plot_eigen_cam/validation_set/img-1085-_png.jpg" raw=true alt="img-1085" style="margin-right: 10px;" />
2.  <img src="interpretability_plot_eigen_cam/validation_set/img-1262-_png.jpg" raw=true alt="img-1262" style="margin-right: 10px;" />
3.  <img src="interpretability_plot_eigen_cam/validation_set/img-238-_png.jpg" raw=true alt="img-238" style="margin-right: 10px;" />
4.  <img src="interpretability_plot_eigen_cam/validation_set/img-254-_png.jpg" raw=true alt="img-254" style="margin-right: 10px;" />
5.  <img src="interpretability_plot_eigen_cam/validation_set/img-301-_png.jpg" raw=true alt="img-301" style="margin-right: 10px;" />
6.  <img src="interpretability_plot_eigen_cam/validation_set/img-450-_png.jpg" raw=true alt="img-450" style="margin-right: 10px;" />
7.  <img src="interpretability_plot_eigen_cam/validation_set/img-466-_png.jpg" raw=true alt="img-466" style="margin-right: 10px;" />
8.  <img src="interpretability_plot_eigen_cam/validation_set/img-553-_png.jpg" raw=true alt="img-553" style="margin-right: 10px;" />
9.  <img src="interpretability_plot_eigen_cam/validation_set/img-765-_png.jpg" raw=true alt="img-765" style="margin-right: 10px;" />
10.  <img src="interpretability_plot_eigen_cam/validation_set/img-860-_png.jpg" raw=true alt="img-860" style="margin-right: 10px;" />


### Testing Dataset 1:

#### Classification and Detection Images (Top 5):

1.  <img src="images/test_dataset_1/A0000_png.jpg" raw=true alt="A0000" style="margin-right: 10px;" />
2.  <img src="images/test_dataset_1/A0003_png.jpg" raw=true alt="A0003" style="margin-right: 10px;" />
3.  <img src="images/test_dataset_1/A0046_png.jpg" raw=true alt="A0046" style="margin-right: 10px;" />
4.  <img src="images/test_dataset_1/A0047_png.jpg" raw=true alt="A0047" style="margin-right: 10px;" />
5.  <img src="images/test_dataset_1/A0049_png.jpg" raw=true alt="A0049" style="margin-right: 10px;" />


#### Interpretability Plots (Top 5):

1.  <img src="interpretability_plot_eigen_cam/test_dataset_1/A0000_png.jpg" raw=true alt="A0000" style="margin-right: 10px;" />
2.  <img src="interpretability_plot_eigen_cam/test_dataset_1/A0003_png.jpg" raw=true alt="A0003" style="margin-right: 10px;" />
3.  <img src="interpretability_plot_eigen_cam/test_dataset_1/A0046_png.jpg" raw=true alt="A0046" style="margin-right: 10px;" />
4.  <img src="interpretability_plot_eigen_cam/test_dataset_1/A0047_png.jpg" raw=true alt="A0047" style="margin-right: 10px;" />
5.  <img src="interpretability_plot_eigen_cam/test_dataset_1/A0049_png.jpg" raw=true alt="A0049" style="margin-right: 10px;" />


### Testing Dataset 2:

#### Classification and Detection Images (Top 5):

1.  <img src="/images/test_dataset_2/A0508_png.jpg" raw=true alt="A0508" style="margin-right: 10px;" />
2.  <img src="/images/test_dataset_2/A0062_png.jpg" raw=true alt="A0062" style="margin-right: 10px;" />
3.  <img src="/images/test_dataset_2/A0472_png.jpg" raw=true alt="A0472" style="margin-right: 10px;" />
4.  <img src="/images/test_dataset_2/A0470_png.jpg" raw=true alt="A0470" style="margin-right: 10px;" />
5.  <img src="/images/test_dataset_2/A0469_png.jpg" raw=true alt="A0469" style="margin-right: 10px;" />


#### Interpretability Plots (Top 5):

1.  <img src="/interpretability_plot_eigen_cam/test_dataset_2/A0469_png.jpg" raw=true alt="A0469" style="margin-right: 10px;" />
2.  <img src="/interpretability_plot_eigen_cam/test_dataset_2/A0470_png.jpg" raw=true alt="A0470" style="margin-right: 10px;" />
3.  <img src="/interpretability_plot_eigen_cam/test_dataset_2/A0472_png.jpg" raw=true alt="A0472" style="margin-right: 10px;" />
4.  <img src="/interpretability_plot_eigen_cam/test_dataset_2/A0508_png.jpg" raw=true alt="A0508" style="margin-right: 10px;" />
5.  <img src="/interpretability_plot_eigen_cam/test_dataset_2/A0062_png.jpg" raw=true alt="A0062" style="margin-right: 10px;" />



