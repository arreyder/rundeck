Future
	Change IIS site bindings
	Search alternate/current environment for cache_hosts

## 1.0.1
	* Merge 10.5 hotfixe to master.
## 0.0.31
	Merge in HBase parameter moves.
## 0.0.30
	Adding missing parameters
## 1.0.0   
	* Incremented version to allow room for hotfixes
## 0.0.29
	Changed hbase settings to use wt_common version of pod_id and moved fb_data_center_id under wt_analtics_ui
## 0.0.28
	Hard code the thrift port for hbase since it's not actually tunable.

## 0.0.27
	Added YouTube settings

## 0.0.26
	Merged IIS config into default.rb

## 0.0.25
	Added general IIS configuration

## 0.0.24
	Changed monitor_service_addr to monitor_hostname
	Changed rest_uri to be under wt_dx rather then wt_analytics_ui
	Removed rest_uri from default attributes

## 0.0.23
	Cookbook renamed to wt_analytics_ui
	Share wrs folder
	Added log4net.config template

## 0.0.22
	Added UI user to MachineKeys folder
	Added UI user to Performance Monitor Users

## 0.0.21
	Added PatentsLink configuration item to appSettings in web.config template
	Added many new attributes
	Added mapping.xml.erb and webtrends-brand.xml.erb
	Removed install_logdir creation

## 0.0.18
	Added hbase values to web.config template