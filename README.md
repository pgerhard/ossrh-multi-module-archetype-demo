# Usage

This project comes with a predefined list of plugin executions and profiles. The following plugins are preconfigured

* Maven Compiler Plugin
* License Maven Plugin
* Maven Source Plugin
* Maven Javadoc Plugin
* Maven GPG Plugin
* Nexus Staging Plugin

If you run the build without any profiles all plugins except the maven gpg plugin and nexus staging plugin is enabled.The following profiles are predefined

* dev: When running this profile the license, source, javadoc, GPG plugin and nexus staging plugin are disabled
* release: When running this profile the nexus staging plugin is enabled


Before running this build you must meet the following prerequisites

* GPG Key (Public and Private Key) installed in your agent
* GPG passphrase is available via the env variable "gpg.passphrase"   