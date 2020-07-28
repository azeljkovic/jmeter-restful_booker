# jmeter-restful_booker
Sample [JMeter] test plan for performance testing against [Restful Booker] application.


## Usage

Replace ```server_name``` user variable with your server address. 

Then import ```restful_booker_test_plan.jmx``` to JMeter or run it via command line:  
```jmeter -n -t restful_booker_test_plan.jmx -l log_file -e -o <Path to output folder>```

[JMeter]: <https://jmeter.apache.org/>
[Restful Booker]: <https://github.com/mwinteringham/restful-booker>
