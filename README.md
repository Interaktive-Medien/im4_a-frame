# Interaktive Medien IV, A-Frame
A-Frame Übungen Interaktive Medien IV, FS 2021  
Version 1.0.4 von A-Frame, getestet mit iOS 14.4.1 und Android 10.0  
Chrom Browser auf Smartphones benutzen  
## Beispiel Sonnensystem
Teil 1: Gestirne platzieren (nur x-Position ändern) und einfärben, index.html  
Teil 2: Hintergrund und Texturen einfügen, index_2.html  
Teil 3: Erde rotieren (Animation), index_3.html  
Teil 4: Bewegung Erde nur, wenn man sie mit Cursor anschaut (Interaktivität), index_4.html  
Teil 5: Grösse Mars mit eigenem Cursor steuern (Interaktivität mit Javascript), index_5.html  
Teil 6: Teleporting, Kamera an anderer Stelle platzieren, index_6.html  
Teil 7: Hintergrundmusik starten, wenn man Mars anschaut, index_7.html (geht nicht auf iOS)  
Teil 7 für iOS: index_7_ios.html mit Schaltfläche für den Audio-Start (geht auch für Android)  
Teil 8: Von https://clara.io den Saturn als .obj einbinden, index_8.html  
Teil 9: Ganzes Universum rotieren, index_9.html  
Teil 10: Parallele und serielle Kamerafahrt, index_10.html  
## Übungen
Übung 1: Objekte platzieren (1): Platzieren Sie vier farbige Würfel direkt vor der Kamera in der gegebenen Form, uebung_1.html  
Übung 2: Objekte platzieren (2): Platzieren Sie die vier farbigen Würfel so, dass sich die Kamera in der Mitte befindet, uebung_2.html  
Übung 3: Objekte animieren: Die vier farbigen Würfel von Übung 2 sollen sich um die Kamera drehen, uebung_3.html  
Übung 4: Bilder: Bauen Sie einen Würfel bestehend aus sechs <a-plane> und laden Sie sechs verschiedene Bilder, uebung_4.html  
Übung 5: Interaktivität: grüne Box und rote Kugel ändern Eigenschaftem beim Anschauen, uebung_5.html  
Übung 6: Inhalte der Szene wechseln: Bauen Sie innerhalb der <a-scene> verschiedene Inhalte, welche sich beim Anschauen der Körper ändern, uebung_6.html  
Übung 7: Video Steuerung: Bauen Sie eine Videosteuerung. Beim Blick auf die linke Box startet das Video, beim Blick auf die rechte Box stoppt Video, uebung_7.html  
## Tutorial
<a href="https://www.youtube.com/playlist?list=PLS1hZNcGg7eG9bzgOAb40ewHcEnFGfC1v" target="_blank">Youtube-Playlist</a>
## Hinweise
- Wenn im VR-Mode seltsame, zackige Formen erscheinen: <i>aframe.min_1_1_0.js</i> verwenden  
- Wenn bei iOS im VR-Mode der Cursor verschwindet: <i>aframe.min_1_0_4.js</i> verwenden (<a href="https://github.com/aframevr/aframe/issues/4825" target="_blank">Quelle</a>) 
- iOS hat ein Problem mit Audio-Dateien: "Playing sound on iOS — in any browser — requires a physical user interaction. This is a browser limitation, and internal A-Frame events (like fusing cursors) do not count as interaction. Ways to deal with this include using a Begin Experience button to start ambient music, or creating audio sprites with libraries like <a href="https://github.com/goldfire/howler.js" target="_blank">Howler.js</a>" (<a target="_blank" href="https://aframe.io/docs/1.2.0/components/sound.html">Quelle</a>). Ist im Sonnensystem-Beispiel "Teil 7 für iOS" implementiert
- Beste Lösung (im <i>allen</i> Beispiel Sonnensystem und den Übungen implementiert): <i>aframe.min_1_0_4.js</i> verwenden
## Video und Audio
- Beispiel Video mit Ton <i>video_test_ios.html</i> funktioniert auf iOS und Android  
- Beispiel Ton <i>index_7_ios.html</i> funktioniert auf iOS und Android
## Interaktive Ausstellung
Ein minimalistisches Beispiel liegt im gleichnamigen Ordner  