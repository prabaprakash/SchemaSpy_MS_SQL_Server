Pre-Requiste

1. Install Graphviz - http://www.graphviz.org/Download..php
  
2. Install Java Development Kit 8/7

3. Set Enironment Path for "JDK" & "Graphviz"


Finally,


`java -jar schemaSpy_5.0.0.jar -dp "jtds-1.3.1.jar" -t mssql-jtds  -db DATABASE_NAME -host "172.16.16.1" -port 4133 -u "username" -p "password" -o output -s "schema_name" `