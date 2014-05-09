# Sound Cloud

Voice recognition and visualization demo.


## Live Example

See a live version of the site at 
[https://mpwoz.github.io/soundcloud/](https://mpwoz.github.io/soundcloud/)


Note: The `https` is important, as it prevents you from having to re-allow
the microphone every few seconds. This is something we did to overcome the 
speech recognition time limit imposed by the browser. 


## Running locally

* Run `python server.py` from the root directory
* Navigate to [https://localhost:8000](https://localhost:8000) in your browser
* Start talking!


Note: if you get an SSL error, try running `generate_cert.sh` and following the 
prompts. This will generate a new certificate for the https server to use. This 
is not secure, but it's necessary to avoid having to re-enable the microphone
every few seconds (allowing the voice recognition to run continuously)


## Team Members

Greg Blaszczuk : Word cloud rendering, frequency calculation


Martin Wozniewicz : Speech recognition, https server


