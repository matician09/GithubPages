# Github Pages 구축 방법

---

## WorkLog
### 2020-09-17
#### Facebook 댓글 플러그인
1. Facebook 개발자 계정 생성  
1. 새로운 `앱 만들기`를 통해 앱 생성  
1. 하단 [레퍼런스](https://developers.facebook.com/docs/plugins/comments) 참조하여, `index.md` 원하는 위치에 코드 추가  

레퍼런스: [Facebook 문서](https://developers.facebook.com/docs/plugins/comments)

### 2020-09-16
#### 한국어 설정
1. [`pages-themes/cayman`](https://github.com/pages-themes/cayman)의 `_layouts/default.html` 확인  
    
    ```html
    {% raw %}<!DOCTYPE html>
    <html lang="{{ site.lang | default: "en-US" }}">
    <head>{% endraw %}
    ```  
1. `site.lang` 설정을 위해 `_config.yml` 파일에 `lang: ko` 추가  

#### Google Analytics
1. [Google Analytics](https://analytics.google.com/analytics/web)에서 추적 ID 발급  
1. `_config.yml`파일에 `google_analytics: [my ID]` 추가  

### 2020-09-14
1. 새로운 Public Repo 생성  
1. `Settings` → `Theme Chooser` → `Select theme`  
1. `index.md` 편집 후 `Commit changes`  

레퍼런스: [Github Pages](https://pages.github.com)

---

## Future Works
- `page.title` and `page.description` 추가  
- Google Ad  
- Facebook 댓글 플러그인 macOS safari 가변폭 설정  

---

## Comments

<div id="fb-root"></div>
<script async defer crossorigin="anonymous" src="https://connect.facebook.net/ko_KR/sdk.js#xfbml=1&version=v8.0&appId=347894753016508&autoLogAppEvents=1" nonce="I00e3BB7"></script>
<div class="fb-comments" data-href="https://matician09.github.io/GithubPages/" data-numposts="5" data-width=""></div>
