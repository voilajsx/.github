# VoilaJS Founding Manifesto

## Vision

VoilaJS is a minimalist, AI-ready JavaScript framework that empowers developers to build fast, modular, and scalable web and Progressive Web Apps (PWAs). We simplify development, enable seamless AI code integration, and foster a collaborative community.

## Mission

VoilaJS solves the frustrations of complex frameworks, unreliable AI code, rigid systems, and slow workflows. With a single-click CLI, independent apps, a shared marketplace, and AI-driven design, we enable developers to build rapidly, scale easily, and code confidently for web and mobile.

## Tagline

**VoilaJS - Build Fast, Stay Modular, Code with AI, Web & Mobile Ready**

## Key Pain Points Solved

VoilaJS tackles these developer challenges:

1. **Complex Frameworks**:
   - Steep learning curves slow down development.
   - **Solution**: Minimal `@voilajs/appkit` and a simple CLI ensure quick starts.
2. **Error-Prone AI Code**:
   - LLMs generate unreliable code for large apps due to context limits.
   - **Solution**: Modular apps simplify LLM tasks, producing small, pluggable code with fast error fixes.
3. **Rigid Architectures**:
   - Monoliths hinder scalability and maintenance.
   - **Solution**: Independent apps and microservices support (`service.js`) enable modularity.
4. **Slow Workflows**:
   - Redundant coding delays delivery.
   - **Solution**: Marketplace with reusable apps speeds up development.

## Key Features

These features drive VoilaJS’s value:

1. **Single-Click CLI**:
   - Instantly creates web and PWA apps (`/tools/scaffolder`) with `@voilajs/appkit`.
   - Adds PWA manifests (`theming.js`) for mobile-ready apps.
   - **Supports**: Build Fast, Web & Mobile Ready.
2. **Independent Apps**:
   - Apps in `/apps` have isolated routes (`router.js`), schemas (`database.js`), and logic.
   - Event-driven (`appkit.events`) and microservices-ready (`service.js`) for scalability.
   - **Supports**: Stay Modular.
3. **LLM-Ready Design**:
   - Modular apps enable small, reliable LLM-generated code (e.g., routes).
   - `/platform` APIs and `service.js` configs support plug-and-unplug code swaps.
   - **Supports**: Code with AI.
4. **Marketplace**:
   - Official apps (e.g., `/apps/auth`) and third-party templates (`marketplace.js`) for reuse.
   - Reduces coding and maintenance time.
   - **Supports**: Stay Modular.
5. **PWA Support**:
   - Seamless web-to-PWA with `theming.js` manifests and `router.js` routes.
   - Delivers fast, lightweight mobile apps.
   - **Supports**: Web & Mobile Ready.

## Values

1. **Simplicity**: Easy tools and APIs for all developers.
2. **Modularity**: Independent, reusable components for flexibility.
3. **AI Innovation**: Reliable LLM integration for productivity.
4. **Community**: Shared apps and tools via marketplace.
5. **Reliability**: Production-ready features for trust.

## Focus Points

1. **Speed**: Streamline CLI for instant app creation.
2. **Modularity**: Keep apps isolated with `appkit.events` and `service.js`.
3. **AI Code**: Optimize APIs for small, LLM-generated code units.
4. **Marketplace**: Launch official apps to spark community contributions.
5. **PWA**: Ensure fast, offline-capable PWAs via `theming.js`.

## Things to Avoid

1. **Bloat**: No heavy features or dependencies.
2. **Tight Coupling**: Apps must stay independent.
3. **AI Overpromises**: Focus on small, reliable LLM code, not full apps.
4. **Poor Docs**: Ensure clear, example-rich `/platform/docs`.
5. **Weak Official Apps**: Prioritize quality `/apps/auth`, `/apps/ecommerce`.

## For Founding Developers

- **Build Fast**:
  - Enhance CLI (`/tools/scaffolder`) for one-command web/PWA setup.
  - Use `theming.js` for PWA manifests and fast mobile apps.
  - Write clear `/platform/docs` with CLI and PWA examples.
- **Stay Modular**:
  - Build isolated apps with `router.js`, `database.js`, and `service.js`.
  - Develop marketplace (`marketplace.js`) with `/apps/auth`, `/apps/ecommerce`.
  - Test app swaps to ensure plug-and-unplug works.
- **Code with AI**:
  - Structure `/platform` APIs for LLM-generated routes and components.
  - Create a sample LLM tool (e.g., route generator) in `/tools`.
  - Document LLM error recovery in `/platform/docs`.
- **Team Actions**:
  - Share manifesto in team channels (Discord, Notion).
  - Review features weekly to align with tagline and avoid pitfalls.
  - Collect feedback to refine marketplace and LLM tools.

## Why This Manifesto?

VoilaJS is built to be fast, modular, and AI-ready. This manifesto ensures we:

- Solve real pain points: complexity, AI errors, rigidity, and slow workflows.
- Deliver key features: CLI, modular apps, LLM design, marketplace, PWAs.
- Stay true to values: simplicity, modularity, AI innovation, community, reliability.
- Focus on what matters: speed, modularity, AI code, marketplace, PWAs.
- Avoid traps: bloat, coupling, overpromises, poor docs, weak apps.

## Commitment

As founding developers, we pledge to build VoilaJS with this manifesto as our guide. We’ll create a framework that’s simple to use, modular to scale, and ready for AI, delivering web and mobile apps that developers love and enterprises trust.
