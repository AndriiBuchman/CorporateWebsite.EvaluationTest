# Corporate Website - Evaluation Test

**Please, commit your changes after each step.**
1. Clone the project.
2. Add `Web API 2.2` to the project and set it up.
3. Add `Ninject` to the project and set it up.
4. Create .NET Framework Class Library `CorporateWebsite.Repositories`.
- create `TestRepository` repository and its interface;
- create `GetMyFavouriteNames` method to `TestRepository` that returns list of strings (anything can be returned).
5. Create `TestController` controller.
- inject `TestRepository` into `TestController`;
- create _[GET]_`GetNames` action/endpoint that returns names from `GetMyFavouriteNames` repository method.
6. Set up routing to be able to call your endpoint `GetNames` by `https://localhost:*/test/names`
7. Push your changes.
