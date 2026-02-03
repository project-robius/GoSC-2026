# GoSC 2026 : Intro to the Robius Ecosystem: Makepad, Moly, Robrix & Tooling

This issue briefly introduces several core parts of the Robius ecosystem and provides links for anyone who wants to explore or contribute.

---

## Makepad

Makepad is a cross‑platform UI toolkit written in Rust, focused on high‑performance rendering and a very fast edit–build–run cycle. It powers many of our demos and is the primary UI stack for Robrix.

Robius‑related Makepad example apps:

- Social media feed demo:  
  [makepad_social_media_feed](https://github.com/project-robius/makepad_social_media_feed)  
- WeChat‑style chat UI:  
  [makepad_wechat](https://github.com/project-robius/makepad_wechat)  
- Taobao/eBay‑style shopping UI:  
  [makepad_taobao](https://github.com/project-robius/makepad_taobao)  
- TikTok‑style short video UI:  
  [makepad_tiktok](https://github.com/project-robius/makepad_tiktok)  
- Widgets gallery:  
  [makepad_widgets_sample](https://github.com/project-robius/makepad_widgets_sample)  
- Image manipulation demo:  
  [makepad_image_manipulation](https://github.com/project-robius/makepad_image_manipulation)

---

## Moly AI App (moly.ai)

Moly is an open‑source, cross‑platform AI LLM chat client built with Rust + Makepad. It also serves as a showcase app for the Project Robius stack.

- Website: Moly AI App — Your Cross‑Platform AI Companion  
- Source / issues / contributions:  
  [moly-ai/moly-ai](https://github.com/moly-ai/moly-ai)  
- Downloads (macOS / Windows / Linux, etc.):  
  [Download Moly](https://github.com/moly-ai/moly-ai/releases)

Key points:

- Cross‑platform: native apps for macOS, Linux, and Windows; iOS/Android/Web are in active development  
- Local + cloud models: supports OpenAI/Anthropic and other cloud providers, plus local LLMs via Moly Server  
- Open‑source & extensible: Apache 2.0 license, extensible via MolyKit for custom AI apps  
- Privacy‑first: supports fully local inference and secure access to cloud providers

---

## Robrix

Robrix is a multi‑platform Matrix chat client built with Makepad and the Robius platform. It is one of the flagship applications in the Robius ecosystem.

- Client source:  
  [project-robius/robrix](https://github.com/project-robius/robrix)  
- Website / documentation:  
  [project-robius/robrix-website](https://github.com/project-robius/robrix-website)

---

## Robius Platform & Tooling

This is the “under the app” layer: platform abstractions and tooling that help Rust apps actually run on multiple platforms and ship to app stores.

- Multi‑platform system abstraction (platform capabilities layer):  
  [project-robius/robius](https://github.com/project-robius/robius)

- Simple platform demo app (how to use Robius platform crates):  
  [project-robius/robius-demo-simple](https://github.com/project-robius/robius-demo-simple)

- Packaging helper (works with `cargo-packager`):  
  [project-robius/robius-packaging-commands](https://github.com/project-robius/robius-packaging-commands)

- Android build integration (generating Java/Android code from Rust build scripts):  
  [project-robius/android-build](https://github.com/project-robius/android-build)

- Directories fork with Android support:  
  [project-robius/robius-directories](https://github.com/project-robius/robius-directories)
