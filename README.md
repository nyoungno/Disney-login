# Disneyplus-login



### 개발기간: 1일

### 개발 목표
Disneyplus-login 웹페이지 구축

### 사용기술
- HTML
- CSS
- Bootstrap

## 프로젝트에서 다루는 주요 개념
footer 하단 고정 (컨텐츠 길이가 변할 때 마다 달라지는 footer)

1.footer { <br>
&nbsp;&nbsp;&nbsp;position : absolute; <br>
&nbsp;&nbsp;&nbsp;bottom : 0; <br>
    }

2.footer { <br>
&nbsp;&nbsp;&nbsp;position : fixed; (상시고정) <br>
&nbsp;&nbsp;&nbsp;bottom : 0; <br>
}

3.강제로 컨텐츠 길이를 늘이고, 그 아래에 footer를 박는다. <br>
<transform : translateY(-100%);> 를 통해 footer의 높이만큼 footer를 강제로 올려치기하여 해결한다.

### 개선사항
- 보류

## 포트폴리오 웹사이트 링크 : <https://nyoungno-disneylogin.netlify.app/>