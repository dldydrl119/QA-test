<img src="https://capsule-render.vercel.app/api?type=waving&fontColor=fff&color=0028b0&height=300&section=header&=0abb26&text=[%20지마켓%20Quality%20Enginnering%20]&fontSize=30" />

## 로그인 및 상품 구매 자동화 자동화

Selenium을 사용하여 로그인하고 G마켓에서 상품을 검색,구매그리고 취소 시나리오를 자동화합니다.

### 이미 로그인되어 있는지 확인

```python
# 이미 로그인되어 있는지 확인
if "로그인" not in driver.page_source:
    print("이미 로그인이 되어있음")
```
### 테스트 계정 안내

자동화 테스트 실행 시 Json 파일에서 테스트 계정을 별도로 추가하여 진행해주세요.
```json
{
  "username": "ID",
  "password": "PASSWORD",
}
```
감사합니다.
