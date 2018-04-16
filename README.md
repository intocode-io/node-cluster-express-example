# Node cluster + Express example

## Pre-requisite to do load testing
* Python and Locust installed
~~~
pip install locustio
~~~

## Installation
* Clone this project
~~~
git clone git@github.com:intocode-io/node-cluster-example.git
~~~
* Install node modules in the project directory
~~~
cd node-cluster-example
npm install
~~~

## Usage

To start a web server in Single-thread mode
~~~
node without-cluster.js
~~~

To start a web server in Cluster mode
~~~
node with-cluster.js
~~~

To start load testing web GUI
~~~
./load-test.sh
~~~