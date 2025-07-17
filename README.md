


# Dx Annotator Annotation Report

## Introduction

This report summarises the progress of the annotation process on our annotation platform, [Dx Annotator](http://uat.dxa.becertain.ai/). You can find the following information in this report:
* Number of annotators.
* Number of annotated/unannotated images.
* Number of annotations.
* Number of annotations each annotator has contributed.
* Efficiency of annotators (number of annotated images/annotations per hour).
* Some statistics about collected annotations (size of bounding boxes, type of annotated objects, percentage of healthy and unhealthy images, etc.).

## Progress

As of the date of the report, there are **8 annotators** who have contributed to the annotation process. These annotators have made **24,308 object-level annotations** and **3,773 image-level annotations** on **800 dental X-rays**.

Total number of uploaded images: 800 (400 Preston, 400 Bricketwood).

**Retirement limit = 5:**

- 400 images from Preston were uploaded to Dx Annotator on 2025-06-03.
- 400 images from Bricketwood were uploaded to Dx Annotator on 2025-06-03.

The following line chart shows the total number of image-level annotations, the total number of object-level annotations, and the total number of annotated images, as of the date of the report:
<h3 style="text-align: center;" markdown="1">Figure 1. History of the total number of image-level annotations, the total number of object-level annotation, and the total number of annotated images. 
  
- "Image-level" means an image annotated by N annotators is counted as N image-level annotations.
- "Object-level" means every bounding box is counted as one object-level annotation.
- The quantity "Total number of annotated images" is the number of non-identical images that has been annotated at least once. </h3>

![](./History/2025_07_15/Figures/img_ann_history.jpg)

The following line chart shows the overall efficiency of annotators in each annotation session, image-level and object-level, along with the number of object-level annotations per image-level annotation:
<h3 style="text-align: center;" markdown="1">Figure 2. History of the overall hourly efficiency (image-level and object-level) of annotators, and the number of object-level annotations per image-level annotation.</h3>

![](./History/2025_07_15/Figures/img_ann_average_efficiency_history.jpg)

The following line chart shows the number of image-level annotations and the number of object-level annotations we collected each day, along with the total working hours of annotators each day:
<h3 style="text-align: center;" markdown="1">Figure 3. History of the number of collected image-level annotations, the number of collected object-level annotations, and working hours of annotators each day.</h3>

![](./History/2025_07_15/Figures/img_ann_number_each_day.jpg)


Click this [link](./History/2025_07_15/list_of_annotated_images.md) for the list of annotated images, along with which images were annotated by how many and which annotators.</summary>

Below is a histogram of the number of annotators per image.

<h3 style="text-align: center;" markdown="1">Figure 4. Histogram of the number of annotators per image.</h3>

![](./History/2025_07_15/Figures/Histogram.jpg)

Statistics below are for the 1325 Belmont images and annotations:

- 0 images were annotated by 0 annotators.

- 0 images were annotated by 1 annotators.

- 0 images were annotated by 2 annotators.

- 37 images were annotated by 3 annotators.

- 153 images were annotated by 4 annotators.

- 610 images were annotated by 5 annotators.

For retirement limit = 5 : we need  0*(5) + 0*(5-1) + 0*(5-2) + 37*(5-3) + 153*(5-4)= **227** image-level annotations to finish this round of annotation.

Click this [link](./History/2025_07_15/list_of_annotators_and_annotations.md) for the list of annotators, along with which annotator has annotated how many and which images, and their working efficiency.

Below is a pie chart showing the number of image-level annotations each annotator has contributed.
<h3 style="text-align: center;" markdown="1">Figure 5. The number and percentage of image-level annotations each annotator has contributed</h3>

![title](./History/2025_07_15/Figures/pie_chart_n_images.jpg)

Below is a pie chart showing the number of object-level annotations each annotator has contributed.
<h3 style="text-align: center;" markdown="1">Figure 6. The number and percentage of object-level annotations each annotator has contributed.</h3>

![title](./History/2025_07_15/Figures/pie_chart_n_annotations.jpg)

The following bar chart compares the efficiency of different annotators, object-level and image-level.
<h3 style="text-align: center;" markdown="1">Figure 7. Comparison of the efficiency of different annotators.</h3>

![title](./History/2025_07_15/Figures/bar_efficiency_images_annotations.jpg)

The image-level efficiency of annotators can be found in the following line chart:
<h3 style="text-align: center;" markdown="1">Figure 8. History of image-level efficiency of different annotators.</h3>

![title](./History/2025_07_15/Figures/Imgs_Efficiency_History.jpg)

The object-level efficiency of annotators can be found in the following line chart:
<h3 style="text-align: center;" markdown="1">Figure 9. History of object-level efficiency of different annotators.</h3>

![title](./History/2025_07_15/Figures/Annotations_Efficiency_History.jpg)

Below is a list of annotation types and the number of annotations we have collected for each annotation type.
<h3 style="text-align: center;" markdown="1">Table 1. List of annotation types and the number of annotations for each type, sorted alphabetically.</h3>

|Annotation type| Abbreviation| Number of annotations of the type|
|:-:|:-:|:-:|
| Bone Loss Stage 1: <15%                            | BL-1       | 5362 |
| Bone Loss Stage 2: Coronal Third                   | BL-2       | 5166 |
| Bone Loss Stage 3: Mid Third                       | BL-3       | 1340 |
| Bone Loss Stage 4: Apical Third                    | BL-4       | 158  |
| Calculus                                           | Cal        | 3600 |
| Dental Caries Grade 1: Outer Enamel                | DC-1       | 494  |
| Dental Caries Grade 2: Inner Enamel                | DC-2       | 571  |
| Dental Caries Grade 3: Outer Dentin                | DC-3       | 1444 |
| Dental Caries Grade 4: Middle Dentin               | DC-4       | 764  |
| Dental Caries Grade 5: Inner Dentin                | DC-5       | 1141 |
| External Resorption                                | ER         | 93   |
| Healthy                                            | Healthy    | 510  |
| Internal Resorption                                | IR         | 4    |
| Missing Coronal Restoration                        | MCR        | 103  |
| Open Margin                                        | OM         | 860  |
| Other                                              | Other      | 499  |
| Overhang                                           | OH         | 775  |
| Periapical Radiolucency                            | PR         | 445  |
| Remaining Root                                     | RR         | 103  |
| Restoration Radiolucency Adhesive/Liner            | RR (A/L)   | 724  |
| Unsure                                             | Unsure     | 152  |

A bar chart showing the number of annotated objects in each annotation type can be found below:
<h3 style="text-align: center;" markdown="1">Figure 10. The number of annotations for each annotation type.</h3>

![title](./History/2025_07_15/Figures/Bar_type_annotation.jpg)

Histograms showing the distribution of the width and height of bounding boxes are as follows: 
<h3 style="text-align: center;" markdown="1">Figure 11. The histogram of the height and width of bounding boxes.</h3>

![title](./History/2025_07_15/Figures/Histogram_bbox.jpg)

Histograms showing the distribution of the width and height of annotated images are as follows: 
<h3 style="text-align: center;" markdown="1">Figure 12. The histogram of the height and width of annotated images.</h3>

![title](./History/2025_07_15/Figures/histogram_image.jpg)

Excel sheets showing the number of annotations and annotated images each annotator has contributed in each hour, and the total working hours in each day can be found in the [link](./History/2025_07_15/Excel_files/).

Below is a list of annotators' object-level precision, recall, and F1 score after the calibration session, computed by using the updated model's annotations as the reference annotations. 

<h3 style="text-align: center;" markdown="1">Table 2. List of annotators' object-level precision, recall, and F1 score computed with the updated model.</h3>

|Annotator| | | | | | |
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|**2025/06/13 - 2025/06/19**|**No. images**| **No. annotations**| **No. model's annotations**| **Precision**| **Recall**| **F1 Score**|
| Rena                  | 221   | 1304 | 1584 | 62.2   | 49.7   | 55.2  |
| Triantafyllio         | 56    | 596  | 403  | 44.8   | 64.0   | 52.7  |
| Woon San              | 185   | 1191 | 1375 | 57.2   | 46.7   | 51.4  |
| Nicholas              | 17    | 109  | 115  | 46.8   | 47.0   | 46.9  |
| Sagar                 | 89    | 495  | 612  | 51.7   | 41.3   | 45.9  |
| Joshua                | 166   | 745  | 1230 | 48.5   | 32.3   | 38.7  |
|**2025/06/20 - 2025/06/26**|**No. images**| **No. annotations**| **No. model's annotations**| **Precision**| **Recall**| **F1 Score**|
| Triantafyllio         | 240   | 1941 | 1485 | 50.2   | 63.8   | 56.2  |
| Deema                 | 249   | 2374 | 1644 | 46.9   | 65.0   | 54.5  |
| Nicholas              | 47    | 337  | 332  | 53.7   | 53.3   | 53.5  |
| Rena                  | 167   | 928  | 1080 | 55.6   | 47.6   | 51.3  |
| Sagar                 | 83    | 565  | 569  | 48.0   | 45.7   | 46.8  |
| Woon San              | 112   | 534  | 802  | 56.0   | 38.7   | 45.7  |
| Joshua                | 101   | 376  | 699  | 43.9   | 26.5   | 33.0  |
|**2025/06/27 - 2025/07/04**|**No. images**| **No. annotations**| **No. model's annotations**| **Precision**| **Recall**| **F1 Score**|
| Triantafyllio         | 124   | 1056 | 774  | 49.1   | 65.1   | 56.0  |
| Rena                  | 194   | 1077 | 1238 | 59.1   | 50.8   | 54.6  |
| Emma                  | 72    | 692  | 556  | 48.7   | 53.2   | 50.9  |
| Deema                 | 133   | 1396 | 829  | 41.4   | 65.4   | 50.7  |
| Nicholas              | 80    | 556  | 589  | 50.2   | 44.8   | 47.3  |
| Woon San              | 162   | 580  | 986  | 52.1   | 35.1   | 41.9  |
| Joshua                | 144   | 411  | 969  | 50.6   | 25.7   | 34.1  |
|**2025/07/05 - 2025/07/11**|**No. images**| **No. annotations**| **No. model's annotations**| **Precision**| **Recall**| **F1 Score**|
| Triantafyllio         | 153   | 1228 | 892  | 44.1   | 61.1   | 51.3  |
| Sagar                 | 109   | 657  | 712  | 53.6   | 48.3   | 50.8  |
| Deema                 | 156   | 1605 | 949  | 40.4   | 65.2   | 49.9  |
| Rena                  | 191   | 915  | 1102 | 55.1   | 45.3   | 49.7  |
| Woon San              | 121   | 479  | 708  | 52.0   | 39.7   | 45.0  |
| Joshua                | 106   | 344  | 623  | 53.5   | 33.7   | 41.4  |
|**2025/07/12 - 2025/07/17**|**No. images**| **No. annotations**| **No. model's annotations**| **Precision**| **Recall**| **F1 Score**|
| Sagar                 | 86    | 533  | 503  | 53.7   | 58.3   | 55.9  |
| Triantafyllio         | 30    | 307  | 220  | 47.6   | 60.5   | 53.2  |
| Deema                 | 40    | 416  | 214  | 37.0   | 67.3   | 47.8  |
| Woon San              | 85    | 390  | 492  | 48.2   | 39.2   | 43.3  |
| Joshua                | 54    | 171  | 318  | 43.3   | 25.2   | 31.8  |

The figures below displays the precision, recall, and F1 scores for each annotator, along with their average and weighted average precision, recall, and F1 score. The average is calculated as the mean of the annotators’ performance metrics, while the weighted average takes into account the number of annotations made by each annotator.
<h3 style="text-align: center;" markdown="1">Figure 13. History of annotators' precision.</h3>

![title](./History/2025_07_15/Figures/Precision.jpg)

<h3 style="text-align: center;" markdown="1">Figure 14. History of annotators' recall</h3>

![title](./History/2025_07_15/Figures/Recall.jpg)

<h3 style="text-align: center;" markdown="1">Figure 15. History of annotators' F1 score.</h3>

![title](./History/2025_07_15/Figures/F1.jpg)

