
# Automate 




## Authors

- [@umeshregmi](https://github.com/umeshregmi/)




## Installation

Install my-project with pip

```bash
  pip install automate
  cd automate
```
    
## Deployment

To deploy this project run

```bash
  npm run deploy
```


## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.


## API Reference

#### Get all items

```http
  GET /api/items
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### add(num1, num2)

Takes two numbers and returns the sum.


## Usage/Examples

```javascript
import Component from 'my-project'

function App() {
  return <Component />
}
```

