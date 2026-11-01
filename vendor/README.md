Local copies of the charting library used by this dashboard.

index.html loads each library from its usual source first and falls back to
these copies only if that source cannot be reached, so charts
keep working on networks that block outside script hosts.

- chart.umd.js            Chart.js 4.4.0 (MIT, see LICENSE-chartjs.md)
