# Mash Up WEB 팀 Next.js 스터디 🧑🏻‍💻👩🏻‍💻
### Members
| [김규리 👑](https://github.com/Grit03) |[안서진](https://github.com/xxj15) | [윤신지](https://github.com/sinji2102) | [조재석](https://github.com/Pridesd) |
|:---:|:---:|:---:|:---:|
| <img src="https://github.com/Grit03.png" width="150"> | <img src="https://github.com/xxj15.png" width="150"> | <img src="https://github.com/sinji2102.png" width="150"> | <img src="https://github.com/Pridesd.png" width="150"> |

### 진행 내용

- 웹 렌더링 전략 및 React Server Component에 대한 이해를 바탕으로, [Next.js 공식문서](https://nextjs.org/docs/app/building-your-application)의 렌더링(Rendering), 데이터 패칭(Data Fetching), 라우팅(Routing) 부분을 학습합니다.

### 진행 방법

- 매주 [진도표](#curriculum) 주제에 맞게, [Next.js 공식문서](https://nextjs.org/docs/app/building-your-application) 혹은 정해진 article를 읽고 정리합니다.
- 학습하면서 정리한 문서는 **스터디 진행 10분 전까지 PR을 작성**합니다.
- 마크다운 문서에 학습 내용을 정리해도 좋고, 노션, 블로그 등에 정리한 후, 마크다운에는 링크만 작성해도 좋습니다.
- 매주 랜덤으로 1명의 발표자를 정해, 정리한 내용을 함께 공유하고 Q&A 세션을 가집니다.
- 발표는 정리한 내용을 함께 읽으면서 공유하는 느낌으로 부담없이 진행합니다.
- 스터디가 끝나면 PR 승인 후 merge 합니다.

### 진도 계획 <a id="curriculum">
| 주차 | 스터디 날짜 | 학습 내용 | 학습 자료 |
|:---:|:---:|:---:|:---|
| **1주차** | 03.20(목) 22시 | 웹 렌더링 전략 및 <br /> React Server Component의 이해 | [웹 렌더링 전략 비교](https://nextjs.org/learn/seo/rendering-strategies) <br/> [내 앱에 가장 적합한 렌더링 전략을 선택하는 방법](https://vercel.com/blog/how-to-choose-the-best-rendering-strategy-for-your-app) <br /> [리액트 서버 컴포넌트](https://ko.react.dev/reference/rsc/server-components) |
| **2주차** | 03.27(목) 21시 | 렌더링(Rendering) | [렌더링(Rendering)](https://nextjs.org/docs/app/building-your-application/rendering) | 
| **3주차** | 04.03(목) 21시 | React Server Function(서버 함수)에 <br/> 대한 이해 및  데이터 페칭(Data fetching) | [리액트 서버 함수](https://ko.react.dev/reference/rsc/server-functions) <br /> [데이터 페칭(Data fetching)](https://nextjs.org/docs/app/building-your-application/data-fetching) | 
| **4주차** | 04.10(목) 21시 | 라우팅(Routing) (1) | [Layouts and Templates](https://nextjs.org/docs/app/building-your-application/routing/layouts-and-templates) <br /> [Linking and Navigating](https://nextjs.org/docs/app/building-your-application/routing/linking-and-navigating) <br /> [Error Handling](https://nextjs.org/docs/app/building-your-application/routing/error-handling) <br /> [Loading UI and Streaming](https://nextjs.org/docs/app/building-your-application/routing/loading-ui-and-streaming) <br /> [Redirecting](https://nextjs.org/docs/app/building-your-application/routing/redirecting) <br /> [Route Groups](https://nextjs.org/docs/app/building-your-application/routing/route-groups) | 
| **5주차** | 05.09(금) 21시 | 라우팅(Routing) (2) | [Dynamic Routes](https://nextjs.org/docs/app/building-your-application/routing/dynamic-routes) <br /> [Parallel Routes](https://nextjs.org/docs/app/building-your-application/routing/parallel-routes) <br /> [Intercepting Routes](https://nextjs.org/docs/app/building-your-application/routing/intercepting-routes) | 


### 과제 제출 컨벤션

#### 최초 설정

1. 현재 레포지토리를 `fork` 한 뒤, fork한 레포지토리를 `clone` 해서 로컬로 내려받습니다.
2. 로컬로 내려받은 레포지토리에 새로운 원격 저장소를 추가합니다.  
   ex) `git remote add upstream https://github.com/mash-up-kr/web-nextjs-study.git`

#### 과제 제출 방법

1. 스터디를 진행하면서 기존의 과제가 merge되어 새로운 파일이 추가된 경우, `pull` 로 가져옵니다.  
   ex) `git pull upstream main`
2. 각 주차에 해당되는 폴더에 본인 영문 이름으로 된 폴더를 생성한 후, 정리한 파일을 마크다운으로 저장합니다.  
   ex) `[1주차] Rendering Strategies and RSC  / gyurikim / 김규리.md`
3. 만약, 마크다운 말고 더 추가하고 싶은 파일이 있다면, 본인 영문 이름으로 된 폴더 안에 추가로 저장합니다.  
   ex) `[1주차] Rendering Strategies and RSC / gyurikim / image.png`
4. 정리를 완료하면 PR의 이름을 `[이름] 1주차 과제 제출` 로 작성합니다.  
   ex) `[김규리] 1주차 과제 제출`
