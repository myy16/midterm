# Git Commit Format Guide

## Format Template
```
<tip>: <başlık>

<detaylı açıklama (opsiyonel)>
```

---

## Commit Tipleri

| Tip | Açıklama | Örnek |
|-----|----------|-------|
| `feat` | Yeni özellik | `feat: Add Bootstrap navbar` |
| `fix` | Hata düzeltme | `fix: Fix HTML5 semantic tags` |
| `style` | CSS/tasarım | `style: Update color scheme` |
| `refactor` | Kod yeniden yapılandırma | `refactor: Clean HTML structure` |
| `docs` | Dokümantasyon | `docs: Add comments to CSS` |

---

## Projemiz İçin Commit Örnekleri

### Commit 1 (Part 1 - Tamamlandı)
```
feat: Integrate Bootstrap 5 and fix HTML5 structure

- Add viewport meta tag for responsive design
- Add lang attribute for accessibility
- Convert header to proper Bootstrap navbar
- Add Contact Us link in navbar
- Wrap content in semantic main tag
```

### Commit 2 (Part 2 - Yapılacak)
```
feat: Add Bootstrap grid and team cards

- Convert team members to Bootstrap cards
- Implement responsive grid (col-md-6, col-lg-4)
- Add placeholder images
- Add social media icons
```

### Commit 3 (Part 3 - Yapılacak)
```
style: Add custom styling and footer

- Change color scheme using Bootstrap utilities
- Add footer with copyright
- Ensure consistent spacing throughout
```

---

## Kurallar
- Başlık maksimum 50 karakter
- Başlık İngilizce yazılmalı
- Detaylı açıklamada bullet points kullanılmalı
- Her commit bağımsız ve anlaşılır olmalı
