---
layout: home
title: Ana Sayfa
---

# Yazılım Ekip Kaynak Planlama

Yazılım projelerinde ekip kaynaklarını verimli kullanmak için rehber makaleler ve pratik araçlar.

## 🎯 Site İçeriği

- **Blog Yazıları:** Ekip yönetimi, kaynak optimizasyonu
- **Demo Araç:** 4 adımda ekip kaynak planlama  
- **Rehberler:** Gerçek dünya örnekleri

[Demo'yu Deneyin](./demo) | [Blog Yazıları](./blog)

## 📋 Son Yazılar

{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%d %B %Y" }}
{% endfor %}

## 🚀 Hızlı Başlangıç

1. **Demo** sayfasını ziyaret edin
2. Ekip bilgilerinizi girin  
3. 4 adımda kaynak planınızı oluşturun
4. Sonuçları analiz edin
