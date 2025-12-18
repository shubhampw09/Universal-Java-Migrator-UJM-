What it does

Detects Maven/Gradle projects
Upgrades Java target using OpenRewrite recipes (e.g., Java 17, Java 21)
Optionally applies framework migrations via OpenRewrite recipe packs (Spring Boot, etc.)
Generates dependency update reports (Maven Versions Plugin)
Optionally runs Renovate in platform=local mode (dry-run) for dependency PR planning
Runs build/tests (optional)
Outputs an updated ZIP of the migrated project + a detailed report
