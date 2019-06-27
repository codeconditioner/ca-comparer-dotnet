Code analysis cloud services catalog, for .NET :hammer: 

Here you go (hint: click a badge to explore results in a live demo):

| Analysis Service      | Feat. |[Entity Framework Core][ef] (a framework)|[NodaTime][noda] (a library)|[Git Extensions][gitext] (a desktop app)|
|-----------------------|-------|-----------------------------------------|----------------------------|----------------------------------------|
| [Better Code Hub][bch]| :traffic_light: :speech_balloon: :gift:| :x: *(no support >200kLOC)* | [![bchr][bch-noda-badge]][bch-noda] | [![bchr][bch-gitext-badge]][bch-gitext] |
| [Codacy][codacy]      | :traffic_light: :speech_balloon: :bar_chart: :gift: | [![badge][codacy-ef-badge]][codacy-ef] | [![badge][codacy-noda-badge]][codacy-noda] | [![badge][codacy-gitext-badge]][codacy-gitext] |
| [CodeCov][ccov]       | :speech_balloon: :umbrella: :gift: | prod: [![badge][ccov-ef-badge]][ccov-ef] | prod+tests: [![badge][ccov-noda-badge]][ccov-noda] | prod: [![badge][ccov-gitext-badge-prod]][ccov-gitext]<br/>prod+tests: [![badge][ccov-gitext-badge-prod-test]][ccov-gitext] |
| [Code Factor][cfact]  | :traffic_light: :speech_balloon: :bar_chart: :gift: | [![badge][cfact-ef-badge]][cfact-ef] | [![badge][cfact-noda-badge]][cfact-noda] | [![badge][cfact-gitext-badge]][cfact-gitext] |
| [Code Scene][scene]   | :traffic_light: :bar_chart: :gift: | [![badge][scene-ef-badge]][scene-ef] | [![badge][scene-noda-badge]][scene-noda] | [![badge][scene-gitext-badge]][scene-gitext] |
| [Coveralls][covall]   | :speech_balloon: :umbrella: :gift: | [![badge][covall-ef-badge]][covall-ef] | [![badge][covall-noda-badge]][covall-noda] | [![badge][covall-gitext-badge]][covall-gitext] |
| [Sonar Cloud][sonar]  | :traffic_light: :speech_balloon: :bar_chart: :umbrella: :gift: | [![gate][sonar-ef-gate]][sonar-ef] [![debt][sonar-ef-debt]][sonar-ef] [![cov][sonar-ef-cov]][sonar-ef] [![squale][sonar-ef-squale]][sonar-ef] [![reliab][sonar-ef-reliab]][sonar-ef] [![secur][sonar-ef-secur]][sonar-ef] | [![gate][sonar-noda-gate]][sonar-noda] [![debt][sonar-noda-debt]][sonar-noda] [![cov][sonar-noda-cov]][sonar-noda] [![squale][sonar-noda-squale]][sonar-noda] [![reliab][sonar-noda-reliab]][sonar-noda] [![secur][sonar-noda-secur]][sonar-noda] | [![gate][sonar-gitext-gate]][sonar-gitext] [![debt][sonar-gitext-debt]][sonar-gitext] [![cov][sonar-gitext-cov]][sonar-gitext] [![squale][sonar-gitext-squale]][sonar-gitext] [![reliab][sonar-gitext-reliab]][sonar-gitext] [![secur][sonar-gitext-secur]][sonar-gitext] |

**Legend**:

- :traffic_light: Issues/measurement reporting
- :speech_balloon: Pull Request analysis
- :bar_chart: Trends (history recording, visualizations)
- :umbrella: Code coverage
- :milky_way: AI based (neural network etc.)
- :gift: Free for OSS

**Please note** that the analysis results may be outdated.

**.NET not supported (nor reliable) in:**

