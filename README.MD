# 일지 관리

각자 본인 디렉토리에서 `일지.md`를 관리합니다.

```text
root/
├── README.md
├── user1/
│   └── 일지.md
├── user2/
│   └── 일지.md
├── user3/
├── user4/
└── user5/
```

## 규칙

* 루트 전체를 일반 clone해서 작업하지 않습니다.
* 본인 디렉토리만 받아서 작업합니다.
* 다른 사람의 디렉토리나 일지는 수정하지 않습니다.
* push 전 본인 `일지.md`만 변경됐는지 확인합니다.

```bash
git status
```

커밋할 때도 본인 일지만 추가합니다.

```bash
git add <본인디렉토리>/일지.md
git commit -m "일지 업데이트"
git push
```

`git add .` 사용은 지양합니다.
