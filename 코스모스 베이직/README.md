# 개요

* 코스모스 베이직 모듈은 코스모스 허브(Gaia)와 IBC(Inter-Blockchain Communication Protocol), 코스모스BFT(BFT Consensus), 그리고 코스모스 SDK로 구성된 코스모스 블록체인 생태계 조망을 위한 아티클과 미션으로 구성된다. 미션은 IBC, CosmosSDK 활용을 위한 고(Go) 언어의 기초 실습부터 SDK의 실제 사용 방안 예시를 포함한다.
* 모듈은 아티클과 미션으로 구성된다. 아티클이란 특정 개념 혹은 현상을 설명하는 자료이다. 아티클은 기술 및 배경의 정의와 출현 배경, 구성 요소, 구동 원리, 특장점, 활용 방안을 포함한다. 반면 미션은 실습을 통해 기술 및 개념 체득을 유도하는 자료이다. 미션은 결과물 설명을 포함하는 목적 및 배경, 사전 설치, 코드와 설명을 포함한 수행 방법, 제출 내용을 포함한다.

# 모듈 구성

이더리움 베이직 모듈의 구성은 다음과 같다

|  | 구분 | 설명 | 자료 링크 |
| --- | --- | --- | ----- |
| 코스모스와<br>앱체인의 출현 배경 | 아티클 | 코스모스 앱체인이 출현한 이유와 맥락 | [앱체인의 출현 배경](https://github.com/Ludium-Official/road-to-dubai/blob/main/%EC%BD%94%EC%8A%A4%EB%AA%A8%EC%8A%A4%20%EB%B2%A0%EC%9D%B4%EC%A7%81/01_empathize_with_app_specific_chain.md) |
| 앱체인 아키텍처 이해 | 아티클 | 앱체인의 실제 구동 방식의 이해와 코스모스SDK의 관계 | [앱체인 아키텍처](https://github.com/Ludium-Official/road-to-dubai/blob/main/%EC%BD%94%EC%8A%A4%EB%AA%A8%EC%8A%A4%20%EB%B2%A0%EC%9D%B4%EC%A7%81/02_understand_app_chain.md) |
| Simapp 만들기 | 미션 | Simapp 제작 실습 | [Simapp 만들기](https://github.com/Ludium-Official/road-to-dubai/blob/main/%EC%BD%94%EC%8A%A4%EB%AA%A8%EC%8A%A4%20%EB%B2%A0%EC%9D%B4%EC%A7%81/04_run_simapp_node.md) |
| Simapp 아키텍처 이해 | 아티클 | Simapp 아키텍처 이해하기 | [Simapp 아키텍처](https://github.com/Ludium-Official/road-to-dubai/tree/main/%EC%BD%94%EC%8A%A4%EB%AA%A8%EC%8A%A4%20%EB%B2%A0%EC%9D%B4%EC%A7%81) |
| $ATOM과 <br>인터체인 보안 | 아티클 | 코스모스 허브 $ATOM의 의미와 인터체인 보안에 기반한<br>체인의 방향성 이해 | [$ATOM과](https://github.com/Ludium-Official/road-to-dubai/tree/main/%EC%BD%94%EC%8A%A4%EB%AA%A8%EC%8A%A4%20%EB%B2%A0%EC%9D%B4%EC%A7%81)<br>[인터체인 보안](https://github.com/Ludium-Official/road-to-dubai/tree/main/%EC%BD%94%EC%8A%A4%EB%AA%A8%EC%8A%A4%20%EB%B2%A0%EC%9D%B4%EC%A7%81) |
| 어카운트 | 아티클 | 코스모스와 어카운트와 주소 이해 | [어카운트](https://github.com/Ludium-Official/road-to-dubai/blob/main/%EC%BD%94%EC%8A%A4%EB%AA%A8%EC%8A%A4%20%EB%B2%A0%EC%9D%B4%EC%A7%81/11_accounts.md) |
| 가스비 | 아티클 | 코스모스 가스비, 가스 미터, AnteHandler 이해 | [가스비](https://github.com/Ludium-Official/road-to-dubai/blob/main/%EC%BD%94%EC%8A%A4%EB%AA%A8%EC%8A%A4%20%EB%B2%A0%EC%9D%B4%EC%A7%81/12_gas_fees.md) |
| 스토어와 키퍼 | 아티클 | 코스모스 앱 상태 유지를 위한 스토어와 키퍼 이해 | [스토어와 키퍼](https://github.com/Ludium-Official/road-to-dubai/blob/main/%EC%BD%94%EC%8A%A4%EB%AA%A8%EC%8A%A4%20%EB%B2%A0%EC%9D%B4%EC%A7%81/13_store_and_keepers.md) |
| RPC | 아티클 | RPC, IPC(Inter-Process Communication), HTTP API 이해 | [RPC](https://github.com/Ludium-Official/road-to-dubai/blob/main/%EC%BD%94%EC%8A%A4%EB%AA%A8%EC%8A%A4%20%EB%B2%A0%EC%9D%B4%EC%A7%81/14_rpc_basic.md) |
| Encoding | 아티클 | 노드 간 정보 통신 최적화 방안 및 코스모스 Encoding 이해 | [Encoding](https://github.com/Ludium-Official/road-to-dubai/blob/main/%EC%BD%94%EC%8A%A4%EB%AA%A8%EC%8A%A4%20%EB%B2%A0%EC%9D%B4%EC%A7%81/15_encoding.md) |
| gRPC와 cometBFT RPC | 아티클 | 코스모스 인터체인의 gRPC, REST, CometBFTRPC 이해 | [gRPC](https://github.com/Ludium-Official/road-to-dubai/blob/main/%EC%BD%94%EC%8A%A4%EB%AA%A8%EC%8A%A4%20%EB%B2%A0%EC%9D%B4%EC%A7%81/15_encoding.md) |
| Query | 아티클 | 풀 노드에게 정보를 요청하여 통신하는 방법 | [Query](https://github.com/Ludium-Official/road-to-dubai/blob/main/%EC%BD%94%EC%8A%A4%EB%AA%A8%EC%8A%A4%20%EB%B2%A0%EC%9D%B4%EC%A7%81/17_query.md) |
| 코스모스 베이직 모듈 | 아티클 | 코스모스 앱체인 개발에 있어 활용 가능한 모듈 이해 | [Basic Module](https://github.com/Ludium-Official/road-to-dubai/blob/main/%EC%BD%94%EC%8A%A4%EB%AA%A8%EC%8A%A4%20%EB%B2%A0%EC%9D%B4%EC%A7%81/20_module_basic.md) |
| Auth 모듈 실습 | 미션 | Auth 모듈 제작 실습 | [Auth Module](https://github.com/Ludium-Official/road-to-dubai/blob/main/%EC%BD%94%EC%8A%A4%EB%AA%A8%EC%8A%A4%20%EB%B2%A0%EC%9D%B4%EC%A7%81/21_module_auth.md) |
| Bank 모듈 실습 | 미션 | Bank 모듈 제작 실습 | [Bank Module](https://github.com/Ludium-Official/road-to-dubai/blob/main/%EC%BD%94%EC%8A%A4%EB%AA%A8%EC%8A%A4%20%EB%B2%A0%EC%9D%B4%EC%A7%81/22_module_bank.md) |
| FreeGrant 모듈 실습 | 미션 | FeeGrant 모듈 제작 실습 | [FeeGrant Module](https://github.com/Ludium-Official/road-to-dubai/blob/main/%EC%BD%94%EC%8A%A4%EB%AA%A8%EC%8A%A4%20%EB%B2%A0%EC%9D%B4%EC%A7%81/23_module_feegrant.md) |
| Authz 모듈 실습 | 미션 | Authz 모듈 제작 실습 | [Authz Module](https://github.com/Ludium-Official/road-to-dubai/blob/main/%EC%BD%94%EC%8A%A4%EB%AA%A8%EC%8A%A4%20%EB%B2%A0%EC%9D%B4%EC%A7%81/24_module_authz.md) |
| gov 모듈 실습 | 미션 | gov 모듈 제작 실습 | [Gov Module](https://github.com/Ludium-Official/road-to-dubai/blob/main/%EC%BD%94%EC%8A%A4%EB%AA%A8%EC%8A%A4%20%EB%B2%A0%EC%9D%B4%EC%A7%81/25_module_gov.md) |
| 커스텀 모듈 만들기 | 미션 | 커스텀 모듈 제작법 이해 | [Custom Module](https://github.com/Ludium-Official/road-to-dubai/blob/main/%EC%BD%94%EC%8A%A4%EB%AA%A8%EC%8A%A4%20%EB%B2%A0%EC%9D%B4%EC%A7%81/30_build_custom_module(wip).md) |

# 제안 및 추가

* 코스모스 베이직 교육 모듈은 오픈 소스 컨트리뷰션을 통해 지속적으로 자료를 보완, 발전시킨다
* 현존하는 모듈에 제안을 원하는 빌더는 [Issue를 통해 제안 내용을 작성하거나](https://github.com/Ludium-Official/road-to-dubai/issues) 리포를 포킹해서 개선된 내용을 [Pull Request로 바로 요청](https://github.com/Ludium-Official/road-to-dubai/pulls)할 수도 있다
* 제안, 요청된 내용은 루디움에서 검토 이후 적절성을 판단하여 자료를 업데이트 한다