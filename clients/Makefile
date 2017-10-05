all: ruby

.PHONY: ruby
ruby:
	protoc -I .. -I ../../../.. --ruby_out=./ruby/lib --grpc_out=./ruby/lib --plugin=protoc-gen-grpc=`which grpc_ruby_plugin` ../pqstream.proto
