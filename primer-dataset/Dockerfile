FROM mongo

COPY primer-dataset.json /tmp
# from https://raw.githubusercontent.com/mongodb/docs-assets/primer-dataset/primer-dataset.json
# see also: https://docs.mongodb.com/getting-started/shell/import-data/
CMD mongoimport --host mongodb --db test --collection restaurants --drop --file /tmp/primer-dataset.json
