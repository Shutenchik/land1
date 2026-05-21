# UPSTARS — Senior Frontend Developer (Vue / SSR / SEO focus)

## Підготовка до технічного інтерв'ю (90 хвилин)

---

## НАВІГАЦІЯ ПО БЛОКАХ ІНТЕРВ'Ю

### Блок 1 (0-10 хв): Знайомство і досвід
- Розкажіть про себе → рядок 319
- Чому ця роль / UPSTARS → рядок 336
- Чому підходите на Vue/SSR/SEO → рядок 348
- Ownership → рядок 1330
- Без дизайнера/PM → рядок 1336
- Керування командою → рядок 1354
- Що значить senior → рядок 1438
- Product-minded → рядок 1422

### Блок 2 (10-25 хв): Vue / Nuxt / TypeScript
- Composition vs Options API → рядок 1482
- Структура composables → рядок 1500
- Composable vs Pinia → рядок 1520
- Pinia в SSR → рядок 1536
- SSR-safe код → рядок 1556
- Lifecycle hooks сервер/клієнт → рядок 1581
- useAsyncData vs useFetch → рядок 1603
- useFetch vs $fetch → рядок 1446
- Route middleware → рядок 1625
- Plugins → рядок 1645
- ClientOnly → рядок 1665
- Error boundaries → рядок 1687
- Suspense / Teleport → рядок 1705
- shallowRef → рядок 1458
- Тяжкі списки → рядок 1468
- Nuxt Layers → рядок 2774 (секція Vue додаткові)
- Nitro → рядок 2774 (секція Vue додаткові)
- TypeScript strict → рядок 1727
- Generics → рядок 1739
- unknown vs any → рядок 1751
- type vs interface → рядок 1767
- API типізація / DTO → рядок 1782
- Discriminated unions → рядок 1798
- Runtime validation → рядок 1830

### Блок 3 (25-45 хв): SSR / Rendering / Hydration — ЯДРО
- SSR vs SSG vs SPA → рядок 390
- Стратегія для iGaming дзеркал → рядок 449
- Hydration mismatch → рядок 409
- Дебаг hydration → рядок 429
- SSR мікросервіс для 5 доменів → рядок 1049 (Блок 3 симуляції)
- Кешування SSR → рядок 641
- Cache-Control заголовки → рядок 2007
- Event loop і SSR → рядок 1987
- Express middleware → рядок 1969

### Блок 4 (45-60 хв): SEO + Multi-domain
- Canonical / hreflang для 5+ доменів → рядок 467
- Duplicate content → рядок 483
- Mirror domains навіщо → рядок 2049
- Sitemap для 5+ доменів → рядок 1848
- Noindex → рядок 1872
- Structured data → рядок 1896
- Crawling vs indexing → рядок 1919
- SEO-регресія після деплою → рядок 687
- Код-рев'ю з SEO-фокусом → рядок 669

### Блок 5 (60-72 хв): Core Web Vitals + Monitoring
- LCP діагностика → рядок 499
- INP діагностика → рядок 528
- CLS → рядок 556
- CrUX + Lighthouse + Sentry разом → рядок 581
- Monitoring і alerting → рядок 606
- Sentry в роботі → рядок 1931
- Production incident → рядок 1949

### Блок 6 (72-80 хв): Behavioral / Leadership
- Конфлікт з backend → рядок 2165
- Нечіткі вимоги + дедлайн → рядок 747
- Швидкість vs надійність → рядок 769
- Overengineering → рядок 787
- KYC під legal deadline → рядок 729
- Production bug → рядок 2195
- Менторинг → рядок 2177

### Блок 7 (80-90 хв): Мої питання до UPSTARS
- 5 питань → рядок 805

### Швидкі довідники
- Vue/Nuxt SSR Cheat Sheet → рядок 817
- SEO Cheat Sheet → рядок 846
- Core Web Vitals Cheat Sheet → рядок 862
- Monitoring Cheat Sheet → рядок 897
- iGaming Cheat Sheet → рядок 928
- Gaps / Bridge Answers → рядок 977
- 10 найсильніших фраз → рядок 1213
- 5 STAR-історій → рядок 1239
- JS Core питання → рядок 2740
- Vue/Nuxt додаткові питання → рядок 2774

---

## 1. Стратегія інтерв'ю

### Що компанія найімовірніше перевіряє:

1. **SSR/SSG архітектура** — чи зможу спроектувати та підтримувати SSR-мікросервіс для 5+ доменів
2. **Технічне SEO** — canonical, hreflang, індексація, вплив рендерингу на crawling
3. **Core Web Vitals** — діагностика регресій, фікси, CrUX моніторинг
4. **Production reliability** — моніторинг, алертинг, інцидент-менеджмент
5. **iGaming domain knowledge** — мультидомени, дзеркала, гео-обмеження, legal compliance
6. **Senior ownership** — код-рев'ю, стандарти, декомпозиція, комунікація з product

### Мої найсильніші точки відповідності:

- **5 років у iGaming** (NetGame Entertainment) — high-load B2C, SSR, WebSockets, Sentry
- **Shared cashier module** для кількох iGaming проєктів — прямий аналог multi-domain архітектури
- **SEO стратегія з нуля** (WPT Technology) — SSR meta, structured data, sitemap, CWV, 15-20 органічних реєстрацій/день
- **KYC/AML інтеграції** (Sumsub, Diia, KYCAID) — регульовані потоки під legal deadlines
- **Міграція Vue 2 → Vue 3/Nuxt 3** — архітектура, composables, shared бібліотека
- **Team Lead досвід** — 4 frontend інженери, PR standards, sprint planning, hiring
- **Sentry як daily practice** — тріаж, пріоритизація, root-cause analysis

### Можливі gaps / зони ризику:

- Prometheus/Grafana — не налаштовувала дашборди з нуля
- Streaming SSR — теоретичне розуміння, не будувала в продакшні
- Redis/PostgreSQL — непрямий досвід через backend колег
- Kubernetes/ArgoCD — знаю концепти деплою, не адмініструвала
- CDN edge caching — працювала з Cache-Control, але не будувала стратегію інвалідації

### Позиціонування в перші 3-5 хвилин:

"Я Senior Frontend Engineer з 8+ років досвіду, з яких 5 — в iGaming. Будувала shared cashier module для кількох iGaming проєктів одночасно, робила міграцію на Vue 3/Nuxt 3 з SSR, з нуля побудувала SEO-стратегію що дала 15-20 органічних реєстрацій/день. Мій останній рік — це product ownership, де я самостійно керувала архітектурними рішеннями, SEO і Core Web Vitals. Плюс — досвід KYC під legal deadlines і керування командою з 4 фронтенд-інженерів."

### 5 тем для повторення протягом інтерв'ю:

1. **"Я вже працювала з мультипроєктною iGaming архітектурою"** — shared cashier, multiple brands
2. **"SEO для мене — не теорія, а бізнес-метрика"** — 15-20 реєстрацій/день через органіку
3. **"Production reliability — мій daily workflow"** — Sentry тріаж, CWV моніторинг
4. **"Я вмію працювати під regulatory pressure"** — KYC, legal deadlines, compliance gates
5. **"Я беру ownership, а не чекаю тікет"** — product thinking, end-to-end delivery

---

## 2. Карта інтерв'ю на 90 хвилин

| Блок                         | Час      | Що перевіряють                                     |
| ---------------------------- | -------- | -------------------------------------------------- |
| Intro + досвід               | 10-12 хв | Seniority, ownership, domain fit                   |
| Vue/Nuxt/TypeScript          | 12-15 хв | Глибина Composition API, SSR-safe код, архітектура |
| SSR/SSG/Hydration            | 15-18 хв | Стратегії рендерингу, hydration mismatch, caching  |
| SEO + Multi-domain           | 12-15 хв | canonical, hreflang, дзеркала, індексація          |
| Core Web Vitals              | 10-12 хв | Діагностика LCP/INP/CLS, моніторинг                |
| Monitoring/Incidents         | 8-10 хв  | Sentry, Lighthouse, Prometheus, alerting           |
| Node.js/Middleware           | 5-8 хв   | Express, event loop, caching headers               |
| System Design / Architecture | 10-12 хв | Проектування SSR-сервісу, кешування, multi-brand   |
| Behavioral / Leadership      | 5-8 хв   | Конфлікти, deadlines, трейдоффи                    |
| Мої питання                  | 5 хв     | Зрілість, культура, tech stack                     |

---

## 3. Банк питань за пріоритетом

### A. Intro / Досвід / Seniority

1. Розкажіть про себе і свій досвід.
2. Чому ця роль? Чому UPSTARS?
3. Чому iGaming?
4. Найбільший приклад ownership на фронтенді?
5. Як ви працюєте без дизайнера/PM?
6. Розкажіть про керування командою з 4 фронтенд-інженерів.
7. Як ви вирішуєте неоднозначності в задачах?
8. Ваші стандарти код-рев'ю?
9. Як комунікуєте з product/backend/QA?
10. Що для вас значить "product-minded engineer"?

### B. Vue 3 / Composition API / Nuxt 3

1. Чим Composition API кращий за Options API для великих проєктів?
2. Як ви структуруєте composables? Коли виносити логіку?
3. Як працює Pinia в SSR-контексті? Як уникнути shared state між запитами?
4. Що таке SSR-safe код? Які помилки виникають при порушенні?
5. Які lifecycle hooks працюють на сервері, а які — ні?
6. useAsyncData vs useFetch — коли що використовувати?
7. Як працюють route middleware в Nuxt 3? Server vs client middleware?
8. Як працюють plugins в Nuxt 3? Порядок виконання?
9. Як правильно робити dynamic imports в Nuxt?
10. Що таке hydration mismatch? Як діагностувати?
11. Коли використовувати `<ClientOnly>`?
12. Як серіалізується стан між сервером і клієнтом?
13. Error boundaries в Nuxt — як обробляти помилки?
14. Як уникнути over-engineering в component architecture?

### C. TypeScript

1. Чому strict mode важливий? Які опції ввімкнені?
2. Як використовуєте generics у composables?
3. Type guards — коли і навіщо?
4. unknown vs any — чому unknown кращий?
5. Як типізуєте API-відповіді?
6. Discriminated unions — приклад використання?
7. Як типізуєте Pinia stores?
8. DTO vs UI models — навіщо розділяти?
9. Runtime validation vs TypeScript types — як поєднуєте?

### D. SSR / SSG / Rendering Strategy

1. SSR vs SSG vs SPA vs ISR — коли що використовувати?
2. Коли SSR НЕ потрібен? Які сторінки краще залишити SPA?
3. Як обираєте стратегію рендерингу для iGaming: SEO-сторінки vs кабінет/каса?
4. Що таке hydration? Чому вона дорога?
5. Основні причини hydration mismatch?
6. Streaming SSR — що це, коли корисно?
7. Server cache для SSR — стратегії?
8. CDN cache + stale-while-revalidate — як працює?
9. Інвалідація кешу — підходи?
10. Multi-domain rendering — як обслуговувати 5+ доменів з одного SSR-сервісу?
11. Geo-specific контент — як рендерити різний контент для різних країн?
12. Canonical і hreflang implications для mirror domains?
13. Як спроектувати SSR microservice architecture?

### E. Технічне SEO

1. Canonical — навіщо, як ставити, типові помилки?
2. Hreflang — формат, помилки, self-referencing?
3. Sitemap — як генерувати динамічно для 5+ доменів?
4. Robots.txt — стратегія для mirror domains?
5. Noindex — коли використовувати?
6. Schema.org / structured data — які типи для iGaming?
7. Open Graph — динамічні meta для різних сторінок?
8. Server response codes — 301 vs 302, 404 vs 410?
9. Crawling vs indexing — в чому різниця?
10. Duplicate content across mirrors — як боротися?
11. SSR impact on indexing — чому SSR важливий для SEO?
12. JS-rendered content ризики?
13. i18n SEO — як правильно?
14. SEO регресії після деплою — як ловити?

### F. Core Web Vitals / Performance

1. LCP — що вимірює, типові причини погіршення, як фіксити?
2. INP — що вимірює, як діагностувати?
3. CLS — причини, як фіксити?
4. CrUX vs Lighthouse — різниця?
5. Lab data vs field data — що важливіше?
6. Як діагностуєте регресію performance?
7. Image optimization — стратегія?
8. Font loading — як впливає на CWV?
9. Critical CSS — підходи?
10. Code splitting в Nuxt — як налаштовуєте?
11. Third-party scripts (GTM, analytics) — як мінімізувати вплив?
12. Performance budget — як визначаєте?
13. Performance monitoring dashboard — що показуєте?

### G. Monitoring / Observability / Incidents

1. Як використовуєте Sentry? Source maps, releases, environments?
2. Error grouping — як налаштовуєте?
3. Як пріоритизуєте помилки — за affected users чи frequency?
4. Prometheus/Grafana — які метрики для frontend?
5. Alerting — на що ставите алерти?
6. Lighthouse CI — як інтегруєте в CI/CD?
7. CrUX tracking — як відстежуєте динаміку?
8. Incident response — ваш процес?
9. Root cause analysis — як проводите?

### H. Node.js / Backend-for-Frontend / SSR Service

1. Express middleware — порядок, error handling?
2. Event loop — як впливає на SSR performance?
3. Caching headers — Cache-Control, ETag, стратегії?
4. Server-side redirects — як реалізуєте?
5. SSR service health checks — що перевіряєте?
6. Memory leaks на сервері — як виявляєте?
7. Request ID / logging — навіщо?

### I. iGaming Domain

1. Специфіка high-load B2C iGaming продукту?
2. Cashier/payment flows — складності?
3. KYC/AML — frontend інтеграція?
4. Geo restrictions — як реалізуєте?
5. Mirror domains — навіщо потрібні в iGaming?
6. SEO ризики для gambling products?
7. Feature flags в iGaming?
8. Responsible gaming — frontend реалізація?
9. Security-sensitive flows на фронтенді?

### J. Testing / CI/CD

1. Як тестуєте composables?
2. Як тестуєте SSR-сторінки?
3. Як тестуєте SEO metadata?
4. Regression testing — підхід?
5. CI/CD pipeline — які етапи?
6. Rollback strategy — як відкочуєте?

### K. Architecture / System Design

1. Спроектуйте SSR/SSG мікросервіс для 5+ доменів.
2. Спроектуйте SEO-safe архітектуру для blog/landing в Nuxt.
3. Спроектуйте caching strategy для geo-specific pages.
4. Спроектуйте monitoring dashboard для performance і SEO.
5. Спроектуйте shared module для кількох iGaming брендів.
6. Спроектуйте код-рев'ю чекліст для SEO/performance-sensitive продукту.

### L. Behavioral / Leadership

1. Конфлікт з backend/product — як вирішували?
2. Нечіткі вимоги — ваш підхід?
3. Стислі дедлайни — приклад?
4. Менторинг — як проводите?
5. Як кажете "ні" поганій архітектурі?
6. Production bug — ваш процес реакції?
7. Як комунікуєте ризики нетехнічним стейкхолдерам?

---

## 4. Модельні відповіді

### 1. Розкажіть про себе

**Відповідь (60-90 сек):**

"Я Наталія, Senior Frontend Engineer, працюю комерційно з 2017 року. Основний стек — Vue 3, Nuxt 3, TypeScript. П'ять років працювала в iGaming — NetGame Entertainment, high-load B2C платформи на українському та американському ринках. Там побудувала shared cashier module для кількох проєктів одночасно, інтегрувала KYC/AML SDK, працювала з SSR, WebSockets, Sentry.

Потім була Team Lead в Prematch — ще один iGaming продукт, де керувала командою з 4 фронтенд-інженерів, впроваджувала PR стандарти і зробила KYC flow під legal deadline з зміною законодавства.

Останній рік — FinTech продукт, де я єдиний фронтенд і product voice: побудувала SEO-стратегію з нуля що дала 15-20 органічних реєстрацій/день, переробила ключові продуктові потоки end-to-end.

Ця вакансія — це комбінація мого iGaming domain knowledge, SSR/SEO досвіду і production reliability підходу."

**English version (if asked):**
"I'm Nataliia, Senior Frontend Engineer with 8+ years of experience. Five years in iGaming at NetGame — built shared cashier modules, SSR, KYC integrations. Then Team Lead at Prematch — 4 engineers, regulatory KYC under legal deadlines. Last year — full product ownership at a FinTech with SEO strategy delivering 15-20 organic sign-ups/day. This role combines my iGaming domain expertise, SSR/SEO delivery, and production reliability mindset."

---

### 2. Чому ця роль / Чому UPSTARS?

**Відповідь:**

"Три причини. Перша — це точне поєднання мого досвіду: iGaming, SSR, SEO, multi-domain. Я не просто Vue-розробник — я працювала саме з цією комбінацією технологій і домену.

Друга — масштаб задач. Побудова SSR-мікросервісу для 5+ доменів — це архітектурний виклик, який мене мотивує. Я вже будувала shared модулі для кількох проєктів, і хочу це масштабувати.

Третя — UPSTARS як продуктова компанія з B2B-ліцензією. Легальний ринок означає довгострокові технічні рішення, а не 'зробив і забув'. Мені це підходить — я product-minded інженер."

---

### 3. Чому ви підходите на Vue / SSR / SEO роль?

**Відповідь:**

"Я не теоретизую про SSR і SEO — я це робила в продакшні і бачила бізнес-результат.

SSR: мігрувала платформу з Vue 2 на Nuxt 3 з SSR, запустила проєкт за 1.5 місяці від архітектури до production.

SEO: побудувала органічний канал з нуля — meta, structured data, sitemap, Core Web Vitals — 15-20 реєстрацій/день без paid.

Multi-domain: будувала shared cashier для кількох iGaming брендів з per-project overrides — це прямий аналог мережі дзеркал.

Performance: Sentry як daily practice — тріаж помилок по affected users, root-cause analysis, hotfixes.

Плюс регуляторний контекст — KYC під legal deadlines, де не можна шіпнути з known gaps."

---

### Що відбувається коли ви вводите URL в браузер?

**Питання:** "Ви ввели в Google пошук URL і натиснули Enter. Що відбувається далі поетапно?"

**Відповідь:**

"Спочатку браузер шукає IP-адресу домену — DNS. Перевіряє свій кеш, кеш системи, якщо немає — питає у DNS-сервера провайдера.

Далі встановлює TCP-з'єднання з сервером і TLS для шифрування. Це кілька раундтріпів по мережі.

Потім відправляє HTTP-запит із заголовками — Host, cookies, User-Agent. Якщо це SSR-додаток — саме Host визначає що рендерити.

Сервер обробляє запит. Або віддає з кешу, або рендерить HTML. Повертає відповідь із заголовками кешування. CDN може перехопити і віддавати далі без звернення до сервера.

Браузер отримав HTML і починає розбирати зверху вниз. CSS блокує малювання — поки стилі не завантажились, нічого не з'явиться. Скрипт без defer блокує парсинг — браузер зупиняється і чекає. Тому критичні стилі краще інлайнити, скрипти — defer або async.

Коли DOM і стилі готові — браузер рахує де що стоїть і малює пікселі. Перший контент на екрані — FCP. Найбільший видимий елемент — LCP.

Далі завантажується JavaScript. Якщо це SSR — запускається hydration: фреймворк підключає інтерактивність до вже існуючого HTML. Не перемальовує, а оживляє — навішує обробники подій, реактивність. Після цього сторінка повністю інтерактивна.

Мені це важливо розуміти на практиці, бо коли є проблема з швидкістю — я проходжу цей ланцюжок і шукаю де саме затримка. DNS — prefetch. З'єднання — preconnect. Сервер — кеш. HTML — streaming. CSS — інлайн критичних. JS — code splitting і defer."

---

### 4. SSR vs SSG vs SPA — коли що?

**Відповідь:**

"Вибір стратегії залежить від двох осей: чи потрібен SEO і як часто змінюється контент.

**SSR** — для сторінок, які повинні індексуватися І мають динамічний контент. В iGaming це: landing pages з гео-специфічним контентом, сторінки ігор з live RTP, промо-сторінки. Перший рендер — з сервера, пошуковий бот бачить повний HTML.

**SSG** — для контенту, який змінюється рідко: блог, правила, legal pages, FAQ. Генеруємо на build time, кешуємо на CDN, працює миттєво.

**SPA (client-only)** — для authenticated зон: кабінет гравця, каса, KYC flow, історія ставок. Тут SEO не потрібен, але потрібна інтерактивність і real-time оновлення через WebSockets.

**Трейдофф:** SSR коштує серверних ресурсів і додає latency. Тому для iGaming з 5+ дзеркалами потрібен aggressive caching — stale-while-revalidate на CDN, server-side cache з invalidation по тригерах."

**English version:**
"SSR for SEO + dynamic pages (landings, game pages). SSG for rarely changing content (blog, legal). SPA for authenticated areas (cashier, KYC, player cabinet). In iGaming with 5+ mirrors, SSR needs aggressive caching — CDN with stale-while-revalidate and server cache with event-driven invalidation."

---

### 5. Що спричиняє hydration mismatch?

**Відповідь:**

"Hydration mismatch — це коли HTML з сервера не збігається з тим, що Vue рендерить на клієнті. П'ять основних причин:

1. **Date/time** — `new Date()` дає різний результат на сервері та клієнті. Рішення: використовувати UTC або передавати timestamp з сервера.

2. **Browser-only APIs** — `window`, `localStorage`, `navigator`. На сервері їх немає. Рішення: guard checks або `<ClientOnly>`.

3. **Random values** — Math.random(), UUID генерація. Рішення: seed з сервера або генерувати тільки на клієнті.

4. **Conditional rendering по user state** — якщо показуємо різний UI для auth/non-auth, а стан ще не синхронізований. Рішення: useAsyncData або lazy hydration.

5. **Third-party scripts** — GTM, analytics інжектять DOM до hydration. Рішення: defer, nextTick, або client-only wrapper.

В моєму досвіді найчастіша причина — це Date/time і localStorage доступ в computed properties. Фікс — завжди думати: 'чи цей код безпечний на сервері?'"

---

### 6. Як дебажити hydration mismatch в Nuxt?

**Відповідь:**

"Мій процес:

1. **Dev mode** — Nuxt показує warning в консолі з двома рядками: server HTML vs client HTML. Зазвичай цього достатньо щоб зрозуміти яка нода не збігається.

