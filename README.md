# Miguel Araujo

**Engenheiro de Software | Professor Backend (Python/Django) | IA Generativa & Maker**

Homelab: Orange Pi 5 (RK3588, 8-core ARM64, 16GB RAM) + IDT-Lab stack completo
- Ollama local (llama3.2:latest) + n8n + MariaDB/PostgreSQL/ClickHouse + Redis
- Prometheus/Grafana + Tailscale + Docker/k3s + 10 IDEs JetBrains Educational Pack

## Projetos em Destaque

### JetBrains IDE Portfolio (10 IDEs + 4 Extras)
| IDE | Repo | Stack Principal | Benchmark Lab |
|-----|------|-----------------|---------------|
| CLion | [clion-embedded-perf](https://github.com/MiguelFAraujo/clion-embedded-perf) | C++20, ARM/RISC-V, FreeRTOS | 3.2µs interrupt latency |
| DataGrip | [datagrip-sql-analytics](https://github.com/MiguelFAraujo/datagrip-sql-analytics) | SQL Multi-dialect, ClickHouse | 42ms OLAP 100M rows |
| GoLand | [goland-microservices](https://github.com/MiguelFAraujo/goland-microservices) | Go 1.23, gRPC, fuzzing | 142k req/s gRPC |
| IntelliJ | [intellij-spring-boot](https://github.com/MiguelFAraujo/intellij-spring-boot) | Java 21, Spring Boot 3, GraalVM | 0.07s native startup |
| PhpStorm | [phpstorm-laravel-api](https://github.com/MiguelFAraujo/phpstorm-laravel-api) | PHP 8.3, Laravel 11, Octane | 28k req/s Swoole |
| PyCharm | [pycharm-fastapi-ml](https://github.com/MiguelFAraujo/pycharm-fastapi-ml) | Python 3.12, FastAPI, PyTorch | 22k req/s + 34ms inferencia |
| Rider | [rider-dotnet-api](https://github.com/MiguelFAraujo/rider-dotnet-api) | .NET 8, C# 12, AOT | 112k req/s gRPC |
| RubyMine | [rubymine-rails-api](https://github.com/MiguelFAraujo/rubymine-rails-api) | Ruby 3.3, Rails 7.2, Hotwire | 11k req/s Puma |
| RustRover | [rustrover-async-wasm](https://github.com/MiguelFAraujo/rustrover-async-wasm) | Rust 1.80, Tokio, WASM | 145k req/s Axum |
| WebStorm | [webstorm-nextjs-dashboard](https://github.com/MiguelFAraujo/webstorm-nextjs-dashboard) | TS 5.5, Next.js 15, React 19 | 0.9s LCP |

### Projetos Especializados
| Projeto | Repo | Stack | Destaque |
|---------|------|-------|----------|
| PHP Octane | [php-octane-api](https://github.com/MiguelFAraujo/php-octane-api) | PHP 8.3, Swoole/FrankenPHP | 32k req/s Swoole |
| Delphi Cross-Platform | [delphi-crossplatform](https://github.com/MiguelFAraujo/delphi-crossplatform) | Delphi 12, FireMonkey | Linux ARM64 nativo |
| Java GraalVM Native | [java-graalvm-native](https://github.com/MiguelFAraujo/java-graalvm-native) | Java 21, GraalVM 24, AOT | 0.07s startup, 38MB |
| NASA Data Challenges | [nasa-data-challenges](https://github.com/MiguelFAraujo/nasa-data-challenges) | Multi-linguagem (10 IDEs) | 5 pipelines NASA reais |

### Projetos Principais (Producao)
- [omniroute-resilience](https://github.com/MiguelFAraujo/omniroute-resilience) - Monitor resiliencia OmniRoute/OpenAI (4★)
- [telebot-cognitive](https://github.com/MiguelFAraujo/telebot-cognitive) - Bot Telegram disciplinado (4★)
- [inteligencia-do-topo](https://github.com/MiguelFAraujo/inteligencia-do-topo) - Site institucional
- [lab-blueprint](https://github.com/MiguelFAraujo/lab-blueprint) - Blueprint homelab open-source
- [arduino-na-veia](https://github.com/MiguelFAraujo/arduino-na-veia) - Referencia maker brasileiro

## Stack do Lab (IDT-Lab)

```
Orchestration: n8n + Docker Compose + systemd
Databases: MariaDB 11.4, PostgreSQL 16, ClickHouse 24.3, Redis 7
Observability: Prometheus 2.54, Grafana 11, Uptime Kuma, Netdata, Dozzle
AI Local: Ollama (llama3.2:latest) @ localhost:11434/v1
Gateway: OmniRoute (resilience monitorado)
Remote: Tailscale (SSH, VNC, noVNC, RustDesk)
CI/CD: GitHub Actions + n8n deploy -> k3s
```

## Metodologia

- **TDD** com red-green-refactor
- **Benchmarks reais** no hardware do lab (Orange Pi 5)
- **AI-assisted development** com Ollama local (code review, SQL generation, analise)
- **Observabilidade completa** em todos os projetos (Prometheus metrics, Grafana dashboards)
- **Deploy automatizado** via n8n workflows para k3s no lab

## Contato

- GitHub: [@MiguelFAraujo](https://github.com/MiguelFAraujo)
- Site: [inteligenciadotopo.com.br](https://inteligenciadotopo.com.br)
- Telegram: @MiguelFAraujo

---

*Desenvolvido no IDT-Lab com Educational Pack JetBrains BD24G146N7 (valido ate 2027-08-23)*
