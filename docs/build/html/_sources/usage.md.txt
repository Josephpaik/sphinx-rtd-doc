# 달팽이 라이브러리 사용자 가이드

## 달팽이 설치

달팽이 라이브러리를 설치하는 방법:
```console
(.venv)$pip install lumache 
```

```{note}
주의!
위의 설치방법은 문서화를 위한 예시일뿐 실제 동작하지 않는다.
```

## 레시피 만들기

랜덤 레시피를 만들려면 {py:func}`lumache.get_random_ingredients` 기능을 사용한다:

```{eval-rst}
.. autofunction:: lumache.get_random_ingredients(kind=None)
```

아래처럼 오류가 나는 경우도 있다:

```{eval-rst}
.. autoexception:: lumache.InvalidKindError
```

## 달팽이 라이브러리 튜토리얼   
세부내용은 {doc}`notebooks/mytutorial` 문서 참고하세요
