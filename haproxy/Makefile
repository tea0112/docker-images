run:
	docker image rm my-haproxy
	docker build -t my-haproxy .
	docker run -d --network host --name my-haproxy my-haproxy
clean:
	docker stop my-haproxy
	docker rm my-haproxy