* [Code Climate][clima]: :traffic_light: :speech_balloon: :bar_chart: :umbrella: *Not supported*
* [Deep Code][deepc]: :traffic_light: :milky_way: :gift: *Failed (C# recognized as Smalltalk)*
* [LGTM][lgtm]: :traffic_light: :speech_balloon: :bar_chart: :gift: *Failed (recognized only .js and .py)*
* [Sider][sider]: :traffic_light: :speech_balloon: *Not supported*

# Contribution

You are more than welcome to: 

1. Create an issue to discuss things prior to any effort investment.
2. Create an issue to report a misbehavior/bug.
3. Get assigned an issue to resolve in a PR.

# License

Creative Commons Attribution 4.0 International as stated in [LICENSE](./LICENSE).



[bch]: https://bettercodehub.com "Better Code Hub"
[codacy]: https://codacy.com "Codacy"
[ccov]: https://codecov.io/ "Codecov"
[cfact]: https://www.codefactor.io "CodeFactor"
[clima]: https://codeclimate.com/ "Code Climate"
[covall]: https://coveralls.io/ "Coveralls"
[deepc]: https://www.deepcode.ai/ "Deep Code"
[lgtm]: https://lgtm.com/ "LGTM"
[scene]: https://codescene.io/ "Code Scene"
[sider]: https://sider.review/  "Sider"
[sonar]: https://sonarcloud.io/ "SonarCloud"

[ef]: https://github.com/aspnet/AspNetCore "A lightweight and extensible version of the popular data access technology."
[noda]: https://github.com/nodatime/nodatime "A better date and time API for .NET"
[gitext]: https://github.com/gitextensions/gitextensions "A standalone UI tool for managing git repositories"

[bch-gitext]: /img/bch-gitext.png
[bch-gitext-badge]: https://bettercodehub.com/edge/badge/wachulski/gitextensions?branch=master
[bch-noda]: /img/bch-noda.png
[bch-noda-badge]: https://bettercodehub.com/edge/badge/codeconditioner/nodatime?branch=master
[ccov-ef]: https://codecov.io/gh/codeconditioner/EntityFrameworkCore/branch/CodeCov
[ccov-ef-badge]: https://codecov.io/gh/codeconditioner/EntityFrameworkCore/branch/CodeCov/graph/badge.svg
[ccov-noda]: https://codecov.io/gh/nodatime/nodatime
[ccov-noda-badge]: https://codecov.io/gh/nodatime/nodatime/branch/master/graph/badge.svg
[ccov-gitext]: https://codecov.io/gh/gitextensions/gitextensions
[ccov-gitext-badge-prod]: https://codecov.io/gh/gitextensions/gitextensions/branch/master/graph/badge.svg?flag=production
[ccov-gitext-badge-prod-test]: https://codecov.io/gh/gitextensions/gitextensions/branch/master/graph/badge.svg
[codacy-ef]: https://www.codacy.com/app/code-conditioner/EntityFrameworkCore
[codacy-ef-badge]: https://api.codacy.com/project/badge/Grade/6bafdf803f12431a9721cc3224c02229
[codacy-noda]: https://www.codacy.com/app/code-conditioner/nodatime
[codacy-noda-badge]: https://api.codacy.com/project/badge/Grade/ef3644505f7d48629739750edf1de6ff
[codacy-gitext]: https://www.codacy.com/app/wachulski/gitextensions?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=wachulski/gitextensions&amp;utm_campaign=Badge_Grade
[codacy-gitext-badge]: https://api.codacy.com/project/badge/Grade/c7e4d208980d4a14b5eb23b76f2d5a01
[covall-ef]: https://coveralls.io/github/codeconditioner/EntityFrameworkCore
[covall-ef-badge]: https://coveralls.io/repos/github/codeconditioner/EntityFrameworkCore/badge.svg
[covall-noda]: https://coveralls.io/repos/github/codeconditioner/nodatime
[covall-noda-badge]: https://coveralls.io/repos/github/codeconditioner/nodatime/badge.svg
[covall-gitext]: https://coveralls.io/repos/github/codeconditioner/gitextensions
[covall-gitext-badge]: https://coveralls.io/repos/github/codeconditioner/gitextensions/badge.svg?branch=coveralls
[cfact-ef]: https://www.codefactor.io/repository/github/codeconditioner/entityframeworkcore/
[cfact-ef-badge]: https://www.codefactor.io/repository/github/codeconditioner/entityframeworkcore/badge
[cfact-noda]: https://www.codefactor.io/repository/github/codeconditioner/nodatime/
[cfact-noda-badge]: https://www.codefactor.io/repository/github/codeconditioner/nodatime/badge
[cfact-gitext]: https://www.codefactor.io/repository/github/wachulski/gitextensions/
[cfact-gitext-badge]: https://www.codefactor.io/repository/github/wachulski/gitextensions/badge
[scene-ef]: https://codescene.io/projects/4454/jobs/latest-successful/results
[scene-ef-badge]: https://codescene.io/projects/4454/status.svg
[scene-noda]: https://codescene.io/projects/4202/jobs/latest-successful/results
[scene-noda-badge]: https://codescene.io/projects/4202/status.svg
[scene-gitext]: https://codescene.io/projects/4180/jobs/latest-successful/results
[scene-gitext-badge]: https://codescene.io/projects/4180/status.svg
[sonar-ef]: https://sonarcloud.io/dashboard?id=EntityFrameworkCore
[sonar-ef-gate]: https://sonarcloud.io/api/project_badges/measure?project=EntityFrameworkCore&metric=alert_status
[sonar-ef-debt]: https://sonarcloud.io/api/project_badges/measure?project=EntityFrameworkCore&metric=sqale_index
[sonar-ef-cov]: https://sonarcloud.io/api/project_badges/measure?project=EntityFrameworkCore&metric=coverage
[sonar-ef-squale]: https://sonarcloud.io/api/project_badges/measure?project=EntityFrameworkCore&metric=sqale_rating
[sonar-ef-reliab]: https://sonarcloud.io/api/project_badges/measure?project=EntityFrameworkCore&metric=reliability_rating
[sonar-ef-secur]: https://sonarcloud.io/api/project_badges/measure?project=EntityFrameworkCore&metric=security_rating
[sonar-noda]: https://sonarcloud.io/dashboard?id=nodatime
[sonar-noda-gate]: https://sonarcloud.io/api/project_badges/measure?project=nodatime&metric=alert_status
[sonar-noda-debt]: https://sonarcloud.io/api/project_badges/measure?project=nodatime&metric=sqale_index
[sonar-noda-cov]: https://sonarcloud.io/api/project_badges/measure?project=nodatime&metric=coverage
[sonar-noda-squale]: https://sonarcloud.io/api/project_badges/measure?project=nodatime&metric=sqale_rating
[sonar-noda-reliab]: https://sonarcloud.io/api/project_badges/measure?project=nodatime&metric=reliability_rating
[sonar-noda-secur]: https://sonarcloud.io/api/project_badges/measure?project=nodatime&metric=security_rating
[sonar-gitext]: https://sonarcloud.io/dashboard?id=GitExtensions
[sonar-gitext-gate]: https://sonarcloud.io/api/project_badges/measure?project=GitExtensions&metric=alert_status
[sonar-gitext-debt]: https://sonarcloud.io/api/project_badges/measure?project=GitExtensions&metric=sqale_index
[sonar-gitext-cov]: https://sonarcloud.io/api/project_badges/measure?project=GitExtensions&metric=coverage
[sonar-gitext-squale]: https://sonarcloud.io/api/project_badges/measure?project=GitExtensions&metric=sqale_rating
[sonar-gitext-reliab]: https://sonarcloud.io/api/project_badges/measure?project=GitExtensions&metric=reliability_rating
[sonar-gitext-secur]: https://sonarcloud.io/api/project_badges/measure?project=GitExtensions&metric=security_rating