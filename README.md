# Phantom App for URLhaus
This [Phantom](https://www.splunk.com/en_us/software/splunk-security-orchestration-and-automation.html) app is written to interface with the abuse.ch [URLhaus database](https://urlhaus.abuse.ch/). 

The app implements four actions:

* Lookup Domain
* Lookup File Hash (MD5/SHA256)
* Lookup IP
* Lookup URL

# Installation

1. Download the gzipped tarball from releases.
2. Install according to the [official documentation](https://docs.splunk.com/Documentation/Phantom/latest/Admin/AppsAssets#Install.2C_update.2C_or_delete_apps_on_Splunk_Phantom).
3. Using the instructions on the same page, configure an asset. No API key is required - verify the default URL is still accurate.
