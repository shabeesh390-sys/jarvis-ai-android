# JARVIS AI (Android, Kotlin + Compose)
1. backend/worker.js -> Cloudflare Worker (secrets: ANTHROPIC_API_KEY, APP_TOKEN).
2. Build APK: push this project to GitHub; Actions builds it (.github/workflows/build.yml). Download the APK from the run's Artifacts.
   Phone shortcut: put jarvis.zip + .github/workflows/build.yml in a repo root; the workflow unzips and builds.
3. In the app: Settings -> paste Worker URL + APP_TOKEN. Enable Usage Access from the Usage tab.
