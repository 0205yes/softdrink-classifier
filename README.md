# softdrink-classifier


## set_vars.py

* 파일 경로 설정
* 모델 훈련에 필요한 변수 정의


## softdrink_classifier.py

* generate_image() : 이미지 처리
* create_model() : 모델 생성
* fit_model(save_dir, model, train_gen, validation_gen) : 모델 훈련
* print_result(history) : 결과 출력


## add_class.py

* 기존 모델에 새로운 layer를 추가
* 마지막 두 개의 layer를 없애고 새로 add


## test_model.py

* 완성된 model을 load
* 새로운 이미지로 모델 성능 test


## convert_model.py

* 완성된 model을 load
* tflite 모델로 변환
