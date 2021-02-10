## Sensu-Plugins-ipmi

[ ![Build Status](https://travis-ci.org/sensu-plugins/sensu-plugins-ipmi.svg?branch=master)](https://travis-ci.org/sensu-plugins/sensu-plugins-ipmi)
[![Gem Version](https://badge.fury.io/rb/sensu-plugins-ipmi.svg)](http://badge.fury.io/rb/sensu-plugins-ipmi)
[![Code Climate](https://codeclimate.com/github/sensu-plugins/sensu-plugins-ipmi/badges/gpa.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-ipmi)
[![Test Coverage](https://codeclimate.com/github/sensu-plugins/sensu-plugins-ipmi/badges/coverage.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-ipmi)
[![Dependency Status](https://gemnasium.com/sensu-plugins/sensu-plugins-ipmi.svg)](https://gemnasium.com/sensu-plugins/sensu-plugins-ipmi)

## Functionality

By default when using `ipmitool` to connect, we default to using the `lan20` driver for IPMI v2 hosts which will not work with older (IPMI v1.5+) hosts. Instead of specifying the driver for each host, you can try setting it to `auto`.

## Files
 * bin/check-sensor.rb

## Usage

## Installation

[Installation and Setup](http://sensu-plugins.io/docs/installation_instructions.html)

## Notes
