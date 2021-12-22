# Cat

Example app used to test docker and kubernetes services.
It's a simple go app that runs on port 4200 and renders cat image.

## Usage

    ./cat

## Docker usage

    docker build . -t andrzejtrzaska/cat
    docker run -p 4200:4200 andrzejtrzaska/cat
    curl -v http://localhost:4200

## License

MIT
