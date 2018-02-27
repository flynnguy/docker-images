FROM flynnguy/glide:latest

RUN go get -u github.com/derekparker/delve/cmd/dlv

ENTRYPOINT ["/go/bin/dlv"]
CMD ["--help"]
