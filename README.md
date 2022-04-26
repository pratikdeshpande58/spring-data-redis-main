# spring-data-redis

##ENDPOINTS:
1. To add data to redis
URL: http://localhost:9292/pubSubDetails/
Method: POST
Body:{
  "id":101,
  "data":"Enc",
  "status":"com"

}

2. To get All Data:
URL: http://localhost:9292/pubSubDetails/
Method: GET


3. To get Data by id:
URL: http://localhost:9292/pubSubDetails/{id}
Method: GET


4. To DELETE Data by id:
URL: http://localhost:9292/pubSubDetails/{id}
Method: DELETE
