# Senior QA Automation Engineering Portfolio

A practical portfolio demonstrating Java-based UI automation, REST API testing, framework design, and CI.

> Demo portfolio: these examples use public practice endpoints and are not production test assets.

## Skills demonstrated
- Java, Maven, Selenium WebDriver, TestNG, Page Object Model
- REST Assured API testing and response validation
- Explicit waits, reusable setup, maintainable test structure
- GitHub Actions CI workflow and test report artifacts

## Projects
- `ui-automation/` — Selenium + TestNG starter framework
- `api-automation/` — REST Assured tests for GET, collection, 404, and POST scenarios
- `.github/workflows/api-tests.yml` — runs API tests on push and pull requests
- `docs/framework-design.md` — architecture notes and next steps

## Run locally
Requirements: Java 17+, Maven 3.9+. For UI tests, install Google Chrome.

```bash
cd api-automation
mvn test
```

```bash
cd ../ui-automation
mvn test
```

## Framework principles
1. Keep tests independent and readable.
2. Prefer explicit waits and stable selectors over fixed sleeps.
3. Validate business-relevant response fields, not just status codes.
4. Keep secrets out of source control.
5. Investigate flaky tests rather than masking failures with arbitrary retries.

## About me
I am a QA Automation Engineer focused on maintainable automation, regression confidence, and integrating quality checks into delivery pipelines.

**Personalize before publishing:** add your own introduction, LinkedIn/contact links, and only list tools and experience you can confidently discuss in an interview.
