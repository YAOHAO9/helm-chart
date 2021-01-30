# helm-chart

### 打包
```bash
1、helm package 文件名 # 打包
2、将打好tgz的包放在当前目录 
3、helm repo index --url https://yaohao9.github.com/helm-chart/ . # 自动更新index.yaml
4、helm repo add myrepo https://yaohao9.github.com/helm-chart
```
