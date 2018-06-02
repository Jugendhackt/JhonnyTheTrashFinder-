# JohnnyTheTrashFinder
Anwendung, die Abfall auf Bildern erkennen kann.
## Idee und Vision
Die Verschmutzung der Umwelt, insbesondere der Str�nde und Meere, durch Abfall ist ein immer gr��ers Problem. 
Um den M�ll zu beseittigen, muss erst einmal geschaut werden, wo �berall Trash zu finden ist.
Das Ziel von JohnnyTheTashFinder ist es eine Heat-Map zu erstellen, auf der die Verschmutzung eingetragen ist. 
Eine Drohne soll dann entsprechend dieser Karte zu den Verschmutzungen fliegen und aufr�umen.
## Umsetzung
### Brainstorming
Zun�chst m�ssen wir viele Bilder haben, auf denen M�ll zu sehen ist und auch welche, auf denen keiner zu sehen ist. 
Um zu erkennen, ob auf den Bildern M�ll zu sehen ist, wollen wir ein neuronales Netzwerk benutzen. 
In einem zweiten Schritt wollen wir die Metadaten der Bilder analysieren und so die Bilder einem Standort zuordnen, sodass eine Heatmap entstehen kann. Dazu k�nnten wir auch OpenStreetMap nutzen.
Im dritten Schritt k�nnen wir dann eine Drohne mit der entwickelten Software ausstatten und dann Testen.
### Deep learning
image classification von Google �ber transfer learning auf unser Problem �bertragen, sodass es am Ende m�glich ist, die Bilder als dreckig oder sauber zu deklarieren.
## Aufgaben und Probleme
viele viele Bilder
evt. Schnittstelle mit Umweltschutzapp
Heatmap
Verbindung mit OpenStreetMap
Drohne 
## Status
02-06-2018 Anfang des Projektes, deep learning ausprobieren
## Links
### Examplecode von Tensorflow ->Grundlage f�r Projekt
https://github.com/tensorflow/hub/raw/r0.1/examples/image_retraining/retrain.py
