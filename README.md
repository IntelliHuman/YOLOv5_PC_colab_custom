# YOLOv5_PC_colab_custom
* YOLOv5 젯슨나노 구동 전 PC colab local enivronment runnig tries
--- 
## Author_Information
- Maker: 김성현(Seong-Hyun Kim / Senior at Dept. of Human-centered Artificial Intelligence)
- Date: 2024.03.18 ~ 2024.03.24.
- Model_used: Yolo v5 tag 10 & Yolo v5 Tag 6.0 / yolov5s.pt, yolov5n.pt
- Environment: Google Colab(python 3.10.8 / **Jetson Nano는 2.7.17이 basic environment이기에 이에 맞춘 code optimization이 필요할 것으로 예상함.**)
### NOTE:
    ## 구축목적: 해당코드는 젯슨나노 구동 전 준비한 custom data의 yolo v5에서의 작동 사전 시험 및 젯슨나노에서의 구동 편리성을 위한 사전 세팅을 목적으로 구축하였음.  
    ## 사용데이터 및 detection object: mask Wearing dataset → https://www.kaggle.com/datasets/andrewmvd/face-mask-detection 
       (class는 효율성과 인식 정확도 상승을 위해 dataset에서 권장한 three-class structure로 하지 않고 *mask, no-mask의 two-class structure로 구성하였음.*/ 마스크 착용-미착용에 대한 detection을 목표로 하였음.)  
    ## Jetson NANO는 기본 environment가 python 2.7.17이기에 해당 환경에 맞춰 yolo v5 tag 6.0 / yolov5n.pt를 사용해야하고, 내부 code 또한 optimization이 필요함.
    
