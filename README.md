Auth: manda X-API-KEY: tuLLAVE en cada
request
Endpoints:
GET /health (sin auth)
GET /metrics (sin auth)
GET /products
POTS /products body: {"name": "Lapicero",
"price": 12.5, "stock":100}
GET /products/{id}
PUT /products/{id} body parcial o complemento
DELETE /products/{id}