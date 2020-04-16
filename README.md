# Postman_dummy_testing
http://dummy.restapiexample.com/api/v1/employees

//creat new employer

post
{"name":"rimarimaite","salary":"123000000","age":"23"}

pm.test("Successful POST request", function () {
   pm.expect(pm.response.code).to.be.oneOf([201,202]);
});

update 
{{dummyUrl}}update/23
 {"name":"test1111","salary":"112311","age":"23"}
 
 
