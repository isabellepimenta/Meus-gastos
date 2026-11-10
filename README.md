# Meus Gastos — MVVM com Kotlin e Jetpack Compose

Programação Mobile · UNASP-SP · 2026/2

Código-fonte do app (pacote `br.unasp.meusgastos`, minSdk 24).

## Como abrir
1. No Android Studio, crie um projeto **Empty Activity** (Kotlin DSL) chamado `MeusGastos`, package `br.unasp.meusgastos`, minSdk 24.
2. Copie a pasta `app/src/main/java/br/unasp/meusgastos/` deste repositório por cima da do projeto.
3. Em `gradle/libs.versions.toml`:
   - em `[versions]`: `lifecycleViewmodelCompose = "2.8.7"`
   - em `[libraries]`: `androidx-lifecycle-viewmodel-compose = { group = "androidx.lifecycle", name = "lifecycle-viewmodel-compose", version.ref = "lifecycleViewmodelCompose" }`
4. Em `app/build.gradle.kts`, dentro de `dependencies`: `implementation(libs.androidx.lifecycle.viewmodel.compose)`
5. Sync Now → Build > Make Project → Run.
