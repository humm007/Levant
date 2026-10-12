# Research notes and evidence register

**Research date:** 11 October 2026. Companion to [the architecture and SEO plan](LEVANT_WEBSITE_ARCHITECTURE_AND_SEO_PLAN.md).

## Method and limits

Seven books were consulted through selected relevant passages. The PDFs/EPUB were extracted locally for navigation, then the cited passages were inspected. Extraction of a whole file is not a claim of having read the whole book. Notes below are paraphrases and applications, not reproduced chapters. PDF positions count pages from the start of each local PDF; printed page numbering may differ.

Five supplied screenshots were visually inspected: 22.05.41, 22.06.18, 22.06.49, 22.08.54, and 22.09.39. Public pages were reviewed through the web tool; shell DNS resolution failed, so there is no complete crawl, original-HTML audit, measured speed report, Search Console dataset, or authenticated admin audit. No site/account changes or outbound messages were made.

Official documentation is used for technical/policy conclusions. Community discussions supply questions and practitioner context, not proof of rankings or current pricing. Some Meta and individual competitor pages could not be fetched; account-specific WhatsApp automation feasibility remains open.

## Books consulted

<a id="b1-dont-make-me-think-revisited"></a>

### B1 — Don't Make Me Think, Revisited

**Author/edition:** Steve Krug; third edition, 2014.

