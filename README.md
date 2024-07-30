## Custom integraration

You need prepare two REST endpoints methods with Bearer authorization:

1. Method POST with params user email, order no
   
   example url: https://shop.com/rj/get.orders.json

   params:

      -email

      -orderNo
   
3. Method GET with no parameters

   example url: https://shop.com/rj/get.statuses.json
