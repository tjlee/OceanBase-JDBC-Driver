# OceanBase JDBC Driver

![Build](https://github.com/tjlee/OceanBase-JDBC-Driver/workflows/Build/badge.svg)
[![Version](https://img.shields.io/jetbrains/plugin/v/MARKETPLACE_ID.svg)](https://plugins.jetbrains.com/plugin/31287)
[![Downloads](https://img.shields.io/jetbrains/plugin/d/MARKETPLACE_ID.svg)](https://plugins.jetbrains.com/plugin/31287)

<!-- Plugin description -->
[OceanBase](https://www.oceanbase.com/) JDBC driver plugin for DataGrip and other JetBrains IDEs with database support.

Adds **OceanBase** as a native data source, so you can browse schemas, run queries, and manage data directly from your IDE — with no manual driver download required.

**Features:**
- OceanBase appears in the *New Data Source* dialog alongside other built-in databases
- Driver JAR bundled inside the plugin — works fully offline
- Supports OceanBase Connector/J versions 2.4.14, 2.4.15, 2.4.16, and 2.4.17
- Native `jdbc:oceanbase://` URL scheme; default port 2881
- Load balance connection template for multi-host HA setups
- SQL completion, schema introspection, and DDL generation via MySQL-dialect compatibility
<!-- Plugin description end -->

## Installation

- Using the IDE built-in plugin system:

  <kbd>Settings/Preferences</kbd> > <kbd>Plugins</kbd> > <kbd>Marketplace</kbd> > <kbd>Search for "OceanBase JDBC Driver"</kbd> >
  <kbd>Install</kbd>

- Using JetBrains Marketplace:

  Go to [JetBrains Marketplace](https://plugins.jetbrains.com/plugin/MARKETPLACE_ID) and install it by clicking the <kbd>Install to ...</kbd> button in case your IDE is running.

  You can also download the [latest release](https://plugins.jetbrains.com/plugin/MARKETPLACE_ID/versions) from JetBrains Marketplace and install it manually using
  <kbd>Settings/Preferences</kbd> > <kbd>Plugins</kbd> > <kbd>⚙️</kbd> > <kbd>Install plugin from disk...</kbd>

- Manually:

  Download the [latest release](https://github.com/tjlee/OceanBase-JDBC-Driver/releases/latest) and install it manually using
  <kbd>Settings/Preferences</kbd> > <kbd>Plugins</kbd> > <kbd>⚙️</kbd> > <kbd>Install plugin from disk...</kbd>