**Local source:** [Don't Make Me Think, Revisited](</Users/jabedhossain/Desktop/Github/Book /Web and software engineering book/Dont Make Me Think, Revisited A Common Sense Approach to Web Usability (3rd Edition) (Voices That Matter) (Krug, Steve) (z-library.sk, 1lib.sk, z-lib.sk).pdf>).

**Reviewed:** Selected Chapter 1 material, PDF positions 29–36; Chapter 3 opening, 47–48; mobile usability selections, 177–183, 185 and 189.

**Principle:** Make labels and next steps recognisable. Visitors scan; visible hierarchy, familiar navigation, and clear controls matter. Mobile constraints require prioritisation without hiding essential tasks.

**Application:** Plain service names; one main estimate action; keyboard/touch-friendly controls; the same content and conversion tasks on mobile and desktop.

<a id="b2-seo-2025"></a>

### B2 — SEO 2025

**Author/edition:** Adam Clarke; 2025 edition.

**Local source:** [SEO 2025](</Users/jabedhossain/Desktop/Github/Book /SEO Book/SEO 2025 - Learn search engine optimization with smart internet marketing strategies (Adam Clarke) (z-library.sk, 1lib.sk, z-lib.sk).pdf>).

**Reviewed:** Keyword intent, PDF positions 28–30; on-page structure, 46–48 and 51; local SEO, 128–132.

**Principle:** Connect page intent to what a customer wants to do. Site structure, clear listings, local business information, and reviews deserve attention together.

**Application:** Service/area intent mapping; budget guides linked to estimation; review/profile work alongside technical SEO. Do not copy the book’s simplified ranking-factor claims, keyword-in-business-name implication, or metadata example as current implementation guidance.

<a id="b3-seo-fitness-workbook"></a>

### B3 — SEO Fitness Workbook

**Author/edition:** Jason McDonald; 2021 edition.

**Local source:** [SEO Fitness Workbook](</Users/jabedhossain/Desktop/Github/Book /SEO Book/Seo Fitness Workbook Search Engine Optimization Success in Seven Steps (2021 Edition) (Jason McDonald) (z-library.sk, 1lib.sk, z-lib.sk).epub>).

**Reviewed:** Selected passages in section 1.2 Goals, EPUB text00011.html; 5.3 Local SEO & Review Marketing, text00031.html; 6.1 Metrics, text00033.html.

**Principle:** Define commercial goals before choosing metrics. Search visibility, clicks, enquiries, follow-up, and sales form a funnel with different possible failure points.

**Application:** Lead dashboard and monthly reporting connect SEO to jobs won. The book predates current GA4 conventions and newer UK storage rules; older product names, analytics steps, and metric claims are not treated as current instructions.

<a id="b4-using-generative-ai-for-seo"></a>

### B4 — Using Generative AI for SEO

**Author/edition:** Eric Enge and Adrián Ridner.

**Local source:** [Using Generative AI for SEO](</Users/jabedhossain/Desktop/Github/Book /SEO Book/Using Generative AI for SEO AI-First Strategies to Improve Quality, Efficiency, and Costs (Eric Enge, Adrián Ridner) (z-library.sk, 1lib.sk, z-lib.sk).pdf>).

**Reviewed:** What Makes Content Valuable and Requiring Human Involvement, selected PDF positions 112–117, printed pages 98–103.

**Principle:** Content should contribute useful information and genuine experience. Human subject experts need to verify AI-assisted output for errors, omissions, context, and voice.

**Application:** Use owner-approved job evidence and FAQ answers. Keep pricing deterministic. Do not invent projects or mass-publish interchangeable location pages. Nuanced Google claims in the book are checked against official guidance rather than repeated as algorithm facts.

<a id="b6-fundamentals-of-software-architecture"></a>

### B6 — Fundamentals of Software Architecture

**Author/edition:** Mark Richards and Neal Ford; second edition.

**Local source:** [Fundamentals of Software Architecture](</Users/jabedhossain/Desktop/Github/Book /Web and software engineering book/Fundamentals of Software Architecture A Modern Engineering Approach (Second Edition) (Mark Richards, Neal Ford) (z-library.sk, 1lib.sk, z-lib.sk).pdf>).

**Reviewed:** Architectural characteristics, selected PDF positions 79–80, 83–85 and 88; limiting/prioritising characteristics, 101–102.

**Principle:** Architecture is a set of tradeoffs. Every quality attribute adds cost and interacts with other attributes. Keep the priority list focused on the business rather than supporting everything imaginable.

**Application:** Prioritise performance, reliable enquiries, owner usability, maintainability, and privacy. Use one application and managed services initially; revisit the choice if traffic, teams, or workflows materially change.

<a id="b7-clean-architecture"></a>

### B7 — Clean Architecture

**Author/edition:** Robert C. Martin.

**Local source:** [Clean Architecture](</Users/jabedhossain/Desktop/Github/Book /Web and software engineering book/Clean Architecture A Craftsmans Guide to Software Structure and Design (Robert C. Martin) (z-library.sk, 1lib.sk, z-lib.sk).pdf>).

**Reviewed:** Chapter 18 Boundary Anatomy, PDF positions 204–208, printed pages 177–181; selected Chapter 25 Layers and Boundaries passages, 249–252, printed pages 222–225.

**Principle:** Business rules should not depend on specific delivery or storage details. Useful boundaries can exist within one process; network boundaries carry additional latency and complexity.

**Application:** Reuse one quotation and lead service across wizard, admin and assistant. Keep email/WhatsApp adapters outside those rules. Apply small explicit boundaries without reproducing a heavyweight layered framework for this small site.

<a id="b8-building-evolutionary-architectures"></a>

### B8 — Building Evolutionary Architectures

**Author/edition:** Neal Ford, Rebecca Parsons, Patrick Kua and Pramod Sadalage; second edition.

**Local source:** [Building Evolutionary Architectures](</Users/jabedhossain/Desktop/Github/Book /Web and software engineering book/Building Evolutionary Architectures, 2nd Edition Automated Software Governance (Neal Ford, Rebecca Parsons, Patrick Kua etc.) (z-library.sk, 1lib.sk, z-lib.sk).pdf>).

**Reviewed:** Chapter 2 Fitness Functions, PDF positions 35–37 and 39, printed pages 13–15 and 17.

**Principle:** Protect architectural characteristics with objective checks as a system evolves. These can include monitors, performance checks, security checks, and manual assessments.

**Application:** Budget public assets, verify metadata/URL responses, test lead durability and permissions, and demonstrate restore/rollback. Checks should expose material regressions rather than mirror every implementation detail.

### B5 — excluded scanned information-architecture volume

The locally available Information Architecture for the World Wide Web volume has 541 PDF pages, but text extraction produced only 983 characters. It is a scanned volume and was not substantively read. It is not counted among the seven consulted books. [Local scanned source](</Users/jabedhossain/Desktop/Github/Book /Web and software engineering book/WEB信息架构设计大型网站=INFORMATION ARCHITECTURE FOR THE WORLD WIDE WEBDESIGNING LARGE-SCALE WEB SITES,3RD EDITION (（美）PETER MORVILLE LOUIS ROSENFELD著) (z-library.sk, 1lib.sk, z-lib.sk).pdf>).

## Community discussions inspected

- [Reddit: Is Astro for business sites?](https://www.reddit.com/r/astrojs/comments/1hbb5ai/is_astro_for_business_sites/) — practitioners describe Astro with a CMS and lightweight endpoints. Useful context for static delivery; anecdotal reports of speed, cost, and maintenance are not benchmarks. Older version/pricing advice is excluded from the proposal.
- [Reddit: WordPress to Next.js migration](https://www.reddit.com/r/nextjs/comments/1ryvtnv/swap_from_wordpress_to_fullstack_nextjs_app/) — raises URL continuity, content changes, and migration concerns. The migration checklist is based on Google’s official guide.
- [Stack Overflow: Open Graph tags in a React SPA](https://stackoverflow.com/questions/55884214/open-graph-meta-tags-and-seo-in-a-react-spa) — historical discussion raises the difference between initial HTML and tags added in the browser. Technical implementation conclusions come from current Google/Next/Astro documentation, not old answers.

## Official web reference register

These pages were retrieved or searched during research. Availability, pricing, and platform compatibility must be checked again before purchasing or implementing.

- [Public homepage](https://levant-painting.co.uk/) — Advertised service scope and visible existing content.
- [Areas covered](https://levant-painting.co.uk/areas-we-cover/) — Broad stated coverage, not proof of priority or demand.
- [Google SEO Starter Guide](https://developers.google.com/search/docs/fundamentals/seo-starter-guide) — No automatic number-one result; variable impact timing.
- [Google local ranking](https://support.google.com/business/answer/7091?hl=en) — Relevance, distance, and prominence.
- [Business Profile representation](https://support.google.com/business/answer/3038177?hl=en) — Accurate identity, service-area business, and address treatment.
- [Google migration guide](https://developers.google.com/search/docs/crawling-indexing/site-move-with-url-changes) — URL mapping, redirects, and migration fluctuations.
- [Google spam policies](https://developers.google.com/search/docs/essentials/spam-policies) — Doorways, scaled abuse, stuffing, and manipulative links.
- [Google JavaScript SEO](https://developers.google.com/search/docs/crawling-indexing/javascript/javascript-seo-basics) — Crawl/render processing and direct HTML availability.
- [Title links](https://developers.google.com/search/docs/appearance/title-link) — Titles may be generated differently from supplied title tags.
- [Snippets](https://developers.google.com/search/docs/appearance/snippet) — Descriptions are suggestions; Google can choose page text.
- [LocalBusiness structured data](https://developers.google.com/search/docs/appearance/structured-data/local-business) — Eligibility requirements distinct from general schema validity.
- [Review snippets](https://developers.google.com/search/docs/appearance/structured-data/review-snippet) — Self-serving business review restrictions.
- [Search documentation updates](https://developers.google.com/search/updates) — FAQ rich-result deprecation from May 2026 and documentation removal in June.
- [Generative AI content guidance](https://developers.google.com/search/docs/fundamentals/using-gen-ai-content) — Value/quality and scaled-content considerations.
- [Web Vitals](https://web.dev/articles/vitals) — LCP, INP, CLS targets and 75th-percentile evaluation.
- [WCAG 2.2](https://www.w3.org/TR/WCAG22/) — Accessibility reference for interaction, reflow, focus, and contrast.
- [Next server/client components](https://nextjs.org/docs/app/getting-started/server-and-client-components) — Keep browser interaction scoped.
- [Next self-hosting](https://nextjs.org/docs/app/guides/self-hosting) — Node hosting and operational caching concerns.
- [Payload overview](https://payloadcms.com/docs/getting-started/what-is-payload) — Integrated configurable admin and application backend.
- [Payload access control](https://payloadcms.com/docs/access-control/overview) — Backend permission enforcement.
- [Payload Local API](https://payloadcms.com/docs/local-api/overview) — Explicit access enforcement on user-context calls.
- [Payload transactions](https://payloadcms.com/docs/database/transactions) — Request-context transaction sharing and awaited writes.
- [Payload jobs](https://payloadcms.com/docs/jobs-queue/overview) — Existing queue alternative; not an additional baseline queue.
- [Payload deployment](https://payloadcms.com/docs/production/deployment) — Production dependencies and deployment planning.
- [Astro islands](https://docs.astro.build/en/concepts/islands/) — HTML-first components and opt-in browser interactivity.
- [Sanity pricing](https://www.sanity.io/pricing) — Current role/seat limits affect the alternative CMS budget.
- [Laravel Blade](https://laravel.com/framework/docs/13.x/blade) — PHP public template rendering.
- [Laravel queues](https://laravel.com/framework/docs/13.x/queues) — Database-backed background jobs.
- [Filament overview](https://filamentphp.com/docs/5.x/introduction/overview) — Admin framework alternative.
- [Filament widgets](https://filamentphp.com/docs/5.x/widgets/overview) — Dashboard implementation alternative.
- [WordPress REST API](https://developer.wordpress.org/rest-api/) — Retain/modernise WordPress as an economic baseline.
- [Render Next deployment](https://render.com/docs/deploy-nextjs-app) — Managed Node deployment possibility.
- [Render regions](https://render.com/docs/regions) — Frankfurt listed; not UK-only hosting.
- [Render pricing](https://render.com/pricing) — Retrieved page did not expose a complete numeric compute table; plan uses budget allowances, not claimed vendor quotes.
- [Resend pricing](https://resend.com/pricing?product=transactional) — Free daily limit and paid transactional plan.
- [WhatsApp click-to-chat](https://faq.whatsapp.com/5913398998672934) — Number format and prefilled text; visible via search retrieval.
- [ICO storage/access guidance](https://ico.org.uk/for-organisations/direct-marketing-and-privacy-and-electronic-communications/guidance-on-the-use-of-storage-and-access-technologies/) — Updated 2026 framework.
- [ICO exceptions](https://ico.org.uk/for-organisations/direct-marketing-and-privacy-and-electronic-communications/guidance-on-the-use-of-storage-and-access-technologies/what-are-the-exceptions/) — Conditional statistical-purpose exception; no blanket analytics exemption.

## Decision changes from the complete brief

The selected design favours Next + Payload + PostgreSQL for a shared private lead dashboard, one admin login, centrally editable content/pricing, and interactive enquiry workflows. The focused language comparison in section 23 considers Laravel + Filament and Django + Wagtail alongside it. Astro + Payload remains a static-public-delivery alternative. This decision is about total maintenance and workflow fit, not a claim of ranking or AI-citation superiority.

## Outstanding evidence before implementation

- Actual target areas, verified service scope, owner price calibration, VAT display, and asset permissions.
- Search Console/Business Profile/lead baseline and full current-URL inventory.
- Local competitor review at relevant postcodes; sampled directory results are not measured Google positions.
- Compatible framework versions, actual host sizing/cost, and restore/publication behaviour.
- Current WhatsApp Business Platform account eligibility, template/recipient rules, intended team destination, and fees before quoting automation.

## Additional research: Next.js, Laravel, Python, and AI discovery

**Added:** 11 October 2026, for section 23 of the main plan. Current official sources were checked for the narrowed language comparison and discovery strategy. No prototype benchmark or live crawler-access audit was performed. The relative stack preference is an engineering judgement for the supplied requirements.

The OpenAI Docs skill was used to check official crawler guidance. Search discovery and model-training crawling are separate settings; neither is equivalent to adding an on-site chatbot. [Skill instructions](</Users/jabedhossain/.codex/skills/.system/openai-docs/SKILL.md>).

Additional sources:

- [Google AI optimisation guide](https://developers.google.com/search/docs/fundamentals/ai-optimization-guide) — current discovery guidance, AI-file/schema myths, and Search Console AI reporting. Check account eligibility/settings at implementation.
- [Google AI features](https://developers.google.com/search/docs/appearance/ai-features) — normal SEO foundations remain relevant.
- [Official OpenAI crawlers](https://developers.openai.com/api/docs/bots) — OAI-SearchBot for search, GPTBot for training, independent controls and published request ranges.
- [Perplexity crawlers](https://docs.perplexity.ai/docs/resources/perplexity-crawlers) — search crawler and firewall handling.
- [Bing AI Performance introduction](https://blogs.bing.com/webmaster/2026/2/Introducing-AI-Performance-in-Bing-Webmaster-Tools-Public-Preview/) — citation reporting and local business information.
- [Bing AI visibility update](https://blogs.bing.com/search/2026/6/New-AI-Visibility-Insights-in-Bing-Webmaster-Tools-Intents-Topics-Citation-Share-Compare/) — newer supported visibility comparisons; not universal AI rankings.
- [IndexNow documentation](https://www.indexnow.org/documentation) — notify participating engines of owned-URL changes.
- [Next ISR guidance](https://nextjs.org/docs/app/guides/incremental-static-regeneration) — public freshness/caching mechanism; use the model appropriate to pinned versions.
- [Laravel cache](https://laravel.com/framework/docs/13.x/cache) — cache capabilities for the PHP alternative.
- [Laravel AI SDK](https://laravel.com/framework/docs/13.x/ai-sdk) — provider integration capability; guided FAQs do not require it.
- [Django admin](https://docs.djangoproject.com/en/5.2/ref/contrib/admin/) — model-focused internal administration; custom views for process-focused interfaces.
- [Django Tasks](https://docs.djangoproject.com/en/6.0/topics/tasks/) — task definitions do not supply a production execution worker; feature introduced in Django 6.
- [Django support schedule](https://www.djangoproject.com/download/) — supported release series and dates; verify Wagtail compatibility too.
- [Wagtail tutorial](https://docs.wagtail.org/en/stable/getting_started/tutorial.html) — integrated Django-based editorial CMS.
- [Wagtail model views](https://docs.wagtail.org/en/stable/extending/generic_views.html) — configurable administration for lead and other non-page records.
- [Filament overview](https://filamentphp.com/docs/5.x/introduction/overview) — PHP admin building blocks.

No additional books were claimed as read for this extension. The original seven-book notes remain the design foundation; new platform/discovery details come from the sources above.
