# ⚡ SQL Index Recommendation Generator

Generate high-performance indexing strategies. Identify missing indexes, fix overlapping indexes, and suggest partial indexes.

This is a specialized variation of the **[SQL Performance Profiler](sql-optimizer.md)** tool.

## 🚀 Try It Now
Experience this tool variation with full interactive features directly on MiniMind AI:
👉 **[Run SQL Index Recommendation Generator on MiniMind AI](https://www.minimindai.com/tools/sql-optimizer-v-index-generator)**

---

## 🛠️ Key Capabilities
- Identify missing and overlapping indexes in complex DDL
- Generate covering and partial index recommendations
- Analyze B-tree vs GIN index performance for specific columns
- Detect redundant indexes to reduce write overhead
- Provide specific CREATE INDEX DDL for Postgres and MySQL

## 💡 Example Prompts
- "Suggest a covering index for this high-traffic Postgres query."
- "Identify overlapping or redundant indexes in this schema."
- "Generate a partial index recommendation for active rows only."
- "Should I use a B-tree or GIN index for this JSONB column?"
- "Optimize indexing strategy for a table with 10M+ rows."

---

### Base Tool
- **[SQL Performance Profiler](sql-optimizer.md)**
