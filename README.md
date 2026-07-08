# banco-api-performance
set "K6_WEB_DASHBOARD=true" && set "K6_WEB_DASHBOARD_EXPORT=html-report.html" && k6 run tests\login.test.js