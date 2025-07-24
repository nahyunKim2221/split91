# 기록용
- [3d 프린팅 주문 사이트](https://cart.jlcpcb.com/shopcart/cart?spm=Jlc3dp.Homepage.1009&_gl=1%2akf6hdr%2a_gcl_au%2aODU3Njc4NzE3LjE3NTI5MTY2MDI.%2a_ga%2aMTM3NTQyMjM4OC4xNzUyOTE2NTUw%2a_ga_BZ8D96C9TK%2aczE3NTI5MjQxNzkkbzIkZzEkdDE3NTI5MjUwMTUkajUxJGwwJGgw)
- [조립 후기 (Eng)](https://www.printables.com/model/75599-split89/comments)
- [ZMK Firmware](https://zmk.dev/docs/hardware)

## 25/07/21
- 3d 프린터 견적 새로 넣음 [메이드올](https://madeall3d.com/), [3d프로](https://blog.naver.com/PostView.naver?blogId=3dprocess&logNo=223705889279&categoryNo=1&parentCategoryNo=-1&viewDate=&currentPage=&postListTopCurrentPage=) -> PLA 소재  
→ 메이드올로 진행 견적 약 5만원

## 25/07/24
### ZMK 관련 문서
- [ZMK 공식 튜토리얼](https://zmk.dev/docs/user-setup)
- [ZMK 키맵 에디터](https://gall.dcinside.com/mgallery/board/view/?id=mechanicalkeyboard&no=2316367)
- [ZMK + nice!nano 연결](https://www.clien.net/service/board/cm_keyboard/16912309)
- [ZMK 키맵 수정 가이드](https://gall.dcinside.com/mini/board/view/?id=splitkeeb&no=1315&exception_mode=recommend&page=1)
- [ZMK로 키보드 빌드 (ENG/요약)](https://www.instructables.com/Budget-DIY-Wireless-Split-Keyboard-With-ZMK/)

## ZMK 설정시 참고할 것들
- 제공되는 키보드 배열 중에는 `Iris` 가 제일 적합  

| 항목           | **Iris**                    | **Helix**          |
| ------------ | --------------------------- | ------------------ |
| **Split 구조** | ✅ 좌우 분리형                    | ✅ 좌우 분리형           |
| **ZMK 지원**   | ✅ 있음                        | ✅ 있음               |
| **키 수**      | 약 56키 (6x5 + thumb cluster) | 약 60키 (5x6)        |
| **기반 형태**    | Ergodox 계열 (인체공학적)          | ortho-linear (격자형) |
| **레이아웃 유사도** | ⭕                           | ❌                   |
| **매트릭스 구조** | 전통적 row/col | 전통적 row/col |
| **TRRS 연결 예시** | 있음 | 있음 |
| **디버깅 사례/예시** | 많음 | 적지만 존재 |
| **ZMK config 커스터마이징** | 비교적 용이 | 가능하나 복잡도 ↑ |



# TODO
- [x] 알아본 3d 프린팅 소재는 9600 Resin 인데 다른 사람들은 PLA를 많이 쓴듯? 어떻게 할지
- [x] 3d 프린팅 가격이 팜레스트 포함시 15만원, 제외시 7만원정도 나올듯 어떻게할지