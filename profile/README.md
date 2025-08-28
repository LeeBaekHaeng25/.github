# 전자정부 표준프레임워크 4.3.0 컨트리뷰션

컨트리뷰션 대상
- DAO 단위 테스트
- ServiceImpl 단위 테스트
- Controller 단위 테스트
- 셀레늄(화면) 단위 테스트
- 이클립스 Problems 제거
- [PMD로 소프트웨어 보안약점 진단하고 제거하기](pmd.md)
- 시큐어코딩 일련번호 PK 파라미터 암복호화
- 검색 조건 유지
- 롬복 생성자 기반 종속성 주입
- CRUD 프로그램 자동 생생 기능 템플릿 수정

유튜브

https://www.youtube.com/playlist?list=PL6pSCmAEuNPE0vLtodu2geX-SA1YO6ALg

브랜치
```
- [ ] 버그수정 Bug fixes
  - feature/Bugfixes/test
- [ ] 기능개선 Enhancements
  - feature/Enhancements/test
- [ ] 기능추가 Adding features
  - feature/Addingfeatures/test
- [x] 기타 Others
  - feature/Others/test
```

|날짜|제목|공유링크|
|-|-|-|
|2025-04-12 토|전자정부 표준프레임워크 4.3.0 컨트리뷰션 준비|https://youtu.be/G82xDweUsX4|
|2025-04-19 토|[PMD로 소프트웨어 보안약점 진단하고 제거하기](#2025-04-19-토-pmd로-소프트웨어-보안약점-진단하고-제거하기)|https://youtu.be/QKyUDsitx90|
|2025-04-20 일|[test PMD-AltibaseClobStringTypeHandler](#2025-04-20-일-test-pmd-altibaseclobstringtypehandler)|https://youtu.be/_oS7O1awbA0|
|2025-04-21 월|[test PMD-EgovComCrossSiteHndlr](#2025-04-21-월-test-pmd-egovcomcrosssitehndlr)|https://youtu.be/3_07tmsmeys|
|2025-04-22 화|[test PMD-EgovWebApplicationInitializer](#2025-04-22-화-test-pmd-egovwebapplicationinitializer)|https://youtu.be/v8z63Dahg_k|
|2025-04-23 수|[test PMD로 소프트웨어 보안약점 진단하고 제거하기-HTMLTagFilter](#2025-04-23-수-test-pmd-htmltagfilter)|https://youtu.be/uqPuU5rEFKs|
|2025-04-24 목|[test PMD로 소프트웨어 보안약점 진단하고 제거하기-HTMLTagFilterRequestWrapper](#2025-04-24-목-test-pmd로-소프트웨어-보안약점-진단하고-제거하기-htmltagfilterrequestwrapper)|https://youtu.be/FB3kPtOyD6w|
|2025-04-25 금|[test PMD로 소프트웨어 보안약점 진단하고 제거하기-SessionTimeoutCookieFilter](#2025-04-25-금-test-pmd로-소프트웨어-보안약점-진단하고-제거하기-sessiontimeoutcookiefilter)|https://youtu.be/aA8nZ0QeFkM|
|2025-04-26 토|||
|2025-04-28 월|[test PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovFileMngUtil](#2025-04-28-월-test-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovfilemngutil)|https://youtu.be/bjEDZsm9_4Y|
|2025-04-29 화|[test PMD로 소프트웨어 보안약점 진단하고 제거하기-FileSystemUtils](#2025-04-29-화-test-pmd로-소프트웨어-보안약점-진단하고-제거하기-filesystemutils)|https://youtu.be/185e28SJt6o|
|2025-04-30 수|[test PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovComAbstractDAO](#2025-04-30-수-test-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovcomabstractdao)|https://youtu.be/6XnOPm7HZp0|
|2025-05-01 목|[test PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovBasicLogger](#2025-05-01-목-test-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovbasiclogger)|https://youtu.be/FUG2LiU_VeQ|
|2025-05-02 금|[test PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovMybatisUtil](#2025-05-02-금-test-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovmybatisutil)|https://youtu.be/8YZyzeBon44|
|2025-05-03 토|[test PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovResourceCloseHelper](#2025-05-03-토-test-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovresourceclosehelper)|https://youtu.be/7Cu3kZxBN4o|
|2025-05-05 월|[test PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovUrlRewriteFilter](#2025-05-05-월-test-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovurlrewritefilter)|https://youtu.be/sPhESldOgaA|
|2025-05-06 화|[test PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovWildcardReloadableResourceBundleMessageSource](#2025-05-06-화-test-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovwildcardreloadableresourcebundlemessagesource)|https://youtu.be/3S8ZxzMXSsk|
|2025-05-07 수|[test PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovBindingInitializer](#2025-05-07-수-test-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovbindinginitializer)|https://youtu.be/cA6OS-UIEaY|
|2025-05-08 목|[test PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovBindingInitializer](#2025-05-08-목-test-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovcomabstractcontroller)|https://youtu.be/xgn6EqSbru0|
|2025-05-09 금|[test PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovComIndexController](#2025-05-09-금-test-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovcomindexcontroller)|https://youtu.be/l-_UKMmPTVU|
|2025-05-10 토|[test PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovComUtlController](#2025-05-10-토-test-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovcomutlcontroller)|https://youtu.be/c83sHEWW0zo|
|2025-05-12 월|[test PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovFileDownloadController](#2025-05-12-월-test-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovfiledownloadcontroller)|https://youtu.be/UqFTcA_b_fk|
|2025-05-13 화|[test PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovFileMngController](#2025-05-13-화-test-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovfilemngcontroller)|https://youtu.be/MqqaUV2AWM4|
|2025-05-14 수|[test PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovImageProcessController](#2025-05-14-수-test-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovimageprocesscontroller)|https://youtu.be/sEcw1Nkbzfg|
|2025-05-15 목|[test PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovArticleController](#2025-05-15-목-test-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovarticlecontroller)|https://youtu.be/u7qSqln_q2M|
|2025-05-16 금|[test PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovSndngMailRegistServiceImpl](#2025-05-16-금-test-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovsndngmailregistserviceimpl)|https://youtu.be/ksReIX4moHw|
|2025-05-17 토|[test PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovSndngMailDetailController](#2025-05-17-토-test-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovsndngmaildetailcontroller)|https://youtu.be/G_Uy8O213Ww|
|2025-05-19 월|[test PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovSndngMailRegistController](#2025-05-19-월-test-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovsndngmailregistcontroller)|https://youtu.be/xiTBvUvN7C0|
|2025-05-20 화|[test PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovSmsBasicReceiver](#2025-05-20-화-test-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovsmsbasicreceiver)|https://youtu.be/IQ3zOwrFCZY|
|2025-05-21 수|[test PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovSmsBasicServiceImpl](#2025-05-21-수-test-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovsmsbasicserviceimpl)|https://youtu.be/8Ph-hZWA6Wg|
|2025-05-21 수|[PMD로 소프트웨어 보안약점 진단하고 제거하기-AltibaseClobStringTypeHandler](#2025-05-21-수-pmd로-소프트웨어-보안약점-진단하고-제거하기-altibaseclobstringtypehandler)|https://youtu.be/SQAP-I40f1M|
|2025-05-22 목|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovComCrossSiteHndlr](#2025-05-22-목-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovcomcrosssitehndlr)|https://youtu.be/7kw-9H2XlXo|
|2025-05-22 목|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovFileBasePathSecurityValidator](#2025-05-22-목-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovfilebasepathsecurityvalidator)|https://youtu.be/8m0WRoJzLp4|
|2025-05-23 금|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovWebApplicationInitializer](#2025-05-23-금-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovwebapplicationinitializer)|https://youtu.be/OkgssPwyuVw|
|2025-05-23 금|[PMD로 소프트웨어 보안약점 진단하고 제거하기-HTMLTagFilter](#2025-05-23-금-pmd로-소프트웨어-보안약점-진단하고-제거하기-htmltagfilter)|https://youtu.be/hlnX-9TiIQM|
|2025-05-24 토|[PMD로 소프트웨어 보안약점 진단하고 제거하기-HTMLTagFilterRequestWrapper](#2025-05-24-토-pmd로-소프트웨어-보안약점-진단하고-제거하기-htmltagfilterrequestwrapper)|https://youtu.be/Fw6mtnStocg|
|2025-05-24 토|[PMD로 소프트웨어 보안약점 진단하고 제거하기-SessionTimeoutCookieFilter](#2025-05-24-토-pmd로-소프트웨어-보안약점-진단하고-제거하기-sessiontimeoutcookiefilter)|https://youtu.be/BmXPy9CBTMA|
|2025-05-24 토|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovSecurityMap](#2025-05-24-토-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovsecuritymap)|https://youtu.be/P-q1ZJqcSCQ|
|2025-05-26 월|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovFileMngUtil](#2025-05-26-월-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovfilemngutil)|https://youtu.be/hRu1nHvmtQw|
|2025-05-26 월|[PMD로 소프트웨어 보안약점 진단하고 제거하기-FileSystemUtils](#2025-05-26-월-pmd로-소프트웨어-보안약점-진단하고-제거하기-filesystemutils)|https://youtu.be/qb3lz0BRXeU|
|2025-05-27 화|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovComAbstractDAO](#2025-05-27-화-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovcomabstractdao)|https://youtu.be/hXw00NoOopE|
|2025-05-27 화|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovBasicLogger](#2025-05-27-화-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovbasiclogger)|https://youtu.be/gN0Ski5ZugI|
|2025-05-28 수|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovMybatisUtil](#2025-05-28-수-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovmybatisutil)|https://youtu.be/ViTCmA0KTtc|
|2025-05-28 수|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovResourceCloseHelper](#2025-05-28-수-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovresourceclosehelper)|https://youtu.be/FRIrJOg2FPU|
|2025-05-28 수|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovUrlRewriteFilter](#2025-05-28-수-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovurlrewritefilter)|https://youtu.be/K6cRxs8j5xI|
|2025-05-29 목|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovWildcardReloadableResourceBundleMessageSource](#2025-05-29-목-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovwildcardreloadableresourcebundlemessagesource)|https://youtu.be/lNN2MGmdMXI|
|2025-05-29 목|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovBindingInitializer](#2025-05-29-목-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovbindinginitializer)|https://youtu.be/26a8ReH2KNI|
|2025-05-30 금|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovComAbstractController](#2025-05-30-금-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovcomabstractcontroller)|https://youtu.be/VSoss8QcG00|
|2025-05-30 금|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovComIndexController](#2025-05-30-금-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovcomindexcontroller)|https://youtu.be/1ZgoViUg3Pw|
|2025-05-31 토|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovFileDownloadController](#2025-05-31-토-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovfiledownloadcontroller)|https://youtu.be/arTaW68iz-M|
|2025-05-31 토|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovFileMngController](#2025-05-31-토-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovfilemngcontroller)|https://youtu.be/ETQCbnfjSbc|
|2025-06-03 화|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovImageProcessController](#2025-06-03-화-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovimageprocesscontroller)|https://youtu.be/e6S_0GQMWIE|
|2025-06-03 화|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovArticleServiceImpl](#2025-06-03-화-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovarticleserviceimpl)|https://youtu.be/k24Q6M1Ax9o|
|2025-06-03 화|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovArticleController](#2025-06-03-화-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovarticlecontroller)|https://youtu.be/tiCrmfVfdFk|
|2025-06-03 화|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovSndngMailRegistServiceImpl](#2025-06-03-화-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovsndngmailregistserviceimpl)|https://youtu.be/6TVGEgdeSLc|
|2025-06-05 목|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovSndngMailDetailController](#2025-06-05-목-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovsndngmaildetailcontroller)|https://youtu.be/16pyjT2dISc|
|2025-06-05 목|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovSndngMailRegistController](#2025-06-05-목-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovsndngmailregistcontroller)|https://youtu.be/CMZkRM1bZ_4|
|2025-06-05 목|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovSmsBasicReceiver](#2025-06-05-목-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovsmsbasicreceiver)|https://youtu.be/-09B8QU-8y8|
|2025-06-05 목|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovSmsBasicServiceImpl](#2025-06-05-목-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovsmsbasicserviceimpl)|https://youtu.be/Lxkp5KglvU0|
|2025-06-09 월|[PMD로 소프트웨어 보안약점 진단하고 제거하기-SmsBasicDAO](#2025-06-09-월-pmd로-소프트웨어-보안약점-진단하고-제거하기-smsbasicdao)|https://youtu.be/UOjvjtXKvKc|
|2025-06-09 월|[PMD로 소프트웨어 보안약점 진단하고 제거하기-SmsBasicDBUtil](#2025-06-09-월-pmd로-소프트웨어-보안약점-진단하고-제거하기-smsbasicdbutil)|https://youtu.be/-7YXr6-v38g|
|2025-06-10 화|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovDeptJobController](#2025-06-10-화-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovdeptjobcontroller)|https://youtu.be/dr6F_Ms3VWA|
|2025-06-10 화|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovDiaryManageController](#2025-06-10-화-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovdiarymanagecontroller)|https://youtu.be/CyHHsIOw40g|
|2025-06-11 수|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovLeaderSchdulServiceImpl](#2025-06-11-수-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovleaderschdulserviceimpl)|https://youtu.be/aNBW4wUuOgw|
|2025-06-11 수|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovMemoReprtController](#2025-06-11-수-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovmemoreprtcontroller)|https://youtu.be/tgQBzI1DTds|
|2025-06-11 수|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovDeptSchdulManageController](#2025-06-11-수-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovdeptschdulmanagecontroller)|https://youtu.be/7AOMzQK-7zA|
|2025-06-12 목|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovIndvdlSchdulManageController](#2025-06-12-목-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovindvdlschdulmanagecontroller)|https://youtu.be/8iRwby4YQ08|
|2025-06-12 목|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovWikMnthngReprtController](#2025-06-12-목-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovwikmnthngreprtcontroller)|https://youtu.be/rhfyEl_23i8|
|2025-06-13 금|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovKnoAppraisalServiceImpl](#2025-06-13-금-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovknoappraisalserviceimpl)|https://youtu.be/l42swd4KtUc|
|2025-06-13 금|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovKnoAppraisalController](#2025-06-13-금-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovknoappraisalcontroller)|https://youtu.be/co4NA0shLLs|
|2025-06-14 토|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovMapMaterialServiceImpl](#2025-06-14-토-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovmapmaterialserviceimpl)|https://youtu.be/mLc0AJhSHs4|
|2025-06-14 토|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovMapMaterialController](#2025-06-14-토-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovmapmaterialcontroller)|https://youtu.be/Sqb0bEWpuYg|
|2025-06-16 월|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovMapTeamServiceImpl](#2025-06-16-월-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovmapteamserviceimpl)|https://youtu.be/r-P56PuzLCU|
|2025-06-16 월|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovMapTeamController](#2025-06-16-월-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovmapteamcontroller)|https://youtu.be/CzY9_SBPNk4|
|2025-06-17 화|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovKnoManagementServiceImpl](#2025-06-17-화-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovknomanagementserviceimpl)|https://youtu.be/YL4EB_TidR4|
|2025-06-17 화|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovKnoPersonalController](#2025-06-17-화-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovknopersonalcontroller)|https://youtu.be/qZFCGXCCDLQ|
|2025-06-18 수|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovRequestOfferController](#2025-06-18-수-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovrequestoffercontroller)|https://youtu.be/S79vPc0nPnw|
|2025-06-18 수|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovKnoSpecialistServiceImpl](#2025-06-18-수-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovknospecialistserviceimpl)|https://youtu.be/llpujB-lj9Y|
|2025-06-19 목|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovKnoSpecialistController](#2025-06-19-목-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovknospecialistcontroller)|https://youtu.be/en2DHCDUOMU|
|2025-06-19 목|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovCaptchaController](#2025-06-19-목-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovcaptchacontroller)|https://youtu.be/PI8ZOV7Nsm4|
|2025-06-20 금|[PMD로 소프트웨어 보안약점 진단하고 제거하기-LdapObject](#2025-06-20-금-pmd로-소프트웨어-보안약점-진단하고-제거하기-ldapobject)|https://youtu.be/qfHDJyvzpm8|
|2025-06-20 금|[PMD로 소프트웨어 보안약점 진단하고 제거하기-LdapTreeObject](#2025-06-20-금-pmd로-소프트웨어-보안약점-진단하고-제거하기-ldaptreeobject)|https://youtu.be/tKrhZn-xr9A|
|2025-06-21 토|[PMD로 소프트웨어 보안약점 진단하고 제거하기-ObjectMapper](#2025-06-21-토-pmd로-소프트웨어-보안약점-진단하고-제거하기-objectmapper-immutablefield불변필드-uselessparentheses쓸모없는-괄호)|https://youtu.be/KClj7VG4GgI|
|2025-06-21 토|[PMD로 소프트웨어 보안약점 진단하고 제거하기-ChatServerEndPoint](#2025-06-21-토-pmd로-소프트웨어-보안약점-진단하고-제거하기-chatserverendpoint)|https://youtu.be/nj4alpeD2fw|
|2025-06-23 월|[PMD로 소프트웨어 보안약점 진단하고 제거하기-UsersServerEndPoint](#2025-06-23-월-pmd로-소프트웨어-보안약점-진단하고-제거하기-usersserverendpoint)|https://youtu.be/443X9J3y5Cs|
|2025-06-23 월|[PMD로 소프트웨어 보안약점 진단하고 제거하기-ChatServerAppConfig](#2025-06-23-월-pmd로-소프트웨어-보안약점-진단하고-제거하기-chatserverappconfig)|https://youtu.be/2VqOBW2n8g8|
|2025-06-24 화|[PMD로 소프트웨어 보안약점 진단하고 제거하기-MessageDecoder](#2025-06-24-화-pmd로-소프트웨어-보안약점-진단하고-제거하기-messagedecoder)|https://youtu.be/fSX5Ql72M7U|
|2025-06-24 화|[PMD로 소프트웨어 보안약점 진단하고 제거하기-MessageEncoder](#2025-06-24-화-pmd로-소프트웨어-보안약점-진단하고-제거하기-messageencoder)|https://youtu.be/U7T7achmMIE|
|2025-06-25 수|[PMD로 소프트웨어 보안약점 진단하고 제거하기-OAuthLogin](#2025-06-25-수-pmd로-소프트웨어-보안약점-진단하고-제거하기-oauthlogin)|https://youtu.be/5vsyxw9dVxw|
|2025-06-25 수|[PMD로 소프트웨어 보안약점 진단하고 제거하기-OAuthVO](#2025-06-25-수-pmd로-소프트웨어-보안약점-진단하고-제거하기-oauthvo)|https://youtu.be/-8cESlHOFKo|
|2025-06-26 목|[PMD로 소프트웨어 보안약점 진단하고 제거하기-GroupManageVO](#2025-06-26-목-pmd로-소프트웨어-보안약점-진단하고-제거하기-groupmanagevo)|https://youtu.be/_WbPENp2r8o|
|2025-06-26 목|[PMD로 소프트웨어 보안약점 진단하고 제거하기-RoleManageVO](#2025-06-26-목-pmd로-소프트웨어-보안약점-진단하고-제거하기-rolemanagevo)|https://youtu.be/HkAX_9ZuKCw|
|2025-06-27 금|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovSpringSecurityLogoutFilter](#2025-06-27-금-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovspringsecuritylogoutfilter)|https://youtu.be/5aTQVtaO8sc|
|2025-06-27 금|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovSpringSecurityLoginFilter](#2025-06-27-금-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovspringsecuritylogoutfilter)|https://youtu.be/ng8uuxPNF6k|
|2025-06-27 금|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovCntcInsttController](#2025-06-27-금-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovcntcinsttcontroller)|https://youtu.be/4a2DFGFL7Hs|
|2025-06-27 금|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovCntcMessageController](#2025-06-27-금-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovcntcmessagecontroller)|https://youtu.be/nA3oFksHaz4|
|2025-06-28 토|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovCntcSttusService](#2025-06-28-토-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovcntcsttusservice)|https://youtu.be/uVsoo36LZqM|
|2025-06-28 토|[PMD로 소프트웨어 보안약점 진단하고 제거하기-CntcSttusDAO](#2025-06-28-토-pmd로-소프트웨어-보안약점-진단하고-제거하기-cntcsttusdao)|https://youtu.be/7w2NFdOpifk|
|2025-06-30 월|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovCntcSttusServiceImpl](#2025-06-30-월-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovcntcsttusserviceimpl)|https://youtu.be/reoJWRcFNIs|
|2025-06-30 월|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovCntcSttusController](#2025-06-30-월-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovcntcsttuscontroller)|https://youtu.be/KLXXdl0FOfE|
|2025-07-01 화|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovSystemCntcController](#2025-07-01-화-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovsystemcntccontroller)|https://youtu.be/PUSD7aNuU9w|
|2025-07-01 화|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovBbsStatsController](#2025-07-01-화-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovbbsstatscontroller)|https://youtu.be/ZOSJlLA7xuM|
|2025-07-02 수|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovConectStatsController](#2025-07-02-수-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovconectstatscontroller)|https://youtu.be/baL4jxsBdm0|
|2025-07-02 수|[PMD로 소프트웨어 보안약점 진단하고 제거하기-ReprtStatsVO](#2025-07-02-수-pmd로-소프트웨어-보안약점-진단하고-제거하기-reprtstatsvo)|https://youtu.be/olP93J8bIUw|
|2025-07-03 목|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovScrinStatsController](#2025-07-03-목-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovscrinstatscontroller)|https://youtu.be/3SsOnf7yNXY|
|2025-07-03 목|[PMD로 소프트웨어 보안약점 진단하고 제거하기-BatchShellScriptJob](#2025-07-03-목-pmd로-소프트웨어-보안약점-진단하고-제거하기-batchshellscriptjob)|https://youtu.be/aSijAw5_Ezc|
|2025-07-04 금|[PMD로 소프트웨어 보안약점 진단하고 제거하기-RestdeVO](#2025-07-04-금-pmd로-소프트웨어-보안약점-진단하고-제거하기-restdevo)|https://youtu.be/Didmdr3BUuY|
|2025-07-04 금|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovCalRestdeManageController](#2025-07-04-금-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovcalrestdemanagecontroller)|https://youtu.be/fcIVEqknAMs|
|2025-07-05 토|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovAdministCodeRecptnServiceImpl](#2025-07-05-토-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovadministcoderecptnserviceimpl)|https://youtu.be/WIPkaXgPZrA|
|2025-07-05 토|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovCcmAdministCodeManageController](#2025-07-05-토-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovccmadministcodemanagecontroller)|https://youtu.be/Gc1fWFUBKQg|
|2025-07-07 월|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovCcmCmmnCodeManageController](#2025-07-07-월-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovccmcmmncodemanagecontroller)|https://youtu.be/6El8FHitsNQ|
|2025-07-07 월|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovCcmCmmnClCodeManageController](#2025-07-07-월-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovccmcmmnclcodemanagecontroller)||
|2025-07-08 화|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovCcmCmmnDetailCodeManageController](#2025-07-08-화-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovccmcmmndetailcodemanagecontroller)|https://youtu.be/RiNbBKOpWV0|
|2025-07-08 화|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovInsttCodeRecptnServiceImpl](#2025-07-08-화-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovinsttcoderecptnserviceimpl)|https://youtu.be/m5j52D20WV8|
|2025-07-09 수|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovCcmZipManageController](#2025-07-09-수-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovccmzipmanagecontroller)|https://youtu.be/fBhIg6ESjpw|
|2025-07-09 수|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovLoginLogAspect](#2025-07-09-수-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovloginlogaspect)|https://youtu.be/F8dmTNxxpsA|
|2025-07-10 목|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovLoginLogServiceImpl](#2025-07-10-목-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovloginlogserviceimpl)|https://youtu.be/7EeaUQ6qaJk|
|2025-07-10 목|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovLoginLogController](#2025-07-10-목-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovloginlogcontroller)|https://youtu.be/L0ls5iSwOpI|
|2025-07-11 금|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovSysLogAspect](#2025-07-11-금-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovsyslogaspect)|https://youtu.be/9ld-mU1qI_4|
|2025-07-11 금|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovSysLogServiceImpl](#2025-07-11-금-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovsyslogserviceimpl)|https://youtu.be/x-98wVEup4Q|
|2025-07-12 토|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovSysLogController](#2025-07-12-토-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovsyslogcontroller)|https://youtu.be/LYgywBOsMtE|
|2025-07-12 토|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovPrivacyLogAspect](#2025-07-12-토-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovprivacylogaspect)|https://youtu.be/hqFZu913zfQ|
|2025-07-14 월|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovSysHistoryController](#2025-07-14-월-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovsyshistorycontroller)|https://youtu.be/cVba60qk_Gw|
|2025-07-14 월|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovUserLogServiceImpl](#2025-07-14-월-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovuserlogserviceimpl)|https://youtu.be/ad2QrIodIAc|
|2025-07-15 화|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovWebLogInterceptor](#2025-07-15-화-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovwebloginterceptor)|https://youtu.be/5S0BhlJcLaw|
|2025-07-15 화|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovBkmkMenuManageservice](#2025-07-15-화-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovbkmkmenumanageservice)|https://youtu.be/UDy7oIrD39k|
|2025-07-16 수|[PMD로 소프트웨어 보안약점 진단하고 제거하기-MenuSiteMapVO](#2025-07-16-수-pmd로-소프트웨어-보안약점-진단하고-제거하기-menusitemapvo)|https://youtu.be/gapv-mNswLM|
|2025-07-16 수|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovMenuCreateManageServiceImpl](#2025-07-16-수-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovmenucreatemanageserviceimpl)|https://youtu.be/1NgTSXsOtHA|
|2025-07-17 목|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovMenuCreateManageController](#2025-07-17-목-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovmenucreatemanagecontroller)|https://youtu.be/NwHcS8UaA0Q|
|2025-07-17 목|[PMD로 소프트웨어 보안약점 진단하고 제거하기-MenuManageVO](#2025-07-17-목-pmd로-소프트웨어-보안약점-진단하고-제거하기-menumanagevo)|https://youtu.be/uMJOVISRvFs|
|2025-07-18 금|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovMenuManageServiceImpl](#2025-07-18-금-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovmenumanageserviceimpl)|https://youtu.be/DUsPMYDiIZ8|
|2025-07-18 금|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovMainMenuManageController](#2025-07-18-금-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovmainmenumanagecontroller)|https://youtu.be/CNyRV5kUwnQ|
|2025-07-19 토|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovMenuManageController](#2025-07-19-토-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovmenumanagecontroller)|https://youtu.be/5o0sOM2VECk|
|2025-07-19 토|[PMD로 소프트웨어 보안약점 진단하고 제거하기-ProgrmManageDtlVO](#2025-07-19-토-pmd로-소프트웨어-보안약점-진단하고-제거하기-progrmmanagedtlvo)|https://youtu.be/9e_zgyKfATE|
|2025-07-21 월|[PMD로 소프트웨어 보안약점 진단하고 제거하기-ProgrmManageVO](#2025-07-21-월-pmd로-소프트웨어-보안약점-진단하고-제거하기-progrmmanagevo)|https://youtu.be/X15nR35UApo|
|2025-07-21 월|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovProgrmManageController](#2025-07-21-월-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovprogrmmanagecontroller)|https://youtu.be/E7S8TRkwU2E|
|2025-07-22 화|[PMD로 소프트웨어 보안약점 진단하고 제거하기-BackupJob](#2025-07-22-화-pmd로-소프트웨어-보안약점-진단하고-제거하기-backupjob)|https://youtu.be/DC6-hQcDmkU|
|2025-07-22 화|[PMD로 소프트웨어 보안약점 진단하고 제거하기-NtwrkVO](#2025-07-22-화-pmd로-소프트웨어-보안약점-진단하고-제거하기-backupjob)|https://youtu.be/7dD1bMtTMu8|
|2025-07-23 수|[PMD로 소프트웨어 보안약점 진단하고 제거하기-NtwrkDAO](#2025-07-23-수-pmd로-소프트웨어-보안약점-진단하고-제거하기-ntwrkdao)|https://youtu.be/rbc6ys9-zxI|
|2025-07-23 수|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovNtwrkController](#2025-07-23-수-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovntwrkcontroller)|https://youtu.be/8M39KNYo8tY|
|2025-07-24 목|[PMD로 소프트웨어 보안약점 진단하고 제거하기-ServerEqpmnRelateVO](#2025-07-24-목-pmd로-소프트웨어-보안약점-진단하고-제거하기-servereqpmnrelatevo)|https://youtu.be/5px5Sx_Y7ko|
|2025-07-24 목|[PMD로 소프트웨어 보안약점 진단하고 제거하기-ServerEqpmnVO](#2025-07-24-목-pmd로-소프트웨어-보안약점-진단하고-제거하기-servereqpmnvo)|https://youtu.be/pNURRiMVOC8|
|2025-07-25 금|[PMD로 소프트웨어 보안약점 진단하고 제거하기-ServerVO](#2025-07-25-금-pmd로-소프트웨어-보안약점-진단하고-제거하기-servervo)|https://youtu.be/PrCFPXxqce8|
|2025-07-25 금|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovServerController](#2025-07-25-금-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovservercontroller)|https://youtu.be/2tQK8c8L5_w|
|2025-07-26 토|[PMD로 소프트웨어 보안약점 진단하고 제거하기-TroblProcessVO](#2025-07-26-토-pmd로-소프트웨어-보안약점-진단하고-제거하기-troblprocessvo)|https://youtu.be/fzXuNE4AJsY|
|2025-07-26 토|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovTroblProcessController](#2025-07-26-토-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovtroblprocesscontroller)|https://youtu.be/FdlVlebam_A|
|2025-07-28 월|[PMD로 소프트웨어 보안약점 진단하고 제거하기-TroblReqstVO](#2025-07-28-월-pmd로-소프트웨어-보안약점-진단하고-제거하기-troblreqstvo)|https://youtu.be/YSpMGK3xuH4|
|2025-07-28 월|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovTroblReqstController](#2025-07-28-월-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovtroblreqstcontroller)|https://youtu.be/kUIiUcC_BTY|
|2025-07-29 화|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovSSOLoginFilter](#2025-07-29-화-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovssologinfilter)|https://youtu.be/C5mp6oGvDPE|
|2025-07-29 화|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovSSOLogoutFilter](#2025-07-29-화-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovssologoutfilter)|https://youtu.be/HkSFNAGJKyg|
|2025-07-30 수|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovLoginPolicyFilter](#2025-07-30-수-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovloginpolicyfilter)|https://youtu.be/jIZ99HXbyxo|
|2025-07-30 수|[PMD로 소프트웨어 보안약점 진단하고 제거하기-LoginPolicyVO](#2025-07-30-수-pmd로-소프트웨어-보안약점-진단하고-제거하기-loginpolicyvo)|https://youtu.be/9HHXzPd_tyg|
|2025-07-31 목|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovLoginServiceImpl](#2025-07-31-목-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovloginserviceimpl)|https://youtu.be/mDUpGx6xTrk|
|2025-07-31 목|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovLoginController](#2025-07-31-목-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovlogincontroller)|https://youtu.be/u7pooWQmrao|
|2025-08-01 금|[PMD로 소프트웨어 보안약점 진단하고 제거하기-CmtManageVO](#2025-08-01-금-pmd로-소프트웨어-보안약점-진단하고-제거하기-cmtmanagevo)|https://youtu.be/V9qZu0p_EMI|
|2025-08-01 금|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovCmtManageServiceImpl](#2025-08-01-금-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovcmtmanageserviceimpl)|https://youtu.be/_BpxEStfWoc|
|2025-08-02 토|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovAnnvrsryManageServiceImpl](#2025-08-02-토-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovannvrsrymanageserviceimpl)|https://youtu.be/i2m06tOAQHM|
|2025-08-02 토|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovAnnvrsryManageController](#2025-08-02-토-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovannvrsrymanagecontroller)|https://youtu.be/XD-tHCE3y-g|
|2025-08-04 월|[PMD로 소프트웨어 보안약점 진단하고 제거하기-BannerVO](#2025-08-04-월-pmd로-소프트웨어-보안약점-진단하고-제거하기-bannervo)|https://youtu.be/QIOjiNdNc00|
|2025-08-04 월|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovBndtManageServiceImpl](#2025-08-04-월-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovbndtmanageserviceimpl)|https://youtu.be/m1hatwBmdCE|
|2025-08-05 화|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovBndtManageController](#2025-08-05-화-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovbndtmanagecontroller)|https://youtu.be/pmNJpwZEDZA|
|2025-08-05 화|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovEventCmpgnController](#2025-08-05-화-pmd로-소프트웨어-보안약점-진단하고-제거하기-egoveventcmpgncontroller)|https://youtu.be/LHzG5xEL8gQ|
|2025-08-06 수|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovEventManageController](#2025-08-06-수-pmd로-소프트웨어-보안약점-진단하고-제거하기-egoveventmanagecontroller)||
|2025-08-06 수|[PMD로 소프트웨어 보안약점 진단하고 제거하기-IntnetSvcGuidanceVO](#2025-08-06-수-pmd로-소프트웨어-보안약점-진단하고-제거하기-intnetsvcguidancevo)|https://youtu.be/OjWCbrHcM3w|
|2025-08-07 목|[PMD로 소프트웨어 보안약점 진단하고 제거하기-LoginScrinImageVO](#2025-08-07-목-pmd로-소프트웨어-보안약점-진단하고-제거하기-loginscrinimagevo)|https://youtu.be/pVJNpenqSX0|
|2025-08-07 목|[PMD로 소프트웨어 보안약점 진단하고 제거하기-MainImageVO](#2025-08-07-목-pmd로-소프트웨어-보안약점-진단하고-제거하기-mainimagevo)|https://youtu.be/0Jmcz2qlLJI|
|2025-08-08 금|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovMtgPlaceManageController](#2025-08-08-금-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovmtgplacemanagecontroller)|https://youtu.be/f7KjNx2d8gc|
|2025-08-08 금|[PMD로 소프트웨어 보안약점 진단하고 제거하기-NoteManageVO](#2025-08-08-금-pmd로-소프트웨어-보안약점-진단하고-제거하기-notemanagevo)|https://youtu.be/GTALAfaD7d0|
|2025-08-09 토|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovNoteManageController](#2025-08-09-토-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovnotemanagecontroller)|https://youtu.be/18S2FRKJcDY|
|2025-08-09 토|[PMD로 소프트웨어 보안약점 진단하고 제거하기-NoteRecptn](#2025-08-09-토-pmd로-소프트웨어-보안약점-진단하고-제거하기-noterecptn)|https://youtu.be/ckOuB_6gt7w|
|2025-08-11 월|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovNewsController](#2025-08-11-월-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovnewscontroller)|https://youtu.be/eBCKM9VkX5Y|
|2025-08-11 월|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovPopupManageController](#2025-08-11-월-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovpopupmanagecontroller)|https://youtu.be/1FQ1NHBuFCM|
|2025-08-12 화|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovRecomendSiteController](#2025-08-12-화-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovrecomendsitecontroller)|https://youtu.be/K4fnsGj8rb0|
|2025-08-12 화|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovRoughMapController](#2025-08-12-화-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovroughmapcontroller)|https://youtu.be/YYZ7IOZofsw|
|2025-08-13 수|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovRecentSrchwrdController](#2025-08-13-수-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovrecentsrchwrdcontroller)|https://youtu.be/J7dO0p_6ahI|
|2025-08-13 수|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovRssServiceImpl](#2025-08-13-수-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovrssserviceimpl)|https://youtu.be/ASa0sx46MjE|
|2025-08-14 목|[PMD로 소프트웨어 보안약점 진단하고 제거하기-RssTagManageDao](#2025-08-14-목-pmd로-소프트웨어-보안약점-진단하고-제거하기-rsstagmanagedao)|https://youtu.be/PNQlzO-4c0A|
|2025-08-15 금|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovRwardManageController](#2025-08-15-금-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovrwardmanagecontroller)|https://youtu.be/PKWGghjC2ds|
|2025-08-15 금|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovSiteController](#2025-08-15-금-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovsitecontroller)|https://youtu.be/6ScTsJWYdR0|
|2025-08-15 금|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovTwitterTrnsmitServiceImpl](#2025-08-15-금-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovtwittertrnsmitserviceimpl)|https://youtu.be/9y4WtvXTVyY|
|2025-08-16 토|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovTwitterController](#2025-08-16-토-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovtwittercontroller)|https://youtu.be/8_4jkH2p-Tw|
|2025-08-16 토|[PMD로 소프트웨어 보안약점 진단하고 제거하기-UserAbsnceVO](#2025-08-16-토-pmd로-소프트웨어-보안약점-진단하고-제거하기-userabsncevo)|https://youtu.be/c5kPQFsV_sU|
|2025-08-18 월|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovUnityLinkController](#2025-08-18-월-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovunitylinkcontroller)|https://youtu.be/wVy_cEEIhEo|
|2025-08-18 월|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovVcatnManageServiceImpl](#2025-08-18-월-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovvcatnmanageserviceimpl)|https://youtu.be/XwcFLQf9_Lg|
|2025-08-19 화|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovVcatnManageController](#2025-08-19-화-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovvcatnmanagecontroller)|https://youtu.be/TW-2k9OqElI|
|2025-08-19 화|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovWikiBookmarkServiceImpl](#2025-08-19-화-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovwikibookmarkserviceimpl)|https://youtu.be/-zS5SXUsTlE|
|2025-08-20 수|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovAdministrationWordController](#2025-08-20-수-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovadministrationwordcontroller)|https://youtu.be/QuBKCxXLcYk|
|2025-08-20 수|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovFaqController](#2025-08-20-수-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovfaqcontroller)|https://youtu.be/EL8avqOQCiI|
|2025-08-21 목|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovHpcmController](#2025-08-21-목-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovhpcmcontroller)|https://youtu.be/oFwVpJcynRI|
|2025-08-21 목|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovOnlineManualController](#2025-08-21-목-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovonlinemanualcontroller)|https://youtu.be/d2o8AVtVwIs|
|2025-08-22 금|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovQnaController](#2025-08-22-금-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovqnacontroller)|https://youtu.be/of-xlyCrSa8|
|2025-08-22 금|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovCnsltManageController](#2025-08-22-금-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovcnsltmanagecontroller)|https://youtu.be/TNq_wqdQIK0|
|2025-08-23 토|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovOnlinePollManageController](#2025-08-23-토-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovonlinepollmanagecontroller)|https://youtu.be/O7DYca9ILmM|
|2025-08-23 토|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovOnlinePollPartcptnController](#2025-08-23-토-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovonlinepollpartcptncontroller)|https://youtu.be/Wj7UJyMN_BM|
|2025-08-25 월|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovQustnrManageController](#2025-08-25-월-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovqustnrmanagecontroller)|https://youtu.be/RW_xZY4yrDU|
|2025-08-25 월|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovQustnrRespondInfoController](#2025-08-25-월-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovqustnrrespondinfocontroller)|https://youtu.be/CPR8c7VWxLA|
|2025-08-26 화|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovQustnrRespondManageController](#2025-08-26-화-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovqustnrrespondmanagecontroller)|https://youtu.be/HwH9p1UyowQ|
|2025-08-26 화|[PMD로 소프트웨어 보안약점 진단하고 제거하기-QustnrTmplatManageVO](#2025-08-26-화-pmd로-소프트웨어-보안약점-진단하고-제거하기-qustnrtmplatmanagevo)|https://youtu.be/Z8qWeftP4k4|
|2025-08-27 수|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovIndvdlInfoPolicyController](#2025-08-27-수-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovindvdlinfopolicycontroller)|https://youtu.be/K9ClNt3Sh7s|
|2025-08-27 수|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovStplatManageController](#2025-08-27-수-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovstplatmanagecontroller)|https://youtu.be/U-PEf-8h8ZE|
|2025-08-28 목|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovEntrprsManageController](#2025-08-28-목-pmd로-소프트웨어-보안약점-진단하고-제거하기-egoventrprsmanagecontroller)|https://youtu.be/SgOiQ5ogjSs|
|2025-08-28 목|[PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovMberManageController](#2025-08-28-목-pmd로-소프트웨어-보안약점-진단하고-제거하기-egovmbermanagecontroller)|https://youtu.be/J7D0VDeJggs|

<hr>

셀레늄 단위 테스트

셀레늄 화면 단위 테스트

셀레늄 화면 자동화 단위 테스트

셀레늄 웹 애플리케이션 자동화 단위 테스트

셀레늄은 웹 애플리케이션 자동화 및 테스트를 위한 포터블 프레임워크이다. 셀레늄은 테스트 스크립트 언어를 학습할 필요 없이 기능 테스트를 만들기 위한 플레이백 도구를 제공한다. 

- https://www.selenium.dev/
- https://www.selenium.dev/documentation/webdriver/
- https://www.selenium.dev/documentation/webdriver/getting_started/
- https://www.selenium.dev/documentation/webdriver/getting_started/using_selenium/

<hr>

## 셀레늄 단위 테스트-게시판관리

게시판생성관리 셀레늄 단위 테스트
- 게시판 목록조회
- 게시판 생성
- 게시판 수정

https://www.egovframe.go.kr/wiki/doku.php?id=egovframework:com:v4.3:cop:%EA%B2%8C%EC%8B%9C%ED%8C%90%EC%83%9D%EC%84%B1%EA%B4%80%EB%A6%AC

화면
- 목록 화면
- 등록 화면
- 상세 화면
- 수정 화면

<hr>

## 2025-04-19 토 PMD로 소프트웨어 보안약점 진단하고 제거하기

### 2025-04-20 일 test PMD-AltibaseClobStringTypeHandler
1. AltibaseClobStringTypeHandler
```
src/main/java/egovframework/com/cmm/AltibaseClobStringTypeHandler.java:86:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'read_data' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cmm/AltibaseClobStringTypeHandler.java:87:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'read_length' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cmm/AltibaseClobStringTypeHandler.java:93:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
```

https://github.com/LeeBaekHaeng25/egovframe-common-components-25/commits/feature/pmd/test/2025/04/20/

<hr>

### 2025-04-21 월 test PMD-EgovComCrossSiteHndlr
2. EgovComCrossSiteHndlr
```
src/main/java/egovframework/com/cmm/EgovComCrossSiteHndlr.java:48:	FieldNamingConventions:	FieldNamingConventions: 'final field' 의 변수 'm_sDiffChar' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cmm/EgovComCrossSiteHndlr.java:49:	FieldNamingConventions:	FieldNamingConventions: 'final field' 의 변수 'm_sArrDiffChar' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cmm/EgovComCrossSiteHndlr.java:103:	CloseResource:	CloseResource: 리소스 'JspWriter' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/EgovComCrossSiteHndlr.java:155:	CloseResource:	CloseResource: 리소스 'JspWriter' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/EgovComCrossSiteHndlr.java:162:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/cmm/EgovComCrossSiteHndlr.java:174:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/cmm/EgovComCrossSiteHndlr.java:185:	CloseResource:	CloseResource: 리소스 'JspWriter' 가 사용 후에 닫혔는지 확인필요
```

AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
```java
w.write(IOUtils.toString((Reader) obj));

String text = IOUtils.toString((Reader) obj);
writeEscapedXml(text.toCharArray(), text.length(), w);
```

<hr>

### 2025-04-22 화 test PMD-EgovWebApplicationInitializer

feature/pmd/test/2025/04/22

feature/pmd/test/EgovWebApplicationInitializer

PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovWebApplicationInitializer

PMD로 소프트웨어 보안약점 진단하고 제거하기-CloseResource

3. EgovWebApplicationInitializer
```
src/main/java/egovframework/com/cmm/config/EgovWebApplicationInitializer.java:75:	CloseResource:	CloseResource: 리소스 'XmlWebApplicationContext' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/config/EgovWebApplicationInitializer.java:86:	CloseResource:	CloseResource: 리소스 'XmlWebApplicationContext' 가 사용 후에 닫혔는지 확인필요
```

```java
 // NOPMD: CloseResource
```

<hr>

### 2025-04-23 수 test PMD-HTMLTagFilter

feature/pmd/test/HTMLTagFilter

PMD로 소프트웨어 보안약점 진단하고 제거하기-HTMLTagFilter

PMD로 소프트웨어 보안약점 진단하고 제거하기-UncommentedEmptyMethodBody

4. HTMLTagFilter
```
src/main/java/egovframework/com/cmm/filter/HTMLTagFilter.java:43:	UncommentedEmptyMethodBody:	UncommentedEmptyMethodBody: 빈 Method Body에 주석을 추가 할 것
```

https://github.com/LeeBaekHaeng25/egovframe-common-components-25/commits/feature/pmd/test/HTMLTagFilter/

<hr>

### 2025-04-24 목 test PMD로 소프트웨어 보안약점 진단하고 제거하기-HTMLTagFilterRequestWrapper

feature/pmd/test/HTMLTagFilterRequestWrapper

이클립스 > Source > Format

PMD로 소프트웨어 보안약점 진단하고 제거하기-SimplifyBooleanExpressions, AvoidReassigningParameters

5. HTMLTagFilterRequestWrapper
```
src/main/java/egovframework/com/cmm/filter/HTMLTagFilterRequestWrapper.java:117:	SimplifyBooleanExpressions:	SimplifyBooleanExpressions: boolean 사용 시 불필요한 비교 연산을 피하도록 함
src/main/java/egovframework/com/cmm/filter/HTMLTagFilterRequestWrapper.java:124:	SimplifyBooleanExpressions:	SimplifyBooleanExpressions: boolean 사용 시 불필요한 비교 연산을 피하도록 함
src/main/java/egovframework/com/cmm/filter/HTMLTagFilterRequestWrapper.java:154:	AvoidReassigningParameters:	AvoidReassigningParameters: 'value' 처럼 파라미터 값을 직접 변경하지 말 것
```

```java
 *   2025.04.24  이백행              PMD로 소프트웨어 보안약점 진단하고 제거하기-SimplifyBooleanExpressions, AvoidReassigningParameters
```

<hr>

### 2025-04-25 금 test PMD로 소프트웨어 보안약점 진단하고 제거하기-SessionTimeoutCookieFilter

feature/pmd/test/SessionTimeoutCookieFilter

이클립스 > Source > Format

PMD로 소프트웨어 보안약점 진단하고 제거하기-UncommentedEmptyMethodBody

```
src/main/java/egovframework/com/cmm/filter/SessionTimeoutCookieFilter.java:89:	UncommentedEmptyMethodBody:	UncommentedEmptyMethodBody: 빈 Method Body에 주석을 추가 할 것
```

```java
 *  2025.04.25   이백행            PMD로 소프트웨어 보안약점 진단하고 제거하기-UncommentedEmptyMethodBody
```

<hr>

### 2025-04-28 월 test PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovFileMngUtil

feature/pmd/test/EgovFileMngUtil

이클립스 > Source > Format

PMD로 소프트웨어 보안약점 진단하고 제거하기-FormalParameterNamingConventions, CloseResource, LocalVariableNamingConventions, AssignmentInOperand

```
src/main/java/egovframework/com/cmm/service/EgovFileMngUtil.java:75:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'KeyStr' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cmm/service/EgovFileMngUtil.java:147:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'KeyStr' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cmm/service/EgovFileMngUtil.java:219:	CloseResource:	CloseResource: 리소스 'InputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/service/EgovFileMngUtil.java:220:	CloseResource:	CloseResource: 리소스 'OutputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/service/EgovFileMngUtil.java:227:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_flag' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cmm/service/EgovFileMngUtil.java:239:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/cmm/service/EgovFileMngUtil.java:291:	CloseResource:	CloseResource: 리소스 'BufferedInputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/service/EgovFileMngUtil.java:292:	CloseResource:	CloseResource: 리소스 'BufferedOutputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/service/EgovFileMngUtil.java:299:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/cmm/service/EgovFileMngUtil.java:347:	CloseResource:	CloseResource: 리소스 'InputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/service/EgovFileMngUtil.java:348:	CloseResource:	CloseResource: 리소스 'OutputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/service/EgovFileMngUtil.java:368:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/cmm/service/EgovFileMngUtil.java:400:	CloseResource:	CloseResource: 리소스 'BufferedInputStream' 가 사용 후에 닫혔는지 확인필요
```

Java 7 이상이라면 try-with-resources를 사용해서 훨씬 깔끔하고 안전하게 리소스를 관리할 수 있습니다

```java
//IOUtils.copy(inputStream, outputStream);
FileCopyUtils.copy(in, out);
```

<hr>

### 2025-04-29 화 test PMD로 소프트웨어 보안약점 진단하고 제거하기-FileSystemUtils

feature/pmd/test/FileSystemUtils

이클립스 > Source > Format

PMD로 소프트웨어 보안약점 진단하고 제거하기-UselessParentheses, AvoidReassigningParameters, CloseResource, UnusedFormalParameter

```
src/main/java/egovframework/com/cmm/service/FileSystemUtils.java:190:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/cmm/service/FileSystemUtils.java:211:	AvoidReassigningParameters:	AvoidReassigningParameters: 'path' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/cmm/service/FileSystemUtils.java:302:	AvoidReassigningParameters:	AvoidReassigningParameters: 'path' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/cmm/service/FileSystemUtils.java:321:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/cmm/service/FileSystemUtils.java:393:	CloseResource:	CloseResource: 리소스 'InputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/service/FileSystemUtils.java:394:	CloseResource:	CloseResource: 리소스 'OutputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/service/FileSystemUtils.java:395:	CloseResource:	CloseResource: 리소스 'InputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/service/FileSystemUtils.java:396:	CloseResource:	CloseResource: 리소스 'BufferedReader' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/service/FileSystemUtils.java:444:	UnusedFormalParameter:	UnusedFormalParameter: 'cmdAttribs' 처럼  사용되지 않는  'method' 파라미터가 있음
```

<hr>

### 2025-04-30 수 test PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovComAbstractDAO

feature/pmd/test/EgovComAbstractDAO

이클립스 > Source > Format

PMD로 소프트웨어 보안약점 진단하고 제거하기-FieldNamingConventions

```
src/main/java/egovframework/com/cmm/service/impl/EgovComAbstractDAO.java:36:	FieldNamingConventions:	FieldNamingConventions: 'final field' 의 변수 'LOGGER' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

<hr>

### 2025-05-01 목 test PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovBasicLogger

feature/pmd/test/EgovBasicLogger

```
src/main/java/egovframework/com/cmm/util/EgovBasicLogger.java:27:	FieldNamingConventions:	FieldNamingConventions: 'constant' 의 변수 'ignoreLogger' 이  '[A-Z][A-Z_0-9]*'  로 시작함
src/main/java/egovframework/com/cmm/util/EgovBasicLogger.java:28:	FieldNamingConventions:	FieldNamingConventions: 'constant' 의 변수 'debugLogger' 이  '[A-Z][A-Z_0-9]*'  로 시작함
src/main/java/egovframework/com/cmm/util/EgovBasicLogger.java:29:	FieldNamingConventions:	FieldNamingConventions: 'constant' 의 변수 'infoLogger' 이  '[A-Z][A-Z_0-9]*'  로 시작함
```

FieldNamingConventions
- 필드 명명 규칙
- Field Naming Conventions
- 필드 명명 규칙

이클립스 > Source > Format

PMD로 소프트웨어 보안약점 진단하고 제거하기-FieldNamingConventions

<hr>

### 2025-05-02 금 test PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovMybatisUtil

feature/pmd/test/EgovMybatisUtil

이클립스 > Source > Format

PMD로 소프트웨어 보안약점 진단하고 제거하기-FieldNamingConventions(필드 명명 규칙), UselessParentheses(쓸모없는 괄호)

FieldNamingConventions
- 필드 명명 규칙
- Field Naming Conventions
- 필드 명명 규칙

UselessParentheses
- 쓸모없는 괄호
- Useless Parentheses
- 쓸모없는 괄호

```
src/main/java/egovframework/com/cmm/util/EgovMybatisUtil.java:33:	FieldNamingConventions:	FieldNamingConventions: 'constant' 의 변수 'logger' 이  '[A-Z][A-Z_0-9]*'  로 시작함
src/main/java/egovframework/com/cmm/util/EgovMybatisUtil.java:88:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/cmm/util/EgovMybatisUtil.java:92:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/cmm/util/EgovMybatisUtil.java:96:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/cmm/util/EgovMybatisUtil.java:101:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
```

@exception IllegalArgumentException 주석 제거

<hr>

### 2025-05-03 토 test PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovResourceCloseHelper

#### PMD로 소프트웨어 보안약점 진단 결과
```
src/main/java/egovframework/com/cmm/util/EgovResourceCloseHelper.java:35:	CloseResource:	CloseResource: 리소스 'Closeable' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/util/EgovResourceCloseHelper.java:112:	CloseResource:	CloseResource: 리소스 'Socket' 가 사용 후에 닫혔는지 확인필요
```

CloseResource 번역
- 닫기리소스
- Close Resource
- 리소스 닫기

#### 브랜치 생성
```
feature/pmd/test/EgovResourceCloseHelper
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

해결이 어려운 예외 상황에서 주석으로 PMD 무시하기
```java
 // NOPMD CloseResource
```

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-CloseResource(리소스 닫기)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.05.03  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-CloseResource(리소스 닫기)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

<hr>

### 2025-05-05 월 test PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovUrlRewriteFilter

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cmm/util/EgovUrlRewriteFilter.java:81:	StringInstantiation:	StringInstantiation: 필요없는 Instance가 생성되어 있음
src/main/java/egovframework/com/cmm/util/EgovUrlRewriteFilter.java:93:	StringInstantiation:	StringInstantiation: 필요없는 Instance가 생성되어 있음
```

StringInstantiation 번역
- 문자열 인스턴스화
- String Instantiation
- 문자열 인스턴스화

#### 브랜치 생성
```
feature/pmd/test/EgovUrlRewriteFilter
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-StringInstantiation(문자열 인스턴스화)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.05.05  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-StringInstantiation(문자열 인스턴스화)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

<hr>

### 2025-05-06 화 test PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovWildcardReloadableResourceBundleMessageSource

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cmm/util/EgovWildcardReloadableResourceBundleMessageSource.java:33:	ImmutableField:	ImmutableField: 생성자에서 Assign된 변수 'resourcePatternResolver' 를 Final로 선언하지 않았음
src/main/java/egovframework/com/cmm/util/EgovWildcardReloadableResourceBundleMessageSource.java:59:	UnnecessarySemicolon:	UnnecessarySemicolon: 필요없는 문장 (;)이 있음
```

ImmutableField 번역
- 불변필드
- Immutable Field
- 불변 필드

UnnecessarySemicolon 번역
- 불필요한 세미콜론
- Unnecessary Semicolon
- 불필요한 세미콜론

#### 브랜치 생성
```
feature/pmd/test/EgovWildcardReloadableResourceBundleMessageSource
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-ImmutableField(불변필드), UnnecessarySemicolon(불필요한 세미콜론)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.05.06  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-ImmutableField(불변필드), UnnecessarySemicolon(불필요한 세미콜론)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

<hr>

### 2025-05-07 수 test PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovBindingInitializer

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cmm/web/EgovBindingInitializer.java:33:	SimpleDateFormatNeedsLocale:	SimpleDateFormatNeedsLocale: SimpleDateFormat 인스턴스를 생성할때 Locale 을 지정하는 것이 바람직함
```

SimpleDateFormatNeedsLocale 번역
- 간단한 날짜 형식에 로캘이 필요합니다.
- Simple Date Format Needs Locale

#### 브랜치 생성
```
feature/pmd/test/EgovBindingInitializer
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

- Locale.KOREA
- Locale.getDefault()

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-SimpleDateFormatNeedsLocale(간단한 날짜 형식에 로캘이 필요합니다.)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.05.07  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-SimpleDateFormatNeedsLocale(간단한 날짜 형식에 로캘이 필요합니다.)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

<hr>

### 2025-05-08 목 test PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovComAbstractController

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cmm/web/EgovComAbstractController.java:31:	AbstractClassWithoutAbstractMethod:	AbstractClassWithoutAbstractMethod: Abstract Class내에  Abstract Method가 존재하지 않음
```

AbstractClassWithoutAbstractMethod 번역
- 추상 메서드가 없는 추상 클래스
- Abstract Class Without Abstract Method

#### 브랜치 생성
```
feature/pmd/test/EgovComAbstractController
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-AbstractClassWithoutAbstractMethod(추상 메서드가 없는 추상 클래스)
```

#### Commit and Push(커밋 및 푸시) 2

```java
 *   2025.05.08  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-AbstractClassWithoutAbstractMethod(추상 메서드가 없는 추상 클래스)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

<hr>

### 2025-05-09 금 test PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovComIndexController

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cmm/web/EgovComIndexController.java:89:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'exception block parameter' 의 변수 'Nfe' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

LocalVariableNamingConventions 번역
- 로컬 변수 명명 규칙
- Local Variable Naming Conventions
- 지역 변수 명명 규칙

#### 브랜치 생성
```
feature/pmd/test/EgovComIndexController
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(지역 변수 명명 규칙)
```

#### Commit and Push(커밋 및 푸시) 3

Commit Message(커밋 메시지)
```
commons-lang3-3.12.0.jar 와 중복되어 ajaxtags 의존성 commons-lang-2.4.jar 제외
```

```xml
		<!-- Ajax -->
		<dependency>
			<groupId>net.sourceforge.ajaxtags</groupId>
			<artifactId>ajaxtags-resources</artifactId>
			<version>1.5.7</version>
			<exclusions>
				<exclusion>
					<groupId>commons-lang</groupId>
					<artifactId>commons-lang</artifactId>
				</exclusion>
			</exclusions>
		</dependency>
```

#### Commit and Push(커밋 및 푸시) 4

```java
 *   2025.05.09  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(지역 변수 명명 규칙)
 *   2025.05.09  이백행          commons-lang3-3.12.0.jar 와 중복되어 ajaxtags 의존성 commons-lang-2.4.jar 제외
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

<hr>

### 2025-05-10 토 test PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovComUtlController

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cmm/web/EgovComUtlController.java:13:	UnnecessaryImport:	UnnecessaryImport: Unused import 'com.raonsecure.omnione.core.eoscommander.util.StringUtils'
```

UnnecessaryImport 번역
- 불필요한 수입
- Unnecessary Import
- 불필요한 주입

#### 브랜치 생성
```
feature/pmd/test/EgovComUtlController
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-UnnecessaryImport(불필요한 주입)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.05.10  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-UnnecessaryImport(불필요한 주입)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

<hr>

### 2025-05-12 월 test PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovFileDownloadController

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cmm/web/EgovFileDownloadController.java:79:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'param_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cmm/web/EgovFileDownloadController.java:124:	CloseResource:	CloseResource: 리소스 'BufferedInputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/web/EgovFileDownloadController.java:125:	CloseResource:	CloseResource: 리소스 'BufferedOutputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/web/EgovFileDownloadController.java:144:	CloseResource:	CloseResource: 리소스 'PrintWriter' 가 사용 후에 닫혔는지 확인필요
```

LocalVariableNamingConventions 번역
- 로컬 변수 명명 규칙
- Local Variable Naming Conventions
- 지역 변수 명명 규칙

CloseResource 번역
- 닫기 리소스
- Close Resource
- 리소스 닫기

#### 브랜치 생성
```
feature/pmd/test/EgovFileDownloadController
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(지역 변수 명명 규칙), CloseResource(리소스 닫기)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.05.12  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(지역 변수 명명 규칙), CloseResource(리소스 닫기)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

<hr>

### 2025-05-13 화 test PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovFileMngController

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cmm/web/EgovFileMngController.java:74:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'param_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cmm/web/EgovFileMngController.java:116:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'param_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

LocalVariableNamingConventions 번역
- 로컬 변수 명명 규칙
- Local Variable Naming Conventions
- 지역 변수 명명 규칙

#### 브랜치 생성
```
feature/pmd/test/EgovFileMngController
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(지역 변수 명명 규칙)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.05.13  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(지역 변수 명명 규칙)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

<hr>

### 2025-05-14 수 test PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovImageProcessController

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cmm/web/EgovImageProcessController.java:76:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'param_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cmm/web/EgovImageProcessController.java:112:	CloseResource:	CloseResource: 리소스 'FileInputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/web/EgovImageProcessController.java:114:	CloseResource:	CloseResource: 리소스 'BufferedInputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/web/EgovImageProcessController.java:128:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
```

LocalVariableNamingConventions 번역
- 로컬 변수 명명 규칙
- Local Variable Naming Conventions
- 지역 변수 명명 규칙

CloseResource 번역
- 닫기리소스
- Close Resource
- 리소스 닫기

AssignmentInOperand 번역
- Assignment In Operand
- 피연산자의 할당

#### 브랜치 생성

```
feature/pmd/test/EgovImageProcessController
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(지역 변수 명명 규칙), CloseResource(리소스 닫기), AssignmentInOperand(피연산자의 할당)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.05.14  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(지역 변수 명명 규칙), CloseResource(리소스 닫기), AssignmentInOperand(피연산자의 할당)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

검색
```
/cmm/fms/getImage.do
```

/egovframe-common-components-25/src/main/webapp/WEB-INF/jsp/egovframework/com/uss/ion/bnr/EgovBannerView.jsp
- 배너가 특정화면에 반영된 결과를 조회한다.
- /uss/ion/bnr/getBannerImage.do
- http://localhost:8080/egovframework-all-in-one/uss/ion/bnr/getBannerImage.do

/egovframe-common-components-25/src/main/webapp/WEB-INF/jsp/egovframework/com/uss/ion/lsi/EgovLoginScrinImageView.jsp
- 로그인화면이미지가 특정화면에 반영된 결과를 조회한다.
- /uss/ion/lsi/getLoginScrinImageResult.do
- http://localhost:8080/egovframework-all-in-one/uss/ion/lsi/getLoginScrinImageResult.do

/egovframe-common-components-25/src/main/webapp/WEB-INF/jsp/egovframework/com/uss/ion/msi/EgovMainImageView.jsp
- 메인화면이미지가 특정화면에 반영된 결과를 조회한다.
- /uss/ion/msi/getMainImageResult.do
- http://localhost:8080/egovframework-all-in-one/uss/ion/msi/getMainImageResult.do

/egovframe-common-components-25/src/main/webapp/WEB-INF/jsp/egovframework/com/uss/ion/mtg/EgovMtgPlaceImageDetail.jsp
- 등록된 회의실관리의 이미지 상세정보를 조회한다.
- /uss/ion/mtg/selectMtgPlaceImage.do
- http://localhost:8080/egovframework-all-in-one/uss/ion/mtg/selectMtgPlaceImage.do

<hr>

### 2025-05-15 목 test PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovArticleController

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cop/bbs/web/EgovArticleController.java:428:	AvoidReassigningParameters:	AvoidReassigningParameters: 'boardVO' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/cop/bbs/web/EgovArticleController.java:669:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

AvoidReassigningParameters 번역
- 매개변수 재할당을 피하세요
- Avoid Reassigning Parameters
- 매개변수 재할당 방지

LocalVariableNamingConventions 번역
- 로컬 변수 명명 규칙
- Local Variable Naming Conventions
- 지역 변수 명명 규칙

#### 브랜치 생성

```
feature/pmd/test/EgovArticleController
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-AvoidReassigningParameters(매개변수 재할당 방지), LocalVariableNamingConventions(지역 변수 명명 규칙)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.05.15  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-AvoidReassigningParameters(매개변수 재할당 방지), LocalVariableNamingConventions(지역 변수 명명 규칙)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

<hr>

### 2025-05-16 금 test PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovSndngMailRegistServiceImpl

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cop/ems/service/impl/EgovSndngMailRegistServiceImpl.java:160:	SimplifyBooleanExpressions:	SimplifyBooleanExpressions: boolean 사용 시 불필요한 비교 연산을 피하도록 함
```

SimplifyBooleanExpressions 번역
- Simplify Boolean Expressions
- 부울 표현식 단순화


#### 브랜치 생성

```
feature/pmd/test/EgovSndngMailRegistServiceImpl
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-SimplifyBooleanExpressions(부울 표현식 단순화)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.05.16  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-SimplifyBooleanExpressions(부울 표현식 단순화)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

<hr>

### 2025-05-17 토 test PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovSndngMailDetailController

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cop/ems/web/EgovSndngMailDetailController.java:158:	CloseResource:	CloseResource: 리소스 'PrintWriter' 가 사용 후에 닫혔는지 확인필요
```

CloseResource 번역
- 닫기 리소스
- Close Resource
- 리소스 닫기

#### 브랜치 생성

```
feature/pmd/test/EgovSndngMailDetailController
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-CloseResource(리소스 닫기)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.05.17  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-CloseResource(리소스 닫기)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

<hr>

### 2025-05-19 월 test PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovSndngMailRegistController

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cop/ems/web/EgovSndngMailRegistController.java:102:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/ems/web/EgovSndngMailRegistController.java:103:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

LocalVariableNamingConventions 번역
- 로컬 변수 명명 규칙
- Local Variable Naming Conventions
- 지역 변수 명명 규칙

#### 브랜치 생성

```
feature/pmd/test/EgovSndngMailRegistController
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(지역 변수 명명 규칙)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.05.19  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(지역 변수 명명 규칙)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

<hr>

### 2025-05-21 수 test PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovSmsBasicServiceImpl

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cop/sms/service/impl/EgovSmsBasicServiceImpl.java:36:	ImmutableField:	ImmutableField: 생성자에서 Assign된 변수 'smsDao' 를 Final로 선언하지 않았음
src/main/java/egovframework/com/cop/sms/service/impl/EgovSmsBasicServiceImpl.java:76:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'FILE_SEPARATOR' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

ImmutableField 번역
- 불변필드
- Immutable Field
- 불변 필드

LocalVariableNamingConventions 번역
- 로컬 변수 명명 규칙
- Local Variable Naming Conventions
- 지역 변수 명명 규칙

#### 브랜치 생성

```
feature/pmd/test/EgovSmsBasicServiceImpl
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-ImmutableField(불변필드), LocalVariableNamingConventions(지역 변수 명명 규칙)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.05.21  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-ImmutableField(불변필드), LocalVariableNamingConventions(지역 변수 명명 규칙)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

<hr>

### 2025-05-21 수 PMD로 소프트웨어 보안약점 진단하고 제거하기-AltibaseClobStringTypeHandler

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cmm/AltibaseClobStringTypeHandler.java:85:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'read_data' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cmm/AltibaseClobStringTypeHandler.java:86:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'read_length' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cmm/AltibaseClobStringTypeHandler.java:92:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
```

LocalVariableNamingConventions 번역
- 로컬 변수 명명 규칙
- LocalVariableNamingConventions
- 지역 변수 명명 규칙

AssignmentInOperand 번역
- 피연산자의 할당
- Assignment In Operand

#### 브랜치 생성

```
feature/pmd/AltibaseClobStringTypeHandler
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(지역 변수 명명 규칙), AssignmentInOperand(피연산자의 할당)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.05.21  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(지역 변수 명명 규칙), AssignmentInOperand(피연산자의 할당)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

LOGGER 제거

https://github.com/eGovFramework/egovframe-common-components/pull/525

<hr>

### 2025-05-22 목 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovComCrossSiteHndlr

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cmm/EgovComCrossSiteHndlr.java:48:	FieldNamingConventions:	FieldNamingConventions: 'final field' 의 변수 'm_sDiffChar' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cmm/EgovComCrossSiteHndlr.java:49:	FieldNamingConventions:	FieldNamingConventions: 'final field' 의 변수 'm_sArrDiffChar' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cmm/EgovComCrossSiteHndlr.java:103:	CloseResource:	CloseResource: 리소스 'JspWriter' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/EgovComCrossSiteHndlr.java:155:	CloseResource:	CloseResource: 리소스 'JspWriter' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/EgovComCrossSiteHndlr.java:162:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/cmm/EgovComCrossSiteHndlr.java:174:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/cmm/EgovComCrossSiteHndlr.java:185:	CloseResource:	CloseResource: 리소스 'JspWriter' 가 사용 후에 닫혔는지 확인필요
```

FieldNamingConventions 번역
- 필드 명명 규칙
- Field Naming Conventions

CloseResource 번역
- 닫기리소스
- Close Resource
- 리소스 닫기

AssignmentInOperand 번역
- 피연산자의 할당
- Assignment In Operand

#### 브랜치 생성

```
feature/pmd/EgovComCrossSiteHndlr
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-FieldNamingConventions(필드 명명 규칙), CloseResource(리소스 닫기), AssignmentInOperand(피연산자의 할당)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.05.22  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-FieldNamingConventions(필드 명명 규칙), CloseResource(리소스 닫기), AssignmentInOperand(피연산자의 할당)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

egovc File Search 파일 검색
- egovc.tld
- ${egovc:
- ${egovc:out 없음

NOPMD comment
- // NOPMD - CloseResource
- Alternatively, you can tell PMD to ignore a specific line by using the “NOPMD” marker in a comment, like this:
  - 또는 다음과 같이 주석에 "NOPMD" 마커를 사용하여 PMD가 특정 줄을 무시하도록 지시할 수 있습니다.
- https://pmd.github.io/pmd/pmd_userdocs_suppressing_warnings.html#nopmd-comment

https://github.com/eGovFramework/egovframe-common-components/pull/526

<hr>

### 2025-05-22 목 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovFileBasePathSecurityValidator

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cmm/aop/EgovFileBasePathSecurityValidator.java:48:	InefficientEmptyStringCheck:	InefficientEmptyStringCheck: Empty String 을 체크하기 위해 String.trim().length() /String.trim().isEmpty() 을 사용하는 것은 피하도록 함
src/main/java/egovframework/com/cmm/aop/EgovFileBasePathSecurityValidator.java:77:	SimplifyBooleanExpressions:	SimplifyBooleanExpressions: boolean 사용 시 불필요한 비교 연산을 피하도록 함
```

InefficientEmptyStringCheck 번역
- 비효율적인 빈 문자열 검사
- Inefficient Empty String Check

SimplifyBooleanExpressions 번역
- 부울 표현식 단순화
- Simplify Boolean Expressions

#### 브랜치 생성

```
feature/pmd/EgovFileBasePathSecurityValidator
```

EgovFileBasePathSecurityValidator Class 구현 단위 테스트 추가

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-InefficientEmptyStringCheck(비효율적인 빈 문자열 검사), SimplifyBooleanExpressions(부울 표현식 단순화)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.05.22  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-InefficientEmptyStringCheck(비효율적인 빈 문자열 검사), SimplifyBooleanExpressions(부울 표현식 단순화)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

if (log.isErrorEnabled()) { 추가

https://github.com/eGovFramework/egovframe-common-components/pull/527

<hr>

### 2025-05-23 금 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovWebApplicationInitializer

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cmm/config/EgovWebApplicationInitializer.java:75:	CloseResource:	CloseResource: 리소스 'XmlWebApplicationContext' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/config/EgovWebApplicationInitializer.java:86:	CloseResource:	CloseResource: 리소스 'XmlWebApplicationContext' 가 사용 후에 닫혔는지 확인필요
```

CloseResource 번역
- 닫기 리소스
- Close Resource
- 리소스 닫기

#### 브랜치 생성

```
feature/pmd/EgovWebApplicationInitializer
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-CloseResource(리소스 닫기)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.05.23  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-CloseResource(리소스 닫기)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

https://github.com/eGovFramework/egovframe-common-components/pull/528

<hr>

### 2025-05-23 금 PMD로 소프트웨어 보안약점 진단하고 제거하기-HTMLTagFilter

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cmm/filter/HTMLTagFilter.java:43:	UncommentedEmptyMethodBody:	UncommentedEmptyMethodBody: 빈 Method Body에 주석을 추가 할 것
```

UncommentedEmptyMethodBody 번역
- 주석 처리되지 않은 EmptyMethodBody
- Uncommented Empty Method Body
- 주석 처리되지 않은 빈 메서드 본문

#### 브랜치 생성

```
feature/pmd/HTMLTagFilter
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-UncommentedEmptyMethodBody(주석 처리되지 않은 빈 메서드 본문)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.05.23  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-UncommentedEmptyMethodBody(주석 처리되지 않은 빈 메서드 본문)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

https://github.com/eGovFramework/egovframe-common-components/pull/529

<hr>

### 2025-05-24 토 PMD로 소프트웨어 보안약점 진단하고 제거하기-HTMLTagFilterRequestWrapper

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cmm/filter/HTMLTagFilterRequestWrapper.java:117:	SimplifyBooleanExpressions:	SimplifyBooleanExpressions: boolean 사용 시 불필요한 비교 연산을 피하도록 함
src/main/java/egovframework/com/cmm/filter/HTMLTagFilterRequestWrapper.java:124:	SimplifyBooleanExpressions:	SimplifyBooleanExpressions: boolean 사용 시 불필요한 비교 연산을 피하도록 함
src/main/java/egovframework/com/cmm/filter/HTMLTagFilterRequestWrapper.java:154:	AvoidReassigningParameters:	AvoidReassigningParameters: 'value' 처럼 파라미터 값을 직접 변경하지 말 것
```

SimplifyBooleanExpressions 번역
- Simplify Boolean Expressions
- 부울 표현식 단순화

AvoidReassigningParameters 번역
- 매개변수 재할당을 피하세요
- Avoid Reassigning Parameters
- 매개변수 재할당 방지

#### 브랜치 생성

```
feature/pmd/HTMLTagFilterRequestWrapper
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-SimplifyBooleanExpressions(부울 표현식 단순화), AvoidReassigningParameters(매개변수 재할당 방지)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.05.24  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-SimplifyBooleanExpressions(부울 표현식 단순화), AvoidReassigningParameters(매개변수 재할당 방지)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

https://github.com/eGovFramework/egovframe-common-components/pull/530

<hr>

### 2025-05-24 토 PMD로 소프트웨어 보안약점 진단하고 제거하기-SessionTimeoutCookieFilter

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cmm/filter/SessionTimeoutCookieFilter.java:89:	UncommentedEmptyMethodBody:	UncommentedEmptyMethodBody: 빈 Method Body에 주석을 추가 할 것
```

UncommentedEmptyMethodBody 번역
- 주석 처리되지 않은 EmptyMethodBody
- Uncommented Empty Method Body
- 주석 처리되지 않은 빈 메서드 본문

#### 브랜치 생성

```
feature/pmd/SessionTimeoutCookieFilter
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-UncommentedEmptyMethodBody(주석 처리되지 않은 빈 메서드 본문)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.05.24  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-UncommentedEmptyMethodBody(주석 처리되지 않은 빈 메서드 본문)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

https://github.com/eGovFramework/egovframe-common-components/pull/531

<hr>

### 2025-05-24 토 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovSecurityMap

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cmm/resolver/EgovSecurityMap.java:41:	SwitchStmtsShouldHaveDefault:	SwitchStmtsShouldHaveDefault: Switch구문에는 반드시 default label이 있어야 함
src/main/java/egovframework/com/cmm/resolver/EgovSecurityMap.java:47:	AvoidReassigningParameters:	AvoidReassigningParameters: 'value' 처럼 파라미터 값을 직접 변경하지 말 것
```

SwitchStmtsShouldHaveDefault 번역
- Switch Stmts Should Have Default
- 스위치 명령문에는 기본값이 있어야 합니다.

AvoidReassigningParameters 번역
- 매개변수 재할당을 피하세요
- Avoid Reassigning Parameters
- 매개변수 재할당 방지

#### 브랜치 생성

```
feature/pmd/EgovSecurityMap
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-SwitchStmtsShouldHaveDefault(스위치 명령문에는 기본값이 있어야 합니다.), AvoidReassigningParameters(매개변수 재할당 방지)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.05.24  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-SwitchStmtsShouldHaveDefault(스위치 명령문에는 기본값이 있어야 합니다.), AvoidReassigningParameters(매개변수 재할당 방지)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

LOGGER 를 @Slf4j 로 수정

https://github.com/eGovFramework/egovframe-common-components/pull/532

<hr>

### 2025-05-26 월 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovFileMngUtil

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cmm/service/EgovFileMngUtil.java:76:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'KeyStr' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cmm/service/EgovFileMngUtil.java:148:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'KeyStr' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cmm/service/EgovFileMngUtil.java:220:	CloseResource:	CloseResource: 리소스 'InputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/service/EgovFileMngUtil.java:221:	CloseResource:	CloseResource: 리소스 'OutputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/service/EgovFileMngUtil.java:228:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_flag' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cmm/service/EgovFileMngUtil.java:240:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/cmm/service/EgovFileMngUtil.java:293:	CloseResource:	CloseResource: 리소스 'BufferedInputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/service/EgovFileMngUtil.java:294:	CloseResource:	CloseResource: 리소스 'BufferedOutputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/service/EgovFileMngUtil.java:301:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/cmm/service/EgovFileMngUtil.java:349:	CloseResource:	CloseResource: 리소스 'InputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/service/EgovFileMngUtil.java:350:	CloseResource:	CloseResource: 리소스 'OutputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/service/EgovFileMngUtil.java:370:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/cmm/service/EgovFileMngUtil.java:403:	CloseResource:	CloseResource: 리소스 'BufferedInputStream' 가 사용 후에 닫혔는지 확인필요
```

FormalParameterNamingConventions 번역
- 형식 매개변수 명명 규칙
- Formal Parameter Naming Conventions
- 공식 매개변수 명명 규칙

CloseResource 번역
- 닫기 리소스
- Close Resource
- 리소스 닫기

LocalVariableNamingConventions 번역
- 로컬 변수 명명 규칙
- Local Variable Naming Conventions
- 지역 변수 명명 규칙

AssignmentInOperand 번역
- Assignment In Operand
- 피연산자의 할당

#### 브랜치 생성

```
feature/pmd/EgovFileMngUtil
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-FormalParameterNamingConventions(공식 매개변수 명명 규칙), CloseResource(리소스 닫기), LocalVariableNamingConventions(지역 변수 명명 규칙), AssignmentInOperand(피연산자의 할당)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.05.26  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-FormalParameterNamingConventions(공식 매개변수 명명 규칙), CloseResource(리소스 닫기), LocalVariableNamingConventions(지역 변수 명명 규칙), AssignmentInOperand(피연산자의 할당)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

https://github.com/eGovFramework/egovframe-common-components/pull/533

<hr>

### 2025-05-26 월 PMD로 소프트웨어 보안약점 진단하고 제거하기-FileSystemUtils

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cmm/service/FileSystemUtils.java:190:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/cmm/service/FileSystemUtils.java:211:	AvoidReassigningParameters:	AvoidReassigningParameters: 'path' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/cmm/service/FileSystemUtils.java:302:	AvoidReassigningParameters:	AvoidReassigningParameters: 'path' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/cmm/service/FileSystemUtils.java:321:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/cmm/service/FileSystemUtils.java:393:	CloseResource:	CloseResource: 리소스 'InputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/service/FileSystemUtils.java:394:	CloseResource:	CloseResource: 리소스 'OutputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/service/FileSystemUtils.java:395:	CloseResource:	CloseResource: 리소스 'InputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/service/FileSystemUtils.java:396:	CloseResource:	CloseResource: 리소스 'BufferedReader' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/service/FileSystemUtils.java:444:	UnusedFormalParameter:	UnusedFormalParameter: 'cmdAttribs' 처럼  사용되지 않는  'method' 파라미터가 있음
```

UselessParentheses 번역
- 쓸모없는 괄호
- Useless Parentheses

AvoidReassigningParameters 번역
- 매개변수 재할당을 피하세요
- Avoid Reassigning Parameters
- 매개변수 재할당 방지

CloseResource 번역
- 닫기 리소스
- Close Resource
- 리소스 닫기

UnusedFormalParameter 번역
- 사용되지 않는 형식 매개변수
- Unused Formal Parameter

#### 브랜치 생성

```
feature/pmd/FileSystemUtils
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-UselessParentheses(쓸모없는 괄호), AvoidReassigningParameters(매개변수 재할당 방지), CloseResource(리소스 닫기), UnusedFormalParameter(사용되지 않는 형식 매개변수)
```

https://github.com/eGovFramework/egovframe-common-components/pull/534

<hr>

### 2025-05-27 화 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovComAbstractDAO

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cmm/service/impl/EgovComAbstractDAO.java:36:	FieldNamingConventions:	FieldNamingConventions: 'final field' 의 변수 'LOGGER' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

FieldNamingConventions 번역
- 필드 명명 규칙
- Field Naming Conventions

#### 브랜치 생성

```
feature/pmd/EgovComAbstractDAO
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-FieldNamingConventions(필드 명명 규칙)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.05.27  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-FieldNamingConventions(필드 명명 규칙)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

https://github.com/eGovFramework/egovframe-common-components/pull/535

<hr>

### 2025-05-27 화 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovBasicLogger

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cmm/util/EgovBasicLogger.java:27:	FieldNamingConventions:	FieldNamingConventions: 'constant' 의 변수 'ignoreLogger' 이  '[A-Z][A-Z_0-9]*'  로 시작함
src/main/java/egovframework/com/cmm/util/EgovBasicLogger.java:28:	FieldNamingConventions:	FieldNamingConventions: 'constant' 의 변수 'debugLogger' 이  '[A-Z][A-Z_0-9]*'  로 시작함
src/main/java/egovframework/com/cmm/util/EgovBasicLogger.java:29:	FieldNamingConventions:	FieldNamingConventions: 'constant' 의 변수 'infoLogger' 이  '[A-Z][A-Z_0-9]*'  로 시작함
```

FieldNamingConventions 번역
- 필드 명명 규칙
- Field Naming Conventions

#### 브랜치 생성

```
feature/pmd/EgovBasicLogger
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-FieldNamingConventions(필드 명명 규칙)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.05.27  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-FieldNamingConventions(필드 명명 규칙)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

https://github.com/eGovFramework/egovframe-common-components/pull/536

<hr>

### 2025-05-28 수 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovMybatisUtil

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cmm/util/EgovMybatisUtil.java:33:	FieldNamingConventions:	FieldNamingConventions: 'constant' 의 변수 'logger' 이  '[A-Z][A-Z_0-9]*'  로 시작함
src/main/java/egovframework/com/cmm/util/EgovMybatisUtil.java:88:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/cmm/util/EgovMybatisUtil.java:92:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/cmm/util/EgovMybatisUtil.java:96:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/cmm/util/EgovMybatisUtil.java:101:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
```

FieldNamingConventions 번역
- 필드 명명 규칙
- Field Naming Conventions

UselessParentheses 번역
- 쓸모없는 괄호
- Useless Parentheses

#### 브랜치 생성

```
feature/pmd/EgovMybatisUtil
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-FieldNamingConventions(필드 명명 규칙), UselessParentheses(쓸모없는 괄호)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.05.28  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-FieldNamingConventions(필드 명명 규칙), UselessParentheses(쓸모없는 괄호)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

https://github.com/eGovFramework/egovframe-common-components/pull/537

<hr>

### 2025-05-28 수 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovResourceCloseHelper

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cmm/util/EgovResourceCloseHelper.java:35:	CloseResource:	CloseResource: 리소스 'Closeable' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/util/EgovResourceCloseHelper.java:112:	CloseResource:	CloseResource: 리소스 'Socket' 가 사용 후에 닫혔는지 확인필요
```

CloseResource 번역
- 닫기 리소스
- Close Resource
- 리소스 닫기

#### 브랜치 생성

```
feature/pmd/EgovResourceCloseHelper
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-CloseResource(리소스 닫기)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.05.28  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-CloseResource(리소스 닫기)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

https://github.com/eGovFramework/egovframe-common-components/pull/538

<hr>

### 2025-05-28 수 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovUrlRewriteFilter

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cmm/util/EgovUrlRewriteFilter.java:81:	StringInstantiation:	StringInstantiation: 필요없는 Instance가 생성되어 있음
src/main/java/egovframework/com/cmm/util/EgovUrlRewriteFilter.java:93:	StringInstantiation:	StringInstantiation: 필요없는 Instance가 생성되어 있음
```

StringInstantiation 번역
- 문자열 인스턴스화
- String Instantiation

#### 브랜치 생성

```
feature/pmd/EgovUrlRewriteFilter
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-StringInstantiation(문자열 인스턴스화)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.05.28  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-StringInstantiation(문자열 인스턴스화)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

https://github.com/eGovFramework/egovframe-common-components/pull/539

<hr>

### 2025-05-29 목 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovWildcardReloadableResourceBundleMessageSource

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cmm/util/EgovWildcardReloadableResourceBundleMessageSource.java:33:	ImmutableField:	ImmutableField: 생성자에서 Assign된 변수 'resourcePatternResolver' 를 Final로 선언하지 않았음
src/main/java/egovframework/com/cmm/util/EgovWildcardReloadableResourceBundleMessageSource.java:59:	UnnecessarySemicolon:	UnnecessarySemicolon: 필요없는 문장 (;)이 있음
```

ImmutableField 번역
- 불변필드
- Immutable Field
- 변경 불가능한 필드

UnnecessarySemicolon 번역
- 불필요한 세미콜론
- Unnecessary Semicolon

#### 브랜치 생성

```
feature/pmd/EgovWildcardReloadableResourceBundleMessageSource
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-ImmutableField(불변필드), UnnecessarySemicolon(불필요한 세미콜론)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.05.29  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-ImmutableField(불변필드), UnnecessarySemicolon(불필요한 세미콜론)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

https://github.com/eGovFramework/egovframe-common-components/pull/540

<hr>

### 2025-05-29 목 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovBindingInitializer

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cmm/web/EgovBindingInitializer.java:34:	SimpleDateFormatNeedsLocale:	SimpleDateFormatNeedsLocale: SimpleDateFormat 인스턴스를 생성할때 Locale 을 지정하는 것이 바람직함
```

SimpleDateFormatNeedsLocale 번역
- Simple Date Format Needs Locale
- 간단한 날짜 형식에 로캘이 필요합니다.

#### 브랜치 생성

```
feature/pmd/EgovBindingInitializer
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-SimpleDateFormatNeedsLocale(간단한 날짜 형식에 로캘이 필요합니다.)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.05.29  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-SimpleDateFormatNeedsLocale(간단한 날짜 형식에 로캘이 필요합니다.)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

https://github.com/eGovFramework/egovframe-common-components/pull/541

<hr>

### 2025-05-30 금 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovComAbstractController

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cmm/web/EgovComAbstractController.java:31:	AbstractClassWithoutAbstractMethod:	AbstractClassWithoutAbstractMethod: Abstract Class내에  Abstract Method가 존재하지 않음
```

AbstractClassWithoutAbstractMethod 번역
- 추상 메서드가 없는 추상 클래스
- Abstract Class Without Abstract Method

#### 브랜치 생성

```
feature/pmd/EgovComAbstractController
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-AbstractClassWithoutAbstractMethod(추상 메서드가 없는 추상 클래스)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.05.30  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-AbstractClassWithoutAbstractMethod(추상 메서드가 없는 추상 클래스)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

egovLogger 제거

https://github.com/eGovFramework/egovframe-common-components/pull/542

<hr>

### 2025-05-30 금 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovComIndexController

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cmm/web/EgovComIndexController.java:89:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'exception block parameter' 의 변수 'Nfe' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

LocalVariableNamingConventions 번역
- 로컬 변수 명명 규칙
- Local Variable Naming Conventions
- 지역 변수 명명 규칙

#### 브랜치 생성

```
feature/pmd/EgovComIndexController
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(지역 변수 명명 규칙)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.05.30  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(지역 변수 명명 규칙)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

https://github.com/eGovFramework/egovframe-common-components/pull/543

<hr>

### 2025-05-31 토 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovFileDownloadController

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cmm/web/EgovFileDownloadController.java:79:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'param_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cmm/web/EgovFileDownloadController.java:124:	CloseResource:	CloseResource: 리소스 'BufferedInputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/web/EgovFileDownloadController.java:125:	CloseResource:	CloseResource: 리소스 'BufferedOutputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/web/EgovFileDownloadController.java:144:	CloseResource:	CloseResource: 리소스 'PrintWriter' 가 사용 후에 닫혔는지 확인필요
```

LocalVariableNamingConventions 번역
- 로컬 변수 명명 규칙
- Local Variable Naming Conventions
- 지역 변수 명명 규칙

CloseResource 번역
- 닫기 리소스
- Close Resource
- 리소스 닫기

#### 브랜치 생성

```
feature/pmd/EgovFileDownloadController
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(지역 변수 명명 규칙), CloseResource(리소스 닫기)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.05.31  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(지역 변수 명명 규칙), CloseResource(리소스 닫기)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

https://github.com/eGovFramework/egovframe-common-components/pull/544


<hr>

### 2025-05-31 토 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovFileMngController

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cmm/web/EgovFileMngController.java:75:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'param_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cmm/web/EgovFileMngController.java:117:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'param_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

LocalVariableNamingConventions 번역
- 로컬 변수 명명 규칙
- Local Variable Naming Conventions
- 지역 변수 명명 규칙

#### 브랜치 생성

```
feature/pmd/EgovFileMngController
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(지역 변수 명명 규칙)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.05.31  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(지역 변수 명명 규칙)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

https://github.com/eGovFramework/egovframe-common-components/pull/545

<hr>

### 2025-06-03 화 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovImageProcessController

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cmm/web/EgovImageProcessController.java:76:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'param_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cmm/web/EgovImageProcessController.java:112:	CloseResource:	CloseResource: 리소스 'FileInputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/web/EgovImageProcessController.java:114:	CloseResource:	CloseResource: 리소스 'BufferedInputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cmm/web/EgovImageProcessController.java:128:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
```

LocalVariableNamingConventions 번역
- 로컬 변수 명명 규칙
- Local Variable Naming Conventions
- 지역 변수 명명 규칙

CloseResource 번역
- 닫기 리소스
- Close Resource
- 리소스 닫기

AssignmentInOperand 번역
- Assignment In Operand
- 피연산자의 할당

#### 브랜치 생성

```
feature/pmd/EgovImageProcessController
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(지역 변수 명명 규칙), CloseResource(리소스 닫기), AssignmentInOperand(피연산자의 할당)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.06.03  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(지역 변수 명명 규칙), CloseResource(리소스 닫기), AssignmentInOperand(피연산자의 할당)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

https://github.com/eGovFramework/egovframe-common-components/pull/546

<hr>

### 2025-06-03 화 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovArticleServiceImpl

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cop/bbs/service/impl/EgovArticleServiceImpl.java:137:	AvoidReassigningParameters:	AvoidReassigningParameters: 'atchFileId' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/cop/bbs/service/impl/EgovArticleServiceImpl.java:143:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

AvoidReassigningParameters 번역
- 매개변수 재할당을 피하세요
- Avoid Reassigning Parameters
- 매개변수 재할당 방지

LocalVariableNamingConventions 번역
- 로컬 변수 명명 규칙
- Local Variable Naming Conventions
- 지역 변수 명명 규칙

#### 브랜치 생성

```
feature/pmd/EgovArticleServiceImpl
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-AvoidReassigningParameters(매개변수 재할당 방지), LocalVariableNamingConventions(지역 변수 명명 규칙)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.06.03  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-AvoidReassigningParameters(매개변수 재할당 방지), LocalVariableNamingConventions(지역 변수 명명 규칙)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

https://github.com/eGovFramework/egovframe-common-components/pull/547

<hr>

### 2025-06-03 화 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovArticleController

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cop/bbs/web/EgovArticleController.java:427:	AvoidReassigningParameters:	AvoidReassigningParameters: 'boardVO' 처럼 파라미터 값을 직접 변경하지 말 것
```

AvoidReassigningParameters 번역
- 매개변수 재할당을 피하세요
- Avoid Reassigning Parameters
- 매개변수 재할당 방지

#### 브랜치 생성

```
feature/pmd/EgovArticleController
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-AvoidReassigningParameters(매개변수 재할당 방지)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.06.03  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-AvoidReassigningParameters(매개변수 재할당 방지)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

https://github.com/eGovFramework/egovframe-common-components/pull/548

<hr>

### 2025-06-03 화 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovSndngMailRegistServiceImpl

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cop/ems/service/impl/EgovSndngMailRegistServiceImpl.java:158:	SimplifyBooleanExpressions:	SimplifyBooleanExpressions: boolean 사용 시 불필요한 비교 연산을 피하도록 함
```

SimplifyBooleanExpressions 번역
- Simplify Boolean Expressions
- 부울 표현식 단순화

#### 브랜치 생성

```
feature/pmd/EgovSndngMailRegistServiceImpl
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-SimplifyBooleanExpressions(부울 표현식 단순화)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.06.03  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-SimplifyBooleanExpressions(부울 표현식 단순화)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

https://github.com/eGovFramework/egovframe-common-components/pull/549

<hr>

### 2025-06-05 목 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovSndngMailDetailController

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cop/ems/web/EgovSndngMailDetailController.java:158:	CloseResource:	CloseResource: 리소스 'PrintWriter' 가 사용 후에 닫혔는지 확인필요
```

CloseResource 번역
- 닫기 리소스
- Close Resource
- 리소스 닫기

#### 브랜치 생성

```
feature/pmd/EgovSndngMailDetailController
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-CloseResource(리소스 닫기)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.06.05  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-CloseResource(리소스 닫기)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

https://github.com/eGovFramework/egovframe-common-components/pull/550

<hr>

### 2025-06-05 목 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovSndngMailRegistController

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cop/ems/web/EgovSndngMailRegistController.java:102:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/ems/web/EgovSndngMailRegistController.java:103:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

LocalVariableNamingConventions 번역
- 로컬 변수 명명 규칙
- Local Variable Naming Conventions
- 지역 변수 명명 규칙

#### 브랜치 생성

```
feature/pmd/EgovSndngMailRegistController
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(지역 변수 명명 규칙)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.06.05  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(지역 변수 명명 규칙)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

https://github.com/eGovFramework/egovframe-common-components/pull/551

<hr>

### 2025-06-05 목 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovSmsBasicReceiver

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cop/sms/service/impl/EgovSmsBasicReceiver.java:40:	ImmutableField:	ImmutableField: 생성자에서 Assign된 변수 'smsDao' 를 Final로 선언하지 않았음
src/main/java/egovframework/com/cop/sms/service/impl/EgovSmsBasicReceiver.java:42:	ImmutableField:	ImmutableField: 생성자에서 Assign된 변수 'smeConfigPath' 를 Final로 선언하지 않았음
```

ImmutableField 번역
- 불변필드
- Immutable Field
- 변경 불가능한 필드

#### 브랜치 생성

```
feature/pmd/EgovSmsBasicReceiver
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-ImmutableField(불변필드)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.06.05  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-ImmutableField(불변필드)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

https://github.com/eGovFramework/egovframe-common-components/pull/552

<hr>

### 2025-06-05 목 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovSmsBasicServiceImpl

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cop/sms/service/impl/EgovSmsBasicServiceImpl.java:36:	ImmutableField:	ImmutableField: 생성자에서 Assign된 변수 'smsDao' 를 Final로 선언하지 않았음
src/main/java/egovframework/com/cop/sms/service/impl/EgovSmsBasicServiceImpl.java:76:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'FILE_SEPARATOR' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

ImmutableField 번역
- 불변필드
- Immutable Field
- 변경 불가능한 필드

LocalVariableNamingConventions 번역
- 로컬 변수 명명 규칙
- Local Variable Naming Conventions
- 지역 변수 명명 규칙

#### 브랜치 생성

```
feature/pmd/EgovSmsBasicServiceImpl
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-ImmutableField(불변필드), LocalVariableNamingConventions(지역 변수 명명 규칙)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.06.05  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-ImmutableField(불변필드), LocalVariableNamingConventions(지역 변수 명명 규칙)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

https://github.com/eGovFramework/egovframe-common-components/pull/553

<hr>

### 2025-06-09 월 PMD로 소프트웨어 보안약점 진단하고 제거하기-SmsBasicDAO

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cop/sms/service/impl/SmsBasicDAO.java:40:	CloseResource:	CloseResource: 리소스 'Connection' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cop/sms/service/impl/SmsBasicDAO.java:41:	CloseResource:	CloseResource: 리소스 'PreparedStatement' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cop/sms/service/impl/SmsBasicDAO.java:42:	CloseResource:	CloseResource: 리소스 'ResultSet' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cop/sms/service/impl/SmsBasicDAO.java:145:	CloseResource:	CloseResource: 리소스 'Connection' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cop/sms/service/impl/SmsBasicDAO.java:146:	CloseResource:	CloseResource: 리소스 'PreparedStatement' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cop/sms/service/impl/SmsBasicDAO.java:147:	CloseResource:	CloseResource: 리소스 'ResultSet' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cop/sms/service/impl/SmsBasicDAO.java:220:	CloseResource:	CloseResource: 리소스 'Connection' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cop/sms/service/impl/SmsBasicDAO.java:221:	CloseResource:	CloseResource: 리소스 'PreparedStatement' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cop/sms/service/impl/SmsBasicDAO.java:285:	CloseResource:	CloseResource: 리소스 'Connection' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cop/sms/service/impl/SmsBasicDAO.java:286:	CloseResource:	CloseResource: 리소스 'PreparedStatement' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cop/sms/service/impl/SmsBasicDAO.java:325:	CloseResource:	CloseResource: 리소스 'Connection' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cop/sms/service/impl/SmsBasicDAO.java:326:	CloseResource:	CloseResource: 리소스 'PreparedStatement' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cop/sms/service/impl/SmsBasicDAO.java:327:	CloseResource:	CloseResource: 리소스 'ResultSet' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cop/sms/service/impl/SmsBasicDAO.java:387:	CloseResource:	CloseResource: 리소스 'Connection' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cop/sms/service/impl/SmsBasicDAO.java:388:	CloseResource:	CloseResource: 리소스 'PreparedStatement' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cop/sms/service/impl/SmsBasicDAO.java:389:	CloseResource:	CloseResource: 리소스 'ResultSet' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cop/sms/service/impl/SmsBasicDAO.java:440:	CloseResource:	CloseResource: 리소스 'Connection' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cop/sms/service/impl/SmsBasicDAO.java:441:	CloseResource:	CloseResource: 리소스 'PreparedStatement' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cop/sms/service/impl/SmsBasicDAO.java:480:	CloseResource:	CloseResource: 리소스 'PreparedStatement' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cop/sms/service/impl/SmsBasicDAO.java:481:	CloseResource:	CloseResource: 리소스 'ResultSet' 가 사용 후에 닫혔는지 확인필요
```

CloseResource 번역
- 닫기 리소스
- Close Resource
- 리소스 닫기

#### 브랜치 생성

```
feature/pmd/SmsBasicDAO
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-CloseResource(리소스 닫기)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.06.09  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-CloseResource(리소스 닫기)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

https://github.com/eGovFramework/egovframe-common-components/pull/554

<hr>

### 2025-06-09 월 PMD로 소프트웨어 보안약점 진단하고 제거하기-SmsBasicDBUtil

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cop/sms/service/impl/SmsBasicDBUtil.java:106:	CloseResource:	CloseResource: 리소스 'GenericObjectPool' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/cop/sms/service/impl/SmsBasicDBUtil.java:114:	AvoidSynchronizedAtMethodLevel:	AvoidSynchronizedAtMethodLevel: mothod 레벨의 synchronization 보다 block 레벨 synchronization 을 사용하는 것이 바람직함
src/main/java/egovframework/com/cop/sms/service/impl/SmsBasicDBUtil.java:115:	CloseResource:	CloseResource: 리소스 'BasicDataSource' 가 사용 후에 닫혔는지 확인필요
```

CloseResource 번역
- 닫기 리소스
- Close Resource
- 리소스 닫기

AvoidSynchronizedAtMethodLevel 번역
- Avoid Synchronized At Method Level
- 메서드 수준에서 동기화를 피하세요

#### 브랜치 생성

```
feature/pmd/SmsBasicDBUtil
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-CloseResource(리소스 닫기), AvoidSynchronizedAtMethodLevel(메서드 수준에서 동기화를 피하세요)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.06.09  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-CloseResource(리소스 닫기), AvoidSynchronizedAtMethodLevel(메서드 수준에서 동기화를 피하세요)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

https://github.com/eGovFramework/egovframe-common-components/pull/555

<hr>

### 2025-06-10 화 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovDeptJobController

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cop/smt/djm/web/EgovDeptJobController.java:613:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/djm/web/EgovDeptJobController.java:621:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/djm/web/EgovDeptJobController.java:629:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_cnt' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/djm/web/EgovDeptJobController.java:630:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/djm/web/EgovDeptJobController.java:677:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/djm/web/EgovDeptJobController.java:678:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/djm/web/EgovDeptJobController.java:718:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

LocalVariableNamingConventions 번역
- 로컬 변수 명명 규칙
- Local Variable Naming Conventions
- 지역 변수 명명 규칙

#### 브랜치 생성

```
feature/pmd/EgovDeptJobController
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(지역 변수 명명 규칙)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.06.10  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(지역 변수 명명 규칙)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

https://github.com/eGovFramework/egovframe-common-components/pull/556

<hr>

### 2025-06-10 화 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovDiaryManageController

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cop/smt/dsm/web/EgovDiaryManageController.java:268:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/dsm/web/EgovDiaryManageController.java:277:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/dsm/web/EgovDiaryManageController.java:286:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_cnt' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/dsm/web/EgovDiaryManageController.java:287:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/dsm/web/EgovDiaryManageController.java:396:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/dsm/web/EgovDiaryManageController.java:397:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

LocalVariableNamingConventions 번역
- 로컬 변수 명명 규칙
- Local Variable Naming Conventions
- 지역 변수 명명 규칙

#### 브랜치 생성

```
feature/pmd/EgovDiaryManageController
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(지역 변수 명명 규칙)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.06.10  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(지역 변수 명명 규칙)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

https://github.com/eGovFramework/egovframe-common-components/pull/557

<hr>

### 2025-06-11 수 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovLeaderSchdulServiceImpl

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cop/smt/lsm/service/impl/EgovLeaderSchdulServiceImpl.java:142:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 implicit unboxing. Use Integer.parseInt(...) instead
src/main/java/egovframework/com/cop/smt/lsm/service/impl/EgovLeaderSchdulServiceImpl.java:143:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 implicit unboxing. Use Integer.parseInt(...) instead
src/main/java/egovframework/com/cop/smt/lsm/service/impl/EgovLeaderSchdulServiceImpl.java:165:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 implicit unboxing. Use Integer.parseInt(...) instead
src/main/java/egovframework/com/cop/smt/lsm/service/impl/EgovLeaderSchdulServiceImpl.java:166:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 implicit unboxing. Use Integer.parseInt(...) instead
src/main/java/egovframework/com/cop/smt/lsm/service/impl/EgovLeaderSchdulServiceImpl.java:167:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 implicit unboxing. Use Integer.parseInt(...) instead
src/main/java/egovframework/com/cop/smt/lsm/service/impl/EgovLeaderSchdulServiceImpl.java:195:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 implicit unboxing. Use Integer.parseInt(...) instead
src/main/java/egovframework/com/cop/smt/lsm/service/impl/EgovLeaderSchdulServiceImpl.java:209:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 implicit unboxing. Use Integer.parseInt(...) instead
src/main/java/egovframework/com/cop/smt/lsm/service/impl/EgovLeaderSchdulServiceImpl.java:210:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 implicit unboxing. Use Integer.parseInt(...) instead
src/main/java/egovframework/com/cop/smt/lsm/service/impl/EgovLeaderSchdulServiceImpl.java:211:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 implicit unboxing. Use Integer.parseInt(...) instead
src/main/java/egovframework/com/cop/smt/lsm/service/impl/EgovLeaderSchdulServiceImpl.java:215:	SimpleDateFormatNeedsLocale:	SimpleDateFormatNeedsLocale: SimpleDateFormat 인스턴스를 생성할때 Locale 을 지정하는 것이 바람직함
src/main/java/egovframework/com/cop/smt/lsm/service/impl/EgovLeaderSchdulServiceImpl.java:216:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 implicit unboxing. Use Integer.parseInt(...) instead
```

UnnecessaryBoxing 번역
- 불필요한 복싱
- Unnecessary Boxing
- 불필요한 복싱
- 불필요한 박싱

SimpleDateFormatNeedsLocale 번역
- Simple Date Format Needs Locale
- 간단한 날짜 형식에 로캘이 필요합니다.
- 간단한 날짜 형식에 로케일이 필요합니다.

#### 브랜치 생성

```
feature/pmd/EgovLeaderSchdulServiceImpl
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-UnnecessaryBoxing(불필요한 박싱), SimpleDateFormatNeedsLocale(간단한 날짜 형식에 로케일이 필요합니다.)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.06.10  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-UnnecessaryBoxing(불필요한 박싱), SimpleDateFormatNeedsLocale(간단한 날짜 형식에 로케일이 필요합니다.)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

https://github.com/eGovFramework/egovframe-common-components/pull/558

<hr>

### 2025-06-11 수 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovMemoReprtController

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cop/smt/mrm/web/EgovMemoReprtController.java:304:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/mrm/web/EgovMemoReprtController.java:313:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/mrm/web/EgovMemoReprtController.java:322:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_cnt' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/mrm/web/EgovMemoReprtController.java:323:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/mrm/web/EgovMemoReprtController.java:393:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/mrm/web/EgovMemoReprtController.java:394:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/mrm/web/EgovMemoReprtController.java:440:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

LocalVariableNamingConventions 번역
- 로컬 변수 명명 규칙
- Local Variable Naming Conventions
- 지역 변수 명명 규칙

#### 브랜치 생성

```
feature/pmd/EgovMemoReprtController
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(지역 변수 명명 규칙)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.06.11  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(지역 변수 명명 규칙)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

https://github.com/eGovFramework/egovframe-common-components/pull/559

<hr>

### 2025-06-11 수 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovDeptSchdulManageController

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cop/smt/sdm/web/EgovDeptSchdulManageController.java:692:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/sdm/web/EgovDeptSchdulManageController.java:701:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/sdm/web/EgovDeptSchdulManageController.java:709:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_cnt' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/sdm/web/EgovDeptSchdulManageController.java:710:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/sdm/web/EgovDeptSchdulManageController.java:823:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/sdm/web/EgovDeptSchdulManageController.java:824:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

LocalVariableNamingConventions 번역
- 로컬 변수 명명 규칙
- Local Variable Naming Conventions
- 지역 변수 명명 규칙

#### 브랜치 생성

```
feature/pmd/EgovDeptSchdulManageController
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(지역 변수 명명 규칙)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.06.11  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(지역 변수 명명 규칙)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

https://github.com/eGovFramework/egovframe-common-components/pull/560

<hr>

### 2025-06-12 목 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovIndvdlSchdulManageController

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cop/smt/sim/web/EgovIndvdlSchdulManageController.java:620:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/sim/web/EgovIndvdlSchdulManageController.java:629:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/sim/web/EgovIndvdlSchdulManageController.java:638:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_cnt' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/sim/web/EgovIndvdlSchdulManageController.java:639:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/sim/web/EgovIndvdlSchdulManageController.java:756:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/sim/web/EgovIndvdlSchdulManageController.java:757:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

LocalVariableNamingConventions 번역
- 로컬 변수 명명 규칙
- Local Variable Naming Conventions
- 지역 변수 명명 규칙

#### 브랜치 생성

```
feature/pmd/EgovIndvdlSchdulManageController
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(지역 변수 명명 규칙)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.06.12  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(지역 변수 명명 규칙)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

https://github.com/eGovFramework/egovframe-common-components/pull/561

<hr>

### 2025-06-12 목 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovWikMnthngReprtController

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/cop/smt/wmr/web/EgovWikMnthngReprtController.java:314:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/wmr/web/EgovWikMnthngReprtController.java:323:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/wmr/web/EgovWikMnthngReprtController.java:332:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_cnt' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/wmr/web/EgovWikMnthngReprtController.java:333:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/wmr/web/EgovWikMnthngReprtController.java:382:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/wmr/web/EgovWikMnthngReprtController.java:383:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/cop/smt/wmr/web/EgovWikMnthngReprtController.java:424:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

LocalVariableNamingConventions 번역
- 로컬 변수 명명 규칙
- Local Variable Naming Conventions
- 지역 변수 명명 규칙

#### 브랜치 생성

```
feature/pmd/EgovWikMnthngReprtController
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(지역 변수 명명 규칙)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.06.12  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(지역 변수 명명 규칙)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

https://github.com/eGovFramework/egovframe-common-components/pull/562

<hr>

### 2025-06-13 금 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovKnoAppraisalServiceImpl

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/dam/app/service/impl/EgovKnoAppraisalServiceImpl.java:31:	FieldNamingConventions:	FieldNamingConventions: 'field' 의 변수 'KnoAppraisalDAO' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

FieldNamingConventions 번역
- 필드 명명 규칙
- Field Naming Conventions
- 필드 명명 규칙

#### 브랜치 생성

```
feature/pmd/EgovKnoAppraisalServiceImpl
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-FieldNamingConventions(필드 명명 규칙)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.06.13  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(지역 변수 명명 규칙)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

https://github.com/eGovFramework/egovframe-common-components/pull/563

<hr>

### 2025-06-13 금 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovKnoAppraisalController

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/dam/app/web/EgovKnoAppraisalController.java:106:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'KnoAppraisalList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

LocalVariableNamingConventions 번역
- 로컬 변수 명명 규칙
- Local Variable Naming Conventions
- 지역 변수 명명 규칙

#### 브랜치 생성

```
feature/pmd/EgovKnoAppraisalController
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(지역 변수 명명 규칙)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.06.13  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(지역 변수 명명 규칙)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

https://github.com/eGovFramework/egovframe-common-components/pull/564

<hr>

### 2025-06-14 토 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovMapMaterialServiceImpl

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/dam/map/mat/service/impl/EgovMapMaterialServiceImpl.java:30:	FieldNamingConventions:	FieldNamingConventions: 'field' 의 변수 'MapMaterialDAO' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

FieldNamingConventions 번역
- 필드 명명 규칙
- Field Naming Conventions

#### 브랜치 생성

```
feature/pmd/EgovMapMaterialServiceImpl
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-FieldNamingConventions(필드 명명 규칙)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.06.14  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-FieldNamingConventions(필드 명명 규칙)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

https://github.com/eGovFramework/egovframe-common-components/pull/566

<hr>

### 2025-06-14 토 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovMapMaterialController

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/dam/map/mat/web/EgovMapMaterialController.java:93:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'MapMaterialList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/map/mat/web/EgovMapMaterialController.java:141:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'MapMaterialList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/map/mat/web/EgovMapMaterialController.java:155:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'MapMaterialList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

LocalVariableNamingConventions 번역
- 로컬 변수 명명 규칙
- Local Variable Naming Conventions
- 지역 변수 명명 규칙

#### 브랜치 생성

```
feature/pmd/EgovMapMaterialController
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(지역 변수 명명 규칙)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.06.14  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(지역 변수 명명 규칙)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

https://github.com/eGovFramework/egovframe-common-components/pull/567

<hr>

### 2025-06-16 월 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovMapTeamServiceImpl

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/dam/map/tea/service/impl/EgovMapTeamServiceImpl.java:29:	FieldNamingConventions:	FieldNamingConventions: 'field' 의 변수 'MapTeamDAO' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

FieldNamingConventions
- 필드 명명 규칙
- Field Naming Conventions
- 필드 명명 규칙

FieldNamingConventions(필드 명명 규칙)

#### 브랜치 생성

```
feature/pmd/EgovMapTeamServiceImpl
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-FieldNamingConventions(필드 명명 규칙)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.06.16  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-FieldNamingConventions(필드 명명 규칙)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

https://github.com/eGovFramework/egovframe-common-components/pull/569

<hr>

### 2025-06-16 월 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovMapTeamController

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/dam/map/tea/web/EgovMapTeamController.java:88:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'MapTeamList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

LocalVariableNamingConventions 번역
- 로컬 변수 명명 규칙
- Local Variable Naming Conventions
- 지역 변수 명명 규칙

#### 브랜치 생성

```
feature/pmd/EgovMapTeamController
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(지역 변수 명명 규칙)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.06.16  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(지역 변수 명명 규칙)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

https://github.com/eGovFramework/egovframe-common-components/pull/571

<hr>

### 2025-06-17 화 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovKnoManagementServiceImpl

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/dam/mgm/service/impl/EgovKnoManagementServiceImpl.java:31:	FieldNamingConventions:	FieldNamingConventions: 'field' 의 변수 'KnoManagementDAO' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

FieldNamingConventions
- 필드 명명 규칙
- Field Naming Conventions
- 필드 명명 규칙

#### 브랜치 생성

```
feature/pmd/EgovKnoManagementServiceImpl
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-FieldNamingConventions(필드 명명 규칙)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.06.17  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-FieldNamingConventions(필드 명명 규칙)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

https://github.com/eGovFramework/egovframe-common-components/pull/572

<hr>

### 2025-06-17 화 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovKnoPersonalController

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/dam/per/web/EgovKnoPersonalController.java:231:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/per/web/EgovKnoPersonalController.java:232:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/per/web/EgovKnoPersonalController.java:326:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/per/web/EgovKnoPersonalController.java:334:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/per/web/EgovKnoPersonalController.java:343:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_cnt' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/per/web/EgovKnoPersonalController.java:344:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

LocalVariableNamingConventions 번역
- 로컬 변수 명명 규칙
- Local Variable Naming Conventions
- 지역 변수 명명 규칙

#### 브랜치 생성

```
feature/pmd/EgovKnoPersonalController
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(지역 변수 명명 규칙)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.06.17  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(지역 변수 명명 규칙)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

https://github.com/eGovFramework/egovframe-common-components/pull/573

<hr>

### 2025-06-18 수 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovRequestOfferController

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/dam/spe/req/web/EgovRequestOfferController.java:193:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'ReusltScript' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/spe/req/web/EgovRequestOfferController.java:218:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'MapTeamList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/spe/req/web/EgovRequestOfferController.java:227:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'MapMaterialList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/spe/req/web/EgovRequestOfferController.java:289:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'MapTeamList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/spe/req/web/EgovRequestOfferController.java:303:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'MapMaterialList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/spe/req/web/EgovRequestOfferController.java:366:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/spe/req/web/EgovRequestOfferController.java:374:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/spe/req/web/EgovRequestOfferController.java:383:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_cnt' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/spe/req/web/EgovRequestOfferController.java:384:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/spe/req/web/EgovRequestOfferController.java:432:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'MapTeamList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/spe/req/web/EgovRequestOfferController.java:446:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'MapMaterialList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/spe/req/web/EgovRequestOfferController.java:508:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/spe/req/web/EgovRequestOfferController.java:514:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

LocalVariableNamingConventions 번역
- 로컬 변수 명명 규칙
- Local Variable Naming Conventions
- 지역 변수 명명 규칙

#### 브랜치 생성

```
feature/pmd/EgovRequestOfferController
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(지역 변수 명명 규칙)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.06.18  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(지역 변수 명명 규칙)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

https://github.com/eGovFramework/egovframe-common-components/pull/574

<hr>

### 2025-06-18 수 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovKnoSpecialistServiceImpl

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/dam/spe/spe/service/impl/EgovKnoSpecialistServiceImpl.java:30:	FieldNamingConventions:	FieldNamingConventions: 'field' 의 변수 'KnoSpecialistDAO' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

FieldNamingConventions
- 필드 명명 규칙
- Field Naming Conventions
- 필드 명명 규칙

#### 브랜치 생성

```
feature/pmd/EgovKnoSpecialistServiceImpl
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-FieldNamingConventions(필드 명명 규칙)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.06.18  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-FieldNamingConventions(필드 명명 규칙)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

https://github.com/eGovFramework/egovframe-common-components/pull/575

<hr>

### 2025-06-19 목 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovKnoSpecialistController

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/dam/spe/spe/web/EgovKnoSpecialistController.java:105:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'KnoSpecialistList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/spe/spe/web/EgovKnoSpecialistController.java:170:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'MapTeamList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/spe/spe/web/EgovKnoSpecialistController.java:180:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'MapMaterialList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/spe/spe/web/EgovKnoSpecialistController.java:194:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'MapTeamList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/dam/spe/spe/web/EgovKnoSpecialistController.java:209:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'MapMaterialList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

LocalVariableNamingConventions 번역
- 로컬 변수 명명 규칙
- Local Variable Naming Conventions
- 지역 변수 명명 규칙

#### 브랜치 생성

```
feature/pmd/EgovKnoSpecialistController
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(지역 변수 명명 규칙)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.06.19  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(지역 변수 명명 규칙)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

https://github.com/eGovFramework/egovframe-common-components/pull/576

<hr>

### 2025-06-19 목 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovCaptchaController

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/ext/captcha/EgovCaptchaController.java:66:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
```

UselessParentheses 번역
- 쓸모없는 괄호
- Useless Parentheses

#### 브랜치 생성

```
feature/pmd/EgovCaptchaController
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-UselessParentheses(쓸모없는 괄호)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.06.19  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-UselessParentheses(쓸모없는 괄호)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

https://github.com/eGovFramework/egovframe-common-components/pull/577

<hr>

### 2025-06-20 금 PMD로 소프트웨어 보안약점 진단하고 제거하기-LdapObject

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/ext/ldapumt/service/LdapObject.java:38:	AbstractClassWithoutAbstractMethod:	AbstractClassWithoutAbstractMethod: Abstract Class내에  Abstract Method가 존재하지 않음
```

AbstractClassWithoutAbstractMethod 번역
- 추상 메서드가 없는 추상 클래스
- Abstract Class Without Abstract Method

#### 브랜치 생성

```
feature/pmd/LdapObject
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-AbstractClassWithoutAbstractMethod(추상 메서드가 없는 추상 클래스)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.06.20  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-AbstractClassWithoutAbstractMethod(추상 메서드가 없는 추상 클래스)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

https://github.com/eGovFramework/egovframe-common-components/pull/578

<hr>

### 2025-06-20 금 PMD로 소프트웨어 보안약점 진단하고 제거하기-LdapTreeObject

#### PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/ext/ldapumt/service/LdapTreeObject.java:92:	FieldNamingConventions:	FieldNamingConventions: 'enum constant' 의 변수 'dept' 이  '[A-Z][A-Z_0-9]*'  로 시작함
```

FieldNamingConventions
- 필드 명명 규칙
- Field Naming Conventions
- 필드 명명 규칙

#### 브랜치 생성

```
feature/pmd/LdapTreeObject
```

#### Commit and Push(커밋 및 푸시) 1

Commit Message(커밋 메시지)
```
이클립스 > Source > Format
```

#### Commit and Push(커밋 및 푸시) 2

Commit Message(커밋 메시지)
```
PMD로 소프트웨어 보안약점 진단하고 제거하기-FieldNamingConventions(필드 명명 규칙)
```

#### Commit and Push(커밋 및 푸시) 3

```java
 *   2025.06.20  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-FieldNamingConventions(필드 명명 규칙)
```

Commit Message(커밋 메시지)
```
개정이력 수정
```

https://github.com/eGovFramework/egovframe-common-components/pull/579

<hr>

### 2025-06-21 토 PMD로 소프트웨어 보안약점 진단하고 제거하기-ObjectMapper-ImmutableField(불변필드), UselessParentheses(쓸모없는 괄호)

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/ext/ldapumt/service/impl/ObjectMapper.java:57:	ImmutableField:	ImmutableField: 생성자에서 Assign된 변수 'type' 를 Final로 선언하지 않았음
src/main/java/egovframework/com/ext/ldapumt/service/impl/ObjectMapper.java:104:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
```

2. 브랜치 생성

```
feature/pmd/ObjectMapper
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.06.21  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-ImmutableField(불변필드), UselessParentheses(쓸모없는 괄호)
```

https://github.com/eGovFramework/egovframe-common-components/pull/580

<hr>

### 2025-06-21 토 PMD로 소프트웨어 보안약점 진단하고 제거하기-ChatServerEndPoint

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/ext/msg/server/ChatServerEndPoint.java:60:	ImmutableField:	ImmutableField: 생성자에서 Assign된 변수 'chatroomUsers' 를 Final로 선언하지 않았음
src/main/java/egovframework/com/ext/msg/server/ChatServerEndPoint.java:97:	CloseResource:	CloseResource: 리소스 'Session' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/ext/msg/server/ChatServerEndPoint.java:105:	CloseResource:	CloseResource: 리소스 'Session' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/ext/msg/server/ChatServerEndPoint.java:117:	CloseResource:	CloseResource: 리소스 'Session' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/ext/msg/server/ChatServerEndPoint.java:142:	CloseResource:	CloseResource: 리소스 'Session' 가 사용 후에 닫혔는지 확인필요
```

2. 브랜치 생성

```
feature/pmd/ChatServerEndPoint
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.06.21  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-ImmutableField(불변필드), CloseResource(리소스 닫기)
```

https://github.com/eGovFramework/egovframe-common-components/pull/581

<hr>

### 2025-06-23 월 PMD로 소프트웨어 보안약점 진단하고 제거하기-UsersServerEndPoint

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/ext/msg/server/UsersServerEndPoint.java:102:	CloseResource:	CloseResource: 리소스 'Session' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/ext/msg/server/UsersServerEndPoint.java:105:	EmptyControlStatement:	EmptyControlStatement: Empty else statement
src/main/java/egovframework/com/ext/msg/server/UsersServerEndPoint.java:124:	CloseResource:	CloseResource: 리소스 'Session' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/ext/msg/server/UsersServerEndPoint.java:132:	CloseResource:	CloseResource: 리소스 'Session' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/ext/msg/server/UsersServerEndPoint.java:166:	CloseResource:	CloseResource: 리소스 'Session' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/ext/msg/server/UsersServerEndPoint.java:180:	CloseResource:	CloseResource: 리소스 'Session' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/ext/msg/server/UsersServerEndPoint.java:184:	UnnecessarySemicolon:	UnnecessarySemicolon: 필요없는 문장 (;)이 있음
src/main/java/egovframework/com/ext/msg/server/UsersServerEndPoint.java:211:	CloseResource:	CloseResource: 리소스 'Session' 가 사용 후에 닫혔는지 확인필요
```

2. 브랜치 생성

```
feature/pmd/UsersServerEndPoint
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.06.23  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-CloseResource(리소스 닫기), EmptyControlStatement(빈 제어문), UnnecessarySemicolon(불필요한 세미콜론)
```

// NOPMD - CloseResource 주석 추가

LOGGER.debug("username을 다시 입력하게하는 로직 넣기."); 로그 추가

필요없는 문장 (;) 제거

https://github.com/eGovFramework/egovframe-common-components/pull/582

<hr>

### 2025-06-23 월 PMD로 소프트웨어 보안약점 진단하고 제거하기-ChatServerAppConfig

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/ext/msg/server/config/ChatServerAppConfig.java:44:	FieldNamingConventions:	FieldNamingConventions: 'constant' 의 변수 'endpointMap' 이  '[A-Z][A-Z_0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/ChatServerAppConfig
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.06.23  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-FieldNamingConventions(필드 명명 규칙)
```

endpointMap 를 ENDPOINT_MAP 로 수정

https://github.com/eGovFramework/egovframe-common-components/pull/583

<hr>

### 2025-06-24 화 PMD로 소프트웨어 보안약점 진단하고 제거하기-MessageDecoder

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/ext/msg/server/model/decoder/MessageDecoder.java:51:	UncommentedEmptyMethodBody:	UncommentedEmptyMethodBody: 빈 Method Body에 주석을 추가 할 것
src/main/java/egovframework/com/ext/msg/server/model/decoder/MessageDecoder.java:54:	UncommentedEmptyMethodBody:	UncommentedEmptyMethodBody: 빈 Method Body에 주석을 추가 할 것
src/main/java/egovframework/com/ext/msg/server/model/decoder/MessageDecoder.java:67:	CloseResource:	CloseResource: 리소스 'JsonReader' 가 사용 후에 닫혔는지 확인필요
```

2. 브랜치 생성

```
feature/pmd/MessageDecoder
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.06.24  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-UncommentedEmptyMethodBody(주석 처리되지 않은 빈 메서드 본문), CloseResource(리소스 닫기)
```

JsonReader/StringReader try-with-resources 로 수정

// init 주석 추가

arg0 를 config 로 수정

// destroy 로그 추가

LOGGER 를 @Slf4j 로 수정하고 debug 를 error 로 수정

destroy, init 를 init, destroy 로 순서 수정

https://github.com/eGovFramework/egovframe-common-components/pull/584

<hr>

### 2025-06-24 화 PMD로 소프트웨어 보안약점 진단하고 제거하기-MessageEncoder

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/ext/msg/server/model/encoder/MessageEncoder.java:47:	UncommentedEmptyMethodBody:	UncommentedEmptyMethodBody: 빈 Method Body에 주석을 추가 할 것
src/main/java/egovframework/com/ext/msg/server/model/encoder/MessageEncoder.java:51:	UncommentedEmptyMethodBody:	UncommentedEmptyMethodBody: 빈 Method Body에 주석을 추가 할 것
```

2. 브랜치 생성

```
feature/pmd/MessageEncoder
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.06.24  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-UncommentedEmptyMethodBody(주석 처리되지 않은 빈 메서드 본문)
```

// destroy 주석 추가

// init 주석 추가

arg0 를 config 로 수정

destroy, init 를 init, destroy 로 순서 수정

https://github.com/eGovFramework/egovframe-common-components/pull/585

<hr>

### 2025-06-25 수 PMD로 소프트웨어 보안약점 진단하고 제거하기-OAuthLogin

`Response response = oauthService.execute(request);` try-with-resources 로 수정

mapper 를 MAPPER 로 수정

`private OAuthVO oauthVO;` 를 `private final OAuthVO oauthVO;` 로 final 추가

`private OAuth20Service oauthService;` 를 `private final OAuth20Service oauthService;` 로 final 추가

`private void getEmails(OAuthUniversalUser user, JsonNode rootNode) {` 사용되지 않는 Private Method 주석

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/ext/oauth/service/OAuthLogin.java:19:	ImmutableField:	ImmutableField: 생성자에서 Assign된 변수 'oauthService' 를 Final로 선언하지 않았음
src/main/java/egovframework/com/ext/oauth/service/OAuthLogin.java:20:	ImmutableField:	ImmutableField: 생성자에서 Assign된 변수 'oauthVO' 를 Final로 선언하지 않았음
src/main/java/egovframework/com/ext/oauth/service/OAuthLogin.java:22:	FieldNamingConventions:	FieldNamingConventions: 'constant' 의 변수 'mapper' 이  '[A-Z][A-Z_0-9]*'  로 시작함
src/main/java/egovframework/com/ext/oauth/service/OAuthLogin.java:52:	CloseResource:	CloseResource: 리소스 'Response' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/ext/oauth/service/OAuthLogin.java:86:	UnusedPrivateMethod:	UnusedPrivateMethod: 사용되지 않는 Private Method 'getEmails(OAuthUniversalUser, JsonNode)' 가 선언되었음
```

2. 브랜치 생성

```
feature/pmd/OAuthLogin
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.06.25  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-ImmutableField(불변필드), FieldNamingConventions(필드 명명 규칙), CloseResource(리소스 닫기), UnusedPrivateMethod(사용되지 않는 개인 메서드)
```

https://github.com/eGovFramework/egovframe-common-components/pull/589

<hr>

### 2025-06-25 수 PMD로 소프트웨어 보안약점 진단하고 제거하기-OAuthVO

`private String origin;` 을 `private final String origin;` 로 final 추가

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/ext/oauth/service/OAuthVO.java:77:	ImmutableField:	ImmutableField: 생성자에서 Assign된 변수 'origin' 를 Final로 선언하지 않았음
```

2. 브랜치 생성

```
feature/pmd/OAuthVO
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.06.25  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-ImmutableField(불변필드)
```

https://github.com/eGovFramework/egovframe-common-components/pull/590

<hr>

### 2025-06-26 목 PMD로 소프트웨어 보안약점 진단하고 제거하기-GroupManageVO

`getDelYn` 메서드를 롬복 `@Getter` 으로 수정

`setDelYn` 메서드를 롬복 `@Setter` 으로 수정

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sec/gmt/service/GroupManageVO.java:60:	MethodReturnsInternalArray:	MethodReturnsInternalArray: 'delYn'을 반환하면 내부 배열이 노출될 수 있음
src/main/java/egovframework/com/sec/gmt/service/GroupManageVO.java:68:	ArrayIsStoredDirectly:	ArrayIsStoredDirectly: 배열 'delYn' 이 직접 저장되어 있음
```

2. 브랜치 생성

```
feature/pmd/GroupManageVO
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.06.26  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-MethodReturnsInternalArray(메서드 반환 내부 배열), ArrayIsStoredDirectly(배열이 직접 저장됨)
```

https://github.com/eGovFramework/egovframe-common-components/pull/591

<hr>

### 2025-06-26 목 PMD로 소프트웨어 보안약점 진단하고 제거하기-RoleManageVO

`getDelYn` 메서드를 롬복 `@Getter` 으로 수정

`setDelYn` 메서드를 롬복 `@Setter` 으로 수정

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sec/rmt/service/RoleManageVO.java:55:	MethodReturnsInternalArray:	MethodReturnsInternalArray: 'delYn'을 반환하면 내부 배열이 노출될 수 있음
src/main/java/egovframework/com/sec/rmt/service/RoleManageVO.java:62:	ArrayIsStoredDirectly:	ArrayIsStoredDirectly: 배열 'delYn' 이 직접 저장되어 있음
```

2. 브랜치 생성

```
feature/pmd/RoleManageVO
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.06.26  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-MethodReturnsInternalArray(메서드 반환 내부 배열), ArrayIsStoredDirectly(배열이 직접 저장됨)
```

https://github.com/eGovFramework/egovframe-common-components/pull/592

<hr>

### 2025-06-27 금 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovSpringSecurityLogoutFilter

`destroy` 빈 Method Body에 주석을 추가

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sec/security/filter/EgovSpringSecurityLogoutFilter.java:43:	UncommentedEmptyMethodBody:	UncommentedEmptyMethodBody: 빈 Method Body에 주석을 추가 할 것
```

2. 브랜치 생성

```
feature/pmd/EgovSpringSecurityLogoutFilter
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.06.27  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-UncommentedEmptyMethodBody(주석 처리되지 않은 빈 메서드 본문)
```

https://github.com/eGovFramework/egovframe-common-components/pull/593

<hr>

### 2025-06-27 금 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovSpringSecurityLoginFilter

`destroy` 빈 Method Body에 주석을 추가

`private String username` 생성자에서 Assign된 변수 'username' 를 Final로 선언

`private String password` 생성자에서 Assign된 변수 'password' 를 Final로 선언

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sec/security/filter/EgovSpringSecurityLoginFilter.java:62:	UncommentedEmptyMethodBody:	UncommentedEmptyMethodBody: 빈 Method Body에 주석을 추가 할 것
src/main/java/egovframework/com/sec/security/filter/EgovSpringSecurityLoginFilter.java:278:	ImmutableField:	ImmutableField: 생성자에서 Assign된 변수 'username' 를 Final로 선언하지 않았음
src/main/java/egovframework/com/sec/security/filter/EgovSpringSecurityLoginFilter.java:279:	ImmutableField:	ImmutableField: 생성자에서 Assign된 변수 'password' 를 Final로 선언하지 않았음
```

2. 브랜치 생성

```
feature/pmd/EgovSpringSecurityLoginFilter
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.06.27  이백행          PMD로 소프트웨어 보안약점 진단하고 제거하기-UncommentedEmptyMethodBody(주석 처리되지 않은 빈 메서드 본문), ImmutableField(불변필드)
```

https://github.com/eGovFramework/egovframe-common-components/pull/594

<hr>

### 2025-06-27 금 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovCntcInsttController

`CmmnCodeList` 를 `resultList` 로 수정

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/ssi/syi/iis/web/EgovCntcInsttController.java:394:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CmmnCodeList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovCntcInsttController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.06.27  이백행          컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(지역 변수 명명 규칙)
```

https://github.com/eGovFramework/egovframe-common-components/pull/595

<hr>

### 2025-06-27 금 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovCntcMessageController

`CmmnCodeList` 를 `resultList` 로 이름 바꾸기

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/ssi/syi/ims/web/EgovCntcMessageController.java:278:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CmmnCodeList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovCntcMessageController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.06.27  이백행          컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(지역 변수 명명 규칙)
```

https://github.com/eGovFramework/egovframe-common-components/pull/596

<hr>

### 2025-06-28 토 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovCntcSttusService

`CntcSttus` 을 `cntcSttus` 로 이름 바꾸기

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/ssi/syi/ist/service/EgovCntcSttusService.java:33:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'CntcSttus' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovCntcSttusService
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.06.28  이백행          컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-FormalParameterNamingConventions(변수명에 밑줄 사용)
```

https://github.com/eGovFramework/egovframe-common-components/pull/597

<hr>

### 2025-06-28 토 PMD로 소프트웨어 보안약점 진단하고 제거하기-CntcSttusDAO

`CntcSttus` 을 `cntcSttus` 로 이름 바꾸기

`(CntcSttus)` 형 변환 제거

`(Integer)` 형 변환 제거

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/ssi/syi/ist/service/impl/CntcSttusDAO.java:39:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'CntcSttus' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/CntcSttusDAO
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.06.28  이백행          컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-FormalParameterNamingConventions(변수명에 밑줄 사용)
 *   2025.06.28  이백행          컨트리뷰션 형 변환 제거-(CntcSttus), (Integer)
```

https://github.com/eGovFramework/egovframe-common-components/pull/598

<hr>

### 2025-06-30 월 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovCntcSttusServiceImpl

`CntcSttus` 을 `cntcSttus` 로 이름 바꾸기

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/ssi/syi/ist/service/impl/EgovCntcSttusServiceImpl.java:45:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'CntcSttus' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovCntcSttusServiceImpl
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.06.30  이백행          컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-FormalParameterNamingConventions(변수명에 밑줄 사용)
```

https://github.com/eGovFramework/egovframe-common-components/pull/599

<hr>

### 2025-06-30 월 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovCntcSttusController

`CntcSttus` 을 `cntcSttus` 로 이름 바꾸기

`CmmnCodeList` 을 `resultList` 로 이름 바꾸기

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/ssi/syi/ist/web/EgovCntcSttusController.java:61:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'CntcSttus' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/ssi/syi/ist/web/EgovCntcSttusController.java:97:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CmmnCodeList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovCntcSttusController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.06.30  이백행          컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-FormalParameterNamingConventions, LocalVariableNamingConventions
```

https://github.com/eGovFramework/egovframe-common-components/pull/600

<hr>

### 2025-07-01 화 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovSystemCntcController

`CmmnCodeList` 을(를) `resultList` 로 이름 바꾸기

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/ssi/syi/sim/web/EgovSystemCntcController.java:292:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CmmnCodeList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/ssi/syi/sim/web/EgovSystemCntcController.java:461:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CmmnCodeList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovSystemCntcController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.01  이백행          컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(final이 아닌 변수는 밑줄을 포함할 수 없음)
```

https://github.com/eGovFramework/egovframe-common-components/pull/601

<hr>

### 2025-07-01 화 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovBbsStatsController

불필요한 괄호를 제거

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sts/bst/web/EgovBbsStatsController.java:190:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/sts/bst/web/EgovBbsStatsController.java:193:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
```

2. 브랜치 생성

```
feature/pmd/EgovBbsStatsController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.01  이백행          컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-UselessParentheses(불필요한 괄호사용)
```

https://github.com/eGovFramework/egovframe-common-components/pull/602

<hr>

### 2025-07-02 수 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovConectStatsController

불필요한 괄호를 제거

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sts/cst/web/EgovConectStatsController.java:95:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/sts/cst/web/EgovConectStatsController.java:98:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
```

2. 브랜치 생성

```
feature/pmd/EgovConectStatsController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.02  이백행          컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-UselessParentheses(불필요한 괄호사용)
```

https://github.com/eGovFramework/egovframe-common-components/pull/603

<hr>

### 2025-07-02 수 PMD로 소프트웨어 보안약점 진단하고 제거하기-ReprtStatsVO

`getDelYn setDelYn` 을(를) 제거하고 `@Getter @Setter` 로 추가

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sts/rst/service/ReprtStatsVO.java:166:	MethodReturnsInternalArray:	MethodReturnsInternalArray: 'delYn'을 반환하면 내부 배열이 노출될 수 있음
src/main/java/egovframework/com/sts/rst/service/ReprtStatsVO.java:172:	ArrayIsStoredDirectly:	ArrayIsStoredDirectly: 배열 'delYn' 이 직접 저장되어 있음
```

2. 브랜치 생성

```
feature/pmd/ReprtStatsVO
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.02  이백행          컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-MethodReturnsInternalArray(Private 배열에 Public 데이터 할당)
 *   2025.07.02  이백행          컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-ArrayIsStoredDirectly(Public 메소드부터 반환된 Private 배열)
```

https://github.com/eGovFramework/egovframe-common-components/pull/604

<hr>

### 2025-07-03 목 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovScrinStatsController

list_menulist 를 resultMenuList 로 이름 바꾸기

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sts/sst/web/EgovScrinStatsController.java:60:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'list_menulist' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovScrinStatsController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.03  이백행          컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(final이 아닌 변수는 밑줄을 포함할 수 없음)
```

https://github.com/eGovFramework/egovframe-common-components/pull/605

<hr>

### 2025-07-03 목 PMD로 소프트웨어 보안약점 진단하고 제거하기-BatchShellScriptJob

paramtr 로그 추가

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sym/bat/service/BatchShellScriptJob.java:72:	UnusedFormalParameter:	UnusedFormalParameter: 'paramtr' 처럼  사용되지 않는  'method' 파라미터가 있음
```

2. 브랜치 생성

```
feature/pmd/BatchShellScriptJob
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.03  이백행          컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-UnusedFormalParameter(메소드 선언 내에사용되지 않는 파라미터를 탐지)
```

https://github.com/eGovFramework/egovframe-common-components/pull/606

<hr>

### 2025-07-04 금 PMD로 소프트웨어 보안약점 진단하고 제거하기-RestdeVO

불필요한 괄호를 제거

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sym/cal/service/RestdeVO.java:92:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
```

2. 브랜치 생성

```
feature/pmd/RestdeVO
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.04  이백행          컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-UselessParentheses(불필요한 괄호사용)
```

https://github.com/eGovFramework/egovframe-common-components/pull/607

<hr>

### 2025-07-04 금 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovCalRestdeManageController

`bindingResult = ` 제거하고  
`public BindingResult checkRestdeWithValidator` 을(를) `private void checkRestdeWithValidator` 로 수정하고  
`return bindingResult;` 제거

`iMaxWeeks = iMaxWeeks + (int) Math.ceil(((iLastDate - iMaxWeeks * 7) + iStartWeek - 1) / 7.0);` 을(를) `iMaxWeeks = iMaxWeeks + (int) Math.ceil((iLastDate - iMaxWeeks * 7 + iStartWeek - 1) / 7.0);` 로 수정

이름 바꾸기
```
model.addAttribute("resultList_1", CalInfoList_1); resultCalInfo1List
model.addAttribute("resultList_2", CalInfoList_2); resultCalInfo2List
model.addAttribute("resultList_3", CalInfoList_3); resultCalInfo3List
model.addAttribute("resultList_4", CalInfoList_4); resultCalInfo4List
model.addAttribute("resultList_5", CalInfoList_5); resultCalInfo5List
model.addAttribute("resultList_6", CalInfoList_6); resultCalInfo6List
model.addAttribute("resultList_7", CalInfoList_7); resultCalInfo7List
model.addAttribute("RestdeList_1", NormalWeekRestdeList_1); resultNormalWeekRestde1List
model.addAttribute("RestdeList_2", NormalWeekRestdeList_2); resultNormalWeekRestde2List
model.addAttribute("RestdeList_3", NormalWeekRestdeList_3); resultNormalWeekRestde3List
model.addAttribute("RestdeList_4", NormalWeekRestdeList_4); resultNormalWeekRestde4List
model.addAttribute("RestdeList_5", NormalWeekRestdeList_5); resultNormalWeekRestde5List
model.addAttribute("RestdeList_6", NormalWeekRestdeList_6); resultNormalWeekRestde6List
model.addAttribute("RestdeList_7", NormalWeekRestdeList_7); resultNormalWeekRestde7List

model.addAttribute("resultList_1", CalInfoList_1);
model.addAttribute("resultList_2", CalInfoList_2);
model.addAttribute("resultList_3", CalInfoList_3);
model.addAttribute("resultList_4", CalInfoList_4);
model.addAttribute("resultList_5", CalInfoList_5);
model.addAttribute("resultList_6", CalInfoList_6);
model.addAttribute("resultList_7", CalInfoList_7);
model.addAttribute("resultList_8", CalInfoList_8);
model.addAttribute("resultList_9", CalInfoList_9);
model.addAttribute("resultList_10", CalInfoList_10);
model.addAttribute("resultList_11", CalInfoList_11);
model.addAttribute("resultList_12", CalInfoList_12);
model.addAttribute("RestdeList_1", NormalMonthRestdeList_1); resultNormalMonthRestde1List
model.addAttribute("RestdeList_2", NormalMonthRestdeList_2); resultNormalMonthRestde2List
model.addAttribute("RestdeList_3", NormalMonthRestdeList_3); resultNormalMonthRestde3List
model.addAttribute("RestdeList_4", NormalMonthRestdeList_4); resultNormalMonthRestde4List
model.addAttribute("RestdeList_5", NormalMonthRestdeList_5); resultNormalMonthRestde5List
model.addAttribute("RestdeList_6", NormalMonthRestdeList_6); resultNormalMonthRestde6List
model.addAttribute("RestdeList_7", NormalMonthRestdeList_7); resultNormalMonthRestde7List
model.addAttribute("RestdeList_8", NormalMonthRestdeList_8); resultNormalMonthRestde8List
model.addAttribute("RestdeList_9", NormalMonthRestdeList_9); resultNormalMonthRestde9List
model.addAttribute("RestdeList_10", NormalMonthRestdeList_10); resultNormalMonthRestde10List
model.addAttribute("RestdeList_11", NormalMonthRestdeList_11); resultNormalMonthRestde11List
model.addAttribute("RestdeList_12", NormalMonthRestdeList_12); resultNormalMonthRestde12List

model.addAttribute("resultList_1", CalInfoList_1);
model.addAttribute("resultList_2", CalInfoList_2);
model.addAttribute("resultList_3", CalInfoList_3);
model.addAttribute("resultList_4", CalInfoList_4);
model.addAttribute("resultList_5", CalInfoList_5);
model.addAttribute("resultList_6", CalInfoList_6);
model.addAttribute("resultList_7", CalInfoList_7);
model.addAttribute("RestdeList_1", AdministWeekRestdeList_1); resultAdministWeekRestde1List
model.addAttribute("RestdeList_2", AdministWeekRestdeList_2); resultAdministWeekRestde2List
model.addAttribute("RestdeList_3", AdministWeekRestdeList_3); resultAdministWeekRestde3List
model.addAttribute("RestdeList_4", AdministWeekRestdeList_4); resultAdministWeekRestde4List
model.addAttribute("RestdeList_5", AdministWeekRestdeList_5); resultAdministWeekRestde5List
model.addAttribute("RestdeList_6", AdministWeekRestdeList_6); resultAdministWeekRestde6List
model.addAttribute("RestdeList_7", AdministWeekRestdeList_7); resultAdministWeekRestde7List

model.addAttribute("resultList_1", CalInfoList_1);
model.addAttribute("resultList_2", CalInfoList_2);
model.addAttribute("resultList_3", CalInfoList_3);
model.addAttribute("resultList_4", CalInfoList_4);
model.addAttribute("resultList_5", CalInfoList_5);
model.addAttribute("resultList_6", CalInfoList_6);
model.addAttribute("resultList_7", CalInfoList_7);
model.addAttribute("resultList_8", CalInfoList_8);
model.addAttribute("resultList_9", CalInfoList_9);
model.addAttribute("resultList_10", CalInfoList_10);
model.addAttribute("resultList_11", CalInfoList_11);
model.addAttribute("resultList_12", CalInfoList_12);
model.addAttribute("RestdeList_1", AdministMonthRestdeList_1); resultAdministMonthRestde1List
model.addAttribute("RestdeList_2", AdministMonthRestdeList_2); resultAdministMonthRestde2List
model.addAttribute("RestdeList_3", AdministMonthRestdeList_3); resultAdministMonthRestde3List
model.addAttribute("RestdeList_4", AdministMonthRestdeList_4); resultAdministMonthRestde4List
model.addAttribute("RestdeList_5", AdministMonthRestdeList_5); resultAdministMonthRestde5List
model.addAttribute("RestdeList_6", AdministMonthRestdeList_6); resultAdministMonthRestde6List
model.addAttribute("RestdeList_7", AdministMonthRestdeList_7); resultAdministMonthRestde7List
model.addAttribute("RestdeList_8", AdministMonthRestdeList_8); resultAdministMonthRestde8List
model.addAttribute("RestdeList_9", AdministMonthRestdeList_9); resultAdministMonthRestde9List
model.addAttribute("RestdeList_10", AdministMonthRestdeList_10); resultAdministMonthRestde10List
model.addAttribute("RestdeList_11", AdministMonthRestdeList_11); resultAdministMonthRestde11List
model.addAttribute("RestdeList_12", AdministMonthRestdeList_12); resultAdministMonthRestde12List

CalInfoList resultCalInfoList

NormalWeekRestdeList resultNormalWeekRestdeList

NormalMonthRestdeList resultNormalMonthRestdeList

AdministWeekRestdeList resultAdministWeekRestdeList

AdministMonthRestdeList resultAdministMonthRestdeList

CmmnCodeList resultCmmnCodeList

CodeVO codeVO

ComDefaultCodeVO CodeVO comDefaultCodeVO
```

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:108:	AvoidReassigningParameters:	AvoidReassigningParameters: 'bindingResult' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:160:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:225:	AvoidReassigningParameters:	AvoidReassigningParameters: 'bindingResult' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:268:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:301:	AvoidReassigningParameters:	AvoidReassigningParameters: 'bindingResult' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:344:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:364:	AvoidReassigningParameters:	AvoidReassigningParameters: 'bindingResult' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:420:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:421:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'NormalWeekRestdeList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:442:	AvoidReassigningParameters:	AvoidReassigningParameters: 'bindingResult' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:495:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:523:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_1' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:524:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'NormalWeekRestdeList_1' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:532:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_2' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:533:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'NormalWeekRestdeList_2' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:541:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_3' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:542:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'NormalWeekRestdeList_3' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:550:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_4' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:551:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'NormalWeekRestdeList_4' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:559:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_5' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:560:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'NormalWeekRestdeList_5' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:568:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_6' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:569:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'NormalWeekRestdeList_6' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:577:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_7' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:578:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'NormalWeekRestdeList_7' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:595:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:614:	AvoidReassigningParameters:	AvoidReassigningParameters: 'bindingResult' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:657:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:660:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'NormalMonthRestdeList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:681:	AvoidReassigningParameters:	AvoidReassigningParameters: 'bindingResult' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:726:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_1' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:727:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'NormalMonthRestdeList_1' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:735:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_2' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:736:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'NormalMonthRestdeList_2' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:744:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_3' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:745:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'NormalMonthRestdeList_3' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:753:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_4' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:754:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'NormalMonthRestdeList_4' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:762:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_5' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:763:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'NormalMonthRestdeList_5' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:771:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_6' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:772:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'NormalMonthRestdeList_6' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:780:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_7' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:781:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'NormalMonthRestdeList_7' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:789:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_8' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:790:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'NormalMonthRestdeList_8' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:798:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_9' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:799:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'NormalMonthRestdeList_9' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:807:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_10' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:808:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'NormalMonthRestdeList_10' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:816:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_11' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:817:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'NormalMonthRestdeList_11' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:825:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_12' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:826:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'NormalMonthRestdeList_12' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:871:	AvoidReassigningParameters:	AvoidReassigningParameters: 'bindingResult' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:927:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:928:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'AdministWeekRestdeList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:951:	AvoidReassigningParameters:	AvoidReassigningParameters: 'bindingResult' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1004:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1023:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1033:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_1' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1034:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'AdministWeekRestdeList_1' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1042:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_2' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1043:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'AdministWeekRestdeList_2' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1051:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_3' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1052:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'AdministWeekRestdeList_3' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1060:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_4' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1061:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'AdministWeekRestdeList_4' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1069:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_5' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1070:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'AdministWeekRestdeList_5' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1078:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_6' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1079:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'AdministWeekRestdeList_6' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1087:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_7' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1088:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'AdministWeekRestdeList_7' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1123:	AvoidReassigningParameters:	AvoidReassigningParameters: 'bindingResult' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1166:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1169:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'AdministMonthRestdeList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1191:	AvoidReassigningParameters:	AvoidReassigningParameters: 'bindingResult' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1236:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_1' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1237:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'AdministMonthRestdeList_1' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1245:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_2' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1246:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'AdministMonthRestdeList_2' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1254:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_3' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1255:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'AdministMonthRestdeList_3' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1263:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_4' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1264:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'AdministMonthRestdeList_4' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1272:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_5' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1273:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'AdministMonthRestdeList_5' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1281:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_6' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1282:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'AdministMonthRestdeList_6' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1290:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_7' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1291:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'AdministMonthRestdeList_7' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1299:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_8' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1300:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'AdministMonthRestdeList_8' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1308:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_9' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1309:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'AdministMonthRestdeList_9' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1317:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_10' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1318:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'AdministMonthRestdeList_10' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1326:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_11' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1327:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'AdministMonthRestdeList_11' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1335:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CalInfoList_12' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1336:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'AdministMonthRestdeList_12' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1485:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CmmnCodeList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1511:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CodeVO' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/cal/web/EgovCalRestdeManageController.java:1537:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CodeVO' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovCalRestdeManageController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.04  이백행          컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-AvoidReassigningParameters(넘겨받는 메소드 parameter 값을 직접 변경하는 코드 탐지)
 *   2025.07.04  이백행          컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(final이 아닌 변수는 밑줄을 포함할 수 없음)
 *   2025.07.04  이백행          컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-UselessParentheses(불필요한 괄호사용)
```

https://github.com/eGovFramework/egovframe-common-components/pull/608

<hr>

### 2025-07-05 토 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovAdministCodeRecptnServiceImpl

TestEgovAdministCodeRecptnServiceImpl 단위 테스트 추가

`import egovframework.com.cop.cmy.service.impl.EgovCommuManageServiceImpl;` 제거

**nonliteral 을 직접 concatenate 하지 말게 수정**

```java
		sb.append("?" + URLEncoder.encode("serviceKey","UTF-8") + "=" + serviceKey); /*Service Key*/
		sb.append("&" + URLEncoder.encode("pageNo","UTF-8") + "=" + URLEncoder.encode(Integer.toString(pageNo), "UTF-8")); /*페이지번호*/
		sb.append("&" + URLEncoder.encode("numOfRows","UTF-8") + "=" + URLEncoder.encode(Integer.toString(numOfRows), "UTF-8")); /*한 페이지 결과 수*/
		sb.append("&" + URLEncoder.encode("type","UTF-8") + "=" + URLEncoder.encode("JSON", "UTF-8")); /*요청자료형식(XML/JSON) Default: XML*/
		sb.append("&" + URLEncoder.encode("locatadd_nm","UTF-8") + "=" + URLEncoder.encode("서울특별시", "UTF-8")); /*지역주소명(옵션)*/

		// URL
		sb.append("https://apis.data.go.kr/1741000/StanReginCd/getStanReginCdList");

		// Service Key
		sb.append("?");
		sb.append(URLEncoder.encode("serviceKey", "UTF-8"));
		sb.append("=");
		sb.append(serviceKey);

		// 페이지번호
		sb.append("&");
		sb.append(URLEncoder.encode("pageNo", "UTF-8"));
		sb.append("=");
		sb.append(URLEncoder.encode(Integer.toString(pageNo), "UTF-8"));

		// 한 페이지 결과 수
		sb.append("&");
		sb.append(URLEncoder.encode("numOfRows", "UTF-8"));
		sb.append("=");
		sb.append(URLEncoder.encode(Integer.toString(numOfRows), "UTF-8"));

		// 요청자료형식(XML/JSON) Default: XML
		sb.append("&");
		sb.append(URLEncoder.encode("type", "UTF-8"));
		sb.append("=");
		sb.append(URLEncoder.encode("JSON", "UTF-8"));

		// 지역주소명(옵션)
		sb.append("&");
		sb.append(URLEncoder.encode("locatadd_nm", "UTF-8"));
		sb.append("=");
		sb.append(URLEncoder.encode("서울특별시", "UTF-8"));
```

**IOUtils.toString 으로 수정**

```java
        BufferedReader br;
        if (conn.getResponseCode() >= 200 && conn.getResponseCode() <= 300) {

        	br = new BufferedReader(new InputStreamReader(conn.getInputStream()));
        	StringBuilder sb = new StringBuilder();
            String line;
            while ((line = br.readLine()) != null) {
                sb.append(line);
            }
            br.close();

sb.append(IOUtils.toString(conn.getInputStream(), StandardCharsets.UTF_8));
```

**공공데이터포털 행정안전부_행정표준코드_법정동코드**

`인증키 복사(Encoding), URL에서 사용이 가능하도록 인코딩 된 인증키` 사용해야 함

globals.properties
```properties
# 기관코드, 법정동코드 수신용 공공데이터포털 인증키(공공데이터포털에서 발급 받은 후 기입)

# 인증키 복사(Encoding), URL에서 사용이 가능하도록 인코딩 된 인증키
Globals.data.serviceKey=

# 인증키 복사(Decoding), 인코딩 되지 않은 원본 인증키
#Globals.data.serviceKey=
```

https://www.data.go.kr/tcs/dss/selectApiDataDetailView.do?publicDataPk=15077871

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sym/ccm/acr/service/impl/EgovAdministCodeRecptnServiceImpl.java:28:	UnnecessaryImport:	UnnecessaryImport: Unused import 'egovframework.com.cop.cmy.service.impl.EgovCommuManageServiceImpl'
src/main/java/egovframework/com/sym/ccm/acr/service/impl/EgovAdministCodeRecptnServiceImpl.java:116:	InefficientStringBuffering:	InefficientStringBuffering: StringBuffer / StringBuilder 함수 또는 append() 함수에서 nonliteral 을 직접 concatenate 하지 말 것
src/main/java/egovframework/com/sym/ccm/acr/service/impl/EgovAdministCodeRecptnServiceImpl.java:117:	InefficientStringBuffering:	InefficientStringBuffering: StringBuffer / StringBuilder 함수 또는 append() 함수에서 nonliteral 을 직접 concatenate 하지 말 것
src/main/java/egovframework/com/sym/ccm/acr/service/impl/EgovAdministCodeRecptnServiceImpl.java:118:	InefficientStringBuffering:	InefficientStringBuffering: StringBuffer / StringBuilder 함수 또는 append() 함수에서 nonliteral 을 직접 concatenate 하지 말 것
src/main/java/egovframework/com/sym/ccm/acr/service/impl/EgovAdministCodeRecptnServiceImpl.java:119:	InefficientStringBuffering:	InefficientStringBuffering: StringBuffer / StringBuilder 함수 또는 append() 함수에서 nonliteral 을 직접 concatenate 하지 말 것
src/main/java/egovframework/com/sym/ccm/acr/service/impl/EgovAdministCodeRecptnServiceImpl.java:120:	InefficientStringBuffering:	InefficientStringBuffering: StringBuffer / StringBuilder 함수 또는 append() 함수에서 nonliteral 을 직접 concatenate 하지 말 것
src/main/java/egovframework/com/sym/ccm/acr/service/impl/EgovAdministCodeRecptnServiceImpl.java:140:	CloseResource:	CloseResource: 리소스 'BufferedReader' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/sym/ccm/acr/service/impl/EgovAdministCodeRecptnServiceImpl.java:146:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/sym/ccm/acr/service/impl/EgovAdministCodeRecptnServiceImpl.java:192:	CloseResource:	CloseResource: 리소스 'BufferedReader' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/sym/ccm/acr/service/impl/EgovAdministCodeRecptnServiceImpl.java:198:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
```

2. 브랜치 생성

```
feature/pmd/EgovAdministCodeRecptnServiceImpl
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.05  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-UnnecessaryImport(불필요한 import문 선언)
 *   2025.07.05  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-InefficientStringBuffering(StringBuffer 함수내에서 비문자열 연산 이용하여 직접 결합하는 코드 사용을 탐지. append 메소드 사용을 권장)
 *   2025.07.05  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-CloseResource(부적절한 자원 해제)
 *   2025.07.05  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-AssignmentInOperand(피연산자내에 할당문이 사용됨. 해당 코드를 복잡하고 가독성이 떨어지게 만듬)
```

https://github.com/eGovFramework/egovframe-common-components/pull/609

<hr>

### 2025-07-05 토 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovCcmAdministCodeManageController

CmmnCodeList 을(를) resultList 로 이름 바꾸기

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sym/ccm/adc/web/EgovCcmAdministCodeManageController.java:170:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CmmnCodeList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/ccm/adc/web/EgovCcmAdministCodeManageController.java:218:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CmmnCodeList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovCcmAdministCodeManageController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.05  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(final이 아닌 변수는 밑줄을 포함할 수 없음)
```

https://github.com/eGovFramework/egovframe-common-components/pull/610

<hr>

### 2025-07-07 월 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovCcmCmmnCodeManageController

CmmnCodeList 을(를) resultList 로 이름 바꾸기

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sym/ccm/cca/web/EgovCcmCmmnCodeManageController.java:95:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CmmnCodeList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovCcmCmmnCodeManageController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.07  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(final이 아닌 변수는 밑줄을 포함할 수 없음)
```

https://github.com/eGovFramework/egovframe-common-components/pull/611

<hr>

### 2025-07-07 월 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovCcmCmmnClCodeManageController

CmmnCodeList 를 resultList 로 이름 바꾸기

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sym/ccm/ccc/web/EgovCcmCmmnClCodeManageController.java:89:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CmmnCodeList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovCcmCmmnClCodeManageController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.07  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(final이 아닌 변수는 밑줄을 포함할 수 없음)
```

https://github.com/eGovFramework/egovframe-common-components/pull/612

<hr>

### 2025-07-08 화 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovCcmCmmnDetailCodeManageController

CmmnCodeList 를 resultList 로 이름 바꾸기

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sym/ccm/cde/web/EgovCcmCmmnDetailCodeManageController.java:100:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CmmnCodeList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovCcmCmmnDetailCodeManageController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.08  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(final이 아닌 변수는 밑줄을 포함할 수 없음)
```

https://github.com/eGovFramework/egovframe-common-components/pull/614

<hr>

### 2025-07-08 화 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovInsttCodeRecptnServiceImpl

TestEgovInsttCodeRecptnServiceImpl 단위 테스트 추가

불필요한 import문 제거
```java
import egovframework.com.sym.ccm.acr.service.impl.EgovAdministCodeRecptnServiceImpl;
```

append 메소드 사용
```java
//		sb.append("http://apis.data.go.kr/1741000/StanOrgCd2/getStanOrgCdList2"); /*URL*/
//		sb.append("?" + URLEncoder.encode("serviceKey","UTF-8") + "=" + serviceKey); /*Service Key*/
//		sb.append("&" + URLEncoder.encode("pageNo","UTF-8") + "=" + URLEncoder.encode(Integer.toString(pageNo), "UTF-8")); /*페이지번호*/
//		sb.append("&" + URLEncoder.encode("numOfRows","UTF-8") + "=" + URLEncoder.encode(Integer.toString(numOfRows), "UTF-8")); /*한 페이지 결과 수*/
//		sb.append("&" + URLEncoder.encode("type","UTF-8") + "=" + URLEncoder.encode("JSON", "UTF-8")); /*요청자료형식(XML/JSON) Default: XML*/
//		sb.append("&" + URLEncoder.encode("full_nm","UTF-8") + "=" + URLEncoder.encode("행정안전부", "UTF-8")); /*기관명(옵션)*/
//		sb.append("&" + URLEncoder.encode("stop_selt","UTF-8") + "=" + URLEncoder.encode("0", "UTF-8")); /*사용:0, 폐지:1(옵션)*/

		// URL
		sb.append("http://apis.data.go.kr/1741000/StanOrgCd2/getStanOrgCdList2");

		// Service Key
		sb.append("?");
		sb.append(URLEncoder.encode("serviceKey", "UTF-8"));
		sb.append("=");
		sb.append(serviceKey);

		// 페이지번호
		sb.append("&");
		sb.append(URLEncoder.encode("pageNo", "UTF-8"));
		sb.append("=");
		sb.append(URLEncoder.encode(Integer.toString(pageNo), "UTF-8"));

		// 한 페이지 결과 수
		sb.append("&");
		sb.append(URLEncoder.encode("numOfRows", "UTF-8"));
		sb.append("=");
		sb.append(URLEncoder.encode(Integer.toString(numOfRows), "UTF-8"));

		// 요청자료형식(XML/JSON) Default: XML
		sb.append("&");
		sb.append(URLEncoder.encode("type", "UTF-8"));
		sb.append("=");
		sb.append(URLEncoder.encode("JSON", "UTF-8"));

		// 기관명(옵션)
		sb.append("&");
		sb.append(URLEncoder.encode("full_nm", "UTF-8"));
		sb.append("=");
		sb.append(URLEncoder.encode("행정안전부", "UTF-8"));

		// 사용:0, 폐지:1(옵션)
		sb.append("&");
		sb.append(URLEncoder.encode("stop_selt", "UTF-8"));
		sb.append("=");
		sb.append(URLEncoder.encode("0", "UTF-8"));
```

CloseResource(부적절한 자원 해제), AssignmentInOperand(피연산자내에 할당문이 사용됨. 해당 코드를 복잡하고 가독성이 떨어지게 만듬)
```java
public static int numberOfRows() throws IOException, ParseException {
...
//        BufferedReader br;
//        if (conn.getResponseCode() >= 200 && conn.getResponseCode() <= 300) {
//
//        	br = new BufferedReader(new InputStreamReader(conn.getInputStream()));
//        	StringBuilder sb = new StringBuilder();
//            String line;
//            while ((line = br.readLine()) != null) {
//                sb.append(line);
//            }
//            br.close();
//
//            JSONParser jsonParser = new JSONParser();
//            JSONObject jsonObject = (JSONObject) jsonParser.parse(sb.toString());

		if (conn.getResponseCode() >= 200 && conn.getResponseCode() <= 300) {
			JSONParser jsonParser = new JSONParser();
			String s = IOUtils.toString(conn.getInputStream(), StandardCharsets.UTF_8);
			if (LOGGER.isDebugEnabled()) {
				LOGGER.debug("s={}", s);
			}
			JSONObject jsonObject = (JSONObject) jsonParser.parse(s);

...
public static List<HashMap<String, String>> apiLink() throws IOException, ParseException {
...
//	        BufferedReader br;
//	        if (conn.getResponseCode() >= 200 && conn.getResponseCode() <= 300) {
//
//	        	br = new BufferedReader(new InputStreamReader(conn.getInputStream()));
//	        	StringBuilder sb = new StringBuilder();
//	            String line;
//	            while ((line = br.readLine()) != null) {
//	                sb.append(line);
//	            }
//	            br.close();
//
//	            JSONParser jsonParser = new JSONParser();
//	            JSONObject jsonObject = (JSONObject) jsonParser.parse(sb.toString());

			if (conn.getResponseCode() >= 200 && conn.getResponseCode() <= 300) {
				JSONParser jsonParser = new JSONParser();
				String s = IOUtils.toString(conn.getInputStream(), StandardCharsets.UTF_8);
				if (LOGGER.isDebugEnabled()) {
					LOGGER.debug("s={}", s);
				}
				JSONObject jsonObject = (JSONObject) jsonParser.parse(s);
```

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sym/ccm/icr/service/impl/EgovInsttCodeRecptnServiceImpl.java:28:	UnnecessaryImport:	UnnecessaryImport: Unused import 'egovframework.com.sym.ccm.acr.service.impl.EgovAdministCodeRecptnServiceImpl'
src/main/java/egovframework/com/sym/ccm/icr/service/impl/EgovInsttCodeRecptnServiceImpl.java:126:	InefficientStringBuffering:	InefficientStringBuffering: StringBuffer / StringBuilder 함수 또는 append() 함수에서 nonliteral 을 직접 concatenate 하지 말 것
src/main/java/egovframework/com/sym/ccm/icr/service/impl/EgovInsttCodeRecptnServiceImpl.java:127:	InefficientStringBuffering:	InefficientStringBuffering: StringBuffer / StringBuilder 함수 또는 append() 함수에서 nonliteral 을 직접 concatenate 하지 말 것
src/main/java/egovframework/com/sym/ccm/icr/service/impl/EgovInsttCodeRecptnServiceImpl.java:128:	InefficientStringBuffering:	InefficientStringBuffering: StringBuffer / StringBuilder 함수 또는 append() 함수에서 nonliteral 을 직접 concatenate 하지 말 것
src/main/java/egovframework/com/sym/ccm/icr/service/impl/EgovInsttCodeRecptnServiceImpl.java:129:	InefficientStringBuffering:	InefficientStringBuffering: StringBuffer / StringBuilder 함수 또는 append() 함수에서 nonliteral 을 직접 concatenate 하지 말 것
src/main/java/egovframework/com/sym/ccm/icr/service/impl/EgovInsttCodeRecptnServiceImpl.java:130:	InefficientStringBuffering:	InefficientStringBuffering: StringBuffer / StringBuilder 함수 또는 append() 함수에서 nonliteral 을 직접 concatenate 하지 말 것
src/main/java/egovframework/com/sym/ccm/icr/service/impl/EgovInsttCodeRecptnServiceImpl.java:131:	InefficientStringBuffering:	InefficientStringBuffering: StringBuffer / StringBuilder 함수 또는 append() 함수에서 nonliteral 을 직접 concatenate 하지 말 것
src/main/java/egovframework/com/sym/ccm/icr/service/impl/EgovInsttCodeRecptnServiceImpl.java:151:	CloseResource:	CloseResource: 리소스 'BufferedReader' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/sym/ccm/icr/service/impl/EgovInsttCodeRecptnServiceImpl.java:157:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/sym/ccm/icr/service/impl/EgovInsttCodeRecptnServiceImpl.java:203:	CloseResource:	CloseResource: 리소스 'BufferedReader' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/sym/ccm/icr/service/impl/EgovInsttCodeRecptnServiceImpl.java:209:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
```

2. 브랜치 생성

```
feature/pmd/EgovInsttCodeRecptnServiceImpl
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.08  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-UnnecessaryImport(불필요한 import문 선언)
 *   2025.07.08  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-InefficientStringBuffering(StringBuffer 함수내에서 비문자열 연산 이용하여 직접 결합하는 코드 사용을 탐지. append 메소드 사용을 권장)
 *   2025.07.08  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-CloseResource(부적절한 자원 해제)
 *   2025.07.08  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-AssignmentInOperand(피연산자내에 할당문이 사용됨. 해당 코드를 복잡하고 가독성이 떨어지게 만듬)
```

https://github.com/eGovFramework/egovframe-common-components/pull/616

<hr>

### 2025-07-09 수 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovCcmZipManageController

CmmnCodeList 를 resultList 로 이름 바꾸기

try-catch-finally 를 try-with-resources 로 교체

불필요한 괄호제거

```java
public String selectZipSearchList(@ModelAttribute("searchVO") ZipVO searchVO, ModelMap model) throws Exception {
...
		if (!sList.equals("2")) {
//			List<EgovMap> CmmnCodeList = zipManageService.selectZipList(searchVO);
//			model.addAttribute("resultList", CmmnCodeList);
			List<EgovMap> resultList = zipManageService.selectZipList(searchVO);
			model.addAttribute("resultList", resultList);
		} else {
			List<EgovMap> CmmnCodeList = rdnmadZipService.selectZipList(searchVO);
			model.addAttribute("resultList", CmmnCodeList);
...
public String insertZip(@ModelAttribute("loginVO") LoginVO loginVO
...
//model.addAttribute("isRoadAddr", ("2".equals(searchVO.getSearchList()))); // true : 도로명주소등록, false : 일반주소등록
model.addAttribute("isRoadAddr", "2".equals(searchVO.getSearchList())); // true : 도로명주소등록, false : 일반주소등록
...
public String insertZip(@ModelAttribute("loginVO") LoginVO loginVO
...
//boolean isRoadAddr = ("2".equals(searchVO.getSearchList()));
boolean isRoadAddr = "2".equals(searchVO.getSearchList());
...
public String insertExcelZip(
...
//					InputStream fis = null;
//
//					try {
//						fis = file.getInputStream();
//						if (searchVO.getSearchList().equals("1")) {
//							zipManageService.insertExcelZip(fis);
//						} else {
//							rdnmadZipService.insertExcelZip(fis);
//						}
//					} catch (IOException e) {
//						throw new IOException(e);
//					} finally {
//						EgovResourceCloseHelper.close(fis);
//					}

// try-catch-finally 를 try-with-resources 로 교체
					try (InputStream fis = file.getInputStream();) {
						if (searchVO.getSearchList().equals("1")) {
							zipManageService.insertExcelZip(fis);
						} else {
							rdnmadZipService.insertExcelZip(fis);
						}
					}
...
public String selectZipList(@ModelAttribute("loginVO") LoginVO loginVO, @ModelAttribute("searchVO") ZipVO searchVO,
...
//		if (!searchVO.getSearchList().equals("2")) {
//			List<EgovMap> CmmnCodeList = zipManageService.selectZipList(searchVO);
//			model.addAttribute("resultList", CmmnCodeList);
//
//			int totCnt = zipManageService.selectZipListTotCnt(searchVO);
//			paginationInfo.setTotalRecordCount(totCnt);
//			model.addAttribute("paginationInfo", paginationInfo);
//		} else {
//			List<EgovMap> CmmnCodeList = rdnmadZipService.selectZipList(searchVO);
//			model.addAttribute("resultList", CmmnCodeList);

		if (!searchVO.getSearchList().equals("2")) {
			List<EgovMap> resultList = zipManageService.selectZipList(searchVO);
			model.addAttribute("resultList", resultList);
...
		} else {
			List<EgovMap> resultList = rdnmadZipService.selectZipList(searchVO);
			model.addAttribute("resultList", resultList);
...
@RequestMapping(value = "/sym/ccm/zip/EgovCcmZipModifyView.do")
public String updateZip(@ModelAttribute("loginVO") LoginVO loginVO
...
//boolean isRoadAddr = ("2".equals(searchVO.getSearchList()));
boolean isRoadAddr = "2".equals(searchVO.getSearchList());
...
@RequestMapping(value = "/sym/ccm/zip/EgovCcmZipModify.do")
public String updateZip(@ModelAttribute("loginVO") LoginVO loginVO
//boolean isRoadAddr = ("2".equals(searchVO.getSearchList()));
boolean isRoadAddr = "2".equals(searchVO.getSearchList());
```

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sym/ccm/zip/web/EgovCcmZipManageController.java:126:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CmmnCodeList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/ccm/zip/web/EgovCcmZipManageController.java:133:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CmmnCodeList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/ccm/zip/web/EgovCcmZipManageController.java:177:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/sym/ccm/zip/web/EgovCcmZipManageController.java:199:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/sym/ccm/zip/web/EgovCcmZipManageController.java:270:	CloseResource:	CloseResource: 리소스 'InputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/sym/ccm/zip/web/EgovCcmZipManageController.java:347:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CmmnCodeList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/ccm/zip/web/EgovCcmZipManageController.java:354:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CmmnCodeList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/ccm/zip/web/EgovCcmZipManageController.java:379:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/sym/ccm/zip/web/EgovCcmZipManageController.java:410:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
```

2. 브랜치 생성

```
feature/pmd/EgovCcmZipManageController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.09  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(final이 아닌 변수는 밑줄을 포함할 수 없음)
 *   2025.07.09  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-UselessParentheses(불필요한 괄호사용)
 *   2025.07.09  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-CloseResource(부적절한 자원 해제)
```

https://github.com/eGovFramework/egovframe-common-components/pull/618

<hr>

### 2025-07-09 수 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovLoginLogAspect

EgovUserDetailsHelper.isAuthenticated() 을 loginVO != null 로 수정

user 를 loginVO 로 이름 바꾸기

접속ID와 접속IP는 NULL 이라서 공백보다는 NULL 로 저장하는 것이 좋을 것 같음
```sql
  `CONECT_ID` varchar(20) DEFAULT NULL COMMENT '접속ID',
  `CONECT_IP` varchar(23) DEFAULT NULL COMMENT '접속IP',
```

```java
//		String uniqId = "";
//		String ip = "";

		String uniqId = null;
		String ip = null;

//		/* Authenticated  */
//        Boolean isAuthenticated = EgovUserDetailsHelper.isAuthenticated();
//    	if(isAuthenticated.booleanValue()) {
//			LoginVO user = (LoginVO)EgovUserDetailsHelper.getAuthenticatedUser();
//			uniqId = (user == null || user.getUniqId() == null) ? "" : user.getUniqId();
//			ip = (user == null || user.getIp() == null) ? "" : user.getIp();
//    	}

		LoginVO loginVO = (LoginVO) EgovUserDetailsHelper.getAuthenticatedUser();
		// loginVO != null 한 번만
		if (loginVO != null) {
			uniqId = loginVO.getUniqId();
			ip = loginVO.getIp();
		}
...
//		String uniqId = "";
//		String ip = "";

		String uniqId = null;
		String ip = null;

//		/* Authenticated  */
//        Boolean isAuthenticated = EgovUserDetailsHelper.isAuthenticated();
//    	if(isAuthenticated.booleanValue()) {
//			LoginVO user = (LoginVO)EgovUserDetailsHelper.getAuthenticatedUser();
//			uniqId = (user == null || user.getUniqId() == null) ? "" : user.getUniqId();
//			ip = (user == null || user.getIp() == null) ? "" : user.getIp();
//    	}

		LoginVO loginVO = (LoginVO) EgovUserDetailsHelper.getAuthenticatedUser();
		if (loginVO != null) {
			uniqId = loginVO.getUniqId();
			ip = loginVO.getIp();
		}
```

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sym/log/clg/service/EgovLoginLogAspect.java:44:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 explicit unboxing
src/main/java/egovframework/com/sym/log/clg/service/EgovLoginLogAspect.java:75:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 explicit unboxing
```

2. 브랜치 생성

```
feature/pmd/EgovLoginLogAspect
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.09  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-UnnecessaryBoxing(불필요한 WrapperObject 생성)
```

https://github.com/eGovFramework/egovframe-common-components/pull/619

<hr>

### 2025-07-10 목 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovLoginLogServiceImpl

_result 를 resultList 로 이름 바꾸기

_cnt 를 resultCnt 로 이름 바꾸기

_map 을 map 으로 이름 바꾸기

Integer.toString 불필요한 형 변환 제거

```java
//	public Map<?, ?> selectLoginLogInf(LoginLog loinLog) throws Exception {
//		List<LoginLog> _result = loginLogDAO.selectLoginLogInf(loinLog);
//		int _cnt = loginLogDAO.selectLoginLogInfCnt(loinLog);
//
//		Map<String, Object> _map = new HashMap<>();
//		_map.put("resultList", _result);
//		_map.put("resultCnt", Integer.toString(_cnt));
//		return _map;

	public Map<?, ?> selectLoginLogInf(LoginLog loinLog) throws Exception {
		List<LoginLog> resultList = loginLogDAO.selectLoginLogInf(loinLog);
		int resultCnt = loginLogDAO.selectLoginLogInfCnt(loinLog);

		Map<String, Object> map = new HashMap<>();
		map.put("resultList", resultList);
		map.put("resultCnt", resultCnt);

		return map;
	}
```

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sym/log/clg/service/impl/EgovLoginLogServiceImpl.java:76:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/log/clg/service/impl/EgovLoginLogServiceImpl.java:77:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_cnt' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/log/clg/service/impl/EgovLoginLogServiceImpl.java:79:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_map' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovLoginLogServiceImpl
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.10  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(final이 아닌 변수는 밑줄을 포함할 수 없음)
```

https://github.com/eGovFramework/egovframe-common-components/pull/622


<hr>

### 2025-07-10 목 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovLoginLogController

`_map` 을 `map` 으로 이름 바꾸기

`HashMap` 을 `Map` 으로 수정하고 불필요한 형 변환 `(HashMap<?, ?>)` 제거

resultCnt int 로 형 변환하고 불필요한 Integer.parseInt 제거

`map.get("resultCnt")` 를 totCnt 로 수정

```java
//@RequestMapping(value="/sym/log/clg/SelectLoginLogList.do")
//...
//		HashMap<?, ?> _map = (HashMap<?, ?>)loginLogService.selectLoginLogInf(loginLog);
//		int totCnt = Integer.parseInt((String)_map.get("resultCnt"));
//
//		model.addAttribute("resultList", _map.get("resultList"));
//		model.addAttribute("resultCnt", _map.get("resultCnt"));

		Map<?, ?> map = loginLogService.selectLoginLogInf(loginLog);
		int totCnt = (int) map.get("resultCnt");

		model.addAttribute("resultList", map.get("resultList"));
		model.addAttribute("resultCnt", totCnt);
```

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sym/log/clg/web/EgovLoginLogController.java:70:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_map' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovLoginLogController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.10  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(final이 아닌 변수는 밑줄을 포함할 수 없음)
```

https://github.com/eGovFramework/egovframe-common-components/pull/623

<hr>

### 2025-07-11 금 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovSysLogAspect

`String uniqId = "";`, `String ip = "";` 제거

`Boolean isAuthenticated = EgovUserDetailsHelper.isAuthenticated();` 제거

`user` 를 `loginVO` 로 이름 바꾸기

`if(isAuthenticated.booleanValue()) {` 을 `if (loginVO != null) {` 로 수정

```sql
COMTNSYSLOG 시스템로그
  `RQESTER_IP` varchar(23) DEFAULT NULL COMMENT '요청자IP',
  `RQESTER_ID` varchar(20) DEFAULT NULL COMMENT '요청자ID',
```

```java
//			String uniqId = "";
//			String ip = "";
//
//	    	/* Authenticated  */
//	        Boolean isAuthenticated = EgovUserDetailsHelper.isAuthenticated();
//	    	if(isAuthenticated.booleanValue()) {
//				LoginVO user = (LoginVO)EgovUserDetailsHelper.getAuthenticatedUser();
//				uniqId = (user == null || user.getUniqId() == null) ? "" : user.getUniqId();
//			    ip = (user == null || user.getIp() == null) ? "" : user.getIp();
//	    	}

			LoginVO loginVO = (LoginVO) EgovUserDetailsHelper.getAuthenticatedUser();
			if (loginVO != null) {
				sysLog.setRqesterId(loginVO.getUniqId());
				sysLog.setRqesterIp(loginVO.getIp());
			}
```

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sym/log/lgm/service/EgovSysLogAspect.java:64:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 explicit unboxing
src/main/java/egovframework/com/sym/log/lgm/service/EgovSysLogAspect.java:115:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 explicit unboxing
src/main/java/egovframework/com/sym/log/lgm/service/EgovSysLogAspect.java:166:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 explicit unboxing
src/main/java/egovframework/com/sym/log/lgm/service/EgovSysLogAspect.java:217:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 explicit unboxing
```

2. 브랜치 생성

```
feature/pmd/EgovSysLogAspect
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.11  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-UnnecessaryBoxing(불필요한 WrapperObject 생성)
```

https://github.com/eGovFramework/egovframe-common-components/pull/626

<hr>

### 2025-07-11 금 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovSysLogServiceImpl

`_result` 를 `resultList` 로 이름 바꾸기

`_cnt` 를 `resultCnt` 로 이름 바꾸기

`_map` 을 `map` 으로 이름 바꾸기

`new HashMap<String, Object>()` 을 `String, Object` 제거하고 `new HashMap<>()` 로 수정

`Integer.toString` 제거

```java
//	/**
//	 * 시스템 로그정보 목록을 조회한다.
//	 *
//	 * @param SysLog
//	 */
//	@Override
//	public Map<?, ?> selectSysLogInf(SysLog sysLog) throws Exception {
//
//		List<SysLog> _result = sysLogDAO.selectSysLogInf(sysLog);
//		int _cnt = sysLogDAO.selectSysLogInfCnt(sysLog);
//
//		Map<String, Object> _map = new HashMap<String, Object>();
//		_map.put("resultList", _result);
//		_map.put("resultCnt", Integer.toString(_cnt));
//
//		return _map;
//	}

		List<SysLog> resultList = sysLogDAO.selectSysLogInf(sysLog);
		int resultCnt = sysLogDAO.selectSysLogInfCnt(sysLog);

		Map<String, Object> map = new HashMap<>();
		map.put("resultList", resultList);
		map.put("resultCnt", resultCnt);

		return map;
	}
```

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sym/log/lgm/service/impl/EgovSysLogServiceImpl.java:73:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/log/lgm/service/impl/EgovSysLogServiceImpl.java:74:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_cnt' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/log/lgm/service/impl/EgovSysLogServiceImpl.java:76:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_map' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovSysLogServiceImpl
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.11  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(final이 아닌 변수는 밑줄을 포함할 수 없음)
```

https://github.com/eGovFramework/egovframe-common-components/pull/627

<hr>

### 2025-07-12 토 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovSysLogController

`_map` 을 `map` 으로 이름 바꾸기

불필요한 형 변환 제거 `(HashMap<?, ?>), Integer.parseInt((String) map.get("resultCnt"))`

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sym/log/lgm/web/EgovSysLogController.java:74:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_map' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovSysLogController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.12  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(final이 아닌 변수는 밑줄을 포함할 수 없음)
```

https://github.com/eGovFramework/egovframe-common-components/pull/628

<hr>

### 2025-07-12 토 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovPrivacyLogAspect

`++count >= maxListCount` 피연산자내에 할당문이 사용 제거

`isAuthenticated.booleanValue` 를 `loginVO != null` 로 수정

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sym/log/plg/service/EgovPrivacyLogAspect.java:77:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/sym/log/plg/service/EgovPrivacyLogAspect.java:157:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 explicit unboxing
```

2. 브랜치 생성

```
feature/pmd/EgovPrivacyLogAspect
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.12  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-AssignmentInOperand(피연산자내에 할당문이 사용됨. 해당 코드를 복잡하고 가독성이 떨어지게 만듬)
 *   2025.07.12  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-UnnecessaryBoxing(불필요한 WrapperObject 생성)
```

https://github.com/eGovFramework/egovframe-common-components/pull/629


<hr>

### 2025-07-14 월 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovSysHistoryController

`_result, _atchFileId, _cnt` 를 카멜 케이스로 이름 바꾸기

`EgovUserDetailsHelper.isAuthenticated()` 를 `loginVO != null` 로 수정

`user` 를 `loginVO` 로 이름 바꾸기

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sym/log/slg/web/EgovSysHistoryController.java:95:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/log/slg/web/EgovSysHistoryController.java:102:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/log/slg/web/EgovSysHistoryController.java:103:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/log/slg/web/EgovSysHistoryController.java:131:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/log/slg/web/EgovSysHistoryController.java:162:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/log/slg/web/EgovSysHistoryController.java:168:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/log/slg/web/EgovSysHistoryController.java:173:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/log/slg/web/EgovSysHistoryController.java:179:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_cnt' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/log/slg/web/EgovSysHistoryController.java:180:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/log/slg/web/EgovSysHistoryController.java:210:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovSysHistoryController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.14  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(final이 아닌 변수는 밑줄을 포함할 수 없음)
```

https://github.com/eGovFramework/egovframe-common-components/pull/631

<hr>

### 2025-07-14 월 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovUserLogServiceImpl

`_result, _cnt, _map` 을 명시적으로 DTO 기반 반환으로 수정

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sym/log/ulg/service/impl/EgovUserLogServiceImpl.java:69:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/log/ulg/service/impl/EgovUserLogServiceImpl.java:70:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_cnt' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/log/ulg/service/impl/EgovUserLogServiceImpl.java:72:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_map' 이  '[a-z][a-zA-Z0-9]*'  로 시작함

src/main/java/egovframework/com/sym/log/ulg/web/EgovUserLogController.java:73:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_map' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovUserLogServiceImpl
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.14  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(final이 아닌 변수는 밑줄을 포함할 수 없음)
```

https://github.com/eGovFramework/egovframe-common-components/pull/632

<hr>

### 2025-07-15 화 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovWebLogInterceptor

`isAuthenticated.booleanValue()` 를 `loginVO != null` 로 수정

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sym/log/wlg/web/EgovWebLogInterceptor.java:53:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 explicit unboxing
```

2. 브랜치 생성

```
feature/pmd/EgovWebLogInterceptor
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.15  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-UnnecessaryBoxing(불필요한 WrapperObject 생성)
```

https://github.com/eGovFramework/egovframe-common-components/pull/633

<hr>

### 2025-07-15 화 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovBkmkMenuManageservice

`BkmkMenuManage` 를 `bkmkMenuManage` 로 이름 바꾸기

`EgovBkmkMenuManageservice` 를 `EgovBkmkMenuManageService` 대문자로 이름 바꾸기

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sym/mnu/bmm/service/EgovBkmkMenuManageservice.java:34:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'BkmkMenuManage' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovBkmkMenuManageservice
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.15  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-FormalParameterNamingConventions(변수명에 밑줄 사용)
```

https://github.com/eGovFramework/egovframe-common-components/pull/634

<hr>

### 2025-07-16 수 PMD로 소프트웨어 보안약점 진단하고 제거하기-MenuSiteMapVO

`tmp_Id` 를 `tmpId` 로 이름 바꾸기

`tmp_Password` 를 `tmpPassword` 로 이름 바꾸기

`tmp_Name` 를 `tmpName` 로 이름 바꾸기

`tmp_UserSe` 를 `tmpUserSe` 로 이름 바꾸기

`tmp_Email` 를 `tmpEmail` 로 이름 바꾸기

`tmp_OrgnztId` 를 `tmpOrgnztId` 로 이름 바꾸기

`tmp_UniqId` 를 `tmpUniqId` 로 이름 바꾸기

`tmp_Cmd` 를 `tmpCmd` 로 이름 바꾸기

`tmp_rootPath` 를 `tmprootPath` 로 이름 바꾸기

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sym/mnu/mcm/service/MenuSiteMapVO.java:204:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'tmp_Id' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mcm/service/MenuSiteMapVO.java:218:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'tmp_Password' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mcm/service/MenuSiteMapVO.java:232:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'tmp_Name' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mcm/service/MenuSiteMapVO.java:246:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'tmp_UserSe' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mcm/service/MenuSiteMapVO.java:260:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'tmp_Email' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mcm/service/MenuSiteMapVO.java:274:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'tmp_OrgnztId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mcm/service/MenuSiteMapVO.java:288:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'tmp_UniqId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mcm/service/MenuSiteMapVO.java:302:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'tmp_Cmd' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mcm/service/MenuSiteMapVO.java:317:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'tmp_rootPath' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/MenuSiteMapVO
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.16  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-FormalParameterNamingConventions(변수명에 밑줄 사용)
```

https://github.com/eGovFramework/egovframe-common-components/pull/637

<hr>

### 2025-07-16 수 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovMenuCreateManageServiceImpl

`AuthorCnt` 를 `resultMenuCreatCnt` 로 이름 바꾸기

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sym/mnu/mcm/service/impl/EgovMenuCreateManageServiceImpl.java:71:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'AuthorCnt' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovMenuCreateManageServiceImpl
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.16  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(final이 아닌 변수는 밑줄을 포함할 수 없음)
```

https://github.com/eGovFramework/egovframe-common-components/pull/638

<hr>

### 2025-07-17 목 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovMenuCreateManageController

`list_menulist` 를 `resultList` 로 이름 바꾸기

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sym/mnu/mcm/web/EgovMenuCreateManageController.java:188:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'list_menulist' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mcm/web/EgovMenuCreateManageController.java:279:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'list_menulist' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovMenuCreateManageController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.17  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(final이 아닌 변수는 밑줄을 포함할 수 없음)
```

https://github.com/eGovFramework/egovframe-common-components/pull/641

<hr>

### 2025-07-17 목 PMD로 소프트웨어 보안약점 진단하고 제거하기-MenuManageVO

`tmp_Id` 를 `tmpId` 로 이름 바꾸기

`tmp_Password` 를 `tmpPassword` 로 이름 바꾸기

`tmp_Name` 을 `tmpName` 로 이름 바꾸기

`tmp_UserSe` 를 `tmpUserSe` 로 이름 바꾸기

`tmp_Email` 을 `tmpEmail` 로 이름 바꾸기

`tmp_OrgnztId` 를 `tmpOrgnztId` 로 이름 바꾸기

`tmp_Cmd` 를 `tmpCmd` 로 이름 바꾸기

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sym/mnu/mpm/service/MenuManageVO.java:223:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'tmp_Id' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mpm/service/MenuManageVO.java:237:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'tmp_Password' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mpm/service/MenuManageVO.java:251:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'tmp_Name' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mpm/service/MenuManageVO.java:265:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'tmp_UserSe' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mpm/service/MenuManageVO.java:279:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'tmp_Email' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mpm/service/MenuManageVO.java:293:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'tmp_OrgnztId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mpm/service/MenuManageVO.java:321:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'tmp_Cmd' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/MenuManageVO
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.17  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-FormalParameterNamingConventions(변수명에 밑줄 사용)
```

https://github.com/eGovFramework/egovframe-common-components/pull/642

<hr>

### 2025-07-18 금 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovMenuManageServiceImpl

`불필요한 WrapperObject 생성` 대신 Primitive 사용

안전한 방식 (셀 null 체크 + 숫자 여부 확인 포함)
```java
					if (cell != null && cell.getCellType() == CellType.NUMERIC) {
						vo.setMenuNo((int) cell.getNumericCellValue());
					}
```

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sym/mnu/mpm/service/impl/EgovMenuManageServiceImpl.java:476:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 explicit boxing
src/main/java/egovframework/com/sym/mnu/mpm/service/impl/EgovMenuManageServiceImpl.java:481:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 explicit boxing
src/main/java/egovframework/com/sym/mnu/mpm/service/impl/EgovMenuManageServiceImpl.java:490:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 explicit boxing
```

2. 브랜치 생성

```
feature/pmd/EgovMenuManageServiceImpl
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.18  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-UnnecessaryBoxing(불필요한 WrapperObject 생성)
```

https://github.com/eGovFramework/egovframe-common-components/pull/643

<hr>

### 2025-07-18 금 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovMainMenuManageController

`list_headmenu` 를 `resultList` 로 이름 바꾸기

`list_menulist` 를 `resultList` 로 이름 바꾸기

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sym/mnu/mpm/web/EgovMainMenuManageController.java:111:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'list_headmenu' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mpm/web/EgovMainMenuManageController.java:145:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'list_headmenu' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mpm/web/EgovMainMenuManageController.java:185:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'list_menulist' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mpm/web/EgovMainMenuManageController.java:242:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'list_headmenu' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovMainMenuManageController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.18  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(final이 아닌 변수는 밑줄을 포함할 수 없음)
```

https://github.com/eGovFramework/egovframe-common-components/pull/644

<hr>

### 2025-07-19 토 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovMenuManageController

`req_menuNo` 를 `searchKeyword` 로 이름 바꾸기

`_MenuNm` 을 `menuManageVO.setMenuNm("%");` 로 수정

`list_menulist` 를 `resultList` 로 이름 바꾸기

`InputStream is = null;` 를 try-with-resources 로 수정

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sym/mnu/mpm/web/EgovMenuManageController.java:98:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'req_menuNo' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mpm/web/EgovMenuManageController.java:317:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_MenuNm' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mpm/web/EgovMenuManageController.java:342:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'list_menulist' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mpm/web/EgovMenuManageController.java:486:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'list_menulist' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mpm/web/EgovMenuManageController.java:509:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'list_menulist' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/mnu/mpm/web/EgovMenuManageController.java:593:	CloseResource:	CloseResource: 리소스 'InputStream' 가 사용 후에 닫혔는지 확인필요
```

2. 브랜치 생성

```
feature/pmd/EgovMenuManageController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.19  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-FormalParameterNamingConventions(변수명에 밑줄 사용)
 *   2025.07.19  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(final이 아닌 변수는 밑줄을 포함할 수 없음)
 *   2025.07.19  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-CloseResource(부적절한 자원 해제)
```

https://github.com/eGovFramework/egovframe-common-components/pull/645

<hr>

### 2025-07-19 토 PMD로 소프트웨어 보안약점 진단하고 제거하기-ProgrmManageDtlVO

`tmp_progrmNm` 를 `tmpProgrmNm` 로 이름 바꾸기

`tmp_rqesterNo` 를 `tmpRqesterNo` 로 이름 바꾸기

`tmp_Email` 를 `tmpEmail` 로 이름 바꾸기

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sym/prm/service/ProgrmManageDtlVO.java:234:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'tmp_progrmNm' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/prm/service/ProgrmManageDtlVO.java:248:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'tmp_rqesterNo' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/prm/service/ProgrmManageDtlVO.java:263:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'tmp_Email' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/ProgrmManageDtlVO
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.19  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-FormalParameterNamingConventions(변수명에 밑줄 사용)
```

https://github.com/eGovFramework/egovframe-common-components/pull/646

<hr>

### 2025-07-21 월 PMD로 소프트웨어 보안약점 진단하고 제거하기-ProgrmManageVO

`URL` 을 `url` 로 이름 바꾸기

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sym/prm/service/ProgrmManageVO.java:94:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'URL' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/ProgrmManageVO
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.21  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-FormalParameterNamingConventions(변수명에 밑줄 사용)
```

https://github.com/eGovFramework/egovframe-common-components/pull/648

<hr>

### 2025-07-21 월 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovProgrmManageController

`tmp_progrmNm` 을 `progrmFileNm` 로 이름 바꾸기

`list_changerequst` 을 `resultList` 로 이름 바꾸기

`String FileNm` 을 `progrmManageDtlVO.setProgrmFileNm(progrmManageDtlVO.getTmpProgrmNm());` 로 수정

`tmp_vo` 를 `resultVO` 로 이름 바꾸기

`int _tmp_no` 를 `resultVO.setRqesterNo(resultProgrmManageDtlVO.getRqesterNo());` 로 수정

`String _FileNm` 를 `progrmManageDtlVO.setProgrmFileNm(progrmManageDtlVO.getTmpProgrmNm());` 로 수정

`int _Tmp_no` 를 `progrmManageDtlVO.setRqesterNo(progrmManageDtlVO.getTmpRqesterNo());` 로 수정

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sym/prm/web/EgovProgrmManageController.java:81:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'tmp_progrmNm' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/prm/web/EgovProgrmManageController.java:321:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'list_changerequst' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/prm/web/EgovProgrmManageController.java:349:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'FileNm' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/prm/web/EgovProgrmManageController.java:400:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'tmp_vo' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/prm/web/EgovProgrmManageController.java:401:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_tmp_no' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/prm/web/EgovProgrmManageController.java:522:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'list_changerequst' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/prm/web/EgovProgrmManageController.java:550:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_FileNm' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/prm/web/EgovProgrmManageController.java:552:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_Tmp_no' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/prm/web/EgovProgrmManageController.java:696:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'list_changerequst' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/prm/web/EgovProgrmManageController.java:724:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_FileNm' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/sym/prm/web/EgovProgrmManageController.java:726:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_tmp_no' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovProgrmManageController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.21  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-FormalParameterNamingConventions(변수명에 밑줄 사용)
 *   2025.07.21  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(final이 아닌 변수는 밑줄을 포함할 수 없음)
```

https://github.com/eGovFramework/egovframe-common-components/pull/649

<hr>

### 2025-07-22 화 PMD로 소프트웨어 보안약점 진단하고 제거하기-BackupJob

`if (result == false) {` 를 `if (!result) {` 로 수정

단위 테스트 추가하고 나중에 수정할 예정
- `FileInputStream finput = null;` 를 try-with-resources 로 수정
- `FileOutputStream fosOutput = null;` 를 try-with-resources 로 수정
- `import org.apache.commons.compress.utils.IOUtils;` 를 `import org.apache.commons.io.IOUtils;` 로 수정

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sym/sym/bak/service/BackupJob.java:141:	CloseResource:	CloseResource: 리소스 'FileInputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/sym/sym/bak/service/BackupJob.java:142:	CloseResource:	CloseResource: 리소스 'FileOutputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/sym/sym/bak/service/BackupJob.java:200:	SimplifyBooleanExpressions:	SimplifyBooleanExpressions: boolean 사용 시 불필요한 비교 연산을 피하도록 함
```

2. 브랜치 생성

```
feature/pmd/BackupJob
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.22  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-CloseResource(부적절한 자원 해제)
 *   2025.07.22  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-SimplifyBooleanExpressions(boolean 사용 시 불필요한 비교 연산을 피하도록 함)
```

https://github.com/eGovFramework/egovframe-common-components/pull/650

<hr>

### 2025-07-22 화 PMD로 소프트웨어 보안약점 진단하고 제거하기-NtwrkVO

`getDelYn, setDelYn` 메서드 삭제하고 `private String delYn[];` 에 `@Getter, @Setter` 추가

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sym/sym/nwk/service/NtwrkVO.java:83:	AvoidArrayLoops:	AvoidArrayLoops: 배열의 값을 루프문을 이용하여 복사하는 것 보다 System.arraycopy() 메소드를 이용하여 복사하는 것이 효율적이며 수행 속도가 빠름
```

2. 브랜치 생성

```
feature/pmd/NtwrkVO
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.22  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-AvoidArrayLoops(배열의 값을 루프문을 이용하여 복사하는 것 보다, System.arraycopy() 메소드를 이용하여 복사하는 것이 효율적이며 수행 속도가 빠름)
```

https://github.com/eGovFramework/egovframe-common-components/pull/651

<hr>

### 2025-07-23 수 PMD로 소프트웨어 보안약점 진단하고 제거하기-NtwrkDAO

`return ((Integer)selectOne("ntwrkDAO.selectNtwrkListTotCnt", ntwrkVO)).intValue();` 를 `return selectOne("ntwrkDAO.selectNtwrkListTotCnt", ntwrkVO);` 로 수정

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sym/sym/nwk/service/impl/NtwrkDAO.java:41:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 explicit unboxing
```

2. 브랜치 생성

```
feature/pmd/NtwrkDAO
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.23  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-UnnecessaryBoxing(불필요한 WrapperObject 생성)
```

https://github.com/eGovFramework/egovframe-common-components/pull/652

<hr>

### 2025-07-23 수 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovNtwrkController

`EgovCmmUseService EgovCmmUseService;` 를 `private EgovCmmUseService egovCmmUseService;` 로 수정

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sym/sym/nwk/web/EgovNtwrkController.java:71:	FieldNamingConventions:	FieldNamingConventions: 'field' 의 변수 'EgovCmmUseService' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovNtwrkController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.23  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-FieldNamingConventions(변수명에 밑줄 사용)
```

https://github.com/eGovFramework/egovframe-common-components/pull/653

<hr>

### 2025-07-24 목 PMD로 소프트웨어 보안약점 진단하고 제거하기-ServerEqpmnRelateVO

`getDelYn, setDelYn` 메서드를 제거하고 `private, @Getter, @Setter` 추가

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sym/sym/srv/service/ServerEqpmnRelateVO.java:65:	MethodReturnsInternalArray:	MethodReturnsInternalArray: 'delYn'을 반환하면 내부 배열이 노출될 수 있음
```

2. 브랜치 생성

```
feature/pmd/ServerEqpmnRelateVO
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.24  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-MethodReturnsInternalArray(Private 배열에 Public 데이터 할당)
```

https://github.com/eGovFramework/egovframe-common-components/pull/654

<hr>

### 2025-07-24 목 PMD로 소프트웨어 보안약점 진단하고 제거하기-ServerEqpmnVO

`getDelYn, setDelYn` 메서드를 제거하고 `private, @Getter, @Setter` 추가

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sym/sym/srv/service/ServerEqpmnVO.java:58:	MethodReturnsInternalArray:	MethodReturnsInternalArray: 'delYn'을 반환하면 내부 배열이 노출될 수 있음
```

2. 브랜치 생성

```
feature/pmd/ServerEqpmnVO
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.24  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-MethodReturnsInternalArray(Private 배열에 Public 데이터 할당)
```

https://github.com/eGovFramework/egovframe-common-components/pull/655

<hr>

### 2025-07-25 금 PMD로 소프트웨어 보안약점 진단하고 제거하기-ServerVO

`getDelYn, setDelYn` 메서드를 제거하고 `private, @Getter, @Setter` 추가

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sym/sym/srv/service/ServerVO.java:60:	MethodReturnsInternalArray:	MethodReturnsInternalArray: 'delYn'을 반환하면 내부 배열이 노출될 수 있음
```

2. 브랜치 생성

```
feature/pmd/ServerVO
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.25  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-MethodReturnsInternalArray(Private 배열에 Public 데이터 할당)
```

https://github.com/eGovFramework/egovframe-common-components/pull/656

<hr>

### 2025-07-25 금 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovServerController

`EgovCmmUseService EgovCmmUseService;` 를 `private EgovCmmUseService egovCmmUseService;` 로 수정

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sym/sym/srv/web/EgovServerController.java:75:	FieldNamingConventions:	FieldNamingConventions: 'field' 의 변수 'EgovCmmUseService' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovServerController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.25  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-FieldNamingConventions(변수명에 밑줄 사용)
```

https://github.com/eGovFramework/egovframe-common-components/pull/657

<hr>

### 2025-07-26 토 PMD로 소프트웨어 보안약점 진단하고 제거하기-TroblProcessVO

`getDelYn, setDelYn` 메서드를 제거하고 `@Getter, @Setter` 추가

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sym/tbm/tbp/service/TroblProcessVO.java:96:	AvoidArrayLoops:	AvoidArrayLoops: 배열의 값을 루프문을 이용하여 복사하는 것 보다 System.arraycopy() 메소드를 이용하여 복사하는 것이 효율적이며 수행 속도가 빠름
```

2. 브랜치 생성

```
feature/pmd/TroblProcessVO
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.26  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-AvoidArrayLoops(배열의 값을 루프문을 이용하여 복사하는 것 보다, System.arraycopy() 메소드를 이용하여 복사하는 것이 효율적이며 수행 속도가 빠름)
```

https://github.com/eGovFramework/egovframe-common-components/pull/658

<hr>

### 2025-07-26 토 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovTroblProcessController

`EgovCmmUseService EgovCmmUseService;` 를 `private EgovCmmUseService egovCmmUseService;` 로 수정

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sym/tbm/tbp/web/EgovTroblProcessController.java:65:	FieldNamingConventions:	FieldNamingConventions: 'field' 의 변수 'EgovCmmUseService' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovTroblProcessController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.26  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-FieldNamingConventions(변수명에 밑줄 사용)
```

https://github.com/eGovFramework/egovframe-common-components/pull/659

<hr>

### 2025-07-28 월 PMD로 소프트웨어 보안약점 진단하고 제거하기-TroblReqstVO

`getDelYn, setDelYn` 메서드를 제거하고 `@Getter, @Setter` 추가

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sym/tbm/tbr/service/TroblReqstVO.java:106:	AvoidArrayLoops:	AvoidArrayLoops: 배열의 값을 루프문을 이용하여 복사하는 것 보다 System.arraycopy() 메소드를 이용하여 복사하는 것이 효율적이며 수행 속도가 빠름
```

2. 브랜치 생성

```
feature/pmd/TroblReqstVO
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.28  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-AvoidArrayLoops(배열의 값을 루프문을 이용하여 복사하는 것 보다, System.arraycopy() 메소드를 이용하여 복사하는 것이 효율적이며 수행 속도가 빠름)
```

https://github.com/eGovFramework/egovframe-common-components/pull/661

<hr>

### 2025-07-28 월 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovTroblReqstController

`EgovCmmUseService EgovCmmUseService;` 를 `private EgovCmmUseService egovCmmUseService;` 로 수정

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/sym/tbm/tbr/web/EgovTroblReqstController.java:71:	FieldNamingConventions:	FieldNamingConventions: 'field' 의 변수 'EgovCmmUseService' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovTroblReqstController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.28  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-FieldNamingConventions(변수명에 밑줄 사용)
```

https://github.com/eGovFramework/egovframe-common-components/pull/662

<hr>

### 2025-07-29 화 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovSSOLoginFilter

`public void destroy() {}` 메서드 제거

`(isLocallyAuthenticated.equals("true"))` 를 `isLocallyAuthenticated.equals("true")` 로 수정

Egov SSO 로그인 필터

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uat/sso/filter/EgovSSOLoginFilter.java:49:	UncommentedEmptyMethodBody:	UncommentedEmptyMethodBody: 빈 Method Body에 주석을 추가 할 것
src/main/java/egovframework/com/uat/sso/filter/EgovSSOLoginFilter.java:78:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
```

2. 브랜치 생성

```
feature/pmd/EgovSSOLoginFilter
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.29  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-UncommentedEmptyMethodBody(빈 메소드에 빈메소드임을 나타내는 주석을 추가할 것)
 *   2025.07.29  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-UselessParentheses(불필요한 괄호사용)
```

https://github.com/eGovFramework/egovframe-common-components/pull/663

<hr>

### 2025-07-29 화 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovSSOLogoutFilter

`public void destroy() {}` 제거

Egov SSO 로그아웃 필터

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uat/sso/filter/EgovSSOLogoutFilter.java:38:	UncommentedEmptyMethodBody:	UncommentedEmptyMethodBody: 빈 Method Body에 주석을 추가 할 것
```

2. 브랜치 생성

```
feature/pmd/EgovSSOLogoutFilter
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.29  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-UncommentedEmptyMethodBody(빈 메소드에 빈메소드임을 나타내는 주석을 추가할 것)
```

https://github.com/eGovFramework/egovframe-common-components/pull/664

<hr>

### 2025-07-30 수 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovLoginPolicyFilter

`public void destroy() {}` 메서드 제거

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uat/uap/filter/EgovLoginPolicyFilter.java:48:	UncommentedEmptyMethodBody:	UncommentedEmptyMethodBody: 빈 Method Body에 주석을 추가 할 것
```

2. 브랜치 생성

```
feature/pmd/EgovLoginPolicyFilter
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.30  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-UncommentedEmptyMethodBody(빈 메소드에 빈메소드임을 나타내는 주석을 추가할 것)
```

https://github.com/eGovFramework/egovframe-common-components/pull/666

<hr>

### 2025-07-30 수 PMD로 소프트웨어 보안약점 진단하고 제거하기-LoginPolicyVO

`getDelYn, setDelYn` 메서드를 제거하고 `private, @Getter, @Setter` 추가

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uat/uap/service/LoginPolicyVO.java:54:	MethodReturnsInternalArray:	MethodReturnsInternalArray: 'delYn'을 반환하면 내부 배열이 노출될 수 있음
src/main/java/egovframework/com/uat/uap/service/LoginPolicyVO.java:60:	ArrayIsStoredDirectly:	ArrayIsStoredDirectly: 배열 'delYn' 이 직접 저장되어 있음
```

2. 브랜치 생성

```
feature/pmd/LoginPolicyVO
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.30  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-MethodReturnsInternalArray(Private 배열에 Public 데이터 할당)
 *   2025.07.30  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-ArrayIsStoredDirectly(Public 메소드부터 반환된 Private 배열)
```

https://github.com/eGovFramework/egovframe-common-components/pull/667

<hr>

### 2025-07-31 목 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovLoginServiceImpl

`if ("Y".equals((mapLockUserInfo.get("lockAt")))) {` 을 `if ("Y".equals(mapLockUserInfo.get("lockAt"))) {` 로 수정

`} else if (!"Y".equals((mapLockUserInfo.get("lockAt")))) {` 을 `} else if (!"Y".equals(mapLockUserInfo.get("lockAt"))) {` 로 수정

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uat/uia/service/impl/EgovLoginServiceImpl.java:225:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/uat/uia/service/impl/EgovLoginServiceImpl.java:234:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
```

2. 브랜치 생성

```
feature/pmd/EgovLoginServiceImpl
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.31  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-UselessParentheses(불필요한 괄호사용)
```

https://github.com/eGovFramework/egovframe-common-components/pull/668

<hr>

### 2025-07-31 목 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovLoginController

`auth_error` 를 `authError` 로 이름 바꾸기

`main_page` 를 `mainPage` 로 이름 바꾸기

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uat/uia/web/EgovLoginController.java:106:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'auth_error' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uat/uia/web/EgovLoginController.java:307:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'main_page' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovLoginController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.07.31  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(final이 아닌 변수는 밑줄을 포함할 수 없음)
```

https://github.com/eGovFramework/egovframe-common-components/pull/669

<hr>

### 2025-08-01 금 PMD로 소프트웨어 보안약점 진단하고 제거하기-CmtManageVO

`wrkt_dt` 를 `wrktDt` 로 이름 바꾸기


<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uss/cmt/service/CmtManageVO.java:286:	FormalParameterNamingConventions:	FormalParameterNamingConventions: 'method parameter' 의 변수 'wrkt_dt' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/CmtManageVO
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.08.01  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-FormalParameterNamingConventions(변수명에 밑줄 사용)
```

https://github.com/eGovFramework/egovframe-common-components/pull/670

<hr>

### 2025-08-01 금 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovCmtManageServiceImpl

// NOPMD - SimpleDateFormatNeedsLocale
```
This is equivalent to calling SimpleDateFormat(pattern, Locale.getDefault(Locale.Category.FORMAT)).
이는 SimpleDateFormat(pattern, Locale.getDefault(Locale.Category.FORMAT))를 호출하는 것과 같습니다.
```

`cmtManageVO = cmtManageDAO.selectWrkStartInfo(cmtManageVO);` 를 `CmtManageVO resultVO = cmtManageDAO.selectWrkStartInfo(cmtManageVO);` 로 수정

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uss/cmt/service/impl/EgovCmtManageServiceImpl.java:75:	SimpleDateFormatNeedsLocale:	SimpleDateFormatNeedsLocale: SimpleDateFormat 인스턴스를 생성할때 Locale 을 지정하는 것이 바람직함
src/main/java/egovframework/com/uss/cmt/service/impl/EgovCmtManageServiceImpl.java:102:	AvoidReassigningParameters:	AvoidReassigningParameters: 'cmtManageVO' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/uss/cmt/service/impl/EgovCmtManageServiceImpl.java:104:	SimpleDateFormatNeedsLocale:	SimpleDateFormatNeedsLocale: SimpleDateFormat 인스턴스를 생성할때 Locale 을 지정하는 것이 바람직함
```

2. 브랜치 생성

```
feature/pmd/EgovCmtManageServiceImpl
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.08.01  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-SimpleDateFormatNeedsLocale(SimpleDateFormat 인스턴스를 생성할때 Locale 을 지정하는 것이 바람직함)
 *   2025.08.01  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-AvoidReassigningParameters(넘겨받는 메소드 parameter 값을 직접 변경하는 코드 탐지)
```

https://github.com/eGovFramework/egovframe-common-components/pull/671

<hr>

### 2025-08-02 토 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovAnnvrsryManageServiceImpl

`result_temp` 를 `resultList` 로 이름 바꾸기

`to_day` 를 `today` 로 이름 바꾸기

`target_day` 를 `targetDate` 로 이름 바꾸기

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uss/ion/ans/service/impl/EgovAnnvrsryManageServiceImpl.java:137:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'result_temp' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/ans/service/impl/EgovAnnvrsryManageServiceImpl.java:173:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'to_day' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/ans/service/impl/EgovAnnvrsryManageServiceImpl.java:174:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'target_day' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovAnnvrsryManageServiceImpl
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.08.02  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(final이 아닌 변수는 밑줄을 포함할 수 없음)
```

https://github.com/eGovFramework/egovframe-common-components/pull/673

<hr>

### 2025-08-02 토 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovAnnvrsryManageController

`annvrsryManageVO_Temp` 를 `resultVO` 로 이름 바꾸기

`AnnvrsryManageVO annvrsryManageVO_Temp = new AnnvrsryManageVO();` 제거하고 `AnnvrsryManageVO resultVO = egovAnnvrsryManageService.selectAnnvrsryManage(annvrsryManageVO);` 로 수정

`to_day` 를 `today` 로 이름 바꾸기

`target_day` 를 `targetDate` 로 이름 바꾸기

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uss/ion/ans/web/EgovAnnvrsryManageController.java:154:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'annvrsryManageVO_Temp' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/ans/web/EgovAnnvrsryManageController.java:381:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'annvrsryManageVO_Temp' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/ans/web/EgovAnnvrsryManageController.java:412:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'to_day' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/ans/web/EgovAnnvrsryManageController.java:413:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'target_day' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovAnnvrsryManageController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.08.02  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(final이 아닌 변수는 밑줄을 포함할 수 없음)
```

https://github.com/eGovFramework/egovframe-common-components/pull/674

<hr>

### 2025-08-04 월 PMD로 소프트웨어 보안약점 진단하고 제거하기-BannerVO

`getDelYn, setDelYn` 메서드를 제거하고 `private, @Getter, @Setter` 추가

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uss/ion/bnr/service/BannerVO.java:53:	MethodReturnsInternalArray:	MethodReturnsInternalArray: 'delYn'을 반환하면 내부 배열이 노출될 수 있음
src/main/java/egovframework/com/uss/ion/bnr/service/BannerVO.java:59:	ArrayIsStoredDirectly:	ArrayIsStoredDirectly: 배열 'delYn' 이 직접 저장되어 있음
```

2. 브랜치 생성

```
feature/pmd/BannerVO
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.08.04  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-MethodReturnsInternalArray(Private 배열에 Public 데이터 할당)
 *   2025.08.04  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-ArrayIsStoredDirectly(Public 메소드부터 반환된 Private 배열)
```

https://github.com/eGovFramework/egovframe-common-components/pull/675

<hr>

### 2025-08-04 월 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovBndtManageServiceImpl

`try-with-resources` 로 수정
- XSSFWorkbook 클래스를 직접 사용하는 것보다 Workbook 인터페이스를 사용하는 것이 유연성과 확장성 면에서 훨씬 좋아 수정
- XSSFWorkbook -> Workbook
- XSSFSheet -> Sheet
- XSSFRow -> Row
- XSSFCell -> Cell
- `LOGGER.debug("=====>>>>> ERR : IOException " + e.getMessage());` 를 `throw new UncheckedIOException(e);` 로 수정
- `hssfWB` 을 `workbook` 으로 이름 바꾸기

`target_day` 를 `targetDate` 로 이름 바꾸기

`private static final Logger LOGGER = LoggerFactory.getLogger(EgovBndtManageServiceImpl.class);` 제거

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uss/ion/bnt/service/impl/EgovBndtManageServiceImpl.java:384:	CloseResource:	CloseResource: 리소스 'XSSFWorkbook' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/uss/ion/bnt/service/impl/EgovBndtManageServiceImpl.java:484:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'target_day' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/bnt/service/impl/EgovBndtManageServiceImpl.java:506:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'target_day' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovBndtManageServiceImpl
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.08.04  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-CloseResource(부적절한 자원 해제)
 *   2025.08.04  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(final이 아닌 변수는 밑줄을 포함할 수 없음)
```

https://github.com/eGovFramework/egovframe-common-components/pull/676

<hr>

### 2025-08-05 화 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovBndtManageController

`bndtManageVO_Temp` 를 `resultVO` 로 이름 바꾸기

`bndtCeckManageVO_Temp` 를 `resultBndtCeckManageVO` 로 이름 바꾸기

`bndtCeckManage_Temp` 를 `resultBndtCeckManage` 로 이름 바꾸기

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uss/ion/bnt/web/EgovBndtManageController.java:169:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'bndtManageVO_Temp' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/bnt/web/EgovBndtManageController.java:348:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'bndtCeckManageVO_Temp' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/bnt/web/EgovBndtManageController.java:355:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'bndtCeckManage_Temp' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovBndtManageController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.08.05  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(final이 아닌 변수는 밑줄을 포함할 수 없음)
```

<hr>

### 2025-08-05 화 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovEventCmpgnController

`_result` 를 `eventTyCode` 로 이름 바꾸기

`_result` 를 `sexdstnCode` 로 이름 바꾸기

`_result` 를 `occpTyCode` 로 이름 바꾸기

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uss/ion/ecc/web/EgovEventCmpgnController.java:176:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/ecc/web/EgovEventCmpgnController.java:233:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/ecc/web/EgovEventCmpgnController.java:359:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/ecc/web/EgovEventCmpgnController.java:420:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovEventCmpgnController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.08.05  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(final이 아닌 변수는 밑줄을 포함할 수 없음)
```

<hr>

### 2025-08-06 수 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovEventManageController

`eventManageVO_check` 를 `resultVO` 로 이름 바꾸기

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uss/ion/evt/web/EgovEventManageController.java:387:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'eventManageVO_check' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovEventManageController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.08.06  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(final이 아닌 변수는 밑줄을 포함할 수 없음)
```

https://github.com/eGovFramework/egovframe-common-components/pull/679

<hr>

### 2025-08-06 수 PMD로 소프트웨어 보안약점 진단하고 제거하기-IntnetSvcGuidanceVO

`getDelYn, setDelYn` 메서드를 제거하고 `private, @Getter, @Setter` 추가

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uss/ion/isg/service/IntnetSvcGuidanceVO.java:48:	MethodReturnsInternalArray:	MethodReturnsInternalArray: 'delYn'을 반환하면 내부 배열이 노출될 수 있음
src/main/java/egovframework/com/uss/ion/isg/service/IntnetSvcGuidanceVO.java:54:	ArrayIsStoredDirectly:	ArrayIsStoredDirectly: 배열 'delYn' 이 직접 저장되어 있음
```

2. 브랜치 생성

```
feature/pmd/IntnetSvcGuidanceVO
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.08.06  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-MethodReturnsInternalArray(Private 배열에 Public 데이터 할당)
 *   2025.08.06  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-ArrayIsStoredDirectly(Public 메소드부터 반환된 Private 배열)
```

https://github.com/eGovFramework/egovframe-common-components/pull/680

<hr>

### 2025-08-07 목 PMD로 소프트웨어 보안약점 진단하고 제거하기-LoginScrinImageVO

`getDelYn, setDelYn` 메서드를 제거하고 `private, @Getter, @Setter` 추가

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uss/ion/lsi/service/LoginScrinImageVO.java:47:	MethodReturnsInternalArray:	MethodReturnsInternalArray: 'delYn'을 반환하면 내부 배열이 노출될 수 있음
src/main/java/egovframework/com/uss/ion/lsi/service/LoginScrinImageVO.java:53:	ArrayIsStoredDirectly:	ArrayIsStoredDirectly: 배열 'delYn' 이 직접 저장되어 있음
```

2. 브랜치 생성

```
feature/pmd/LoginScrinImageVO
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.08.07  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-MethodReturnsInternalArray(Private 배열에 Public 데이터 할당)
 *   2025.08.07  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-ArrayIsStoredDirectly(Public 메소드부터 반환된 Private 배열)
```

https://github.com/eGovFramework/egovframe-common-components/pull/681

<hr>

### 2025-08-07 목 PMD로 소프트웨어 보안약점 진단하고 제거하기-MainImageVO

`getDelYn, setDelYn` 메서드를 제거하고 `private, @Getter, @Setter` 추가

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uss/ion/msi/service/MainImageVO.java:47:	MethodReturnsInternalArray:	MethodReturnsInternalArray: 'delYn'을 반환하면 내부 배열이 노출될 수 있음
src/main/java/egovframework/com/uss/ion/msi/service/MainImageVO.java:53:	ArrayIsStoredDirectly:	ArrayIsStoredDirectly: 배열 'delYn' 이 직접 저장되어 있음
```

2. 브랜치 생성

```
feature/pmd/MainImageVO
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.08.07  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-MethodReturnsInternalArray(Private 배열에 Public 데이터 할당)
 *   2025.08.07  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-ArrayIsStoredDirectly(Public 메소드부터 반환된 Private 배열)
```

https://github.com/eGovFramework/egovframe-common-components/pull/682

<hr>

### 2025-08-08 금 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovMtgPlaceManageController

`_result` 를 `fvoList` 로 이름 바꾸기

`_atchFileId` 를 `atchFileId` 로 이름 바꾸기

`_cnt` 를 `fileKeyParam` 으로 이름 바꾸기

`mtgPlaceManage_Temp` 를 `resultVO` 로 이름 바꾸기

`mtgPlaceManageVO_Temp` 를 `resultVO` 로 이름 바꾸기

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uss/ion/mtg/web/EgovMtgPlaceManageController.java:195:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/mtg/web/EgovMtgPlaceManageController.java:196:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/mtg/web/EgovMtgPlaceManageController.java:240:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/mtg/web/EgovMtgPlaceManageController.java:248:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/mtg/web/EgovMtgPlaceManageController.java:257:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_cnt' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/mtg/web/EgovMtgPlaceManageController.java:258:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/mtg/web/EgovMtgPlaceManageController.java:284:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/mtg/web/EgovMtgPlaceManageController.java:312:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'mtgPlaceManage_Temp' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/mtg/web/EgovMtgPlaceManageController.java:391:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'mtgPlaceManageVO_Temp' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/mtg/web/EgovMtgPlaceManageController.java:421:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'mtgPlaceManageVO_Temp' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovMtgPlaceManageController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.08.08  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(final이 아닌 변수는 밑줄을 포함할 수 없음)
```

https://github.com/eGovFramework/egovframe-common-components/pull/684

<hr>

### 2025-08-08 금 PMD로 소프트웨어 보안약점 진단하고 제거하기-NoteManageVO

`getAtchFile, setAtchFile` 메서드를 제거하고 `@Getter, @Setter` 추가

`@SuppressWarnings("serial"), implements Serializable` 제거하고 `private static final long serialVersionUID = 1L;` 추가. Adds a default serial version ID to the selected type.

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uss/ion/ntm/service/NoteManageVO.java:235:	AvoidArrayLoops:	AvoidArrayLoops: 배열의 값을 루프문을 이용하여 복사하는 것 보다 System.arraycopy() 메소드를 이용하여 복사하는 것이 효율적이며 수행 속도가 빠름
```

2. 브랜치 생성

```
feature/pmd/NoteManageVO
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.08.08  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-AvoidArrayLoops(배열의 값을 루프문을 이용하여 복사하는 것 보다, System.arraycopy() 메소드를 이용하여 복사하는 것이 효율적이며 수행 속도가 빠름)
```

https://github.com/eGovFramework/egovframe-common-components/pull/685

<hr>

### 2025-08-09 토 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovNoteManageController

`_result` 를 `fvoList` 로 이름 바꾸기

`_atchFileId` 를 `atchFileId` 로 이름 바꾸기

`ReusltScript` 를 `reusltScript` 로 이름 바꾸기

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uss/ion/ntm/web/EgovNoteManageController.java:174:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/ntm/web/EgovNoteManageController.java:175:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/ntm/web/EgovNoteManageController.java:191:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'ReusltScript' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovNoteManageController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.08.04  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(final이 아닌 변수는 밑줄을 포함할 수 없음)
```

https://github.com/eGovFramework/egovframe-common-components/pull/687

<hr>

### 2025-08-09 토 PMD로 소프트웨어 보안약점 진단하고 제거하기-NoteRecptn

`getAtchFileId, setAtchFileId` 메서드를 제거하고 `@Getter, @Setter` 추가

`@SuppressWarnings("serial"), implements Serializable` 제거하고 `private static final long serialVersionUID = 1L;` 추가. Adds a default serial version ID to the selected type.

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uss/ion/ntr/service/NoteRecptn.java:218:	AvoidArrayLoops:	AvoidArrayLoops: 배열의 값을 루프문을 이용하여 복사하는 것 보다 System.arraycopy() 메소드를 이용하여 복사하는 것이 효율적이며 수행 속도가 빠름
```

2. 브랜치 생성

```
feature/pmd/NoteRecptn
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.08.09  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-AvoidArrayLoops(배열의 값을 루프문을 이용하여 복사하는 것 보다, System.arraycopy() 메소드를 이용하여 복사하는 것이 효율적이며 수행 속도가 빠름)
```

https://github.com/eGovFramework/egovframe-common-components/pull/688

<hr>

### 2025-08-11 월 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovNewsController

`NewsList` 를 `resultList` 로 이름 바꾸기

`_result` 를 `fvoList` 로 이름 바꾸기

`_atchFileId` 를 `atchFileId` 로 이름 바꾸기

`_cnt` 를 `fileKeyParam` 로 이름 바꾸기

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uss/ion/nws/web/EgovNewsController.java:82:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'NewsList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/nws/web/EgovNewsController.java:143:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/nws/web/EgovNewsController.java:144:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/nws/web/EgovNewsController.java:225:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/nws/web/EgovNewsController.java:232:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/nws/web/EgovNewsController.java:239:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_cnt' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/nws/web/EgovNewsController.java:240:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovNewsController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.08.11  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(final이 아닌 변수는 밑줄을 포함할 수 없음)
```

https://github.com/eGovFramework/egovframe-common-components/pull/689

<hr>

### 2025-08-11 월 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovPopupManageController

`PrintWriter` 에 `// NOPMD - CloseResource 규칙 무시` 특정 규칙 무시 주석 추가

`String fileUrl2` 로 이름 바꾸기

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uss/ion/pwm/web/EgovPopupManageController.java:285:	CloseResource:	CloseResource: 리소스 'PrintWriter' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/uss/ion/pwm/web/EgovPopupManageController.java:318:	AvoidReassigningParameters:	AvoidReassigningParameters: 'fileUrl' 처럼 파라미터 값을 직접 변경하지 말 것
```

2. 브랜치 생성

```
feature/pmd/EgovPopupManageController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.08.11  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-CloseResource(부적절한 자원 해제)
 *   2025.08.11  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-AvoidReassigningParameters(넘겨받는 메소드 parameter 값을 직접 변경하는 코드 탐지)
```

https://github.com/eGovFramework/egovframe-common-components/pull/690

<hr>

### 2025-08-12 화 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovRecomendSiteController

`RecomendSiteList` 를 `resultList` 로 이름 바꾸기

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uss/ion/rec/web/EgovRecomendSiteController.java:89:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'RecomendSiteList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovRecomendSiteController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.08.12  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(final이 아닌 변수는 밑줄을 포함할 수 없음)
```

https://github.com/eGovFramework/egovframe-common-components/pull/691

<hr>

### 2025-08-12 화 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovRoughMapController

`roughMap` 을 `RoughMapVO result` 로 이름 바꾸기

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uss/ion/rmm/web/EgovRoughMapController.java:198:	AvoidReassigningParameters:	AvoidReassigningParameters: 'roughMap' 처럼 파라미터 값을 직접 변경하지 말 것
```

2. 브랜치 생성

```
feature/pmd/EgovRoughMapController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.08.12  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-AvoidReassigningParameters(넘겨받는 메소드 parameter 값을 직접 변경하는 코드 탐지)
```

https://github.com/eGovFramework/egovframe-common-components/pull/692

<hr>

### 2025-08-13 수 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovRecentSrchwrdController

아이디 설정을 수정
```java
		// 로그인 객체 선언
		LoginVO loginVO = (LoginVO) EgovUserDetailsHelper.getAuthenticatedUser();
		// 아이디 설정
//		String uniqId = (loginVO == null ? "" : EgovStringUtil.isNullToString(loginVO.getUniqId()));
//		recentSrchwrd.setFrstRegisterId(uniqId);
//		recentSrchwrd.setLastUpdusrId(uniqId);
		if (loginVO != null) {
			recentSrchwrd.setFrstRegisterId(loginVO.getUniqId());
			recentSrchwrd.setLastUpdusrId(loginVO.getUniqId());
		}
```

`PrintWriter` 에 `// NOPMD - CloseResource 규칙 무시` 특정 규칙 무시 주석 추가

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uss/ion/rsm/web/EgovRecentSrchwrdController.java:203:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/uss/ion/rsm/web/EgovRecentSrchwrdController.java:265:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/uss/ion/rsm/web/EgovRecentSrchwrdController.java:392:	CloseResource:	CloseResource: 리소스 'PrintWriter' 가 사용 후에 닫혔는지 확인필요
```

2. 브랜치 생성

```
feature/pmd/EgovRecentSrchwrdController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.08.13  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-UselessParentheses(불필요한 괄호사용)
 *   2025.08.13  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-CloseResource(부적절한 자원 해제)
```

https://github.com/eGovFramework/egovframe-common-components/pull/693

<hr>

### 2025-08-13 수 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovRssServiceImpl

`sBDT_TITLE` 을 `sBdtTitle` 로 이름 바꾸기

`sBDT_LINK` 를 `sBdtLink` 로 이름 바꾸기

`sBDT_DESCRIPTION` 을 `sBdtDescription` 로 이름 바꾸기

`sBDT_TAG` 를 `sBdtTag` 로 이름 바꾸기

`sBDT_ETC` 를 `sBdtEtc` 로 이름 바꾸기

---

`sM_BDT_TITLE` 를 `smBdtTitle` 로 이름 바꾸기

`sM_BDT_LINK` 를 `smBdtLink` 로 이름 바꾸기

`sM_BDT_DESCRIPTION` 를 `smBdtDescription` 로 이름 바꾸기

`sM_BDT_TAG` 를 `smBdtTag` 로 이름 바꾸기

`sM_BDT_ETC` 를 `smBdtEtc` 로 이름 바꾸기

---

`Keys` 를 `keys` 로 이름 바꾸기

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uss/ion/rsn/service/impl/EgovRssServiceImpl.java:48:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sBDT_TITLE' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/rsn/service/impl/EgovRssServiceImpl.java:49:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sBDT_LINK' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/rsn/service/impl/EgovRssServiceImpl.java:50:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sBDT_DESCRIPTION' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/rsn/service/impl/EgovRssServiceImpl.java:51:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sBDT_TAG' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/rsn/service/impl/EgovRssServiceImpl.java:52:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sBDT_ETC' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/rsn/service/impl/EgovRssServiceImpl.java:60:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sM_BDT_TITLE' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/rsn/service/impl/EgovRssServiceImpl.java:61:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sM_BDT_LINK' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/rsn/service/impl/EgovRssServiceImpl.java:62:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sM_BDT_DESCRIPTION' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/rsn/service/impl/EgovRssServiceImpl.java:63:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sM_BDT_TAG' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/rsn/service/impl/EgovRssServiceImpl.java:64:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sM_BDT_ETC' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/rsn/service/impl/EgovRssServiceImpl.java:66:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'Keys' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovRssServiceImpl
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.08.13  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(final이 아닌 변수는 밑줄을 포함할 수 없음)
```

https://github.com/eGovFramework/egovframe-common-components/pull/694

<hr>

### 2025-08-14 목 PMD로 소프트웨어 보안약점 진단하고 제거하기-RssTagManageDao

`TABLE_NAME` 을 `columnLabelTableName` 로 이름 바꾸기

`TABLE_SCHEMA` 를 `columnLabelTableSchema` 로 이름 바꾸기

`TABLE_AND_VIEW_TYPES` 을 `types` 로 이름 바꾸기

`Connection conn = null;`, `ResultSet tables = null;` 을 try-with-resources 로 수정

`Connection conn = null;`, `PreparedStatement st = null;`, `ResultSet rs = null;` 을 try-with-resources 로 수정

`if ( tableWhiteList.contains(tableName.toLowerCase()) == true ) {` 를 `if (tableWhiteList.contains(tableName.toLowerCase())) {` 로 수정
- `== true` 제거

`if ( tableWhiteList.contains(sTableName.toLowerCase()) == true ) {` 를 `if (tableWhiteList.contains(sTableName.toLowerCase())) {` 로 수정
- `== true` 제거

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uss/ion/rss/service/impl/RssTagManageDao.java:54:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'TABLE_NAME' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/rss/service/impl/RssTagManageDao.java:55:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'TABLE_SCHEMA' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/rss/service/impl/RssTagManageDao.java:56:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'TABLE_AND_VIEW_TYPES' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/rss/service/impl/RssTagManageDao.java:59:	CloseResource:	CloseResource: 리소스 'Connection' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/uss/ion/rss/service/impl/RssTagManageDao.java:61:	CloseResource:	CloseResource: 리소스 'ResultSet' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/uss/ion/rss/service/impl/RssTagManageDao.java:75:	SimplifyBooleanExpressions:	SimplifyBooleanExpressions: boolean 사용 시 불필요한 비교 연산을 피하도록 함
src/main/java/egovframework/com/uss/ion/rss/service/impl/RssTagManageDao.java:105:	CloseResource:	CloseResource: 리소스 'Connection' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/uss/ion/rss/service/impl/RssTagManageDao.java:106:	CloseResource:	CloseResource: 리소스 'PreparedStatement' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/uss/ion/rss/service/impl/RssTagManageDao.java:107:	CloseResource:	CloseResource: 리소스 'ResultSet' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/uss/ion/rss/service/impl/RssTagManageDao.java:114:	SimplifyBooleanExpressions:	SimplifyBooleanExpressions: boolean 사용 시 불필요한 비교 연산을 피하도록 함
```

2. 브랜치 생성

```
feature/pmd/RssTagManageDao
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.08.14  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(final이 아닌 변수는 밑줄을 포함할 수 없음)
 *   2025.08.14  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-CloseResource(부적절한 자원 해제)
 *   2025.08.14  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-SimplifyBooleanExpressions(boolean 사용 시 불필요한 비교 연산을 피하도록 함)
```

https://github.com/eGovFramework/egovframe-common-components/pull/695

<hr>

### 2025-08-15 금 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovRwardManageController

`rwardManage_1` 을 `rwardManage1` 로 이름 바꾸기

`_result` 를 `fvoList` 로 이름 바꾸기

`_atchFileId` 을 `atchFileId` 로 이름 바꾸기

`_cnt` 를 `fileKeyParam` 로 이름 바꾸기

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uss/ion/rwd/web/EgovRwardManageController.java:157:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'rwardManage_1' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/rwd/web/EgovRwardManageController.java:217:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/rwd/web/EgovRwardManageController.java:218:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/rwd/web/EgovRwardManageController.java:262:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/rwd/web/EgovRwardManageController.java:272:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/rwd/web/EgovRwardManageController.java:282:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_cnt' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/rwd/web/EgovRwardManageController.java:283:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/rwd/web/EgovRwardManageController.java:307:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovRwardManageController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.08.15  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(final이 아닌 변수는 밑줄을 포함할 수 없음)
```

https://github.com/eGovFramework/egovframe-common-components/pull/696

<hr>

### 2025-08-15 금 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovSiteController

`SiteList` 을 `resultList` 로 이름 바꾸기

`_result` 를 `siteThemaClCode` 로 이름 바꾸기

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uss/ion/sit/web/EgovSiteController.java:93:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'SiteList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/sit/web/EgovSiteController.java:135:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/sit/web/EgovSiteController.java:195:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovSiteController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.08.15  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(final이 아닌 변수는 밑줄을 포함할 수 없음)
```

https://github.com/eGovFramework/egovframe-common-components/pull/697

<hr>

### 2025-08-15 금 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovTwitterTrnsmitServiceImpl

`sCONSUMER_KEY` 를 `consumerKey` 로 이름 바꾸기

`sCONSUMER_SECRET` 을 `consumerSecret` 로 이름 바꾸기

`userCreate_at` 을 `userCreateAt` 로 이름 바꾸기

`userProfile_url` 를 `userProfileUrl` 로 이름 바꾸기

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uss/ion/tir/service/impl/EgovTwitterTrnsmitServiceImpl.java:55:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sCONSUMER_KEY' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/tir/service/impl/EgovTwitterTrnsmitServiceImpl.java:56:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sCONSUMER_SECRET' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/tir/service/impl/EgovTwitterTrnsmitServiceImpl.java:82:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sCONSUMER_KEY' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/tir/service/impl/EgovTwitterTrnsmitServiceImpl.java:83:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sCONSUMER_SECRET' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/tir/service/impl/EgovTwitterTrnsmitServiceImpl.java:100:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'userCreate_at' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/tir/service/impl/EgovTwitterTrnsmitServiceImpl.java:101:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'userProfile_url' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/tir/service/impl/EgovTwitterTrnsmitServiceImpl.java:120:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sCONSUMER_KEY' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/tir/service/impl/EgovTwitterTrnsmitServiceImpl.java:121:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sCONSUMER_SECRET' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovTwitterTrnsmitServiceImpl
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.08.15  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(final이 아닌 변수는 밑줄을 포함할 수 없음)
```

https://github.com/eGovFramework/egovframe-common-components/pull/698

<hr>

### 2025-08-16 토 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovTwitterController

`ReusltScript` 를 `reusltScript` 로 이름 바꾸기

`sCONSUMER_KEY` 를 `consumerKey` 로 이름 바꾸기

`sCONSUMER_SECRET` 을 `consumerSecret` 로 이름 바꾸기

`String tID2 = tID.replace("&quot;", "");` 로 수정

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uss/ion/tir/web/EgovTwitterController.java:168:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'ReusltScript' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/tir/web/EgovTwitterController.java:288:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sCONSUMER_KEY' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/tir/web/EgovTwitterController.java:289:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sCONSUMER_SECRET' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/tir/web/EgovTwitterController.java:325:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sCONSUMER_KEY' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/tir/web/EgovTwitterController.java:326:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sCONSUMER_SECRET' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/tir/web/EgovTwitterController.java:362:	AvoidReassigningParameters:	AvoidReassigningParameters: 'tID' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/uss/ion/tir/web/EgovTwitterController.java:365:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sCONSUMER_KEY' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/ion/tir/web/EgovTwitterController.java:366:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sCONSUMER_SECRET' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovTwitterController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.08.16  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(final이 아닌 변수는 밑줄을 포함할 수 없음)
 *   2025.08.16  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-AvoidReassigningParameters(넘겨받는 메소드 parameter 값을 직접 변경하는 코드 탐지)
```

https://github.com/eGovFramework/egovframe-common-components/pull/699

<hr>

### 2025-08-16 토 PMD로 소프트웨어 보안약점 진단하고 제거하기-UserAbsnceVO

`getDelYn, setDelYn` 메서드를 제거하고 `private, @Getter, @Setter` 추가

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uss/ion/uas/service/UserAbsnceVO.java:50:	MethodReturnsInternalArray:	MethodReturnsInternalArray: 'delYn'을 반환하면 내부 배열이 노출될 수 있음
src/main/java/egovframework/com/uss/ion/uas/service/UserAbsnceVO.java:56:	ArrayIsStoredDirectly:	ArrayIsStoredDirectly: 배열 'delYn' 이 직접 저장되어 있음
```

2. 브랜치 생성

```
feature/pmd/UserAbsnceVO
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.08.16  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-MethodReturnsInternalArray(Private 배열에 Public 데이터 할당)
 *   2025.08.16  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-ArrayIsStoredDirectly(Public 메소드부터 반환된 Private 배열)
```

https://github.com/eGovFramework/egovframe-common-components/pull/700

<hr>

### 2025-08-18 월 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovUnityLinkController

아이디 설정 수정
- `String uniqId = (loginVO == null ? "" : EgovStringUtil.isNullToString(loginVO.getUniqId()));` 제거

```java
		// 로그인 객체 선언
		LoginVO loginVO = (LoginVO) EgovUserDetailsHelper.getAuthenticatedUser();

		// 아이디 설정
		if (loginVO != null) {
			unityLink.setFrstRegisterId(loginVO.getUniqId());
			unityLink.setLastUpdusrId(loginVO.getUniqId());
		}
```

`LOGGER` 제거하고 `@Slf4j` 추가

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uss/ion/ulm/web/EgovUnityLinkController.java:250:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/uss/ion/ulm/web/EgovUnityLinkController.java:319:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
```

2. 브랜치 생성

```
feature/pmd/EgovUnityLinkController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.08.18  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-UselessParentheses(불필요한 괄호사용)
```

https://github.com/eGovFramework/egovframe-common-components/pull/701

<hr>

### 2025-08-18 월 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovVcatnManageServiceImpl

`Count` 를 `count` 로 이름 바꾸기
- `double Count = 0.0;`

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uss/ion/vct/service/impl/EgovVcatnManageServiceImpl.java:472:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'Count' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovVcatnManageServiceImpl
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.08.18  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(final이 아닌 변수는 밑줄을 포함할 수 없음)
```

https://github.com/eGovFramework/egovframe-common-components/pull/702

<hr>

### 2025-08-19 화 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovVcatnManageController

`vcatnManageVO` 를 `resultVO` 로 이름 바꾸기
```java
//vcatnManageVO = egovVcatnManageService.selectIndvdlYrycManage(user.getUniqId());
VcatnManageVO resultVO = egovVcatnManageService.selectIndvdlYrycManage(user.getUniqId());
```

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uss/ion/vct/web/EgovVcatnManageController.java:103:	AvoidReassigningParameters:	AvoidReassigningParameters: 'vcatnManageVO' 처럼 파라미터 값을 직접 변경하지 말 것
```

2. 브랜치 생성

```
feature/pmd/EgovVcatnManageController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.08.19  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-AvoidReassigningParameters(넘겨받는 메소드 parameter 값을 직접 변경하는 코드 탐지)
```

https://github.com/eGovFramework/egovframe-common-components/pull/703

<hr>

### 2025-08-19 화 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovWikiBookmarkServiceImpl

필요없는 ; 문장 제거

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uss/ion/wik/bmk/service/impl/EgovWikiBookmarkServiceImpl.java:99:	UnnecessarySemicolon:	UnnecessarySemicolon: 필요없는 문장 (;)이 있음
```

2. 브랜치 생성

```
feature/pmd/EgovWikiBookmarkServiceImpl
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.08.19  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-UnnecessarySemicolon(필요없는 ; 문장 존재)
```

https://github.com/eGovFramework/egovframe-common-components/pull/704

<hr>

### 2025-08-20 수 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovAdministrationWordController

`_result` 를 `wordSeCode` 로 이름 바꾸기

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uss/olh/awm/web/EgovAdministrationWordController.java:201:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/olh/awm/web/EgovAdministrationWordController.java:248:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovAdministrationWordController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.08.20  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(final이 아닌 변수는 밑줄을 포함할 수 없음)
```

https://github.com/eGovFramework/egovframe-common-components/pull/705

<hr>

### 2025-08-20 수 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovFaqController

`FaqList` 를 `resultList` 로 이름 바꾸기

`_result` 를 `fvoList` 로 이름 바꾸기

`_atchFileId` 를 `atchFileId` 로 이름 바꾸기

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uss/olh/faq/web/EgovFaqController.java:105:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'FaqList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/olh/faq/web/EgovFaqController.java:176:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/olh/faq/web/EgovFaqController.java:177:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/olh/faq/web/EgovFaqController.java:269:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/olh/faq/web/EgovFaqController.java:297:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovFaqController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.08.20  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(final이 아닌 변수는 밑줄을 포함할 수 없음)
```

https://github.com/eGovFramework/egovframe-common-components/pull/706

<hr>

### 2025-08-21 목 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovHpcmController

`HpcmList` 를 `resultList` 로 이름 바꾸기

`_result` 를 `hpcmSeCode` 로 이름 바꾸기

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uss/olh/hpc/web/EgovHpcmController.java:96:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'HpcmList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/olh/hpc/web/EgovHpcmController.java:140:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/olh/hpc/web/EgovHpcmController.java:197:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovHpcmController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.08.21  이백행          2125년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(final이 아닌 변수는 밑줄을 포함할 수 없음)
```

https://github.com/eGovFramework/egovframe-common-components/pull/707

<hr>

### 2025-08-21 목 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovOnlineManualController

`_result` 를 `onlineMnlSeCode` 로 이름 바꾸기

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uss/olh/omm/web/EgovOnlineManualController.java:196:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/olh/omm/web/EgovOnlineManualController.java:253:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovOnlineManualController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.08.21  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(final이 아닌 변수는 밑줄을 포함할 수 없음)
```

https://github.com/eGovFramework/egovframe-common-components/pull/708

<hr>

### 2025-08-22 금 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovQnaController

`QnaList` 를 `resultList` 로 이름 바꾸기

필요없는 ; 문장 제거
- `QnaVO vo = egovQnaService.selectQnaDetail(qnaVO);;`

`QnaAnswerList` 를 `resultList` 로 이름 바꾸기

`_result` 를 `qnaProcessSttusCode` 로 이름 바꾸기

`qnaVO` 를 `resultVO` 로 이름 바꾸기
```java
//qnaVO = egovQnaService.selectQnaDetail(qnaVO);
QnaVO resultVO = egovQnaService.selectQnaDetail(qnaVO);
````

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uss/olh/qna/web/EgovQnaController.java:102:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'QnaList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/olh/qna/web/EgovQnaController.java:274:	UnnecessarySemicolon:	UnnecessarySemicolon: 필요없는 문장 (;)이 있음
src/main/java/egovframework/com/uss/olh/qna/web/EgovQnaController.java:321:	UnnecessarySemicolon:	UnnecessarySemicolon: 필요없는 문장 (;)이 있음
src/main/java/egovframework/com/uss/olh/qna/web/EgovQnaController.java:360:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'QnaAnswerList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/olh/qna/web/EgovQnaController.java:403:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/olh/qna/web/EgovQnaController.java:406:	AvoidReassigningParameters:	AvoidReassigningParameters: 'qnaVO' 처럼 파라미터 값을 직접 변경하지 말 것
```

2. 브랜치 생성

```
feature/pmd/EgovQnaController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.08.22  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(final이 아닌 변수는 밑줄을 포함할 수 없음)
 *   2025.08.22  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-UnnecessarySemicolon(필요없는 ; 문장 존재)
 *   2025.08.22  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-AvoidReassigningParameters(넘겨받는 메소드 parameter 값을 직접 변경하는 코드 탐지)
```

https://github.com/eGovFramework/egovframe-common-components/pull/709

<hr>

### 2025-08-22 금 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovCnsltManageController

`_result` 를 `fvoList` 로 이름 바꾸기

`_atchFileId` 를 `atchFileId` 로 이름 바꾸기

`_cnt` 를 `fileKeyParam` 로 이름 바꾸기

필요없는 ; 문장 제거
- `LOGGER.debug("@ XSS 권한체크 START ----------------------------------------------");`

`CnsltAnswerList` 를 `resultList` 로 이름 바꾸기

`_result` 를 `resultList` 로 이름 바꾸기

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uss/olp/cns/web/EgovCnsltManageController.java:302:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/olp/cns/web/EgovCnsltManageController.java:303:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/olp/cns/web/EgovCnsltManageController.java:456:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/olp/cns/web/EgovCnsltManageController.java:464:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/olp/cns/web/EgovCnsltManageController.java:473:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_cnt' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/olp/cns/web/EgovCnsltManageController.java:474:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/olp/cns/web/EgovCnsltManageController.java:517:	UnnecessarySemicolon:	UnnecessarySemicolon: 필요없는 문장 (;)이 있음
src/main/java/egovframework/com/uss/olp/cns/web/EgovCnsltManageController.java:530:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_atchFileId' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/olp/cns/web/EgovCnsltManageController.java:571:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'CnsltAnswerList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/olp/cns/web/EgovCnsltManageController.java:618:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 '_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovCnsltManageController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.08.22  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(final이 아닌 변수는 밑줄을 포함할 수 없음)
 *   2025.08.22  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-UnnecessarySemicolon(필요없는 ; 문장 존재)
```

https://github.com/eGovFramework/egovframe-common-components/pull/710

<hr>

### 2025-08-23 토 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovOnlinePollManageController

불필요한 괄호제거
```java
		// 로그인 객체 선언
		LoginVO loginVO = (LoginVO) EgovUserDetailsHelper.getAuthenticatedUser();
//		String uniqId = (loginVO == null ? "" : EgovStringUtil.isNullToString(loginVO.getUniqId()));
		// 아이디 설정
		if (loginVO != null) {
			onlinePollManage.setFrstRegisterId(loginVO.getUniqId());
			onlinePollManage.setLastUpdusrId(loginVO.getUniqId());
		}
````

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uss/olp/opm/web/EgovOnlinePollManageController.java:221:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/uss/olp/opm/web/EgovOnlinePollManageController.java:290:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
```

2. 브랜치 생성

```
feature/pmd/EgovOnlinePollManageController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.08.23  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-UselessParentheses(불필요한 괄호사용)
```

https://github.com/eGovFramework/egovframe-common-components/pull/711

<hr>

### 2025-08-23 토 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovOnlinePollPartcptnController

`ReusltScript` 를 `reusltScript` 로 이름 바꾸기

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uss/olp/opp/web/EgovOnlinePollPartcptnController.java:200:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'ReusltScript' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/olp/opp/web/EgovOnlinePollPartcptnController.java:212:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'ReusltScript' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovOnlinePollPartcptnController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.08.23  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(final이 아닌 변수는 밑줄을 포함할 수 없음)
```

https://github.com/eGovFramework/egovframe-common-components/pull/712

<hr>

### 2025-08-25 월 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovQustnrManageController

불필요한 괄호제거
```java
		// 로그인 객체 선언
		LoginVO loginVO = (LoginVO) EgovUserDetailsHelper.getAuthenticatedUser();
//		String uniqId = (loginVO == null ? "" : EgovStringUtil.isNullToString(loginVO.getUniqId()));
		// 아이디 설정
		if (loginVO != null) {
			qustnrManageVO.setFrstRegisterId(loginVO.getUniqId());
			qustnrManageVO.setLastUpdusrId(loginVO.getUniqId());
		}
````

LOGGER 제거하고 `@Slf4j` 로 수정
```java
//private static final Logger LOGGER = LoggerFactory.getLogger(EgovQustnrManageController.class);
```

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uss/olp/qmc/web/EgovQustnrManageController.java:374:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
```

2. 브랜치 생성

```
feature/pmd/EgovQustnrManageController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.08.25  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-UselessParentheses(불필요한 괄호사용)
```

https://github.com/eGovFramework/egovframe-common-components/pull/714

<hr>

### 2025-08-25 월 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovQustnrRespondInfoController

`ReusltScript` 를 `reusltScript` 로 이름 바꾸기

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uss/olp/qri/web/EgovQustnrRespondInfoController.java:381:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'ResultScript' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovQustnrRespondInfoController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.08.25  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(final이 아닌 변수는 밑줄을 포함할 수 없음)
```

https://github.com/eGovFramework/egovframe-common-components/pull/715

<hr>

### 2025-08-26 화 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovQustnrRespondManageController

불필요한 괄호제거
```java
		// 로그인 객체 선언
		LoginVO loginVO = (LoginVO) EgovUserDetailsHelper.getAuthenticatedUser();
//		String uniqId = (loginVO == null ? "" : EgovStringUtil.isNullToString(loginVO.getUniqId()));
		// 아이디 설정
		if (loginVO != null) {
			qustnrRespondManageVO.setFrstRegisterId(loginVO.getUniqId());
			qustnrRespondManageVO.setLastUpdusrId(loginVO.getUniqId());
		}
````

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uss/olp/qrm/web/EgovQustnrRespondManageController.java:243:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/uss/olp/qrm/web/EgovQustnrRespondManageController.java:333:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
```

2. 브랜치 생성

```
feature/pmd/EgovQustnrRespondManageController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.08.26  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-UselessParentheses(불필요한 괄호사용)
```

https://github.com/eGovFramework/egovframe-common-components/pull/716

<hr>

### 2025-08-26 화 PMD로 소프트웨어 보안약점 진단하고 제거하기-QustnrTmplatManageVO

`getQestnrTmplatImagepathnm, setQestnrTmplatImagepathnm` 메서드를 제거하고 `@Getter, @Setter` 추가

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uss/olp/qtm/service/QustnrTmplatManageVO.java:96:	AvoidArrayLoops:	AvoidArrayLoops: 배열의 값을 루프문을 이용하여 복사하는 것 보다 System.arraycopy() 메소드를 이용하여 복사하는 것이 효율적이며 수행 속도가 빠름
```

2. 브랜치 생성

```
feature/pmd/QustnrTmplatManageVO
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.08.26  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-AvoidArrayLoops(배열의 값을 루프문을 이용하여 복사하는 것 보다, System.arraycopy() 메소드를 이용하여 복사하는 것이 효율적이며 수행 속도가 빠름)
```

https://github.com/eGovFramework/egovframe-common-components/pull/717

<hr>

### 2025-08-27 수 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovIndvdlInfoPolicyController

불필요한 괄호제거
```java
//String uniqId = (loginVO == null ? "" : EgovStringUtil.isNullToString(loginVO.getUniqId()));
String uniqId = loginVO == null ? "" : EgovStringUtil.isNullToString(loginVO.getUniqId());
````

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uss/sam/ipm/web/EgovIndvdlInfoPolicyController.java:198:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/uss/sam/ipm/web/EgovIndvdlInfoPolicyController.java:263:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
```

2. 브랜치 생성

```
feature/pmd/EgovIndvdlInfoPolicyController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.08.27  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-UselessParentheses(불필요한 괄호사용)
```

https://github.com/eGovFramework/egovframe-common-components/pull/718

<hr>

### 2025-08-27 수 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovStplatManageController

`StplatList` 를 `resultList` 로 이름 바꾸기

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uss/sam/stp/web/EgovStplatManageController.java:112:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'StplatList' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovStplatManageController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.08.27  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(final이 아닌 변수는 밑줄을 포함할 수 없음)
```

https://github.com/eGovFramework/egovframe-common-components/pull/719

<hr>

### 2025-08-28 목 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovEntrprsManageController

`@ModelAttribute` 애노테이션 사용에서 `private` 을 `public` 으로 수정

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uss/umt/web/EgovEntrprsManageController.java:79:	UnusedPrivateMethod:	UnusedPrivateMethod: 사용되지 않는 Private Method 'getPasswordHintResult(ComDefaultCodeVO)' 가 선언되었음
src/main/java/egovframework/com/uss/umt/web/EgovEntrprsManageController.java:86:	UnusedPrivateMethod:	UnusedPrivateMethod: 사용되지 않는 Private Method 'getSexdstnCode_result(ComDefaultCodeVO)' 가 선언되었음
src/main/java/egovframework/com/uss/umt/web/EgovEntrprsManageController.java:93:	UnusedPrivateMethod:	UnusedPrivateMethod: 사용되지 않는 Private Method 'getEntrprsMberSttus_result(ComDefaultCodeVO)' 가 선언되었음
src/main/java/egovframework/com/uss/umt/web/EgovEntrprsManageController.java:100:	UnusedPrivateMethod:	UnusedPrivateMethod: 사용되지 않는 Private Method 'getGroupId_result(ComDefaultCodeVO)' 가 선언되었음
src/main/java/egovframework/com/uss/umt/web/EgovEntrprsManageController.java:107:	UnusedPrivateMethod:	UnusedPrivateMethod: 사용되지 않는 Private Method 'getEntrprsSeCode_result(ComDefaultCodeVO)' 가 선언되었음
src/main/java/egovframework/com/uss/umt/web/EgovEntrprsManageController.java:114:	UnusedPrivateMethod:	UnusedPrivateMethod: 사용되지 않는 Private Method 'getIndutyCode_result(ComDefaultCodeVO)' 가 선언되었음
```

2. 브랜치 생성

```
feature/pmd/EgovEntrprsManageController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.08.28  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-UnusedPrivateMethod(사용되지 않는 Private Method 선언을 탐지)
```

https://github.com/eGovFramework/egovframe-common-components/pull/723

<hr>

### 2025-08-28 목 PMD로 소프트웨어 보안약점 진단하고 제거하기-EgovMberManageController

`mberSttus_result` 를 `mberSttusResult` 로 이름 바꾸기

`passwordHint_result` 를 `passwordHintResult` 로 이름 바꾸기

`sexdstnCode_result` 를 `sexdstnCodeResult` 로 이름 바꾸기

`mberSttus_result` 를 `mberSttusResult` 로 이름 바꾸기

`groupId_result` 를 `groupIdResult` 로 이름 바꾸기

`passwordHint_result` 를 `passwordHintResult` 로 이름 바꾸기

`sexdstnCode_result` 를 `sexdstnCodeResult` 로 이름 바꾸기

`mberSttus_result` 를 `mberSttusResult` 로 이름 바꾸기

`groupId_result` 를 `groupIdResult` 로 이름 바꾸기

`passwordHint_result` 를 `passwordHintResult` 로 이름 바꾸기

`sexdstnCode_result` 를 `sexdstnCodeResult` 로 이름 바꾸기

`mberSttus_result` 를 `mberSttusResult` 로 이름 바꾸기

`groupId_result` 를 `groupIdResult` 로 이름 바꾸기

`passwordHint_result` 를 `passwordHintResult` 로 이름 바꾸기

`sexdstnCode_result` 를 `sexdstnCodeResult` 로 이름 바꾸기

<hr>

1. PMD로 소프트웨어 보안약점 진단 결과

```
src/main/java/egovframework/com/uss/umt/web/EgovMberManageController.java:119:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'mberSttus_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovMberManageController.java:147:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'passwordHint_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovMberManageController.java:150:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sexdstnCode_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovMberManageController.java:153:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'mberSttus_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovMberManageController.java:156:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'groupId_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovMberManageController.java:191:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'passwordHint_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovMberManageController.java:194:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sexdstnCode_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovMberManageController.java:197:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'mberSttus_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovMberManageController.java:200:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'groupId_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovMberManageController.java:241:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'passwordHint_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovMberManageController.java:245:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sexdstnCode_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovMberManageController.java:249:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'mberSttus_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovMberManageController.java:253:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'groupId_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovMberManageController.java:406:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'passwordHint_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovMberManageController.java:409:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sexdstnCode_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
```

2. 브랜치 생성

```
feature/pmd/EgovMberManageController
```

3. 이클립스 > Source > Format

4. 개정이력 수정

```java
 *   2025.08.28  이백행          2025년 컨트리뷰션 PMD로 소프트웨어 보안약점 진단하고 제거하기-LocalVariableNamingConventions(final이 아닌 변수는 밑줄을 포함할 수 없음)
```

https://github.com/eGovFramework/egovframe-common-components/pull/724

<hr>

```
src/main/java/egovframework/com/uss/umt/web/EgovUserManageController.java:119:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'emplyrSttusCode_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovUserManageController.java:147:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'passwordHint_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovUserManageController.java:150:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sexdstnCode_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovUserManageController.java:153:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'emplyrSttusCode_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovUserManageController.java:156:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'insttCode_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovUserManageController.java:159:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'orgnztId_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovUserManageController.java:162:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'groupId_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovUserManageController.java:229:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'passwordHint_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovUserManageController.java:232:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'sexdstnCode_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovUserManageController.java:235:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'emplyrSttusCode_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovUserManageController.java:238:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'insttCode_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovUserManageController.java:241:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'orgnztId_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/uss/umt/web/EgovUserManageController.java:244:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'groupId_result' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/cas/service/EgovMessageUtil.java:137:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fcc/service/EgovDateUtil.java:195:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fcc/service/EgovDateUtil.java:196:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fcc/service/EgovDateUtil.java:575:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'SDay' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/fcc/service/EgovDateUtil.java:701:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'Week' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/fcc/service/EgovDateUtil.java:728:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'HH' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/fcc/service/EgovDateUtil.java:729:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'MM' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/fcc/service/EgovDateUtil.java:859:	AvoidReassigningParameters:	AvoidReassigningParameters: 'timeStr' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/utl/fcc/service/EgovEhgtCalcUtil.java:81:	CloseResource:	CloseResource: 리소스 'InputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/fcc/service/EgovEhgtCalcUtil.java:82:	CloseResource:	CloseResource: 리소스 'InputStreamReader' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/fcc/service/EgovEhgtCalcUtil.java:262:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fcc/service/EgovEhgtCalcUtil.java:277:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fcc/service/EgovEhgtCalcUtil.java:277:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fcc/service/EgovEhgtCalcUtil.java:280:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fcc/service/EgovEhgtCalcUtil.java:292:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fcc/service/EgovEhgtCalcUtil.java:292:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fcc/service/EgovEhgtCalcUtil.java:295:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fcc/service/EgovEhgtCalcUtil.java:304:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fcc/service/EgovEhgtCalcUtil.java:307:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fcc/service/EgovEhgtCalcUtil.java:307:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fcc/service/EgovEhgtCalcUtil.java:319:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fcc/service/EgovEhgtCalcUtil.java:319:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fcc/service/EgovEhgtCalcUtil.java:322:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fcc/service/EgovFormBasedFileUtil.java:104:	CloseResource:	CloseResource: 리소스 'OutputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/fcc/service/EgovFormBasedFileUtil.java:113:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/utl/fcc/service/EgovFormBasedFileUtil.java:218:	AvoidReassigningParameters:	AvoidReassigningParameters: 'original' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/utl/fcc/service/EgovFormBasedFileUtil.java:225:	CloseResource:	CloseResource: 리소스 'BufferedInputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/fcc/service/EgovFormBasedFileUtil.java:226:	CloseResource:	CloseResource: 리소스 'BufferedOutputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/fcc/service/EgovFormBasedFileUtil.java:234:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/utl/fcc/service/EgovFormBasedFileUtil.java:297:	CloseResource:	CloseResource: 리소스 'BufferedInputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/fcc/service/EgovFormBasedFileUtil.java:298:	CloseResource:	CloseResource: 리소스 'BufferedOutputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/fcc/service/EgovFormBasedFileUtil.java:306:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/utl/fcc/service/EgovFormBasedUUID.java:235:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 explicit unboxing
src/main/java/egovframework/com/utl/fcc/service/EgovFormBasedUUID.java:237:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 explicit unboxing
src/main/java/egovframework/com/utl/fcc/service/EgovFormBasedUUID.java:239:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 explicit unboxing
src/main/java/egovframework/com/utl/fcc/service/EgovFormBasedUUID.java:241:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 explicit unboxing
src/main/java/egovframework/com/utl/fcc/service/EgovFormBasedUUID.java:243:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 explicit unboxing
src/main/java/egovframework/com/utl/fcc/service/EgovFormBasedUUID.java:434:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fcc/service/EgovFormBasedUUID.java:482:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fcc/service/EgovFormBasedUUID.java:503:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fcc/service/EgovFormBasedUUID.java:504:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fcc/service/EgovFormBasedUUID.java:505:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fcc/service/EgovFormBasedUUID.java:506:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fcc/service/EgovNumberCheckUtil.java:35:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'IDAdd' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/fcc/service/EgovNumberCheckUtil.java:37:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'count_num' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/fcc/service/EgovNumberCheckUtil.java:38:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'add_num' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/fcc/service/EgovNumberCheckUtil.java:39:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'total_id' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/fcc/service/EgovNumberCheckUtil.java:157:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fcc/service/EgovStringUtil.java:639:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/utl/fcc/service/EgovStringUtil.java:678:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/utl/fcc/service/EgovStringUtil.java:768:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 explicit conversion from char to int through Integer
src/main/java/egovframework/com/utl/fcc/service/EgovStringUtil.java:769:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 explicit conversion from char to int through Integer
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:22:	FieldNamingConventions:	FieldNamingConventions: 'field' 의 변수 'g_hmVt' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:25:	FieldNamingConventions:	FieldNamingConventions: 'field' 의 변수 'g_hmVl' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:28:	FieldNamingConventions:	FieldNamingConventions: 'field' 의 변수 'g_hmAr' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:31:	FieldNamingConventions:	FieldNamingConventions: 'field' 의 변수 'g_hmWt' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:41:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:42:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:43:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:44:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:46:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:47:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:48:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:53:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:54:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:55:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:59:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:60:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:61:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:62:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:72:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:73:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:74:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:83:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:84:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:85:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:86:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:87:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:104:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:119:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:134:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/fda/ucc/service/EgovUnitCalcUtil.java:149:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/pao/service/PrntngOutptVO.java:56:	AvoidArrayLoops:	AvoidArrayLoops: 배열의 값을 루프문을 이용하여 복사하는 것 보다 System.arraycopy() 메소드를 이용하여 복사하는 것이 효율적이며 수행 속도가 빠름
src/main/java/egovframework/com/utl/sim/service/EgovClntInfo.java:79:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'user_agent' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/sim/service/EgovClntInfo.java:80:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'os_info' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/sim/service/EgovClntInfo.java:81:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'os_conf' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/sim/service/EgovClntInfo.java:99:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'user_agent' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/sim/service/EgovClntInfo.java:139:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'user_agent' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/sim/service/EgovClntInfo.java:145:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 's_loc' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/sim/service/EgovClntInfo.java:147:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'f_loc' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/sim/service/EgovFileCmprs.java:53:	CloseResource:	CloseResource: 리소스 'FileInputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sim/service/EgovFileCmprs.java:54:	CloseResource:	CloseResource: 리소스 'FileOutputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sim/service/EgovFileCmprs.java:55:	CloseResource:	CloseResource: 리소스 'ZipInputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sim/service/EgovFileCmprs.java:73:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/utl/sim/service/EgovFileCmprs.java:84:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/utl/sim/service/EgovFileMntrg.java:277:	CloseResource:	CloseResource: 리소스 'FileWriter' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sim/service/EgovFileMntrg.java:278:	CloseResource:	CloseResource: 리소스 'BufferedWriter' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sim/service/EgovFileMntrg.java:279:	CloseResource:	CloseResource: 리소스 'BufferedReader' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sim/service/EgovFileMntrg.java:285:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/utl/sim/service/EgovFileMntrg.java:310:	CloseResource:	CloseResource: 리소스 'BufferedReader' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sim/service/EgovFileMntrg.java:311:	CloseResource:	CloseResource: 리소스 'FileReader' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sim/service/EgovFileMntrg.java:321:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/utl/sim/service/EgovFileScrty.java:72:	CloseResource:	CloseResource: 리소스 'BufferedInputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sim/service/EgovFileScrty.java:73:	CloseResource:	CloseResource: 리소스 'BufferedOutputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sim/service/EgovFileScrty.java:84:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/utl/sim/service/EgovFileScrty.java:114:	CloseResource:	CloseResource: 리소스 'BufferedReader' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sim/service/EgovFileScrty.java:115:	CloseResource:	CloseResource: 리소스 'BufferedOutputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sim/service/EgovFileScrty.java:126:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/utl/sim/service/EgovFileTool.java:98:	AvoidReassigningParameters:	AvoidReassigningParameters: 'basePath' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/utl/sim/service/EgovFileTool.java:141:	AvoidReassigningParameters:	AvoidReassigningParameters: 'basePath' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/utl/sim/service/EgovFileTool.java:206:	AvoidReassigningParameters:	AvoidReassigningParameters: 'basePath' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/utl/sim/service/EgovFileTool.java:262:	AvoidReassigningParameters:	AvoidReassigningParameters: 'basePath' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/utl/sim/service/EgovFileTool.java:320:	AvoidReassigningParameters:	AvoidReassigningParameters: 'basePath' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/utl/sim/service/EgovFileTool.java:351:	AvoidReassigningParameters:	AvoidReassigningParameters: 'basePath' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/utl/sim/service/EgovFileTool.java:364:	CloseResource:	CloseResource: 리소스 'BufferedReader' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sim/service/EgovFileTool.java:373:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/utl/sim/service/EgovFileToolBean.java:85:	AvoidReassigningParameters:	AvoidReassigningParameters: 'basePath' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/utl/sim/service/EgovFileToolBean.java:99:	CloseResource:	CloseResource: 리소스 'BufferedReader' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sim/service/EgovFileToolBean.java:108:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/utl/sim/service/EgovMenuGov.java:46:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'FileName' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/sim/service/EgovMenuGov.java:75:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'FileName' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/sim/service/EgovMenuGov.java:79:	CloseResource:	CloseResource: 리소스 'BufferedWriter' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sim/service/EgovNetworkState.java:84:	CloseResource:	CloseResource: 리소스 'InputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sim/service/EgovNetworkState.java:87:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/utl/sim/service/EgovNetworkState.java:88:	StringInstantiation:	StringInstantiation: 필요없는 Instance가 생성되어 있음
src/main/java/egovframework/com/utl/sim/service/EgovNetworkState.java:118:	CloseResource:	CloseResource: 리소스 'BufferedReader' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sim/service/EgovNetworkState.java:183:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'InetA' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/sim/service/EgovNetworkState.java:228:	CloseResource:	CloseResource: 리소스 'BufferedReader' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sim/service/EgovNetworkState.java:228:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'b_out' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/sim/service/EgovNetworkState.java:293:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 explicit boxing
src/main/java/egovframework/com/utl/sim/service/EgovPdfCnvr.java:75:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'file_iter' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/sim/service/EgovPdfCnvr.java:141:	CloseResource:	CloseResource: 리소스 'InputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sim/service/EgovPdfCnvr.java:142:	CloseResource:	CloseResource: 리소스 'OutputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sim/service/EgovPdfCnvr.java:162:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/utl/sim/service/EgovXMLDoc.java:63:	CloseResource:	CloseResource: 리소스 'FileInputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sim/service/EgovXMLDoc.java:90:	CloseResource:	CloseResource: 리소스 'FileOutputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sim/service/EgovXMLDoc.java:94:	AvoidReassigningParameters:	AvoidReassigningParameters: 'file' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/utl/sim/service/EgovXMLDoc.java:120:	CloseResource:	CloseResource: 리소스 'FileInputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sys/dbm/service/DbMntrngChecker.java:49:	CloseResource:	CloseResource: 리소스 'Connection' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sys/dbm/service/DbMntrngChecker.java:50:	CloseResource:	CloseResource: 리소스 'PreparedStatement' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sys/dbm/service/DbMntrngChecker.java:52:	CloseResource:	CloseResource: 리소스 'ResultSet' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sys/fsm/service/FileSystemChecker.java:110:	CloseResource:	CloseResource: 리소스 'FileWriter' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sys/fsm/service/FileSystemChecker.java:138:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 implicit unboxing. Use Long.parseLong(...) instead
src/main/java/egovframework/com/utl/sys/fsm/service/FileSystemChecker.java:142:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 implicit unboxing. Use Long.parseLong(...) instead
src/main/java/egovframework/com/utl/sys/fsm/service/FileSystemChecker.java:185:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/sys/fsm/service/FileSystemChecker.java:211:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 implicit unboxing. Use Long.parseLong(...) instead
src/main/java/egovframework/com/utl/sys/fsm/service/FileSystemChecker.java:233:	CloseResource:	CloseResource: 리소스 'BufferedReader' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sys/fsm/service/FileSystemChecker.java:233:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'b_out' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/sys/htm/service/HttpMntrngChecker.java:40:	AvoidUsingHardCodedIP:	AvoidUsingHardCodedIP: 하드코딩된 IP 주소 whiteListURL 사용
src/main/java/egovframework/com/utl/sys/htm/service/HttpMntrngChecker.java:65:	AvoidReassigningParameters:	AvoidReassigningParameters: 'siteUrl' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/utl/sys/htm/service/impl/EgovHttpMonServiceImpl.java:33:	FieldNamingConventions:	FieldNamingConventions: 'field' 의 변수 'HttpMonDAO' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/sys/nsm/service/EgovNtwrkSvcMntrngScheduling.java:88:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 implicit unboxing. Use Integer.parseInt(...) instead
src/main/java/egovframework/com/utl/sys/prm/service/ProcessMonChecker.java:52:	CloseResource:	CloseResource: 리소스 'BufferedReader' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sys/prm/service/ProcessMonChecker.java:79:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/sys/pxy/service/ProxyServer.java:112:	CloseResource:	CloseResource: 리소스 'InputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sys/pxy/service/ProxyServer.java:113:	CloseResource:	CloseResource: 리소스 'OutputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sys/pxy/service/ProxyServer.java:118:	CloseResource:	CloseResource: 리소스 'InputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sys/pxy/service/ProxyServer.java:119:	CloseResource:	CloseResource: 리소스 'OutputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sys/pxy/service/ProxyServer.java:128:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/utl/sys/pxy/service/ProxyServer.java:164:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/sys/pxy/service/ProxyThread.java:22:	ImmutableField:	ImmutableField: 생성자에서 Assign된 변수 'client' 를 Final로 선언하지 않았음
src/main/java/egovframework/com/utl/sys/pxy/service/ProxyThread.java:99:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/utl/sys/pxy/web/EgovProxySvcController.java:74:	FieldNamingConventions:	FieldNamingConventions: 'field' 의 변수 'EgovCmmUseService' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/sys/pxy/web/EgovProxySvcController.java:127:	AvoidReassigningParameters:	AvoidReassigningParameters: 'proxySvcVO' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/utl/sys/srm/service/EgovServerResrceMntrngScheduling.java:72:	ImmutableField:	ImmutableField: 생성자에서 Assign된 변수 'serverResrceMntrngVO' 를 Final로 선언하지 않았음
src/main/java/egovframework/com/utl/sys/srm/service/EgovServerResrceMntrngScheduling.java:83:	CloseResource:	CloseResource: 리소스 'JMXConnector' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sys/srm/web/EgovServerResrceMntrngController.java:150:	AvoidReassigningParameters:	AvoidReassigningParameters: 'serverResrceMntrngVO' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/utl/sys/ssy/service/impl/EgovSynchrnServerServiceImpl.java:249:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'SynchrnServerVo' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/sys/ssy/service/impl/EgovSynchrnServerServiceImpl.java:327:	CloseResource:	CloseResource: 리소스 'FileInputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sys/ssy/service/impl/EgovSynchrnServerServiceImpl.java:460:	CloseResource:	CloseResource: 리소스 'InputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sys/ssy/service/impl/EgovSynchrnServerServiceImpl.java:461:	CloseResource:	CloseResource: 리소스 'OutputStream' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/sys/ssy/service/impl/EgovSynchrnServerServiceImpl.java:480:	AssignmentInOperand:	AssignmentInOperand: 피연산자내에 할당문이 사용됨. Code 를 복잡하고 가독성이 떨어지게 만듬
src/main/java/egovframework/com/utl/sys/ssy/service/impl/EgovSynchrnServerServiceImpl.java:485:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'SynchrnServerVo' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/sys/ssy/service/impl/EgovSynchrnServerServiceImpl.java:519:	LocalVariableNamingConventions:	LocalVariableNamingConventions: 'local variable' 의 변수 'SynchrnServerVo' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/sys/ssy/web/EgovSynchrnServerController.java:69:	FieldNamingConventions:	FieldNamingConventions: 'field' 의 변수 'EgovCmmUseService' 이  '[a-z][a-zA-Z0-9]*'  로 시작함
src/main/java/egovframework/com/utl/sys/ssy/web/EgovSynchrnServerController.java:152:	AvoidReassigningParameters:	AvoidReassigningParameters: 'synchrnServerVO' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/utl/sys/ssy/web/EgovSynchrnServerController.java:172:	AvoidReassigningParameters:	AvoidReassigningParameters: 'synchrnServerVO' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/utl/sys/ssy/web/EgovSynchrnServerController.java:191:	AvoidReassigningParameters:	AvoidReassigningParameters: 'synchrnServerVO' 처럼 파라미터 값을 직접 변경하지 말 것
src/main/java/egovframework/com/utl/sys/ssy/web/EgovSynchrnServerController.java:370:	SimplifyBooleanExpressions:	SimplifyBooleanExpressions: boolean 사용 시 불필요한 비교 연산을 피하도록 함
src/main/java/egovframework/com/utl/sys/ssy/web/EgovSynchrnServerController.java:373:	SimplifyBooleanExpressions:	SimplifyBooleanExpressions: boolean 사용 시 불필요한 비교 연산을 피하도록 함
src/main/java/egovframework/com/utl/sys/trm/service/impl/TrsmrcvMntrngCheckerTestImpl.java:51:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 explicit unboxing
src/main/java/egovframework/com/utl/sys/trm/service/impl/TrsmrcvMntrngCheckerTestImpl.java:52:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 explicit unboxing
src/main/java/egovframework/com/utl/sys/trm/service/impl/TrsmrcvMntrngCheckerTestImpl.java:54:	UnnecessaryBoxing:	UnnecessaryBoxing: 불필요한 explicit unboxing
src/main/java/egovframework/com/utl/wed/filter/CkFilter.java:55:	FieldNamingConventions:	FieldNamingConventions: 'constant' 의 변수 'log' 이  '[A-Z][A-Z_0-9]*'  로 시작함
src/main/java/egovframework/com/utl/wed/filter/CkImageSaver.java:68:	FieldNamingConventions:	FieldNamingConventions: 'constant' 의 변수 'log' 이  '[A-Z][A-Z_0-9]*'  로 시작함
src/main/java/egovframework/com/utl/wed/filter/CkImageSaver.java:72:	ImmutableField:	ImmutableField: 생성자에서 Assign된 변수 'imageBaseDir' 를 Final로 선언하지 않았음
src/main/java/egovframework/com/utl/wed/filter/CkImageSaver.java:73:	ImmutableField:	ImmutableField: 생성자에서 Assign된 변수 'imageDomain' 를 Final로 선언하지 않았음
src/main/java/egovframework/com/utl/wed/filter/CkImageSaver.java:74:	ImmutableField:	ImmutableField: 생성자에서 Assign된 변수 'allowFileTypeArr' 를 Final로 선언하지 않았음
src/main/java/egovframework/com/utl/wed/filter/CkImageSaver.java:75:	ImmutableField:	ImmutableField: 생성자에서 Assign된 변수 'fileSaveManager' 를 Final로 선언하지 않았음
src/main/java/egovframework/com/utl/wed/filter/CkImageSaver.java:87:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/wed/filter/CkImageSaver.java:90:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/wed/filter/CkImageSaver.java:95:	UselessParentheses:	UselessParentheses: 괄호가 없어도 되는 상황에서 불필요한 괄호를 사용할 경우 마치 메소드 호출처럼 보여서 소스 코드의 가독성을 떨어뜨릴 수 있음
src/main/java/egovframework/com/utl/wed/filter/CkImageSaver.java:185:	CloseResource:	CloseResource: 리소스 'PrintWriter' 가 사용 후에 닫혔는지 확인필요
src/main/java/egovframework/com/utl/wed/filter/DirectoryPathManager.java:55:	UnnecessarySemicolon:	UnnecessarySemicolon: 필요없는 문장 (;)이 있음
```
