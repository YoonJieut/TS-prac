# npm init -y

npm install --save typescript

npm install --save typescript ts-node 
이걸로 설치하면 프로젝트 내부에서만 동작한다.

# 실행하려면 npx 명령어가 필요
npx tsc --init

## tsm : ts 컴파일 명령어
--init 옵션은 tsconfig.js를 생성해준다.
ts compiler의 약자로, ts-node 패키지가 이를 가능하게 한다.

# npm과 tpyescript 두가지가 초기화 완료 되어야 정상작동한다.
tsconfig.json 파일이 생성됐는지 확인한다.

# ts를 js로 컴파일한다.
`npx tsc index.ts`를 실행하면 index.js가 생성된다.