2. **Локалізація** — дивлюся на компонент, обертаю підозрілу частину в `<ClientOnly>` щоб підтвердити гіпотезу. Якщо warning зникає — причина знайдена.

3. **Перевірка data flow** — часто проблема не в рендері, а в тому що стан на сервері та клієнті ініціалізується по-різному. Перевіряю useAsyncData, Pinia hydration.

4. **Network tab** — порівнюю HTML з response з тим що Vue пробує hydrate.

5. **Production** — в production Vue не показує warnings, тому важливо ловити на CI. Можна додати e2e тест який перевіряє що сторінка рендериться без JS-помилок.

Ключове правило: в SSR кожен composable і computed має бути deterministic — однаковий результат на сервері та клієнті з однаковими inputs."

---

### 7. Як обрати стратегію рендерингу для iGaming дзеркал?

**Відповідь:**

"Я б розділив сторінки на три зони:

**Зона 1: SSR + CDN cache** — landing pages, сторінки ігор, промо, категорії. Це SEO-критичні сторінки. SSR з aggressive caching: CDN edge cache 5-15 хв, stale-while-revalidate, invalidation через webhook коли контент змінюється.

**Зона 2: SSG** — legal pages, T&C, about, responsible gaming, blog. Рідко змінюються, генеруємо на етапі білда і кешуємо надовго. Якщо контент оновився — перегенеровуємо тільки ту сторінку яка змінилась, а не весь сайт.

**Зона 3: SPA (client-only)** — кабінет гравця, каса, KYC, бонуси, ставки, live ігри. Тут SSR не потрібен (authenticated контент, SEO не релевантне) і навіть шкідливий (sensitive data в HTML response).

Для кількох доменів — один SSR-сервіс обслуговує всі дзеркала. Сервер дивиться з якого домену прийшов запит і підтягує відповідний конфіг: мова, валюта, які провайдери доступні, яке лого. Код і компоненти спільні, а дані і налаштування — різні для кожного домену.

Трейдофф: більше доменів = більше cache keys. Потрібна стратегія cache warming і моніторинг cache hit ratio."

---

### 8. Як реалізувати canonical/hreflang для 5+ доменів?

**Відповідь:**

"Якщо є п'ять доменів і на них схожий контент — Google за замовчуванням вирішить що це дублікати і почне прибирати зайві з пошуку. Canonical і hreflang — це спосіб пояснити Google що кожен домен самостійний і для свого ринку.

Canonical — кожен домен каже про себе: 'моя правильна адреса — ось ця'. domain-ua.com/slots вказує на себе ж. Не на якийсь спільний головний домен — бо нам потрібно щоб кожне дзеркало жило в пошуку окремо.

Hreflang — каже Google що ці п'ять доменів пов'язані між собою. Українська версія посилається на британську, британська — назад на українську. Плюс є x-default — для всіх хто не підпадає під конкретний гео. Якщо забути зворотне посилання — Google просто ігнорує hreflang, і тоді він нічого не дає.

Як я це роблю в Nuxt: серверний middleware визначає з якого домену запит, і через useHead ставить правильні теги. Конфіг усіх дзеркал в одному місці — змінила один раз, працює для всіх.

З помилок які бачила: забувають вказати домен сам на себе в hreflang, не додають x-default, або URL в hreflang не збігається з тим що в sitemap. Перевіряю через Search Console — там видно проблеми. І в CI додала б перевірку що ці теги на місці після кожного деплою."

---

### 9. Як запобігти duplicate content across mirror domains?

**Відповідь:**

"Тут кілька рівнів захисту, вони працюють разом.

Перше — hreflang. Це сигнал Google що домени пов'язані і є локалізованими версіями, а не дублікатами. Обов'язково двосторонні — якщо UA посилається на UK, то UK має посилатись назад. Інакше Google ігнорує.

Друге — canonical на кожному домені вказує сам на себе. Це запобігає тому щоб Google сам вирішив яка версія 'головна' і прибрав решту.

Третє — контент реально має відрізнятись. Навіть якщо структура однакова — тексти, мова, валюта, промо, доступні ігри, юридичні застереження мають бути різними. Якщо два домени англійською — наприклад UK і Австралія — вони все одно повинні відрізнятись по текстах і meta descriptions. Однаковий контент слово-в-слово — це те що Google вважає дублікатом.

Четверте — кожне дзеркало зареєстроване окремо в Google Search Console з правильним гео-таргетингом. І robots.txt не блокує основний контент від пошукового бота."

---

### 10. Як діагностувати LCP регресію?

**Відповідь:**

"LCP — це час до рендеру найбільшого видимого елемента. Мій процес діагностики:

**Крок 1: Визначити що змінилося.** CrUX показує тренд за 28 днів. Якщо бачу деградацію — дивлюсь на deployment history: що шіпнули в цей період?

**Крок 2: Визначити LCP-елемент.** В DevTools → Performance → дивлюсь який елемент є LCP (зазвичай hero image, h1, або великий блок тексту).

**Крок 3: Розкласти на компоненти:**

- TTFB (сервер повільний?) — перевіряю SSR latency, cache hit ratio
- Resource load time (картинка велика?) — перевіряю розмір, формат, чи є preload
- Render blocking (CSS/JS блокують?) — дивлюсь waterfall
- Client-side rendering delay (hydration?) — перевіряю чи LCP-елемент є в SSR HTML

**Крок 4: Типові фікси в iGaming:**

- Hero banner: preload + srcset + WebP/AVIF + priority hint
- SSR: кешування щоб TTFB < 200ms
- Fonts: font-display: swap + preload critical font
- Third-party: defer GTM, async analytics
- Reduce critical CSS size

**Крок 5: Валідація** — прогоняю Lighthouse, Після фіксу я ставлю alert — якщо сімдесят п'ятий перцентиль LCP знову перевищить дві з половиною секунди, я отримаю нотифікацію і зможу відреагувати одразу, а не чекати поки CrUX покаже деградацію через 28 днів.""

---

### 11. Як діагностувати INP регресію?

**Відповідь:**

"INP (Interaction to Next Paint) — це latency від кліку/тапу до візуального оновлення. Замінив FID з 2024 року.

**Діагностика:**

1. **Web Vitals library** — додаю attribution build, яка показує конкретний елемент і event що спричинив поганий INP.

2. **Performance panel** — записую interaction, дивлюсь на Long Tasks в main thread. Шукаю: що блокує між input і paint?

3. **Типові причини в iGaming:**
   - Важкий re-render при оновленні live data (odds, balance) — рішення: virtualization, shallow reactivity, debounce
   - Event handler робить sync heavy computation — рішення: виносити в Web Worker або розбивати через requestIdleCallback
   - Hydration ще не завершилась і перший клік 'зависає'
   - Third-party scripts (chat widgets, tracking) блокують main thread

4. **Фікси:**
   - Оптимізувати re-renders: shallowRef для великих об'єктів, v-memo
   - Code splitting: lazy load неcritical modules
   - Yield to main thread: scheduler.yield() або setTimeout(0) в довгих задачах
   - Debounce/throttle high-frequency updates (WebSocket)

5. **Моніторинг:** відправляю INP attribution data в analytics, будую p75/p95 дашборд по сторінках."

---

### 12. Як боротися з CLS?

**Відповідь:**

"CLS (Cumulative Layout Shift) — це візуальна нестабільність. Елементи 'стрибають' після initial render.

**Типові причини і фікси:**

1. **Картинки без розмірів** → завжди вказувати width/height або aspect-ratio в CSS
2. **Динамічно вставлений контент** (банери, промо) → зарезервувати місце заздалегідь (min-height або skeleton)
3. **Web fonts** → font-display: swap + size-adjust або fallback з однаковими метриками
4. **Injected ads/banners** → фіксований slot з min-height
5. **Late-loading components** → SSR або skeleton, не порожній div що потім розширюється
6. **Dynamic content above fold** → ніколи не вставляти контент вище viewport після load

**В iGaming:**

- Live odds що змінюються — фіксувати висоту контейнера
- Promotional banners що підвантажуються через API — skeleton placeholder
- Cookie consent banner — показувати зверху або знизу без зсуву основного контенту

**Моніторинг:** Layout Instability API + Sentry → ловити CLS > 0.1, визначати яка нода shift source."

---

### 13. Як використовувати CrUX, Lighthouse і Sentry разом?

**Відповідь:**

"Це три різних інструменти з різними ролями:

**CrUX** — field data від реальних користувачів. Показує p75 LCP/INP/CLS за 28 днів. Це 'правда' для Google (впливає на rankings). Використовую для трендів і як джерело для алертів.

**Lighthouse** — lab data, синтетичні тести. Використовую для:

- CI/CD gate: PR не мержиться якщо score < threshold
- Швидкої діагностики: конкретні recommendations
- Порівняння before/after

**Sentry** — real-time errors + performance monitoring:

- Web Vitals per transaction (конкретна сторінка, конкретний deployment)
- Error correlation: якщо помилка корелює з поганим LCP
- Source maps для stack traces
- Release tracking: 'ця версія зробила LCP гіршим'

**Разом:** CrUX показує проблему → Lighthouse локалізує → Sentry підтверджує масштаб і пов'язує з release. Якщо CrUX деградує — перевіряю Sentry по цій сторінці, бачу який release, дивлюсь Lighthouse recommendations для фіксу."

---

### 14. Як побудувати performance monitoring і alerting?

**Відповідь:**

"Я б побудувала трирівневу систему:

**Рівень 1: CI/CD (prevention)**

- Lighthouse CI на кожен PR: score, bundle size, performance budget
- Alert якщо bundle > threshold або LCP score < 80

**Рівень 2: Synthetic monitoring (detection)**

- Scheduled Lighthouse runs кожні 4-6 годин на ключових сторінках
- Порівняння з baseline, alert на деградацію > 10%
- Для multi-domain: кожне дзеркало окремо

**Рівень 3: Real User Monitoring (truth)**

- Web Vitals library → custom analytics / Sentry Performance
- Дашборд: p75 LCP, INP, CLS по сторінках і по дзеркалах
- Alert якщо p75 LCP > 2.5s або INP > 200ms

**Дашборд Grafana (якщо є Prometheus):**

- SSR response time (p50, p95, p99)
- Cache hit ratio per domain
- Error rate per domain
- CWV trends
- Deploy markers

**Щоденна рутина:** перевірити Sentry issues, глянути CWV дашборд, тріажити нові алерти."

---

### 15. "У вас 5 дзеркал під навантаженням — як ви організуєте кешування щоб SSR сервер не ліг і users отримували сторінки швидко?"

_(також може звучати як: "Що таке stale-while-revalidate і де б ви застосували?" або "Як ви кешуєте SSR відповіді?")_

**Відповідь:**

"Перше що треба зрозуміти — SSR рендер коштує CPU. Якщо тисяча users одночасно заходить на сторінку /slots, без кешу сервер рендерить тисячу разів одне і те саме. Це нерозумно.

Тому я будую два рівні кешу.

Перший — CDN. Він стоїть перед сервером і просто віддає готовий HTML не доходячи до мого коду взагалі. Я ставлю заголовок:

```
Cache-Control: public, max-age=300, stale-while-revalidate=3600
```

Це означає: 5 хвилин сторінка свіжа, CDN віддає її миттєво. Після 5 хвилин — CDN все одно продовжує віддавати стару версію, але паралельно в фоні запитує у мого сервера нову. User не чекає ніколи.

Другий рівень — server cache всередині самого SSR сервісу. Redis або in-memory. Якщо CDN промахнувся — хоча б сервер не рендерить повторно.

Важливий момент для mirror domains — cache key обов'язково включає домен. Тобто `domain-ua.com:/slots` і `domain-uk.com:/slots` — це різні записи в кеші. Якщо забути домен в ключі — user з українського дзеркала отримає контент британського. Це і SEO катастрофа, і compliance порушення.

Що я ніколи не кешую — кабінет, касу, все що authenticated або містить дані конкретного user.

Трейдофф тут очевидний — деякі users побачать контент з запізненням до 5 хвилин. Для лендингів і ігрових сторінок це прийнятно. Але для бонусних умов або legal pages — де зміна має бути миттєва — я або скорочую TTL до хвилини, або роблю webhook-інвалідацію: CMS оновив контент → одразу purge цієї сторінки в CDN."

---

### 16. "Як ти ревʼюєш PR в продукті де важливі SEO і performance?"

_(також: "Що ти перевіряєш в код-рев'ю?" або "Як ти не допускаєш SEO-регресій після деплою?")_

**Відповідь:**

"У мене є внутрішній чекліст із трьох зон — SEO, performance і SSR-безпека. Пройдусь по кожній.

По SEO я дивлюсь чи не зламали щось в head. Якщо є зміни в meta, canonical або hreflang — перевіряю що вони правильні, бо одна помилка там може коштувати деіндексації цілого дзеркала. Якщо додається нова сторінка — перевіряю що вона є в sitemap і має title з description. Якщо змінюється URL — обов'язково має бути 301 редирект зі старого, інакше втрачаємо посилальну вагу і отримуємо 404 в GSC.

По performance — якщо PR додає нову бібліотеку, я одразу дивлюсь на її розмір. Є сайт bundlephobia — вставляєш назву пакету, бачиш скільки він важить. Якщо 50кб заради одного хелпера — питання є. Далі: нові зображення без розмірів і без lazy load — це одразу CLS і зайвий трафік. Новий third-party скрипт без defer — блокує рендер і б'є по LCP.

По SSR-безпеці — шукаю звернення до window, document, localStorage поза onMounted. Це крашить сервер при SSR. Також дивлюсь на Math.random() або Date.now() в шаблоні — вони дають різні значення на сервері і клієнті, тобто гарантований hydration mismatch. І ще одна пастка — якщо хтось змінює Pinia store напряму в setup поза action: Node.js один процес на всіх users, і якщо store живе не per-request — дані одного user потраплять до іншого. User A залогінився, записав свій userId, і User B чий запит прийшов через 10 мілісекунд бачить чужий userId. Це критична дірка.

В Prematch я впровадила цей чекліст як обов'язковий для всієї команди. Перші два тижні були питання, потім стало автоматично. SEO-сюрпризи після деплою зникли десь на 70%."

---

### 17. "Після деплою Google почав деіндексувати сторінки. Що робиш?"

_(також: "Як ти виявляєш і виправляєш SEO-регресію в продакшні?" або "Розкажи про процес incident response для SEO")_

**Відповідь:**

"Перше — зрозуміти масштаб. Одна сторінка чи весь домен? Це визначає наскільки швидко треба реагувати.

Йду в Google Search Console, дивлюсь Coverage report — там видно які сторінки випали і з якою причиною. Причини зазвичай чотири: з'явився noindex якого не було, canonical почав вказувати на інший домен, сторінки почали повертати 404 або 5xx, або robots.txt заблокував crawling.

Далі локалізую. Роблю `curl -I` на кілька affected URLs — дивлюсь status code і заголовки. Потім view-source — перевіряю чи є noindex в meta robots, чи правильний canonical. І одразу дивлюсь git log — що задеплоїли в той день коли почалась проблема.

У мене був такий кейс у WPT. Canonical middleware мав баг — для одного locale canonical починав вказувати на інший домен. Тобто українська сторінка казала Google що її canonical — британський домен. Google почав деіндексувати українські URL як дублікати. Виявила через GSC coverage drop, знайшла причину за 30 хвилин через git blame, задеплоїла хотфікс за 2 години. Але відновлення в індексі зайняло ще близько 5 днів — ось чому краще не допускати.

Тому після того я додала автоматичну перевірку після кожного деплою: скрипт перевіряє top-50 URL на наявність canonical, відсутність noindex, правильні hreflang. Якщо щось не так — alert іде до того як Google це побачив.

Якщо проблема критична — noindex на головних сторінках або canonical на чужий домен — це hotfix прямо зараз, не завтра. Якщо щось помірне — наприклад один зламаний hreflang — фіксую в найближчому спринті."

---

### 18. "Як би ти спроектувала shared cashier module який працює для кількох iGaming брендів одночасно?"

_(також: "Розкажи про найскладніший архітектурний виклик з якими ти стикалась")_

**Відповідь:**

"Це якраз те що я робила в NetGame — у нас було кілька iGaming проєктів і кожен потребував касу. Проблема в тому що на перший погляд каса виглядає однаково — форма поповнення, форма виводу, список методів. Але насправді кожен бренд має свої payment провайдери, свою валюту, свої ліміти, різні KYC-вимоги і різний вигляд.

Перше рішення яке напрошується — просто копіювати код між проєктами. Але це означає що баг в логіці платежу треба фіксити в п'яти місцях одночасно. Я пішла іншим шляхом.

Розділила на два рівні. Перший — незмінне ядро: бізнес-логіка, state machine платежу, API шар, типи. Це спільне для всіх і не залежить від бренду. Другий рівень — конфігурація бренду: які провайдери доступні, яка валюта, де саме в флоу стоїть KYC-перевірка, кольори і токени теми.

Composable `useCashier` приймає цей конфіг і повертає реактивний стан. Компоненти зроблені зі слотами — бренд може підставити свій заголовок, своє лого провайдера, свій текст помилки, але логіка залишається спільною.

Окремо важлива деталь — нормалізація помилок. Різні payment провайдери повертають помилки у своєму форматі. Один каже `error.code`, інший `error.reason`, третій `error.message`. Я зробила один mapper на вході — і далі весь код працює з єдиним форматом помилки. Це зберегло купу часу при відлагодженні.

Найскладніший трейдофф — знати коли зупинитись з абстракцією. Я спочатку хотіла зробити максимально гнучку систему, але швидко зрозуміла що якщо бренд потребує flow який кардинально відрізняється — краще зробити окремий модуль ніж додавати ще один if/else в загальний код.

Результат: додавання нового бренду скоротилось з двох-трьох тижнів до трьох-п'яти днів."

---

### 19. "Розкажи про досвід роботи з KYC і regulated flows"

_(також: "Як ти працювала з верифікацією користувачів?" або "Що таке KYC з фронтенд-перспективи?")_

**Відповідь:**

"Маю досвід з кількох проєктів, і KYC — одна з найскладніших зон на фронтенді саме тому що тут немає права на помилку.

В NetGame я інтегрувала Sumsub — це SDK для верифікації документів і особи. Технічно: ти створюєш applicant на бекенді, передаєш токен на фронт, Sumsub відкриває свій флоу де user фотографує документ і робить селфі. Далі — асинхронний процес верифікації. І ось тут складність: статуси можуть бути pending, approved, rejected, requires_action. Плюс купа edge cases — документ міг закінчитись під час review, верифікація могла пройти частково, міг прийти запит на повторну верифікацію через кілька тижнів. Кожен з цих станів має свій UI і свою логіку — що показати юзеру, що заблокувати, що дозволити.

В Prematch була інша ситуація — складніша. Змінилось законодавство по азартних іграх в Україні і з'явився жорсткий дедлайн. Нам треба було інтегрувати два SDK одночасно: Diia для державної верифікації і KYCAID для документів. І не просто інтегрувати — а покрити всі edge cases, бо це compliance: якщо щось не так — це не баг, це юридичний ризик для компанії.

Я розбила роботу на три паралельні треки між чотирма інженерами, ми робили daily sync замість weekly, а з QA узгодили скорочений але обов'язковий regression scope. Зашіпали в дедлайн без жодного compliance gap.

Головне що я винесла з цих проєктів: в регульованих флоу немає концепції 'допишемо потім'. Якщо є відомий edge case який не покритий — ти не шіпаєш, крапка. Це формує зовсім іншу дисципліну ніж у звичайній розробці."

---

### 20. "Розкажи про ситуацію коли у тебе були нечіткі вимоги і жорсткий дедлайн одночасно"

_(також: "Як ти працюєш в умовах невизначеності?" або "Як ти справлялась з legal deadlines?")_

**Відповідь:**

"Найяскравіший приклад — Prematch. Змінилось законодавство по азартних іграх і з'явився дедлайн який не можна перенести — це не product рішення, це закон.

На початку scope був дуже розмитий. Ніхто не розумів до кінця що саме треба зробити і в якому обсязі. Я не стала чекати поки хтось принесе готове завдання.

Перше що зробила — розбила все що відомо на блоки які можна починати незалежно. UI форм можна робити навіть коли API ще не готовий — просто на моках. Інтеграцію з SDK — окремий трек. Edge cases і стани верифікації — ще окремо. Розподілила між чотирма інженерами по силових сторонах кожного.

Важливий момент — я одразу підняла cadence спілкування. Не weekly синк, а щоденний, і в критичні дні двічі на день. Це здається як overhead, але насправді це єдиний спосіб виловити блокер на день 3 а не на день 6.

Саме так і сталось — на третій день daily sync виявив що backend не встигає з одним ендпоінтом. Я підняла це одразу, не чекала. Backend переприоритизував, ми не втратили день.

Ще одне правило яке я не порушую навіть під тиском — не шіпати без regression тестування. Краще зменшити scope ніж випустити щось зламане. Ми так і зробили — прибрали одну не критичну частину, але те що вийшло — вийшло без відомих gaps.

Зашіпали в дедлайн."

---

### 21. "Як ти балансуєш між швидкістю доставки і надійністю?"

_(також: "Як ти поводишся коли є тиск здати швидше?" або "Де ти готова йти на компроміс, а де ні?")_

**Відповідь:**

"Для мене швидкість і якість — це не протилежності. Питання в тому де саме ти економиш.

Моє правило: якщо дедлайн жорсткий — зменшую scope, але не якість. Тобто не 'зробимо все але наполовину', а 'зробимо половину але добре'. MVP який стабільно працює — кращий за повний product з багами в касі.

Є речі де я ніколи не йду на компроміс. Error handling, loading states, типізація — це не 'потім допишемо'. Якщо зараз не написати try/catch навколо API-виклику, то через тиждень будеш дебажити silent failure в продакшні і витратиш вдвічі більше часу. Тому я пишу це одразу — це коштує плюс 10% часу але рятує від мінус 40% потім.

Також я не шіпаю великими шматками. Маленькі PR, кожен з яких можна окремо задеплоїти і окремо відкотити. Якщо щось зламається — rollback одного PR, а не всього тижня роботи.

