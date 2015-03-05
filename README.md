#paypal-ipn-listner

References:

    http://runnable.com/UtkFzblr0N9YAABV/paypal-ipn-listner-for-node-js-and-webserver
    http://www.imooc.com/qadetail/60858

A simple Paypal IPN listener written in Node.js


**1. Install dependency**

    npm install

**2. Start server**

     sudo npm start

(It needs to run as *root* to listen to port 80. Paypal IPN Simulator can only send request to this port, so I kept it.)

**The server process will show its out to console.**