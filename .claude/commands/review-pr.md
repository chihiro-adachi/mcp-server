---
allowed-tools: Bash(gh pr comment:*),Bash(gh pr diff:*),Bash(gh pr view:*)
description: プルリクエストをレビューする
---

主要な領域についてサブエージェントを使用して包括的なコードレビューを実行してください：

- code-quality-reviewer
- performance-reviewer
- test-coverage-reviewer
- documentation-accuracy-reviewer
- security-code-reviewer

それぞれに、注目に値するフィードバックのみを提供するよう指示してください。完了したら、フィードバックをレビューし、あなたも注目に値すると判断したフィードバックのみを投稿してください。

特定の問題にはインラインコメントを使用してフィードバックを提供してください。
一般的な所見や称賛にはトップレベルのコメントを使用してください。
フィードバックは簡潔に保ってください。

---