А от де можна зрізати — це pixel-perfect UI на першому релізі, якась анімація, ідеальна адаптивна верстка для рідкісного breakpoint. Це можна допілити. Але логіку KYC gate, обробку помилок платежу, SEO-теги — ні. Там помилка коштує або грошей, або compliance, або позицій в пошуку."

---

### 22. "Як ти розумієш що рішення занадто складне? Як уникаєш overengineering?"

_(також: "Розкажи про момент коли ти спростила архітектуру" або "Як ти знаходиш баланс між гнучкістю і простотою?")_

**Відповідь:**

"У мене є кілька маркерів які сигналізують що я йду не туди.

Перший — якщо я не можу пояснити рішення колезі за дві хвилини, значить воно занадто складне. Хороша архітектура пояснюється просто. Якщо потрібна п'ятихвилинна лекція з діаграмою — це привід зупинитись і спростити.

Другий маркер — я ловлю себе на тому що будую щось 'на майбутнє'. Це класична пастка. Я не знаю яким буде майбутнє. Якщо немає конкретних двох-трьох реальних use cases — абстракція передчасна. Дублювання коду на цьому етапі дешевше ніж неправильна абстракція.

У мене був прямий приклад з cashier. Я почала будувати 'universal payment flow engine' — максимально гнучкий, конфігурований, з підтримкою будь-якого сценарію. Швидко зрозуміла що це нікуди не годиться: код став незрозумілим, тестувати важко, додати новий бренд складніше ніж якби я просто скопіювала код. Зупинилась, переробила на прості конкретні composables — useDeposit, useWithdraw — зі спільним ядром але без зайвих абстракцій.

Ще одне просте запитання яке я ставлю собі: якщо мене завтра не буде в команді — хтось інший зможе в цьому розібратись? Якщо відповідь 'напевно ні' — треба спрощувати."

---

### 23. Які питання поставити UPSTARS?

1. "Як зараз виглядає SSR-сервіс? Це існуючий Nuxt проєкт, чи будемо будувати з нуля?"
2. "Які метрики CWV зараз? Є базовий дашборд, чи це теж потрібно побудувати?"
3. "Як організована взаємодія між моєю роллю і основною frontend-командою? Скільки людей в ній?"
4. "Яка інфраструктура для multi-domain: CDN, edge caching, чи є DevOps підтримка?"
5. "Що для вас виглядає як success за перші 3 місяці на цій позиції?"

---

## 5. Глибокі технічні шпаргалки

### Vue/Nuxt SSR Cheat Sheet

**Ключові концепти:**

- **Як працює SSR:** сервер будує повний HTML і віддає його браузеру. Браузер показує сторінку одразу — без очікування JS. Потім JS завантажується і "оживляє" вже існуючий HTML: підключає кліки, реактивність, події. Цей процес і називається hydration.

- **useAsyncData / useFetch:** дані запитуються на сервері, вкладаються прямо в HTML, браузер їх читає звідти — і не робить повторний запит до API. Якщо запит не обгорнути в ці composables а написати звичайний fetch — він виконається двічі: на сервері і на клієнті.

- **Pinia в SSR:** Nuxt автоматично створює окремий store для кожного запиту — але тільки якщо ти викликаєш `useUserStore()` всередині `setup()`, composable або middleware функції. Якщо викликати його на верхньому рівні файлу поза функцією — він стає спільним для всіх users одночасно, і дані одного user потраплять до іншого. Правило просте: `useXxxStore()` — тільки всередині функції, ніколи зовні.

- **Lifecycle хуки:** `onMounted` виконується тільки в браузері — тут безпечно звертатись до window, document, localStorage. На сервері цей хук просто не викликається. `onServerPrefetch` — навпаки, тільки на сервері, для асинхронного підвантаження даних перед рендером.

- **ClientOnly:** якщо є компонент який використовує браузерні API і не може бути відрендерений на сервері — обертаєш в `<ClientOnly>`. На сервері він просто не рендериться, показується fallback. На клієнті — нормально. Типові кейси: карти, графіки, все що звертається до window.

**Типові помилки:**

- Доступ до `window`/`document` в setup → crash на сервері
- `useState` vs `ref` в Nuxt: useState серіалізується, ref — ні
- Забути `key` на `useAsyncData` → cache collision
- Pinia action без await в SSR → data race

**Фрази для інтерв'ю:**

- "SSR — це не безкоштовне SEO. Це архітектурне рішення з серверними витратами і caching складністю."
- "Hydration mismatch — це завжди детермінізм. Якщо код дає різний результат на сервері і клієнті — буде mismatch."
- "В iGaming з mirror domains SSR cache key MUST включати домен."

---

### SEO Cheat Sheet

| Тема            | Що важливо                                                                                   |
| --------------- | -------------------------------------------------------------------------------------------- |
| Canonical       | Self-referencing для кожного дзеркала. Один canonical на сторінку.                           |
| Hreflang        | Bidirectional. Self-reference. x-default. Має бути в sitemap АБО в head.                     |
| Sitemap         | Динамічна генерація. Окрема для кожного домену. Lastmod актуальний.                          |
| Robots.txt      | Per-domain. Не блокувати JS/CSS. Вказувати sitemap.                                          |
| Structured data | JSON-LD в head. Для iGaming: Organization, WebSite, FAQPage, BreadcrumbList                  |
| Status codes    | 200 = OK, 301 = permanent redirect, 302 = temporary, 404 = not found, 410 = gone permanently |
| Redirects       | Зміна URL → 301. Тимчасова → 302. Chain redirects — уникати.                                 |
| SSR vs CSR      | Google рендерить JS, але із затримкою і не завжди повністю. SSR = guaranteed indexing.       |
| i18n            | hreflang + per-locale URL + per-locale content (не тільки переклад UI)                       |

---

### Core Web Vitals Cheat Sheet

**LCP (Largest Contentful Paint) — < 2.5s:**

- Що: час до render найбільшого елемента у viewport
- Причини: повільний TTFB, великі images, render-blocking resources, SSR latency
- Fix: preload hero image, CDN, cache SSR, optimize images (WebP/AVIF), font-display: swap
- Monitor: CrUX p75, Lighthouse, Web Vitals JS lib

**INP (Interaction to Next Paint) — < 200ms:**

- Що: час від кліку/тапу user до того як екран оновився. Якщо натиснув кнопку і нічого не сталось пів секунди — це поганий INP.
- Причини:
  - головний поток зайнятий важкою роботою і не може обробити клік — наприклад оновлюється 500 рядків списку одночасно
  - при кожному оновленні live-даних (odds, balance) Vue перерендерює забагато компонентів
  - обробник кліку робить щось важке синхронно — довгий цикл, складний розрахунок — перш ніж відповісти на дію
- Fix: code splitting, yield to main thread, shallowRef, virtualization, debounce
- Monitor: Web Vitals attribution, Long Tasks API

**CLS (Cumulative Layout Shift) — < 0.1:**

- Що: елементи на сторінці "стрибають" після завантаження — наприклад читаєш текст, підвантажився банер зверху і весь контент зсунувся вниз
- Причини:
  - картинка без вказаних ширини і висоти — браузер не знає скільки місця зарезервувати і "стрибає" коли картинка завантажилась
  - контент що підвантажується через API після рендеру — банер, промо, сповіщення — вставляється і зсуває все нижче
  - шрифт підвантажився і текст перемалювався з іншими розмірами — весь блок "скочив"
- Як фіксити:
  - для картинок — завжди вказувати width і height або aspect-ratio в CSS, тоді браузер заздалегідь резервує місце
  - для контенту що підвантажується — показувати skeleton (сірий placeholder правильного розміру) поки дані не прийшли
  - для шрифтів — `font-display: swap` щоб спочатку показати системний шрифт, і `size-adjust` щоб розміри збігались
  - для банерів і реклами — завжди резервувати місце фіксованою висотою контейнера заздалегідь
- Monitor: Layout Instability API, Lighthouse

---

### Monitoring Cheat Sheet

**Sentry:**

- Source maps → readable stack traces в production
- Release tracking → бачити які помилки з'явились після deploy
- Environment tags → staging vs production
- Error grouping → fingerprinting для кращого grouping
- Performance → transactions, spans, Web Vitals per page
- Alert: error rate spike > 2x baseline

**Lighthouse CI:**

- В GitHub Actions/GitLab CI
- Assertions: performance > 80, accessibility > 90
- Budget: main bundle < 200KB, total JS < 500KB
- Compare: before/after для кожного PR

**CrUX:**

- BigQuery або CrUX API
- 28-day rolling window
- p75 values — те що Google використовує для rankings
- Per-origin і per-URL data

**Prometheus/Grafana:**

- Frontend metrics: SSR response time, cache hit ratio, error rate
- Custom metrics: performance_lcp_seconds, performance_inp_seconds
- Alerts: p95 SSR latency > 1s, cache hit ratio < 70%, error rate > 5%

---

### iGaming Cheat Sheet

**Mirror domains:**

- Різні домени для різних гео (legal compliance, geo restrictions)
- Один codebase, multi-tenant config
- SEO challenge: duplicate content, hreflang complexity

**Payments/Cashier:**

- Multiple payment providers per geo
- KYC gates в payment flow
- State machine: idle → processing → success/error/pending
- Fallback providers якщо primary fails
- PCI DSS compliance для card data (iframe від provider)

**KYC/AML:**

- Onboarding verification: document + selfie + liveness
- Status lifecycle: pending → approved/rejected/requires_action
- Re-verification triggers
- Не можна дозволити unverified user робити фінансові операції

**Geo restrictions:**

- IP detection → правильне дзеркало
- Restricted countries → block access
- Per-geo: валюта, мова, payment methods, доступні ігри, legal pages

**SEO ризики для gambling:**

- Google strict з gambling content
- Потрібна ліцензія для ads
- Duplicate content across mirrors → penalізація
- UGC spam (fake reviews) → noindex/moderation
- Thin content → кожна сторінка має unique value

**Traffic spikes:**

- Events (sports), promotions → 3-10x traffic spike
- CDN + SSR cache critical
- WebSocket connections surge → backend capacity planning

---

## 6. Gaps та Honest Bridge Answers

### Prometheus/Grafana

"Я активно працювала з Sentry для frontend monitoring — тріаж помилок, performance transactions, release tracking. З Prometheus/Grafana я знайома на рівні споживача: читала дашборди SSR latency і cache hit ratio. Налаштування з нуля не робила, але розумію концепцію metrics → queries → dashboards → alerts. Для мене це природне розширення — я знаю ЩО моніторити (SSR response time, CWV, error rate), залишається освоїти HOW в конкретному інструменті. Це питання тижня-двох рамп-апу, а не фундаментальний gap."

### Streaming SSR

"Streaming SSR я не використовувала в production, але розумію принцип: сервер починає відправляти HTML chunks до того як весь response готовий. Це покращує TTFB — user бачить header/nav поки body ще рендериться. В Nuxt 3 це підтримується через renderToNodeStream. Мій поточний досвід — класичний SSR з повним render → response. Якщо потрібно впроваджувати streaming. Я б починала з тих сторінок де user довго чекає поки сервер взагалі починає відповідати — і де є сенс показати хоча б шапку і навігацію одразу, поки решта ще підвантажується."

### Redis/PostgreSQL

"Я не писала SQL queries або Redis commands напряму в своїх проєктах — це була зона backend команди. Але я розумію Redis як кеш-шар для SSR rendered pages (key-value store з TTL і invalidation), і PostgreSQL як джерело даних для sitemap generation і SEO metadata. Мій досвід — це правильна комунікація з backend: 'мені потрібен endpoint що віддає X за < 100ms, можемо кешувати в Redis з TTL 5хв'. Тобто я знаю де і навіщо використовувати, навіть якщо не адмініструю."

### Kubernetes/ArgoCD

"Мій деплой досвід — GitLab CI / GitHub Actions: build → test → deploy pipeline. Kubernetes як рантайм — знаю концепти (pods, services, ingress), бачила helm charts, але не писала їх. ArgoCD — знаю що це GitOps для K8s deployments. Для Senior Frontend ролі це не блокер — я розумію як мій SSR-сервіс деплоїться і скейлиться, навіть якщо інфраструктурою займається DevOps. Готова заглибитись якщо потрібно."

### CDN edge caching / Invalidation

"Я працювала з Cache-Control headers і розумію CDN caching: edge locations, cache keys, TTL, stale-while-revalidate. Побудову стратегії інвалідації (purge by URL, purge by tag, surrogate keys) не робила в production. Але це логічне продовження мого досвіду з server-side caching. Підхід: працювати з DevOps/Platform team на інтеграції, а я забезпечу правильні cache headers і invalidation triggers з application рівня."

### PWA / Service Workers

"Service Workers в продакшні не робила. Розумію що це таке: це скрипт який живе у фоні в браузері і може перехоплювати мережеві запити — наприклад зберігати сторінки щоб вони відкривались навіть без інтернету, або показувати свій екран замість стандартної помилки браузера коли зв'язок пропав. В iGaming це могло б бути корисно для push-нотифікацій про турніри або для того щоб сайт відчувався як мобільний додаток. Але це не те з чим я регулярно працювала — якби треба було впровадити, я б розбиралась окремо, це досить ізольована річ яка не зачіпає решту архітектури."

### Microfrontends

"Microfrontend архітектуру не будувала. Мій досвід — shared modules між проєктами (cashier module). Розумію підходи: module federation (Webpack/Vite), single-spa, iframe isolation.

---

## 7. Симуляція інтерв'ю (90 хв)

### Блок 1: Intro (10 хв)

**Інтерв'юер:** "Наталіє, розкажіть про себе і чому вас зацікавила ця роль."

**Що тестують:** Чи розуміє кандидат роль, чи може коротко донести relevant досвід.

