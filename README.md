# microservice-rabbitmq-nestjs-caasandra
## Setup Project

**Step 1: Setup**

Before you start, make sure you have Node.js and npm (Node Package Manager) installed on your system. You should also have Nest CLI installed. If you don't have it, you can install it globally using npm:

```bash
npm install -g @nestjs/cli
```

**Step 2: Create a New NestJS Project**

Create a new NestJS project by running the following command:

```bash
nest new api
```

This will create a new NestJS project in a directory called `api` and got to this directory.

**Step 3: Create a Microservice APP**

In NestJS, create microservice app using  the following command:

```bash
nest generate app auth
```

This will generate a new app in the `apps` directory  and there have existing `api` project.

**Step 4: Create Library**

Create  a library  within the microservice Project, The help us to configure common entity, method ect and used this multiple apss:

```bash
nest g library shared
```

This will create a controller file in the `src/microservice` directory.

**Step 5: Install Dependencies**

Install the necessary NestJS packages and RabbitMQ library, Cassandra Driver:

```bash
npm install --save @nestjs/microservices amqplib nestjs-rabbitmq
```


```bash
npm install cassandra-driver
```


