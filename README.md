torchvision.transforms의 거의 모든 class (of function)이 input으로 Image or Tensor이다.  
https://pytorch.org/vision/0.9/transforms.html  

물론 추가로 trasnformation이 tensor에서 빠른지 Image에서 빠른지는 한번 더 봐야함.  

transformations from tensor or image 결과가 다를수도 있음.
(아마 다를거임)

https://pytorch.org/vision/stable/transforms.html#scriptable-transforms  
에 따르면 `Use tensors instead of PIL images`
