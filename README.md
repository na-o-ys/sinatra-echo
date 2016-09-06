A simple server on which 'http://host/foo' renders text 'foo' with 200 success.

# Usage

http://localhost:3000

## Native

```
$ bundle install
$ bundle exec rackup --port 3000
```

## Docker

```
$ docker build -t sinatra-echo .
$ docker run -p 3000:80
```
