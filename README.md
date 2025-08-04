
###############################################################################

CXF-JMX example
============================================
The cxf-jmx example illustrates how to enable CXF for JMX for web service
providers contained either within a war file deployed in Tomcat or an OSGI bundle
deployed in the TESB OSGi container.

The web service provides simple sayHi and doubleIt operations.

After deploying the samples you can see CXF MBeans and their attributes that
can be monitored using the Sun JDK's JConsole.  Attributes also form the metrics
that we will monitor with help of HypericHQ.

See also:
https://cwiki.apache.org/CXF20DOC/jmx-management.html
http://download.oracle.com/javase/1.5.0/docs/guide/management/jconsole.html


