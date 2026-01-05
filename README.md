# gemini-video-analysis

# Vision-Language-Model Video Analysis

Dieses Repository enthält ein Google-Colab-Notebook zur Analyse von YouTube-Videos
mit Vision-Language-Modellen. Ziel ist der Vergleich der Modellantworten auf
vordefinierte Prompts im Rahmen einer Bachelorarbeit.

## Inhalt
- Google-Colab-Notebook zur Abfrage von Gemini 3 Pro Preview
- Vorgegebene Prompts zur Videoanalyse
- Automatisierte Ausgabe der Modellantworten

## Ausführung
Das Notebook ist für die Ausführung in **Google Colab** vorgesehen.

Zur Nutzung ist ein eigener **Gemini API-Key** erforderlich, der in Google Colab
als Secret mit dem Namen `GEMINI_API_KEY` hinterlegt werden muss.
Der API-Key ist **nicht** im Repository enthalten.

Ohne hinterlegten API-Key kann der Code nicht ausgeführt werden.

Hier sind nochmal die Video Urls die man manuell eingeben muss:

Sportvideos:

Mainz - Fc Köln https://www.youtube.com/watch?v=YCBUSAAIFPg

Galatasaray - Besiktas https://www.youtube.com/watch?v=LchfrISjwwY


Alltags-Aufnahmen:

Wochen Alltagsvideo https://www.youtube.com/watch?v=LWCFsczZ9QM

Food Flog Video  https://www.youtube.com/watch?v=TV7IAUA9WEY 


Anleitungs-Videos:

Geburtstagskarte https://www.youtube.com/watch?v=42Lkt5MU5lY

Virtual Studio code https://www.youtube.com/watch?v=KMxo3T_MTvY

## Hinweis zur Reproduzierbarkeit
Die im Rahmen der Bachelorarbeit gewonnenen Ergebnisse, einschließlich der
verwendeten Prompts und Modellantworten, sind vollständig im Text sowie im
Anhang der Arbeit dokumentiert. Der bereitgestellte Code dient der
Nachvollziehbarkeit des Vorgehens und als Referenz für die methodische Umsetzung.

## Verwendete Modelle
- Gemini 3 Pro Preview 
- Qwen3-VL-235B-A22B

## Hinweis

Hinweis:
Die Ergebnisse für Qwen3-VL-235B-A22B wurden über die offizielle Weboberfläche
des Modells erzeugt, da für dieses Modell keine frei zugängliche und praktikable 
Programmierschnittstelle zur direkten Videoanalyse zur Verfügung stand.

-> https://chat.qwen.ai/ hier die oben genannten Videos immer im neuen Chat einfügen:
https://th-koeln.sciebo.de/s/d5Moz74LNYwQy57 im Ordner BachelorarbeitVideos

Dieses Repository dient ausschließlich wissenschaftlichen Zwecken im Rahmen
einer akademischen Arbeit.
