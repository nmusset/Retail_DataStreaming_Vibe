# Architecture Overview

The overall simplified workflow is:
database -> transformation -> client system

Basically an ETL system.

* From client of view:
    - Database with the data tables about tickets, products, catalog, store, etc.
    - Client endpoint where the data must be received
    - in between a system that collects changes (delta) from specific tables in the database, and sends them to a client in a format specific to the client's need


* From functional team point of view:
composants:
    - configuration to tell from which database and from table the data is taken from, and where the data is sent
    - deliverable in a form of script, binary, or whole packages (not decided yet)
    - way to give, send or apply that deliverable to the platform so that data taken from the database is transformed to the client requirements and then sent to the client endpoint

* From the platform team point of view:
    - a platform that is able to listen to database changes, apply data transformation which rules are given by the functional team, and with connector to external system endpoints to be able to send the data
    - logging, metrics and monitoring
    - ability to have several workflows in parallel from the same databse or several databases
