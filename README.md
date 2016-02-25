# Powerhive2
This application is a RESTFul api that generates random
numbers between -1 and 1, the application also sums the
numbers generated for each request made. 

The application has been developed in Python with the 
Flask microframework

TOOLS & DEPENDANCIES
-------------------- 

- Python 2.7
- Flask microfamework
- virtualenv


DEPLOYMENT.
-----------

The api server can be started from the comand prompt, by 
changing directory to where the random_number_generator.py
file is saved then executing the comand below,

./random_number_generator.py

you should see an output similar to below;

	* Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
 	* Restarting with stat
 	* Debugger is active!
 	* Debugger pin code: 329-437-942

once the server has been successfully started you can then
Access the application by using the GET method
to this url "http://127.0.0.1:5000/",via a web browser or from 
the command prompt using curl.

for getting random number and the sum of the numbers use the command below url

curl -i http://localhost:5000/randomnumber

to reset the accumilator use the below url

curl -i http://localhost:5000/reset
