# twitter-clone-Vuejs-

뷰를 cli버젼으로 설치할떄 하는 명령어
npm install -g @vue/cli

라우터 생성
const router = new VueRouter({
    mode: = "history",
    route:[
        {path:'/',component:Home} -> 아무것도 안눌렀을때 home페이지로 오게한다
        {path:'/about',component:About} -> about페이지를 눌렀을때 about페이지로 오게 한다.
    ]
});

Tailwind css의 장점
1. 기존 css는 따로 html과 css를 따로 썻지만 tailwind css 는 html에 css 요소를 같이 쓸수 있어서 코드가 간편해진다.
