# Hidden Face 2024 Noonootv Action

이 GitHub Action은 이미지에서 얼굴을 자동으로 숨기는 기능을 제공합니다.

## 사용법

이 액션을 워크플로우에 추가하려면 다음과 같이 설정하세요:

```yaml
jobs:
  hide_faces_job:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout code
        uses: actions/checkout@v2
      - name: Hide Faces
        uses: imleadingmylife/hidden-face-actions@v1
        with:
          image_path: './images/example.jpg'
# hidden-face-actions
