docker build -t chynologic.com:55000/chyno/test:${BUILD_NUMBER} .

docker push chynologic.com:55000/chyno/test:${BUILD_NUMBER}