# Code Analysis tooling :wrench: comparer for .NET

Here you go:

| Analysis Service      | Features |[C# compiler][roslyn]|[CoreCLR][clr]|[ASP.NET Core][asp]|[NodaTime][noda]|[Git Extensions][gitext]|
|-----------------------|----------|---------------------|--------------|-------------------|----------------|------------------------|
| [Better Code Hub][hub]| | | | | | |
| [Codacy][codacy]      | | | | | | |
| [CodeCov][ccov]       | | | | | | |
| [CodeFactor][cfact]   | | | | | | |
| [Code Climate][clima] | | | | | | |
| [Coveralls][covall]   | | | | | | |
| [Deep Code][deepc]    | | | | | | |
| [LGTM][lgtm]          | | | | | | |
| [Sider][sider]        | | | | | | |
| [SonarCloud][sonar]   | :traffic_light: :speech_balloon: :bar_chart: :umbrella: :gift: | | | | | [![gate][sonar-gitext-gate]][sonar-gitext] [![debt][sonar-gitext-debt]][sonar-gitext] [![cov][sonar-gitext-cov]][sonar-gitext] [![squale][sonar-gitext-squale]][sonar-gitext] [![reliab][sonar-gitext-reliab]][sonar-gitext] [![secur][sonar-gitext-secur]][sonar-gitext] |

**Legend**:

- :traffic_light: Issues reporting
- :speech_balloon: Pull Request analysis
- :bar_chart: Trends (history recording, visualizations)
- :umbrella: Code coverage
- :gift: Free for OSS

**Please note** that the analysis results may be outdated.

# Contribution

You are more than welcome to: 

1. Create an issue to discuss things prior to any effort investment.
2. Create an issue to report a misbehavior/bug.
3. Get assigned an issue to resolve in a PR.

# License

Apache License 2.0 as stated in [LICENSE](./LICENSE).

[hub]: https://bettercodehub.com "Better Code Hub"
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

[sonar-gitext]: https://sonarcloud.io/dashboard?id=GitExtensions
[sonar-gitext-gate]: https://sonarcloud.io/api/project_badges/measure?project=GitExtensions&metric=alert_status
[sonar-gitext-debt]: https://sonarcloud.io/api/project_badges/measure?project=GitExtensions&metric=sqale_index
[sonar-gitext-cov]: https://sonarcloud.io/api/project_badges/measure?project=GitExtensions&metric=coverage
[sonar-gitext-squale]: https://sonarcloud.io/api/project_badges/measure?project=GitExtensions&metric=sqale_rating
[sonar-gitext-reliab]: https://sonarcloud.io/api/project_badges/measure?project=GitExtensions&metric=reliability_rating
[sonar-gitext-secur]: https://sonarcloud.io/api/project_badges/measure?project=GitExtensions&metric=security_rating