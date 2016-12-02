FROM mongo

COPY primer-dataset.json /tmp
CMD mongoimport --host mongodb --db test --collection restaurants --drop --file /tmp/primer-dataset.json
