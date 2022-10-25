
deps:
	go get github.com/pact-foundation/pact-go/v2@2.x.x
	pact-go -l DEBUG install
	go mod tidy 

test:
	go test main/consumer_v2_test.go