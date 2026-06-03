# 🚨 Reduce SQL Full Table Scan

Fix dangerous full table scans in production. Improve index coverage and rewrite queries to leverage range scans.

This is a specialized variation of the **[SQL Performance Profiler](sql-optimizer.md)** tool.

## 🚀 Try It Now
Experience this tool variation with full interactive features directly on MiniMind AI:
👉 **[Run Reduce SQL Full Table Scan on MiniMind AI](https://www.minimindai.com/tools/sql-optimizer-v-full-table-scan-fix)**

---

## 🛠️ Key Capabilities
- Optimize complex JOINs and Subqueries for speed
- Generate specific CREATE INDEX recommendations
- Convert N+1 query patterns into efficient set-based logic
- Analyze execution plans to identify bottlenecks
- Rewrite queries for specific dialects (e.g., Postgres to BigQuery)

## 💡 Example Prompts
- "Why is my Postgres query doing a Seq Scan instead of Index Scan?"
- "Fix this full table scan caused by a leading wildcard in LIKE '%text'"
- "Avoid a full table scan by rewriting this OR condition into UNION ALL"
- "Suggest an index to eliminate this full scan on the users table"

---

### Base Tool
- **[SQL Performance Profiler](sql-optimizer.md)**
