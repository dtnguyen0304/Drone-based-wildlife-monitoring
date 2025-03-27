# Drone-based-wildlife-monitoring
This repository includes a wildlife dataset captured by drones.

- DAID-T: A Drone-based Animal Image Dataset with annotated Thermal detections

There is one class (animal) of interest. Each training/validation image (.jpg) is associated with a ground-truth annotation file (.txt) formatted using the YOLO's format, e.g., classID centre_x, centre_y width height. Note that centre_x, centre_y, width and height are normalised values. ClassID is always 0.


# Citation
If you use our provided datasets and/or models, please cite our respective works at,

**DAID-T**

    @article{DAID-T,
        author       = {Tan Vuong and 
                      Miao Chang and 
                      Manas Palaparthi and 
                      Lachlan G. Howell and 
                      Alessio Bonti and 
                      Mohamed Abdelrazek and 
                      Duc Thanh Nguyen},      
        title        = {An empirical study of automatic wildlife detection using drone-derived imagery and object detection}, 
        journal      = {Multimedia Tools and Applications},
        year         = {2025} 
    }
