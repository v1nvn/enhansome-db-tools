# Awesome Database Tools [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) with stars

> Community driven list of database tools

Here we will collect information about awesome useful and awesome experimental tools that simplify working with databases for DBA, DevOps, Developers and mere mortals.

Feel free to add information about your own db-tools or your favorite third-party db-tools.

For updates on `awesome-db-tools` and thoughts/news about databases/tools/SQL follow me at [@GraminMaksim](https://twitter.com/GraminMaksim)

## Contents

* [IDE](#ide)
* [GUI](#gui)
* [CLI](#cli)
* [Schema](#schema)
  * [Changes](#changes)
  * [Code generation](#code-generation)
  * [Diagrams](#diagrams)
  * [Documentations](#documentations)
  * [Design](#design)
  * [Samples](#samples)
* [API](#api)
* [Application platforms](#application-platforms)
* [Backup](#backup)
* [Cloning](#cloning)
* [Monitoring/Statistics/Perfomance](#monitoringstatisticsperfomance)
  * [Prometheus](#prometheus)
  * [Zabbix](#zabbix)
* [Testing](#testing)
* [HA/Failover/Sharding](#hafailoversharding)
* [Kubernetes](#kubernetes)
* [Configuration Tuning](#configuration-tuning)
* [DevOps](#devops)
* [Reporting](#reporting)
* [Distributions](#distributions)
* [Security](#security)
* [SQL](#sql)
  * [Analyzers](#analyzers)
  * [Extensions](#extensions)
  * [Frameworks](#frameworks)
  * [Formatters](#formatters)
  * [Games](#games)
  * [Parsers](#parsers)
  * [Über SQL](#über-sql)
  * [Language Server Protocol](#language-server-protocol)
  * [Learning](#learning)
  * [Plan](#plan)
  * [Scripts](#scripts)
* [Data](#data)
  * [Catalog](#catalog)
  * [Lineage](#lineage)
  * [Generation/Masking/Subsetting](#generationmaskingsubsetting)
  * [Data Profilers](#data-profilers)
  * [Replication](#replication)
  * [Compare](#compare)
* [Papers](#papers)
* [Machine Learning](#machine-learning)

## IDE

* [DBeaver](https://github.com/dbeaver/dbeaver) ⭐ 48,690 | 🐛 3,227 | 🌐 Java | 📅 2026-02-15 - Free universal database manager and SQL client.
* [HeidiSQL](https://github.com/HeidiSQL/HeidiSQL) ⭐ 5,803 | 🐛 419 | 🌐 Pascal | 📅 2026-02-15 - A lightweight client for managing MySQL, MSSQL and PostgreSQL, written in Delphi.
* [DataStation](https://github.com/multiprocessio/datastation) ⭐ 2,958 | 🐛 38 | 🌐 TypeScript | 📅 2023-11-10 - Easily query, script, and visualize data from every database, file, and API.
* [Querybook](https://github.com/pinterest/querybook) ⭐ 2,233 | 🐛 202 | 🌐 TypeScript | 📅 2026-02-13 - Pinterest open-source Big Data Querying UI, combining collocated table metadata and a simple notebook IDE interface.
* [Slashbase](https://github.com/slashbaseide/slashbase) ⚠️ Archived - The open-source collaborative IDE for your databases. Connect to your database, browse data, run a bunch of SQL commands or share SQL queries with your team, right from your browser.
* [dbKoda](https://github.com/SouthbankSoftware/dbkoda) ⚠️ Archived - Modern (JavaScript/Electron framework), open source IDE for MongoDB. It has features to support development, administration and performance tuning on MongoDB databases.
* [Kangaroo](https://github.com/dbkangaroo/kangaroo) ⭐ 463 | 🐛 27 | 🌐 TSQL | 📅 2026-02-09 - A AI-powered SQL client and admin tool for popular databases(SQLite / MySQL / PostgreSQL / etc) on Windows / macOS / Linux, support table design, query, model, sync, export/import etc, focus on comfortable, fun and developer friendly.
* [TOra](https://github.com/tora-tool/tora) ⭐ 294 | 🐛 64 | 🌐 C++ | 📅 2024-03-03 - Open source SQL IDE for Oracle, MySQL and PostgreSQL dbs.
* [AnySQL Maestro](https://www.sqlmaestro.com/products/anysql/maestro) - Premier multi-purpose admin tool for database management, control and development.
* [Aqua Data Studio](https://www.aquafold.com/aquadatastudio) - Productivity software for Database Developers, DBAs, and Analysts.
* [Coginiti Pro](https://www.coginiti.co/products/coginiti-pro/) - Modern IDE for analyst and analytics engineers with proweful script and grid functionality.
* [Database .net](http://fishcodelib.com/Database.htm) - Multiple database management tool with support for 20+ databases.
* [Database Workbench](https://www.upscene.com/database_workbench/) - Complete IDE for database design, development and testing for Oracle, SQL Server, PostgreSQL, MySQL, MariaDB, Firebird, InterBase, SQLite and NexusDB.
* [DataGrip](https://www.jetbrains.com/datagrip) - Cross-Platform IDE for Databases & SQL by JetBrains.
* [dbForge Edge](https://www.devart.com/dbforge/edge/) - Multidatabase solution for DB development, design, management, and administration of MySQL, MariaDB, SQL Server, Oracle, PostgreSQL databases, and various cloud services.
* [dbForge Studio for MySQL](https://www.devart.com/dbforge/mysql/studio) - Universal IDE for MySQL and MariaDB database development, management, and administration.
* [dbForge Studio for Oracle](https://www.devart.com/dbforge/oracle/studio) - Powerful IDE for Oracle management, administration, and development.
* [dbForge Studio for PostgreSQL](https://www.devart.com/dbforge/postgresql/studio) - GUI tool for managing and developing databases and objects.
* [dbForge Studio for SQL Server](https://www.devart.com/dbforge/sql/studio) - Powerful integrated development environment for SQL Server development, management, administration, data analysis, and reporting.
* [DBHawk](https://www.datasparc.com/) - Datasparc offers database security, database management, database governance and data analytics - all in one solution.
* [IBExpert](http://www.ibexpert.net/ibe) - Comprehensive GUI tool for Firebird and InterBase.
* [KeepTool](https://keeptool.com) - A professional suite of tools for Oracle Database developers, administrators and advanced application users.
* [MySQL Workbench](https://www.mysql.com/products/workbench) - Unified visual tool for database architects, developers, and DBAs.
* [Navicat](https://www.navicat.com/en/products#navicat) - A database development tool that allows you to simultaneously connect to MySQL, MariaDB, SQL Server, Oracle, PostgreSQL, and SQLite databases from a single application.
* [Oracle SQL Developer](http://www.oracle.com/technetwork/developer-tools/sql-developer) - Free, integrated development environment that simplifies the development and management of Oracle Database in both traditional and Cloud deployments.
* [pgAdmin](https://www.pgadmin.org) - The most popular and feature rich Open Source administration and development platform for PostgreSQL, the most advanced Open Source database in the world.
* [pgAdmin3](https://www.bigsql.org/pgadmin3) - Long Term Support for pgAdmin3.
* [PL/SQL Developer](https://www.allroundautomations.com/products/pl-sql-developer) - IDE that is specifically targeted at the development of stored program units for Oracle Databases.
* [PostgreSQL Maestro](https://www.sqlmaestro.com/products/postgresql/maestro) - Complete and powerful database management, admin and development tool for PostgreSQL.
* [Sql Server Management Studio](https://docs.microsoft.com/en-us/sql/ssms/sql-server-management-studio-ssms) - Integrated environment for managing any SQL infrastructure, for SQL Server and Azure SQL Databases.
* [Toad](https://www.quest.com/toad/) - Premier database solution for developers, admins and data analysts. Manage complex database changes with a single database management tool.
* [Toad Edge](https://www.toadworld.com/products/toad-edge) - Simplified database development tool for MySQL and PostgreSQL.
* [Valentina Studio](https://www.valentina-db.com/en/valentina-studio-overview) - Create, administer, query and explore Valentina DB, MySQL, MariaDB, PostgreSQL and SQLite databases for FREE.
* [WebDB](https://webdb.app) - Free Efficient Database IDE. Featuring Server Discovery, ERD, Data Generator, AI, NoSQL Structure Manager, Database Versioning and many more.

## GUI

* [Another Redis Desktop Manager](https://github.com/qishibo/AnotherRedisDesktopManager) ⭐ 33,930 | 🐛 174 | 🌐 JavaScript | 📅 2025-10-16 - Free Open Source Redis Manager. Available on Mac, Linux, Windows, Homebrew, Snap, winget, and more.
* [Beekeeper Studio](https://github.com/beekeeper-studio/beekeeper-studio) ⭐ 22,009 | 🐛 1,042 | 🌐 TypeScript | 📅 2026-02-15 - Open Source SQL Editor and Database Manager with a privacy commitment in their mission statement.
* [Robo 3T](https://github.com/Studio3T/robomongo) ⭐ 9,370 | 🐛 724 | 🌐 C++ | 📅 2022-09-22 - Shell-centric cross-platform MongoDB management tool.
* [Pgweb](https://github.com/sosedoff/pgweb) ⭐ 9,256 | 🐛 41 | 🌐 Go | 📅 2026-02-01 - Web-based database browser for PostgreSQL, written in Go and works on macOS, Linux and Windows machines.
* [Sequel Pro](https://github.com/sequelpro/sequelpro) ⭐ 9,200 | 🐛 529 | 🌐 Objective-C | 📅 2023-02-25 - Fast, easy-to-use Mac database management application for working with MySQL & MariaDB databases.
* [phpMyAdmin](https://github.com/phpmyadmin/phpmyadmin) ⭐ 7,796 | 🐛 912 | 🌐 PHP | 📅 2026-02-16 - A web interface for MySQL and MariaDB.
* [Azure Data Studio](https://github.com/microsoft/azuredatastudio) ⭐ 7,715 | 🐛 2,604 | 🌐 TypeScript | 📅 2026-02-14 - A data management tool that enables working with SQL Server, PostgreSQL, Azure SQL DB and SQL DW from Windows, macOS and Linux.
* [Sequel Ace](https://github.com/Sequel-Ace/Sequel-Ace) ⭐ 7,295 | 🐛 233 | 🌐 Objective-C | 📅 2026-02-12 - MySQL/MariaDB database management for macOS.
* [Adminer](https://github.com/vrana/adminer) ⭐ 7,265 | 🐛 21 | 🌐 PHP | 📅 2026-02-12 - Database management in a single PHP file.
* [DbGate](https://github.com/dbgate/dbgate) ⭐ 6,761 | 🐛 444 | 🌐 Svelte | 📅 2026-02-13 - Database manager for MySQL, PostgreSQL, SQL Server, MongoDB, SQLite and others. Runs under Windows, Linux, Mac or as web application.
* [sqlpad](https://github.com/rickbergfalk/sqlpad) ⚠️ Archived - Web-based SQL editor run in your own private cloud.
* [Clidey WhoDB](https://github.com/clidey/whodb) ⭐ 4,563 | 🐛 21 | 🌐 Go | 📅 2026-02-15 - A lightweight database explorer with next-gen UX for all SQL, NoSQL, Caches, and Queues.
* [TablePlus](https://github.com/TablePlus/TablePlus) ⭐ 3,721 | 🐛 1,402 | 📅 2024-03-15 - Modern, native, and friendly GUI tool for relational databases: MySQL, PostgreSQL, SQLite & more.
* [OmniDB](https://github.com/OmniDB/OmniDB) ⭐ 3,275 | 🐛 329 | 🌐 JavaScript | 📅 2023-02-01 - Web tool for database management.
* [Jailer](https://github.com/Wisser/Jailer) ⭐ 3,128 | 🐛 5 | 🌐 Java | 📅 2026-02-08 - Database Subsetting and Relational Data Browsing Tool/Client.
* [Antares SQL](https://github.com/antares-sql/antares) ⭐ 2,551 | 🐛 143 | 🌐 Vue | 📅 2025-10-14 - A modern, fast and productivity driven SQL client with a focus in UX. Available for Mac, Linux and Windows.
* [Tabix](https://github.com/tabixio/tabix) ⭐ 2,282 | 🐛 46 | 🌐 TypeScript | 📅 2023-01-15 - SQL Editor & Open source simple business intelligence for Clickhouse.
* [sqlite-tui](https://github.com/mathaou/sqlite-tui) ⭐ 1,814 | 🐛 6 | 🌐 Go | 📅 2022-06-11 - A TUI for viewing SQLite databases, written in Go.
* [SQLTools](https://github.com/mtxr/vscode-sqltools) ⭐ 1,720 | 🐛 313 | 🌐 TypeScript | 📅 2026-02-14 - Database management for VSCode.
* [DB Lens](https://github.com/dblens/app) ⭐ 274 | 🐛 10 | 🌐 TypeScript | 📅 2025-08-07 - Open Source PostgreSQL GUI - Automatic ER diagrams, Internal DB Insights, Disk Utilisation, Performance Metrics, Index Usage, Sequential scan counts and more.
* [Malewicz](https://github.com/mgramin/malewicz) ⭐ 66 | 🐛 9 | 🌐 SQL | 📅 2025-01-04 - Yet Another WEB client for DB schema exploring and performance analysis, but originally created specifically for hacking and extending.
* [ocelotgui](https://github.com/ocelot-inc/ocelotgui) ⭐ 63 | 🐛 2 | 🌐 C++ | 📅 2025-11-06 - For MySQL, MariaDB, and Tarantool. Developed for Linux but can run on Windows.
* [DbVisualizer](https://www.dbvis.com) - Universal database tool for developers, DBAs and analysts.
* [JackDB](https://www.jackdb.com) - Direct SQL access to all your data, no matter where it lives.
* [MissionKontrol](https://www.missionkontrol.io) - Modern drag & drop admin panel/client with full user permissions for non-technical users.
* [phpLiteAdmin](https://www.phpliteadmin.org) - Web-based SQLite database admin tool written in PHP with support for SQLite3 and SQLite2.
* [psequel](http://www.psequel.com) - Provides a clean and simple interface for you to perform common PostgreSQL tasks quickly.
* [PopSQL](https://popsql.com) - Modern, collaborative SQL editor for your team.
* [Postico](https://eggerapps.at/postico) - A Modern PostgreSQL Client for the Mac.
* [SQLite Expert](http://www.sqliteexpert.com/index.html) - Graphical interface supports all SQLite features.
* [SQLPro](https://www.macpostgresclient.com) - A simple, powerful PostgreSQL manager for macOS.
* [SQuirreL](https://sourceforge.net/projects/squirrel-sql) - Graphical SQL client written in Java that will allow you to view the structure of a JDBC compliant database, browse the data in tables, issue SQL commands etc.
* [SQLyog](https://www.webyog.com/product/sqlyog) - The most complete and easy to use MySQL GUI.
* [TeamPostgreSQL](http://www.teampostgresql.com) - PostgreSQL Web Administration GUI - use your PostgreSQL databases from anywhere, with rich, lightning-fast AJAX web interface.
* [Query.me](https://query.me) - Collaborative SQL editor in Notebook format. Let's you reference query results using JINJA, visualize data, and schedule runs and exports.

## CLI

* [usql](https://github.com/xo/usql) ⭐ 9,813 | 🐛 105 | 🌐 Go | 📅 2026-01-11 - A universal command-line interface for PostgreSQL, MySQL, Oracle Database, SQLite3, Microsoft SQL Server, and many other databases including NoSQL and non-relational databases!
* [pg\_activity](https://github.com/julmon/pg_activity) ⭐ 2,994 | 🐛 13 | 🌐 Python | 📅 2026-01-13 - Top-like application for PostgreSQL server activity monitoring.
* [iredis](https://github.com/laixintao/iredis) ⭐ 2,724 | 🐛 55 | 🌐 Python | 📅 2026-02-16 - A Cli for Redis with AutoCompletion and Syntax Highlighting.
* [pspg](https://github.com/okbob/pspg) ⭐ 2,688 | 🐛 1 | 🌐 C | 📅 2026-02-15 - PostgreSQL Pager.
* [sqlite-utils](https://github.com/simonw/sqlite-utils) ⭐ 2,006 | 🐛 126 | 🌐 Python | 📅 2026-01-21 - CLI tools for manipulating SQLite database files - inserting data, running queries, creating indexes, configuring full-text search and more.
* [ipython-sql](https://github.com/catherinedevlin/ipython-sql) ⭐ 1,803 | 🐛 114 | 🌐 Python | 📅 2024-07-12 - Connect to a database for issue SQL commands within IPython or IPython Notebook.
* [pgcenter](https://github.com/lesovsky/pgcenter) ⭐ 1,591 | 🐛 13 | 🌐 Go | 📅 2026-01-06 - Top-like admin tool for PostgreSQL.
* [SQLLine](https://github.com/julianhyde/sqlline) ⭐ 648 | 🐛 63 | 🌐 Java | 📅 2023-07-07 - Command-line shell for issuing SQL to relational databases via JDBC.
* [pg\_top](https://github.com/markwkm/pg_top) ⭐ 119 | 🐛 4 | 🌐 C | 📅 2024-06-06 - Top for PostgreSQL.
* [SQLcl](http://www.oracle.com/technetwork/developer-tools/sqlcl/overview/index.html) - Oracle SQL Developer Command Line (SQLcl) is a free command line interface for Oracle Database.

### dbcli

* [pgcli](https://github.com/dbcli/pgcli) ⭐ 13,023 | 🐛 59 | 🌐 Python | 📅 2026-01-17 - PostgreSQL CLI with autocompletion and syntax highlighting.
* [mycli](https://github.com/dbcli/mycli) ⭐ 11,868 | 🐛 28 | 🌐 Python | 📅 2026-02-15 - A Terminal Client for MySQL with AutoCompletion and Syntax Highlighting.
* [litecli](https://github.com/dbcli/litecli) ⭐ 3,189 | 🐛 35 | 🌐 Python | 📅 2026-02-15 - CLI for SQLite Databases with auto-completion and syntax highlighting.
* [mssql-cli](https://github.com/dbcli/mssql-cli) ⭐ 1,410 | 🐛 162 | 🌐 Python | 📅 2024-02-26 - A command-line client for SQL Server with auto-completion and syntax highlighting.
* [athenacli](https://github.com/dbcli/athenacli) ⭐ 226 | 🐛 8 | 🌐 Python | 📅 2025-12-12 - CLI tool for AWS Athena service that can do auto-completion and syntax highlighting.
* [vcli](https://github.com/dbcli/vcli) ⚠️ Archived - Vertica CLI with auto-completion and syntax highlighting.

## Schema

### Changes

* [Bytebase](https://github.com/bytebase/bytebase) ⭐ 13,728 | 🐛 141 | 🌐 Go | 📅 2026-02-14 - Web-based, zero-config, dependency-free database schema change and version control tool for teams.
* [gh-ost](https://github.com/github/gh-ost) ⭐ 13,210 | 🐛 322 | 🌐 Go | 📅 2026-02-10 - Online schema migration for MySQL.
* [flyway](https://github.com/flyway/flyway) ⭐ 9,533 | 🐛 239 | 🌐 Java | 📅 2026-02-12 - Database migration tool.
* [Atlas](https://github.com/ariga/atlas) ⭐ 8,083 | 🐛 241 | 🌐 Go | 📅 2026-02-07 - Inspect and Apply changes to your database schema.
* [liquibase](https://github.com/liquibase/liquibase) ⭐ 5,422 | 🐛 682 | 🌐 Java | 📅 2026-02-13 - Database-independent library for tracking, managing and applying database schema changes.
* [Sqitch](https://github.com/sqitchers/sqitch) ⭐ 3,101 | 🐛 77 | 🌐 Perl | 📅 2026-01-25 - Sensible database-native change management for framework-free development and dependable deployment.
* [migra](https://github.com/djrobstep/migra) ⭐ 3,052 | 🐛 86 | 🌐 Python | 📅 2025-08-25 - Like diff but for PostgreSQL schemas.
* [sqldef](https://github.com/k0kubun/sqldef) ⭐ 2,954 | 🐛 5 | 🌐 Go | 📅 2026-02-15 - Idempotent schema management for MySQL, PostgreSQL, and more.
* [Reshape](https://github.com/fabianlindfors/reshape) ⭐ 1,824 | 🐛 7 | 🌐 Rust | 📅 2026-02-10 - An easy-to-use, zero-downtime schema migration tool for Postgres.
* [node-pg-migrate](https://github.com/salsita/node-pg-migrate) ⭐ 1,443 | 🐛 50 | 🌐 TypeScript | 📅 2026-02-16 - Node.js database migration management built exclusively for PostgreSQL. (But can also be used for other DBs conforming to SQL standard - e.g. CockroachDB.)
* [Skeema](https://github.com/skeema/skeema) ⭐ 1,357 | 🐛 16 | 🌐 Go | 📅 2026-02-13 - Declarative pure-SQL schema management system for MySQL and MariaDB, with support for sharding and external online schema change tools.
* [SchemaHero](https://github.com/schemahero/schemahero) ⭐ 1,105 | 🐛 127 | 🌐 Go | 📅 2026-02-11 - A Kubernetes operator for declarative database schema management (gitops for database schemas).
* [Prisma Migrate](https://github.com/prisma/migrate) ⚠️ Archived - Declarative database schema migration tool that uses a declarative data modeling syntax to describe your database schema.
* [pg-osc](https://github.com/shayonj/pg-osc) ⭐ 609 | 🐛 18 | 🌐 Ruby | 📅 2026-02-03 - Easy CLI tool for making zero downtime schema changes and backfills in PostgreSQL.
* [yuniql](https://github.com/rdagumampan/yuniql) ⭐ 428 | 🐛 113 | 🌐 C# | 📅 2024-07-25 - Yet another schema versioning and migration tool just made with native .NET Core 3.0+ and hopefully better.
* [Pyrseas](https://github.com/perseas/Pyrseas) ⭐ 406 | 🐛 47 | 🌐 Python | 📅 2024-07-10 - Provides utilities to describe a PostgreSQL database schema as YAML.
* [2bass](https://github.com/CourseOrchestra/2bass) ⭐ 44 | 🐛 12 | 🌐 Java | 📅 2024-11-12 - Database configuration-as-code tool that utilizes concept of idempotent DDL scripts.

### Code generation

* [ddl-generator](https://github.com/catherinedevlin/ddl-generator) ⭐ 276 | 🐛 20 | 🌐 HTML | 📅 2022-09-09 - Infers SQL DDL (Data Definition Language) from table data.
* [scheme2ddl](https://github.com/qwazer/scheme2ddl) ⭐ 84 | 🐛 15 | 🌐 Java | 📅 2024-11-28 - Command line util for export Oracle schema to set of ddl init scripts with ability to filter undesirable information, separate DDL in different files, pretty format output.

### Diagrams

* [DrawDB](https://github.com/drawdb-io/drawdb) ⭐ 36,607 | 🐛 179 | 🌐 JavaScript | 📅 2026-02-13 - Free, simple, and intuitive online database design tool and SQL generator.
* [ChartDB](https://github.com/chartdb/chartdb) ⭐ 21,238 | 🐛 134 | 🌐 TypeScript | 📅 2026-02-11 - Free and Open-source database diagrams editor, visualize and design your DB with a single query.
* [Liam ERD](https://github.com/liam-hq/liam) ⭐ 4,701 | 🐛 33 | 🌐 TypeScript | 📅 2026-02-15 - Open-source tool that generates beautiful and easy-to-read Entity Relationship Diagrams from your database and ORMs.
* [Azimutt](https://github.com/azimuttapp/azimutt) ⭐ 2,048 | 🐛 78 | 🌐 Elm | 📅 2025-07-07 - An Entity Relationship diagram (ERD) visualization tool, with various filters and inputs to help understand your database schema.
* [ERAlchemy](https://github.com/Alexis-benoist/eralchemy) ⭐ 1,398 | 🐛 10 | 🌐 Python | 📅 2026-01-12 - Entity Relation Diagrams generation tool.
* [ERD Lab](https://www.erdlab.io/) - Free cloud based entity relationship diagram (ERD) tool made for developers.
* [QuickDBD](https://www.quickdatabasediagrams.com/) - Simple online tool to quickly draw database diagrams.

### Documentations

* [tbls](https://github.com/k1LoW/tbls) ⭐ 4,143 | 🐛 54 | 🌐 Go | 📅 2026-01-16 - CI-Friendly tool for document a database, written in Go.
* [Schema Spy](https://github.com/schemaspy/schemaspy) ⭐ 3,537 | 🐛 297 | 🌐 HTML | 📅 2026-01-26 - Generating your database to HTML documentation, including Entity Relationship diagrams.
* [DBML](https://github.com/holistics/dbml) ⭐ 3,515 | 🐛 106 | 🌐 JavaScript | 📅 2026-02-13 - Database Markup Language, designed to define and document database structures.
* [SchemaCrawler](https://github.com/schemacrawler/SchemaCrawler) ⭐ 1,784 | 🐛 2 | 🌐 HTML | 📅 2026-02-16 - A free database schema discovery and comprehension tool.
* [dbdocs](https://dbdocs.io/) - Create web-based database documentation using DSL code.

### Design

* [pgmodeler](https://github.com/pgmodeler/pgmodeler) ⭐ 3,480 | 🐛 265 | 🌐 C++ | 📅 2026-02-14 - Data modeling tool designed for PostgreSQL.
* [WWW SQL Designer](https://github.com/ondras/wwwsqldesigner) ⭐ 2,918 | 🐛 90 | 🌐 JavaScript | 📅 2025-08-25 - Online SQL diagramming tool.
* [Database Design](https://github.com/alextanhongpin/database-design) ⭐ 496 | 🐛 0 | 🌐 Go | 📅 2025-08-26 - Useful tips for designing robust database schema.
* [DBDiagram](https://dbdiagram.io) - A free, simple tool to draw ER diagrams by just writing code.
* [DbSchema](https://dbschema.com/) - Universal database designer for out-of-the-box schema management, schema documentation, design in a team, and deployment on multiple databases. DbSchema features tools for writing and executing queries, exploring the data, generating data, and building reports.
* [ERBuilder Data Modeler](https://soft-builder.com/erbuilder-data-modeler) - Easy-to-use database modeling software for high-quality data models. It's a complete data modeling solution for data modelers and data architects.
* [Moon Modeler](https://www.datensen.com) - Data modeling tool for both noSQL and relational databases. Available for Windows, Linux and macOS.
* [Navicat Data Modeler](https://www.navicat.com/en/products/navicat-data-modeler) - A powerful and cost-effective database design tool which helps you build high-quality conceptual, logical and physical data models.
* [Oracle SQL Developer Data Modeler](http://www.oracle.com/technetwork/developer-tools/datamodeler/overview/index.html) - Free graphical tool that enhances productivity and simplifies data modeling tasks.

### Samples

* [Oracle Database Sample Schemas](https://github.com/oracle/db-sample-schemas) ⭐ 893 | 🐛 3 | 🌐 PLSQL | 📅 2025-06-25 - Sample schemas for Oracle Database.

## API

Building API for your Data

* [Hasura GraphQL Engine](https://github.com/hasura/graphql-engine) ⭐ 31,899 | 🐛 2,375 | 🌐 TypeScript | 📅 2026-02-12 - Blazing fast, instant realtime GraphQL APIs on PostgreSQL with fine grained access control, also trigger webhooks on database events.
* [PostgREST](https://github.com/PostgREST/postgrest) ⭐ 26,517 | 🐛 381 | 🌐 Haskell | 📅 2026-02-15 - REST API for any PostgreSQL database.
* [Prisma](https://github.com/prismagraphql/prisma) ⚠️ Archived - Turns your database into a realtime GraphQL API.
* [PostGraphile](https://github.com/graphile/postgraphile) ⭐ 12,901 | 🐛 142 | 🌐 TypeScript | 📅 2026-02-13 - Instantly spin-up a GraphQL API server by pointing PostGraphile at your existing PostgreSQL database.
* [Datasette](https://github.com/simonw/datasette) ⭐ 10,748 | 🐛 654 | 🌐 Python | 📅 2026-02-15 - A tool for exploring and publishing data.
* [prest](https://github.com/prest/prest) ⭐ 4,519 | 🐛 147 | 🌐 Go | 📅 2026-02-11 - Is a way to serve a RESTful API from any databases written in Go.
* [Remult](https://github.com/remult/remult) ⭐ 3,201 | 🐛 90 | 🌐 TypeScript | 📅 2026-02-03 - End-to-end type-safe CRUD via REST API for your database, with fine-grained access control.
* [sandman2](https://github.com/jeffknupp/sandman2) ⭐ 2,042 | 🐛 45 | 🌐 Python | 📅 2026-02-09 - Automatically generate a RESTful API service for your legacy database.
* [DreamFactory](https://github.com/dreamfactorysoftware/dreamfactory) ⭐ 1,741 | 🐛 64 | 🌐 Shell | 📅 2026-02-13 - A open source REST API backend for mobile, web, and IoT applications.
* [soul](https://github.com/thevahidal/soul) ⭐ 1,676 | 🐛 18 | 🌐 JavaScript | 📅 2025-11-30 - Automatic SQLite RESTful and realtime API server.
* [VulcanSQL](https://github.com/Canner/vulcan-sql) ⭐ 785 | 🐛 35 | 🌐 TypeScript | 📅 2024-07-01 - Write templated SQL to automatically exposing RESTful APIs from your database/data warehouse/data lake.
* [Graphweaver](https://github.com/exogee-technology/graphweaver) ⭐ 547 | 🐛 22 | 🌐 TypeScript | 📅 2026-02-13 - Turn multiple data sources into a single GraphQL API.
* [restSQL](https://github.com/restsql/restsql) ⭐ 146 | 🐛 26 | 🌐 JavaScript | 📅 2019-01-12 - SQL generator with Java and HTTP APIs, uses a simple RESTful HTTP API with XML or JSON serialization.
* [resquel](https://github.com/formio/resquel) ⭐ 128 | 🐛 1 | 🌐 TypeScript | 📅 2024-09-06 - Easily convert your SQL database into a REST API.
* [Oracle REST Data Services](http://www.oracle.com/technetwork/developer-tools/rest-data-services) - A mid-tier Java application, ORDS maps HTTP(S) verbs (GET, POST, PUT, DELETE, etc.) to database transactions and returns any results formatted using JSON.

## Application platforms

Low-code and no-code platforms for application building

* [Appsmith](https://github.com/appsmithorg/appsmith) ⭐ 39,097 | 🐛 4,436 | 🌐 TypeScript | 📅 2026-02-13 - Powerful open source low code framework to build internal applications really quickly.
* [Tooljet](https://github.com/ToolJet/ToolJet) ⭐ 37,430 | 🐛 966 | 🌐 JavaScript | 📅 2026-02-15 - Open-source low-code platform to build internal tools.
* [Budibase](https://github.com/Budibase/budibase) ⭐ 27,636 | 🐛 318 | 🌐 TypeScript | 📅 2026-02-15 - Low-code platform for creating internal apps in minutes.
* [ILLA Cloud](https://github.com/illacloud/illa-builder) ⭐ 12,372 | 🐛 43 | 🌐 TypeScript | 📅 2026-02-15 - Low-code internal tool building platform.
* [Nhost](https://github.com/nhost/nhost) ⭐ 9,072 | 🐛 109 | 🌐 TypeScript | 📅 2026-02-14 - The Open Source Firebase Alternative with GraphQL.
* [SQLPage](https://github.com/sqlpage/SQLPage) ⭐ 2,441 | 🐛 114 | 🌐 Rust | 📅 2026-02-07 - Fast SQL-only data application builder. Automatically build a UI on top of SQL queries.
* [Saltcorn](https://github.com/saltcorn/saltcorn) ⭐ 1,992 | 🐛 677 | 🌐 JavaScript | 📅 2026-02-13 - Open source no-code builder for web datatabase applications. Server and drag-and-drop UI builder, data stored in PostgreSQL or SQLite.

## Backup

* [Databasus](https://github.com/databasus/databasus) ⭐ 5,541 | 🐛 0 | 🌐 Go | 📅 2026-02-14 - Tool for scheduled PostgreSQL backups via web UI with external storages (local, S3, FTP, Google Drive, etc.), notifications (webhook, Discord, Slack, etc.) and team management.
* [pgbackrest](https://github.com/pgbackrest/pgbackrest) ⭐ 3,601 | 🐛 55 | 🌐 C | 📅 2026-02-16 - Reliable PostgreSQL Backup & Restore.
* [BaRMan](https://github.com/2ndquadrant-it/barman) ⭐ 2,721 | 🐛 63 | 🌐 Python | 📅 2026-01-20 - Backup and Recovery Manager for PostgreSQL.
* [pgcopydb](https://github.com/dimitri/pgcopydb) ⭐ 1,406 | 🐛 95 | 🌐 C | 📅 2025-04-28 - Copy a PostgreSQL database to a target PostgreSQL server (pg\_dump | pg\_restore on steroids).
* [pg\_probackup](https://github.com/postgrespro/pg_probackup) ⭐ 779 | 🐛 186 | 🌐 Python | 📅 2025-12-09 - A backup and recovery manager for PostgreSQL.
* [Portabase](https://github.com/Portabase/portabase) ⭐ 319 | 🐛 10 | 🌐 TypeScript | 📅 2026-02-15 - Agent-based platform for PostgreSQL backups and restores with decentralized execution and centralized orchestration.

## Cloning

* [Database Lab Engine](https://gitlab.com/postgres-ai/database-lab) - Instant thin cloning for PostgreSQL to scale the development process.
* [clone\_schema](https://github.com/denishpatel/pg-clone-schema) ⭐ 200 | 🐛 0 | 🌐 PLpgSQL | 📅 2025-12-17 - PostgreSQL clone schema utility without need of going outside of database.
* [Spawn](https://spawn.cc/) - Cloud service for creating instant database copies for development and CI. No more local db installs, instant recovery to arbitrary save points, isolated copies for each feature branch or test. Instant provisioning regardless of database size.

## Monitoring/Statistics/Perfomance

* [Telegraf PostgreSQL plugin](https://github.com/influxdata/telegraf/tree/master/plugins/inputs/postgresql) ⭐ 16,694 | 🐛 448 | 🌐 Go | 📅 2026-02-13 - Provides metrics for your PostgreSQL database.
* [PgHero](https://github.com/ankane/pghero) ⭐ 8,791 | 🐛 15 | 🌐 Ruby | 📅 2025-12-26 - A performance dashboard for PostgreSQL - health checks, suggested indexes, and more.
* [pgwatch2](https://github.com/cybertec-postgresql/pgwatch2) ⚠️ Archived - Flexible self-contained PostgreSQL metrics monitoring/dashboarding solution.
* [Promscale](https://github.com/timescale/promscale) ⚠️ Archived - The open-source observability backend for metrics and traces powered by SQL.
* [pgmetrics](https://github.com/rapidloop/pgmetrics) ⭐ 1,073 | 🐛 12 | 🌐 Go | 📅 2026-01-18 - Collect and display information and stats from a running PostgreSQL server.
* [Percona Monitoring and Management](https://github.com/percona/pmm) ⭐ 965 | 🐛 171 | 🌐 Go | 📅 2026-02-16 - Open source platform for managing and monitoring MySQL and MongoDB performance.
* [pgMonitor](https://github.com/CrunchyData/pgmonitor) ⭐ 696 | 🐛 14 | 🌐 PLpgSQL | 📅 2026-02-13 - All-in-one tool to easily create an environment to visualize the health and performance of your PostgreSQL cluster.
* [PostgreSQL Metrics](https://github.com/spotify/postgresql-metrics) ⭐ 598 | 🐛 3 | 🌐 Python | 📅 2023-05-29 - Service to extract and provide metrics on your PostgreSQL database.
* [pganalyze collector](https://github.com/pganalyze/collector) ⭐ 387 | 🐛 37 | 🌐 Go | 📅 2026-02-13 - Pganalyze statistics collector for gathering PostgreSQL metrics and log data.
* [ASH Viewer](https://github.com/akardapolov/ASH-Viewer) ⭐ 200 | 🐛 39 | 🌐 Java | 📅 2023-12-04 - Provides a graphical view of active session history data within the Oracle and PostgreSQL DB.
* [pgstats](https://github.com/gleu/pgstats) ⭐ 126 | 🐛 3 | 🌐 C | 📅 2026-01-22 - Collects PostgreSQL statistics, and either saves them in CSV files or print them on the stdout.
* [mssql-monitoring](https://github.com/microsoft/mssql-monitoring) ⚠️ Archived - Monitor your SQL Server on Linux performance using collectd, InfluxDB and Grafana.
* [pgbadger](https://github.com/dalibo/pgbadger) ⭐ 25 | 🐛 0 | 🌐 HTML | 📅 2018-09-13 - A fast PostgreSQL Log Analyzer.
* [Metis](https://www.metisdata.io/product/troubleshooting) - Provides observability and performance tuning for SQL databases.
* [Monyog](https://www.webyog.com/product/monyog) - Agentless & Cost-effective MySQL Monitoring Tool.
* [Navicat Monitor](https://www.navicat.com/en/products/navicat-monitor) - A safe, simple and agentless remote server monitoring tool that is packed with powerful features to make your monitoring effective as possible.
* [pgDash](https://pgdash.io) - Measure and track every aspect of your PostgreSQL databases.
* [pgMustard](https://www.pgmustard.com) - A user interface for PostgreSQL explain plans, plus tips to improve performance.
* [PostgreSQL Monitor](https://postgresmonitor.com) - An easy-to-use monitoring service for PostgreSQL providing alerts, dashboards, query stats and dynamic recommendations.
* [postgres-checkup](https://gitlab.com/postgres-ai/postgres-checkup) - New-generation diagnostics tool that allows users to do a deep analysis of the health of PostgreSQL databases.
* [Releem](https://releem.com) - Performance monitoring and optimization tool for MySQL & MariaDB that delivers actionable insights and safe automation for misconfigurations, slow queries, schema issues, and deadlocks, reducing manual work at scale.

### Prometheus

* [postgres\_exporter](https://github.com/wrouesnel/postgres_exporter) ⭐ 3,410 | 🐛 344 | 🌐 Go | 📅 2026-02-11 - Prometheus exporter for PostgreSQL server metrics.
* [pg\_exporter](https://github.com/Vonng/pg_exporter) ⭐ 299 | 🐛 13 | 🌐 Go | 📅 2026-02-12 - Fully customizable Prometheus exporter for PostgreSQL & Pgbouncer with fine-grained execution control.
* [pgSCV](https://github.com/weaponry/pgscv) ⚠️ Archived - Metrics exporter for PostgreSQL and PostgreSQL-related services.

### Zabbix

* [Mamonsu](https://github.com/postgrespro/mamonsu) ⭐ 187 | 🐛 27 | 🌐 Python | 📅 2025-11-20 - Monitoring agent for PostgreSQL.
* [pg\_monz](https://github.com/pg-monz/pg_monz) ⭐ 162 | 🐛 36 | 🌐 Shell | 📅 2021-10-31 - This is the Zabbix monitoring template for PostgreSQL Database.
* [Pyora](https://github.com/bicofino/Pyora) ⭐ 121 | 🐛 0 | 🌐 Python | 📅 2023-12-03 - Python script to monitor Oracle Databases.
* [ZabbixDBA](https://github.com/anetrusov/ZabbixDBA) ⭐ 100 | 🐛 2 | 🌐 Perl | 📅 2020-04-27 - Fast, flexible, and continuously developing plugin to monitor your RDBMS.
* [Orabbix](http://www.smartmarmot.com/wiki/index.php?title=Orabbix) - Plugin designed to work with Zabbix Enterprise Monitor to provide multi-tiered monitoring, performance and availability reporting and measurement for Oracle Databases, along with server performance metrics.

## Testing

* [SQLancer](https://github.com/sqlancer/sqlancer) ⭐ 1,695 | 🐛 149 | 🌐 Java | 📅 2025-11-23 - Automatically test DBMS in order to find logic bugs in their implementation.
* [pgTAP](https://github.com/theory/pgtap) ⭐ 1,116 | 🐛 51 | 🌐 PLpgSQL | 📅 2025-12-18 - Unit Testing for PostgreSQL.
* [RegreSQL](https://github.com/dimitri/regresql) ⭐ 348 | 🐛 4 | 🌐 Go | 📅 2024-09-04 - Regression Testing your SQL queries.
* [DbFit](https://github.com/dbfit/dbfit) ⭐ 242 | 🐛 147 | 🌐 Java | 📅 2026-02-12 - A database testing framework that supports easy test-driven development of your database code.

## HA/Failover/Sharding

* [Vitess](https://github.com/vitessio/vitess) ⭐ 20,697 | 🐛 924 | 🌐 Go | 📅 2026-02-15 - Database clustering system for horizontal scaling of MySQL through generalized sharding.
* [ShardingSphere](https://github.com/apache/shardingsphere) ⭐ 20,676 | 🐛 349 | 🌐 Java | 📅 2026-02-16 - Distributed SQL transaction & query engine for data sharding, scaling, encryption, and more - on any database.
* [Citus](https://github.com/citusdata/citus) ⭐ 12,289 | 🐛 1,050 | 🌐 C | 📅 2026-02-13 - PostgreSQL extension that distributes your data and your queries across multiple nodes.
* [patroni](https://github.com/zalando/patroni) ⭐ 8,157 | 🐛 75 | 🌐 Python | 📅 2026-01-29 - A template for PostgreSQL High Availability with ZooKeeper, etcd, or Consul.
* [stolon](https://github.com/sorintlab/stolon) ⭐ 4,807 | 🐛 152 | 🌐 Go | 📅 2024-07-08 - Cloud native PostgreSQL manager for PostgreSQL high availability.
* [autobase](https://github.com/vitabaks/autobase) ⭐ 3,926 | 🐛 36 | 🌐 TypeScript | 📅 2026-02-16 - Open-source DBaaS that automates the deployment and management of highly available PostgreSQL clusters.
* [pg\_auto\_failover](https://github.com/citusdata/pg_auto_failover) ⭐ 1,325 | 🐛 121 | 🌐 C | 📅 2025-11-17 - PostgreSQL extension and service for automated failover and high-availability.
* [pgslice](https://github.com/ankane/pgslice) ⭐ 1,233 | 🐛 4 | 🌐 Ruby | 📅 2026-01-06 - PostgreSQL partitioning as easy as pie.
* [Percona XtraDB Cluster](https://github.com/percona/percona-xtradb-cluster) ⭐ 376 | 🐛 12 | 🌐 C++ | 📅 2026-02-03 - A High Scalability Solution for MySQL Clustering and High Availability.
* [PostgreSQL Automatic Failover](https://github.com/ClusterLabs/PAF) ⭐ 346 | 🐛 20 | 🌐 Perl | 📅 2024-06-13 - High-Availibility for PostgreSQL, based on industry references Pacemaker and Corosync.
* [pglookout](https://github.com/aiven/pglookout) ⭐ 189 | 🐛 12 | 🌐 Python | 📅 2025-01-17 - PostgreSQL replication monitoring and failover daemon.

## Kubernetes

* [PostgreSQL operator](https://github.com/zalando/postgres-operator) ⭐ 5,084 | 🐛 554 | 🌐 Go | 📅 2026-02-13 - The PostgreSQL Operator enables highly-available PostgreSQL clusters on Kubernetes (Kubernetes) powered by Patroni.
* [Spilo](https://github.com/zalando/spilo) ⭐ 1,785 | 🐛 145 | 🌐 Python | 📅 2026-02-13 - HA PostgreSQL Clusters with Docker.
* [KubeDB](https://kubedb.com) - Making running production-grade databases easy on Kubernetes.
* [StackGres](https://gitlab.com/ongresinc/stackgres) - Enterprise-grade, Full Stack PostgreSQL on Kubernetes.

## Configuration Tuning

* [MySQLTuner-perl](https://github.com/major/MySQLTuner-perl) ⭐ 9,436 | 🐛 35 | 🌐 Perl | 📅 2026-02-14 - Script written in Perl that allows you to review a MySQL installation quickly and make adjustments to increase performance and stability.
* [postgresqltuner.pl](https://github.com/jfcoz/postgresqltuner) ⭐ 2,685 | 🐛 13 | 🌐 Perl | 📅 2024-01-08 - Simple script to analyse your PostgreSQL database configuration, and give tuning advice.
* [pgtune](https://github.com/gregs1104/pgtune) ⭐ 1,081 | 🐛 12 | 🌐 Python | 📅 2021-08-17 - PostgreSQL configuration wizard.
* [PGConfigurator](https://pgconfigurator.cybertec-postgresql.com) - Free online tool to generate an optimized `postgresql.conf`.

## DevOps

* [DBmaestro](https://www.dbmaestro.com) - Accelerates release cycles & supports agility across the entire IT ecosystem.
* [Toad DevOps Toolkit](https://www.quest.com/products/toad-devops-toolkit/) - Executes key database development functions within your DevOps workflow —without compromising quality, performance or reliability.

## Reporting

* [Chartbrew](https://chartbrew.com) - Create live dashboards, charts, and client reports from multiple databases and services.
* [Poli](https://github.com/shzlw/poli) ⭐ 1,975 | 🐛 43 | 🌐 Java | 📅 2023-01-06 - An easy-to-use SQL reporting application built for SQL lovers.

## Distributions

* [Postgres.app](https://github.com/PostgresApp/PostgresApp) ⭐ 7,689 | 🐛 147 | 🌐 Makefile | 📅 2026-02-12 - Full-featured PostgreSQL installation packaged as a standard Mac app.
* [Pigsty](https://github.com/Vonng/pigsty) ⭐ 4,683 | 🐛 16 | 🌐 Shell | 📅 2026-02-13 - Battery-Included Open-Source Distribution for PostgreSQL with ultimate observability & Database-as-Code toolbox for developers.
* [dbatools](https://github.com/sqlcollaborative/dbatools) ⭐ 2,727 | 🐛 190 | 🌐 PowerShell | 📅 2026-02-15 - PowerShell module that you may think of like a command-line SQL Server Management Studio.
* [DBdeployer](https://github.com/datacharmer/dbdeployer) ⚠️ Archived - Tool that deploys MySQL database servers easily.
* [Elephant Shed](https://github.com/credativ/elephant-shed) ⭐ 228 | 🐛 5 | 🌐 Shell | 📅 2026-01-26 - Web-based PostgreSQL management front-end that bundles several utilities and applications for use with PostgreSQL.
* [BigSQL](https://www.bigsql.org) - A developer-friendly distribution of PostgreSQL.

## Security

* [Acra](https://github.com/cossacklabs/acra) ⭐ 1,453 | 🐛 16 | 🌐 Go | 📅 2025-12-05 - Database security suite. Database proxy with field-level encryption, search through encrypted data, SQL injections prevention, intrusion detection, honeypots. Supports client-side and proxy-side ("transparent") encryption. SQL, NoSQL.
* [Databunker](https://github.com/securitybunker/databunker) ⭐ 1,384 | 🐛 3 | 🌐 Go | 📅 2025-11-06 - Special GDPR compliant secure vault for customer records built on top of regular DB.
* [Inspektor](https://github.com/poonai/inspektor) ⭐ 283 | 🐛 18 | 🌐 Rust | 📅 2022-07-15 - Access control layer for databases. Inspektor leverages open policy agent to make policy decisions.

## SQL

### Analyzers

* [SQLFluff](https://github.com/sqlfluff/sqlfluff) ⭐ 9,509 | 🐛 576 | 🌐 Python | 📅 2026-02-15 - Dialect-flexible and configurable SQL linter.
* [SQLCheck](https://github.com/jarulraj/sqlcheck) ⭐ 2,521 | 🐛 13 | 🌐 C++ | 📅 2024-02-21 - Automatically detects common SQL anti-patterns.
* [SQLLineage](https://github.com/reata/sqllineage) ⭐ 1,618 | 🐛 50 | 🌐 Python | 📅 2026-01-22 - SQL Lineage Analysis Tool powered by Python.
* [TSQLLint](https://github.com/tsqllint/tsqllint) ⭐ 235 | 🐛 18 | 🌐 C# | 📅 2024-09-18 - A tool for describing, identifying, and reporting the presence of anti-patterns in TSQL scripts.
* [Holistic.dev](https://holistic.dev) - Automatic detection service for database performance, security, and architecture issues.

### Extensions

* [PartiQL](https://partiql.org) - SQL-compatible access to relational, semi-structured, and nested data.

### Frameworks

* [Apache Calcite](https://calcite.apache.org) - Dynamic data management framework with advanced SQL features.
* [ZetaSQL](https://github.com/google/zetasql) ⭐ 2,601 | 🐛 102 | 🌐 C++ | 📅 2026-01-31 - Analyzer Framework for SQL.

### Formatters

* [SQL Formatter](https://github.com/zeroturnaround/sql-formatter) ⭐ 2,816 | 🐛 72 | 🌐 TypeScript | 📅 2026-02-13 - JavaScript library for pretty-printing SQL queries.
* [pgFormatter](https://github.com/darold/pgFormatter) ⭐ 1,901 | 🐛 19 | 🌐 PLpgSQL | 📅 2026-02-13 - A PostgreSQL SQL syntax beautifier.
* [CodeBuff](https://github.com/antlr/codebuff) ⭐ 475 | 🐛 6 | 🌐 Java | 📅 2025-07-12 - Language-agnostic pretty-printing through machine learning.
* [JSQLFormatter](https://github.com/manticore-projects/jsqlformatter) ⭐ 40 | 🐛 7 | 🌐 PLpgSQL | 📅 2026-02-16 - Open Source Java SQL Formatter for many RDBMS based on JSqlParser.
* [SQL Online](https://sqlonline.in) - A Free Tool to format your SQL Queries followed by content for Analysts.
* [Poor SQL](https://poorsql.com) - Instant free and open-source T-SQL formatting.

### Games

* [Lost at SQL](https://lost-at-sql.therobinlord.com) - A SQL learning game to help you pick up basic SQL skills - so that you can use queries to get information.
* [Querymon](https://codepip.com/games/querymon/) - Learn to use SQL queries on the Querydex, a database of monsters from common to legendary.
* [Schemaverse](https://datalemur.com/blog/games-to-learn-sql#schemaverse) - A Space-based strategy game implemented entirely within a PostgreSQL database.
* [SQL Island](https://sql-island.informatik.uni-kl.de) - After the survived plane crash, you will be stuck on SQL Island for the time being. By making progress in the game, you will find a way to escape from this island.
* [SQL Murder Mystery](https://mystery.knightlab.com) - Designed to be both a self-directed lesson to learn SQL concepts and commands and a fun game for experienced SQL users to solve an intriguing crime.
* [SQL Police Department](https://sqlpd.com) - In SQLPD, you get to solve crimes while learning SQL at the same time.

### Parsers

* [SQLGlot](https://github.com/tobymao/sqlglot) ⭐ 8,916 | 🐛 8 | 🌐 Python | 📅 2026-02-13 - Pure Python SQL parser, transpiler, and builder.
* [jOOQ](https://github.com/jOOQ/jOOQ) ⭐ 6,661 | 🐛 2,148 | 🌐 Java | 📅 2026-02-13 - Parses SQL, translates it to other dialects, and allows for expression tree transformations.
* [JSqlParser](https://github.com/JSQLParser/JSqlParser) ⭐ 5,916 | 🐛 107 | 🌐 Java | 📅 2026-02-15 - Parses an SQL statement and translate it into a hierarchy of Java classes.
* [sqlparse](https://github.com/andialbrecht/sqlparse) ⭐ 3,993 | 🐛 255 | 🌐 Python | 📅 2025-12-19 - Non-validating SQL parser for Python.
* [libpg\_query](https://github.com/pganalyze/libpg_query) ⭐ 1,428 | 🐛 49 | 🌐 C | 📅 2026-02-07 - C library for accessing the PostgreSQL parser outside of the server environment.
* [More SQL Parsing!](https://github.com/klahnakoski/mo-sql-parsing) ⭐ 292 | 🐛 13 | 🌐 Python | 📅 2025-10-28 - Parse SQL into JSON.
* [General SQL Parser](https://www.sqlparser.com) - Parsing, formatting, modification and analysis for SQL.

### Über SQL

Run SQL queries against anything

* [osquery](https://github.com/osquery/osquery) ⭐ 23,101 | 🐛 670 | 🌐 C++ | 📅 2026-02-11 - SQL powered operating system instrumentation, monitoring, and analytics.
* [Trino](https://github.com/trinodb/trino) ⭐ 12,556 | 🐛 2,531 | 🌐 Java | 📅 2026-02-16 - Distributed SQL query engine designed to query large data sets distributed over one or more heterogeneous data sources.
* [TextQL](https://github.com/dinedal/textql) ⭐ 9,117 | 🐛 39 | 🌐 Go | 📅 2023-10-22 - Execute SQL against structured text like CSV or TSV.
* [Steampipe](https://github.com/turbot/steampipe) ⭐ 7,699 | 🐛 22 | 🌐 Go | 📅 2026-02-13 - Use SQL to instantly query your cloud services (AWS, Azure, GCP and more).
* [CloudQuery](https://github.com/cloudquery/cloudquery) ⭐ 6,322 | 🐛 131 | 🌐 Go | 📅 2026-02-14 - Extracts, transforms, and loads your cloud assets into normalized PostgreSQL tables.
* [OctoSQL](https://github.com/cube2222/octosql) ⭐ 5,212 | 🐛 49 | 🌐 Go | 📅 2024-05-26 - Query tool that allows you to join, analyse and transform data from multiple databases and file formats using SQL.
* [dsq](https://github.com/multiprocessio/dsq) ⭐ 3,863 | 🐛 22 | 🌐 Go | 📅 2023-09-30 - Commandline tool for running SQL queries against JSON, CSV, Excel, Parquet, and more.
* [trdsql](https://github.com/noborus/trdsql) ⭐ 2,147 | 🐛 13 | 🌐 Go | 📅 2026-01-15 - CLI tool that can execute SQL queries on CSV, LTSV, JSON and TBLN.
* [csvq](https://github.com/mithrandie/csvq) ⭐ 1,609 | 🐛 26 | 🌐 Go | 📅 2024-07-25 - SQL-like query language for CSV.
* [MAT Calcite plugin](https://github.com/vlsi/mat-calcite-plugin) ⭐ 174 | 🐛 12 | 🌐 Java | 📅 2025-12-22 - This plugin for Eclipse Memory Analyzer allows to query heap dump via SQL.
* [Resmo](https://www.resmo.com) - Audit and evaluate resources using SQL.

### Language Server Protocol

* [sqls](https://github.com/lighttiger2505/sqls) ⭐ 1,263 | 🐛 44 | 🌐 Go | 📅 2026-01-07 - SQL Language Server written in Go.
* [SQLLanguageServer](https://github.com/joe-re/sql-language-server) ⭐ 766 | 🐛 65 | 🌐 TypeScript | 📅 2024-12-05 - SQL Language Server.

### Learning

Learning and puzzles for SQL

* [SQL Murder Mystery](https://github.com/NUKnightLab/sql-mysteries) ⭐ 2,023 | 🐛 19 | 🌐 JavaScript | 📅 2025-04-14 - Self-directed lesson to learn SQL concepts and commands and a fun game for experienced SQL users to solve an intriguing crime.
* [Advanced SQL Puzzles](https://github.com/smpetersgithub/AdvancedSQLPuzzles) ⭐ 849 | 🐛 0 | 🌐 TSQL | 📅 2026-01-23 - Difficult set-based SQL puzzles.
* [Hackerrank](https://www.hackerrank.com/domains/sql) - Practice coding, prepare for interviews, and get hired.
* [Learn SQL in a Month of Lunches](https://www.manning.com/books/learn-sql-in-a-month-of-lunches) - A book about how to use SQL to retrieve, filter, and analyze data.
* [LeetCode](https://leetcode.com/problemset/database) - Enhance your skills, expand your knowledge and prepare for technical interviews.
* [Select Star SQL](https://selectstarsql.com) - Free interactive book which aims to be the best place on the internet for learning SQL.
* [StrataScratch](https://www.stratascratch.com/blog/categories/sql) - Data science educational resources.

### Plan

* [pev2](https://github.com/dalibo/pev2) ⭐ 3,356 | 🐛 71 | 🌐 TypeScript | 📅 2026-02-02 - A Vue.js component to show a graphical vizualization of a PostgreSQL execution plan.
* [pg\_flame](https://github.com/mgartner/pg_flame) ⭐ 1,614 | 🐛 2 | 🌐 Go | 📅 2020-01-13 - A flamegraph generator for PostgreSQL `EXPLAIN ANALYZE` output.

### Scripts

Useful SQL-scripts for various purposes

* [pgx\_scripts](https://github.com/pgexperts/pgx_scripts) ⭐ 1,459 | 🐛 8 | 🌐 Shell | 📅 2023-08-10 - A collection of useful little scripts for database analysis and administration, created by our team at PostgreSQL Experts.
* [postgres\_dba](https://github.com/NikolayS/postgres_dba) ⭐ 1,219 | 🐛 1 | 🌐 PLpgSQL | 📅 2026-02-10 - The missing set of useful tools for PostgreSQL DBAs and all engineers.
* [pg-utils](https://github.com/dataegret/pg-utils) ⭐ 1,186 | 🐛 6 | 🌐 Shell | 📅 2025-12-05 - Useful PostgreSQL utilities.
* [TPT](https://github.com/tanelpoder/tpt-oracle) ⭐ 712 | 🐛 16 | 🌐 PLSQL | 📅 2026-01-14 - These sqlplus scripts are for Oracle Database performance optimization & troubleshooting.
* [pgsql-bloat-estimation](https://github.com/ioguix/pgsql-bloat-estimation) ⭐ 565 | 🐛 5 | 📅 2022-08-23 - Queries to mesure statistical bloat in indexes and tables for PostgreSQL.
* [DBA MultiTool](https://github.com/LowlyDBA/dba-multitool) ⭐ 102 | 🐛 2 | 🌐 PLpgSQL | 📅 2026-01-26 - T-SQL scripts for the long haul: optimizing storage, on-the-fly documentation, and general administrative needs for SQL Server.
* [pgWikiDont](https://gitlab.com/depesz/pgWikiDont) - SQL test that checks if your database follows rules from <https://wiki.postgresql.org/wiki/Don't_Do_This>.
* [PostgreSQL cheat sheet](https://postgrescheatsheet.com) - Useful SQL-scripts and commands by \<timescale.com>.
* [postgres\_queries\_and\_commands.sql](https://gist.github.com/rgreenjr/3637525) - Useful PostgreSQL Queries and Commands.

## Data

* [dbt](https://github.com/dbt-labs/dbt-core) ⭐ 12,249 | 🐛 817 | 🌐 Python | 📅 2026-02-15 - Transform your data by simply writing select statements, while dbt handles turning these statements into tables and views in a data warehouse.
* [QuickTable](https://quicktable.io) - Empowers everyone to access, clean, analyze, transform, and model data with no code.

### Catalog

* [DataHub](https://github.com/datahub-project/datahub) ⭐ 11,580 | 🐛 739 | 🌐 Java | 📅 2026-02-16 - The Metadata Platform for the Modern Data Stack.
* [Amundsen](https://github.com/amundsen-io/amundsen) ⭐ 4,737 | 🐛 37 | 🌐 Python | 📅 2026-02-09 - Metadata driven application for improving the productivity of data analysts, data scientists and engineers when interacting with data.
* [Marquez](https://github.com/MarquezProject/marquez) ⭐ 2,121 | 🐛 238 | 🌐 Java | 📅 2026-02-11 - Collect, aggregate, and visualize a data ecosystem's metadata.

### Lineage

* [Dwh.dev](https://dwh.dev) - Nexgen data lineage for Snowflake.

### Generation/Masking/Subsetting

* [Faker](https://github.com/faker-js/faker) ⭐ 14,883 | 🐛 134 | 🌐 TypeScript | 📅 2026-02-16 - Generate massive amounts of fake data in the browser and Node.js.
* [Noisia](https://github.com/lesovsky/noisia) ⭐ 699 | 🐛 0 | 🌐 Go | 📅 2023-11-06 - Harmful workload generator for PostgreSQL.
* [Benerator](https://github.com/rapiddweller/rapiddweller-benerator-ce) ⭐ 157 | 🐛 13 | 🌐 Java | 📅 2026-01-17 - Generate, obfuscate (anonymize / pseudonymize) and migrate data for development, testing and training purposes.
* [myanon](https://github.com/ppomes/myanon) ⭐ 113 | 🐛 0 | 🌐 C | 📅 2026-02-15 - Streaming anonymizer for MySQL dump files. Reads mysqldump from stdin, writes anonymized version to stdout. Supports deterministic hashing, fixed values, JSON field anonymization, and Python extensions.
* [quick-seed](https://github.com/miit-daga/quick-seed) ⭐ 25 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-02 - Database-agnostic seeding tool for generating realistic test data with support for PostgreSQL, MySQL, SQLite, Prisma, and Drizzle ORM.
* [dbForge Data Generator for MySQL](https://www.devart.com/dbforge/mysql/data-generator) - Powerful GUI tool for creating massive volumes of realistic test data.
* [dbForge Data Generator for Oracle](https://www.devart.com/dbforge/oracle/data-generator) - Small but mighty GUI tool for populating Oracle schemas with tons of realistic test data.
* [dbForge Data Generator for SQL Server](https://www.devart.com/dbforge/sql/data-generator) - Powerful GUI tool for a fast generation of meaningful test data for databases.
* [SB Data Generator](https://soft-builder.com/sb-data-generator) - Simple and powerful tool to generate and populate selected tables or entire databases with realistic test data for your applications. Generate test data for: Oracle, MS SQL Server, MySQL, PostgreSQL, Firebird, SQLite, Azure SQL Database, Amazon Redshift and Amazon RDS.
* [SQLable](https://sqlable.com/generator/) - Generate fake data in the browser.
* [Synthesized TDK](https://docs.synthesized.io/tdk/latest) - DevOps' best friend for database masking and generation.

### Data Profilers

* [YData Profiling](https://github.com/ydataai/ydata-profiling) ⭐ 13,376 | 🐛 293 | 🌐 Python | 📅 2026-02-02 - A general-purpose open-source data profiler for high-level analysis of a dataset.
* [Data Profiler](https://github.com/capitalone/dataprofiler) ⭐ 1,543 | 🐛 80 | 🌐 Python | 📅 2025-09-26 - The DataProfiler is a Python library designed to make data analysis, monitoring, and sensitive data detection easy.
* [Desbordante](https://github.com/desbordante/desbordante-core) ⭐ 466 | 🐛 82 | 🌐 C++ | 📅 2026-02-07 - An open-source data profiler specifically focused on discovery and validation of complex patterns in data.

### Replication

* [Litestream](https://github.com/benbjohnson/litestream) ⭐ 13,196 | 🐛 32 | 🌐 Go | 📅 2026-02-14 - Streaming replication for SQLite.
* [pgsync](https://github.com/ankane/pgsync) ⭐ 3,429 | 🐛 14 | 🌐 Ruby | 📅 2025-12-26 - Sync PostgreSQL data between databases.
* [repmgr](https://github.com/2ndQuadrant/repmgr) ⭐ 1,685 | 🐛 129 | 🌐 C | 📅 2025-04-17 - The Most Popular Replication Manager for PostgreSQL.
* [dtle](https://github.com/actiontech/dtle) ⭐ 560 | 🐛 137 | 🌐 Go | 📅 2023-12-12 - Distributed Data Transfer Service for MySQL.
* [pg\_chameleon](https://github.com/the4thdoctor/pg_chameleon) ⭐ 429 | 🐛 45 | 🌐 Python | 📅 2025-01-21 - MySQL to PostgreSQL replica system written in Python 3. The system use the library mysql-replication to pull the row images from MySQL which are stored into PostgreSQL as JSONB.
* [PGDeltaStream](https://github.com/hasura/pgdeltastream) ⭐ 259 | 🐛 5 | 🌐 Go | 📅 2018-06-13 - A Golang webserver to stream PostgreSQL changes atleast-once over websockets, using PostgreSQL logical decoding feature.

### Compare

* [data-diff](https://github.com/datafold/data-diff) ⚠️ Archived - Command-line tool and Python library to efficiently diff rows across two different databases.
* [KS DB Merge Tools](https://ksdbmerge.tools) - GUI to compare and sync DB schema and data. For Oracle Database, MySQL, MariaDB, SQL Server, PostgreSQL, SQLite, MS Access and Cross-DBMS.

## Papers

Documents, articles, manifestos and other theoretical materials on database tools

* [The "Database as Code" Manifesto](https://github.com/mgramin/database-as-code) ⭐ 113 | 🐛 3 | 📅 2025-01-15 - Treat your database as Code.
* [Grokking Relational Database Design](https://www.manning.com/books/grokking-relational-database-design) - A friendly illustrated guide to designing and implementing your first database.

## Machine Learning

* [MindsDB](https://github.com/mindsdb/mindsdb) ⭐ 38,487 | 🐛 171 | 🌐 Python | 📅 2026-02-13 - In-database Machine Learning.
* [SQLFlow](https://github.com/sql-machine-learning/sqlflow) ⭐ 5,190 | 🐛 251 | 🌐 Go | 📅 2024-04-18 - Brings SQL and AI together.

## Contributing

* Your contributions are always welcome! Please read the [contribution guidelines](origin/contributing.md) first.
