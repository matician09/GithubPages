# Github Pages 구축 방법

## WorkLog
### 2020-09-16
#### 한국어 설정
1. [`pages-themes/cayman`](https://github.com/pages-themes/cayman)의 `_layouts/default.html` 확인  
    
    ```html
    <!DOCTYPE html>
    <html lang="{{ site.lang | default: "en-US" }}">
    <head>
    ```  
1. `site.lang` 설정을 위해 `_config.yml` 파일에 `lang: ko` 추가  

#### Google Analytics
1. [Google Analytics](http://anlytics.google.com)에서 추적 ID 발급  
1. `_config.yml`파일에 `google_analytics: [my ID]` 추가  

### 2020-09-14
1. 새로운 Public Repo 생성  
1. `Settings` → `Theme Chooser` → `Select theme`  
1. `index.md` 편집 후 `Commit changes`  

레퍼런스: [Github Pages](https://pages.github.com/)

## Future Works
- Facebook Comments Plugin  
- Google Ad  