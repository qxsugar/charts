自定义Charts
-------------------------------

### 更新版本

> 修改`charts/app/Chart.yaml`的`version`，github action会自动打包

### 添加仓库

> helm repo add {alias} https://me.ppapi.cn/charts

### 更新仓库

> helm repo update

### 搜索安装包

> helm search repo {appName}

### 安装应用

> helm install {chartName} {alias}/{appName}
