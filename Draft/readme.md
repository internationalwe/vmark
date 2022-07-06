<img width="678" alt="(Input Data)" src="https://user-images.githubusercontent.com/92769643/177542430-36029be6-237a-4d4b-afef-cc3bf5e7d212.png">


![image](https://user-images.githubusercontent.com/92702297/177488949-c41268c9-cc16-4da9-9310-59baef6002a4.png)



# 산꾼도시여자들_s.csv
![image](https://user-images.githubusercontent.com/92702297/177489024-97c3f1da-e23b-4930-b6b8-d5409be7552c.png)


# 산꾼도시여자들_i.csv
![image](https://user-images.githubusercontent.com/92702297/177489102-d2a12c27-4684-496e-baac-16af72a5a85e.png)
- 위에는 위치데이터 |를 식별자로 썼습니다, 근데 사용은 안하는 중입니다.

![image](https://user-images.githubusercontent.com/92702297/177489166-c72f414c-59ae-42d5-a00f-5bd1fd1288aa.png)
- 영상 프레임 분할은 0.1초 단위
- 만약에 30이면 3프레임당 1번씩만 검색
    - 0.1 [사람0, 사람1, 사람2, 자동차1]
    - 0.2 [사람0, 사람1, 사람2, 자동차1, 자동차2]
    - 0.3 [사람0, 사람1, 사람2, 자동차1, 자동차2]
    - 0.4 [사람0, 사람1, 자동차1] 
    - ------------------------->
    - 0.4초에 사람2랑 자동차2가 없어졌으니까
    - 0.1 0.3 사람2
    - 0.2 0.3 자동차2 
    - 기록


## 욜로는 Pretrained 된 클래스는 다 아시겠지만 
- names: ['person', 'bicycle', 'car', 'motorcycle', 'airplane', 'bus', 'train', 'truck', 'boat', 'traffic light',
        'fire hydrant', 'stop sign', 'parking meter', 'bench', 'bird', 'cat', 'dog', 'horse', 'sheep', 'cow',
        'elephant', 'bear', 'zebra', 'giraffe', 'backpack', 'umbrella', 'handbag', 'tie', 'suitcase', 'frisbee',
        'skis', 'snowboard', 'sports ball', 'kite', 'baseball bat', 'baseball glove', 'skateboard', 'surfboard',
        'tennis racket', 'bottle', 'wine glass', 'cup', 'fork', 'knife', 'spoon', 'bowl', 'banana', 'apple',
        'sandwich', 'orange', 'broccoli', 'carrot', 'hot dog', 'pizza', 'donut', 'cake', 'chair', 'couch',
        'potted plant', 'bed', 'dining table', 'toilet', 'tv', 'laptop', 'mouse', 'remote', 'keyboard', 'cell phone',
        'microwave', 'oven', 'toaster', 'sink', 'refrigerator', 'book', 'clock', 'vase', 'scissors', 'teddy bear',
        'hair drier', 'toothbrush']  # class names

  
