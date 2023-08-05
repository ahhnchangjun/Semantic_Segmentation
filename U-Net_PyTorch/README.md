# U-Net
**TITLE**
[U-Net: Convolutional Networks for Biomedical Image Segmentation](https://arxiv.org/abs/1505.04597)

한요섭님의 유튜브 강좌와 GITHUB를 참고하며 공부 후 업로드한 자료입니다.
해당 링크를 첨부하도록 하겠습니다.

**hanyoseob's GITHUB** -> [[Link](https://github.com/hanyoseob/youtube-cnn-002-pytorch-unet)]

 - UNet: 데이터셋 전처리 하기 -> [[Link](https://www.youtube.com/watch?v=fWmRYmjF-Xw)]
 - UNet: 네트워크 구현하기 -> [[Link](https://www.youtube.com/watch?v=sSxdQq9CCx0)]
 - Data loader & transform
   구현하기 -> [[Link](https://www.youtube.com/watch?v=1gMnChpUS9k)]
 - UNet: Training 시키기 -> [[Link](https://www.youtube.com/watch?v=rBb597ct_FQ)]
 - UNet:Testing 시키기 -> [[Link](https://www.youtube.com/watch?v=igvk1W1JtHA)]
 
 구현은 colab에서 진행하였으며, 영상을 보며 실습해보았습니다.
 
 #### DATASETS
 
 - ISBI 2012 EM Sementation Challenge에 사용한 membrane 데이터셋
 - 왼쪽의 세포 이미지는 512 x 512 (grayscale)이며, 오른쪽 세포와 세포 사이의 벽을 분할한 모습입니다.
(실제 레이블된 값은 세포는 255, 배경은 1로 지정되어 있습니다.)

 
![enter image description here](https://imagej.net/media/events/challenge-isbi-2012-sample-image.png)
 

 - 다운로드: [ImageNet](https://imagej.net/events/isbi-2012-segmentation-challenge) (register 후 download) or 한요섭님의 [GITHUB](https://github.com/hanyoseob/youtube-cnn-002-pytorch-unet)

직접 보고 따라하며 도움이 많이된 자료입니다 !
