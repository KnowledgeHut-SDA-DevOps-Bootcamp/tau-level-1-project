build:
	docker build --build-arg rebuild=$$RANDOM --tag rayanah/person-service .

run:
	docker run -it --rm --name person-service -p 8081:80 -d rayanah/person-service 

debug:
	docker exec -it person-service sh

logs:
	docker logs person-service

followu:
	docker logs -f person-service

stop:
	docker stop person-service

clean:
	docker rm person-service
