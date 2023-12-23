# Sutdy
JS / react Study ... 


# 프로젝트 생성 명령어 
yarn create react-app 

yarn add react react-dom react-scripts react-router-dom 



# 테일윈드 초기 설치
1. yarn add -D tailwindcss
2. npx tailwindcss init.
3. 설정 CSS (index.css)
@tailwind base;
@tailwind components;
@tailwind utilities;

4. tailwind.config.js 설정
content : ['경로/**/*.{jsx,js}']

a

# fontawesome 

1. yarn add @fortawesome/fontawesome-svg-core 
폰트어썸 svg 사용 
2. yarn add @fortawesome/free-solid-svg-icons @fortawesome/free-regular-svg-icons @fortawesome/free-brands-svg-icons
Free 아이콘 라이브러리 설치

3. yarn add --save @fortawesome/react-fontawesome@latest
Font Awesome을 React 컴포넌트 형태로 사용 할 수 있게하는 패키지 설치


# Yarn
 - yarn install

# Scss
- yarn add sass


# GIT
- 
git config user.name	# 이름 확인
git config user.email	# 이메일 확인

- .gitignore 파일 : push 예외파일반영
Ignore node_modules directory
/node_modules

Ignore yarn lock file
/yarn.lock



# mysql install
1. mysql -u 아이디 -p패스워드
2. mysql --version 
3. 환경변수 잘확인하기