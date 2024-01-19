# 사용한 기술 
<img src="https://img.shields.io/badge/Swift-F05138?style=for-the-badge&logo=Swift&logoColor=white"> <img src="https://img.shields.io/badge/UIKit-2396F3?style=for-the-badge&logo=Swift&logoColor=white">

# 실행 환경
- Xcode 15.2
- iOS 17.0
- iPhone 12 환경에서 시뮬레이터 진행  
<br/>

# 앱 소개  
<img src="https://github.com/kangsworkspace/DataStorage/assets/141600830/fc63f96c-4aa4-4286-8ca7-a0a2723337cd"  width="300" height="650"/>
<img src="https://github.com/kangsworkspace/DataStorage/assets/141600830/e3feddda-0fcc-46fc-8b07-d4d8c8398abc"  width="300" height="650"/>


**이번에 출시한 앱의 이름은 <뭐 먹지? 태그로 관리하는 맛집 & 룰렛> 입니다.**   
밖에 나가서 밥을 먹을 때는 항상 무엇을 먹을지 고민하지 않으세요?  
<br/>
특히 자주 가는 장소에서 고민하다가 일단 생각나는 곳에서 먹고 뒤늦게  
아 거기도 있었는데 그거 먹을걸...하던 순간들이 누구나 한번쯤 있을것이라고 생각합니다.  
<br/>
그래서 자주 가는 식당들을 특정 **키워드와 함께 등록**해두고 ex) 집 근처, 회사 근처    
고민될 때 **랜덤으로 뽑아주는 앱**을 만들어봐야겠다! 하고 만든 앱이 이  **<뭐 먹지? 태그로 관리하는 맛집 & 룰렛>** 입니다.     
<br/>
<br/>
<br/>
<뭐 먹지? 태그로 관리하는 맛집 & 룰렛>은 아래의 그림처럼  
맛집을 추가하기 위한 검색이 가능하고 추가할 맛집을 태그와 함께 저장/수정이 가능합니다.  
<img src="https://github.com/kangsworkspace/DataStorage/assets/141600830/8d39f204-2186-47aa-967f-15a103115fde"  width="300" height="650"/>
<img src="https://github.com/kangsworkspace/DataStorage/assets/141600830/2d8fb13d-ff96-4c3f-b22c-cc292df81a27"  width="300" height="650"/>
<img src="https://github.com/kangsworkspace/DataStorage/assets/141600830/9550d26c-6049-4416-a5c0-99397c5cf207"  width="300" height="650"/>  
<br/>
<br/>
<br/>
또한 태그를 이용하여 랜덤으로 저장한 맛집을 뽑아줍니다.  
<img src="https://github.com/kangsworkspace/DataStorage/assets/141600830/f68ef71c-1f99-4796-b00d-328281b687ae"  width="300" height="650"/>
<img src="https://github.com/kangsworkspace/DataStorage/assets/141600830/59aeb1b2-30da-4d38-94a7-62b82c7d58ab"  width="300" height="650"/>  
<br/>
<br/>
<br/>
또한 맛집을 추가할 때 이미 추가했던 태그는 다음에 미리 목록에 표시하고  
룰렛을 돌릴 태그를 설정할 때 이전 태그에 해당하는 식당의 태그만 다음 목록에 보여주는 로직이 구현되어 있습니다.  
<img src="https://github.com/kangsworkspace/DataStorage/assets/141600830/daaa2fa5-8607-4643-b147-2f46846a66f0"  width="300" height="650"/>
<img src="https://github.com/kangsworkspace/DataStorage/assets/141600830/bc79d597-1502-45af-b6e9-256167f04814"  width="300" height="650"/>  
<br/>
<br/>
그 외에도  
사진을 눌러서 기본 이미지를 앨범 이미지로 바꾸기와 중간에 추가한 태그 꾹 눌러서 삭제하기,  
링크를 누르면 해당 페이지로 연결해주기 등의 기능이 있습니다.  
<img src="https://github.com/kangsworkspace/DataStorage/assets/141600830/fc18a35c-3f04-49bb-b834-57fa2f2d6509"  width="300" height="650"/>
<img src="https://github.com/kangsworkspace/DataStorage/assets/141600830/388c3fc4-707b-42a5-84c2-38510c60613b"  width="300" height="650"/>
<img src="https://github.com/kangsworkspace/DataStorage/assets/141600830/952bd69d-e7a0-4988-969d-b95ae9752caa"  width="300" height="650"/>  
<br/>
<br/>
<br/>

