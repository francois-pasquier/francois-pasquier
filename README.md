# François Pasquier

**Tech Lead React Native.** I take mobile apps out of technical dead ends: dying frameworks, three codebases that should be one, teams that need to move to something they have never used.

Nine years on mobile, React Native since 2017. Based in Paris, working remote across Europe.

---

### Getting off a framework nobody maintains

I migrated a 1.3M-user app from **NativeScript to React Native**, screen by screen, with no service interruption and no roadmap freeze.

The hard part was not the code. It was the 30 developers who had only ever written NativeScript. I wrote the training material, set the conventions and the architecture docs, and reviewed every pull request during the transition. They finished the migration autonomous, and the company could hire again.

### Turning three codebases into one

Native iOS, native Android and a PHP web app, unified into a single **React Native + Next.js** codebase with server-side rendering. One feature written once, shipped everywhere, automatically.

### Making accessibility the default

Component libraries built on **React Aria**, WCAG compliant, documented in Storybook, so accessibility stops depending on each developer remembering it at the moment they write the code.

### Leaving you able to continue without me

Architecture documentation, tests, CI/CD and training as I go. If you still need me after the mission, I did the job badly.

---

### Selected work

| | |
|---|---|
| **Genybet** | Online betting platform. Native iOS, native Android and a PHP web app unified into one React Native + Next.js codebase with SSR, and continuous delivery to both stores. |
| **Socios** | Web3 platform for sports fans, 1.3M users. NativeScript to React Native migration, and reconversion of a 30-developer team. |
| **Salsify** | Retail SaaS. Accessible design system on React Aria, and progressive migration of a Redux / Redux Saga codebase to React Query and Jotai. |
| **Mittsun** | Workspace booking product built end to end: React Native app, web app, Node backend, Stripe payments, DevOps. |
| **Défimédoc** | Quiz app for pharmacists. Native iOS and Android in-app purchases, automated over-the-air updates. |

---

### Stack

**Mobile** React Native · Expo · EAS Build & Update · Reanimated · Nativewind · App Store & Play Store releases
**Web** React · Next.js (SSR, SEO) · TypeScript · Tailwind · Vue 3
**State & data** React Query · Jotai · Redux · Redux Saga · React Hook Form · Zod · GraphQL · REST
**Quality** Jest · Testing Library · Playwright · Cypress · Storybook · React Aria · WCAG / RGAA · Sentry
**Delivery** GitHub Actions · Fastlane · EAS Build · Turborepo · Docker
**AI** LLM integration in TypeScript: tool calling, RAG, agents, evaluation of model output

---

### Under the hood

The parts that rarely make it into a portfolio, and that decide whether a release ships on a Friday or not.

**Release engineering.** Fastlane lanes for TestFlight and Play test tracks, code signing with certificates encrypted and decrypted on CI, over-the-air updates through CodePush and EAS Update. I have spent enough hours decoding Xcode's more cryptic errors to recognise most of them on sight.

**Testing.** Jest and Testing Library, API mocking with MSW, Detox on React Native, Playwright and Cypress on web. Testing Library because it makes accessibility hard to break by accident.

**Native integrations.** Push notifications through Firebase, payments with Stripe, StoreKit and Play Billing, maps, AR with Viro, chat over GraphQL subscriptions, and charts hand-built in SVG with d3 interpolation rather than a charting library.

**Environments.** Docker and Docker Compose, Traefik with HTTPS on local environments, Ansible for machine setup. UNIX in most of its flavours, Neovim and VS Code.

---

### Currently

Looking for a **Staff Engineer or Tech Lead position**, permanent, in Paris or remote across Europe. Open to freelance missions in parallel.

What I am best at: **migrating an app off a dead or dying framework**, **unifying platforms into a single codebase**, **auditing a codebase nobody dares touch anymore**, and **training a team on React Native**.

On the freelance side, a technical audit takes two to five days and ends with a costed, prioritised plan. You can stop there and keep the plan.
