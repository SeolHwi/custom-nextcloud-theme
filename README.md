# custom-nextcloud-theme

### 테마 적용 전 설정

* themes 폴더에서 git clone

* layout.guest_new.php 파일을 core/templates/ 경로로 옮기기

* lib/private/TemplateLayout.php line 166, 172

  * 'guest' 를 'guest_new'로 수정

* core/css/variables.scss line 46 (적용 안됨.)

  * $color-primary: #0A5ABC !default; 로 변경
  
* config/config.php

  * 'theme' => 'one-tact', 추가


##### 참고
[https://github.com/zorn-v/nextcloud-social-login](https://github.com/juliushaertl/theming_customcss)
