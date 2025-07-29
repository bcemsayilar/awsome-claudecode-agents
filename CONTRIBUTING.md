# 🤝 Katkıda Bulunma Rehberi

Awesome Claude Code Agents projesine katkıda bulunmak istediğiniz için teşekkürler! Bu rehber, nasıl etkili bir şekilde katkıda bulunabileceğinizi açıklar.

## 🎯 Katkı Türleri

### 1. 🆕 Yeni Agent Oluşturma

**En çok ihtiyaç duyulan agent türleri:**
- Blockchain/Web3 Development
- Game Development (Unity, Unreal)
- E-commerce Development
- Content Management Systems
- API Integration Specialists
- Database Design Experts

### 2. 🔧 Mevcut Agent'ları İyileştirme

- Agent açıklamalarını genişletme
- Yeni teknolojiler ekleme
- Örnek kullanım senaryoları ekleme
- Performance iyileştirmeleri

### 3. 📚 Dokümantasyon

- Türkçe çeviriler
- Örnek projeler
- Video tutorials
- Blog yazıları

### 4. 🐛 Bug Reports ve Öneriler

- Agent'larda karşılaştığınız sorunlar
- Yeni özellik önerileri
- Kullanıcı deneyimi iyileştirmeleri

## 📝 Agent Oluşturma Rehberi

### 1. Agent Template Kullanın

Her yeni agent için [AGENT_TEMPLATE.md](AGENT_TEMPLATE.md) dosyasını temel alın:

```markdown
---
name: "agent-name"
description: "Kısa açıklama"
color: "renk"
tags: ["tag1", "tag2", "tag3"]
author: "Your Name"
version: "1.0"
---

# Agent Name

Detaylı açıklama...

## Uzmanlık Alanları
- Alan 1
- Alan 2
- Alan 3

## Teknolojiler
- Tech 1
- Tech 2

## Yaklaşım
Agent'ın çalışma yaklaşımı...
```

### 2. Klasörleme Kuralları

```
agents/
├── engineering/        # Yazılım geliştirme
├── product/           # Ürün yönetimi
├── marketing/         # Pazarlama ve sosyal medya
├── design/           # Tasarım ve UX
├── data-science/     # Veri bilimi ve ML
├── security/         # Güvenlik
├── testing/          # Test ve QA
├── devops/          # DevOps ve infrastructure
├── project-management/ # Proje yönetimi
└── studio-operations/ # Studio operasyonları
```

### 3. Kalite Standartları

**✅ İyi bir agent şunları içerir:**
- Açık ve anlaşılır açıklama
- Belirli teknolojiler ve araçlar
- Gerçekçi uzmanlık alanları
- Pratik yaklaşım metodları
- Kullanım örnekleri

**❌ Kaçınılması gerekenler:**
- Çok genel açıklamalar
- Gerçekçi olmayan yetenekler
- Belirsiz teknoloji listeleri
- Kopyala-yapıştır içerik

## 🚀 Katkı Süreci

### 1. Development Setup

```bash
# Repo'yu fork edin ve clone edin
git clone https://github.com/yourusername/awsome-claudecode-agents.git
cd awsome-claudecode-agents

# Development branch oluşturun
git checkout -b feature/your-agent-name
```

### 2. Agent Geliştirme

```bash
# Uygun kategoride agent dosyası oluşturun
touch agents/engineering/your-agent.md

# Agent'ı geliştirin ve test edin
# Claude Code ile test edin:
claude-code agents/engineering/your-agent.md
```

### 3. Pull Request Süreci

```bash
# Değişiklikleri commit edin
git add .
git commit -m "feat: Add [Agent Name] for [Technology/Domain]

- Added comprehensive [technology] expertise
- Included practical examples and use cases
- Tested with real-world scenarios"

# Branch'i push edin
git push origin feature/your-agent-name
```

### 4. PR Template

Pull request oluştururken şu template'i kullanın:

```markdown
## 📝 Agent Açıklaması
**Agent Adı:** [Agent Name]
**Kategori:** [engineering/product/marketing/etc.]
**Teknolojiler:** [Ana teknolojiler]

## 🎯 Neler Eklenip/Değiştirildi
- [ ] Yeni agent oluşturuldu
- [ ] Mevcut agent güncellenip
- [ ] Dokümantasyon eklendi
- [ ] Örnek kullanımlar eklendi

## ✅ Test Checklist
- [ ] Claude Code ile test edildi
- [ ] Gerçek senaryolarda kullanıldı
- [ ] Dokümantasyon kontrol edildi
- [ ] Template standardına uygun

## 📚 Ek Bilgiler
[Agent hakkında ek açıklamalar, kullanım önerileri vb.]
```

## 🌟 Agent Kalite Kriterleri

### ⭐⭐⭐⭐⭐ Mükemmel Agent
- Detaylı uzmanlık alanları
- Kapsamlı teknoloji listesi
- Pratik yaklaşım metodları
- Gerçek kullanım örnekleri
- Test edilmiş ve onaylanmış

### ⭐⭐⭐⭐ İyi Agent
- Net uzmanlık alanları
- Belirli teknolojiler
- Açık yaklaşım
- Temel örnekler

### ⭐⭐⭐ Orta Agent
- Genel uzmanlık
- Sınırlı teknoloji listesi
- Basit açıklama

## 🏆 Özel Katkı Programları

### 🥇 Agent Champion Program
**En aktif contributors için özel rozet ve recognition**

### 🚀 Startup Agent Program
**Startup'lar için özel agent'lar geliştiren contributors**

### 🎓 Educational Agent Program
**Eğitim odaklı agent'lar için özel program**

## 📋 İnceleme Süreci

### 1. Otomatik Kontroller
- Markdown syntax kontrolü
- Template uyumluluk kontrolü
- Dosya yapısı kontrolü

### 2. Topluluk İncelemesi
- Minimum 2 community member onayı
- Teknoloji expert review (eğer gerekirse)
- Test sonuçları değerlendirmesi

### 3. Maintainer Onayı
- Final quality check
- Repository standartlarına uygunluk
- Merge ve deployment

## 🤔 Sık Sorulan Sorular

### Q: Agent'ımın hangi kategoriye girmesi gerektiğinden emin değilim?
A: GitHub issues'da soru açın, community size yardım edecektir.

### Q: Agent'ımı nasıl test edebilirim?
A: Claude Code ile gerçek projelerinizde test edin ve sonuçları paylaşın.

### Q: Katkımın kabul edilme süresi ne kadar?
A: Genellikle 3-7 gün içinde incelenir ve geri dönüş yapılır.

### Q: Türkçe bilmiyorum, yine de katkıda bulunabilir miyim?
A: Elbette! İngilizce agent'lar da kabul edilir, community Türkçeye çevirir.

## 📞 İletişim

**Sorularınız için:**
- GitHub Issues kullanın
- Discord: [Claude C](https://discord.gg/claude-code-tr)
- Email: me@cemsayilar.com

## 🙏 Teşekkürler

Her türlü katkınız değerlidir ve Türk developer topluluğunun gelişimine katkıda bulunur!

---"