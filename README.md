# TAGYP API V1 - CURL EXAMPLES

All endpoints require Authorization header:

```
'Authorization: bearer <TOKEN>'
```

#### Subscriptions Create:

```
curl --location --request POST 'https://tagyp-node-zftoosm2vq-ew.a.run.app/v1/subscriptions' \
--header 'Authorization: bearer <TOKEN>' \
--header 'Content-Type: application/json' \
--data-raw '{
   "reference": "12091k209e121",
   "startDate": "2020-12-13",
   "endDate": "2022-12-13"
}'
```

#### Subscriptions Show:

```
curl --location --request GET 'https://tagyp-node-zftoosm2vq-ew.a.run.app/v1/subscriptions/4XjDQxDfkWu8yMCfi8TB' \
--header 'Authorization: bearer <TOKEN>'
```

#### Subscriptions List:

```
curl --location --request GET 'https://tagyp-node-zftoosm2vq-ew.a.run.app/v1/subscriptions' \
--header 'Authorization: bearer <TOKEN>'
```

#### Subscriptions Delete:

```
curl --location --request DELETE 'https://tagyp-node-zftoosm2vq-ew.a.run.app/v1/subscriptions/24810YkWMMuxYlqTY04x' \
--header 'Authorization: bearer <TOKEN>'
```
