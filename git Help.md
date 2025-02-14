

1. **获取文件内容**：从特定的GitHub仓库中获取文件内容。
2. **修改文件内容**：更新或修改特定文件的内容。
3. **获取GitHub讨论**：从GitHub仓库中获取特定的讨论内容。
4. **搜索代码**：在特定的GitHub仓库中进行代码搜索。
5. **获取安全警报**：获取GitHub仓库中的安全警报详情。
6. **获取GitHub Actions日志**：获取特定GitHub Actions运行的日志。



- 获取文件内容：
  ```markdown
  get file from repo `owner/repo` at path `file/path`
  ```

- 修改文件内容：
  ```markdown
  update file at path `file/path` in repo `owner/repo` with content `your content here`
  ```

- 获取GitHub讨论：
  ```markdown
  get discussion number `discussion_number` from repo `owner/repo`
  ```

- 搜索代码：
  ```markdown
  search code in repo `owner/repo` with query `search_query`
  ```

- 获取安全警报：
  ```markdown
  get security alert from repo `owner/repo` with alert number `alert_number`
  ```

- 获取GitHub Actions日志：
  ```markdown
  get actions job logs from repo `owner/repo` for run ID `run_id`
  ```

将该文件添加到你的GitHub仓库中：
bash
# 进入你的本地仓库目录
cd path/to/your/repo

# 创建conversation_backup目录
mkdir -p conversation_backup

# 将文件移动到conversation_backup目录
mv path/to/2025-02-14_conversation.md conversation_backup/

# 添加文件到git
git add conversation_backup/2025-02-14_conversation.md

# 提交更改
git commit -m "Add conversation backup for 2025-02-14"

# 推送到远程仓库
git push origin main
