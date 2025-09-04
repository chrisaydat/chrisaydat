# Chris Ayeh-Datey — CAD { }
**QA + Software Engineer**  
**Ruthless clarity. Relentless shipping.**  
**Test. Prove. Ship.**

**I build** deterministic mobile automation and developer tooling for Android & Flutter that survive refactors and scale.

**Core Stack**
- **Automation:** Appium • TestNG • UIAutomator • **Maestro** (scripted smokes)
- **Mobile:** **Flutter (Dart)** • Android (Java) • iOS (**Swift/SwiftUI** – learning track)
- **CI/CD & Device Cloud:** GitHub Actions • Azure DevOps • **Genymotion SaaS**
- **Patterns & Reporting:** Page Object Model (POM) • ExtentReports • JUnit XML • custom listeners/step logs

---

## Now
- Hardening a mobile test framework: **stable selectors**, deterministic waits, **parallel** device matrix, report skins
- Porting execution to **Genymotion Cloud** with GitHub Actions (screenshots, logs, artifacts)
- Building **Sartorial** — AI sizing/tailoring (Flutter client + API test harness)

---

## I can help you with
- **Turning flaky UI suites into signal** (selector strategy, timeouts, flake quarantine)
- **Flutter automation** (integration tests, golden tests, **Maestro** smokes)
- **Cloud/device lab setup** (Genymotion/real devices, version pinning, parallel runs)
- **CI you can trust** (Actions/Azure, caching, artifacts, step-level logs)
- **Reports people actually read** (ExtentReports/JUnit XML with screenshots, logcat, step trace)
- **POM architecture** that’s small-surface, composable, and easy to extend

---

## Playbooks
- **Stable Selectors**
  - Prefer `content-desc`/accessibility IDs → anchored `UiSelector` chains → last-resort text  
  - Ban `.instance(n)`; use ancestor/descendant relations  
  - Centralize waits; no raw `Thread.sleep` in tests
- **POM Done Right**
  - One-liner actions & assertions via `Listeners.executeStep(() -> action(), "step text")`  
  - Keep locators private; expose intentful methods
- **Maestro Smokes**
  - YAML flows for “cold-start → key path → happy exit”  
  - Run on PR for fast red/green before the heavier Appium matrix
- **CI/CD**
  - Matrix by Android versions/devices; shard by class; retry **only** quarantined flakes  
  - Always publish: screenshots, videos (if available), logs, HTML report

---

## Badges — Languages, Platforms, Tooling

<!-- Languages -->
![Dart](https://img.shields.io/badge/Dart-0175C2?logo=dart&logoColor=white&style=flat)
![Flutter](https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=white&style=flat)
![Java](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white&style=flat)
![Swift](https://img.shields.io/badge/Swift-FA7343?logo=swift&logoColor=white&style=flat)
![SwiftUI](https://img.shields.io/badge/SwiftUI-0D96F6?logo=swift&logoColor=white&style=flat)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white&style=flat)

<!-- Mobile / OS -->
![Android](https://img.shields.io/badge/Android-3DDC84?logo=android&logoColor=white&style=flat)
![iOS](https://img.shields.io/badge/iOS-000000?logo=apple&logoColor=white&style=flat)

<!-- Automation / Testing -->
![Appium](https://img.shields.io/badge/Appium-9B59B6?logo=appium&logoColor=white&style=flat)
![Maestro](https://img.shields.io/badge/Maestro-000000?style=flat)
![TestNG](https://img.shields.io/badge/TestNG-FF8C00?style=flat)
![UIAutomator](https://img.shields.io/badge/UIAutomator-0B0F14?style=flat)

<!-- CI/CD -->
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white&style=flat)
![Azure DevOps](https://img.shields.io/badge/Azure%20DevOps-0078D7?logo=azuredevops&logoColor=white&style=flat)

<!-- Build & Tools -->
![Gradle](https://img.shields.io/badge/Gradle-02303A?logo=gradle&logoColor=white&style=flat)
![Android Studio](https://img.shields.io/badge/Android%20Studio-3DDC84?logo=androidstudio&logoColor=white&style=flat)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?logo=firebase&logoColor=000&style=flat)
![SQLite](https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=white&style=flat)
![Postman](https://img.shields.io/badge/Postman-FF6C37?logo=postman&logoColor=white&style=flat)
![Jira](https://img.shields.io/badge/Jira-0052CC?logo=jira&logoColor=white&style=flat)
![Figma](https://img.shields.io/badge/Figma-F24E1E?logo=figma&logoColor=white&style=flat)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white&style=flat)

> Tip: change `style=flat` to `style=for-the-badge` if you want bigger, bolder badges.

---

## Principles
**Signal over noise • Small surface area • Repeatable proofs • Green builds are protected • If it isn’t deterministic, it isn’t done.**