**Моя відповідь:** [див. Модельна відповідь #1 + #2 вище]

**Follow-up:** "Яка ваша найбільша технічна перемога за останній рік?"

**Відповідь:** "SEO стратегія з нуля для FinTech продукту. Нуль платного трафіку, результат — 15-20 органічних реєстрацій/день. Це включало: SSR з правильним meta, structured data, sitemap, Core Web Vitals optimization, content clustering. Показало що technical SEO — це не тільки 'правильні теги', а архітектурне рішення яке впливає на бізнес-метрику."

**Red flags:** Не говорити "я passionate about code". Не перераховувати технології списком. Не відповідати > 2 хвилини.

---

### Блок 2: Vue/Nuxt Technical (12 хв)

**Інтерв'юер:** "Як ви структуруєте великий Nuxt 3 проєкт? Як розділяєте SSR-safe і client-only код?"

**Що тестують:** Архітектурне мислення, розуміння SSR constraints.

**Відповідь:** "Поділяю код на рівні:

- `/composables` — бізнес-логіка, SSR-safe by default (не використовують browser APIs)
- `/components` — UI компоненти. Якщо потрібен browser API — обертаю в onMounted або ClientOnly
- `/utils` — чисті функції, zero side effects, працюють однаково на сервері і клієнті
- `/server` — server-only код (API routes, middleware)

Правило: якщо composable використовує window/document/localStorage — це client-only composable і має бути позначений явно. В ньому має бути guard: `if (import.meta.client)` або він використовується тільки в onMounted.

Для великого проєкту з 5+ доменами — додатково layer architecture: shared base layer + per-brand overrides через Nuxt Layers."

**Follow-up:** "Розкажіть про hydration mismatch в реальному проєкті."

**Відповідь:** [Модельна відповідь #5 + конкретний приклад з Date/localStorage]

---

### Блок 3: SSR/Rendering Architecture (15 хв)

**Інтерв'юер:** "Уявіть: вам потрібно спроектувати SSR-мікросервіс для 5 доменів-дзеркал. Кожне дзеркало — свій гео, своя мова, свої промо. Як підходите?"

**Що тестують:** System design, multi-tenant thinking, caching, production readiness.

**Відповідь:**

"Окей, давайте по порядку.

Основна ідея — один сервіс обслуговує всі 5 доменів. Не п'ять окремих серверів, а один. Чому? Бо інакше кожну зміну в коді треба деплоїти п'ять разів, синхронізувати версії, тестувати окремо — це нереально підтримувати.

**Як сервіс розрізняє який домен перед ним?**

Коли браузер робить запит, він передає заголовок Host — це і є ім'я домену. Мій SSR сервіс читає цей заголовок і розуміє: 'ага, це domain-ua.com, значить мова українська, валюта гривня, доступні ось ці ігри і ось ці провайдери платежів'. Весь цей набір я називаю конфігурацією бренду — він лежить окремо, або в env-змінних або підтягується з API при старті сервісу.

В коді це виглядає так: server middleware зчитує Host, витягує конфіг, і далі в будь-якому місці додатку можна викликати composable — наприклад `useTenant()` — і отримати: яка зараз мова, валюта, які ігри показувати, який лого ставити.

**Кешування — найважливіша частина:**

Без кешу цей сервіс помре під навантаженням. 5 доменів, тисячі users на кожному — рендерити для кожного однаковий HTML недопустимо.

Перший рівень — CDN. Він стоїть перед моїм сервісом. Для більшості запитів CDN просто віддає готовий HTML взагалі не доходячи до мого коду. Сторінка лежить в кеші CDN п'ять хвилин, потім оновлюється в фоні.

Другий рівень — кеш всередині самого сервісу. Redis або просто в пам'яті. Якщо CDN промахнувся — хоча б мій сервер не рендерить заново.

Критично важливий момент: ключ кешу обов'язково включає домен. Тобто `/slots` для domain-ua.com і `/slots` для domain-uk.com — це два різних записи в кеші. Якщо забути домен в ключі — один user побачить контент іншого гео. Це і баг, і SEO катастрофа, і юридична проблема.

Коли контент змінюється — наприклад маркетинг оновив промо-акцію — приходить webhook і мій сервіс каже CDN: 'видали цю сторінку з кешу'. Наступний запит отримає свіжу версію.

**SEO — кожен домен живе окремо:**

Кожен домен має свій sitemap, свій robots.txt, свій canonical що посилається сам на себе. Плюс hreflang теги які зв'язують всі дзеркала між собою — це каже Google що це локалізовані версії одного продукту, а не дублікати.

**Моніторинг — обов'язково per-domain:**

Я б відстежувала окремо для кожного домену: як швидко сервер рендерить, яка частка запитів йде з кешу, скільки помилок, і метрики швидкості для реальних users. Якщо один домен деградує а інші ні — одразу зрозуміло що проблема специфічна для нього, а не загальна.

**Деплой:**

Мій SSR сервіс нічого не запам'ятовує між запитами. Прийшов запит — зрендерив HTML — відповів — забув. Ніякої сесії, ніяких даних в пам'яті які потрібні для наступного запиту. Все зберігається або в Redis, або приходить з API.

Чому це важливо: якщо сервіс нічого не зберігає — я можу поставити 10 однакових копій і кожен запит може йти на будь-яку з них. Це і є горизонтальне масштабування. Навантаження зросло — додали копії. Одна впала — решта працюють, user нічого не помітив. Якби сервіс тримав щось в пам'яті — при падінні ці дані б зникли і наступний запит зламався б.

**Головний ризик:**

Один сервіс на всі домени — якщо він впаде, впадуть усі п'ять. Тому обов'язково: кілька копій, перевірки здоров'я (сервіс відповідає — значить живий), і CDN як запасний варіант — якщо сервіс не відповідає, CDN віддає стару закешовану версію замість помилки."

**Якщо запитають: "А що якщо один домен має в десять разів більше трафіку за інші?"**

"Тут два варіанти. Або обмеження по кількості запитів з одного домену щоб він не з'їв усі ресурси. Або — що краще — виділити для нього окрему групу серверів. Плюс для найпопулярнішого домену особливо важливо щоб CDN кеш працював добре — якщо 90% запитів віддаються з CDN, до мого сервісу доходить тільки 10%, і навантаження нормальне."

---

### Блок 4: SEO (12 хв)

**Інтерв'юер:** "Після деплою ви бачите що Google деіндексував 30% сторінок одного з дзеркал. Ваші дії?"

**Що тестують:** Incident response, SEO debugging, production thinking.

**Відповідь:**

"Перше — не панікувати, а зрозуміти масштаб і причину.

Йду в Google Search Console — він показує стан індексації сайту. заходжу в розділ Coverage — він показує які саме сторінки зникли з пошуку і з якою причиною. Причини зазвичай одна з чотирьох:

Перша — на сторінках з'явився тег noindex, який каже Google 'не показуй цю сторінку в пошуку'. Хтось міг випадково додати його в коді.

Друга — canonical почав показувати на інший домен. Canonical — це тег який каже Google 'ось правильна адреса цієї сторінки'. Якщо українське дзеркало каже що його canonical — британський домен, Google вирішить що українська версія — дублікат і прибере її.

Третя — сторінки почали повертати помилки. 404 — сторінка не знайдена, або 500 — сервер зламався.

Четверта — файл robots.txt заблокував сторінки. Це файл який каже пошуковому боту які сторінки дозволено дивитись. Якщо хтось додав туди заборону — Google перестане їх індексувати.

Далі локалізую. Беру кілька адрес зі списку і дивлюсь на них вручну: що повертає сервер, які заголовки, що в HTML. Потім git log — хто коли що задеплоїв. Зазвичай проблема в конкретному коміті.

Якщо проблема критична — хотфікс прямо зараз. Деплою одразу. Після фіксу — прошу Google переіндексувати через ту ж Search Console. Але відновлення займає 3-7 днів — Google не перевіряє сайт щохвилини, ось чому краще не допускати.

Тому після такого я б додала автоматичну перевірку: після кожного деплою скрипт проходить по топ-50 сторінках і перевіряє що вони повертають 200, мають правильний canonical і не мають noindex. Якщо щось не так — alert одразу.

У мене був реальний такий випадок у WPT. Middleware для мета-тегів мав баг — для одного locale canonical вказував на чужий домен. Google почав прибирати українські сторінки. Знайшла через Search Console, через git blame побачила який коміт зламав, зафіксила за 2 години. Але відновлення індексації зайняло ще 5 днів."

---

### Блок 5: Performance (10 хв)

**Інтерв'юер:** "CrUX показує що LCP на мобільних погіршився на 800ms за останні 4 тижні. Як діагностуєте?"

**Що тестують:** Systematic debugging, знання CWV pipeline.

**Відповідь:**

"Окей, давайте розберемось. LCP — це час до моменту коли найбільший елемент на екрані повністю завантажився і показався user. Зазвичай це або головна картинка-банер, або великий заголовок. Якщо це число виросло на 800 мілісекунд — значить users чекають на майже секунду довше, і треба зрозуміти чому.

CrUX — це дані від реальних users Chrome за останні 28 днів. Тобто це не тест, а реальність. Якщо там деградація — проблема точно є.

Мій перший крок — подивитись що деплоїли за ці 4 тижні. Якщо LCP різко впав в один день — це конкретний деплой який зламав. Легко знайти через git log. Якщо погіршення поступове — значить не один конкретний коміт, а накопичення: може JS bundle ріс поступово, або додавали third-party скрипти які один за одним блокують рендер.

Далі відкриваю Lighthouse з емуляцією мобільного — ставлю throttling, бо на desktop все може виглядати нормально. Дивлюсь яку конкретну ноду Lighthouse вважає LCP-елементом. В iGaming це майже завжди герой-банер з промо-акцією.

Далі розкладаю проблему на частини. LCP залежить від чотирьох речей:

Перша — як швидко сервер відповів. Якщо SSR став рендерити довше або кеш перестав працювати — перший байт відповіді приходить пізніше, і LCP автоматично погіршується.

Друга — наскільки важкий сам ресурс. Якщо банер це картинка 2 мегабайти в PNG — це проблема. Треба WebP або AVIF, правильний розмір для мобільного, і preload щоб браузер почав завантажувати її якомога раніше.

Третя — чи є щось що блокує рендер перед ним. Якщо CSS або JS файл завантажується раніше і блокує показ сторінки — банер чекає. Треба перевірити waterfall — послідовність завантаження ресурсів.

Четверта — чи LCP-елемент рендериться на сервері чи тільки на клієнті. Якщо банер рендериться клієнтським JS а не приходить у початковому HTML — user чекає поки JS завантажиться і виконається. Для SEO-сторінок банер має бути вже в HTML з сервера.

Після фіксу — не просто деплою і забув, а ставлю алерт: якщо LCP знову перевищить 2.5 секунди для 75% users — отримую повідомлення одразу."

---

### Блок 6: Monitoring (8 хв)

**Інтерв'юер:** "Як ви організуєте моніторинг для SEO і performance на 5 доменах?"

**Відповідь:**

"Головне правило — моніторити кожен домен окремо, а не всі разом. Якщо у мене алерт 'середня швидкість по всіх 5 доменах', то це марно — один може деградувати а інші чотири витягують середнє. Я не побачу проблему.

Тому три рівні моніторингу, кожен окремо для кожного дзеркала:

Перший рівень — на етапі деплою. При кожному PR в CI запускається Lighthouse і перевіряє: чи не виросли розміри JS-бандла, чи не впав performance score, чи не зник canonical. Якщо щось не так — PR не мержиться. Це ловить проблеми ДО того як вони потрапляють в продакшн.

Другий рівень — синтетичний моніторинг. Кожні кілька годин автоматично прогоняється Lighthouse на ключових сторінках кожного домену. Результати порівнюються з попередніми. Якщо деградація більше 10% — мені приходить повідомлення в Slack.

Третій рівень — дані від реальних users. Через Sentry або Web Vitals бібліотеку збираю реальні метрики: як швидко сторінка завантажується для справжніх людей на справжніх телефонах. Будую дашборд де бачу LCP, INP, CLS для кожного домену окремо. Алерт ставлю так: якщо для конкретного домену 75% users мають LCP більше 2.5 секунди — повідомлення.

По SEO: окремо слідкую через Google Search Console за кожним доменом. Кількість проіндексованих сторінок, помилки crawling, hreflang проблеми. Якщо індексація впала — це ранній сигнал що щось зламалось.

І ось чому окремо по доменах це критично: якщо бачу що domain-ua деградує а інші ні — це одразу звужує пошук. Або проблема в контенті саме цього домену, або в CDN конфігурації для цього регіону, або в трафіку який різко виріс."

---

### Блок 7: Behavioral (8 хв)

**Інтерв'юер:** "Розкажіть про ситуацію коли ви не погодились з технічним рішенням і як це вирішили."

**Відповідь:**

"В Prematch була задача — потрібно дати маркетинг-команді можливість самостійно публікувати контент на сайт: новини, акції, статті. Початкова пропозиція від команди була побудувати свій власний CMS-дашборд з нуля — тобто адмінку з редактором, з базою, з авторизацією.

Я подивилась на це і сказала: це 2-3 місяці розробки мінімум. Плюс потім цю адмінку потрібно підтримувати, фіксити баги, додавати фічі. А задача по суті проста — маркетолог хоче написати текст і натиснути 'опублікувати'.

Я запропонувала Decap CMS — це готова CMS яка працює через Git. Тобто маркетолог заходить в зручний веб-інтерфейс, пише текст, натискає 'зберегти' — і це створює коміт в Git-репозиторій. Сайт автоматично підхоплює зміни. Ніякого окремого бекенду, ніякої бази даних, ніякого обслуговування.

Я не просто сказала 'ваше рішення погане'. Я прийшла з порівнянням:

- Свій дашборд: 2-3 місяці розробки, потім постійна підтримка, маркетинг залежить від інженерів.
- Decap CMS: 2 тижні інтеграції, підтримка нульова бо це стороннє рішення, маркетинг публікує самостійно без залучення розробників.

Прийняли мою пропозицію. Зробили за два тижні. Маркетинг з тих пір публікував автономно без звернень до команди розробки"

---

### Блок 8: Мої питання (5 хв)

[Див. відповідь #23]

---

## 8. Фінальний пакет для запам'ятовування

### 10 найсильніших фраз:

1. "Я вже будувала shared module для кількох iGaming проєктів — це прямий аналог ваших mirror domains."
2. "SEO для мене — бізнес-метрика, не чекліст. 15-20 реєстрацій/день через органіку без paid."
3. "Hydration mismatch — це завжди про передбачуваність. Код має давати однаковий результат і на сервері, і в браузері. Якщо щось відрізняється — буде mismatch."
4. "В regulated flows немає 'дофіксимо потім'. Або все працює, або не шіпається."
5. "Cache key для multi-domain MUST включати Host. Інакше один користувач побачить контент іншого гео."
6. "Я не чекаю тікет — я беру ownership: від competitive analysis до production monitoring."
7. "CrUX — це правда, Lighthouse — це діагностика, Sentry — це real-time."
8. "Краще зменшити scope до MVP на 100% якості, ніж зробити все на 60%."
9. "Не робити абстракцію поки не побачив 2-3 конкретні use cases."
10. "Мій підхід до production incident: detect → triage → fix → prevent."

### 10 коротких відповідей на найімовірніші питання:

1. **Чому ви?** → "5 років iGaming + SSR + SEO з бізнес-результатом + shared multi-brand modules + regulatory experience."
2. **SSR коли?** → "Коли потрібен SEO і контент динамічний. Landing, game pages — SSR. Cashier, cabinet — SPA."
3. **Hydration mismatch?** → "Код дає різний результат на сервері і клієнті. Date, localStorage, random, browser APIs."
4. **LCP fix?** → "Визначити LCP element → preload → optimize image → cache SSR → reduce TTFB."
5. **Canonical для mirrors?** → "Self-referencing на кожному дзеркалі. Hreflang зв'язує альтернативи. x-default для fallback."
6. **Sentry як?** → "Source maps, release tracking, error priority by affected users, correlation з deployments."
7. **Cache strategy?** → "CDN edge + stale-while-revalidate + server Redis cache + event-driven invalidation."
8. **KYC досвід?** → "Sumsub + Diia + KYCAID. Applicant lifecycle, status polling, compliance gates, legal deadlines."
9. **Overengineering?** → "YAGNI. Якщо пояснення архітектури > 5 хвилин — занадто складно."
10. **Prometheus/Grafana?** → "Знайома як consumer. Для frontend: SSR latency, cache hit, error rate, CWV. Рамп-ап — 1-2 тижні."

### 5 STAR-історій з мого CV (як розповідати вголос):

**1. Shared Cashier Module (NetGame)**

"В NetGame у нас було кілька iGaming проєктів одночасно — і кожен потребував свою касу. Різні платіжні провайдери, різний дизайн, різні ліміти. Спочатку кожен проєкт мав свою копію коду каси, і це було боляче — баг фіксиш в одному місці, а в іншому він залишається.

Я спроектувала спільний модуль: одне ядро з бізнес-логікою, а для кожного бренду — свій конфіг де прописано які провайдери доступні, яка валюта, де в процесі перевіряти KYC. Зробила окремі composables для депозиту і виводу, і state machine для всього платіжного потоку — щоб чітко було видно в якому стані зараз транзакція.

Результат: раніше підключення нового бренду займало 2-3 тижні, після — 3-5 днів. І швидкість проходження транзакцій виросла на 20-30%."

---

**2. SEO стратегія з нуля (WPT)**

"В WPT Technology я прийшла в FinTech продукт де не було жодного органічного трафіку. Нуль. І бюджету на рекламу теж не було.

Мені потрібно було побудувати канал залучення користувачів виключно через пошук. Я зробила: правильний SSR щоб Google бачив повний контент, прописала всі мета-теги і Open Graph, додала структуровані дані для пошукових систем, створила sitemap, оптимізувала швидкість завантаження під Core Web Vitals, зробила кластеризацію контенту по ключових словах, підключила Google Analytics і Search Console щоб бачити що працює.

За 3-4 місяці це дало 15-20 реєстрацій на день чисто з органіки — без жодної копійки на рекламу."

---

**3. KYC під legal deadline (Prematch)**

"В Prematch змінилось законодавство по азартних іграх — і з'явився жорсткий дедлайн за який потрібно було запустити верифікацію користувачів. Дата не обговорюється — це закон.

Потрібно було інтегрувати два SDK одночасно: Diia для державної верифікації і KYCAID для документів. Плюс покрити всі можливі сценарії — відмова, повторна верифікація, прострочений документ.

Я розбила роботу на три паралельні напрямки, розподілила між чотирма інженерами, організувала щоденні синки щоб блокери виловлювались одразу, і з QA узгодила мінімальний але обов'язковий обсяг тестування.

Зашіпали в дедлайн. Жодного compliance-порушення."

---

**4. Міграція Vue 2 → Nuxt 3 (NetGame)**

"В NetGame платформа працювала на Vue 2 з Quasar — старий стек, повільна розробка, складно додавати нові фічі. Потрібно було перевести на сучасний стек.

Я була в core-команді міграції. Побудувала бібліотеку спільних composables, визначила архітектуру компонентів, налаштувала SSR. Міграцію робили поступово — не переписували все з нуля, а модуль за модулем.

Результат: швидкість доставки фіч зросла приблизно на 40%"

---

**5. PR Standards (Prematch)**

"Коли я прийшла в Prematch як тімлід, в команді було 4 інженери з різним бекграундом. Код-рев'ю було формальне — хтось дивився, хтось ні, критеріїв не було, якість була нестабільна.

Я впровадила чекліст для рев'ю: що обов'язково перевіряти, як називати компоненти і файли, яка структура компонентів вважається правильною. Плюс щотижневі 1-on-1 де обговорювали що було складно і що покращити.

Через місяць-два процес устаканився — review cycle став швидшим бо всі розуміли правила, і 'сюрпризні' SEO-баги після деплою зникли приблизно на 70%."

### 5 питань для UPSTARS:

1. "Яка архітектура зараз: SSR service вже існує чи будемо проектувати з нуля?"
2. "Які CWV метрики зараз по доменах? Є baseline?"
3. "Як взаємодія з основною frontend командою — це окрема team чи embedded?"
4. "Яка інфраструктура: CDN provider, caching layer, DevOps support?"
5. "Що для вас success за перші 90 днів на цій позиції?"

### 5 речей які НЕ можна говорити:

1. **НЕ:** "Я ніколи не працювала з Prometheus/Grafana" → **КРАЩЕ:** "Як користувач знайома, setup — 1-2 тижні рамп-ап"
2. **НЕ:** "Я passionate about clean code" → **КРАЩЕ:** конкретний приклад як architectural decision вплинув на метрику
3. **НЕ:** "Це зона відповідальності DevOps" → **КРАЩЕ:** "Я забезпечу application-level рішення і collaborate з platform team"
4. **НЕ:** "В моєму попередньому проєкті все було погано" → **КРАЩЕ:** "Я побачила можливість покращити X і ось результат"
5. **НЕ:** Довгі академічні пояснення без прикладу → **КРАЩЕ:** коротка теза + приклад з досвіду + трейдофф

---

## 9. Позиціонування

**Моя позиція на цьому інтерв'ю:**

"Я не просто Vue/Nuxt розробник. Я — інженер який може взяти ownership на SEO-sensitive, performance-critical frontend архітектуру в regulated iGaming продукті. Я розумію як рендеринг, індексація, кешування, моніторинг, Core Web Vitals і продуктові потоки впливають на revenue і reliability.

Мій unique value:

- iGaming domain (5 років) + shared multi-brand architecture
- SEO як бізнес-канал (не тільки 'правильні мета-теги')
- Regulated flows (KYC/AML під legal deadlines)
- Production reliability mindset (Sentry daily, incident response)
- Product ownership (end-to-end delivery без PM/designer)
- Team leadership і standards (4 engineers, PR review, hiring)"

Кожна відповідь на інтерв'ю має підсилювати одну з цих тем. Не просто 'я знаю технологію X' — а 'я використовувала X для досягнення Y бізнес-результату в Z контексті'.

---

## 4b. Додаткові модельні відповіді (A–L)

### A4. Найбільший приклад ownership на фронтенді?

"Shared cashier module в NetGame. Кілька iGaming проєктів потребували cashier — різні payment providers, різний UI, різні KYC gates. Я спроектувала архітектуру: core бізнес-логіка + per-brand config + composables (useDeposit, useWithdraw). Це не просто 'написати компонент' — це визначити API контракти з backend, спроектувати state machine для payment flow, покрити edge cases (timeout, partial failure, KYC block mid-flow), і забезпечити що новий бренд додається за 3-5 днів замість 2-3 тижнів. Ownership від архітектурного рішення до production monitoring через Sentry."

---

### A5. "Як ти працюєш коли немає дизайнера і PM?"

**Відповідь:**

"В WPT Technology я була єдиний фронтенд-інженер, і ні дизайнера, ні продакт-менеджера в команді не було. Тобто рішення що будувати, як це має виглядати і як це подати користувачу — все було на мені.

Що я робила замість PM: дивилась на конкурентів. Не просто 'о, в них красиво' — а системно: які flow вони мають, чого нам не вистачає, де в них краще а де гірше, як вони перформлять по швидкості. Це давало мені розуміння що робити далі і в якому пріоритеті.

Що я робила замість дизайнера: я не малювала макети в Figma. Я брала перевірені UI-патерни — Tailwind дає хорошу систему відступів, типографіки, кольорів — і будувала інтерфейс на цих готових блоках. Не винаходила дизайн з нуля, а використовувала те що працює.

Для лендінгу наприклад — я сама визначила хто наша аудиторія, що для них важливо, яка структура сторінки буде працювати, і написала напрямок тексту. Потім зверстала і запустила.

І далі — не вгадувала чи вийшло, а дивилась на цифри. Google Analytics показує скільки людей прийшло, Search Console — за якими запитами знаходять, і вже на основі цього я ітерувала — змінювала те що не працює.

Результат: переробка UX інвойсів дала зростання кількості створених інвойсів, а лендінг почав конвертити в реєстрації з органічного трафіку."

---

### A6. "Розкажи про досвід керування командою"

**Відповідь:**

"В Prematch я керувала командою з чотирьох фронтенд-інженерів. Люди були з різним досвідом і різним бекграундом — хтось прийшов з іншого фреймворку, хтось був більш junior.

Перше що я зробила — впровадила правила код-рев'ю. До мене їх просто не було — кожен писав по-своєму, ніхто не знав що вважати 'правильним'. Я написала чекліст: як називати компоненти, яка структура файлів, що обов'язково перевіряти перед тим як затвердити PR. Перші два тижні були питання, потім стало автоматично.

По процесах: sprint planning — разом визначали що беремо в роботу. Daily standup — коротко хто що робить і чи є блокери. І щотижневі 1-on-1 з кожним — не мікроменеджмент, а 'що тобі заважає, що хочеш вивчити, де потрібна допомога'.

Найскладніший момент — коли прийшов legal deadline по KYC. Дата не рухається, обсяг великий. Я розбила задачу на три напрямки і розподілила між інженерами — кожен отримав те що йому ближче по навичках. Організувала щоденний синк щоб блокери не накопичувались. На третій день один блокер виявили — я одразу ескалювала на бекенд, вони переприоритизували. Зашіпали вчасно.

Також проводила технічні інтерв'ю і формувала склад команди.

Головне що я зрозуміла про роль ліда: це не про те що ти найкращий кодер в кімнаті. Це про те щоб команда доставляла якісно і вчасно, і щоб кожна людина зростала."

---

### A7. "Як ти поводишся коли задача нечітка і незрозуміло що саме треба зробити?"

**Відповідь:**

"Я не чекаю поки хтось принесе мені ідеальне завдання з усіма деталями. Цього може не статись ніколи.

Мій підхід: спочатку розділяю — що я точно знаю, а що є припущенням. Потім іду уточнювати — але не абстрактно 'розкажіть що робити', а конкретно: 'я правильно розумію що флоу має бути такий: спочатку вибір методу, потім сума, потім підтвердження? Чи є винятки?'. На конкретне питання завжди простіше відповісти.

Якщо відповіді довго немає — я не стою і не чекаю. Роблю найбезпечніший варіант який легко потім змінити.

Конкретний приклад з cashier module в NetGame. API ще не був готовий, бекенд ще визначався з форматами. Замість сидіти і чекати — я зробила підставний шар: UI і логіку написала повністю, а замість реальних запитів до серверу підставила фейкові відповіді з правильною структурою. Коли бекенд фіналізував API — мені треба було лише замінити фейкові дані на реальний запит. Зайняло пів дня замість тижня простою."

---

### A8. "Які у тебе стандарти код-рев'ю? Що ти перевіряєш?"

**Відповідь:**

"У мене є внутрішній пріоритет — я перевіряю не все одночасно, а по важливості.

Перше — чи воно взагалі правильно працює. Чи вирішує задачу, чи немає випадків які не враховані — наприклад що буде якщо API поверне помилку, або якщо дані порожні.

Друге — чи не зламається на сервері при SSR. Чи є звернення до window або localStorage без перевірки, чи не буде розбіжностей між тим що рендерить сервер і що бачить браузер.

Третє — чи не постраждає SEO. Якщо є зміни в мета-тегах — перевіряю що canonical на місці, що hreflang не зламаний. Якщо нова сторінка — чи є вона в sitemap.

Четверте — performance. Якщо додається нова бібліотека — скільки вона важить. Якщо картинки — чи є розміри, чи є lazy loading. Якщо новий сторонній скрипт — чи не блокує він завантаження сторінки.

П'яте — типізація. Чи немає any, чи обробляються помилки, чи перевіряються nullable значення.

Шосте — читабельність. Просте правило: чи зрозуміє цей код інший інженер через три місяці без пояснень.

Через що я ніколи не блокую PR — стилістика, форматування, порядок імпортів. Для цього є лінтер, він сам поправить. А от через що блокую обов'язково — зламаний SSR, SEO-регресія, відсутня обробка помилок, або дірка в безпеці.

В Prematch після впровадження цього чекліста несподівані баги після деплою зменшились приблизно на 70%."

---

### A9. Як комунікуєте з product/backend/QA?

"Залежить від контексту:

**З product:** Говорю мовою бізнес-метрик. Не 'це складно технічно', а 'це +2 тижні, і ось що ми отримаємо / не отримаємо'. Пропоную MVP scope якщо deadline жорсткий.

**З backend:** Спільно визначаю API контракти ДО початку розробки. Не чекаю готовий endpoint — пишу interface, обговорюю, backend імплементує під контракт. Якщо API змінюється — DTO layer захищає frontend від cascading changes.

**З QA:** Разом визначаємо що вважати 'готовим' ще ДО того як я починаю писати код — тобто які сценарії мають працювати, що перевіряти, які граничні випадки можуть бути. Я сама описую QA які edge cases варто тестити — бо я як розробник знаю де можуть бути проблеми. Після того як я здала задачу — доступна для питань під час тестування. Рішення чи можна релізити — це спільна відповідальність, не тільки QA і не тільки моя."

---

### A10. "Що для тебе product-minded engineer?"

**Відповідь:**

"Для мене це означає розуміти навіщо я щось роблю, а не просто як.

Наприклад. Я робила SEO — але не тому що 'так правильно'. А тому що це єдиний спосіб привести користувачів коли немає бюджету на рекламу. І це дало 15-20 реєстрацій на день.

Або performance. Я оптимізую швидкість не заради зеленого кружечка в Lighthouse. А тому що якщо сторінка вантажиться повільно — людина просто закриває вкладку і йде до конкурента. Це прямо впливає на гроші.

Або shared cashier. Я побудувала його не заради красивої архітектури. А тому що без нього підключення нового бренду займало три тижні, а з ним — три дні. Це швидкість виходу на ринок.

Моє просте правило: перед тим як починати задачу, я запитую себе 'а що це покращить для бізнесу?'. Якщо відповідь 'нічого конкретного' — можливо зараз це не найважливіше."

---

### A11. "Що значить для тебе senior frontend engineer?"

*(також: "Чим senior відрізняється від mid?" або "Як ти розумієш seniority?")*

"Для мене senior — це не про кількість років, а про те як ти приймаєш рішення і яку відповідальність береш. Mid-рівень отримує задачу і робить її добре. Senior бачить ширше — думає про наслідки для SEO, performance, підтримуваність, моніторинг, про те як це вплине на інших розробників у команді. І бере ownership: не чекає поки хтось скаже що робити, а сам бачить проблему, пропонує рішення, доводить до продакшну і слідкує що воно працює. Плюс — вміє сказати 'ні' поганому рішенню, аргументовано і з альтернативою."

---

### A12. "Чим useFetch відрізняється від $fetch?"

*(також: "Коли що використовувати?" або "Навіщо useFetch якщо є $fetch?")*

"$fetch — це просто обгортка над fetch, вона робить запит і повертає дані. Все. Якщо написати $fetch в setup — він виконається двічі: на сервері і потім ще раз на клієнті. Тому що клієнт не знає що сервер вже отримав ці дані.

useFetch — це composable який вирішує цю проблему. Він робить запит на сервері, вкладає результат в HTML, і на клієнті підхоплює його без повторного запиту. Плюс дає реактивний стан: data, pending, error, refresh.

Просте правило: в компонентах і сторінках — завжди useFetch або useAsyncData. $fetch — тільки всередині серверних API routes, в обробниках подій або коли потрібен запит без SSR-інтеграції."

---

### A13. "shallowRef — коли і навіщо?"

"Звичайний ref робить об'єкт реактивним на всю глибину — кожне вкладене поле трекається. Для маленьких об'єктів це нормально. Але якщо в ref лежить масив з тисячею елементів або складне дерево — Vue витрачає час на обхід всієї структури і створення Proxy для кожного рівня.

shallowRef робить реактивним тільки саме посилання — змінив весь об'єкт цілком — Vue побачить. Змінив поле всередині — не побачить. Це значно швидше для великих даних.

Використовую для великих списків, live-даних з WebSocket, або будь-якого об'єкта де мені не потрібна глибока реактивність — я і так замінюю весь об'єкт цілком при оновленні."

---

### A14. "Як оптимізуєш тяжкі списки?"

*(також: "Що робиш коли список з 10 000 елементів гальмує?" або "Як рендерити великі таблиці?")*

"Якщо список великий і гальмує — перше що роблю: рендерю тільки те що видно на екрані. Це називається віртуалізація — бібліотеки типу vue-virtual-scroller або vue-virtual-list. Замість 10 000 DOM-елементів у браузері живе 30-50, і при скролі вони переиспользовуються. Різниця драматична.

Друге — v-memo. Це директива у Vue 3 яка каже: не перерендерюй цей елемент списку поки конкретні залежності не змінились. Корисно коли список оновлюється частково — змінився один елемент, а Vue без v-memo перевіряє всі.

Третє — shallowRef для самих даних, щоб Vue не робив deep tracking на кожному елементі масиву.

І четверте — пагінація або infinite scroll замість завантаження всього одразу. Не завжди потрібно тримати 10 000 записів у пам'яті."

---

### B1. "Чим Composition API кращий за Options API для великих проєктів?"

**Відповідь:**

"Для великих проєктів — три речі які реально відчуваються.

Перша — в Options API код однієї фічі розкиданий по різних секціях: дані окремо, обчислення окремо, методи окремо, вотчери окремо. Коли компонент виростає — ти стрибаєш по файлу вгору-вниз щоб зрозуміти як одна функція працює. В Composition API вся логіка однієї фічі лежить поруч. І її можна винести в окремий файл — composable — і перевикористати в іншому місці.

Друга — перевикористання коду. В Options API для цього були mixins, але вони створювали купу проблем: незрозуміло звідки приходить змінна, імена можуть конфліктувати якщо підключив два mixins з однаковою назвою. Composables — це звичайні функції, все явно, видно що вони повертають, TypeScript їх підхоплює автоматично.

Третя — TypeScript. Composition API від початку спроектований так щоб типи працювали з коробки. В Options API — потрібні обгортки і хаки щоб TypeScript нормально розумів що відбувається.

Ще з бонусів: composable — це звичайна функція, тому її легко тестувати юніт-тестами. І для SSR важливо — чітко видно що виконується на сервері а що ні, бо lifecycle хуки прописані явно.

Options API при цьому не поганий — для маленького простого компонента де все вміщається на один екран і нічого не треба перевикористовувати — він нормально працює."

---

### B2. "Як ти структуруєш composables? Коли виносиш логіку з компонента?"

**Відповідь:**

"Два випадки коли я виношу логіку в composable.

Перший — коли та ж логіка потрібна в кількох місцях. Наприклад, отримання даних про турніри — це потрібно і на головній сторінці, і на сторінці турнірів, і всередині самої гри. Один composable — і все працює однаково всюди.

Другий — коли компонент став занадто великим. Якщо setup розрісся більше ніж на 100 рядків і в ньому перемішані різні речі — час розділити. Кожен composable відповідає за одну конкретну задачу.

Як виглядає типовий composable в мене: він приймає вхідні дані, тримає в собі стан (дані, стан завантаження, помилку), робить запит до API, і повертає все це назовні. Тобто компонент не знає деталей — він просто каже 'дай мені список методів' і отримує готовий результат з індикатором завантаження і помилкою якщо щось пішло не так.

Наприклад `usePaymentMethods` — приймає ідентифікатор бренду, сам робить запит, сам слідкує якщо бренд змінився і перезапитує, сам обробляє помилки. Компонент отримує тільки готові дані і прапорець 'завантажується чи ні'.

Важливий принцип: composable повинен бути безпечний для SSR — тобто не звертатись до window чи localStorage. І обробка помилок і стану завантаження — всередині composable, а не в кожному компоненті окремо.

Коли НЕ виношу: якщо логіка використовується тільки в одному місці і це менше 30 рядків — нема сенсу створювати окремий файл заради 30 рядків."

---

### B2b. "А коли краще composable, а коли Pinia store?"

**Відповідь:**

"Просте правило: якщо дані потрібні тільки одному компоненту або групі батько-дитина — composable. Якщо дані потрібні в різних частинах додатку які між собою ніяк не зв'язані — Pinia.

Наприклад. Дані про поточного user — баланс, статус KYC, ім'я — це потрібно і в шапці, і в касі, і в кабінеті, і в профілі. Ці компоненти між собою не пов'язані, вони в різних частинах дерева. Тому це Pinia store — глобальний стан всього додатку.

А от логіка завантаження списку ігор для конкретної сторінки — це composable. Зайшов на сторінку — підвантажив, пішов зі сторінки — дані більше не потрібні. Ніхто інший в додатку ці дані не чекає.

Ще один маркер: якщо дані повинні зберігатись між переходами по сторінках — це Pinia. Якщо дані живуть тільки поки компонент на екрані — це composable.

В iGaming: баланс user — Pinia (показується всюди). Список турнірів на конкретній сторінці — composable. Налаштування каси — Pinia (бо каса може відкриватись з різних місць і стан повинен зберігатись)."

---

### B3. "Як працює Pinia в SSR? Як уникнути витоку даних між користувачами?"

**Відповідь:**

"Головна пастка тут ось яка. Node.js — це один процес який одночасно обслуговує запити від тисяч різних людей. Якщо store створений один раз і живе 'глобально' — то дані одного користувача можуть потрапити до іншого.

Уявіть: User A зайшов, залогінився, його userId записався в store. Через мілісекунду прийшов запит від User B — і він бачить чужий userId, бо store один на всіх.

Nuxt це вирішує автоматично: при кожному новому запиті від користувача створюється свій окремий екземпляр store. User A має свій, User B — свій, вони не перетинаються.

Але це працює тільки за однієї умови: ти викликаєш `useUserStore()` всередині функції — в setup компонента, в composable, в middleware. Якщо ж ти напишеш `const store = useUserStore()` на верхньому рівні файлу поза будь-якою функцією — це виконається один раз при старті сервера і далі буде спільним для всіх. Ось тут і виникає витік.

Тобто одне просте правило: `useStore()` — завжди всередині функції. Ніколи зовні.

Ще один момент: якщо потрібно щоб стан передався з сервера в браузер — наприклад сервер завантажив дані і хочемо щоб браузер їх підхопив без повторного запиту — використовуємо `useState()` замість звичайного `ref()`. Він серіалізується автоматично.

Перевірити що все правильно просто: відкрити сайт в двох різних браузерах одночасно — кожен повинен бачити тільки свої дані."

---

### B4. "Що таке SSR-safe код? Що може піти не так якщо про це не думати?"

**Відповідь:**

"SSR-safe код — це код який нормально працює і на сервері, і в браузері. Або чітко розділений: ось це тільки для сервера, а ось це тільки для браузера.

Якщо про це не думати — чотири типи проблем:

Перша — сервер крашиться. Написав `window.innerWidth` в setup компонента — на сервері window не існує, і весь запит падає з помилкою. Замість сторінки user отримує 500-ту помилку.

Друга — hydration mismatch. Сервер зрендерив один HTML, браузер при підключенні Vue спробував зрендерити інший. Наприклад, якщо в шаблоні показуєш поточний час — на сервері це буде одне значення, в браузері через секунду вже інше. Vue побачить розбіжність і може зламати інтерфейс.

Третя — витік даних між користувачами. Це ми вже обговорювали з Pinia — якщо store глобальний, дані одного user потрапляють до іншого.

Четверта — витік пам'яті на сервері. Якщо створити setInterval або addEventListener на сервері — вони ніколи не очистяться, бо onUnmounted на сервері не викликається. З кожним запитом їх стає більше, сервер повільнішає і зрештою падає.

Мої правила щоб цього уникнути:

— Все що стосується window, document, localStorage — тільки в onMounted або за перевіркою `if (import.meta.client)`.
— Math.random() і Date.now() — не використовувати в шаблоні, бо вони дадуть різний результат на сервері і клієнті.
— Аналітика, трекінг, чати — тільки на клієнті, серверу це не потрібно.
— useRouter, useRoute і подібні Nuxt composables — з ними все добре, вони вже побудовані так щоб працювати і на сервері, і в браузері."

---

### B5. "Які lifecycle hooks працюють на сервері, а які тільки в браузері?"

**Відповідь:**

"Тут просте правило: на сервері працює тільки `setup()` і те що пов'язане з підготовкою даних. Все що пов'язане з DOM, монтуванням, оновленням — тільки в браузері.

Конкретно:

`setup()` — працює і на сервері, і в браузері. Тому якщо я напишу туди звернення до window — сервер впаде. Все що в setup — має бути безпечним для обох середовищ.

`onMounted` — працює ТІЛЬКИ в браузері. Це моє безпечне місце: якщо мені потрібно звернутись до window, document, localStorage, підключити chart-бібліотеку, ініціалізувати third-party widget — все це в onMounted. На сервері цей код просто не виконається.

`onUnmounted` — теж тільки в браузері. Тому якщо я створила WebSocket або setInterval в onMounted — закриваю їх в onUnmounted. На сервері ці хуки не викликаються взагалі.

`onServerPrefetch` — навпаки, тільки на сервері. Це для підвантаження даних перед рендером. Але в Nuxt зазвичай використовують useAsyncData замість нього — це зручніше і результат автоматично передається в браузер.

`onErrorCaptured` - ловить помилĸи і на сервері і на клієнті

В Nuxt є ще `useAsyncData` і `useFetch` — вони виконуються на сервері, результат вкладається в HTML, і браузер його підхоплює без повторного запиту. Це основний спосіб завантаження даних в SSR."

---

### B6. "useAsyncData і useFetch — яка різниця і коли що використовувати?"

**Відповідь:**

"Обидва роблять одне і те саме: завантажують дані на сервері, вкладають результат в HTML, і браузер їх підхоплює без повторного запиту. Різниця в тому наскільки складний запит.

`useFetch` — для простих випадків. Один запит до одного ендпоінту. Наприклад: 'дай мені список ігор категорії слоти для українського гео'. Це коротко і зрозуміло.

`useAsyncData` — коли логіка складніша. Наприклад, для дашборду гравця мені потрібно одночасно завантажити баланс, бонуси і історію транзакцій — три запити паралельно, і потім скласти з них один об'єкт. Або коли потрібно трансформувати відповідь перед тим як використовувати.

Кілька важливих нюансів які часто забувають:

Ключ — кожен виклик має мати унікальне ім'я. Якщо два різних запити випадково отримають однаковий ключ — вони будуть конфліктувати в кеші і один перетре дані іншого.

Опція `lazy: true` — корисна коли не хочемо щоб сторінка чекала на ці дані перед показом. Наприклад, основний контент показуємо одразу, а рекомендовані ігри підвантажуються вже після.

Опція `server: false` — каже що цей запит потрібен тільки в браузері, на сервері його не робити. Це для авторизованих даних — балансу, профілю — які не мають потрапляти в HTML який кешується.

Опція `watch` — якщо передати reactive змінну, дані перезапитаються автоматично коли вона зміниться. Наприклад, змінився фільтр категорії — список ігор оновився без додаткового коду."

---

### B7. "Як працюють route middleware в Nuxt 3?"

**Відповідь:**

"Middleware — це код який виконується перед тим як user потрапляє на сторінку. Типовий приклад: перевірити чи user залогінений — якщо ні, перекинути на сторінку логіну замість того щоб показати кабінет.

В Nuxt є три типи:

Перший — глобальний. Файл з `.global.ts` в назві. Виконується при КОЖНОМУ переході між сторінками. Наприклад, перевірка гео-обмежень: якщо user з заблокованої країни — перекидуємо на сторінку 'сервіс недоступний у вашому регіоні'. Це працює на кожній сторінці автоматично.

Другий — іменований. Прив'язується тільки до конкретних сторінок. Наприклад, middleware перевірки KYC — вішаю тільки на касу і виведення коштів. В налаштуваннях сторінки прописую: 'перед показом цієї сторінки — запусти перевірку kyc-check'.

Третій — інлайн. Прямо в налаштуваннях конкретної сторінки написана логіка. Для одноразових простих перевірок.

Важливий момент: при першому завантаженні сайту middleware виконується на сервері. При переходах між сторінками вже в браузері — виконується на клієнті. Тому middleware не може звертатись до window чи document — він має бути безпечним для обох середовищ.

І ще одне — не плутати з серверними middleware. В Nuxt є папка `/server/middleware/` — це зовсім інше. Те що там — працює тільки на сервері і обробляє HTTP запити: додає заголовки, логує, перевіряє токени. Route middleware — це про навігацію по сторінках. Server middleware — це про обробку запитів як в Express."

---

### B8. "Як працюють plugins в Nuxt 3?"

**Відповідь:**

"Plugins — це код який виконується один раз при старті додатку. Використовуються для речей які потрібно налаштувати глобально до того як додаток почне працювати. Наприклад: підключити Sentry для відстеження помилок, створити API-клієнт який буде доступний всюди, зареєструвати якусь кастомну директиву.

по суфіксу файлу Nuxt розрізняє де запускати plugin:

- `sentry.client.ts` — тільки в браузері. Sentry потрібен тільки на клієнті.
- `api.ts` (без суфікса) — і на сервері, і в браузері. API-клієнт потрібен в обох місцях.
- `analytics.server.ts` — тільки на сервері. Рідко, але буває для серверного логування.

Порядок виконання: спочатку серверні, потім універсальні, потім клієнтські. В межах одного типу — за алфавітом імені файлу.

Якщо plugin щось 'дає' всьому додатку — наприклад API-клієнт — він повертає `provide`. І далі в будь-якому компоненті можна дістати цей клієнт через `useNuxtApp().$api`.

головний нюанс, якщо plugin звертається до window, document або будь-чого браузерного — він ОБОВ'ЯЗКОВО має мати суфікс `.client.ts`. Інакше він спробує виконатись на сервері при SSR і все впаде."

---

### B11. "Коли використовувати ClientOnly?"

**Відповідь:**

"ClientOnly — це обгортка в Nuxt: 'цей шматок не рендери на сервері взагалі, покажи його тільки в браузері'. На сервері замість нього показується заглушка.

Коли це потрібно:

Перше — компонент використовує щось що існує тільки в браузері. Наприклад графіки, карти, live chat віджет — всі ці бібліотеки звертаються до document або canvas, а на сервері їх нема.

Друге — компонент залежить від даних які є тільки в браузері. Наприклад, щось з localStorage або cookies які не передаються при серверному рендері.

Третє — контент який гарантовано буде різним. Наприклад, live odds які оновлюються кожну секунду — нема сенсу рендерити їх на сервері, все одно через мить будуть інші.

Якщо обернути в ClientOnly текст або заголовки — вони не потраплять в HTML який бачить Google. SEO буде нуль.

І не використовувати як 'ліки' від hydration mismatch не розуміючи причину. Якщо є mismatch — треба зрозуміти чому і пофіксити. ClientOnly — це костиль якщо застосовувати його бездумно.

Важливий момент: коли використовуєш ClientOnly — завжди давай fallback. Тобто поки в браузері компонент ще не з'явився — на його місці має бути сіра заглушка правильного розміру. Інакше коли компонент з'явиться — весь контент нижче стрибне вниз, і це зіпсує CLS."

---

### B13. "Як обробляються помилки в Nuxt? Що таке error boundaries?"

**Відповідь:**

"В Nuxt є три рівні обробки помилок — від локального до глобального.

Перший — обгортка навколо конкретного шматка інтерфейсу. Називається `NuxtErrorBoundary`. Ідея проста: якщо щось всередині зламалось — показати замість нього повідомлення про помилку, а не крашити весь додаток. Наприклад, обертаю касу в таку обгортку. Якщо каса впала через якийсь баг — решта сайту продовжує працювати, а замість каси user бачить 'виникла помилка, зверніться в підтримку' з кнопкою 'спробувати знову'.

Це важливо для продукту — якщо зламався один блок на сторінці, це не привід показувати білий екран замість всього сайту. Користувач має бачити все інше і розуміти що проблема локальна.

Другий рівень — глобальна сторінка помилки. Файл `error.vue` в корені проєкту. Якщо щось пішло не так — 404 сторінка не знайдена, або 500 сервер впав — Nuxt показує цю сторінку замість всього інтерфейсу. Там я можу показати красиву сторінку з поясненням і кнопкою 'на головну'.

Третій — коли я сама хочу кинути помилку з коду. Наприклад, user зайшов на сторінку гри яка не існує. Я перевіряю: гра не знайдена — кидаю помилку з кодом 404. Nuxt підхопить і покаже відповідну сторінку.

Головний принцип: помилка в одній частині не повинна вбивати все інше. Error boundary ізолює проблему — решта працює."

---

### B13b. "Що таке Suspense і Teleport у Vue 3? Коли їх використовують?"

**Відповідь:**

"Це два вбудовані компоненти у Vue 3, кожен вирішує свою задачу.

**Teleport** — переміщує DOM-елемент в інше місце на сторінці, не змінюючи логічну структуру компонентів.

Простий приклад: модальне вікно. Логічно модалка належить компоненту який її відкриває — наприклад кнопка 'поповнити баланс' в касі. Але фізично в DOM модалка має бути в body — щоб вона коректно показувалась поверх усього, без проблем з z-index і overflow.

Teleport робить саме це: в коді модалка лежить в компоненті каси, але рендериться в body. Те саме для тултіпів, дропдаунів, нотифікацій — все що має 'вискочити' поверх інтерфейсу.

**Suspense** — показує заглушку поки асинхронний компонент або дані ще не завантажились.

Уявіть: є компонент який робить async запит в setup — тобто він не може відрендеритись поки дані не прийшли. Suspense обертає такий компонент і каже: 'поки він не готовий — покажи ось цей лоадер, а коли готовий — покажи його'.

В Nuxt Suspense використовується під капотом автоматично — коли ви робите useAsyncData, Nuxt сам обробляє стан 'loading'. Але явно Suspense буває корисний коли у вас кілька незалежних async-блоків на сторінці і ви хочете кожному дати свій лоадер.

Коротко: Teleport — 'рендери в іншому місці DOM'. Suspense — 'покажи заглушку поки не готово'."

---

### C1. "Чому strict mode в TypeScript важливий?"

**Відповідь:**

"Strict mode змушує TypeScript бути максимально суворим. Головне що він дає: не дозволяє працювати зі значенням яке може бути null або undefined без явної перевірки. Тобто якщо змінна може бути порожньою — ми ЗОБОВ'ЯЗАНА це перевірити в коді, інакше проєкт не збілдиться.

Чому це критично саме для SSR: якщо на сервері звернутись до undefined — весь запит впаде з помилкою 500 і user побачить білу сторінку. Strict mode ловить таке ще до деплою, на етапі написання коду.

Мій стандарт: `strict: true` завжди ввімкнений. Без цього TypeScript — це декорація яка нічого не захищає."

---

### C2. "Як використовуєш generics у composables?"

**Відповідь:**

"Generics дозволяють написати один composable який працює з будь-яким типом даних, і при цьому TypeScript точно знає що всередині.

Наприклад, `useApi<T>` — один composable для будь-якого API-запиту. Коли я викликаю `useApi<Game[]>('/api/games')` — TypeScript автоматично розуміє що data — це масив ігор, і дає автопідказки по полях гри. Якщо викликаю `useApi<User>('/api/user')` — data стає типом User. Код один і той самий, типізація підставляється автоматично.

Це економить час: не потрібно писати окремий composable для кожного ендпоінту. Один generic composable покриває все, і при цьому нуль any в коді."

---

### C4. "Яка різниця між unknown і any? Чому unknown кращий?"

**Відповідь:**

"Різниця проста. якщо тип `any` TypeScript повністю вимикається для цієї змінної — дозволяє звертатись до будь-яких полів, викликати будь-які методи, і не попередить якщо щось неправильно. А в runtime ми отримаємо помилку.

Якщо тип `unknown` — TypeScript не дозволить нічого зробити з цією змінною поки я не напишу перевірку. Не можна звернутись до полів, не можна викликати методи — спочатку перевір що це за тип, і тільки тоді працюй.

на практиці це важоиво в catch-блок. Помилка може бути чим завгодно — не обов'язково Error, може бути string, може бути об'єкт, може бути null. Тому `catch (e: unknown)` — і далі перевіряю що це перед тим як звертатись до e.message.

Те саме з API-відповідями до валідації і з WebSocket повідомленнями — це дані ззовні, я не контролюю їхній формат, тому спочатку перевіряю, потім використовую.

any в продуктовому коді не використовую ніколи. Якщо бачу any на код-рев'ю — прошу замінити на правильний тип або на unknown з перевіркою."

---

### C4b. "Яка різниця між type і interface? Коли що використовуєш?"

**Відповідь:**

"На 90% вони взаємозамінні. Але є різниця.

`interface` — для опису форми об'єктів. Можна розширювати через extends, і головне — можна дописувати пізніше. Якщо я оголосила interface в одному файлі, а в іншому файлі оголосила його ще раз з тими ж ім'ям — TypeScript зіллє їх разом. Це називається declaration merging. Корисно для бібліотек, але в продуктовому коді може створити плутанину.

`type` — більш гнучкий. Можна описувати не тільки об'єкти, а й union-типи, перетини, умовні типи, примітиви. Не можна дописувати пізніше — один раз оголосив і все.

- `interface` — коли описую форму об'єкта: props компонента, відповідь API, модель даних. Тому що interface краще читається для об'єктів і дає зрозуміліші помилки.
- `type` — коли потрібен union (кілька варіантів), або коли це не об'єкт. Наприклад: `type PaymentStatus = 'success' | 'pending' | 'failed'` — тут interface не підходить.

---

### C5. "Як ти типізуєш API-відповіді?"

**Відповідь:**

"Я розділяю на два рівні: те що прийшло з API, і те з чим працює фронтенд. Між ними — функція-перетворювач.

Перший рівень — DTO, тобто точна форма того що повертає сервер. Як бекенд назвав поля — так і описую: `provider_id`, `is_active`, `created_at` як рядок. Нічого не перейменовую, нічого не перетворюю. Просто чесний опис формату.

Другий рівень — UI модель. Це те з чим зручно працювати на фронтенді: camelCase назви полів, Date замість рядка, замість `provider_id` — вже готовий об'єкт провайдера, замість null в полі rtp — значення за замовчуванням.

Між ними — mapper. Одна функція яка перетворює DTO в UI модель. Зробив `created_at` → `createdAt`, розрезолвив `provider_id` в об'єкт, підставив fallback для null-полів.

це для того, що якщо завтра бекенд перейменує поле або змінить формат — я правлю один mapper в одному місці. А не 50 компонентів які звертаються до цих даних. Компоненти взагалі не знають як виглядає відповідь API — вони працюють тільки з UI моделлю."

---

### C6. "Що таке discriminated unions? Де використовуєш?"

**Відповідь:**

"Це коли є об'єкт який може мати кілька різних форм, і одне спільне поле визначає яка саме форма зараз.

Найпростіший приклад з практики — результат платежу. Платіж може завершитись по-різному: успіх, в обробці, помилка, або потрібна верифікація. І для кожного статусу є різний набір даних. Успіх — має номер транзакції і суму. Помилка — має код помилки і повідомлення. Верифікація — має рівень який потрібен.

Якщо це описати як один тип зі всіма полями optional — це хаос, бо непонятно які поля в якому випадку є. А якщо описати як discriminated union — TypeScript сам підказує: 'якщо статус success — у тебе є transactionId і amount, а message тут немає'. Перевірив статус — і TypeScript знає яка форма об'єкта і які поля доступні.

Де ще використовую: статуси KYC верифікації (pending, approved, rejected — кожен з різними полями), типи WebSocket повідомлень (кожен тип має різну структуру payload), різні варіанти API відповідей.

Чому це краще ніж просто `status: string` і купа optional полів — TypeScript підкаже якщо я забула обробити якийсь варіант. Не скомпілюється поки не покрию всі можливі статуси."

---

### C8. "Навіщо розділяти DTO і UI model? Чому не працювати з тим що прийшло від API напряму?"

**Відповідь:**

"Три причини.

Перша — захист від змін на бекенді. Якщо бекенд перейменував поле або змінив формат — а мої компоненти працюють напряму з тим що прийшло — зламається все що це поле використовує. А якщо між API і компонентами стоїть перетворювач — я правлю одне місце і все працює далі.

Друга — бекенд і фронтенд мають різні потреби. API повертає дату як рядок в ISO форматі — а мені для відображення потрібен об'єкт Date. API повертає provider_id числом — а мені в компоненті потрібен об'єкт провайдера з іменем і логотипом. Ці перетворення мають відбуватись в одному місці, а не в кожному компоненті окремо.

Третя — безпека. Дані від API — це зовнішній світ. Я не контролюю що звідти прийде. Може прийти null де не очікував, може змінитись формат. Перетворювач — це межа де я перевіряю і нормалізую дані. Після нього — все безпечне і передбачуване.

Моє правило: компонент ніколи не бачить 'сирих' даних від API. Він працює тільки з підготовленою UI моделлю. Сирі дані живуть тільки в composable який робить запит."

---

### C9. "TypeScript ж тільки на етапі компіляції працює. Як захищаєшся від неправильних даних в runtime?"

_(також: "Як ти валідуєш дані від API?" або "Навіщо Zod/Yup якщо є TypeScript?" або "Що буде якщо бекенд поверне не ту структуру?")_

**Відповідь:**

"Правильне зауваження. TypeScript зникає після білда — в продакшні працює звичайний JavaScript без жодних типів. Якщо API раптом поверне не той формат — TypeScript ніяк не допоможе, і додаток може зламатись.

Тому я розділяю: всередині додатку — TypeScript достатньо. Composables, компоненти, утіліти — тут я контролюю дані і типи працюють на етапі написання коду.

Але на межі — там де приходять дані ззовні — потрібна перевірка в реальному часі. Це API-відповіді, введення користувача у формах, WebSocket повідомлення, параметри з URL. Тут я використовую бібліотеку типу Zod або Yup: описую схему того що очікую, і валідую дані коли вони приходять. Якщо формат неправильний — отримую чітку помилку замість непередбачуваної поведінки десь глибоко в коді.

Трейдофф: валідація коштує часу виконання. Для більшості API-запитів це непомітно. Але якщо дані приходять кожну секунду через WebSocket — валідувати кожне повідомлення може бути накладно. В такому випадку або валідую тільки вибірково, або довіряю контракту з бекендом і покладаюсь на типізацію."

---

### E1-E14 (SEO block — compact answers)

### E3. "Як організувати sitemap для 5+ доменів?"

_(також: "Як Google дізнається які сторінки у вас є?" або "Як генеруєте sitemap динамічно?")_

**Відповідь:**

"Sitemap — це XML-файл зі списком всіх сторінок сайту які мають бути в пошуку. Пошуковий бот читає цей файл і знає куди заходити. Без нього Google може не знайти всі сторінки, особливо якщо на них немає посилань.

Для 5 доменів — кожен домен має свій окремий sitemap. Не один спільний, а п'ять різних. Тому що сторінки на domain-ua.com і domain-uk.com — це різний контент для різних країн.

Як це працює технічно: коли бот запитує sitemap.xml — мій сервер дивиться з якого домену прийшов запит, витягує список сторінок саме для цього домену, і генерує XML з правильними URL-адресами.

Кілька важливих моментів:

Перше — в robots.txt кожного домену має бути прописано де лежить його sitemap. Без цього бот може не знайти його.

Друге — дата останнього оновлення кожної сторінки має бути реальною. Не поточна дата, а дата коли контент дійсно змінювався. Якщо ставити сьогоднішню дату на все підряд — Google перестає довіряти цьому полю.

Третє — якщо сторінок більше 50 тисяч — потрібно розбити на кілька файлів і зробити sitemap index, який посилається на кожен файл.

Четверте — кожен sitemap реєструю окремо в Google Search Console. Це дає видимість скільки сторінок подано, скільки проіндексовано, і чи є помилки."

---

### E5. "Коли ставиш noindex і навіщо?"

_(також: "Які сторінки не повинні потрапляти в пошук?")_

**Відповідь:**

"Noindex — це мета-тег який забороняє Google показувати цю сторінку в результатах пошуку. Сторінка продовжує працювати для користувачів, але в пошуку її не буде.

Коли ставлю:

— Сторінки пагінації — друга, третя, десята сторінка списку. Вони не несуть унікального контенту, і якщо Google їх всі проіндексує — буде купа thin content в індексі.

— Результати пошуку і фільтрації — якщо кожна комбінація фільтрів генерує свій URL, це мільйони сторінок без реального контенту. Google це не подобається.

— Staging і тестове оточення — щоб тестові сторінки випадково не потрапили в пошук.

— Кабінет, адмінка, каса — це authenticated зони, вони не повинні бути в пошуку. Noindex тут як додатковий захист.

— Thank you сторінки, підтвердження — вони не потрібні в пошуку.

Важливий нюанс: я ставлю `noindex, follow`. Follow означає що Google не індексує саму сторінку, але продовжує переходити по посиланнях на ній. Тобто посилання на цій сторінці все ще працюють для SEO."

---

### E6. "Що таке structured data / Schema.org і як використовуєш для iGaming?"

_(також: "Що таке JSON-LD?" або "Як отримати rich snippets в пошуку?")_

**Відповідь:**

"Structured data — це спеціальна розмітка в коді сторінки яка допомагає Google краще зрозуміти що на цій сторінці. Без неї Google бачить просто текст і HTML. З нею — розуміє: це сайт такої-то компанії, ось FAQ, ось навігація.

Формат — JSON-LD. Це просто JSON-об'єкт який вставляється в head сторінки в тегу script. Google його читає і може на основі нього показати розширений результат в пошуку — наприклад FAQ прямо в результатах, або хлібні крихти замість голого URL.

Які типи я б використовувала для iGaming:

— Organization — інформація про компанію, номер ліцензії. Це показує легітимність.
— WebSite — опис сайту і можливість пошуку по ньому прямо з Google.
— FAQPage — сторінка з частими питаннями. Google може показати відповіді прямо в пошуку — це збільшує площу в видачі.
— BreadcrumbList — хлібні крихти, навігаційний ланцюжок типу Головна → Слоти → Конкретна гра. Google показує це замість голого URL.

Важливий момент для gambling: не використовувати типи Game або Offer для азартного контенту. Google суворо ставиться до gambling і може покарати за спробу отримати rich snippets на казино-контенті. Тому тільки загальні організаційні типи.

Перевіряю правильність через Google Rich Results Test — вставляєш URL, бачиш чи розпізнає Google твою розмітку і чи є помилки."

---

### E9. "Яка різниця між crawling і indexing?"

**Відповідь:**

"Це два окремих етапи. Crawling — бот зайшов на сторінку і прочитав її. Indexing — бот вирішив додати її в пошук.

Одне не означає інше. Бот може зайти на сторінку, прочитати — але не додати в пошук. Наприклад, якщо контент дублюється або стоїть noindex. І навпаки — robots.txt може блокувати crawling, але якщо на цю сторінку хтось посилається ззовні, Google може показати URL в пошуку навіть без прочитання контенту.

Для mirror domains це означає: кожен домен має свій crawl budget — це скільки сторінок бот готовий обійти за одну сесію. Якщо внутрішня перелінковка зроблена погано — бот не дійде до важливих сторінок і вони не потраплять в індекс навіть якщо noindex ніде нема."

---

### G1. "Як ти використовуєш Sentry в роботі?"

_(також: "Як ти моніториш помилки на продакшні?" або "Як пріоритизуєш баги?")_

**Відповідь:**

"Як у мене налаштовано: при кожному деплої я завантажую source maps — це дозволяє бачити помилку в оригінальному коді, а не в мініфікованому нечитабельному JS. Кожен деплой отримує свій тег версії — тому якщо після деплою з'явились нові помилки, одразу видно що це саме цей реліз зламав.

Мій щоденний процес: відкриваю Sentry, сортую помилки не по кількості повторень, а по кількості користувачів яких зачепило. Бо одна помилка може спрацьовувати 10 000 разів в одного user — це не критично. А помилка яка зачіпає 500 різних людей — це проблема. Дивлюсь які нові помилки з'явились з останнього деплою, і вирішую: це критичне — фіксити зараз, це шум — ігнорити, це реальне але не горить — в бекліг.

Якщо після деплою різко зросла кількість помилок — одразу дивлюсь на яку версію це прив'язано, і розумію що конкретно зламалось.

Також додаю кастомні теги: домен, гео, тип сторінки. Для mirror domains це обов'язково — потрібно розуміти чи проблема на одному дзеркалі чи на всіх.

По алертах: якщо кількість помилок зросла вдвічі від норми — мені прилітає повідомлення в Slack. Якщо нова помилка зачепила більше 100 users за годину — теж одразу нотифікація. Для каси ставлю окремий алерт — бо помилка в платежах це завжди найвищий пріоритет, бо там мова про гроші."

---

### G8. "Що ти робиш коли на продакшні щось зламалось? Який у тебе процес?"

_(також: "Розкажи про incident response" або "Як реагуєш на production bug?")_

**Відповідь:**

"У мене чотири кроки: виявити, оцінити, пофіксити, не допустити повторення.

Перший — виявити. Або прилітає алерт від Sentry, або QA повідомляє, або user написав в підтримку. Чим швидше дізнаюсь — тим менше людей зачепить.

Другий — оцінити масштаб. Скільки людей зачеплено? Що саме зламалось — каса не працює, сторінка не відкривається, або щось косметичне? Який деплой це спричинив? На основі цього вирішую: якщо каса не працює або SEO зламане — це критичне, фікшу прямо зараз. Якщо кнопка на одній сторінці не того кольору — це в наступний спринт.

Третій — пофіксити. Якщо критичне — або відкочую деплой до попередньої версії, або роблю хотфікс і деплою терміново. Після фіксу перевіряю на staging, деплою, і моніторю ще пів години щоб переконатись що проблема зникла і нових не з'явилось.

Четвертий — не допустити повторення. Для серйозних інцидентів роблю розбір: що трапилось, чому не зловили раніше на тестах або в CI, і що додати щоб наступного разу це зловилось автоматично. Зазвичай це або новий тест, або новий алерт, або перевірка в CI.

Реальний приклад: middleware для мета-тегів зламав canonical на одному дзеркалі. Виявила через алерт в Search Console — 30% сторінок зникло з індексу. Через git blame знайшла який коміт це зробив, написала хотфікс, задеплоїла за 2 години. Після цього додала CI тест який перевіряє що на топових сторінках canonical правильний — щоб більше таке не пролізло."

---

### H1. "Як працює middleware в Express? Що важливо знати про порядок і обробку помилок?"

_(також: "Як обробляєш помилки на сервері?" або "Що буде якщо в SSR щось впаде?")_

**Відповідь:**

"Middleware — це конвеєр функцій. Запит проходить через них по черзі: логування → визначення домену → перевірка кешу → SSR рендер → обробка помилок.

Для SSR-сервісу конвеєр виглядає приблизно так: спочатку присвоюємо запиту унікальний ID для логування, потім визначаємо з якого домену прийшов запит, потім перевіряємо чи є ця сторінка в кеші — якщо є, одразу віддаємо і далі не йдемо. Якщо нема — рендеримо HTML. І в самому кінці — обробник помилок.

Обробник помилок — завжди останній. Express розпізнає його по тому що в нього чотири аргументи замість трьох (err — сама помилка, req — запит, res — відповідь, next — передай далі). Якщо де-небудь раніше в ланцюжку щось впало — запит потрапляє сюди. Тут я вирішую що показати user: якщо SSR не встиг відрендерити за відведений час — повертаю SPA-оболонку як запасний варіант. Якщо зовсім незрозуміла помилка — повертаю красиву сторінку 'щось пішло не так'.

Важлива пастка: якщо помилка виникає в асинхронному коді — наприклад запит до API впав — Express сам її НЕ зловить. Потрібно або обернути в try/catch і вручну передати помилку далі, або написати маленьку обгортку яка ловить відхилений промис і передає в обробник помилок автоматично.

Головне правило: один зламаний запит не повинен повалити весь сервер. Кожна помилка — ловиться, логується, user отримує хоч щось осмислене замість білого екрану."

---

### H2. "Як event loop впливає на SSR performance?"

_(також: "Чому SSR може бути повільним?" або "Що блокує сервер?")_

**Відповідь:**

"Тут ключове розуміння — JavaScript і на сервері працює в одному потоці. Тобто поки сервер рендерить сторінку для одного користувача — всі інші стоять у черзі і чекають. Рендер однієї сторінки — це 100-200 мілісекунд. Звучить мало, але прийшло 50 людей одночасно — і останній чекає 10 секунд. Для iGaming це неприпустимо.

Тому перше і найголовніше — кешування. Якщо 90% запитів віддаються з кешу і взагалі не доходять до рендеру — проблеми по суті немає. Event loop вільний.

Друге — таймаут на рендер. Якщо сторінка не відрендерилась за 3 секунди — я обриваю і віддаю запасний варіант. Або SPA-оболонку яка дорендериться вже в браузері, або стару закешовану версію. Головне — користувач не чекає нескінченно.

Третє — кілька копій сервісу за балансувальником. Навантаження зросло — додали копії.

І четверте — streaming SSR. Не чекати поки вся сторінка готова, а починати віддавати по частинах. Користувач вже бачить шапку і навігацію, поки тіло ще рендериться.

А по моніторингу — дивлюсь не на середній час відповіді, а на найповільніші запити. Якщо вони почали рости — значить або кеш перестав працювати, або сторінки стали важчими, і потрібно розбиратись."

---

### H3. "Які заголовки кешування використовуєш і для чого?"

_(також: "Що таке Cache-Control?" або "Як керуєш кешем на рівні HTTP?")_

**Відповідь:**

"Cache-Control — це заголовок який сервер відправляє разом зі сторінкою і каже браузеру та CDN: скільки часу цю відповідь можна тримати і не запитувати заново.

Я розділяю стратегію по типах контенту.

Публічні сторінки — лендінги, каталог ігор — ставлю `public, max-age=300, stale-while-revalidate=3600`. Це означає: п'ять хвилин сторінка свіжа, CDN віддає її миттєво. Після п'яти хвилин CDN все одно продовжує віддавати стару версію, але паралельно в фоні запитує нову у сервера. Користувач не чекає ніколи.

Авторизовані зони — кабінет, каса, баланс — `private, no-store`. Це персональні дані, CDN взагалі не повинен їх бачити, і браузер не повинен тримати в кеші. Інакше один користувач може побачити дані іншого.

Юридичні сторінки — правила, T&C — кешую довше, на годину. Вони рідко змінюються.

Статичні файли — JS, CSS, картинки — кешую на рік. Вони мають хеш в назві файлу, тому коли код змінюється — змінюється назва файлу, і браузер автоматично запитує новий. Стару версію ніхто не отримає.

Для mirror domains єдиний нюанс — cache key обов'язково включає домен. Щоб CDN не віддав контент українського дзеркала британському користувачу."

---

### I1. "Яка специфіка high-load iGaming продукту з точки зору фронтенду?"

_(також: "Чим iGaming відрізняється від звичайного B2C?" або "Які технічні виклики в gambling-продуктах?")_

**Відповідь:**

"П'ять речей які роблять iGaming складнішим за звичайний B2C:

Перше — стрибки трафіку. Почався великий матч або запустили промо-акцію — і за хвилини трафік зростає в 3-10 разів. Без кешу і масштабування сервер просто ляже. Тому CDN і кеш — це не оптимізація, це необхідність для виживання.

Друге — все в реальному часі. Коефіцієнти ставок, баланс, стан гри — оновлюються через WebSocket постійно. Тисячі з'єднань одночасно. На фронтенді потрібно обмежувати частоту оновлень інтерфейсу, бо якщо перерендерювати кожну мілісекунду — браузер не потягне.

Третє — мова про гроші. Баг в касі — це не 'кнопка не того кольору'. Це дублікат транзакції, неправильний баланс, або фінансові втрати. Тут нульова толерантність до помилок. Кожен edge case повинен бути покритий.

Четверте — регуляції. Різні країни — різні ліцензії, різні вимоги. KYC верифікація обов'язкова. Перевірка віку обов'язкова. Ліміти на відповідальну гру обов'язкові. Не можна випустити продукт з відомими прогалинами — це юридичний ризик для компанії.

П'яте — мультигео. Один і той самий продукт працює в різних країнах: різні домени, мови, валюти, платіжні провайдери, набір доступних ігор, юридичні вимоги. І все це один codebase який розрізняє що показувати через конфігурацію."

---

### I5. Mirror domains — навіщо?

_(також: "Навіщо кілька доменів для одного продукту?" або "Чому не один домен з підпапками для різних гео?" або "Яка різниця між мультидоменом і мультилокаллю?")_

"Дзеркала в iGaming — це не просто копії сайту, це бізнес-необхідність.

Головна причина — юридична. Кожна країна де ти працюєш вимагає свою ліцензію, і часто — окремий домен під цю ліцензію. Тобто domain-ua.com працює під українською ліцензією, domain-uk.com — під британською. Це не вибір архітектора, це вимога регулятора.

Друга причина — SEO. Google індексує кожен домен окремо для свого гео. Українські users шукають і знаходять domain-ua.com, британські — domain-uk.com. Без окремих доменів ти конкуруєш сам з собою в пошуку.

Третя — ізоляція ризиків. Якщо один домен заблокували або він потрапив під санкції в якійсь юрисдикції — решта продовжують працювати. Не кладеш весь бізнес через одну країну.

І четверта — контент реально різний. Різні ігри доступні в різних гео через ліцензійні обмеження провайдерів, різні платіжні методи, різна валюта, різні промо.

Технічно при цьому — один codebase. Не п'ять окремих проєктів. Один SSR-сервіс який по Host header розуміє яке дзеркало перед ним і підтягує відповідний конфіг. Hreflang зв'язує дзеркала між собою для Google, canonical self-referencing на кожному. І моніторинг обов'язково per-domain — бо якщо один домен деградує, в загальній метриці це потоне."

---

### I7. Feature flags в iGaming?

_(також: "Як ви випускаєте нові фічі поступово?" або "Як вмикаєте функціональність для конкретного гео?" або "Як робите A/B тести?")_

"В iGaming feature flags — це не просто зручність, це необхідність. І ось чому.

Перше — регуляції. В різних країнах різні вимоги. Наприклад, popup з нагадуванням про відповідальну гру обов'язковий для Великобританії, але не потрібний в інших гео. Бонуси можуть бути заборонені в одній юрисдикції і дозволені в іншій. Це один codebase — і feature flag визначає що показувати де.

Друге — безпечний випуск. Новий cashier flow не вмикаєш одразу на всіх. Спочатку 10% користувачів, дивишся метрики, якщо все добре — розширюєш. Якщо щось не так — вимикаєш без деплою, одним перемикачем.

Третє — kill switch. Платіжний провайдер почав повертати помилки — вимикаєш його runtime, без нового релізу. Для каси це критично, бо кожна хвилина простою — це втрачені гроші.

По реалізації: composable `useFeatureFlag` який повертає стан прапорця. В SSR-зоні прапорці визначаються на сервері, щоб HTML одразу був правильний. В SPA-зонах — toggle без перезавантаження.

І одна важлива пастка для SSR з кешуванням: якщо сторінка кешується — feature flag має бути частиною ключа кешу. Інакше один користувач з увімкненою фічею побачить закешовану сторінку де фіча вимкнена."

---

### I8. Responsible gaming — frontend?

"Regulatory requirement в більшості юрисдикцій:

- **Self-exclusion** — user може заблокувати свій аккаунт на період. Frontend: показати попередження, не дозволити bypass
- **Deposit limits** — user встановлює max deposit per day/week/month. Frontend: block transaction якщо limit reached
- **Session time reminders** — popup кожні N хвилин: 'ви граєте X годин'
- **Reality check** — показати win/loss statistics під час session
- **Cool-off period** — після великого виграшу/програшу запропонувати паузу
- **Age verification gate** — не показувати контент до верифікації віку
- **Problem gambling links** — обов'язкові посилання на helpline в footer

**Технічно:** це не 'nice to have' UI — це compliance requirement. Missing = fine або втрата ліцензії. Тому тести на ці flows обов'язкові."

---

### J1. Як тестуєте composables?

_(також: "Як ви підходите до unit-тестів у Vue 3?" або "Що саме покриваєте тестами?")_

"Composables — це звичайні функції, тому і тестуються як звичайні функції. Ніякої магії.

Беру Vitest, мокаю API-шар щоб тест не ходив на реальний сервер, викликаю composable і перевіряю що він повертає правильні дані і правильні стани.

Наприклад, `usePaymentMethods` — я передаю ідентифікатор бренду, перевіряю що спочатку loading дорівнює true, після завершення запиту — false, і дані прийшли. Далі — що буде якщо API поверне помилку: composable не впаде, а поверне порожній масив і стан помилки. І що буде якщо бренд зміниться — composable має перезапитати дані автоматично.

Тобто для кожного composable три речі: нормальний сценарій, помилка, і реактивність — що зміна вхідних даних тригерить оновлення.

Що я не покриваю тестами — верстку і стилі. Це краще перевіряти візуально. А от бізнес-логіку, стани завантаження, обробку помилок — обов'язково."

---

### J5. CI/CD pipeline — етапи?

_(також: "Що відбувається від PR до продакшну?" або "Як ви деплоїте?" або "Як запобігаєте поламаному коду в production?")_

"Я ділю pipeline на дві фази: до мержу і після.

До мержу — це захист. Коли розробник створює PR, автоматично запускаються: лінтер, перевірка типів, юніт-тести, білд щоб переконатись що проєкт збирається, і перевірка розміру бандла щоб хтось випадково не додав бібліотеку яка подвоїть вагу. Для SEO-критичного продукту я б додав ще Lighthouse CI — щоб PR не мержився якщо performance score впав нижче порогу. Це все ловить проблеми до того як вони потрапляють в основну гілку.

Після мержу — деплой. Збираємо продакшн-білд, деплоїмо на staging, прогоняємо smoke-тести: критичні сторінки повертають 200, canonical на місці, noindex не з'явився де не треба. Якщо все ок — деплоїмо в продакшн. Після деплою — ще один прогін тих самих перевірок вже на живому сервері, і 30 хвилин спостереження за Sentry — чи не з'явились нові помилки.

Для п'яти дзеркал — smoke-тести обов'язково на кожному домені окремо. Не тільки на одному. Бо проблема може бути специфічна для конкретного гео — наприклад зламаний hreflang тільки для одного locale.

Якщо після деплою Sentry показує різкий ріст помилок — відкочуємо. Або автоматично, або одним кліком. Краще повернутись до робочої версії за дві хвилини ніж годину дебажити на живому трафіку."

---

### J6. Rollback strategy?

_(також: "Що ви робите коли деплой зламав продакшн?" або "Як швидко можете відкотити?")_

"У мене три варіанти, і який обирати — залежить від того що саме зламалось.

Якщо критичне — сервер повертає 500, каса не працює, або Google почав деіндексувати сторінки — миттєвий відкат до попередньої версії. В контейнерному середовищі це перемикання трафіку на попередній pod, займає менше двох хвилин. Тут не дебажимо на живому — спочатку повертаємо робочий стан, потім розбираємось.

Якщо проблема в конкретній новій фічі, а все інше працює — вимикаю feature flag. Жодного деплою, миттєво. Фіча зникла, решта продовжує працювати. Тому я і люблю випускати нове під прапорцями.

Якщо ситуація складніша — наприклад зачеплено кілька комітів і потрібно відкотити частково — роблю git revert, проганяю через CI і деплою. Це 10-15 хвилин, але зате точково і контрольовано.

Головне правило: в production інциденті спочатку повертаємо робочий стан, потім шукаємо причину. Не навпаки."

---

### K2. SEO-safe архітектура для blog/landing в Nuxt?

_(також: "Як побудувати блог щоб він добре індексувався?" або "Як організувати лендінги для різних гео?")_

"Тут я б розділив на дві частини — блог і лендінги, бо у них різна стратегія рендерингу.

Блог — це контент який змінюється рідко. Написали статтю — вона лежить. Тому тут SSG: сторінки генеруються на етапі білда, кешуються на CDN, працюють миттєво. Список постів — одна сторінка, кожен пост — окрема сторінка по slug. Якщо постів стає багато і білд затягується — переходжу на ISR-подібний підхід, де сторінка генерується при першому запиті і потім кешується.

Лендінги — інша історія. Вони можуть відрізнятись по гео: різні промо, різна мова, різні пропозиції. Тому тут SSR з кешуванням. Контент прийшов з CMS, сервер зрендерив правильну версію для конкретного дзеркала, CDN закешував.

По SEO на кожній сторінці обов'язково: title і description через useHead, canonical, Open Graph теги для соцмереж, structured data в JSON-LD — для блогу це BlogPosting, для лендінгів WebPage. Плюс хлібні крихти і внутрішня перелінковка між пов'язаним контентом — це допомагає Google розуміти структуру сайту.

І окремо — як контент потрапляє на сайт. Маркетинг-команда не повинна чекати розробника щоб опублікувати статтю. Тому CMS — або Decap який працює через Git, або щось типу Strapi. Маркетолог натиснув 'опублікувати', прилітає webhook, кеш інвалідується, і нова версія одразу доступна."

---

### L1. Конфлікт з backend — як вирішували?

_(також: "Як ви вирішуєте технічні розбіжності з колегами?" або "Розкажіть про ситуацію коли ви не погодились з рішенням")_

"В Prematch backend запропонував отримувати статус KYC верифікації через polling кожні 5 секунд. Я побачила дві проблеми: зайве навантаження на сервер і користувач чекає до 5 секунд після того як верифікація вже пройшла.

Я не сказала 'це погано'. Я прийшла з конкретикою: ось скільки запитів це створить при N користувачах одночасно, ось наскільки це погіршить UX. І запропонувала альтернативу — push-нотифікацію коли статус змінився, а polling як запасний варіант з довшим інтервалом.

Домовились на гібридний підхід. Всі задоволені, бо рішення прийняте через аргументи, а не через те хто голосніше."

---

### L4. Менторинг — як проводите?

"В NetGame менторила junior і mid-level розробників. Підхід:

1. **Onboarding** — перший тиждень: pair programming на реальних задачах, не документація. Показую codebase 'зсередини', пояснюю WHY, не тільки HOW.

2. **Code review як навчання** — не просто 'виправ'. А 'тут проблема X бо Y, кращий підхід Z, ось чому'. Посилання на docs.

3. **Поступове ускладнення** — починаємо з ізольованих UI tasks, потім composables, потім full feature з API integration.

4. **1-on-1** — щотижня 30 хв: що вивчив, що блокує, що хоче зробити далі. Не микроменеджмент — а support.

5. **Дозволяю помилятись** — якщо помилка не critical, дозволяю зробити, побачити наслідки, виправити. Так краще запам'ятовується.

**Маркер успіху:** через 2-3 місяці інженер самостійно бере feature від початку до PR без моїх підказок."

---

### L6. Production bug — процес реакції?

_(також: "Що ви робите коли на продакшні щось зламалось?" або "Як реагуєте на інциденти?")_

"Перше — зрозуміти наскільки серйозно. Відкриваю Sentry, дивлюсь скільки людей зачепило і що саме зламалось. Каса не працює — це одне. Кнопка не того кольору — зовсім інше.

Якщо критичне — гроші, compliance, SEO-деіндексація — відкочую одразу, не дебажу на живому трафіку. Спочатку повернути робочий стан, потім розбиратись.

Далі шукаю причину. Sentry покаже stack trace і до якого релізу прив'язана помилка. Git log покаже що змінилось. Зазвичай цього достатньо щоб локалізувати.

Фікшу мінімально — тільки те що зламалось, ніяких рефакторингів заодно. Перевіряю на staging, деплою, і ще пів години спостерігаю що нових проблем немає.

Для серйозних інцидентів роблю розбір: що трапилось, чому не зловили раніше, і що додати щоб наступного разу це спіймалось автоматично — новий тест, новий алерт, перевірка в CI."

---

### L7. Як комунікуєте ризики нетехнічним стейкхолдерам?

"Правило: НІКОЛИ не говорити 'це технічно складно'. Завжди переводити в бізнес-мову.

**Замість:** 'SSR cache invalidation складна і може зламатись'
**Кажу:** 'Якщо ми не інвестуємо 3 дні в cache strategy, users будуть бачити застарілий контент до 1 години після оновлення промо. Для flash promotions це = втрачені конверсії'

**Замість:** 'Цей feature потребує рефакторингу'
**Кажу:** 'Зараз додавання нового payment provider займає 2-3 тижні. Якщо інвестуємо 1 sprint в архітектуру — зменшимо до 3-5 днів. Окупиться після 2-го провайдера.'

**Формат:**

1. Проблема (бізнес-мовою)
2. Impact (що втрачаємо якщо не вирішимо)
3. Пропозиція (конкретна, з timeline)
4. Trade-off (що отримуємо vs що коштує)"

---

## 10. Класичні CS / JavaScript питання та модельні відповіді

### Що таке `this` в JavaScript?

**Питання:** "Поясніть що таке `this` в JavaScript."

**Відповідь:**

"`this` визначається тим як функція викликана, а не де написана. Це головне що треба розуміти.

Якщо викликаємо як метод об'єкта — `obj.method()` — this дорівнює тому об'єкту що зліва від крапки. Якщо витягнути метод у змінну і викликати окремо — this втрачається, буде undefined в strict mode.

Через call, apply, bind можна явно задати this — передаєш першим аргументом.

З new — this вказує на новий створений об'єкт.

І стрілочна функція — взагалі не має свого this. Вона бере його з того місця де була оголошена. Тому стрілочна функція в setTimeout працює як очікуєш, а звичайна — ні.

На практиці в Composition API ми з this майже не стикаємось — все через замикання в setup, ніякого this. Але в Options API this — це інстанс компонента, і якщо хтось напише стрілочну функцію в methods — this буде не компонент а зовнішній scope. Класична помилка.

В сучасному коді я використовую стрілочні функції майже всюди, і проблеми з this просто не виникають."

---

### Замикання (Closures)

**Питання:** "Що таке замикання? Приклад використання?"

**Відповідь:**

"Замикання — це коли функція запам'ятовує змінні з того місця де була створена, навіть після того як той код вже відпрацював.

Найпростіший приклад — лічильник. Є зовнішня функція з змінною count. Вона повертає внутрішню функцію яка цей count збільшує. Зовнішня функція давно завершилась, а внутрішня все ще має доступ до count. Ніхто ззовні до цієї змінної дістатись не може — ось тобі і інкапсуляція.

На практиці ми це використовуємо щодня навіть не замислюючись. Composables у Vue — це по суті замикання. Пишеш функцію usePaymentMethods, всередині створюєш ref з даними, ref з loading, функцію яка робить запит — і повертаєш назовні. Внутрішній стан закритий, назовні виходить тільки те що потрібно. Кожен composable — це замикання.

Те саме з debounce — таймер живе в замиканні. З мемоізацією — кеш живе в замиканні.

Єдине де треба бути обережним — memory leaks. Якщо замикання тримає посилання на великий об'єкт який вже не потрібен — garbagge collection його не видалить. На сервері при SSR це особливо критично, бо сервер працює довго і витоки накопичуються."

---

### Рекурсія

**Питання:** "Що таке рекурсія? Коли використовуєте? Ризики?"

**Відповідь:**

"Рекурсія — функція викликає сама себе, з обов'язковою умовою зупинки. Без неї — нескінченний цикл і стек переповнюється.

Де я це реально використовую — рекурсивні компоненти. Дерево категорій, вкладене меню, коментарі з відповідями. Компонент TreeNode рендерить себе для кожного дочірнього елемента. Глибина 5-10 рівнів — рекурсія працює ідеально, код читається природно.

Ще — коли API повертає вкладену структуру, а мені потрібен плоский список. Рекурсивно обходжу дерево і збираю в масив.

Ризик один — stack overflow. В JavaScript стек виклнків обмежений. Для UI-дерев це нереально — там 5-10 рівнів. Але якщо раптом потрібно обійти структуру з сотнями рівнів вкладеності — переписую на цикл зі своїм стеком. Це менш елегантно, але безпечно."

---

### Паттерн Singleton

**Питання:** "Що таке Singleton? Де використовуєте?"

**Відповідь:**

"Singleton — це коли в додатку існує тільки один екземпляр чогось. В JavaScript це виходить майже автоматично — ES-модуль виконується один раз, і всі хто його імпортує отримують один і той самий об'єкт.

Де це є на практиці: API-клієнт — один на весь додаток, з налаштованими заголовками і обробкою помилок. WebSocket з'єднання — одне, різні компоненти підписуються на нього. Pinia store — по суті теж singleton.

Але в SSR є серйозна пастка. На сервері один процес обслуговує тисячі користувачів. Якщо singleton зберігає стан на рівні модуля — цей стан стає спільним для всіх. Дані одного користувача потрапляють до іншого. Тому в Nuxt Pinia створює окремий store для кожного запиту, і замість глобального ref потрібно використовувати useState який безпечний для SSR.

Загалом, singleton — це просто, але в серверному контексті потрібно чітко розуміти що глобальне, а що per-request."

---

### Паттерн Factory

**Питання:** "Що таке Factory pattern? Приклад?"

**Відповідь:**

"Factory — це коли логіка створення об'єкта винесена в окрему функцію. Замість того щоб по всьому коду писати if-else і вирішувати що створювати — є одне місце яке це робить.

Приклад з моєї практики — платіжні провайдери. Для кожного гео свій набір: в одній країні Stripe, в іншій крипта, в третій банківський переказ. Всі мають однаковий інтерфейс — депозит, вивід. Але реалізація різна. Factory-функція отримує тип і конфіг, і повертає потрібний провайдер. Код який використовує провайдер — взагалі не знає яка реалізація всередині. Йому все одно.

Те саме з API-клієнтами — одна функція створює клієнт з потрібним базовим URL і перехоплювачами. Або з CMS-блоками — приходить тип блоку з CMS, factory повертає відповідний компонент для рендеру.

Замість switch/case я використовую Map-lookup — це чистіше і легше розширювати. Потрібен новий провайдер — додав один рядок в Map, а не ще одну гілку в switch.

Factory часто йде разом зі Strategy — factory створює об'єкт, а Strategy визначає його поведінку. По суті різні реалізації за одним інтерфейсом."

---

### Паттерн Observer / Event-driven

**Питання:** "Observer pattern — де використовуєте на фронтенді?"

**Відповідь:**

"Observer — патерн де об'єкт (subject) повідомляє список підписників (observers) про зміни.

**На фронтенді це всюди:**

1. **Vue reactivity** — це Observer під капотом. `ref()` / `reactive()` = subject. `watch()` / `computed()` / template = observers. Vue 3 використовує Proxy для tracking.

2. **Event listeners** — DOM events це classic Observer: `addEventListener` = subscribe, `removeEventListener` = unsubscribe.

3. **WebSockets** — сервер pushує events, клієнт підписаний на певні канали:

```typescript
// В iGaming: live odds updates, balance changes, game results
socket.on("balance:update", (data) => {
  balance.value = data.amount;
});
socket.on("odds:change", (data) => {
  updateOdds(data);
});
```

4. **Pinia actions + subscriptions** — `store.$onAction()`, `store.$subscribe()`

5. **Custom EventBus** — для cross-component communication коли provide/inject недостатньо:

```typescript
const emitter = mitt<Events>();
emitter.on("notification", handler);
emitter.emit("notification", { type: "success", msg: "..." });
```

**Пастка:** memory leak якщо забути unsubscribe. В Vue — onUnmounted(() => cleanup()). В WebSocket — disconnect при route change."

---

### Паттерн Strategy

**Питання:** "Strategy pattern — приклад з реального проєкту?"

**Відповідь:**

"Strategy — патерн де алгоритм інкапсулюється в окремий об'єкт і може бути замінений runtime.

**Мій реальний приклад — rendering strategy для сторінок:**

```typescript
interface RenderStrategy {
  shouldCache: boolean;
  ttl: number;
  render(context: RenderContext): Promise<string>;
}

const strategies: Record<PageType, RenderStrategy> = {
  landing: { shouldCache: true, ttl: 300, render: ssrRender },
  blog: { shouldCache: true, ttl: 3600, render: ssgRender },
  cabinet: { shouldCache: false, ttl: 0, render: spaRender },
};

function handleRequest(req: Request) {
  const pageType = resolvePageType(req.path);
  const strategy = strategies[pageType];
  return strategy.render(context);
}
```

**Інший приклад — валідація форм:**

```typescript
interface ValidationStrategy {
  validate(value: unknown): ValidationResult;
}

const strategies = {
  email: {
    validate: (v) => (emailRegex.test(v) ? valid() : error("Invalid email")),
  },
  phone: {
    validate: (v) => (phoneRegex.test(v) ? valid() : error("Invalid phone")),
  },
  amount: {
    validate: (v) => (v > 0 && v <= maxLimit ? valid() : error("Out of range")),
  },
};
```

**Де ще:** per-geo content strategy, per-brand theme strategy, cache invalidation strategy (time-based vs event-based vs hybrid)."

---

### Інші класичні питання

#### Event Loop

**Питання:** "Як працює Event Loop в JavaScript?"

**Відповідь:**

"JavaScript однопоточний — є один потік який виконує код. Event loop — це механізм який дозволяє цьому одному потоку обробляти асинхронні операції не зависаючи.

Як це працює: спочатку виконується весь синхронний код. Коли стек порожній — event loop перевіряє чергу мікрозадач — це проміси, Promise.then. Виконує все що там є. Потім бере одну макрозадачу — setTimeout, I/O. І по колу.

Класичний приклад: console.log 1, потім setTimeout з нулем, потім Promise.then, потім console.log 4. Результат: 1, 4, 3, 2. Бо синхронний код виконується першим, потім промис як мікрозадача, і тільки потім setTimeout як макрозадача. Навіть з нульовою затримкою setTimeout завжди після промісу.

Чому мені це важливо на практиці — дві причини.

На сервері: SSR-рендер — це важка синхронна операція. Поки сервер рендерить одну сторінку — event loop заблокований і всі інші запити чекають. Тому кешування критичне — чим менше запитів доходить до рендеру, тим вільніший event loop.

На клієнті: якщо обробник кліку виконує щось важке більше 50 мілісекунд — event loop зайнятий і наступна взаємодія користувача не обробляється. Це напряму впливає на INP. Рішення — розбивати важку роботу на менші шматки і давати event loop перепочити між ними."

---

#### Hoisting

**Питання:** "Що таке hoisting?"

**Відповідь:**

"Hoisting — це коли JavaScript на етапі компіляції піднімає оголошення змінних і функцій на початок їхнього scope. Тобто технічно можна використати щось до того як воно оголошене в коді.

З var — змінна піднімається, але з значенням undefined. Тобто помилки не буде, але значення неочікуване — і це була постійна причина багів.

З let і const — вони теж піднімаються, але до рядка оголошення потрапляють в так звану temporal dead zone. Спробуєш звернутись — отримаєш помилку. Це захист від випадкового використання до ініціалізації.

Функція оголошена через function declaration — піднімається повністю, можна викликати до оголошення. Стрілочна або function expression — ні, вони поводяться як змінна.

На практиці в сучасному коді це не проблема — ми використовуємо const і let, і temporal dead zone нас захищає. Але розуміти це потрібно коли дебажиш legacy код на var."

---

#### Prototypal Inheritance

**Питання:** "Як працює прототипне наслідування в JS?"

**Відповідь:**

"Кожен об'єкт в JavaScript має посилання на свій прототип. Коли звертаєшся до якоїсь властивості — JS спочатку шукає її в самому об'єкті. Не знайшов — йде до прототипу. Не знайшов там — до прототипу прототипу. І так по ланцюжку, поки не дійде до кінця.

Class в JavaScript — це синтаксичний цукор. Під капотом ті самі прототипи. Просто зручніший запис.

В сучасному коді з Composition API і TypeScript ми з прототипами напряму майже не працюємо — інтерфейси і композиція замінили наслідування через класи. Але розуміти це потрібно для відладки — коли метод чомусь undefined, іноді причина в тому що він загубився десь по ланцюжку прототипів. І деякі бібліотеки досі розширюють прототипи."

---

#### Promise / Async-Await

**Питання:** "Promise, async/await — як обробляєте помилки в async коді?"

**Відповідь:**

"Promise — це об'єкт який представляє результат асинхронної операції. Він або виконається успішно, або впаде з помилкою. Async/await — це зручніший синтаксис для роботи з промісами.

По обробці помилок у мене чіткі правила. Будь-який асинхронний виклик — завжди в try/catch. В catch — помилку типізую як unknown, не any, і перевіряю що це за помилка перед тим як з нею працювати. 404 — це одне, 401 — інше, мережева помилка — третє. В finally — завжди прибираю стан завантаження, незалежно від результату. І ніколи не ковтаю помилку мовчки — або обробляю, або прокидаю далі.

По паралельності — якщо кілька запитів незалежні один від одного, запускаю їх одночасно через Promise.all. Це швидше ніж чекати кожен по черзі. А якщо не хочу щоб падіння одного запиту завалило всі — використовую Promise.allSettled. Наприклад, завантажую паралельно баланс, бонуси і список ігор. Бонусний сервіс впав — показую решту, а замість бонусів заглушку. Користувач бачить сторінку, а не білий екран."

---

#### WeakMap / WeakSet / Map / Set

**Питання:** "Різниця між Map і Object? Коли WeakMap?"

**Відповідь:**

"Map від Object відрізняється тим що ключем може бути що завгодно — не тільки рядок, а й об'єкт, функція. Плюс Map гарантує порядок додавання, має зручний .size, і оптимізований для частого додавання і видалення.

Я використовую Map замість switch/case для lookup-таблиць. Наприклад, є статус платежу — замість switch з п'ятьма гілками роблю Map де ключ це статус, а значення — функція-обробник. Одним рядком дістаю потрібний обробник і викликаю. Чистіше, легше розширювати.

WeakMap — це Map де ключі тримаються слабко. Якщо об'єкт-ключ більше ніде не використовується — збирач сміття його видалить разом із записом у WeakMap. Це корисно для кешу прив'язаного до DOM-елементів або компонентів — видалили елемент зі сторінки, кеш очистився автоматично, ніякого витоку пам'яті. Vue під капотом використовує WeakMap саме для цього — для відстеження залежностей реактивності."

---

## Що можуть запитати і навіщо

Ця роль — не backend developer. Вони хочуть переконатись що ти розумієш **як працює SSR-сервіс під капотом**: чому він може "залипнути", як обробляти помилки щоб один зламаний request не повалив весь сервер, як middleware chain працює в Express (бо Nuxt SSR під капотом — це Nitro/H3, що дуже схоже на Express).

**Типові питання:**

1. "Як працює middleware chain в Express? Що таке next()?"
2. "Як обробляти помилки в Express? Що станеться якщо не зловити помилку?"
3. "Що таке event loop? Що блокує event loop і чому це погано для SSR?"
4. "Як уникнути блокування event loop при SSR?"
5. "Що станеться якщо SSR render для однієї сторінки займає 5 секунд?"
6. "Як зробити timeout для SSR?"
7. "Чим відрізняється process.nextTick від setTimeout(fn, 0)?"
8. "Що таке backpressure і як це стосується SSR streaming?"

---

## Стислі відповіді

### Express Middleware

**Що це:** функції які виконуються послідовно для кожного request. Кожна може: змінити req/res, завершити response, або передати далі через `next()`.

```javascript
// Порядок має значення!
app.use(loggerMiddleware); // 1. Логування
app.use(corsMiddleware); // 2. CORS headers
app.use(authMiddleware); // 3. Перевірка авторизації
app.use(cacheMiddleware); // 4. Server cache check
app.get("/page", ssrHandler); // 5. SSR render
app.use(errorHandler); // 6. Error handler (ЗАВЖДИ останній)
```

**Ключове:**

- Middleware виконується в порядку оголошення
- Якщо не викликати `next()` — request "зависне" (timeout)
- Error middleware має 4 аргументи: `(err, req, res, next)` — Express розпізнає по кількості аргументів
- Якщо throw в sync коді — Express зловить. Якщо reject в async — потрібно explicitly `next(err)` або express-async-errors

**Для SSR-сервісу реальна chain:**

```
request → detect domain (Host header) → load tenant config → check cache →
  HIT: return cached HTML
  MISS: SSR render → store in cache → return HTML
→ error handler → fallback (serve stale / SPA shell)
```

---

### Обробка помилок

**Що станеться якщо не зловити помилку:**

- В Express sync handler — Express зловить і передасть в error middleware
- В async handler без catch — **unhandled promise rejection** → process може крашнутись (Node 15+ default: crash)
- Без error middleware — Express відправить generic 500 HTML

**Правильний підхід:**

```javascript
// Async wrapper — щоб не писати try/catch в кожному handler
const asyncHandler = (fn) => (req, res, next) => {
  Promise.resolve(fn(req, res, next)).catch(next);
};

app.get(
  "/page",
  asyncHandler(async (req, res) => {
    const html = await renderPage(req.url);
    res.send(html);
  }),
);

// Error middleware (4 args!)
app.use((err, req, res, next) => {
  logger.error({ err, requestId: req.id, url: req.url });

  if (err.code === "SSR_TIMEOUT") {
    return res.status(503).send(spaFallbackShell);
  }

  res.status(500).send(fallbackErrorPage);
});
```

**Для SSR критично:**

- Один зламаний render не повинен повалити сервер
- Fallback: якщо SSR впав → віддати SPA shell (client-side render)
- Timeout: якщо render > 3s → abort, віддати cached або fallback
- Graceful shutdown: drain existing connections перед restart

---

### Event Loop (глибше для Node.js контексту)

_(також: "Як event loop в Node.js відрізняється від браузерного?" або "Що таке process.nextTick?")_

"В Node.js event loop працює за тим самим принципом що й у браузері — один потік, черга задач — але є додаткові фази пов'язані з серверними операціями: таймери, мережеві запити, робота з файлами.

Для SSR головне ось що: рендер сторінки — це важка обчислювальна робота. Поки сервер рендерить HTML для одного користувача — event loop заблокований і всі інші запити стоять у черзі. Рендер займає 200 мілісекунд — здається мало. Але 50 одночасних запитів — і останній чекає 10 секунд.

Як з цим жити: найголовніше — кешування, щоб більшість запитів взагалі не доходили до рендеру. Далі — таймаут: якщо рендер затягнувся — обриваємо і віддаємо запасний варіант. І горизонтальне масштабування — кілька копій сервісу, кожна обробляє свою частину.

Якщо запитають про різницю між process.nextTick, setTimeout і setImmediate —
nextTick виконується з найвищим пріоритетом, ще до наступної фази event loop.
Promise.then — одразу після нього.
setTimeout навіть з нульовою затримкою — це вже наступна ітерація, в фазі таймерів.
setImmediate — після обробки мережевих запитів. "

---

### Практичне питання: "Як ви реалізуєте SSR timeout?"

```javascript
function renderWithTimeout(url, timeoutMs = 3000) {
  return new Promise((resolve, reject) => {
    const timer = setTimeout(() => {
      reject(new Error("SSR_TIMEOUT"));
    }, timeoutMs);

    renderPage(url)
      .then((html) => {
        clearTimeout(timer);
        resolve(html);
      })
      .catch((err) => {
        clearTimeout(timer);
        reject(err);
      });
  });
}

// В handler:
app.get(
  "*",
  asyncHandler(async (req, res) => {
    try {
      const html = await renderWithTimeout(req.url, 3000);
      res.set("Cache-Control", "public, max-age=300");
      res.send(html);
    } catch (err) {
      if (err.message === "SSR_TIMEOUT") {
        res.set("Cache-Control", "no-cache");
        res.send(spaFallbackShell); // client-side render as fallback
      } else {
        throw err; // pass to error middleware
      }
    }
  }),
);
```

---

## Що почитати щоб реально зрозуміти (не 500-сторінкові книги, а конкретне)

### Event Loop (1-2 години):

1. **"What the heck is the event loop anyway?"** — Jake Archibald, JSConf talk (YouTube, 26 хв). Найкраще візуальне пояснення event loop. Подивись один раз і все зрозумієш.
   - https://www.youtube.com/watch?v=8aGhZQkoFbQ

2. **"In The Loop"** — Jake Archibald (ще один talk, 35 хв). Глибше: microtasks, rendering pipeline, requestAnimationFrame.
   - https://www.youtube.com/watch?v=cCOL7MC4Pl0

3. **Node.js Event Loop docs** — офіційна документація, 15 хв читання:
   - https://nodejs.org/en/learn/asynchronous-work/event-loop-timers-and-nexttick

### Express Middleware (30-60 хв):

4. **Express docs: "Writing middleware"** + **"Error handling"** — коротко і по суті:
   - https://expressjs.com/en/guide/writing-middleware.html
   - https://expressjs.com/en/guide/error-handling.html

5. **"How does Express middleware work?"** — зрозуміти chain і next():
   - Просто напиши 3 middleware вручну, додай console.log в кожен, подивись порядок. 20 хв hands-on > 2 години читання.

### SSR + Node.js performance (для senior відповідей):

6. **"Don't Block the Event Loop"** — Node.js best practices guide:
   - https://nodejs.org/en/learn/asynchronous-work/dont-block-the-event-loop

7. **Nuxt 3 / Nitro server engine docs** — зрозуміти як Nuxt використовує H3 (lightweight Express alternative):
   - https://nitro.build/guide

### Порядок читання (якщо мало часу):

**Мінімум (2 години):**

1. Jake Archibald video #1 (event loop візуально)
2. Express error handling docs
3. "Don't Block the Event Loop" guide

**Ідеально (4-5 годин):**

- Всі 7 ресурсів вище + написати простий Express server з middleware chain, error handling, і setTimeout-based "SSR render" щоб побачити як event loop блокується

---

Ключове для інтерв'ю: тобі не треба знати Node.js як backend розробник. Треба впевнено пояснити **чому SSR може бути повільним** (event loop blocking), **як захистити сервер від cascade failures** (error handling, timeouts, fallbacks), і **як middleware chain організує request processing**. Це все прив'язується до твоєї ролі — ти будуєш SSR-сервіс, ти маєш розуміти його runtime поведінку.

## Чи реально за 1.5 доби? Чесна відповідь:

**Так, але з правильним фокусом.** Ти не "вивчаєш з нуля" — у тебе 8 років досвіду. Задача — не вивчити, а **структурувати те що знаєш** і **заповнити конкретні діри**.

---

## Стратегія підготовки на 36 годин

### Пріоритет 1: MUST (8-10 годин) — це 80% інтерв'ю

| Тема                               | Час     | Що робити                                      |
| ---------------------------------- | ------- | ---------------------------------------------- |
| Відповідь "про себе" + positioning | 1 год   | Промовити вголос 5 разів, щоб звучало nature   |
| SSR/SSG/Hydration                  | 2 год   | Перечитати свої відповіді + Nuxt docs по SSR   |
| SEO (canonical, hreflang, mirrors) | 1.5 год | Перечитати + уявити як пояснюєш на дошці       |
| Core Web Vitals                    | 1.5 год | LCP/INP/CLS — causes + fixes, промовити вголос |
| Event Loop + Node.js basics        | 1.5 год | Jake Archibald video + Express error handling  |
| System design "SSR for 5 domains"  | 1 год   | Промовити відповідь вголос як на дошці         |

### Пріоритет 2: SHOULD (4-5 годин)

| Тема                               | Час     |
| ---------------------------------- | ------- |
| Vue/Nuxt технічні питання (нижче)  | 2 год   |
| JS core (this, closures, patterns) | 1.5 год |
| Behavioral stories (STAR)          | 1 год   |

### Пріоритет 3: NICE TO HAVE (2-3 год)

| Тема                            | Час     |
| ------------------------------- | ------- |
| Monitoring (Sentry, Prometheus) | 1 год   |
| TypeScript глибокі питання      | 1 год   |
| Gaps (bridge answers)           | 0.5 год |

---

## Додаткові питання які ЧАСТО задають (і яких ще нема в документі)

### JavaScript Core — ще питання:

**1. "Різниця між == і ===?"**

"Подвійне дорівнює перетворює типи перед порівнянням — рядок '1' і число 1 будуть рівні. Потрійне — порівнює без перетворення, строго. Я завжди використовую потрійне. Єдиний виняток — `value == null`, бо це одночасно перевіряє і null і undefined, що зручно."

**2. "var vs let vs const?"**

"var — це legacy, область видимості на рівні функції, піднімається як undefined. Не використовую ніколи. let і const — блочна область видимості, temporal dead zone. Різниця: let можна перезаписати, const — ні. Але важливо — const захищає від перезапису самої змінної, а не від зміни вмісту об'єкта. Об'єкт всередині const можна мутувати. Мій стандарт — const за замовчуванням, let тільки коли потрібно перезаписати значення."

**3. "Що таке Event Delegation?"**

"Замість того щоб вішати обробник на кожен елемент списку окремо — вішаю один на батьківський контейнер. Подія спливає вгору, я ловлю її на батьку і через event.target розумію на якому елементі клікнули. Менше пам'яті, плюс працює для елементів які додаються динамічно. У Vue ми рідко робимо це вручну — @click на v-for елементах Vue і так оптимізує — але для vanilla JS або для дуже великих списків це важливий прийом."

**4. "Shallow copy vs Deep copy?"**

**4. "Shallow copy vs Deep copy?"**

"Shallow copy — копіює тільки перший рівень. Наприклад, є об'єкт user з вкладеним address. Роблю `const copy = { ...user }`. Тепер copy.name — це окреме значення, можу змінювати. Але copy.address — це те саме посилання що й user.address. Зміню copy.address.city — зміниться і в оригіналі. Бо скопіювалось посилання, а не сам об'єкт.

Deep copy — копіює все на всю глибину. Зараз для цього є structuredClone — вбудований в браузер і Node.js, працює коректно з датами і вкладеними структурами. До нього використовували JSON.parse(JSON.stringify()), але цей хак не працює з Date, undefined і функціями.

У Vue нюанс — якщо об'єкт реактивний, structuredClone не зможе його клонувати як є. Спочатку знімаю реактивність через toRaw, потім клоную."

**5. "Що таке debounce і throttle?"**

"Це техніки оптимізації — функції-обгортки які контролюють як часто виконується інша функція. Обидва обмежують частоту виконання, але по-різному. Debounce — виконати після паузи. Користувач друкує в пошук — я не відправляю запит на кожну літеру, а чекаю 500 мілісекунд після останнього натискання. Перестав друкувати — тоді запит. Throttle — виконати не частіше ніж раз в N мілісекунд. Наприклад, обробка скролу або оновлення даних з WebSocket — дані приходять десятки разів на секунду, а я оновлюю інтерфейс максимум раз на 200 мілісекунд."

**6. "Що таке garbage collection в JS?"**

"JavaScript сам звільняє пам'ять від об'єктів до яких більше ніхто не звертається. Працює за принципом mark-and-sweep — обходить усі досяжні об'єкти від кореня, а все що не досяжне — видаляє. Витік пам'яті виникає коли ми тримаємо посилання на щось що вже не потрібне — забутий обробник подій, замикання яке тримає великий об'єкт, відчеплені DOM-елементи. На сервері при SSR це особливо небезпечно — сервер працює безперервно, витоки накопичуються, і врешті процес падає через нестачу пам'яті."

---

### Vue 3 / Nuxt 3 — додаткові часті питання:

**7. "Reactive vs Ref — коли що?"**

- `ref` — для примітивів і коли потрібно перезаписати весь об'єкт (`value = newObj`)
- `reactive` — для об'єктів коли не плануєш перезаписувати весь об'єкт
- `shallowRef` — для великих об'єктів де не потрібна deep reactivity (performance)
- Мій стандарт: `ref` для всього (consistency), `shallowRef` для performance-critical data (live odds, large lists)

**8. "Як працює Vue reactivity під капотом?"**

"У Vue 3 реактивність побудована на Proxy. Коли я пишу `reactive(obj)` — Vue обертає об'єкт у Proxy, який перехоплює звернення до полів. Коли компонент рендериться і читає якесь поле — Vue запам'ятовує: 'цей компонент залежить від цього поля'. Коли поле змінюється — Vue знає хто від нього залежить і перерендерює тільки ці компоненти, а не все підряд.

Наприклад, є об'єкт user з полями name і age. Один компонент показує name, інший — age. Змінився age — перерендериться тільки другий. Перший навіть не дізнається.

У Vue 2 це працювало через Object.defineProperty — і там була проблема: якщо додати нове поле до об'єкта або змінити елемент масиву по індексу — Vue це не бачив. Потрібні були спеціальні методи типу Vue.set. Proxy в Vue 3 це вирішив — перехоплює все, включаючи додавання і видалення полів."

**9. "watch vs watchEffect vs computed?"**

- `computed` — derived state, кешується, перераховується тільки коли dependencies змінились. Для template display
- `watch` — явна реакція на зміну конкретного source. Для side effects (API call, analytics)
- `watchEffect` — автоматично трекає всі reactive dependencies всередині. Зручно але менш explicit
- Правило: computed для UI, watch для side effects, watchEffect коли лінь перераховувати deps

**10. "Що таке Teleport і Suspense в Vue 3?"**

- `<Teleport to="body">` — рендерить DOM в інше місце (модалки, tooltips). Логічно компонент в дереві, фізично — в body
- `<Suspense>` — для async components і async setup(). Показує fallback поки async resolves. В Nuxt — використовується під капотом для useAsyncData

**11. "Nuxt 3 auto-imports — як працює і проблеми?"**

- Nuxt автоматично імпортує composables з `/composables`, components з `/components`, utils
- Проблеми: namespace collisions, важко зрозуміти звідки функція, IDE може не підхоплювати types
- Мій підхід: для великих проєктів — explicit imports з `#imports` для clarity; auto-import ОК для стандартних Vue/Nuxt composables

**12. "Nuxt 3 layers — для чого?"**

"Layers — це вбудований у Nuxt спосіб ділити код між проєктами. В nuxt.config прописуєш extends і вказуєш базовий шар — і все що там є автоматично доступне: компоненти, composables, конфігурація.

Для multi-brand продукту це ідеально: базовий шар зі спільними компонентами і логікою, і окремий шар для кожного бренду — своя тема, свій конфіг, свої overrides. Один codebase, але кожен бренд виглядає по-своєму.

Альтернатива — monorepo з npm-пакетами, але layers простіше і нативніше для Nuxt, без зайвого оверхеду з публікацією і версіонуванням пакетів."

**13. "Як працює useFetch / useAsyncData в Nuxt?"**

- На сервері: робить fetch, серіалізує результат в payload (HTML)
- На клієнті при hydration: НЕ робить повторний fetch, бере з payload
- При client-side navigation: робить fetch на клієнті
- Key — унікальний ідентифікатор для кешу. Без key або з однаковим key — cache collision
- `refresh()` — примусовий re-fetch. `watch` params — auto re-fetch при зміні

**14. "Що таке Nitro в Nuxt 3?"**

"Nitro — це серверний движок Nuxt 3. По суті це те що обробляє запити на сервері — раніше для цього використовували Express, а Nuxt 3 замінив його на власне рішення. Під капотом — h3, легкий HTTP-фреймворк. Працює так само як Express — middleware, роутинг, обробка запитів — але значно легший і швидший.

Серверний код живе в папці `/server/` — там API-ендпоінти і серверні middleware. Замість звичних req, res пишеш defineEventHandler — це обгортка Nitro.

Головна перевага — Nitro універсальний. Один і той самий код можна задеплоїти на Node.js сервер, на Cloudflare Workers, на Vercel Edge. Не переписуючи нічого. Для multi-domain продукту це зручно — можна вибирати інфраструктуру під потреби."

**15. "Як робити error handling в Nuxt 3?"**

- `<NuxtErrorBoundary>` — ловить помилки в дочірніх компонентах
- `error.vue` — глобальна error page (404, 500)
- `createError({ statusCode: 404 })` — для programmatic errors
- `showError()` / `clearError()` — для manual error state management
- В SSR: unhandled error → 500 response. Тому ЗАВЖДИ try/catch в useAsyncData або error handling в server middleware

**16. "Pinia vs Vuex — чому Pinia?"**

- Нативна підтримка TypeScript (не потрібні типізовані обгортки)
- Composition API style (setup stores)
- Немає mutations — actions і direct state access
- Модульність без modules/namespaces — кожен store окремий
- Менший bundle, простіший API
- DevTools інтеграція та ж сама

**17. "Як уникнути shared state в SSR з Pinia?"**

- В SSR кожен request = новий app instance = нові store instances
- Nuxt Plugin з Pinia цим займається автоматично
- Проблема: якщо імпортувати store ПОЗА defineNuxtPlugin/setup — може бути shared
- Правило: завжди отримувати store instance через `useStore()` всередині setup або composable, ніколи на module level

---

### Ще можуть спитати (quick-fire):

**18. "nextTick — навіщо?"**

- Vue batch updates: змінив 10 refs — DOM оновиться один раз
- `nextTick()` — дочекатись наступного DOM update
- Коли потрібно: після зміни data потрібно виміряти DOM (scrollHeight, getBoundingClientRect)

**19. "v-if vs v-show?"**

- `v-if` — повністю видаляє/створює DOM. Дорого для частих toggle
- `v-show` — display:none/block. Дешево для toggle, але рендерить при mount навіть якщо hidden
- SSR: `v-if="false"` не потрапить в HTML зовсім. `v-show` — потрапить з display:none

**20. "key attribute — навіщо?"**

- Vue використовує key для ідентифікації vnodes в v-for
- Без key — Vue реюзає DOM nodes по порядку (може бути баг з input state)
- Трюк: змінити key щоб форсувати пересоздання компонента (reset state)
- В SSR: key допомагає уникнути hydration mismatch при списках

**21. "provide/inject vs props vs Pinia?"**

- Props: parent → child. Для 1-2 рівні
- Provide/inject: ancestor → будь-який descendant. Для theme, config, DI
- Pinia: глобальний shared state. Для app-wide data (user, cart, balance)
- Provide/inject НЕ reactive by default — потрібно передавати ref/reactive

**22. "Що таке Virtual DOM і навіщо?"**

- Virtual DOM — JavaScript representation DOM дерева
- Зміна state → новий VDOM → diff з попереднім → мінімальний patch реального DOM
- Навіщо: DOM operations дорогі, batch і diff роблять update ефективним
- Альтернатива: Svelte (compile-time, без VDOM). Vue/React — runtime diffing

---

## Головна порада на 1.5 доби:

**НЕ читай все.** Ось алгоритм:

1. **Сьогодні ввечері (3-4 год):** промови вголос "про себе", SSR architecture, SEO mirrors. Подивись Jake Archibald video про event loop.

2. **Завтра вранці (4-5 год):** Core Web Vitals (LCP/INP/CLS діагностика), Vue/Nuxt питання вище, JS core (this, closures, event loop).

3. **Завтра після обіду (3-4 год):** System design (SSR microservice), behavioral STAR stories, gaps bridge answers. Express middleware + error handling (docs, 30 хв).

4. **Ввечері перед інтерв'ю (1-2 год):** Перечитай "10 найсильніших фраз" і "10 коротких відповідей". Промови вголос 3-4 ключові відповіді.

**Секрет:** на інтерв'ю виграє не той хто знає все, а той хто **впевнено і структуровано відповідає на 70%** і чесно каже "не робила, але ось як підійду" на 30%. Твій досвід — реальний і сильний. Задача — не вивчити нове, а навчитись ГОВОРИТИ про те що вже знаєш.
