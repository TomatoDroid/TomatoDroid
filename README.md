# Hi, I'm TomatoDroid

I'm a frontend developer focused on **Vue 3, TypeScript and interactive web applications**. Based in **China (UTC+8)**, I'm open to remote frontend roles with international teams that can hire in China.

My frontend experience includes browser-based video recording, resumable file uploads, schema-driven forms and permission-aware interfaces.

**Core stack:** Vue 3 · TypeScript · Nuxt · Vite · Pinia · Vue Router

The projects below show my work with browser interactions, state management, accessibility and rendering performance. Each includes a live demo and inspectable source code.

## Selected projects

### Yarn Ocean — an interactive 3D aquarium

[Live demo](https://tomatodroid.github.io/yarn-ocean/) · [Source code](https://github.com/TomatoDroid/yarn-ocean) · [Implementation & validation notes](https://github.com/TomatoDroid/yarn-ocean#readme)

**Built with:** JavaScript, Three.js, HTML and CSS. The interface is in Chinese.

- **Interaction design:** Tap to feed a fish and receive animated heart bubbles. Gesture tracking distinguishes taps from camera drags, long presses and multi-touch, including a drag that returns to its starting point.
- **Accessibility and resilience:** Keyboard feeding and fish selection, reduced-motion behavior, and a static gallery of 20 fish with a retry link when WebGL initialization fails.
- **Resource management:** Reuse bounded pools of food and heart effects, share geometry and textures, and dispose of GPU resources when no longer needed.
- **Rendering performance:** Use instancing and material-based geometry merging, cap pixel density, and pause rendering while the scene is hidden or offscreen.
- **Regression testing:** Node.js tests cover gestures, feeding lifecycles, fallback behavior, swimming and other features. GitHub Actions runs syntax checks and tests before deployment; a [verified CI run on 14 October 2026](https://github.com/TomatoDroid/yarn-ocean/actions/runs/38548928319/job/115801818919) passed **46 tests**.

**Representative merged PRs:** [#1 — feeding, heart feedback and gesture handling](https://github.com/TomatoDroid/yarn-ocean/pull/1) · [#2 — mobile accessibility and static fallback](https://github.com/TomatoDroid/yarn-ocean/pull/2)

The project documents desktop Chrome and mobile touch-emulation checks. **Real-device iOS Safari validation remains pending**; emulation results do not establish mobile hardware performance.

### AI Agent Learning Lab — learn by experimenting

[Live demo](https://tomatodroid.github.io/ai-agent-learning-lab/) · [Source code](https://github.com/TomatoDroid/ai-agent-learning-lab) · [Implementation & validation notes](https://github.com/TomatoDroid/ai-agent-learning-lab#readme)

**Built with:** JavaScript, HTML and CSS. An independent Chinese-language interactive adaptation of Bojie Li's [Understanding AI Agents](https://github.com/bojieli/ai-agent-book), with attribution retained.

- **Learning flow:** Organize concepts into **12 lessons, 12 interactive labs and 24 quiz questions**, with explanations, retryable answers and explicit completion rules.
- **State and data:** Save progress and notes in localStorage, restore them on return, and export notes as Markdown. Data stays in the current browser; it does not sync across devices.
- **Usability:** Responsive navigation, searchable terminology, keyboard-operable learning tabs, focus styles and reduced-motion support.
- **Simple delivery:** A static GitHub Pages site with no build step or API keys. The labs are deterministic teaching simulations.

JavaScript syntax checks pass. The project README records manual walkthroughs of the lessons, quizzes, notes export and desktop/mobile layouts; the repository does not currently include an automated functional test suite.

## What I'm looking for

Remote frontend work on Vue / TypeScript products, developer tools or interactive learning experiences, with room to own features from implementation through testing and iteration.

[Personal website](https://www.liuzhenvip.com/) · [GitHub](https://github.com/TomatoDroid)
