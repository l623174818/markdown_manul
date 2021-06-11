
# git

## git bash

### 1. 环境配置

> 设置本地用户  

```linux
1   git config --global user.name 'l623174818'  
2   git config --global user.email '623174818@qq.com'
```

> 初始化仓库

```linux
1    git init
```

> 创建SSH Key

```linux
1    ssh-keygen -t rsa -C '623174818@qq.com'
```

> 检查SSH Key

```linux
1    ~./ssh ls
```

### 2. 创建仓库

> 连接远程仓库

```linux
1    git remote add origin git@github.com:l623174818/*.git
```

> 查看远程仓库

```linux
1    git remote -v
```

> 查看仓库状态

```linux
1    git status
```

### 3. 上传文件

> 添加暂存区

```linux
1    git add -A
2    git add -u
3    git add .
```

> 添加新提交

```linux
1    git commit -m "注释"
```

> 推送文件

```linux
1    git push origin master
2    git push -u origin master (首次)
```

### 4. 下载文件

> 克隆仓库

```linux
1    git clone git@github.com:l623174818/*.git (首次)
```

> 拉回远程commit数据

```linux
1    git fetch
```

> 合并本地仓库

```linux
1    git merge
```

> 取回文件

```linux
1    git pull origin
```
