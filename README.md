## Create job


### POST /api/v1/job 

|name|type|required|note|
|--|--|--|--|
|id| String|*||
|client_id| String|*||
|name| String|*||
|body| String|*|разделитель \n (перенос строки)|

пример
{
  "id": "15f0034b-abd3-4155-9b33-9bc9e00b88fe",
  "client_id": "15f0034b-abd3-4155-9b33-9bc9e00b88fe",
  "name": "job title",
  "body": "kid tool set"
}

## Get reviews job

### GET /api/v1/job/reviews

параметры
|name|type|required|note|
|--|--|--|--|
|job_id|String|*||

пример:

/api/v1/job/reviews?job_id=15f0034b-abd3-4155-9b33-9bc9e00b88fe




## GET /api/v1/job
#### задачи
|name|type|required|note|
|--|--|--|--|
|client_id|String|||
|completed|bool|||
|limit|usize|||
|offset|usize|||


