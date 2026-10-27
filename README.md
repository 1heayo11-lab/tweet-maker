# TWEET MAKER

X(트위터) 화면처럼 보이는 게시물·답글·프로필·대화방 화면을 만들어 **PNG**나 **HTML**로 저장하는 메이커예요. 빌드 과정 없이 파일 하나(`index.html`)로 돌아가는 순수 HTML·CSS·JS라서 GitHub Pages에 그대로 올리면 사이트가 돼요.

사이트 주소: https://1heayo11-lab.github.io/tweet-maker/

## 폴더 구성

```
tweet-maker/
├─ index.html   편집기 전체 (화면·스타일·스크립트가 한 파일에 들어 있어요)
├─ README.md
└─ .nojekyll    GitHub Pages가 파일을 그대로 쓰게 하는 빈 파일
```

## GitHub Pages 켜기

1. 저장소의 **Settings → Pages**로 가요.
2. **Source: Deploy from a branch**, **Branch: main / (root)**를 고르고 **Save**를 눌러요.
3. 1~2분 뒤 위 사이트 주소로 열려요.

## 고치기

`index.html`을 저장소에서 열고 연필 아이콘으로 고치거나, 같은 이름의 파일을 다시 올리면 덮어써져요. 저장하면 1~2분 뒤 사이트에도 반영돼요.

## 내 컴퓨터에서 보기

`index.html`을 더블클릭하면 바로 열려요. 글꼴(Pretendard)을 jsDelivr에서 불러오므로 인터넷 연결이 있으면 더 보기 좋아요.

임시저장은 브라우저 안(IndexedDB)에만 남아요. 다른 브라우저나 기기로는 옮겨지지 않고, 사생활 보호 모드에서는 쓸 수 없어요.
