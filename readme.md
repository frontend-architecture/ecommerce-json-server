# e-commerce JSON server

[Product list REST API](https://frontend-architecture-products.herokuapp.com/).

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

Products list API is built using [json-server](https://github.com/typicode/json-server).

## Installing

There are 2 ways to run the API on your computer, natively using Node or using Docker.

### Using Node

Install node modules

`npm install`

Run development server

`npm run dev`

### Using Docker

Build image

`docker build -t fe-architecture/products-list .`

Run image

`docker run -p 3001:3001 -d fe-architecture/products-list`

## Usage

Shoppping cart API exposes 1 resource:

- `products`

JSON-Server provides some additional functionallity like filtering, pagination and more. Read the JSON-Server documentation for more.

## Deployment

WIP

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.
