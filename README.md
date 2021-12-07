# Kubernetes selinux 一鍵安装

下載腳本

```shell
git clone https://github.com/MollyHuang/kubernetes.git

```

部署程序

```shell
cd kubernetes
chmod 777 deploy.sh
./deploy.sh
```

删除程序

```shell
cd kubernetes
chmod 777 delete.sh
./delete.sh
```

這是 selinux 的版本，ubuntu不適用。

必須支持 yum …指令才行，也許ubuntu環境可以嘗試把相關指令改為apt…或對應指令後試試。
