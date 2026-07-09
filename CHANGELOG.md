# Changelog

## 3.4.0 (2026-07-09)

* [feat] Upgrade to ghapi 2.x using sync client mode ([#9](https://github.com/coralogix/OTLP-GitHubAction-Exporter/pull/9), thanks @g-sponda)
* [feat] Allow disabling traces, metrics, or logs independently via `OTEL_*_EXPORTER=none` ([#6](https://github.com/coralogix/OTLP-GitHubAction-Exporter/pull/6), thanks @dzaman)
* [feat] Emit histogram metrics for workflow, job, and step duration ([#8](https://github.com/coralogix/OTLP-GitHubAction-Exporter/pull/8), thanks @julesverned)
* [fix] Quote `github.repository` in example `GITHUB_CUSTOM_ATTS` JSON ([#7](https://github.com/coralogix/OTLP-GitHubAction-Exporter/pull/7), thanks @julesverned)
* [fix] Paginate workflow jobs API calls so runs with more than 30 jobs export completely (thanks @gangadhar-res, [StephenGoodall#38](https://github.com/StephenGoodall/OTLP-GitHubAction-Exporter/pull/38))
* [chore] Bump `opentelemetry-sdk` to `>=1.43.0`

## 3.3.2 (2026-07-09)

* [fix] Pin ghapi below 2.0.0 to avoid breaking async API change

## 3.3.1 (2026-03-04)

* [fix] Handle slashes in the Action step's name

## 3.3.0 (2025-08-27)

* [feat] Publish new action to be used by Coralogix integration
