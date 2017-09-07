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

- `/api/manager/{managerId}`  
- `/api/manager/{managerId}/ability`
- `/api/manager/{managerId}/funds`
- `/api/manager/{managerId}/fund-rank`
- `/api/manager/{managerId}/fund-rate-trend`
- `/api/manager/{managerId}/fund-rank-trend`
- `/api/manager/{managerId}/fund-returns`
