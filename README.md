# 教师健康随访服务

这是 Java 后端的基础工程，提供独立 HTTP 进程和健康检查。领域代码按医务记录、提醒与访问边界组织在 `src/main/java`，运行数据不提交到仓库。

```bash
docker build -t health-followup .
docker run --rm -p 8080:8080 health-followup
curl http://localhost:8080/health
```
