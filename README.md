# Roadster API Docs
Generated API docs from OpenApi definition via Redoc source at RoadsterInc/api_docs

To generate new version from RoadsterInc/api_docs use:

npm install -g redoc-cli

redoc-cli bundle dist/openapi.yaml

mv redoc-static.html ../docs/index.html

push it to origing/master which should automatically appear at https://docs.roadster.com
