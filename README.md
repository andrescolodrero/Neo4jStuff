# Neo4jStuff

CSV IMPORT:

AS line FIELDTERMINATOR ';'

Import a file from Windows

LOAD CSV WITH HEADERS FROM "file:///C:/neo.csv" AS csvLine  FIELDTERMINATOR ';'
CREATE (p:NodeNames {  NodeName: csvLine.NodeName })
note: in Neo4J Desktop file to import can be in 
C:\Users\andres\AppData\Roaming\Neo4j Desktop\Application\neo4jDatabases\database-c1e7622c-ae0c-47a4-bcef-f72630916c62\installation-3.3.1\
