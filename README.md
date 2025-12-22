# 在`Github Actions`上使用`UUP dump`自动制作`Windows 10/11` ISO镜像

## 说明
1. 本项目的主要目的是：使用`UUP dump`自动制作`Windows 10/11`ISO镜像(使用`Github Actions`自动构建)

## 地址
1. 本仓库地址: https://github.com/yuanpeirong/UUPdumpWinISO
2. `UUP dump`地址: https://uupdump.net/

## 目前已构建`Windows 10`版本
- Windows10_21H2_amd64_Cumulative_Update：`19044.6693.251217-1256.21H2_RELEASE_SVC_IM_CLIENTMULTI_X64FRE_ZH-CN.ISO`
- Windows10_21H2_amd64_Feature_update：`19044.6691.251205-1411.21H2_RELEASE_SVC_PROD1_CLIENTMULTI_X64FRE_ZH-CN.ISO`
- Windows10_22H2_amd64_Cumulative_Update：`19045.6693.251217-1256.22H2_RELEASE_SVC_IM_CLIENTMULTI_X64FRE_ZH-CN.ISO`
- Windows10_22H2_amd64_Feature_update：`19045.6693.251217-1256.22H2_RELEASE_SVC_IM_CLIENTMULTI_X64FRE_ZH-CN.ISO`

## 目前已构建`Windows 11`版本
- Windows11_24H2_amd64：`26100.7462.251206-1712.GE_RELEASE_SVC_PROD1_CLIENTMULTI_X64FRE_ZH-CN.ISO`
- Windows11_25H2_amd64：`26200.7462.251206-1712.25H2_GE_RELEASE_SVC_PROD1_CLIENTMULTI_X64FRE_ZH-CN.ISO`

## 仓库原理和目的
- 将`UUP dump`网站上得到的脚本上传到仓库，利用Github Actions自动生成ISO镜像
- 将本地运行`UUP dump`脚本改为远程运行，不耗时、不耗CPU、不耗硬盘，坐等远程完成后下载即可
- 支持同时运行多个制作任务

