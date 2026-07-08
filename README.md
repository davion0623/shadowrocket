# Shadowrocket Rule Sets

## AI

Rule-set URL:

```text
https://raw.githubusercontent.com/davion0623/shadowrocket/master/AI.list
```

Shadowrocket rule:

```text
RULE-SET,https://raw.githubusercontent.com/davion0623/shadowrocket/master/AI.list,PROXY
```

This rule set aggregates current AI service domains from iab0x00 ProxyRules and blackmatrix7 Shadowrocket rules, covering ChatGPT/OpenAI, Claude, Gemini, Copilot, GitHub Copilot, Apple Intelligence, Grok, OpenRouter, Perplexity, DeepSeek, Cursor, Devin/Windsurf, Mistral, Hugging Face, Poe, Midjourney, Runway, and selected common AI platforms.

## DNS Privacy

Rule-set URL:

```text
https://raw.githubusercontent.com/davion0623/shadowrocket/master/dns-privacy.list
```

Shadowrocket rules:

```text
DOMAIN-SUFFIX,dns.alidns.com,DIRECT
DOMAIN-SUFFIX,doh.pub,DIRECT
RULE-SET,https://raw.githubusercontent.com/davion0623/shadowrocket/master/dns-privacy.list,PROXY
```

This rule set captures common third-party encrypted DNS providers to reduce DNS bypass/leakage. Keep the configured domestic DoH resolvers direct before this rule set as explicit overrides.

## Foreign Airlines Direct

Rule-set URL:

```text
https://raw.githubusercontent.com/davion0623/shadowrocket/master/foreign-airlines-direct.list
```

Shadowrocket rule:

```text
RULE-SET,https://raw.githubusercontent.com/davion0623/shadowrocket/master/foreign-airlines-direct.list,DIRECT
```

This rule set focuses on foreign airline websites and app backends that are generally suitable for direct access from China, with Air France and Qatar Airways included first.

## dns

Module URL:

```text
https://raw.githubusercontent.com/davion0623/shadowrocket/master/dns.module
```
