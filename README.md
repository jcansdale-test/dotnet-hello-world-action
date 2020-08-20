## A GitHub Action written using .NET Core

This is an example action written using .NET Core and invoked as a [composite action](https://github.com/jcansdale-test/dotnet-hello-world-action/blob/master/action.yml). It is published and tested in this [workflow](https://github.com/jcansdale-test/dotnet-hello-world-action/blob/master/.github/workflows/publish-and-test.yml).

A specific version can be executed like:

```yml
    - uses: jcansdale-test/dotnet-hello-world-action@v1.0.2
      with:
        who: Moon
```        

The latest version can be executed like:

```yml
    - uses: jcansdale-test/dotnet-hello-world-action@action
      with:
        who: Moon
```        

See [Creating a composite run steps action](https://docs.github.com/en/actions/creating-actions/creating-a-composite-run-steps-action).

