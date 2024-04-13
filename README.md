# Query Minimal

Query Minimal is a 30-second guide to setting up Query.

## Quick Start

Follow these simple steps to run a Query Server and configure the working environment.

### Install

Clone this proyect:

```sh
git clone https://github.com/gc-victor/query-minimal.git
```

Remember to change the working directory `cd query-minimal`.

Install dependencies:

```sh
npm install -g @qery/query @qery/query-server esbuild
```

### Query Server

Run the server:

```sh
query-server
```

### Configure

Configure the working environment in a **different** terminal.

Execute the settings and answer:

```sh
query settings
```

- What is the server URL? **[http&ZeroWidthSpace;://localhost:3000]**
- What is her email? **admin**
- What is her password? **admin**
- Do you want to save the history of your shell? **[Enter]**

Push the function:

```sh
query function
```

### Let's test it!

```sh
curl 'http://localhost:3000/'
```

## Recomendation

Follow the [documentation](https://github.com/gc-victor/query/blob/main/README.md) for a non-test local project.

## References

- [Query Website](https://qery.io)
- [Query - GitHub](https://github.com/gc-victor/query)