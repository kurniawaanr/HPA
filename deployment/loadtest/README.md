# Load Testing Using Apache JMeter[^1]

to test apache Jmeter using CLI, use this command:

```
/opt/apache-jmeter/bin/jmeter.sh -n -t /opt/apache-jmeter/bin/templates/testplan.jmx -l /opt/apache-jmeter/reports/testresult.jtl -e -o /opt/apache-jmeter/reports/
```

to configure using Jmeter GUI, to access :

```
/opt/apache-jmeter/bin/jmeter.sh
```

## References
[^1]: testing with apache JMeter [source](https://www.linuxbabe.com/linux-server/apache-jmeter-load-testing)