# fruit-detection
fruit detection mainly based on faster rcnn model in pytorch


## some results
Original outputs             |  Outputs with group label
:-------------------------: |:-------------------------:
![image](https://github.com/kkalee/fruit-detection/blob/master/fruit-detection/visual_result_nogroup/999_j0736o1l93c_121.jpg)  |  ![image](https://github.com/kkalee/fruit-detection/blob/master/visual_result/999_j0736o1l93c_121.jpg)
![image](https://github.com/kkalee/fruit-detection/blob/master/fruit-detection/visual_result_nogroup/979_e0525se6v85_099.jpg)  |  ![image](https://github.com/kkalee/fruit-detection/blob/master/visual_result/979_e0525se6v85_099.jpg)
![image](https://github.com/kkalee/fruit-detection/blob/master/fruit-detection/visual_result_nogroup/996_l0772ncxq2l_073.jpg)  |  ![image](https://github.com/kkalee/fruit-detection/blob/master/visual_result/996_l0772ncxq2l_073.jpg)
![image](https://github.com/kkalee/fruit-detection/blob/master/fruit-detection/visual_result_nogroup/997_r0506w1hu1y_038.jpg)  |  ![image](https://github.com/kkalee/fruit-detection/blob/master/visual_result/997_r0506w1hu1y_038.jpg)
![image](https://github.com/kkalee/fruit-detection/blob/master/fruit-detection/visual_result_nogroup/999_g0724jp5pu3_005.jpg)  |  ![image](https://github.com/kkalee/fruit-detection/blob/master/visual_result/999_g0724jp5pu3_005.jpg)


## model
The faster rcnn uses a resnet50 backbone.You can change the depth of the resnet model. Depth must be one of 18, 34, 50, 101 or 152. Note that deeper models are more accurate but are slower and use more memory.
