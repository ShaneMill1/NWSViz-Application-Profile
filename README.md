To build, run: docker run --rm -v "$(pwd)":/metanorma -v ${HOME}/.fontist/fonts/:/config/fonts  metanorma/metanorma  metanorma compile --agree-to-terms -t ogc -x pdf nwsviz_application_profile.adoc

not make

# NWSViz-Application-Profile
This is a prototype of the nwsviz-application-Profile for OGC API - EDR Part 3

schemathesis run -u http://localhost:5900 https://raw.githubusercontent.com/ShaneMill1/NWSViz-Application-Profile/refs/heads/main/openapi.yaml
