# 👩🏾‍⚕️ Project: Complex API 2 - Med Spa

### Goal: Build a simple front-end app that uses data returned from one api to make a request to another api to create something that would be beneficial to a Med Spa.

### How to submit your code for review:

- Fork and clone this repo
- Create a new branch called answer
- Checkout answer branch
- Push to your fork
- Issue a pull request
- Your pull request description should contain the following:
  - (1 to 5 no 3) I completed the challenge
  - (1 to 5 no 3) I feel good about my code
  - Anything specific on which you want feedback!

Example:
```
I completed the challenge: 5
I feel good about my code: 4
I'm not sure if my constructors are setup cleanly...
```





fetch(' https://api.openuv.io/api/v1/uv?lat=:lat&lng=:lng&alt=:alt&dt=:dt', {
    headers: {
        'x-api-key': 'openuv-9gis2ihrmuhs9bz1-io'
    }
})
.then(response => response.json())
.then(data => {
    console.log(data)
})


