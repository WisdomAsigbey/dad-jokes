## Dad Jokes Project

#### HTML Structure

- div.container
  - button.btn
  - p.result(dummy text)


#### Dad Jokes Docs

- [Dad Jokes](https://icanhazdadjoke.com/api)

- random joke
- https://icanhazdadjoke.com/

#### Select Elements

- select btn, result
- check if both elements selected
- listen for click events

#### FetchDadJoke Function

- create async function
- setup fetch
- set result.textContent = joke


#### Loading

- set result equal to - 'Loading...'

#### Error Handling

- try/catch block
- set result equal to - 'There was an error..'

#### Check Status

- Fetch - only throws an error if cannot resolve
- Error response still a response
- check response.ok property
- throw new Error('Whoops!!! There was an error')
