
Gazebo World:
 ![Screenshot from 2022-06-19 22-28-30](https://user-images.githubusercontent.com/96300383/174492135-2a1680c9-2094-44ef-a809-05040048449e.png)
Input PointCloud:
  ![Screenshot from 2022-06-19 22-28-50](https://user-images.githubusercontent.com/96300383/174492150-2299a638-a202-43e0-9ee5-a546fac3bc85.png)
Output PointCloud after ground plane elimination and clustering:
  ![Screenshot from 2022-06-19 22-28-21](https://user-images.githubusercontent.com/96300383/174492190-d8d404c4-68c3-4bc0-981e-7e921f9a7926.png)
RQT Graph:
  ![Screenshot from 2022-06-19 22-16-27](https://user-images.githubusercontent.com/96300383/174492217-5864c039-770c-4047-89b6-3aa9449f8b21.png)

Input as a sensor_msgs::PointCloud2 message , converted to a pcl::PointCloud2 as an intermediary message , further converted to pcl::PointCloud<pcl::PointXYZRGB> message for PCL computation .
Passthrough filter for Ground Plane Elimination.
KDTree as a search algorithm.
Euclidean Clustering to create clusters.
