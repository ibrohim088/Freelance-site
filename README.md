```
freelance-site/
├── README.md
├── .gitignore
├── .editorconfig
├── .github/
│   └── workflows/
│       └── ci.yml
│
├── docs/
│   ├── oferta.uz.md
│   ├── oferta.ru.md
│   └── oferta.en.md
│
├── frontend/
│   ├── package.json
│   ├── vite.config.ts
│   ├── tsconfig.json
│   ├── tsconfig.node.json
│   ├── eslint.config.js
│   ├── index.html
│   ├── .env
│   ├── public/
│   │   ├── favicon.svg
│   │   └── robots.txt
│   └── src/
│       ├── main.ts
│       ├── App.vue
│       ├── env.d.ts
│       ├── assets/
│       │   ├── icons/
│       │   ├── images/
│       │   └── styles/
│       │       ├── tokens.scss
│       │       ├── base.scss
│       │       └── mixins.scss
│       ├── data/
│       │   ├── projects.ts
│       │   ├── experience.ts
│       │   └── skills.ts
│       ├── types/
│       │   ├── order.ts
│       │   └── content.ts
│       ├── api/
│       │   ├── http.ts
│       │   └── orders.ts
│       ├── composables/
│       │   ├── useTheme.ts
│       │   ├── usePhoneMask.ts
│       │   ├── useOfertaGate.ts
│       │   └── useCopyToClipboard.ts
│       ├── utils/
│       │   ├── validators.ts
│       │   └── normalizeTelegram.ts
│       ├── ui-components/
│       │   ├── BaseButton.vue
│       │   ├── BaseCard.vue
│       │   ├── BaseInput.vue
│       │   ├── BasePhoneInput.vue
│       │   ├── BaseSelect.vue
│       │   ├── BaseTextarea.vue
│       │   ├── BaseCheckbox.vue
│       │   ├── BaseDatePicker.vue
│       │   ├── BaseModal.vue
│       │   └── index.ts
│       └── components/
│           ├── layout/
│           │   ├── TheHeader.vue
│           │   ├── TheFooter.vue
│           │   └── ThemeToggle.vue
│           ├── sections/
│           │   ├── HeroSection.vue
│           │   ├── AboutSection.vue
│           │   ├── ProjectsSection.vue
│           │   ├── ExperienceSection.vue
│           │   ├── SkillsSection.vue
│           │   └── OrderSection.vue
│           ├── hero/
│           │   └── BugTicket.vue
│           └── order/
│               ├── OrderForm.vue
│               ├── OrderSteps.vue
│               ├── OrderTerms.vue
│               ├── OfertaModal.vue
│               └── OrderStatus.vue
│
└── backend/
    ├── package.json
    ├── tsconfig.json
    ├── eslint.config.js
    ├── .env
    ├── prisma/
    │   ├── schema.prisma
    │   └── migrations/
    └── src/
        ├── server.ts
        ├── app.ts
        ├── config/
        │   └── env.ts
        ├── routes/
        │   ├── index.ts
        │   ├── order.routes.ts
        │   └── health.routes.ts
        ├── controllers/
        │   └── order.controller.ts
        ├── services/
        │   ├── order.service.ts
        │   └── telegram.service.ts
        ├── validators/
        │   └── order.schema.ts
        ├── middlewares/
        │   ├── validate.ts
        │   ├── rateLimit.ts
        │   └── errorHandler.ts
        ├── lib/
        │   └── prisma.ts
        ├── utils/
        │   ├── escapeHtml.ts
        │   ├── formatOrderMessage.ts
        │   └── clientCode.ts
        └── types/
            └── order.ts
```