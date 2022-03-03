# 腾讯云 SCF Java Demo

SCF Java Demo应用

## 构建项目

```bash
gradle build
```
查看构建产物：

```bash
tree build/distributions
```

需要部署的构建产物:

```
build/distributions
└── scf-java-demo.zip

0 directories, 1 file

```


### 部署到 腾讯云 云函数 SCF

控制台链接：https://console.cloud.tencent.com/scf

在控制台选择对应的 zip 文件上传：

![Deploy via Console](https://user-images.githubusercontent.com/251222/156494330-e6735398-18e4-44ba-a132-79b21d95c603.png)

在控制台进行测试：

![Test via Console](https://user-images.githubusercontent.com/251222/156494335-ced01adf-b2d8-4218-942d-93fa3f2cdbae.png)

### 部署到 腾讯云 Cloudbase SCF

控制台链接：https://console.cloud.tencent.com/tcb

在控制台选择对应的 zip 文件上传：

![Deploy via Console](https://user-images.githubusercontent.com/251222/156492930-cf6a458f-0296-42b5-bbd1-72d7f82ef939.png)

在控制台进行测试：

![Test via Console](https://user-images.githubusercontent.com/251222/156492933-ebe3a698-813c-469b-ae46-1dc960644052.png)