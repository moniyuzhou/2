# 2
```mermaid
sequenceDiagram
    participant A as 客户端
    participant B as 服务器
    
    A->>B: 登录请求
    B-->>A: 返回Token
    A->>B: 携带Token请求数据
    B-->>A: 返回用户数据
```
