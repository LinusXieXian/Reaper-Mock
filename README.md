# Reaper-Mock
JSON Server Mock for Reaper.


### Start
Install Node & npm
`sudo npm install -g json-server`
`json-server --watch db.json --routes routes.json`

### Api

- `/api/fund/search?{query}`
- `/api/fund/{code}`
- `/api/fund/{id}/unit-net-value`
- `/api/fund/{id}/cumulative-net-value`
- `/api/fund/{id}/rate?{query}`  
- `/api/fund/{id}/current-assert`
- `/api/fund/{id}/managers`
- `/api/manager/{id}`  
