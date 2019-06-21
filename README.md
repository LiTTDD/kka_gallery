# fruit-detection
fruit detection mainly based on faster rcnn model in pytorch


## some results
Original outputs             |  Outputs with group label
:-------------------------: |:-------------------------:
![image](https://github.com/kkalee/fruit-detection/blob/master/fruit-detection/visual_result_nogroup/999_j0736o1l93c_121.jpg)  |  ![image](https://github.com/kkalee/fruit-detection/blob/master/fruit-detection/visual_result/999_j0736o1l93c_121.jpg)
![image](https://github.com/kkalee/fruit-detection/blob/master/fruit-detection/visual_result_nogroup/979_e0525se6v85_099.jpg)  |  ![image](https://github.com/kkalee/fruit-detection/blob/master/fruit-detection/visual_result/979_e0525se6v85_099.jpg)
![image](https://github.com/kkalee/fruit-detection/blob/master/fruit-detection/visual_result_nogroup/996_l0772ncxq2l_073.jpg)  |  ![image](https://github.com/kkalee/fruit-detection/blob/master/fruit-detection/visual_result/996_l0772ncxq2l_073.jpg)
![image](https://github.com/kkalee/fruit-detection/blob/master/fruit-detection/visual_result_nogroup/997_r0506w1hu1y_038.jpg)  |  ![image](https://github.com/kkalee/fruit-detection/blob/master/fruit-detection/visual_result/997_r0506w1hu1y_038.jpg)
![image](https://github.com/kkalee/fruit-detection/blob/master/fruit-detection/visual_result_nogroup/999_g0724jp5pu3_005.jpg)  |  ![image](https://github.com/kkalee/fruit-detection/blob/master/fruit-detection/visual_result/999_g0724jp5pu3_005.jpg)


## model
The faster rcnn uses a resnet50 backbone.You can change the depth of the resnet model. Depth must be one of 18, 34, 50, 101 or 152. Note that deeper models are more accurate but are slower and use more memory.

# image-outpainting
edge guided image outpainting


## some results
origin input     | cropped_input        |  edge_input |  result_without_edge | result_with_edge
:-------------------------: |:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:
![image](https://github.com/kkalee/fruit-detection/blob/master/image-outpainting/input/input1.png)  |  ![image](https://github.com/kkalee/fruit-detection/blob/master/image-outpainting/crop_input/input1.png) |  ![image](https://github.com/kkalee/fruit-detection/blob/master/image-outpainting/edge/edge1.png)|  ![image](https://github.com/kkalee/fruit-detection/blob/master/image-outpainting/gen_noedge/test1.png)|  ![image](https://github.com/kkalee/fruit-detection/blob/master/image-outpainting/gen_edge/test1.png)
![image](https://github.com/kkalee/fruit-detection/blob/master/image-outpainting/input/input2.png)  |  ![image](https://github.com/kkalee/fruit-detection/blob/master/image-outpainting/crop_input/input2.png) |  ![image](https://github.com/kkalee/fruit-detection/blob/master/image-outpainting/edge/edge2.png)|  ![image](https://github.com/kkalee/fruit-detection/blob/master/image-outpainting/gen_noedge/test2.png)|  ![image](https://github.com/kkalee/fruit-detection/blob/master/image-outpainting/gen_edge/test2.png)
![image](https://github.com/kkalee/fruit-detection/blob/master/image-outpainting/input/input3.png)  |  ![image](https://github.com/kkalee/fruit-detection/blob/master/image-outpainting/crop_input/input3.png) |  ![image](https://github.com/kkalee/fruit-detection/blob/master/image-outpainting/edge/edge3.png)|  ![image](https://github.com/kkalee/fruit-detection/blob/master/image-outpainting/gen_noedge/test3.png)|  ![image](https://github.com/kkalee/fruit-detection/blob/master/image-outpainting/gen_edge/test3.png)
![image](https://github.com/kkalee/fruit-detection/blob/master/image-outpainting/input/input4.png)  |  ![image](https://github.com/kkalee/fruit-detection/blob/master/image-outpainting/crop_input/input4.png) |  ![image](https://github.com/kkalee/fruit-detection/blob/master/image-outpainting/edge/edge4.png)|  ![image](https://github.com/kkalee/fruit-detection/blob/master/image-outpainting/gen_noedge/test4.png)|  ![image](https://github.com/kkalee/fruit-detection/blob/master/image-outpainting/gen_edge/test4.png)
![image](https://github.com/kkalee/fruit-detection/blob/master/image-outpainting/input/input5.png)  |  ![image](https://github.com/kkalee/fruit-detection/blob/master/image-outpainting/crop_input/input5.png) |  ![image](https://github.com/kkalee/fruit-detection/blob/master/image-outpainting/edge/edge5.png)|  ![image](https://github.com/kkalee/fruit-detection/blob/master/image-outpainting/gen_noedge/test5.png)|  ![image](https://github.com/kkalee/fruit-detection/blob/master/image-outpainting/gen_edge/test5.png)
![image](https://github.com/kkalee/fruit-detection/blob/master/image-outpainting/input/input6.png)  |  ![image](https://github.com/kkalee/fruit-detection/blob/master/image-outpainting/crop_input/input6.png) |  ![image](https://github.com/kkalee/fruit-detection/blob/master/image-outpainting/edge/edge6.png)|  ![image](https://github.com/kkalee/fruit-detection/blob/master/image-outpainting/gen_noedge/test6.png)|  ![image](https://github.com/kkalee/fruit-detection/blob/master/image-outpainting/gen_edge/test6.png)


# image-captioning

## some results
input             |  output
:-------------------------: |:-------------------------:
![image](https://github.com/kkalee/fruit-detection/blob/master/image-captioning/input/123.png)  |  a giraffe standing next to a tree in a field
![image](https://github.com/kkalee/fruit-detection/blob/master/image-captioning/input/1234.png) |  a bunch of food is on a table
![image](https://github.com/kkalee/fruit-detection/blob/master/image-captioning/input/12345.png)|  a table with a vase of flowers on the table 