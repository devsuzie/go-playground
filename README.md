# Go Playground

<img src="https://user-images.githubusercontent.com/40863240/145233206-2cbbb2c1-24db-4ae7-8943-26f46a96b54f.jpg" alt="gopher" width="350"/>

> 아아, 그건 제 잔상입니다만 

## command
- `go mod init`
  - go mod 파일 생성 
- `go run .`
  - go 파일 실행 명령어
- `go mod tidy`
  - 최신 패키지로 설치
  - 패키지를 신기하게 가져오네.. package / symbol 찾는 곳은 [여기](https://pkg.go.dev/)

## modules
> Go code is grouped into packages, and packages are grouped into modules.

- 모듈 이름 정하기
  - https://go.dev/doc/modules/managing-dependencies#naming_module
  - `<prefix>/<descriptive-text>`
    - prefix: 레포 이름 또는 다른 사람이 사용하지 않을 이름
    - descriptive-text: 프로젝트 이름
- Exported names
  - 함수 이름의 첫글자가 대문자인 경우 호출 가능
- `:=`
  - 변수 선언하고 initializing 한 줄로 할 수 있게 함
  - 오징어 같다 약간 qm6 센터페시아 같기도 하고