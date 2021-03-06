Trading API Introduction
========================

Besides to manually trading in `Spiral Exchange Web <https://www.spiral.exchange>`_, there is trading API for automation trading programming.
There are two forms of API: HTTP REST API and WebSocket. These forms of API must be used together to receive realtime data and management orders.

HTTP REST API
--------------

With HTTP REST API, you can

* Query trading production information (symbol and currencies)
* Place orders
* Cancel orders
* Query orders
* Query trade

WebSocket
---------

With WebSocket connection, market data, trade and order information is pushed to client in realtime. 

* Subscribe order book, ticker, KLine
* Subscribe private channel update data: order, transaction and account

.. Attention::
   Some websocket data will be dropped if network connection is too slow. Spiral Exchange will drop some data in sending buffer to save server resources.
