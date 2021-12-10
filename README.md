# swagger-docs

## Viewing API documentation
You can use any local HTTP server of your choice to serve the `index.html` file locally to view the documentation.
If you don't have any local HTTP server installed, one simple way is to use python to start a local HTTP server.

First, try entering the following command:

    python -V
    # If the above fails, try:
    python3 -V

This should return a version number of python installed in your system.

Given that you have python 2.x installed, run the following command to start the local HTTP server:

    python -m SimpleHTTPServer

If you have python 3.x installed, run the following command to start the local HTTP server:

    python3 -m http.server

Then, you can visit [http://localhost:8000](http://localhost:8000) to view the API documentation.
