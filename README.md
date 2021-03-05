CHARTS 公开仓库
------------------

> 本项目为通用服务的app charts配置项目
> 
> 通过一个values.yaml快速安装一个项目

### 基本命令
1. 打包一个charts文件
> helm package ${app}

2. 重新构建一个索引
> helm repo index charts

3. 安装repo
> helm repo add my-charts https://me.isugar.wang/charts

4. 安装一个app
> helm install ${name} my-charts/base-app -f values.yaml