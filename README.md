# Api Chatgpt Nodejs

This is an api for chatgpt with nodejs

## Installation

Use the npm

```bash
npm intall
```

## Configuration

You need the api key to be able to use it, if you don't have one you can do it by registering in open ai,
if you already have one you have to add it to the .env file

```python
OPENAI_API_KEY=Your_api_key
```

## Usage

Start the server

```bash
node index.js
```

With the server running, make a POST request

```python
{
  "message": "Hello, How are you?"
}
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
