# Augmentation-Depth2PointCloud

## Bounding Box Augmentation 
![image](https://user-images.githubusercontent.com/50072640/177681418-095e2c99-4eaf-492f-9f1a-70417f5f43c1.png)

### original image
![image](https://user-images.githubusercontent.com/50072640/177681653-b95d45c0-facc-4355-bc10-53cef67dc377.png)
### augmented image
![image](https://user-images.githubusercontent.com/50072640/177681668-52b775c0-3c14-420c-88f0-a05c8b2d443e.png)

## Depth to Point Cloud
Given depth value d at (u, v) image coordinate, the corresponding 3d point is:
```
Z = d / depth_scale
X = (u - cx) * Z / fx
Y = (v - cy) * Z / fy
```

![image](https://user-images.githubusercontent.com/50072640/177681861-ee07ae34-945e-46a1-851d-c510bb004c01.png)
![image](https://user-images.githubusercontent.com/50072640/177682097-d16c0e40-fe3a-4273-add7-aeb398be69cf.png)
