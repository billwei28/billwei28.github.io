---
title: Android 15 Selinux 编译
date: 2023-10-30 14:30:00
---

### Android 15 selinux 编译

Android 15 selinux 编译 和之前不一样了,之前可以
```shell
        mmm system/sepolicy
```
现在这个用不了了,

需要m 单独编译
```makefile
   make selinux_policy -j32
```

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

```mermaid
sequenceDiagram
title: 序列图
participant NetWork Thread
participant Message Thread
participant AI Thread


NetWork Thread->Message Thread: 收到网络信息
Message Thread->Message Thread: Paser处理信息
Message Thread->AI Thread: 解析好的信息

```
```mermaid
flowchart LR
A[hexo] --> B[mermaid]
A --> C[latex]
```

graph LR
    A[开始] --> B[中间步骤]
    B --> C[结束]


```mermaid
sequenceDiagram
title: 序列图
participant NetWork Thread
participant Message Thread
participant AI Thread


NetWork Thread->Message Thread: 收到网络信息
Message Thread->Message Thread: Paser处理信息
Message Thread->AI Thread: 解析好的信息

```

