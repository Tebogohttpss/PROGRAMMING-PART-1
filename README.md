Initial commit: add README and repo structure
docs: add empty /docs folder with placeholder
docs: draft initial entity list for RaceDay ERD
docs: add Users entity attributes and constraints
docs: add Events entity and relationship to Users
docs: add Categories entity and relationship to Events
docs: add Routes entity
docs: add Enrolments junction table to resolve many-to-many
docs: add Results entity with one-to-one relationship to Enrolments
docs: complete relationship list and cardinalities
docs: add Mermaid ERD diagram source
docs: export ERD as PNG and add to /docs
docs: draft API endpoint plan table structure
	docs: add authentication and user profile endpoints
docs: add events and categories endpoints
docs: add enrolments and results endpoints
docs: add HTTP status codes to endpoint plan
sql: create database and Users/Events tables
sql: add Categories and Routes tables
sql: add Enrolments and Results tables with constraints
sql: add sample data (organisers, participants, events)
sql: add sample categories, enrolments and results
sql: add validation SELECT queries
sql: bracket reserved-style identifiers for SSMS compatibility
sql: test script on clean SQL Server instance and fix errors
ci: add GitHub Actions workflow to validate repo structure
ci: fix workflow file checks after testing
docs: add CI screenshot and role descriptions to README
