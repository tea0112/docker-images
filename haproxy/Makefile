run:
	docker image rm my-haproxy
	docker build -t my-haproxy .
	docker run -d -p 3000:3000 --name my-haproxy my-haproxy
clean:
	docker stop my-haproxy
	docker rm my-haproxy
