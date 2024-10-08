# SolarPanel_STM32
System sterujący silnikami odpowiedzialnych za położenie paneli fotowoltaicznych
* komunikuje się z ESP32 interfejsem UART aby umożliwić zdalne sterowanie manualne
* sterowanie automatyczne na podstawie różnicy między oświetleniem fotorezystorów
* obsługa czujników krańcowych
* system używa FreeRTOS w celu "równoległego" sterowania silnikami
