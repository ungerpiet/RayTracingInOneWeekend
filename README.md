# Ray Tracing in One Weekend

Eine C++ Implementierung des Computergrafik-Buchs *"Ray Tracing in One Weekend"* von Peter Shirley. Die Raytracing-Engine wird von Grund auf ohne externe Grafik-Bibliotheken entwickelt.

**Aktueller Status:**
Das Projekt ist aktuell bis einschließlich **Kapitel 10.6** (Fuzzy Reflection / Metalle) abgeschlossen. Die Engine berechnet bereits exakte Vektormathematik, diffuse Lichtreflexionen sowie metallische Oberflächen mit anpassbarer Unschärfe.

## Quickstart

Voraussetzung: Ein C++ Compiler (z. B. GCC)

**Kompilieren:**
g++ main.cpp -o raytracer

**Rendern:**
./raytracer > image.ppm

*(Hinweis: Das Programm generiert eine .ppm-Datei, die mit gängigen Bildbetrachtern geöffnet werden kann.)*
