# Postman_dummy_testing
http://dummy.restapiexample.com/api/v1/employees

//creat new employer

pm.test("Successful POST request", function () {
   pm.expect(pm.response.code).to.be.oneOf([201,202]);
});
