## 중앙여중 이미지크롤링 수업

#### (1) 구름 IDE 접속하기
https://ide.goorm.io/


#### (2) 구글 이미지 다운로드 코드 복사하기
git clone https://github.com/doramons/google_image_download

cd google_image_download && python setup.py install



#### (3) 사진 다운로드 코드 입력하기
from google_images_download import google_images_download

response = google_images_download.googleimagesdownload()

arguments = {"keywords":"방탄소년단", "limit":20, "print_urls":True}

paths = response.download(arguments)

print(paths)


#### (4) 코드 실행 시키기
python index.py
