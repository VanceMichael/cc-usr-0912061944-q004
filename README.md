# 成长陪伴记录服务

这是 Java 后端的基础工程，提供 Spring Boot 进程和健康检查。儿童档案、陪伴记录与交接边界的领域代码放在 `src/main/java`，运行数据不提交到仓库。

```bash
docker build -t growth-companion .
docker run --rm -p 8080:8080 growth-companion
curl http://localhost:8080/health
```
