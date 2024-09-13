---
title: 예시 발표

event: Hugo Blox Builder 컨퍼런스
event_url: https://example.org

location: Hugo Blox Builder 본사
address:
  street: 450 Serra Mall
  city: 스탠포드
  region: CA
  postcode: '94305'
  country: 미국

summary: Hugo Blox Builder의 마크다운 슬라이드 기능을 사용한 예시 발표입니다.
abstract: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellusac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum. Sed ac faucibus dolor, scelerisque sollicitudin nisi. Cras purus urna, suscipit quis sapien eu, pulvinar tempor diam.'

# 발표 시작 및 종료 시간.
#   종료 시간을 숨기려면 줄 앞에 `#`을 추가하세요.
date: '2030-06-01T13:00:00Z'
date_end: '2030-06-01T15:00:00Z'
all_day: false

# 페이지 게시 날짜 (발표 날짜 아님).
publishDate: '2017-01-01T00:00:00Z'

authors:
  - admin

tags: []

# 이 발표가 주요 발표인가요? (true/false)
featured: false

image:
  caption: '이미지 출처: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: Right

#links:
#  - icon: twitter
#    icon_pack: fab
#    name: 팔로우
#    url: https://twitter.com/georgecushen
url_code: 'https://github.com'
url_pdf: ''
url_slides: 'https://slideshare.net'
url_video: 'https://youtube.com'

# 마크다운 슬라이드 (선택 사항).
#   이 발표를 마크다운 슬라이드와 연결하세요.
#   슬라이드 파일의 이름을 확장자 없이 입력하세요.
#   예: `slides = "example-slides"`는 `content/slides/example-slides.md`를 참조합니다.
#   그렇지 않으면 `slides = ""`로 설정하세요.
slides: ""

# 프로젝트 (선택 사항).
#   이 게시물을 하나 이상의 프로젝트와 연결하세요.
#   프로젝트 폴더 또는 파일 이름을 확장자 없이 입력하세요.
#   예: `projects = ["internal-project"]`는 `content/project/deep-learning/index.md`를 참조합니다.
#   그렇지 않으면 `projects = []`로 설정하세요.
projects:
  - example
---

{{% callout note %}}
위의 **슬라이드** 버튼을 클릭하여 내장된 슬라이드 기능을 확인하세요.
{{% /callout %}}

슬라이드는 몇 가지 방법으로 추가할 수 있습니다:

- Hugo Blox Builder의 [_Slides_](https://docs.hugoblox.com/reference/content-types/) 기능을 사용해 슬라이드를 **생성**하고, 발표 파일의 front matter에 `slides` 매개변수를 사용하여 연결
- `static/`에 기존 슬라이드 데크를 **업로드**하고, 발표 파일의 front matter에 `url_slides` 매개변수를 사용해 연결
- [쇼트코드](https://docs.hugoblox.com/reference/markdown/)를 사용해 Google Slides와 같은 슬라이드 또는 발표 비디오를 **임베드**.

추가적인 이벤트 세부 사항, 이미지 갤러리와 같은 [페이지 요소](https://docs.hugoblox.com/reference/markdown/)는 이 페이지 본문에 추가할 수 있습니다.
