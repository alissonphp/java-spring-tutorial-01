# Java Tutorials: #01 Init with spring boot
#### Main goal:

- Install IDE [IntelliJ](https://www.jetbrains.com/pt-br/idea/)
- Start new spring project using [initializr](https://start.spring.io/)
- Setup REST dependencies
- Create new controller *Greeting* to map path GET /greeting
- Use *@RequestParam* to catch a request param
- Return a JSON body with wellcome message

#### References:

- [spring guide](https://spring.io/guides/gs/rest-service/)

#### Results:
```
> curl http://localhost:8080/greeting\?name\=Alisson
{"id":1,"content":"Hello, Alisson!"}
```