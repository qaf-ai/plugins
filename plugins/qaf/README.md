# Qaf

Qaf connects your assistant to a library of classical Arabic books from the Islamic scholarly tradition: Qur’an commentary (tafsir), hadith collections and their commentaries, jurisprudence (fiqh) across the schools, theology, history and Arabic language. Ask in English or Arabic and get passages in the original Arabic, each with its book, author, volume, page and a link to the printed page.

## Use it

Ask a question and name a scholar or book if you have one in mind. The assistant resolves the name, searches the library, reads the passages around a result, and answers only from what it found, with a citation for each point. For example:

- What do classical scholars say about combining prayers while traveling? Cite the books.
- Find what al-Nawawi wrote about intention (niyyah) in his commentary on Sahih Muslim.
- ما قول المالكية في المسح على الخفين؟ اذكر المصادر والصفحات.

Qaf returns sources, not rulings. For a ruling on your own situation, ask a qualified scholar.

## What it includes

- The Qaf MCP server at `https://api.qaf.ai/mcp`, whose tools search the library, read passages and look up authors and books. Every tool is read-only.
- The `research-with-qaf` skill, which tells the assistant how to cite passages.

## Before you connect

You need a Qaf account. The free plan works. The first time a tool runs, you sign in on qaf.ai and approve access. Each account has a weekly search allowance; reading passages and catalog lookups don't count against it.

## Data and network

The plugin contacts one host, `api.qaf.ai`, over HTTPS, using OAuth sign-in. It stores no credentials and runs no local code. Your search text goes to Qaf to find passages. See the privacy policy at https://qaf.ai/privacy and the terms at https://qaf.ai/terms. Disconnect at any time in Qaf under Settings › MCP.

## Support

https://qaf.ai/contact

## License

The plugin files are MIT-licensed (see LICENSE). The Qaf name and logo are trademarks of Qaf LLC, and the library's texts are not covered by this license.
