# Reaper-Mock
JSON Server Mock for Reaper.


### Start
Install Node & npm
`sudo npm install -g json-server`
`json-server --watch db.json --routes routes.json`

### Api

- `/api/fund/search?{query}`
- `/api/fund/{code}`
- `/api/fund/{code}/unit-net-value`
- `/api/fund/{code}/cumulative-net-value`
- `/api/fund/{code}/rate?{query}`  
- `/api/fund/{code}/current-assert`
- `/api/fund/{code}/managers`

- `/api/fund/{code}/risk-trend`
- `/api/fund/{code}/daily-retracement`
- `/api/fund/{code}/volatility`
- `/api/fund/{code}/value-at-risk`
- `/api/fund/{code}/downside-volatility`
- `/api/fund/{code}/sharpe-index`
- `/api/fund/{code}/treynor-index`
- `/api/fund/{code}/jensen-index`
- `/api/fund/{code}/information-ratio`

- `/api/fund/{code}/performance-attribution/allocation`
- `/api/fund/{code}/performance-attribution/management`
- `/api/fund/{code}/style-attribution/profit`
- `/api/fund/{code}/style-attribution/risk`
- `/api/fund/{code}/industry-attribution/profit`
- `/api/fund/{code}/industry-attribution/risk`
- `/api/fund/{code}/style-stability/profit`
- `/api/fund/{code}/style-stability/risk`
- `/api/fund/{code}/interest-rate-curve/variety`
- `/api/fund/{code}/interest-rate-curve/ability`


- `/api/manager/{managerId}`  
- `/api/manager/{managerId}/ability`
- `/api/manager/{managerId}/funds`
- `/api/manager/{managerId}/fund-rank`
- `/api/manager/{managerId}/fund-rate-trend`
- `/api/manager/{managerId}/fund-rank-trend`
- `/api/manager/{managerId}/fund-returns`
- `/api/manager/{managerId}/fund-performance`
- `/api/manager/{managerId}/manager-performance`

- `/api/company/{companyId}/fund-performance`
- `/api/company/{companyId}/manager-performance`