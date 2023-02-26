### Installation

Install allure https://docs.qameta.io/allure/.

### Test Runner

npx playwright test --trace on
npx playwright show-report

allure generate ./allure-results --clean
allure open ./allure-report
