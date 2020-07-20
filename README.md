# Roadster API Docs
Generated API docs from OpenApi definition via Redoc source at RoadsterInc/api_docs

To generate new version from RoadsterInc/api_docs use:

npm install -g redoc-cli

redoc-cli bundle dist/openapi.yaml

copy output to index.html and push it to origing/master which should publish to docs.roadster.com
