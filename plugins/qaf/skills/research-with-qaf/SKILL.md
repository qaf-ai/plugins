---
name: research-with-qaf
description: Use when the user asks what classical Islamic sources say on a question, wants passages from a named scholar or book, or asks for references with page numbers.
---

# Research with Qaf

1. If the user names an author or book, resolve it with `lookup_catalog`. If several candidates match, ask which one is meant, or say which you chose and why.
2. Call `search` with an Arabic query, even when the user asks in another language: keyword matching reads Arabic text only. Search different or opposing views as separate calls, in parallel. Add filters only for what the user asked for: an author, a book, a genre or a death year.
3. Before relying on a passage, read around it with `fetch` (radius 1 or 2).
4. Answer only from the returned passages. Name the book and author for each point and link its `url`. Quote Arabic exactly as returned and label any translation as a translation.
5. If the passages don't address the question, say so. Don't fill gaps from memory, and never write out Qur’an verses or hadith that a tool did not return.
6. Qaf returns sources, not rulings. For a ruling on the user's own situation, suggest asking a qualified scholar.
