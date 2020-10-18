# 한시간안에 끝내는 Vue.js

### Vue.js?

Component 기반의 SPA를 구축할 수 있게 해주는 프레임워크

> Component?
>
> 웹을 구성하는 로고, 메뉴바, 버튼, 모달 등 웹 페이지 내의 다양한 UI요소
>
> 재사용 가능하도록 구조화 한 것
>
> 
>
> SPA(Single Page Application)
>
> 단일 페이지 어플리케이션, 하나의 페이지 안에서 필요한 영역 부분만 로딩 되는 형태
>
> 빠른 페이지 변환, 적은 트래픽 양
>
> 초기에 로딩해야 하는 js, css 파일의 크기가 크면 클 수록 최초 로딩 시간이 길어진다.



#### Vue CLI

Vue project를 빠르게 개발, 빌드, 서비스 런칭 할 수 있도록 도와주는 Tool

기본적인 project 구조, 라이브러리, 웹팩을 자동으로 설정 해준다.

> CLI : Command Line Interface



vue cli 설치

```
npm install -g @vue/cli
```



프로젝트 생성

```
vue creaet (프로젝트명)
```

위와 같은 명령어로 프로젝트를 생성할 수 있고, 프로젝트 생성 옵션으로는 Default와 Manual이 있다.



#### Vue Router

Vue에서 Routing 기능을 구현할 수 있도록 지원해주는 공식 라이브러리

> Routing?
>
> 기존의 웹 페이지 이동 방법은 서버에 요청을 하여 이동 할 새로운 페이지는 받아왔다. 
>
> 기존의 개념과는 다르게 Single Page Application에서는 해당하는 모든 컴포넌트 페이지를 받아놓고 Routing을 이용하여 변경하고자 하는 부분만 화면을 갱신



vue router 설치

```
npm install vue-router --save
```



#### Vue lifecycle

![lifecycle](./images/lifecycle.png)