log4php-kafka
=============

A log4php Kafka Appender - LoggerAppenderKafka

This project is to create a Log4PHP appender which sends log messages to apache kafka: http://kafka.apache.org/

It works with version 2.3.0 of log4php

To install, clone this repository into the log4php/src directory, 
and add the following line to the static $classes array in main/php/LoggerAutoloader.php:

  	'LoggerAppenderKafka' => '/appenders/LoggerAppenderKafka.php',

Usage example can be found in the examples directory.
