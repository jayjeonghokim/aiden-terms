---
layout: terms
title: 현재 약관
version: "1.0.0"
effective_date: 2026-01-01
---

# AIDEN 서비스 이용약관

최신 버전의 약관을 확인하세요.

---

## 📋 모든 버전

{% for term in site.terms reversed %}
- **[v{{ term.version }}]({{ site.baseurl }}{{ term.url }})** - 시행일: {{ term.effective_date }}
{% endfor %}

---

[변경 이력 보기 →]({{ site.baseurl }}/changelog)
