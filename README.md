# Jmeter
node {
  stage 'Run JMeter Test'
  jmeter '/D:/apache-jmeter-5.3/apache-jmeter-5.3/bin/jmeter.bat -n -t //D:/apache-jmeter-5.3/apache-jmeter-5.3/bin/Jmeter_demo.jmx -l Jmeter_demo.jtl'
}
