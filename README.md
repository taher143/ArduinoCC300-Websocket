# ArduinoCC300-Websocket
Make changes to the https://github.com/brandenhall/Arduino-Websocket repository which is for WiFly to make it run for cc3000 wifi modile from adafruit.
Websocket client application for  arduino-CC3000 Wi-Fi from Adafruit
Have modified the WebSocketClient.cpp file to work with CC3000. Commented "Sec-WebSocket-Protocol:" line from Headers. and added one more CRLF after the last header. Tested with echo.websocket.org.
It's receiving two times the sending data then it disconnected.
Hope somebody improve this "BUG".
WebSocketServer is not updated, will updated it soon.
