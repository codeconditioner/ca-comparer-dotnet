# :wrench: :hammer: Code Analysis tooling comparer for .NET :hammer: :wrench:

Here you go (hint: click a badge to explore results in a live demo):

| Analysis Service      | Features |[C# compiler][roslyn]|[CoreCLR][clr]|[ASP.NET Core][asp]|[NodaTime][noda]|[Git Extensions][gitext]|
|-----------------------|----------|---------------------|--------------|-------------------|----------------|------------------------|
| [Better Code Hub][bch]| :traffic_light: :speech_balloon: :gift:| | | | | [![bchr][bch-gitext-badge]][bch-gitext] *live demo n/a* |
| [Codacy][codacy]      | :traffic_light: :speech_balloon: :bar_chart: :gift: | | | | | [![badge][codacy-gitext-badge]][codacy-gitext] |
| [CodeCov][ccov]       | | | | | | |
| [CodeFactor][cfact]   | :traffic_light: :speech_balloon: :bar_chart: :gift: | | | | | [![badge][cfact-gitext-badge]][cfact-gitext] |
| [Code Climate][clima] | :traffic_light: :speech_balloon: :bar_chart: :umbrella: | *.NET not supported* | *.NET not supported* | *.NET not supported* | *.NET not supported* | *.NET not supported* |
| [Coveralls][covall]   | | | | | | |
| [Deep Code][deepc]    | :traffic_light: :milky_way: :gift: | | | | | *Failed* (C# recognized as Smalltalk) |
| [LGTM][lgtm]          | | | | | | *Failed* (recognized only .js and .py) |
| [Sider][sider]        | :traffic_light: :speech_balloon: | *.NET not supported* | *.NET not supported* | *.NET not supported* | *.NET not supported* | *.NET not supported* |
| [SonarCloud][sonar]   | :traffic_light: :speech_balloon: :bar_chart: :umbrella: :gift: | | | | | [![gate][sonar-gitext-gate]][sonar-gitext] [![debt][sonar-gitext-debt]][sonar-gitext] [![cov][sonar-gitext-cov]][sonar-gitext] [![squale][sonar-gitext-squale]][sonar-gitext] [![reliab][sonar-gitext-reliab]][sonar-gitext] [![secur][sonar-gitext-secur]][sonar-gitext] |

**Legend**:

- :traffic_light: Issues/measurement reporting
- :speech_balloon: Pull Request analysis
- :bar_chart: Trends (history recording, visualizations)
- :umbrella: Code coverage
- :milky_way: AI based (neural network etc.)
- :gift: Free for OSS

**Please note** that the analysis results may be outdated.

# Contribution

You are more than welcome to: 

1. Create an issue to discuss things prior to any effort investment.
2. Create an issue to report a misbehavior/bug.
3. Get assigned an issue to resolve in a PR.

# License

Apache License 2.0 as stated in [LICENSE](./LICENSE).

[bch]: https://bettercodehub.com "Better Code Hub"
[codacy]: https://codacy.com "Codacy"
[ccov]: https://codecov.io/ "Codecov"
[cfact]: https://www.codefactor.io "CodeFactor"
[clima]: https://codeclimate.com/ "Code Climate"
[covall]: https://coveralls.io/ "Coveralls"
[deepc]: https://www.deepcode.ai/ "Deep Code"
[lgtm]: https://lgtm.com/ "LGTM"
[sider]: https://sider.review/  "Sider"
[sonar]: https://sonarcloud.io/ "SonarCloud"

[roslyn]: https://github.com/dotnet/roslyn "The .NET Compiler Platform (Roslyn)"
[clr]: https://github.com/dotnet/coreclr "The runtime for .NET Core"
[asp]: https://github.com/aspnet/AspNetCore "A cross-platform .NET framework for building web apps."
[noda]: https://github.com/nodatime/nodatime "A better date and time API for .NET"
[gitext]: https://github.com/gitextensions/gitextensions "A standalone UI tool for managing git repositories"

[bch-gitext]: /img/bch-gitext.png
[bch-gitext-badge]: https://bettercodehub.com/edge/badge/wachulski/gitextensions?branch=master
[codacy-gitext]: https://www.codacy.com/app/wachulski/gitextensions?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=wachulski/gitextensions&amp;utm_campaign=Badge_Grade
[codacy-gitext-badge]: https://api.codacy.com/project/badge/Grade/c7e4d208980d4a14b5eb23b76f2d5a01
[cfact-gitext]: https://www.codefactor.io/repository/github/wachulski/gitextensions/
[cfact-gitext-badge]: https://www.codefactor.io/Content/badges/AMinus.svg
[sonar-gitext]: https://sonarcloud.io/dashboard?id=GitExtensions
[sonar-gitext-gate]: https://sonarcloud.io/api/project_badges/measure?project=GitExtensions&metric=alert_status
[sonar-gitext-debt]: https://sonarcloud.io/api/project_badges/measure?project=GitExtensions&metric=sqale_index
[sonar-gitext-cov]: https://sonarcloud.io/api/project_badges/measure?project=GitExtensions&metric=coverage
[sonar-gitext-squale]: https://sonarcloud.io/api/project_badges/measure?project=GitExtensions&metric=sqale_rating
[sonar-gitext-reliab]: https://sonarcloud.io/api/project_badges/measure?project=GitExtensions&metric=reliability_rating
[sonar-gitext-secur]: https://sonarcloud.io/api/project_badges/measure?project=GitExtensions&metric=security_rating