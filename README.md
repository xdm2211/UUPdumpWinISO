# 在`Github Actions`上使用`UUP dump`自动制作`Windows 10/11` ISO镜像

## 说明
1. 本项目的主要目的是：使用`UUP dump`自动制作`Windows 10/11`ISO镜像(使用`Github Actions`自动构建)

## 地址
1. 本仓库地址: https://github.com/yuanpeirong/UUPdumpWinISO (只发布源码)
2. 备用仓库地址: https://github.com/yprsoft/UUPdumpWinISO (发布源码+镜像)
3. `UUP dump`地址: https://uupdump.net/

## 目前已构建`Windows 10`版本
- Windows10_21H2_amd64_Cumulative_Update：
  - `19044.6812.260122-0756.21H2_RELEASE_SVC_IM_CLIENTMULTI_X64FRE_ZH-CN.ISO` (2026年2月)
- Windows10_21H2_amd64_Feature_update：
  - `19044.7184.260411-1655.21H2_RELEASE_SVC_PROD1_CLIENTMULTI_X64FRE_ZH-CN.ISO` (2026年4月)
- Windows10_22H2_amd64_Cumulative_Update：
  - `19045.7184.260411-1655.22H2_RELEASE_SVC_PROD1_CLIENTMULTI_X64FRE_ZH-CN.ISO` (2026年4月)
- Windows10_22H2_amd64_Feature_update：
  - `19045.7184.260411-1655.22H2_RELEASE_SVC_PROD1_CLIENTMULTI_X64FRE_ZH-CN.ISO` (2026年4月)

## 目前已构建`Windows 11`版本
- Windows11_23H2_amd64：
  - `22631.6936.260411-1701.23H2_NI_RELEASE_SVC_PROD1_CLIENTMULTI_X64FRE_ZH-CN.ISO` (2026年4月)
- Windows11_24H2_amd64：
  - `26100.8313.260413-1757.GE_RELEASE_SVC_PROD3_CLIENTMULTI_X64FRE_ZH-CN.ISO` (2026年4月第2次)
- Windows11_25H2_amd64：
  - `26200.8313.260413-1757.25H2_GE_RELEASE_SVC_PROD3_CLIENTMULTI_X64FRE_ZH-CN.ISO` (2026年4月第2次)
- Windows11_26H1_amd64：
  - `28000.1836.260411-1607.BR_RELEASE_SVC_PROD1_CLIENTMULTI_X64FRE_ZH-CN.ISO` (2026年4月)
  - `28000.1890` UUP代码暂有问题
- Windows11_Insider_Preview_Feature_Update_Dev_amd64
  - `26300.8276.260410-1655.GE_PRERELEASE_IM_CLIENTMULTI_X64FRE_ZH-CN.ISO` (2026年4月第2次)
- Windows11_Insider_Preview_Feature_Update_Canary_amd64
  - `28020.1863.260410-1018.BR_RELEASE_SVC_BETAFLT_PROD1_CLIENTMULTI_X64FRE_ZH-CN.ISO`  (2026年4月第2次)
- Windows11_Insider_Preview_rs_prerelease_Canary_amd64
  - `29570.1000.260410-1505.RS_PRERELEASE_CLIENTMULTI_X64FRE_ZH-CN.ISO`  (2026年4月第2次)

## 仓库原理和目的
- 将`UUP dump`网站上得到的脚本上传到仓库，利用Github Actions自动生成ISO镜像
- 将本地运行`UUP dump`脚本改为远程运行，不耗时、不耗CPU、不耗硬盘，坐等远程完成后下载即可
- 支持同时运行多个制作任务
