# 연습용

1. 안녕하세요.
2. *박재현*입니다.
- 안녕하세요
- **박재현**입니다
+ 안녕하세요
+ ***박재현***입니다
  + ~~반가워요~~
```python
class Member:
    def __init__(self,name,account,passwd,birthyear):
        self.name = name
        self.account = account
        self.passwd = passwd
        self.birthyear = birthyear

member1 = Member('둘리','DL','1234','1996')
member2 = Member('또치','ddochi','5678','1996')
member3 = Member('고길동','go','road','1970')

print(f'회원1 : {member1.name}({member1.account},{member1.passwd},{member1.birthyear})')
print(f'회원2 : {member2.name}({member2.account},{member2.passwd},{member2.birthyear})')
print(f'회원3 : {member3.name}({member3.account},{member3.passwd},{member3.birthyear})')
```
<https://github.com/ParkJaehyeonZany>

[본계정 프로필](https://github.com/ParkJaehyeonZany)

[Google](https://google.com, "구글")
