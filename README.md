# Transformers
<ul>

  <li>Transformer.ipynb -> 트랜스포머 구조를 직접 구현하여 만듬, 영어 프랑스어 개별 tokenizer를 사용하지 않고 공백을 기준으로 vocab생성 그러나 훈련 데이터셋에 존재하는 token만 vocab에 존재하므로 unknown token이 발생할때 번역 정확도가 매우 떨어짐 </li>

  <li>newTransformer.ipynb -> Transformer.ipynb에서 unk토큰의 개수를 줄이기 위해서 사전 학습된 개별 Tokenizer를 가져와서 만듬 그러나 French_tokenizer를 생성할때 eng_tokenizer와 special_token가 동일하지 않고 index도 서로 달라서 문제가 발생했는데 parameter로 설정하지 않고 임의로 index를 변경하다 보니 시원찮은 결과가 나타난것같다. </li>

</ul>
