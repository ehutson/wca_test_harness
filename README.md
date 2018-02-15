# wca_test_harness

`docker build -t wca_test_harness:v1 .`

Then

`docker run -d -p 9999:80 wca_test_harness:v1`

Then you should be able to access it by going to
[http://localhost:9999](http://localhost:9999)

*Note*:  If you are using this for local development, it assumes that you are running the API module on port 8088.  You may need to edit `xmlAPIServlet.html` if you need a different port.

