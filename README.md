# Swagger Open Api Generator

## 사용방법

### 1. package.json 으로 들어가 scripts의 주소를 수정한다.

```bash
# insert your url (ex: https://your-swagger-url/test-section/v3/api-docs)
"openapi": "openapi-generator generate -i https://dev.yourapiserver.com/openapi.json -g typescript-axios -o ./models -c ./openapi.json --skip-validate-spec"
```

### 2. command 에서 yarn openapi 수행하기

```bash
# in your command line
> yarn open api
```

## Mac 에서 수행시 빌드 오류 뜰때

### brew로 openapi-generator 가 설치되어있는지 확인한다.
```bash
# in your command line
> brew install openapi-generator
```