# 핵심 기능 및 구현 방법들   
## 룰렛 돌리기   
## 코어데이터  
## 파일매니저  
## 핵심 로직1(이전 태그에 해당하는 식당의 태그만 보여주기)  
## (+, -)버튼에 따른 테이블 뷰 처리  

<br/>
<br/>
<br/>  

# Troubleshooting  
## 유동적인 테이블 뷰 갯수 처리  
## 디자인 패턴  
## 코어데이터 - Relationships
## 동작이 가능한지를 시각적으로 알려주는 버튼의 색상과 실제 동작 가능의 여부 연결
<br/>
<br/>
<br/>

# 앱을 만들며 고민한 부분들
### URL 이동
첫번째 그림은 제 <뭐 먹지? 태그로 관리하는 맛집 & 룰렛 > 앱에서 맛집을 저장하거나 수정하는 페이지 입니다.  
저기서 URL을 누르면 두번째 그림처럼 URL에 해당하는 웹뷰를 띄우게 됩니다.  
<img src="https://github.com/kangsworkspace/MukAppOfficial/assets/141600830/3dd3485c-31cf-4f31-b6c5-c23e83add64e"  width="300" height="650"/>
<img src="https://github.com/kangsworkspace/MukAppOfficial/assets/141600830/5f8c4c34-3a16-40a0-93fe-3e85b0cf9866"  width="300" height="650"/>   

해당 기능은 아래의 코드와 같이 `SFSafariViewController`를 사용하였습니다.  
먼저 `SafariServices`를 임포트 하고 해당 url을 파라미터로 넣은 `SFSafariViewController` 타입의 `safariViewController`를 선언했습니다.  
그리고 해당 `safariViewController`를  `present`로 화면을 띄웠습니다.  

```swift
func goWebPage(url: String, fromVC: UIViewController) {
    if url != "등록된 정보가 없습니다" {
        guard let url = URL(string: url) else { return }
        let safariViewController = SFSafariViewController(url: url)
        safariViewController.modalPresentationStyle = .automatic
        fromVC.present(safariViewController, animated: true)
    }
}
```  

처음에 사용한 코드는 아래와 같이 조금 달랐습니다.  
아래 코드로는 `import SafariServices`를 하지 않고 바로 화면을 띄울 수 있었습니다.  
```swift
@objc func buttonTapped(_ url: String) {
    if let url = URL(string: url) {
        UIApplication.shared.open(url, options: [:])
    }
}
```  
그림은 위 코드로 화면을 이동한 모습입니다.
이전의 코드와 달리 완전히 사파리 앱이 켜져서 해당 URL로 이동하는 방식으로 작동합니다.  
<img src="https://github.com/kangsworkspace/MukAppOfficial/assets/141600830/4a5a4895-fe01-4df2-b04f-3e48eff97a4c"  width="300" height="650"/>  
<img src="https://github.com/kangsworkspace/MukAppOfficial/assets/141600830/834aa7b2-d496-4b0d-9ca2-9932cfe449c1"  width="300" height="650"/>   
**저는 제 앱에서 사용자가 식당의 정보를 간단하게 둘러보고 아래로 쓱 내려서 창을 끌 수 있으면 좋겠다고 생각했습니다.**  
하지만 이 방식으로는 네비게이션 바의 작은 버튼을 눌러서 돌아가거나 홈 화면으로 돌아가면서 앱을 다시 켜줘야해서  
사용자의 입장에서 번거로울거 같아 `SFSafariViewController` 사용하였습니다.  
그리고 `SFSafariViewController`가 비교적 더 최근에 나온 방식이고 웹 뷰를 따로 설정하지 않고도 간단하게 창을 띄울 수 있어 일반적으로 더 사용성이 좋은 방법이라고 생각하기도 합니다.  

# 추가 / 보완하면 좋을 내용들  
### 저장한 맛집 페이지에서 원하는 맛집을 바로 검색할 수 있는 편의 기능  
- `UISearchController`를 이용한 검색 기능이나 저장한 태그를 설정할 수 있는 항목을 추가하면 완성도가 높아질 것 같습니다.  

### 저장한 맛집이 아닌 주변의 음식점들을 랜덤으로 뽑아주는 기능  
- 카카오 API의 거리를 기준으로 데이터를 받는 기능을 응용하여 구현 가능할 것 같습니다.  

# 사용한 외부 라이브러리  
[드롭다운 라이브러리](https://github.com/AssistoLab/DropDown)
- 태그 버튼에 해당하는 UI에 사용되었습니다. 

[카카오 API Service](https://developers.kakao.com)
- 검색 기능에 사용되었습니다.

# License  
Licensed under the [MIT](https://github.com/kangsworkspace/MukAppOfficial/blob/main/LICENSE) license.

