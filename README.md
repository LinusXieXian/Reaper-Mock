# Reaper-Mock
JSON Server Mock for Reaper.


### Start
Install Node & npm

`sudo npm install -g json-server`

`json-server --watch db.json --routes routes.json`

### Api

- `/api/user`

- `/api/fund/search?{query}`
- `/api/fund/{code}`
- `/api/fund/{code}/name`
- `/api/fund/{code}/unit-net-value`
- `/api/fund/{code}/cumulative-net-value`
- `/api/fund/{code}/rate?{query}`  
- `/api/fund/{code}/current-asset`
- `/api/fund/{code}/managers`
- `/api/fund/{code}/manager`
- `/api/fund/{code}/company`

- `/api/fund/{code}/risk-trend`
- `/api/fund/{code}/daily-retracement`
- `/api/fund/{code}/volatility`
- `/api/fund/{code}/value-at-risk`
- `/api/fund/{code}/downside-volatility`
- `/api/fund/{code}/sharpe-index`
- `/api/fund/{code}/treynor-index`
- `/api/fund/{code}/jensen-index`
- `/api/fund/{code}/information-ratio`
- `/api/fund/{code}/performance-index`

- `/api/fund/{code}/style-attribution/profit`
- `/api/fund/{code}/style-attribution/risk`
- `/api/fund/{code}/industry-attribution/profit`
- `/api/fund/{code}/industry-attribution/risk`
- `/api/fund/{code}/style-stability/profit`
- `/api/fund/{code}/style-stability/risk`
- `/api/fund/{code}/variety-attribution`
- `/api/fund/{code}/brison-attribution/stock`
- `/api/fund/{code}/brison-attribution/bond`
- `/api/fund/{code}/choose-time-stock`
- `/api/fund/{code}/fund-performance`
- `/api/fund/{code}/manager-performance`
- `/api/fund/{code}/public-opinion`
- `/api/fund/{code}/position-network`

- `/api/manager/{managerId}`  
- `/api/manager/{managerId}/ability`
- `/api/manager/{managerId}/funds`
- `/api/manager/{managerId}/fund-rank`
- `/api/manager/{managerId}/fund-rate-trend`
- `/api/manager/{managerId}/fund-rank-trend`
- `/api/manager/{managerId}/fund-returns`
- `/api/manager/{managerId}/fund-performance`
- `/api/manager/{managerId}/manager-performance`
- `/api/manager/{managerId}/social-network`

- `/api/company/{companyId}/fund-performance`
- `/api/company/{companyId}/manager-performance`
- `/api/company/{companyId}/product-strategy`
- `/api/company/{companyId}/asset-allocation`
- `/api/company/{companyId}/style-attribution/profit`
- `/api/company/{companyId}/style-attribution/risk`
- `/api/company/{companyId}/industry-attribution/profit`
- `/api/company/{companyId}/industry-attribution/risk`

- `/api/combination`
- `/api/combination/{combinationId}/backtest`