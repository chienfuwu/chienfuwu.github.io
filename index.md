---
title:
feature_text: |
  ## Chien-Fu Wu 吳建甫
  Special Researcher · Kyoto University
feature_image: "/assets/img/index.JPG"
---
<div style="text-align: center;">
{% include button.html text="Google Scholar" icon="googlescholar" link="https://scholar.google.com.tw/citations?user=bVZ3DOwAAAAJ&hl=zh-TW" color="#4285F4" %} {% include button.html text="ResearchGate" icon="researchgate" link="https://www.researchgate.net/profile/Chien-Fu-Wu" color="#00CCBB" %} {% include button.html text="Researchmap" icon="researchmap" link="https://researchmap.jp/chienfuwu" color="#0066CC" %} {% include button.html text="LinkedIn" icon="linkedin" link="https://www.linkedin.com/in/chienfuwu/" color="#0077B5" %} {% include button.html text="ORCID" icon="orcid" link="https://orcid.org/0000-0003-3354-9879" color="#A6CE39" %}

---
<h2>News</h2>

<table>
{% for item in site.data.news %}
<tr>
  <td style="white-space: nowrap; padding-right: 20px;"><strong>{{ item.date }}</strong></td>
  <td><a href="{{ item.link }}">{{ item.text }} {{ item.authors }}</a></td>
</tr>
{% endfor %}
</table>