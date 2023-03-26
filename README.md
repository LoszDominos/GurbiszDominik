Klient Gerald:

Ermöglichen Sie ihrem Klienten die Steuerung des PCs mittels Kamera. Er soll über diese das AsTeRICS Grid ansteuern können sowie einen Browser bedienen können und ggf. E-mails schreiben. (Tastatureingaben!)



Für das ACS und ARE wurde eine Modell gebraucht für die Übertragung von Daten vom Asterics Grid and das Openhab und somit an die Jalousien und Lichet in der Küche. Im Folgenden Bild wird das Mordell dargestellt. 
![ACS](https://user-images.githubusercontent.com/128988422/227797069-732cb72e-bf0e-477d-8193-98c4bd3b585d.PNG)

Für die Steuerung wurde ein Asterics Grid benötigt. Dies sieht wie Folgt aus. 
![Grid](https://user-images.githubusercontent.com/128988422/227797072-778c96b2-9352-45b1-8cf3-d29b6d50361b.PNG)

Um das Asterics Grid mit dem Openhab zu verbinden musste zuerst das ACS Modell gedownloadet werden. Dadurch wurde einem ermöglicht dem Block im Modell auszuwählen. Die Daten für die Jalousien wurden aus einem PDF entnommen. Jeder Datentyp besteht aus @OPENHAB: GERÄT, Variable. Im Fall der Jalousien gab es die Varianlen UP, DOWN und 40.
![Jalousien](https://user-images.githubusercontent.com/128988422/227797073-1083c257-206c-44b8-88d8-7ab17a2e7670.PNG)

Für die Lichet in der Küche wurde das selbe gemacht wie für die Jalousien. Nach dem Download des ACS Modelles konnte der Block ausgewählt und die Daten reingeschrieben werden. Hier sind die Optionen für die Variablen entweder OFF oder ON.
![Openhab](https://user-images.githubusercontent.com/128988422/227797075-675c4c24-e9e2-4088-8278-0c90a4717417.PNG)

Da unser Kunde ein Radio bedienen wollte wurde eine Weiterleitung zu einem andern Grid erstellt. Dieses Grid ermöglicht ihm Sender auszuwählen, die Musik lauter oder leiser zu machen und das Radio auszuschalten.
![Radio Grid](https://user-images.githubusercontent.com/128988422/227797078-8dde8f43-2f63-4332-bdfd-482a1b0e00e7.PNG)
Im darauffolgenden Bild ist ersichtlich wie die Einstellungen für so eine Funktion, Sender auswählen, eingestellt sein müssen.
![Radio](https://user-images.githubusercontent.com/128988422/227797082-9c195c76-7959-49e7-bd82-1736b7da8321.PNG)
  
