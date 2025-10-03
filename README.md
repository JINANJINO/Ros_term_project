# Robot Operating system 수업 프로젝트
- 패키지는 2개 생성하였습니다.(ros_term_package, msg_interface)
```bash
src
    ├── msg_interface
    │   ├── action
    │   ├── CMakeLists.txt
    │   ├── include
    │   │   └── msg_interface
    │   ├── msg
    │   ├── package.xml
    │   ├── src
    │   └── srv
    └── ros_term_package
        ├── package.xml
        ├── resource
        │   └── ros_term_package
        ├── ros_term_package
        │   └── __init__.py
        ├── setup.cfg
        ├── setup.py
        └── test
            ├── test_copyright.py
            ├── test_flake8.py
            └── test_pep257.py
```

여기서 ```src/ros_term_package/ros_term_package```의 위치에 소스코드 작성해 주시면 됩니다.
message 관련 패키지는 ```src/msg_interface```에 있습니다.

- Custom message 저장 시

|Directory| Custom message |
|--------------|--------|
| `msg`    | Topic |
| `srv`  | Service |
| `Action`  | Action |
| `CMakeList.txt` | 의존성 메세지들 추가 |
