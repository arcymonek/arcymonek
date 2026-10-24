### 👋 Hi, I'm Arkadiusz Polak (@arcymonek)

I'm not a professional programmer, but I'm passionate about digital sovereignty.\
In an era dominated by big cloud providers, I believe building your own infrastructure is the best way to regain control over your data and privacy.

🛠️ **What I do**\
I run a self-hosted homelab (VPS, Debian, Docker, nginx and my own services) and learn by building it.\
I treat modern language models as learning partners: they help a lot, but the result is also dozens of hours of reading documentation and many mistakes, some of them really silly :)

- **Self-hosting:** my own services, from media to work tools.
- **AI & RAG:** experimenting with local and cloud models to boost personal productivity.
- **Security:** system hardening, monitoring, automation, backups.
- **Open source:** I use it wherever I can, and out of gratitude I encourage others to do the same. 💞️

💡 I'm not looking for the quickest route; I'm looking for a full understanding of what I build.\
Every problem solved is another step toward independence.

---

### 🎯 My projects
### [Seisa](https://github.com/arcymonek/seisa)
A local tool for checking whether an IP address, a link or a suspicious e-mail can be trusted, explained in plain language for people who are not security professionals.
The goal is simple: facts come from code, not from a language model.

- IP reputation, URL scans, DMARC reports, e-mail source analysis and AbuseIPDB reports in one place
- Runs only on your own computer (127.0.0.1), no accounts, no server
- Security facts (sender IP, SPF/DKIM/DMARC, report eligibility) are derived deterministically; the optional LLM only explains and double-checks, and sees nothing until you click "Analyze"
- Python (FastAPI) and plain JavaScript without a framework, with unit tests, an end-to-end harness and CI
- Interface and documentation in English and Polish
- Open source (GPL-3.0-or-later),
- Built in collaboration with Claude Code (Anthropic)\
  I am not a professional programmer, so the project leans on tests and documentation


**[reportabuseipdb](https://github.com/arcymonek/reportabuseipdb)**\
Automated, policy-compliant reporting of attackers detected by your own [CrowdSec](https://www.crowdsec.net/) instance
to [AbuseIPDB](https://www.abuseipdb.com/).\
The goal is simple: never report anything that is not a real, locally observed attack.
- Python (standard library only) and Bash, with an extensive test suite
- Documentation in English and Polish
- Running in production on my own server
- Built in collaboration with Claude Code (Anthropic)\
  I am not a professional programmer, so the project leans on tests and documentation
