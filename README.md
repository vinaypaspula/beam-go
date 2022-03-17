# beam-go

### To install and check the version
I have downloaded the msi file from the [Go lang website](https://go.dev/dl/) and installed it

### To check the go version
`go version`

### To get the sdk
`go get -u github.com/apache/beam/sdks/v2/go/pkg/beam`

### To download the wordcount example
`go install github.com/apache/beam/sdks/v2/go/examples/wordcount`

When i try to install wordcount i got an error saying **missing go.sum** entry so i searched the stackover flow and found a soluiton

### I executed the below command
`go mod tidy`

### Now i tried to install the wordcount
`go install github.com/apache/beam/sdks/v2/go/examples/wordcount`

### Now i have executed the wordcount file with the input as sample.txt and output as counts.txt
`wordcount --input sample.txt --output counts.txt`
