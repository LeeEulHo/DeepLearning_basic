# 『딥러닝 기초 정리 - 밑바닥부터 시작하는 딥러닝』

<a href="https://www.hanbit.co.kr/channel/category/category_view.html?cms_code=CMS2416204088&cate_cd="><img src="https://github.com/WegraLee/deep-learning-from-scratch/blob/master/remastered.png" width="300" align=right></a>

<a href="https://product.kyobobook.co.kr/book/preview/S000215599933">[미리보기]</a> | <a href="https://docs.google.com/document/d/1kOK8Tu4E0ENtl0N5ugSVH8B7kfIJ53Uiarx52T5RIqE/">[알려진 오류(정오표)]</a> | <a href="https://github.com/WegraLee/deep-learning-from-scratch/raw/refs/heads/master/equations_and_figures.zip">[본문 그림과 수식 이미지 모음]</a>

:red_circle: **[공지]** 2025년 1월에 '리마스터판'이 출간되었습니다. 리마스터판의 예제 코드는 초판의 예제 코드와 호환되므로, 초판 독자 분들도 이 저장소의 코드를 그대로 활용하시면 됩니다. 또한, 본질이 달라진 게 아니므로 다시 구매하실 필요 없습니다. 달라진 점은 <a href="https://www.hanbit.co.kr/channel/category/category_view.html?cms_code=CMS2416204088&cate_cd=">제작 뒷이야기</a>에 정리했습니다.

:red_circle: **[공지]** 종종 실습용 손글씨 데이터셋 다운로드 사이트( http://yann.lecun.com/exdb/mnist/ )가 연결되지 않습니다.
그래서 예제 수행에 필요한 데이터셋 파일을 /dataset/ 디렉터리에 올려뒀습니다.
혹 사이트가 다운되어 데이터를 받을 수 없다면 아래 파일 4개를 각자의 <예제 소스 홈>/dataset/ 디렉터리 밑에 복사해두면 됩니다.

* [t10k-images-idx3-ubyte.gz](https://github.com/WegraLee/deep-learning-from-scratch/raw/master/dataset/t10k-images-idx3-ubyte.gz)
* [t10k-labels-idx1-ubyte.gz](https://github.com/WegraLee/deep-learning-from-scratch/raw/master/dataset/t10k-labels-idx1-ubyte.gz)
* [train-images-idx3-ubyte.gz](https://github.com/WegraLee/deep-learning-from-scratch/raw/master/dataset/train-images-idx3-ubyte.gz)
* [train-labels-idx1-ubyte.gz](https://github.com/WegraLee/deep-learning-from-scratch/raw/master/dataset/train-labels-idx1-ubyte.gz)

---
## 요구사항
소스 코드를 실행하려면 아래의 소프트웨어가 설치되어 있어야 합니다.

* 파이썬 3.x
* NumPy
* Matplotlib


## 실행 방법 (리마스터판)
어디서든 실행할 수 있습니다.
```
$ python deep-learning-from-scratch-master/ch01/img_show.py

$ cd deep-learning-from-scratch-master
$ python ch01/img_show.py

$ cd ch01
$ python img_show.py
```

## 실행 방법 (초판)
각 장의 디렉터리로 이동 후 실행해야 합니다(**다른 디렉터리에서는 제대로 실행되지 않을 수 있습니다!**).
```
$ cd ch01
$ python man.py

$ cd ../ch05
$ python train_nueralnet.py
```

---

## 동영상 강의
수원대학교 한경훈 교수님께서 『밑바닥부터 시작하는 딥러닝』 1, 2편을 교재로 진행하신 강의를 공개해주셨습니다. 책만으로 부족하셨던 분들께 많은 도움이 되길 바랍니다.

딥러닝 I - <a href="https://sites.google.com/site/kyunghoonhan/deep-learning-i">[강의 홈페이지]</a>

[![시리즈 1](https://img.youtube.com/vi/8Gpa_pdHrPE/0.jpg)](https://www.youtube.com/watch?v=8Gpa_pdHrPE&list=PLBiQZMT3oSxW1RS1hn2jWBgswh0nlcgQZ)

딥러닝 II - <a href="https://sites.google.com/site/kyunghoonhan/deep-learning-ii">[강의 홈페이지]</a>

[![시리즈 1](https://img.youtube.com/vi/5fwD1p9ymx8/0.jpg)](https://www.youtube.com/watch?v=5fwD1p9ymx8&list=PLBiQZMT3oSxXNGcmAwI7vzh2LzwcwJpxU)

딥러닝 III - <a href="https://sites.google.com/site/kyunghoonhan/deep-learning-iii">[강의 홈페이지]</a>

[![시리즈 1](https://img.youtube.com/vi/kIobK76on3s/0.jpg)](https://www.youtube.com/watch?v=kIobK76on3s&list=PLBiQZMT3oSxV3RxoFgNcUNV4R7AlvUMDx)

이 저장소의 소스 코드는 [MIT 라이선스](http://www.opensource.org/licenses/MIT)를 따릅니다.
상업적 목적으로도 자유롭게 이용하실 수 있습니다.
