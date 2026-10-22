---
sidebar_position: 4
---

# Integration Tests

An integration test is a test that measures the interaction of multiple systems
or parts of your application. They are meant to test aspects like the requests and responses coming back from the server, changes to data implemented business logic. We’re not looking to test page interactivity here, which  can be found in the [end to end tests](../types/e2e-tests.md).

Integration tests can be found in the directory `spec/requests`.

You can run all integration tests with:

```shell
bundle exec rspec spec/requests
```

To run an individual file you can use:

```shell
bundle exec rspec spec/requests/stories_show_spec.rb
```

To run a specific test case you can use:

```shell
bundle exec rspec spec/requests/stories_show_spec.rb:10
```

keep as is.
