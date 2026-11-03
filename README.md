# Vita Flow

Open in Android Studio (File > Open), sync, run. Package app.vitaflow.com, minSdk 31.

Flow: login or sign up -> detailed profile questions (mandatory, trainer style) -> roadmap -> app.
Tabs: Home (greeting and summary), Fitness (workout, diet), Tasks, Max (chat), Profile (gear icon = settings).
Max listens as soon as the app is open; say "Hey Max".
Settings > সমস্যা নির্ণয় has a voice test and a problem report (what stopped the app and why).
Models are added from Settings > Model (only .litertlm LLM files work).
Fill GoogleConfig.WEB_CLIENT_ID in data/auth/GoogleAuth.kt for Google login.
