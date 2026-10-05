# Cybersecurity Landing

Kibertəhlükəsizlik xidmətləri üçün tək səhifəlik, asılılıqsız landing səhifəsi. Başlıq: *"Security built into every system layer"*.

## Texnologiyalar

- HTML, CSS və JavaScript (tək `index.html`, build addımı yoxdur)
- Şriftlər: Space Grotesk, JetBrains Mono (Google Fonts)

## İşə salmaq

Yalnız `index.html` faylını brauzerdə açın. İstəsəniz yerli server ilə də işlədə bilərsiniz:

```bash
python -m http.server 8000
# sonra http://localhost:8000 ünvanını açın
```

## Struktur

```
cybersecurity-landing/
├── index.html   # bütün səhifə (markup, stil, skript)
└── .gitignore
```

## Qeydlər

- Layihədə API açarı, backend və ya gizli məlumat yoxdur.
- Yerli server logları (`*.log`) `.gitignore` ilə istisna edilib.

## Lisenziya

[MIT Lisenziyası](LICENSE) © 2026 Ali Xanbabayev
