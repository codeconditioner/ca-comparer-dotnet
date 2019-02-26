# :wrench: :hammer: Code Analysis tooling comparer for .NET :hammer: :wrench:

Here you go (hint: click a badge to explore results in a live demo):

| Analysis Service      | Feat. |[C# compiler][roslyn]|[CoreCLR][clr]|[ASP.NET Core][asp]|[NodaTime][noda]|[Git Extensions][gitext]|
|-----------------------|----------|---------------------|--------------|-------------------|----------------|------------------------|
| [Better Code Hub][bch]| :traffic_light: :speech_balloon: :gift:| :x: *(no support >200kLOC)* | :x: *(no support >200kLOC)* | :x: *(no support >200kLOC)* | [![bchr][bch-noda-badge]][bch-noda] | [![bchr][bch-gitext-badge]][bch-gitext] |
| [Codacy][codacy]      | :traffic_light: :speech_balloon: :bar_chart: :gift: | [![badge][codacy-roslyn-badge]][codacy-roslyn] | [![badge][codacy-clr-badge]][codacy-clr] | [![badge][codacy-asp-badge]][codacy-asp] | [![badge][codacy-noda-badge]][codacy-noda] | [![badge][codacy-gitext-badge]][codacy-gitext] |
| [CodeCov][ccov]       | | | | | | prod: [![badge][ccov-gitext-badge-prod]][ccov-gitext]<br/>prod+tests: [![badge][ccov-gitext-badge-prod-test]][ccov-gitext] |
| [Code Factor][cfact]  | :traffic_light: :speech_balloon: :bar_chart: :gift: | [![badge][cfact-roslyn-badge]][cfact-roslyn] | [![badge][cfact-clr-badge]][cfact-clr] | [![badge][cfact-asp-badge]][cfact-asp] | [![badge][cfact-noda-badge]][cfact-noda] | [![badge][cfact-gitext-badge]][cfact-gitext] |
| [Code Scene][scene]   | :traffic_light: :bar_chart: :gift: | [![badge][scene-roslyn-badge]][scene-roslyn] | [![badge][scene-clr-badge]][scene-clr] | [![badge][scene-asp-badge]][scene-asp] | [![badge][scene-noda-badge]][scene-noda] | [![badge][scene-gitext-badge]][scene-gitext] |
| [Coveralls][covall]   | | | | | | |
| [Sonar Cloud][sonar]  | :traffic_light: :speech_balloon: :bar_chart: :umbrella: :gift: | | | | | [![gate][sonar-gitext-gate]][sonar-gitext] [![debt][sonar-gitext-debt]][sonar-gitext] [![cov][sonar-gitext-cov]][sonar-gitext] [![squale][sonar-gitext-squale]][sonar-gitext] [![reliab][sonar-gitext-reliab]][sonar-gitext] [![secur][sonar-gitext-secur]][sonar-gitext] |

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

[roslyn]: https://github.com/dotnet/roslyn "The .NET Compiler Platform (Roslyn)"
[clr]: https://github.com/dotnet/coreclr "The runtime for .NET Core"
[asp]: https://github.com/aspnet/AspNetCore "A cross-platform .NET framework for building web apps."
[noda]: https://github.com/nodatime/nodatime "A better date and time API for .NET"
[gitext]: https://github.com/gitextensions/gitextensions "A standalone UI tool for managing git repositories"

[bch-gitext]: /img/bch-gitext.png
[bch-gitext-badge]: https://bettercodehub.com/edge/badge/wachulski/gitextensions?branch=master
[bch-noda]: /img/bch-noda.png
[bch-noda-badge]: https://bettercodehub.com/edge/badge/codeconditioner/nodatime?branch=master
[ccov-gitext]: https://codecov.io/gh/gitextensions/gitextensions
[ccov-gitext-badge-prod]: https://codecov.io/gh/gitextensions/gitextensions/branch/master/graph/badge.svg?flag=production
[ccov-gitext-badge-prod-test]: https://codecov.io/gh/gitextensions/gitextensions/branch/master/graph/badge.svg
[codacy-roslyn]: https://www.codacy.com/app/code-conditioner/roslyn
[codacy-roslyn-badge]: https://api.codacy.com/project/badge/Grade/8fed6be839824c8586ee8ce704b12182
[codacy-clr]: https://www.codacy.com/app/code-conditioner/coreclr
[codacy-clr-badge]: https://api.codacy.com/project/badge/Grade/2343d15b86e547ae9a78b07640ddaf22
[codacy-asp]: https://www.codacy.com/app/code-conditioner/AspNetCore
[codacy-asp-badge]: https://api.codacy.com/project/badge/Grade/f5b1c3b645844e26b92df6c977e88f76
[codacy-noda]: https://www.codacy.com/app/code-conditioner/nodatime
[codacy-noda-badge]: https://api.codacy.com/project/badge/Grade/ef3644505f7d48629739750edf1de6ff
[codacy-gitext]: https://www.codacy.com/app/wachulski/gitextensions?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=wachulski/gitextensions&amp;utm_campaign=Badge_Grade
[codacy-gitext-badge]: https://api.codacy.com/project/badge/Grade/c7e4d208980d4a14b5eb23b76f2d5a01
[cfact-roslyn]: https://www.codefactor.io/repository/github/codeconditioner/roslyn/
[cfact-roslyn-badge]: https://www.codefactor.io/repository/github/codeconditioner/roslyn/badge
[cfact-clr]: https://www.codefactor.io/repository/github/codeconditioner/coreclr/
[cfact-clr-badge]: https://www.codefactor.io/repository/github/codeconditioner/coreclr/badge
[cfact-asp]: https://www.codefactor.io/repository/github/codeconditioner/AspNetCore/
[cfact-asp-badge]: https://www.codefactor.io/repository/github/codeconditioner/AspNetCore/badge
[cfact-noda]: https://www.codefactor.io/repository/github/codeconditioner/nodatime/
[cfact-noda-badge]: https://www.codefactor.io/repository/github/codeconditioner/nodatime/badge
[cfact-gitext]: https://www.codefactor.io/repository/github/wachulski/gitextensions/
[cfact-gitext-badge]: https://www.codefactor.io/repository/github/wachulski/gitextensions/badge
[scene-roslyn]: https://codescene.io/projects/4203/jobs/latest-successful/results
[scene-roslyn-badge]: https://codescene.io/projects/4203/status.svg
[scene-clr]: https://codescene.io/projects/4201/jobs/latest-successful/results
[scene-clr-badge]: https://codescene.io/projects/4201/status.svg
[scene-asp]: https://codescene.io/projects/4200/jobs/latest-successful/results
[scene-asp-badge]: https://codescene.io/projects/4200/status.svg
[scene-noda]: https://codescene.io/projects/4202/jobs/latest-successful/results
[scene-noda-badge]: https://codescene.io/projects/4202/status.svg
[scene-gitext]: https://codescene.io/projects/4180/jobs/latest-successful/results
[scene-gitext-badge]: https://codescene.io/projects/4180/status.svg
[sonar-gitext]: https://sonarcloud.io/dashboard?id=GitExtensions
[sonar-gitext-gate]: https://sonarcloud.io/api/project_badges/measure?project=GitExtensions&metric=alert_status
[sonar-gitext-debt]: https://sonarcloud.io/api/project_badges/measure?project=GitExtensions&metric=sqale_index
[sonar-gitext-cov]: https://sonarcloud.io/api/project_badges/measure?project=GitExtensions&metric=coverage
[sonar-gitext-squale]: https://sonarcloud.io/api/project_badges/measure?project=GitExtensions&metric=sqale_rating
[sonar-gitext-reliab]: https://sonarcloud.io/api/project_badges/measure?project=GitExtensions&metric=reliability_rating
[sonar-gitext-secur]: https://sonarcloud.io/api/project_badges/measure?project=GitExtensions&metric=security_rating