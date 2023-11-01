# CRUD

## 프로젝트 구조 작성

1. 프로젝트 폴더 생성
2. 프로젝트 폴더 VS CODE 열기
    - `.git ignore`,`README.md` 만들기

3. django 프로젝트 생성
```
django-admin startproject <project_name> .
```

4. 가상환경 설정
```
python -m venv venv
```

5. 가상환경 활성화
```
source venv/Scripts/activate
```

6. 가상환경에 장고 설치
```
pip install django
```

7. 서버 실행 확인
```
python manage.py runserver
```

8. 앱 생성
```
django-admin startapp <app_name>
```

9. 앱 등록 => 'settings.py'
```python
INSATALLED APP =[
    ..
    '<app_name>'
]
```