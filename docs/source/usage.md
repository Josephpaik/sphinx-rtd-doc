# 달팽이 라이브러리 사용자 가이드

## 라이브러리 설치

달팽이 라이브러리를 설치하는 방법:
```console
(.venv)$pip install lumache 
```
```{note}주의!
위의 설치방법은 문서화를 위한 예시일뿐 실제 동작하지 않는다.
```


## 기능 문서화 방법
### Creating Recipe

랜덤 레시피를 만들려면 {py:func}`lumache.get_random_ingredients` 함수를 사용한다:


( .rst 문서를 소스코드 코멘트에서 가져오는 방법)
```{eval-rst}
.. autofunction:: lumache.get_random_ingredients(kind=None)
```

Some times, an error will be raised:

```{eval-rst}
.. autoexception:: lumache.InvalidKindError
```

## 문서 참조를 위한 링크 만들기
세부내용은 Check out {doc}`tutorial` 문서 참고하세요
