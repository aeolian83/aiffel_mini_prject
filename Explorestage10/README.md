# Aiffel Mini Project - Explorestage 10

### Seq2Seq Machine Translator
- Check library version(라이브러리 버전을 확인해 봅니다)
- Step 1. Cleaning, normalization, preprocessing (both in English and French!).(정제, 정규화, 전처리 (영어, 프랑스어 모두!))
	- Cleaning(정제)
	- Word tokenization(단어토크나이징)
	- Shuffling the DataFrame(Dataframe 셔플)
- Step 2. Insertion of start and end tokens in the decoder's sentence.(디코더의 문장에 시작 토큰과 종료 토큰을 넣어주세요.)
- Step 3. Integer encoding text using Keras' Tokenizer.(케라스의 토크나이저로 텍스트를 숫자로 바꿔보세요.)
	- English integer encoding.(영어 정수 인코딩)
	- French integer encoding.(프랑스어 정수 인코딩)
	- Check the results of integer encoding.(정수인코딩 결과 확인)
- Step 4. Using an embedding layer.(임베딩 층(Embedding layer) 사용하기)
	- Building an embedding model and an encoder model.(임베딩 모델 및 인코더 모델 빌딩)
- Step 5. Implementing the model.모델 구현하기
	- Building the decoder model.디코더 모델 빌드
	- Testing training time and training performance according to batch size.(배치사이즈에 따른 훈련시간 및 훈련적합도 테스트)
	- Conclusions
- Step 6. Evaluating the model(모델 평가하기)
	- Redesigning the decoder(디코더 재설계)
	- Implementing a translator(번역기 작성)

### Reflection(회고)